# Conception d'étition

### Objectif

Créer une édition numérique des poèmes d’Emily Brontë mettant en valeur leur dimension symbolique et intertextuelle, à travers leurs thèmes, symboles récurrents et allusions bibliques ou mythologiques.

L’œuvre de Brontë explore des thèmes universels : mort, nature, foi, amour, transcendance... Des thèmes souvent symbolisés par des images récurrentes, telles que la nuit, le ciel, le feu, etc. Ces symboles sont souvent liés à des références culturelles implicites, notamment bibliques et mythologiques.

Cette édition veut rendre visibles ces réseaux symboliques et permettre leur exploration en utilisant des index thématiques et intertextuels.

L’encodage aura pour but non seulement de structurer le texte, mais aussi d’en révéler la profondeur littéraire et spirituelle, en rendant visible le réseau de symboles dissimulés dans son oeuvre.

### Axe éditorial 

L’édition se veut centrée sur une lecture interprétative des poèmes. Elle met en avant les grands thèmes récurrents, les symboles poétiques associés à ces thèmes, et les références culturelles et religieuses implicites ou explicites.

L’objectif est de proposer une édition analytique qui permette de naviguer dans le corpus non seulement par poème, mais aussi par thème, symbole ou référence intertextuelle.

### Encodage TEI

Afin de parvenir à mon objectif, je pense me pencher sur les balises suivantes:

Chaque poème sera structuré à l'aide des balises TEI habituelles: <div>, <head>, <lg>, <l>

Ensuite, à l'aide de la balise <rs>, j'encoderai les thèmes, allusions et symboliques. Ceux-ci seront liés aux attributs type/key afin de générer un index. Il y aura un type différent si c'est une allusion ou une thématique. 

Il sera possible pour moi d'apporter un commentaire d'analyse grâce à la balise <note type="intérpretation">


