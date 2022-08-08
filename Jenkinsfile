pipeline{
    agent{
        label "slave01"
    }
    stages{
        stage("Check ansible version"){
            steps{
                echo "========executing A========"
                sh 'ansible --version'
                // sh 'ansible-playbook -i inventory playbook.yml'
            }
        }
    }
}