@Library('pipleline-library-demo')_

env.NODEJS_HOME = "${tool 'node'}"
env.PATH = "${env.NODEJS_HOME}/bin:${env.PATH}"

buildJavascriptApp deploy: false, {
        notify type: "slack", message: "Build succeeded"
    }