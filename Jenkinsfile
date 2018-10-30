node("windows") {

    stage("checkout"){
        git credentialsId: '3ca1550f-d21c-4a7c-ae5b-bce851eac92d', url: 'https://github.com/bols-blue-org/build-gocv-win.git'
    }
    stage("build"){
        bat ".\\gocv.bat"
    }
}
