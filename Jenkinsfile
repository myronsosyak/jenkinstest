node {
    
    checkout scm
    
    parameters {
        booleanParam(defaultValue: true, description: 'dsgfdsgfdgdf', name: 'testarg', defaultValue: 'DEFAULT')
    }

    def common = load "common/echo.groovy"

    stage('Build') {
        common.echo2("${testarg}")
    }
    load 'Jenkinsfile_2'
}