pipeline{
agent any
stages{
stage('Build') {
steps {
echo 'running bulid automatio'
sh'./gradle build --no-daemon'
archiveArtifacts artifactes:'dist/trainsSchedule.zip'
} }
}
}
