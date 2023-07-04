<div  align="center">
<h1>ARESIS2</h1>
<h2>coll_synthese.js</h2>
<h3>Réalisé par Sanchis Brian</h3>

<img  width="500"  alt="login"  src="/logo-sncf.jpg">
</div>

# qu'est ce que coll_synthese.js ?

**coll_synthese.js** est un fichier du dossier **collectes**.

Il a pour utilité principale d'afficher les différentes applications à décommissionner ou modifier.

# Auteur et versions

- Dimitri Lyonnet (DLT)
- Brian Sanchis (BS)
- created on 02-Mar-2020
- subVersion, 0.2.001 2020-05-19

# Langage, technologie et principale variable

**Langage et technologie utilisée :**

- JavaScipt (60%)
- HTML (15%)
- CSS, bootstrap (15%)
- XML (10%)

**Principal variables :**

- collecte : génération du HTML et du CSS (bootstrap)
- xmlList : liste des applications modifiées
- d.nom : nom de chaque application une par une
- count : compteur d'application affiché

# Déscription des différentes fonctions

- **fonction coll_listAppli_call()** -> appelle la fonction **coll_listAppli_Update()**

- **fonction coll_listAppli_Update()** -> permet de rafraîchir la page à partir du cache

- **fonction coll_listAppli_draw()** -> affichage des applications -> contient ->
	- **fonction load()** -> récupère la liste des applications modifiées ou décommissionner
	- Boucle for permettant de trier les applications modifiées.
	- Plusieurs conditions permettant de filtrer l'application
	- Plusieurs conditions permettant d'afficher uniquement les applications non-modifiées

# Installation

``git clone https://github.com/txttxttxttxttxttxt/txttxttxt``
<br>
``cd aresis2``
