node('linux_node1_ssh') {
    withEnv (['DISABLE_AUTH=true','DB_ENGINE=sqlite']){
        stage('BUILDWithEnvs'){
            echo 'DB engine is ${DB_ENGINE}'
            echo 'Disable auth is ${DISABLE_AUTH)'
            sh 'printenv
        }
    }
}
