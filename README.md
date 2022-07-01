
<!-- README.md is generated from README.Rmd. Please edit that file -->

# agreste

<div id="badges">

![](https://git.lab.sspcloud.fr/ksteunou/agreste/badges/master/pipeline.svg?job=build)
![](https://git.lab.sspcloud.fr/ksteunou/agreste/badges/master/coverage.svg)

</div>

Le but du package agreste est de fournir à l’ensemble des agents du SSP
des outils pour faciliter la diffusion auprès du grand public. Le
package agreste propose des aides pour construire des tableaux, des
graphiques, des cartes… Il facilite la création des documents attendus
par la PAO (docx, xlsx). Il apporte des modèles de Rmarkdown.

## Installation

Vous pouvez installer le package agreste à partir du fichier
`agreste.tar.gz` :

``` r
devtools::install_github("https://github.com/killian31/agrestePubli.git")
```

## Example

Voici un exemple simple d’utilisation du package agreste :

``` r
library(agreste)

# Démarrer l'app Shiny pour mettre en forme les tableaux
app_formatage()
```

Vous pouvez également démarrer l’interface graphique en utilisant
l’*Addin* intégré.
