---
source-git-commit: d3e36cef27fce533e9435717d428d54b982fd427
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---
# Documentation collaborative pour Advertising Cloud

Il s’agit du référentiel de documentation de Adobe Advertising Cloud, y compris les documents multiproduits, DSP et télévisés. (Par la suite, il contiendra des documents pour Creative and Search.)

**Remarque : Cette page n’est pas publiée dans la documentation destinée aux clients.**

## Table des matières

+ `TOC.md` à la racine de n’importe quel guide d’utilisation fournit l’organisation des rubriques contenues dans le guide.
+ Chaque guide de l’utilisateur comporte un `TOC.md` unique, dans lequel vous pouvez classer toutes les pages/rubriques selon vos besoins.


## Guide de l’utilisateur

+ L’introduction au guide de l’utilisateur est appelée `overview.md`
+ Chaque rubrique du guide de l’utilisateur possède son propre répertoire.
   + S’il existe une rubrique dans le guide appelée *Implémentation*, le répertoire correspondant est `/implementation`
+ Toutes les ressources d’image sont stockées dans `/assets` à la racine du guide de l’utilisateur.
   + Toutes les images du répertoire `/assets` seront localisées.
   + Les images du répertoire `/no-localize` ne seront pas localisées (surprise !). Cela peut être utilisé pour garantir dans les versions loc que des ressources spécifiques ne sont pas reproduites inutilement.

## Métadonnées au niveau du guide de l’utilisateur

+ Les métadonnées qui décrivent le guide de l’utilisateur sont stockées dans la balise `TOC.md`. Cela inclut :
   + product - nom du produit/de la fonctionnalité.
   + cloud : cloud auquel ce produit appartient.
   + audience : audience ou archétype à qui le guide est ciblé.
   + user-guide - nom du guide de l’utilisateur.

## Métadonnées au niveau de la page

+ Les métadonnées requises pour décrire un document sont stockées dans chaque page. Cela inclut :
   + title : titre de la page.
   + description - description de la page
   + seo-title - autre titre seo
   + seo-description - autre titre à des fins d’optimisation pour les moteurs de recherche
   + short-title - (champ facultatif)
   + index - yes/no - la page sera indexée par la plateforme de recherche de l’Adobe
   + translate - yes/no - cette page sera-t-elle localisée ?
   + beta - ce produit est-il en version bêta ?
   + redirect : peut être utilisé pour créer une référence à une nouvelle page si nécessaire.
   + doc-type : référence (par défaut)/dépannage/développeur/tutoriel/kb/livre blanc

## Plus d’informations

Pour plus d’instructions de publication, de guides de style, d’exemples et d’autres ressources, voir :

+ [Instructions relatives à la contribution des auteurs  **spécifiquement pour Advertising Cloud**](https://wiki.corp.adobe.com/pages/viewpage.action?spaceKey=EfficientFrontier&amp;title=Contributing+Author+Guidelines+for+Advertising+Cloud+Help)
+ [Création collaborative pour tous les auteurs d’Adobe](https://experienceleague.adobe.com/docs/authoring-guide-exl/using/home.html)

Voir aussi :

+ contributing.md Pour obtenir un aperçu de la contribution à la documentation.

<!-- * guidelines.md For an overview on what is expected in contributions and how to compose your documentation contributions. -->
+ code-of-conduct.md Pour une présentation des normes de comportement attendues lorsque vous contribuez à ce projet de documentation.
