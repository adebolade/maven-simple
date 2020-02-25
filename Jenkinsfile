node {
    stage("Checkout SCM") {
        tool name: 'maven-3.5.2', type: 'maven'
        git 'https://github.com/adebolade/maven-simple'
    }
    stage('Execute maven goal'){
        sh 'mvn package'
    }
}
