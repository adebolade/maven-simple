node {
    stage("Checkout SCM") {
        git 'https://github.com/adebolade/maven-simple'
    }
    stage('Execute maven goal'){
        def mvnHome = tool name: 'maven-3.5.2', type: 'maven'
        sh "${mvnHome}/bin/mvn clean package -e -B"
    }
}
