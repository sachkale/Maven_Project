pipeline {
agent any
parameters {
string(name: 'Greeting'\n defaultValue: 'Hello'\n description: 'How should I
greet the world?')\n
}
stages {
stage('Example') {
steps {
echo "${params.Greeting} World!"
}
}
}
}
