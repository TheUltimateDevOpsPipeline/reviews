@Library('PipelineUtils@dev') _

def utils = new org.bookinfo.pipeline.PipelineUtils(this)
utils.runPipeline(
    buildType: 'gradle', // or 'maven', 'ant', 'nodejs'
    buildCommand: 'gradle build',
    sonarQubeBinariesPath: 'reviews-application/build/classes/',
    groupId: 'com.bookinfo',
    artifactId: 'reviews',
    version: '1.0',
    filePath: 'reviews-wlpcfg/servers/LibertyProjectServer/apps/reviews-application-1.0.war',
)

