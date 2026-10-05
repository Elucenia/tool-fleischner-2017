<!-- ELUCENIA technical documentation · fleischner-2017 · fr · no clinical/professional/rights approval -->

# Fleischner 2017 (nodule pulmonaire solide)

[conditions, sources et autorisations](https://elucenia.org/fr/outils/fleischner-2017)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Diamètre moyen du nodule (le plus suspect s’il y en a plusieurs)

`tamanho`

mm · intervalle: 1–30

### Nombre de nodules

`num`

- `u` — Unique
- `m` — Multiples

### Risque de cancer du poumon

`risco`

- `b` — Faible
- `a` — Élevé (tabagisme, âge, exposition, antécédents familiaux, emphysème, lobe supérieur)

## Édition de la méthode

Fleischner Society 2017 : nodules solides fortuits, diamètre moyen arrondi ; exclusions préservées

## Formule documentée

Diamètre moyen = (grand axe + petit axe) ÷ 2, arrondi au millimètre le plus proche. Plages : \< 6 mm (\< 100 mm³), 6 à 8 mm (100 à 250 mm³) et \> 8 mm (\> 250 mm³).

## Limites et population

Variante pour les nodules pulmonaires solides découverts fortuitement chez les adultes de 35 ans ou plus. Les recommandations Fleischner 2017 ne s’appliquent pas au dépistage du cancer pulmonaire, aux personnes immunodéprimées ni aux patients ayant un cancer primitif connu. Les nodules sous-solides ou partiellement solides nécessitent un autre algorithme. En présence de plusieurs nodules, le nodule le plus suspect doit guider l’évaluation ; il n’est pas nécessairement le plus grand. La stratification du risque et la décision de suivi dépendent de l’évaluation clinique et radiologique.

## Références

- [MacMahon H et al. Guidelines for management of incidental pulmonary nodules detected on CT images: from the Fleischner Society 2017. Radiology, 2017.](https://doi.org/10.1148/radiol.2017161659)

- [MacMahon et al. Radiology2017, DOI10.1148/radiol.2017161659](https://pubs.rsna.org/doi/full/10.1148/radiol.2017161659)

- [Original sixteen-page RSNA article, institutional copy at University of Wisconsin](https://wiki.radiology.wisc.edu/images/b/b9/Flesichner_Guidelines_2017.pdf)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
