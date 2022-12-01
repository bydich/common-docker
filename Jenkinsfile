#!/usr/bin/env groovy

dockerfile {
    nodeLabel = 'docker-debian-jdk8-compose'
    dockerPush = true
    usePackages = true
    dockerRepos = ['confluentinc/cp-base-new', 'confluentinc/cp-jmxterm']
    slackChannel = '#tools-notifications'
    mvnSkipDeploy = true
    cron = ''
    cpImages = true
    osTypes = ['deb9', 'ubi8']
    disableConcurrentBuilds = true
}
