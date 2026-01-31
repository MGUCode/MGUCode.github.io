---
layout: post
title: "Nouveautés de Siemens PLCSim Advanced V8"
date: 2026-01-31
categories: [Actualités]
tags: [Siemens,PLCSim,TIA]
---

***PLCSim Advanced V8 est sorti. Point sur LA nouveauté principale de cette version.***

## Tour du propriétaire

PLCSIM Advanced est un logiciel qui permet de simuler un automate, comme PLCSIM "standard" depuis STEP7 V5.X. Cette version « Advanced » a la particularité majeure d’offrir une communication Ethernet à l'automate, ce qui n’est pas possible avec PLCSIM "standard". Cette communication vous permet, par exemple, de dialoguer avec un IHM, un autre système de supervision non Siemens, ou encore d'échanger avec un vrai automate. Cependant, PLCSIM Advanced ne remplacera jamais un vrai automate, car les temps de cycle seront plus élevé (l'automate simulé pouvant être légèrement plus lent à répondre). De plus, la communication vers un réseau terrain (Profinet ou Profibus) ne fonctionnera pas.

Un cas concret d'utilisation possible est l'exécution de PLCSIM Advanced dans un environnement de "jumeau numérique", qui n'est juste qu'un terme marketing pour signifier la simulation d'un process industriel dans un environnement virtuel (à des fins de formation opérateur par exemple).

Cette nouvelle version en V8 offre une petite révolution : la possibilité de simuler un S7-1200 (de 2ème génération uniquement). Cet ajout est le bienvenu, car c’était la seule gamme d’automate non prise en charge par le logiciel jusqu'à aujourd'hui.

![Capture écran logiciel]({{ site.url }}/assets/2026-01-31-PLCSIM-Adv-8-Nouveautes/1.png)


## Les gammes supportées

On retrouve donc les gammes principales d’automates :
- S7-1500
- ET200SP CPU
- ET200Pro CPU
- S7-1200 G2

Seuls les gammes S7-300 et S7-400 ne sont pas supportées (les S7-300 étant en fin de vie et les S7-400 réservés à des usages plus évolués). Ces gammes sont assez minoritaires en programmation TIA.


## Quelques restrictions

Attention néanmoins, quelques restrictions sont à prendre en compte : 
- Compatible à partir de TIA V14 et plus
- Les S7-1200 de première génération ne sont pas supporté

Afin de différentier les S7-1200 de première et seconde génération, vous pouvez vous référer à cet [article du support](https://support.industry.siemens.com/cs/document/109973175) ou vous rendre sur le [catalogue en ligne](https://sieportal.siemens.com/en-fr/products-services/10593998?tree=CatalogTree).
En résumé, si vous possédez un S7-1200 depuis longtemps, il est peu probable qu'il soit compatible pour PLCSIM Advanced : la gamme des S7-1200 G2 est assez récente (apparue avec TIA V20).

Afin d'utiliser le logiciel plus de 21 jours, il est nécessaire d'acheter une licence (ou d'acheter la licence d'upgrade si vous la possédez déjà dans une version inférieure).


## Comment l'essayer

Les logiciels PLCSIM sont en général très utilisés par les automaticiens. Grâce à ces logiciels, il n'est pas nécessaire d'avoir le matériel physiquement pour simuler son programme. 

Si votre automate est déjà parti dans l'armoire de votre partenaire électricien préféré, il est toujours possible de continuer vos développements et tests grâce à PLCSIM Advanced.

Pour plus d'information et essayer le logiciel, ça se passe [ici](https://support.industry.siemens.com/cs/document/109990051). Il est également inclus dans l'ISO de PLCSIM que l'on peut trouver par [là](https://support.industry.siemens.com/cs/document/109989774/).