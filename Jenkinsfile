node {
    stage("clone"){
        git url: "https://github.com/VladimirKogan/project1.git", branch:"feature1"
    }
    stage("Show file"){
        sh "python mhyapp.py"
    }
}