load "common/common.groovy"

 properties([
        parameters([
            string(name: 'testarg', defaultValue: 'DEFAULT', description: 'The target environment', )
        ])
    ])
    
node {
    
    checkout scm
   
    def common = load "common/echo.groovy"

    stage('Build') {
        common.echo2("${testarg}")
    }
    load 'Jenkinsfile_2'
}