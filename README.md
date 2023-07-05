<div  align="center">
<h1>ARESIS2</h1>
<h2>coll_synthese.js</h2>
<h3>Réalisé par Sanchis Brian</h3>

<picture>
  <source media="(max-width: 767px)" srcset="">
  <img align="center" alt="" src="/LOGO_SNCF_GROUPE_RVB.png" width=400px>
</picture>

</div>

# Qu'est-ce que coll_synthese.js ?

**coll_synthese.js** est un fichier du dossier **collectes**.

Il a pour utilité principale d'afficher les différentes applications à décommissionner ou modifier.

# Auteurs et versions

- Dimitri Lyonnet (DLT)
- Brian Sanchis (BS)
- created on 02-Mar-2020
- subVersion, 0.2.001 2020-05-19

# Langages, technologies et principales variables

**Langages et technologies utilisées :**

![HTML5](https://img.shields.io/badge/HTML5%20-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) 

![CSS3](https://img.shields.io/badge/CSS%20-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) 

![JavaScript](https://img.shields.io/badge/JavaScript%20-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black) 

XML (Extensible Markup Language)

**Principales variables :**

- collecte : génération du HTML et du CSS (bootstrap)
- xmlList : liste des applications modifiées
- d.nom : nom de chaque application une par une
- count : compteur d'application affiché

# Déscription des différentes fonctions

- **fonction coll_listAppli_call()** -> appelle la fonction **coll_listAppli_Update()**

- **fonction coll_listAppli_Update()** -> Elle prend un paramètre ***bCache*** qui indique si le cache doit être utilisé lors du chargement de la page -> Permet de rafraîchir la page à partir du cache.

- **fonction coll_listAppli_draw()** -> affichage des applications -> contient ->
	- **fonction load()**  
		- effectue une requête ***AJAX*** en utilisant l'objet ***XMLHttpRequest*** pour récupérer des données à partir de l'URL spécifiée -> 
		- récupère la liste des applications modifiées ou décommissionner.
	- ***Boucle for*** parcourant la liste des applicatifs modifiés pour la comparer avec l'applicatif généré 
		- permet de trier les applications modifiées.
	- Plusieurs conditions prenant en compte les détails d'une application 
		- permet de filtrer l'application à afficher
	- Plusieurs conditions prenant en compte les filtres 
		- permet d'afficher uniquement les applications non-modifiées

# Installation

``git clone https://github.com/txttxttxttxttxttxt/txttxttxt``
<br>
``cd aresis2``
