pipeline {
agent {
label { label '172.31.20.233'
}
}
stages {
stage ('slave2-httpd') {

steps {
dir ('/mnt') {
sh "git clone https://github.com/Aditya885here/assignment1.git -b 22Q2"
}
}
}
}
}
