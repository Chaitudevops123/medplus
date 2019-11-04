node
{
    stage("checkout scm") {
        git credentialsId: 'git_cred', url: 'https://github.com/Chaitudevops123/medplus.git'
    }
    stage("build") {
        sh 'mvn clean package'
    }
}

