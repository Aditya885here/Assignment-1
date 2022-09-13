pipeline {
agent {
label { label '172.31.26.79'
}
}
stages {
stage ('slave1-httpd') {

steps {
dir ('/mnt') {
sh "git clone https://github.com/Aditya885here/assignment1.git -b 22Q1"
}
}
}
}
}
