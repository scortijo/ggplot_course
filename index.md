**Où:** Salle 109 du batiment 9 (IMAG), au premier étage

**Quand:** 15/10/2020, 14h-17h

**Instructeurs:** 
[Sandra Cortijo](mailto:sandra.cortijo@hotmail.fr), 
[Isabelle Sanchez](mailto:Isabelle.Sanchez@inrae.fr)


### Description

Ce cours va vous apprendre comment réaliser des graphique sur **R** en utilisant **ggplot2**, en partant de données tabulaires (ce que vous pourriez créer en utilisant excel).

Le jeu de données que nous allons utiliser en exemple à été publié par 
[Burghardt .. Schmitt (2015)](https://doi.org/10.1111/nph.13799). 


### Prérequis
Les participant doivent déjà avoir des bases de R et savoir utiliser Rstudio. Si ce n'est pas le cas, veuillez vous inscrire pour une formation R avant de venir à la formation ggplot.



### A faire avant le cours: 
Les participants doivent amener leur ordinateur sur lequel R et R studio sont installés.
[Installer R](https://cran.biotools.fr/),
[Installer Rstudio](https://rstudio.com/products/rstudio/download/)

Dans chaque cas, télécharger la version pour votre système opérateur (Mac, Windows ou Linux) et installer les programmes normalement.

Vous devez aussi avoir les packages `tidyverse`, `visdat` et `plotly`  installé. 
Pour cela:
1. Assurez vous d'avoir acces à internet
2. Ouvrez Rstudio
3. Dans la "console"" (panel en haut à gauche), tapez `install.packages("tidyverse")` puis enter
4. De même tapez `install.packages("visdat")` et enter puis enfin `install.packages("plotly")` et enter
4. Assurez vous que l'installation a fonctionné en tapant `library(tidyverse)` (puis faites la même chose avec `visdat` et `plotly`)
5. Le message affiché doit être similaire à la capture d'écran ci-dessous. Si vous avez un message du type: 
"Error in library(tidyverse): there is no package called 'tidyverse'"
**contantez un des instructeur avant le cours**.

ouvrez R studio taper dans la console R de Rstudio: install.packages("tidyverse")

![capture d'écran d'un installation correcte](installation_package_instructions.png)



### Matériel du cours


[Cours](materiel/ggplot_lesson.html)



### Ressources 

[Gallerie de graphiques pouvant être réalisé avec ggplot2](https://www.r-graph-gallery.com/)

[ggplot2 cheat sheet](https://rstudio.com/wp-content/uploads/2015/03/ggplot2-cheatsheet.pdf)

[réorganisation de données cheat sheet](module01_data_and_files/materials/data_organisation.md)






