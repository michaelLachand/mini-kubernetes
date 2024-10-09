Déployez Wordpress à l’aide de manifests. 

* Créez un deployment mysql avec un seul replicat 

* Créez un service de type clusterIP pour exposer votre pod mysql 

* Créez un deployment wordpress avec les bonnes variables d’environnemet pour se connecter à la base de données 

* Votre deployment devra stocker les données de wordpress sur un volume mounté dans le /data de votre noeud 

* Créez un service de type nodeport pour exposer le frontend wordpress

<img width="470" alt="image" src="https://github.com/user-attachments/assets/c8b158e5-72f6-4843-b663-ce9a0499036d">


