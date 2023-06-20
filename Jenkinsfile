pipeline {
    evirontment {
        VERSION="1.0.0"
        GITHUB_CREDENTIAL = credentials("github-token")
    }

    agent any

    stage("build") {
        steps  {
            echo "building ${VERSION}"
        }
    }

    stage("test") {
        steps  {
            echo "testing"
        }
    }

    stage("deploy") {
        steps  {
            echo "deploying ${GITHUB_CREDENTIAL}"
        }
    }
}