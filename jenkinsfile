node{
  stage("download repo"){
        git branch: 'main', url: 'https://github.com/docdoom12345/multibranch-jenkins.git'
    }
 stage("display file content"){
   sh """#!/bin/bash
   cat sample.txt
   """
}
}
