#!groovy
@Library('lts-basic-pipeline@artifactory') _

// projName: The directory name for the project on the servers for it's docker/config files
// intTestPort: port of integration test container
// intTestEndpoints: List of integration test endpoints i.e. ['healthcheck/', 'another/example/']
// default values: slackChannel = "lts-jenkins-notifications"

def endpoints = []
ltsBasicPipeline.call("dais-notifier", "DAIS", "hdc3a", "10587", endpoints, "hdc-3a")
