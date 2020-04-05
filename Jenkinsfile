pipeline {
    agent { label 'Ansible-Con' }
    stages { 
        stage ("Linux-Patching") {
            steps {
                sh "ansible-playbook linux-patch.yml"
            }
        }   
    }
}
