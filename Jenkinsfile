node {
    stage("clone"){
        git url: "https://github.com/VladimirKogan/project1.git", branch:"master"
    }
    stage("Show file"){
        sh "python mhyapp.py"
    }
}