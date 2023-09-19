pipeline       //it starts with pipeline keyword

{
agent any       //any: run stages on any available agent
stages          //it contains stages

{
 stage ('print something')                //stage name
 { steps { sh 'echo Hello_Jenkins' } }    //

 stage ('build')
 { steps { sh 'echo build the code'} }

 stage ('deploye')
 { steps {sh 'echo deploying code'} }


}
}
