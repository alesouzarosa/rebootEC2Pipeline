@Library('pipeline-commons') _

rebootEC2Pipeline {
    patternRule: /master/,
    schedule: "*/5 0 0 0 0"   /*cron format */,
    credentialIdAws: "AWS_JENKINS_CREDENTIALS",
    instanceId: "",
    awsRegion: "us-east-1"    
}