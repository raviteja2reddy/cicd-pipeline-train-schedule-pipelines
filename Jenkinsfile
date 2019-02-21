pipeline
{
agent any
stages ('Build')
{
steps
{
echo "Running Build Automation"
sh './gradlew build --no-deamon'
archiveArtifacts artifacts: 'dist/trainSchedule.zip'
}
}
}
