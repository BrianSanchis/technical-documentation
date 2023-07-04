<div  align="center">
<h1>ARESIS2</h1>
<h2>coll_synthese.js</h2>
<h3>Réalisé par Sanchis Brian</h3>

<img  width="500"  alt="login"  src="/logo-sncf.jpg">
</div>

# qu'est ce que coll_synthese.js ?

**coll_synthese.js** est un fichier du dossier **collectes**.

Il a pour utilisé principale d'afficher les différentes applications à décommissioner ou modifier.

# Auteur et versions
  
- Dimitri Lyonnet (DLT)
- Brian Sanchis (BS)
- created on 02-Mar-2020
- subVersion, 0.2.001 2020-05-19

# Langage, technologie et principal variable

**Langage et technologie utilisée :**

- JavaScipt (60%)
- HTML (15%)
- CSS, bootstrap (15%)
- XML (10%)

**Principal variables :**

- collecte : géneration du HTML et du CSS (bootstrap)
- xmlList : liste des applications modifiés
- nom : nom de chaque applications une par une
- count : compteur d'application affiché

# Déscription des différentes fonctions

-  **function coll_listAppli_call()** -> appele **coll_listAppli_Update()**

-  **function coll_listAppli_Update()** -> permet de rafraichir la page à partir du cache

-  **function coll_listAppli_draw()** -> affichage des applications -> contient ->
	- **function load()** -> récupère la liste des applications modifiés ou 	décommissionées
	- boucle for permettant de trier les applications modifiés
	- plusieurs condiftions permettant de filtrer l'application
	- plusieurs conditions, si l'application n'est pas modifié, alors on génere le contenu de l'application

# Installation

``git clone https://github.com/txttxttxttxttxttxt/txttxttxt``

<br>

``cd aresis2``
