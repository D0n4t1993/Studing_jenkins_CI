node('linux_node1_ssh') {
    node {
        stage('Build') {
            echo 'Building'
        }
        stage('Test') {
            echo 'Testing'
        }
        if (currentBuild.currentResult == 'SUCCESS') {
            stage('Deploy') {
                echo 'Deploying'
            }
        }
    }
}
