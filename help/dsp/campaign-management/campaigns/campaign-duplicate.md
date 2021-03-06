---
title: Dupliquer une campagne
description: Découvrez comment dupliquer une campagne.
feature: DSP Campaigns
exl-id: 2bb4030d-22b0-4a16-aeed-35f64a19df6a
source-git-commit: d10e1c24ee7c93eaab3fd4fefe853860226cc8e2
workflow-type: tm+mt
source-wordcount: '200'
ht-degree: 0%

---

# Dupliquer une campagne

<!-- Some placements don't have this option. Clarify which placement types aren't eligible -- is it PG placements, or all placements using private inventory? And anything else? -->

Dupliquez une campagne pour créer une campagne avec des paramètres similaires. Vous pouvez :

* Dupliquez la campagne pour l’annonceur d’origine ou pour une autre campagne.
* Vous pouvez éventuellement dupliquer les packages et emplacements d’origine
* Modifier les dates de vol de la nouvelle opération

Voir &quot;[Ce qui n’est pas dupliqué](#campaign-not-duplicated)&quot; pour obtenir la liste des paramètres d’emplacement qui ne sont pas dupliqués.

1. Dans le menu principal, cliquez sur **[!UICONTROL Campaigns]**.
1. En regard du nom de la campagne, cliquez sur **... >[!UICONTROL Duplicate]**.
1. Définissez les nouveaux paramètres de campagne :
   1. Saisissez le nouveau nom de l&#39;opération et la date de fin du vol.
   1. (Facultatif) Modifiez les paramètres par défaut.

      Par défaut, la nouvelle campagne est affectée à l’annonceur d’origine, son planning de vol commence le jour en cours et comprend les kits et emplacements d’origine.

1. Cliquez sur **[!UICONTROL Submit]**.

## Ce qui n’est pas dupliqué {#campaign-not-duplicated}

Tous les paramètres des emplacements d’origine sont dupliqués sauf :

* Paramètres d’expérience
* (Si vous modifiez les dates de vol) Planification publicitaire personnalisée
* (Si vous ne joignez pas de publicités) Pondération et planification des publicités personnalisées
* Emplacements par défaut pour les offres garanties par programmation (PG) et emplacements pour les offres [!UICONTROL Simple Ad Serving]
* (Si vous copiez des emplacements dans une autre campagne) :
   * Cibles géographiques
   * Pixels d’événement
   * Publicités
   * Segments de niveau emplacement [!DNL DoubleVerify Authentic Brand Safety] (qui remplacent les segments de niveau annonceur)

>[!MORELIKETHIS]
>
>* [Gestion de campagne](campaign-about.md)
>* [Création d’une campagne](campaign-create.md)
>* [Modifier une campagne](campaign-edit.md)
>* [Paramètres de campagne](campaign-settings.md)

