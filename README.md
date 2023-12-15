# Caesar III FrDeluxe

![FrDeluxe](https://raw.githubusercontent.com/Ouaz/frdeluxe/master/banniere.jpg)

## Téléchargement

Télécharger [FrDeluxe 1.3](https://github.com/Ouaz/frdeluxe/releases/download/v1.3/FrDeluxe_1.3.zip)

## Quel but ?

Bien que tout à fait correcte, la traduction française d'origine de Caesar III souffrait de quelques défauts majeurs:

- Manque d'homogénéité: la récurrence des formulations n'était pas respectée, c'est-à-dire que plusieurs entrées semblables en anglais étaient traduites de plusieurs manières différentes en français, prêtant parfois à confusion (les gradations des malus des bâtiments par exemple). La version française ne conserve pas non plus la catégorisation des items (par exemple les noms de fermes ou d'ateliers), inhérente aux City Builders.

- Traduction hors-contexte: il semble évident que les traducteurs de l'époque ont effectué une partie de leur travail hors-contexte (adaptation à l'interface par exemple), et se sont donc appliqués à respecter le plus possible la longueur des entrées anglaises. Cela mène parfois à des traductions approximatives (et à la syntaxe alambiquée) engendrant une perte de précision ou de sens (ou pire des erreurs) dans la version française.

- Problèmes de formatage: de nombreuses ponctuations inutiles (par exemple sur les boutons), et quelques problèmes d'adaptation à l'interface (principalement dans les Rapports et les Messages).

La pack de langue FrDeluxe remédie à ces problèmes en proposant une traduction française améliorée, corrigée et harmonisée pour le jeu principal, l'Aide en jeu, ainsi que l'Éditeur de cartes et son Aide.

Cette nouvelle traduction est plus fidèle à la version anglaise, sans pour autant modifier trop profondément les traductions d'origine auxquelles tous les fans français du jeu se sont habitués.

## Installation

- FrDeluxe nécessite le [patch 1.1 de Caesar III](https://github.com/bvschaik/julius/wiki/Patches) correspondant à la langue de votre version. FrDeluxe est compatible avec toutes les versions de Caesar III, quelle que soit la langue d'origine.

- Si vous utilisez les mods [Julius](https://github.com/bvschaik/julius) ou [Augustus](https://github.com/Keriew/augustus):

1) Placez le dossier `frdeluxe` contenu dans l'archive zip, à la racine du dossier d'installation de Caesar III (par exemple `C:\Caesar III\frdeluxe`)
2) Dans les options de Julius ou d'Augustus, sélectionnez comme langue le dossier `frdeluxe` et appliquez (Augustus) ou validez (Julius).

- Si vous jouez sur la version d'origine (vanilla) de Caesar III, copiez les 4 fichiers contenus dans le dossier "frdeluxe" (c3.eng / c3_mm.eng / c3_map.eng / c3_map_mm.eng) à la racine du dossier d'installation de Caesar III. Il est conseillé au préalable de faire une copie des 4 fichiers .eng d'origine, si vous désirez éventuellement revenir à la traduction originale.

## Quelles modifications ?

Consultez quelques [exemples de changements](https://github.com/Ouaz/frdeluxe/blob/master/LisezMoi_FrDeluxe.txt#L37) dans le fichier LisezMoi_FrDeluxe.txt.

Pour afficher toutes les modifications apportées, consultez le fichier [`patch-diff.txt`](https://github.com/Ouaz/frdeluxe/blob/master/patch-diff.txt), listant les 1116 entrées modifiées pour le jeu principal, mais pas celles de l'Aide (trop nombreuses!), ni celles de l'Éditeur de cartes et de son Aide.

Notes: 
- Le fichier `c3.eng` contient toutes les entrées du jeu principal.
- Le fichier `c3_mm.eng` contient toutes les entrées de l'Aide, les messages des scribes, les événements spéciaux, et les briefings de mission.
- Le fichier `c3_map.eng` contient les entrées supplémentaires de l'Éditeur de cartes.
- Le fichier `c3_map_mm.eng` contient les entrées supplémentaires de l'Aide de l'Éditeur de cartes. 
- Aucune ligne de dialogue n'a été modifiée car elles sont toutes accompagnées d'un fichier audio. 

Pour toutes suggestions ou remontées d'erreurs, rendez-vous sur
https://github.com/Ouaz/frdeluxe

ou

sur le site [Abandonware Forums - Les Aventuriers de la Traduction Perdue](https://www.abandonware-forums.org/forum/autres/les-aventuriers-de-la-traduction-perdue/836163-caesar-iii-traduction-frdeluxe#post836163)

## Remerciements

Merci à Bianca van Schaik (bvschaik) pour le mod [Julius](https://github.com/bvschaik/julius) et l'utilitaire [ENG Converter](https://github.com/bvschaik/citybuilding-tools) permettant de manipuler les fichiers langue de Caesar III.

Merci à la Team Augustus Project pour le mod [Augustus](https://github.com/Keriew/augustus).

Merci à Impressions Games pour Caesar III, city builder éternel, et aux traducteurs français d'origine, pour leur travail assez convenable, compte tenu, j'imagine, des circonstances (délais, traduction hors-contexte).