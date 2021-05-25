node{ 
   stage('Code Pull From Git'){
     git 'https://github.com/anandlahase/my-app'
   } 

   stage('Compile-Packages'){
     sh 'mvn package'
   }
} 
