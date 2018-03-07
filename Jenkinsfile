#!/usr/bin/env groovy

checkout scm
node{
    stage 'build'
    sh 'cat index.html'
}

node{
    stage 'deploy'
    sh 'cat README.md'
}
