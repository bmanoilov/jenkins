simpleBuild {

    machine = "hi-speed"
    docker = "java:1.9"

    env = [
        FOO : 42,
        BAR : "YASS"
    ]

    git_repo = "https://github.com/cloudbeers/PR-demo"

    before_script = "echo before"
    script = 'echo after $FOO'
    after_script = 'echo done now'

    notifications = [
        email : "mneale@cloudbees.com"
    ]

}

# pipeline {
#     agent any
# 
#     stages {
#         stage('Build') {
#             steps {
#                 echo 'Building..'
#             }
#         }
#         stage('Test') {
#             steps {
#                 echo 'Testing..'
#             }
#         }
#         stage('Deploy') {
#             steps {
#                 echo 'Deploying....'
#             }
#         }
#     }
# }
