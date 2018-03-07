#!/usr/bin/env groovy


node{
    checkout scm
    stage 'build'
    // sshagent('a4823767-c3da-4c6c-a6ee-a2d0cbf68199'){
        sh 'cat index.html'
    // }
}

node{
    stage 'deploy'
    // sshagent('a4823767-c3da-4c6c-a6ee-a2d0cbf68199'){
        sh 'cat README.md'
    // }
}
