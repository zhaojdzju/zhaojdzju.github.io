pipeline {
  agent any
  stages {
    stage('start') {
      steps {
        echo 'start jenkins pipeline '
        sh '''#!/bin/bash
echo \'hello world\''''
      }
    }

    stage('compile') {
      steps {
        sh '''#!/bin/bash
echo \'compile\''''
      }
    }

    stage('Test') {
      steps {
        echo 'test ok'
      }
    }

    stage('security scan') {
      steps {
        sh '''#!/bin/bash

echo \'hello\''''
      }
    }

  }
}