---
layout: page
title: Doc. Vitam UI
fatherref: documentation
---

> Est ici présentée la documentation de Vitam UI.

Naviguer dans la documentation par domaine :
* [Organisation et droits utilisateurs](#orga)
* [Référentiels](#referentiels)
* [Sécurité et droits applicatifs](#secu)
* [Supervision et audit](#supervision)
* [Versement et consultation](#versement)

Documentation générale
* **Vitam UI : documentation produit** ([pdf](/ressources/DocCourante/autres/fonctionnel/VitamUI_Doc_produit.pdf))
* **Vitam UI : guide de prise en main** ([pdf](/ressources/DocCourante/autres/fonctionnel/VitamUI_Guide_de_prise_en_main.pdf))
* **Vitam UI : jeu de tests pour prise en main** ([zip](https://download.programmevitam.fr/jeux_de_tests/v6/Jeux_de_tests_Guide_de_prise_en_main_VitamUI.zip))

## Guide de lecture de la documentation Vitam UI


### Domaine : organisation et droits utilisateurs<a name="orga">   
![Logos](/public/images/VitamUI_organisation.JPG){: style="display: block; margin-left: auto; margin-right: auto; height:30rem"} 

<table>
	<tr>
		<th>Ordre d'exécution</th>
		<th>Je souhaite... </th>
		<th>Je suis... </th>
		<th>APP Vitam UI</th>
	</tr>
	<tr>
		<td>1.1 (obligatoire)</td>
		<td>... créer une nouvelle organisation utilisatrice de Vitam UI et lui associer 1 ou plusieurs coffre(s)</td>
		<td>administrateur d'instance (si vous exposez Vitam UI en tant que service), administrateur technique VitamUI (si vous utilisez Vitam UI hébergé en propre)</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Organisation.pdf">Organisation</a></td>
	</tr>
	<tr>
		<td>1.2 (obligatoire)</td>
		<td>... créer le compte nominatif de l'administrateur fonctionnel d'une organisation à des fins d'activation et prendre la main sur la session d'un utilisateur à des fins de support</td>
		<td>administrateur d'instance (si vous exposez Vitam UI en tant que service), administrateur technique VitamUI (si vous utilisez Vitam UI hébergé en propre)</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Subrogation.pdf">Subrogation</a></td>
	</tr>
	<tr>
		<td>1.2 (facultatif)</td>
		<td>... définir des droits fins sur les utilisateurs de mon organisation en créant un nouveau profil de droits</td>
		<td>administrateur fonctionnel Vitam UI</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Profil_APP_Utilisateur.pdf">Profil APP Utilisateur</a></td>
	</tr>
	<tr>
		<td>1.3 (obligatoire sauf si le groupe existe déjà)</td>
		<td>... définir des regroupements de droits sur les APPs Vitam UI pour mes utilisateurs en créant un nouveau groupe de profils</td>
		<td>administrateur fonctionnel Vitam UI</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Groupe_profil.pdf">Groupes de profils</a></td>
	</tr>
	<tr>
		<td>1.4 (obligatoire sauf si le groupe existe déjà)</td>
		<td>... créer mes utilisateurs et leur attribuer des droits</td>
		<td>administrateur fonctionnel Vitam UI</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Utilisateur.pdf">Utilisateur</a></td>
	</tr>
		<tr>
		<td>NA</td>
		<td>... paramétrer des profils de droits permettant d’associer un contrat d’accès à un utilisateur</td>
		<td>administrateur fonctionnel Vitam UI</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Profil_APP_Parametrages_externes.pdf">Profil APP Paramétrages externes</a></td>
	</tr>
		<tr>
		<td>NA</td>
		<td>... Créer de nouveaux profils de niveaux inférieurs, limiter l’attribution de profils à une portée d’utilisateurs et adapter la séparation des rôles</td>
		<td>opérateur d'instance</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Hierarchisation_profils.pdf">APP Hiérarchisation des profils</a></td>
	</tr>
</table>




### Domaine : référentiels<a name="referentiels">  
![Logos](/public/images/VitamUI_referentiels.JPG){: style="display: block; margin-left: auto; margin-right: auto; height:30rem"}

<table>
	<tr>
		<th>Ordre d'exécution</th>
		<th>Je souhaite... </th>
		<th>Je suis... </th>
		<th>APP Vitam UI</th>
	</tr>
	<tr>
		<td>2.1 (obligatoire)</td>
		<td>... déclarer un nouveau service producteur ou un nouveau service versant dans Vitam UI</td>
		<td>administrateur fonctionnel Vitam UI</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Services_agents.pdf">Services agents</a></td>
	</tr>
	<tr>
		<td>2.2 (obligatoire)</td>
		<td>... déclarer des nouvelles règles de gestion</td>
		<td>administrateur fonctionnel Vitam UI</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Regles_gestion.pdf">Règles de gestion</a></td>
	</tr>
	<tr>
		<td>2.3 (facultatif)</td>
		<td>... créer et modifier un profil d’archivage (PA) ou un profil d’unité archivistique (PUA), créer et modifier une notice d’un profil, importer et exporter un profil d’archivage</td>
		<td>administrateur fonctionnel Vitam UI</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Profils_documentaires.pdf">Profils documentaires</a></td>
	</tr>
	<tr>
		<td>2.4 (facultatif)</td>
		<td>... déclarer un nouveau format non présent dans le référentiel PRONOM</td>
		<td>administrateur technique Vitam UI</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Formats_fichiers.pdf">Formats de fichier</a></td>
	</tr>
	<tr>
		<td>2.5 (facultatif)</td>
		<td>... déclarer un nouveau vocabulaire non présent dans l'ontologie SEDA</td>
		<td>administrateur technique Vitam UI</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Ontologie.pdf">Ontologie</a></td>
	</tr>
	<tr>
		<td>2.6 (facultatif)</td>
		<td>... importer un arbre de positionnement ou un plan de classement</td>
		<td>administrateur fonctionnel Vitam UI</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Arbres_plans.pdf">Arbres et plans</a></td>
	</tr>
	<tr>
		<td>2.7 (facultatif)</td>
			<td>... rechercher et consulter un contrat de gestion, le créer et le mettre à jour</td>
		<td>administrateur fonctionnel Vitam UI</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Contrat_gestion.pdf">Contrats de gestion</a></td>
</table>  
  



### Domaine : Sécurité et droits applicatifs<a name="secu">  
![Logos](/public/images/VitamUI_securite.JPG){: style="display: block; margin-left: auto; margin-right: auto; height:30rem"}  


<table>
	<tr>
		<th>Ordre d'exécution</th>
		<th>Je souhaite... </th>
		<th>Je suis... </th>
		<th>APP Vitam UI</th>
	</tr>
	<tr>
		<td>3.1 (obligatoire sauf si le contrat existe déjà)</td>
		<td>... paramétrer des droits pour le versement d'archives dans un coffre par une nouvelle application</td>
		<td>administrateur fonctionnel Vitam UI</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Contrat_entree.pdf">Contrat d'entrée</a></td>
	</tr>
	<tr>
		<td>3.2 (obligatoire sauf si le contrat existe déjà)</td>
		<td>... paramétrer des droits pour la consultation ou mise à jour d'archives dans un coffre par une nouvelle application</td>
		<td>administrateur fonctionnel Vitam UI</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Contrat_acces.pdf">Contrat d'accès</a></td>
	</tr>
	<tr>
		<td>3.3 (obligatoire sauf si le contrat existe déjà)</td>
		<td>... définir les droits d'une nouvelle application sur les services exposés par Vitam</td>
		<td>administrateur technique Vitam UI</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Profil_securite.pdf">Profil de sécurité</a></td>
	</tr>
	<tr>
		<td>3.4 (obligatoire sauf si le contrat existe déjà)</td>
		<td>... authentifier une nouvelle application interconnectée avec Vitam et lui attribuer des droits</td>
		<td>administrateur technique Vitam UI</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Contexte_applicatif.pdf">Contexte applicatif</a></td>
	</tr>
</table>

 

### Domaine : supervision et audit<a name="supervision"> 
![Logos](/public/images/VitamUI_supervision.JPG){: style="display: block; margin-left: auto; margin-right: auto; height:30rem"}  


<table>
	<tr>
		<th>Je souhaite... </th>
		<th>Je suis... </th>
		<th>APP Vitam UI</th>
	</tr>
	<tr>
		<td>... consulter le journal des opérations VITAM (entrées, éliminations et données de base)</td>
		<td>administrateur technique Vitam UI ou administrateur fonctionnel Vitam UI</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Journal_operations.pdf">Journal des opérations</a></td>
	</tr>
	<tr>
		<td>... visualiser les opérations de sécurisation et accéder aux journaux du cycle de vie des objets</td>
		<td>administrateur technique Vitam UI</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Operations_securisation.pdf">Opérations de sécurisation</a></td>
	</tr>
	<tr>
		<td>... effectuer des requêtes complexes sur les bases de données documentaires en vue de retrouver des objets</td>
		<td>administrateur technique Vitam UI</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_RequetesDSL.pdf">Requêtes DSL</a></td>
	</tr>
	<tr>
		<td>... vérifier la conformité de la conservation de mes archives</td>
		<td>administrateur fonctionnel Vitam UI, super-archiviste</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Audit.pdf">Audit</a></td>
	</tr>
	<tr>
		<td>... produire un relevé de valeur probante sur une ou plusieurs de mes archives électroniques</td>
		<td>administrateur fonctionnel Vitam UI, super-archiviste</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Releve_valeur_probante.pdf">Relevé de valeur probante</a></td>
	</tr>
	<tr>
		<td>... gérer des opérations et interagir sur les étapes du workflow des opérations</td>
		<td>administrateur fonctionnel Vitam UI, super-archiviste</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Gestion_operations.pdf">Gestion des opérations</a></td>
	</tr>
</table>




### Domaine : versement et consultation<a name="versement">
![Logos](/public/images/VitamUI_versement.JPG){: style="display: block; margin-left: auto; margin-right: auto; height:30rem"}  


<table>
	<tr>
		<th>Je souhaite... </th>
		<th>Je suis... </th>
		<th>APP Vitam UI</th>
	</tr>
	<tr>
		<td>... créer un projet de versement, consulter et rechercher les unités archivistiques liées à un versement, ajouter des métadonnées descriptives et de gestion des unités archivistiques, consulter, valider, transférer les versements liés à un projet</td>
		<td>archiviste</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Collecte_et_preparation_des_versements.pdf">Collecte et préparation des versements</a></td>
	</tr>
	<tr>
		<td>... déposer un lot d'archives dans le SAE et en visualiser l'entrée</td>
		<td>archiviste</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Depot_et_suivi_versements.pdf">Dépôt et suivi des versements</a></td>
	</tr>
	<tr>
		<td>... rechercher et télécharger des unités archivistiques contenues dans le SAE</td>
		<td>archiviste</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Recherche_et_consultation.pdf">Recherche et consultation des archives</a></td>
	</tr>
	<tr>
	</tr>
	<tr>
		<td>...consulter et rechercher dans le registre des fonds</td>
		<td> archiviste</td>
		<td><a href="https://www.programmevitam.fr/ressources/DocCourante/autres/fonctionnel/VitamUI_DocAPP_Registre_des_fonds.pdf">Registre des fonds</a></td>
			</tr>
</table>