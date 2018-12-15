#!/usr/bin/env groovy

properties([
    parameters([
        string(name: 'string_prop', defaultValue: "moo", description: 'some string prop')
    ]),
    disableConcurrentBuilds(),
])


pipeline {
  agent any

  stages {
    stage("Do Work") {
      steps {
        sh '''
          echo hello
        '''
      }
    }
  }
}
