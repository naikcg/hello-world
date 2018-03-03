#!/usr/bin/env groovy

stage 'build'
node{
    checkout scm
    sh 'cat index.html'
}
stage 'deploy'
node{
    checkout scm
    sh 'cat README.md'
}
