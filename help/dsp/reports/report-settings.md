---
title: Paramètres des rapports personnalisés
description: Reportez-vous à la description des paramètres de rapport personnalisés.
feature: DSP Custom Reports
source-git-commit: 3059a5b211a8a219b02930f7f5763d5ec1467b8e
workflow-type: tm+mt
source-wordcount: '966'
ht-degree: 0%

---

# Paramètres des rapports personnalisés

**[!UICONTROL Name]** Nom du rapport. La longueur maximale est de 180 caractères.

**[!UICONTROL Report Type]** Le type de rapport : *[!UICONTROL Custom]* (qui inclut la plupart des options disponibles), *[!UICONTROL Billing]*, *[!UICONTROL Conversion]*, *[!UICONTROL Device]*, *[!UICONTROL Frequency (by Impression)]*,  *[!UICONTROL Frequency (by App/Site)]*, *[!UICONTROL Geo]*, *[!UICONTROL Margin]*, *[!UICONTROL Media Performance]*,  *[!UICONTROL Segment]* ou *[!UICONTROL Site]*.

## [!UICONTROL Apply Filters] Section

**[!UICONTROL Timezone]:** Fuseau horaire pour la création de rapports.

**[!UICONTROL Observe Daylight Savings Time]:** Considère l’heure d’été comme l’heure d’été dans les heures signalées.

**\[Période\] :** La période pour laquelle générer les données. Le nombre de jours disponibles varie selon le rapport et selon les dimensions sélectionnées. Choisissez-en une :

* **[!UICONTROL Previous N days]:** Inclut des données pour un nombre spécifique de jours avant aujourd’hui.

* **[!UICONTROL Custom]:** Inclut des données entre des dates de début et de fin spécifiques. Pour créer un rapport sur les données du jour précédent, sélectionnez **[!UICONTROL Present]**.

* **[!UICONTROL Last Calendar Month]:** Inclut les données du mois civil précédent.

**[!UICONTROL Add Filters]:** (Facultatif) Dimensions supplémentaires par lesquelles filtrer les données, que les dimensions soient incluses ou non sous forme de colonnes dans le rapport : *[!UICONTROL Account]*,\* *[!UICONTROL Advertiser]*, *[!UICONTROL Campaign]*, *[!UICONTROL Placement]*, *[!UICONTROL Ad]*, *[!UICONTROL Ad Type]*, *[!UICONTROL Video]*, *[!UICONTROL Video Duration]*, *[!UICONTROL Country]*, et *[!UICONTROL Package]*.

\* *[!UICONTROL Account]* est disponible pour les types de rapports suivants uniquement lorsque votre entreprise est configurée pour [rapport entre comptes](report-about.md#cross-account-reporting):  [!UICONTROL Custom], [!UICONTROL Site], [!UICONTROL Segment], [!UICONTROL Geo], [!UICONTROL Device], [!UICONTROL Frequency (by Impression)], et [!UICONTROL Conversion]. Contactez votre [!DNL Adobe] équipe de compte pour plus d’informations sur les rapports entre comptes.

Pour appliquer un ou plusieurs filtres, procédez comme suit :

* Sélectionnez une dimension, puis l&#39;opérateur (*est égal à* ou *not equals*), puis sélectionnez la valeur appropriée. Par exemple, pour renvoyer des données uniquement pour les publicités preroll, spécifiez &quot;[!UICONTROL Ad Type equals Preroll].&quot;
* (Facultatif) Ajoutez des critères supplémentaires au filtre.
* (Facultatif) Ajoutez des filtres supplémentaires, chacun avec un ou plusieurs critères.

## [!UICONTROL Build Your Report] Section

**[!UICONTROL Select To Add As Report Headers]:**  Les colonnes de données, ou en-têtes, à inclure dans le rapport. Pour ajouter une colonne, développez la catégorie et cochez la case en regard de son nom. Toutes les mesures non disponibles sont désactivées. Les catégories de données disponibles sont les suivantes :

* [!UICONTROL  Dimensions]
* [!UICONTROL Metrics]
* [!UICONTROL Conversion Metrics] (triés par annonceur)
* [!UICONTROL Custom Goals] (triés par annonceur)

**[!UICONTROL Drag to Re-Order Report Headers Below]:** L’ordre des en-têtes de colonne. Vous pouvez faire glisser et déposer n’importe quelle colonne pour personnaliser l’ordre.

## [!UICONTROL Multi-Touch Conversion Options] Section

**[!UICONTROL Format]:** Génération ou non d’un rapport dans *[!UICONTROL CSV]* (valeurs séparées par des virgules) ou *[!UICONTROL Tab]* format (valeurs séparées par des tabulations).

**[!UICONTROL Report Headers]:** Si *[!UICONTROL Include]* ou *[!UICONTROL Do Not Include]* en-têtes de colonne.

**[!UICONTROL Attribution Rule Settings]:** (Tous) [!UICONTROL Custom], [!UICONTROL Conversion], [!UICONTROL Device], [!UICONTROL Geo], [!UICONTROL Segment], et [!UICONTROL Site] rapports avec [!UICONTROL Conversion Metrics] ou [!UICONTROL Custom Goals] colonnes; publicitaires avec suivi de conversion Adobe Advertising uniquement) Dans le rapport, comment attribuer des données de conversion dans une série d’événements qui mènent à une conversion. Vous pouvez choisir plusieurs règles si vous souhaitez comparer les différences entre les règles.

