#!/usr/bin/env groovy


node{
    checkout scm
    stage 'build'
    sh 'cat index.html'
}

node{
    stage 'deploy'
    sh 'cat README.md'
}
