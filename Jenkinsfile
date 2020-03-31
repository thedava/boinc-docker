node {
    checkout scm
    stage('Lint') {
        sh 'find . -name "*.sh"   -print0 | xargs -l1 -0 shellcheck -s bash'
        sh 'find . -name "*.yml"  -print0 | xargs -l1 -0 yamllint'
    }
}
