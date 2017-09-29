env.SCM_URL            = 'https://github.com/seikarui/gitTest.git'
env.SCM_BRANCH         = 'master'
env.LINUX_SLAVE        = 'linux-slave'

node(env.LINUX_SLAVE) {
    stage('Preparation') {
        sh "echo ${env.BASE_AMI}"
        sh "echo add post commit."
        sh "echo success."
    }
}

