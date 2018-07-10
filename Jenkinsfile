import jenkins.automation.builders.PipelineJobBuilder
def PROJECT_NAME = "Hema"
def script = """
    pipeline {
        agent { label 'master' }
        stages {
            stage('hello') {
                steps {
                    sh 'echo "Hello World"'
                }
            }
        }
    }
