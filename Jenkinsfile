node('linux_node1_ssh') {
    stage('Deploy') {
        retry(3) {
            sh './flakey-deploy.sh'
        }

        timeout(time: 3, unit: 'MINUTES') {
            sh './health-check.sh'
        }
    }
}
