1 Partie <head>
# balise html lang="Default"
--> remplacé par langue="fr".


# balise les mots-clés dans la balise "meta keywords" ne correspond pas parfaitement au contenu du site et il a bcp de répétition, en plus, c'est une agence à Lyon, pas à Paris. il faut préciser et varier les mots-clés plus pertinents.
--> remplacé par exemple : "seo, site web, agence de webdesign, agence desigon, Lyon, objectifs commerciaux, illustration, création du site, conception".


# il manque la description dans la balise "meta description"
--> On peut ajouter "L'agence le Cerf est l'une des meilleurs agence de webdesign de Lyon, qui aide les entreprise à devenir attractives sur Internet". 

# il manque un titre
--> Agence le Cerf-Une agence de Webdesign.

2 Partie 
# les balise ne sont pas sémantiques, au lieu d'utiliser "header, section, main et footer" etc., j'ai vu que le ".container" va du haut jusqu'au bas, pour le SEO, c'est confuse pour attraper les info pertinentes.

2.1 bloc-0 
 <header>
 # je supprime la partie ".navbar-header", car c'est black hat".

 # Dans la partie ".navbar-header", pour l'image de logo, il faut corriger la localisation d'agence dans "alt" pour optimiser la capturtation correcte des info.
 --> alt=""Lyon web design logo agence web meilleure agence".

 # dans le <div class="collapse navbar-collapse navbar-1 special-dropdown-nav">, le deuxième item de navigation n'est pas clair.
 -->remplacer "page 2" par "Contactez-nous" par exemple.

 2.2 Bloc-1-présenttion

 # Le même problème sur alt, c'est à Lyon, il faut pas donner les fausse infos pour SEO. et je renomme le nom de l'image logo (logo-agence du Cerf.png)pour optimiser SEO.
 --> alt="Agence le Cerf, agence web Lyon, création logo Lyon"
     je corrige la taille de logo pour être plus visible pour les visiteurs

# Dans le <h1> je corrige la couleur en blanc, car la couleur en #896cf3 n'est pas lisible.

2.3 Bloc-2-Service 
# dans cette partir, je remplace "paris" par "lyon" dans l'alt des images,  même erreur comme ci-dessus
--> <img alt="agence web, agence web paris, web design Lyon, stratégie web">

# Je corrige le taille police <p> de 11px à 14px pour plus lisible.

# Dans le div .med-width-whitespace, je supprime dans le css {box-shadow: 0px 0px 0px #000000;}; et je change le max-width: 1200px pour qu'il y ait plus d'espace entre les trois bloc services.

2.4 Bloc-3-What-I-do

