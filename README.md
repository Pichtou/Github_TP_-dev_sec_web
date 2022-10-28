# Github_TP_dev_sec_web

## Automatisatisaion avec trivy 

### Trivy est un scanner de vulnérabilité pour les conteneurs qui se veut simple et complet.
#### Liste des réalisations à cette étape : 

● Création de l’arborescence pour le bon fonctionnement de Github Actions

● Automatisation des tests de sécurité avec Trivy à l'aide d'une Github Actions

○ Scanner les images docker:  
■ DVWA  - ici on a choisi l'image officiel de DVWA situé dans vulnerales/dvwa dans Dockerhub  
■ Nginx  - image officiel du package nginx  
■ Une autre image de votre choix  - ici on a choisi l'image du package alpine   

## Automatisation avec TF Sec  

### Cette  deuxième étape consiste à analyser du code Terraform vulnérable avec le logiciel TFSec via Github Actions.  
### TFSec est un SAST (Static Analysis Security Testing) principalement dédié à Terraform.  
Cet outil est capable d’analyser le code Terraform pour en déduire les potentielles faiblesses de sécurité de nos infrastructures, et cela avant même qu’elles soient déployées.  

De nombreux projets vulnérable sont disponibles sur GITHUB ainsi pour tester cet outils le code Terrafom suivant sera utiliser:  
● https://github.com/bridgecrewio/terragoat  

TerraGoat est le référentiel Terraform « Vulnerable by Design » de Bridgecrew.  
TerraGoat est un projet d’apprentissage et de formation qui démontre comment des erreurs de configuration courantes peuvent se retrouver dans les environnements cloud de production.  



