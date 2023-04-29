## Compte Rendu: HospitalApplication
## Auteur: 
ELHARDI khadija
## Plan:
* Introduction
L'idée de cette application est de créer un système de gestion de patients utilisant Spring Boot et JPA pour la persistance des données. L'application permet aux administrateurs de gérer les informations des patients, tandis que les utilisateurs simples peuvent seulement visualiser la liste des patients. Les fonctionnalités principales de l'application incluent l'ajout, la suppression, et la modification des patients, ainsi que l'affichage des patients dans un tableau.

Pour faciliter la visualisation des patients, l'application fournira une fonctionnalité d'affichage paginé des patients dans un tableau. Cela permettra aux utilisateurs de naviguer à travers la liste des patients de manière conviviale et de rechercher des patients spécifiques en utilisant des filtres tels que le nom, le prénom, ou d'autres critères.

L'application permettra aux administrateurs de se connecter à un compte sécurisé avec des autorisations spécifiques pour effectuer des opérations de gestion des patients. Une fois connecté, l'administrateur pourra ajouter de nouveaux patients en fournissant des informations. Les administrateurs auront également la possibilité de modifier les informations des patients existants.

En outre, l'application offrira la possibilité aux administrateurs de supprimer les patients du système si nécessaire. La suppression des patients sera gérée de manière sécurisée, en s'assurant que seuls les administrateurs autorisés peuvent effectuer cette opération.

Il est important de noter que seuls les administrateurs auront la possibilité d'effectuer des opérations de modification ou de suppression des patients, tandis que les utilisateurs simples pourront uniquement visualiser la liste des patients sans pouvoir effectuer de modifications.

* Systeme d'authentification
+ pour se connecter à l'application il faut saisair le nom et le mot de passe:

![AppScreenshot](/image/formulaireAuthentification.PNG)
* Interface Admin:
+ Après la connexion à l'application il vous affiche cet interface qui contient les informations sur les patients avec l'action modifier et supprimer
+ pour supprimer un patient il faut cliquez sur le button supprimer.

+ pour modifier un patient il faut cliquez sur le button modifier
![AppScreenshot](/image/InterfaceAdmin.PNG)
* Ajout d'un patient:
+ pour ajouter un patient il faut remplir le formulaire ci dessous
![AppScreenshot](/image/formulaireAjout.PNG)
* Modification d'un patient
+ Après le clique sur le button modifier il nous affiche ce formulaire:

![AppScreenshot](/image/formulaireModification.PNG)
* Chercher un patient
+ pour chercher un patient par son nom on tape le nom dans la barre de recherche:

![AppScreenshot](/image/chercherparKey.PNG)
* Conclusion
Cette application utilise le framework Spring Boot pour créer une application Java autonome, avec des dépendances minimales et une configuration simplifiée. 
Spring Security est également utilisé pour assurer la sécurité des données des patients et limiter l'accès aux utilisateurs autorisés.
 Les utilisateurs doivent se connecter avec leurs identifiants pour accéder à l'application et les rôles d'utilisateur peuvent être utilisés pour limiter l'accès aux fonctions de l'application.

