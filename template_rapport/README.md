# Template LaTeX HeH

## Table des matières

-   [Installation](#installation)
-   [Recommandations](#recommandations)
-   [Note](#note)

## Installation

1. Installez une distribution LaTeX (par example TexLive sous Linux, MacTeX ou MikTeX sous Windows).
2. Verifiez que les packages sont bien disponibles (une installation dites "complete").
    - Pour TexLive, veillez simplement à installer le package `texlive-full` si votre distribution le permet.
    - Pour MikTeX, utilisez le gestionnaire de packages intégré.
3. Installez un éditeur de texte (forte recommandation pour Visual Studio Code)
4. Compilez vos documents en `.tex`!

## Recommandations

1. L'installation des extensions suivantes est recommandée pour une meilleure expérience de 
-   [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) : pour la compilation et l'édition de documents LaTeX.
-   [LTeX+](https://marketplace.visualstudio.com/items?itemName=ltex-plus.vscode-ltex-plus) : pour la correction orthographique et grammaticale.

2. L'utilisation fréquente et régulière de GIT pour le suivi des modifications et la sauvgarde de vos documents est fortement recommandée.


## Note

-   Les compilations effectuées sous Windows sont généralement plus lentes que sous Linux.
-   Si vous suivez les recommandations, les erreurs de complilation seront rendues invisibles, si les changements ne se répercutent pas n'oubliez pas de vérifier les fichiers `.log` pour de potentielles erreurs.
-   Ce template est conçu pour être utilisé avec le compilateur `latexmk`. d'autres compilateurs peuvent fonctionner, mais ne sont pas garantis.
-   Ce template est le fruit d'un travail collaboratif et evolutif. Le code source ainsi que les contributeurs sont disponibles sur [GitHub](https://github.com/shadowthib/LaTex-learning). Toute contribution est la bienvenue 😀
