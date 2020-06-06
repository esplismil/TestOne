#!groovy
import groovy.json.JsonSlurperClassic
node {
    echo 'This is new commit and auto triggered 123 '
    echo 'Master branch'    
    echo '------------------------------'
    echo scm.branches[0].name
    checkout scm
    echo scm.branches[0].name
    branchname=scm.branches[0].name
    echo branchname
}