>[!NOTE]
>
>Les chemins de conversion incluent toutes les impressions et tous les clics dans les fenêtres d’impression ou de recherche en amont des clics de l’annonceur, qui sont configurés dans [!DNL Adobe Advertising Search]. Les clics sont préférés aux impressions lors de l’attribution de conversion. Tous les clics dans un chemin de conversion reçoivent un crédit complet en fonction de la règle d’attribution. Les impressions ne reçoivent du crédit que lorsqu’aucun clic n’est suivi dans le chemin de conversion.

* *[!UICONTROL Last Event]:* Attribue des conversions au dernier clic ou impression dans le chemin de conversion.

* *[!UICONTROL Weight Last More]:* Attribue des conversions à tous les événements du chemin de conversion, mais donne le plus de poids au dernier événement et, successivement, le moins de poids aux événements précédents.

* *[!UICONTROL Even Distribution]:* Attribue les conversions de manière égale à chaque événement du chemin de conversion.

* *[!UICONTROL Weight First More]:* Attribue des conversions à tous les événements du chemin de conversion, mais accorde le plus de poids au premier événement et, successivement, moins de poids aux événements suivants.

* *[!UICONTROL First Event]:* Attribue des conversions au premier clic ou impression dans le chemin de conversion.

* *[!UICONTROL U-shaped]:* Attribue la conversion à tous les événements du chemin de conversion, mais donne le plus de poids aux premier et dernier événements, avec successivement moins de poids aux événements au milieu du chemin de conversion.

* *[!UICONTROL Display Only]:*  Attribue des conversions au dernier clic ou impression DSP dans le chemin de conversion. Cela inclut les publicités vidéo et télévisées et exclut les clics sur [!DNL Adobe Advertising Search] publicités.

* *[!UICONTROL Social Only]:* Obsolète

<!-- See also [How Attribution Rules Are Calculated for Adobe Advertising](). -->

**[!UICONTROL Paths as Columns]:**  (Tous) [!UICONTROL Custom], [!UICONTROL Conversion], [!UICONTROL Device], [!UICONTROL Geo], [!UICONTROL Segment], et [!UICONTROL Site] rapports avec [!UICONTROL Conversion Metrics] ou [!UICONTROL Custom Goals] Colonnes) Quels types de conversions signaler les événements précédents qui se sont produits sur le même appareil ? Vous pouvez inclure jusqu’à trois types. Pour chaque type sélectionné, une colonne distincte est incluse pour chaque mesure de conversion et est ajoutée avec le suffixe spécifié ([!UICONTROL (tl)], [!UICONTROL (ct)]ou [!UICONTROL (vt)]) :

* *[!UICONTROL Total (TL) = CT + VT \* VT weight]:* Inclut des conversions attribuées aux clics (CT pour les clics publicitaires) et aux impressions (VT pour les affichages publicitaires). Les conversions attribuées aux impressions sont multipliées par le poids d’affichage publicitaire spécifié. Le poids par défaut de l’affichage publicitaire est de 100 %, ce qui signifie que les conversions attribuées aux impressions sont comptabilisées à 100 % de la valeur des conversions attribuées aux clics.

* *[!UICONTROL With Clicks (CT)]:* Inclut uniquement les conversions attribuées aux clics.

