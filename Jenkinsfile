pipeline {
    agent any
    stages {
        stage('fetching code from github'){
          steps {
            git url: 'https://github.com/sulavbasukala1/jenkins-ansible.git'
    }
}
        stage ('building code'){
          steps {
    sh 'ansible-playbook -i inventory playbook.yml'
}
}
    }
}



        
