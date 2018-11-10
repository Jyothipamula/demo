node {
    def mvnhome
    stage ("checkout")
{
    git 'https://github.com/Jyothipamula/course-1.git'
}
    mvnhome= tool 'MAVEN_HOME'
    stage ("compilation")
 {
     sh "'${mvnhome}/bin/mvn' compile"
 }   
stage ("packging")
{
    sh "'${mvnhome}/bin/mvn' package"
}
stage ("result")
{
    echo "succesful"
}
    }
