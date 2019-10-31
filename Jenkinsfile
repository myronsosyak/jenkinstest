node {
    checkout scm
    
    parameters {
        booleanParam(defaultValue: true, description: 'dsgfdsgfdgdf', name: 'userFlag')
    }

    def common = load "common/echo.groovy"

    stage('Build') {
        common.echo2('Building....')
    }
    load 'Jenkinsfile_2'
}