* *[!UICONTROL Impressions Only (VT)]:* Inclut uniquement les conversions qui ont été attribuées aux impressions car aucun clic n’a été suivi dans le chemin de conversion.

**[!UICONTROL Conversion Reporting Based On]:**  Comment signaler les données de conversion :

* *[!UICONTROL Conversion Timestamp]:* (Par défaut) Les conversions sont associées à la date de conversion.

* *[!UICONTROL Event Timestamp]:* Les conversions sont signalées en fonction de la date de l’impression ou du clic qui a provoqué la conversion, comme déterminé par la variable [!UICONTROL Attribution Rule Settings].

## [!UICONTROL Add Report Destinations] Section

**[!UICONTROL Destination Type]:** Sélectionnez l’un des types de destinations suivants :

* *[!UICONTROL S3]:* Pour envoyer le rapport terminé à un ou plusieurs [!DNL Amazon Simple Storage Service] ([!DNL Amazon S3]), que vous préciserez dans la variable **[!UICONTROL Destination Name]** champ .
* *[!UICONTROL sFTP]:* Pour envoyer le rapport terminé à un ou plusieurs emplacements SFTP, que vous indiquez dans la variable **[!UICONTROL Destination Name]** champ .
* *[!UICONTROL FTP]:* Pour envoyer le rapport terminé à un ou plusieurs emplacements FTP, que vous indiquez dans la variable **[!UICONTROL Destination Name]** champ .
* *[!UICONTROL FTP SSL](Actuellement en version bêta) :* Pour envoyer le rapport terminé à un ou plusieurs emplacements SSL FTP, que vous indiquez dans la variable **[!UICONTROL Destination Name]** champ .
* *[!UICONTROL Email]:* Pour indiquer la ou les adresses électroniques auxquelles envoyer les rapports ou notifications terminés si le rapport est annulé en raison d’erreurs. Pour spécifier plusieurs adresses, séparez-les par des virgules ou des espaces.

>[!NOTE]
>
> Vous ne pouvez pas modifier le type de destination une fois le rapport enregistré.

**[!UICONTROL Destination Name]:** (Types de destination S3, FTP, sFTP et FTP SSL uniquement) Les noms des destinations de rapport vers lesquelles le rapport personnalisé sera envoyé.

* Pour spécifier une destination existante, sélectionnez un nom de destination dans la liste. Vous pouvez sélectionner plusieurs noms de destination séparément.

* Pour créer une destination :

   1. Cliquez sur **Ajouter une nouvelle destination**.

   1. Saisissez le [paramètres de destination du rapport](/help/dsp/reports/report-destinations/report-destination-settings.md), puis cliquez sur **Enregistrer**.

   1. Dans les paramètres du rapport, cliquez sur **Actualisez Les Noms De Destination.**

      La nouvelle destination est désormais disponible dans la liste des destinations existantes et vous pouvez éventuellement l’ajouter au rapport.

**[!UICONTROL Frequency]:** (Pour chaque [!UICONTROL Destination Name] À quelle fréquence envoyer le rapport à la destination : *[!UICONTROL Once]*, *[!UICONTROL Daily]*, *[!UICONTROL Weekly]* ou *[!UICONTROL Monthly]*.

## [!UICONTROL Save Report] Section

**[!UICONTROL Send & Save]:** Quand envoyer le rapport : *[!UICONTROL On Schedule]* ou *[!UICONTROL Run Now]*. Les rapports planifiés seront remis avant 9h00 dans le fuseau horaire du compte.

>[!NOTE]
>
>Vous pouvez [exécuter un rapport personnalisé à tout moment ;](report-run-now.md) de la [!UICONTROL Reports] vue.

>[!MORELIKETHIS]
>
>* [À propos des rapports personnalisés](/help/dsp/reports/report-about.md)
>* [Créer un rapport personnalisé](/help/dsp/reports/report-create.md)
>* [Duplication d’un rapport personnalisé](/help/dsp/reports/report-copy.md)
>* [Modifier un rapport personnalisé](/help/dsp/reports/report-edit.md)
>* [Exécution d’un rapport personnalisé](/help/dsp/reports/report-run-now.md)
>* [Paramètres des rapports personnalisés](/help/dsp/reports/report-settings.md)
>* [À propos des destinations de rapport](/help/dsp/reports/report-destinations/report-destination-about.md)

* [Colonnes de rapport disponibles](/help/dsp/reports/report-columns.md)
