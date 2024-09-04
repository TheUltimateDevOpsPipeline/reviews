/* groovylint-disable-next-line CompileStatic, NoDef, UnusedVariable, VariableName, VariableTypeRequired */
@Library('PipelineUtils@dev') _

def utils = new org.bookinfo.pipeline.PipelineUtils(this)

utils.runPipeline(
    buildType: 'gradle', // or 'maven', 'ant', 'nodejs'
    buildCommand: 'gradle build'
    groupId: 'com.bookinfo',
    skipBuild: true,
    skipNexusUpload: true,
    artifactId: 'reviews',
    version: '1.0',
    filePath: 'target/reviews-application-1.0.war',
    // imageName: 'your-image-name',
    // chartPath: 'path/to/chart',
    // values: [image: 'your-image-name', tag: '1.0.0'],
    // additionalContainers: [
    //     [name: 'nodejs', image: 'node:16-alpine', ttyEnabled: true],
    //     [name: 'python', image: 'python:3.9-alpine', ttyEnabled: true]
    // ]
)

