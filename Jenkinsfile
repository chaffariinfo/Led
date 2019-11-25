node{
             
                
            
             stage('phase de validation de code') 
                          { 
                          echo 'phase de validation de code '
                          bat 'mvn validate'
                        }
             stage('phase de compilation') 
                          { 
                          echo 'phase de compilation '
                          bat 'mvn compile'
                        }
             stage('phase de test') 
                          { 
                          echo 'phase de test '
                          bat 'mvn test'
                        }
             stage('phase de paqueetage') 
                          { 
                          echo 'phase de packetage  '
                          bat 'mvn package'
                        }
             stage('phase d_intallation de package dans votre RL') 
                          { 
                          echo 'phase d_intallation de pachake dans votre RL '
                          bat 'mvn validate'
                        }
               stage('phase de deploiement d_un artefact dans le referentiel distant') 
                          { 
                          echo 'phase de déploiement d_un artefact dans le référentiel distant'
                          bat 'mvn deploy'
                        }
 }
      
     
