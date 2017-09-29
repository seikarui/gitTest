env.SCM_URL            = 'https://github.com/seikarui/gitTest.git'
env.SCM_BRANCH         = 'master'
env.LINUX_SLAVE        = 'linux-slave'

node(env.LINUX_SLAVE) {
    stage('Preparation') {
        sh "echo ${BASE_AMI}"
        sh "echo success."
    }
}

