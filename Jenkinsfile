#!groovy
def branch_name = "PR-123"
def change_target = "sandbox"

def x = branch_name =~ /^(sandbox|development|release.*)$/ &&  change_target =~ /^(sandbox|development|release.*)$/

println('teszt1')
println(x==1 ? 'true' : 'false')
println(x=="cica" ? 'true' : 'false')

branch_name = "release"
x = branch_name ==~ /^(sandbox|development|release.*)$/ &&  change_target ==~ /^(sandbox|development|release.*)$/

println('teszt2')
println(x ? 'true' : 'false')
println(x ? 'true' : 'false')




// pipeline {
//     agent any
//     stages {
//         stage('Build') {
//             steps {
//                 sh 'echo "Hello World"'
//                 sh '''
//                     echo "Multiline shell steps works too"
//                     ls -lah
//                 '''  
//             }
//         }
//     }
// }