@Library('org-shared-library') _

node {
    standardPipeline(
        artifactId: 'enterprise-web-app',
        groupId: 'com.org.demo',
        version: '1.0.0',
        nexusUrl: '107.178.223.130:8081',
        nexusCreds: 'nexus_auth',
        devUrl: 'http://107.178.223.130:8080',
        devCreds: 'tomcat_cred2',
        prodUrl: 'http://34.31.196.184:8080',
        prodCreds: 'tomcat_cred3'
    )
}

