pipeline{
    agent any
    parameters {
      string defaultValue: 'shahul', description: 'choose your name ', name: 'name'
      string defaultValue: 'Snehatheeram', description: 'choose your locality', name: 'locality'
   }
   stages{
       stage("param demo"){
           steps{
               echo "Hi ${name} Welcome to PALAKKAD ${locality}"
           }
       }
   }    
}
