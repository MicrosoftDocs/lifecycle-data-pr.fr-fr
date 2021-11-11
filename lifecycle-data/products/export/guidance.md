---
title: Guide d’exportation des données sur le cycle de vie
description: Guide d’exportation des informations sur le cycle de vie des produits
ms.date: 12/16/2020
layout: ContentPage
ms.openlocfilehash: 5e9dddbff5fac32e6d3cf8ef0943151d2dfe5e35
ms.sourcegitcommit: 6ea3221fd5475440480515f04f33988656d71748
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 11/02/2021
ms.locfileid: "3546797"
---
# <a name="lifecycle-data-export-guidance"></a>Guide d’exportation des données sur le cycle de vie
Ce document décrit comment utiliser le fichier d’exportation de produits.

## <a name="query-information"></a>Informations sur les requêtes
Le document Excel comporte des champs qui permettent d’identifier les données renseignées dans le tableau des produits.

### <a name="end-of-support"></a>Fin de support
La valeur relative à la fin du support permet de filtrer les produits en fonction de leur date de fin de support ou de leur date de fin de publication.

Valeurs possibles : Tous (aucun filtre appliqué), Année et Période.

### <a name="family"></a>Famille
La valeur relative à la famille filtre les produits en fonction de leur niveau parent au sein de la hiérarchie appelée famille.

Valeurs possibles : Tous (aucun filtre appliqué), Nom de famille

### <a name="group"></a>Group
La valeur relative au groupe filtre les produits au sein de leur niveau parent (famille) pour un groupe spécifique.

Valeurs possibles : Tous (aucun filtre appliqué), Nom de groupe

## <a name="table-columns"></a>Colonnes de tableau
Le tableau des produits se compose de colonnes définissant le produit, les éditions, les versions et les dates de support correspondantes.

> [!NOTE]
> Chaque ligne correspond à une combinaison de produit, d’édition et de version.

### <a name="product"></a>Produit
Nom du produit.

### <a name="edition"></a>Édition
La colonne relative à l’édition est renseignée lorsque le produit comporte des éditions. S’il n’existe aucune édition de produit, ce champ est vide.

### <a name="release"></a>Débloquer
La colonne relative à la version est renseignée lorsque le produit comporte plusieurs versions.
Lorsque le produit n’a qu’une seule version, ce champ est vide.

### <a name="support-policy"></a>Stratégie de support
Ce champ définit la stratégie de support suivie par le produit.

Valeurs possibles : [Fixe](/lifecycle/policies/fixed), [Moderne](/lifecycle/policies/modern), Composant

### <a name="start-date"></a>Date de début
Date de début du support pour le produit.

### <a name="mainstream-date"></a>Date standard
Lorsque la stratégie de support est de type **Fixe** ou **Composant**, il s’agit de la date de fin du support standard du produit.
  
Lorsque la stratégie de support est de type **Moderne**, ce champ est vide.

### <a name="extended-end-date"></a>Date de fin du support étendu
Lorsque la stratégie de support est de type **Fixe** ou **Composant**, il s’agit de la date de fin du support étendu du produit.

Lorsque la stratégie de support est de type **Moderne**, ce champ est vide.

### <a name="retirement-date"></a>Date de retrait
Lorsque la stratégie de support est de type **Fixe** ou **Composant**, ce champ est vide.

Lorsque la stratégie de support est de type **Moderne**, il s’agit de la date de retrait du produit.

### <a name="release-start-date"></a>Date de début pour la version
Date de début du support pour la version. Lorsque le produit n’a qu’une seule version, ce champ est vide.
 
### <a name="release-end-date"></a>Date de fin pour la version
Date de fin du support pour la version.
Lorsque le produit n’a qu’une seule version, ce champ est vide.

### <a name="docs-url"></a>URL des documents
URL de la documentation étendue.
