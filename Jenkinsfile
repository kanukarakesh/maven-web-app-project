node 
{
    stage('git chekout')
    {
     git credentialsId: '545009842403', url: 'https://github.com/kanukarakesh/maven-web-app-project.git'
    }
    stage('build')
    {
     //sh "${mavenHome}/bin/mvn clean package"
    }
    stage ('compile')
    {
     //sh "${mavenHome}/bin/mvn clean compile"
    }
    stage ('SQ REPORT')
    {
     //sh "${mavenHome}/bin/mvn clean sonar:sonar"
    }
}

