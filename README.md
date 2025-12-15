etape 1 : Création d'un compte GitHub par personne                                                      
etape 2 : Création d'un fichier Algobox par l'un des membres du groupe puis insertion dans GitHub                                    
etape 3 : Ajout des collaborateurs par le créateur du fichier grâce au pseudo GitHub                                 
etape 4 : Acceptation des invitations, les modifications peuvent commencer                                  
etape 5 : Récupérartion du fichier de départ grâce aux commandes suivantes :                                              
cd $env:USERPROFILE\Documents                                           
git clone https://github.com/BoeciaMagnien/TP_github/TP_github_algobox.git                                                         
etape 6 : Modification du programme Algobox et partage des nouveaux programmes grâce au code suivant :                                    
git pull origin main                                             
git add TP.alg                                                   
git push origin main                                                
etape 7 : Création d'un conflit à la ligne 14 en écrivant 2 lignes différentes                                                
etape 8 : Ouverture du code dans le bloc note pour retirer les erreurs et les marqueurs "<<<<<<<", "=======" et ">>>>>>>"                                      
etape 9 : Réouverture du fichier sur algobox après resolution du problème :                                                 
git merge --abort                                               
git reset --hard origin/main                                           
git pull origin main                                              
