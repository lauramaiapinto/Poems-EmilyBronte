# Conception d'édition

### Objectif

Créer une édition numérique des poèmes d’Emily Brontë mettant en valeur leur dimension symbolique et intertextuelle, à travers leurs thèmes, symboles récurrents et allusions bibliques ou mythologiques.

L’œuvre de Brontë explore des thèmes universels : mort, nature, foi, amour, transcendance... Des thèmes souvent symbolisés par des images récurrentes, telles que la nuit, le ciel, le feu, etc. Ces symboles sont souvent liés à des références culturelles implicites, notamment bibliques et mythologiques.

Cette édition veut rendre visibles ces réseaux symboliques et permettre leur exploration en utilisant des index thématiques.

L’encodage aura pour but non seulement de structurer le texte, mais aussi d’en révéler la profondeur littéraire et spirituelle, en rendant visible le réseau de symboles dissimulés dans son oeuvre, et en tissant des liens entre les poèmes.

Ce projet s'inscrit dans le cadre d'un cours universitaire.

### Axe éditorial 

L’édition se veut centrée sur une lecture interprétative des poèmes. Elle met en avant les grands thèmes récurrents, c'est-à-dire l'amour, la nature, la tristesse, et le temps.

L’objectif est de proposer une édition analytique qui permette de naviguer dans le corpus non seulement par poème, mais aussi par thème. Ainsi, le lecteur peut choisir de relever les différents thèmes et liens entre les poèmes afin d'en développer une analyse.

### Encodage TEI

Seule une sélection de balises ont été retenues afin de faciliter la création de l'édition, c'est-à-dire la TEI Lite. Afin de parvenir à mon objectif, je pense me pencher sur les balises suivantes:

Chaque poème sera structuré à l'aide des balises TEI habituelles: - `<div type="poem">` (identification) ;
- `<lg>` (strophes) ;
- `<l>` (vers) ;

Grâce à une annotation sémantique, je ressortirai les thèmes principaux qui seront les suivants:
- **Love**
- **Nature**
- **Sadness**
- **Time**

Les mots clés ressortis des poèmes seront disponibles sur l'index de l'édition. Ces mots clés proviennent des poèmes, et ont été ressorti dans une liste grâce à une requête XPath.

