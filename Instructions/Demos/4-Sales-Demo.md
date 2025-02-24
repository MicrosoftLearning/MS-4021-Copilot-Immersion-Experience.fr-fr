---
demo:
  title: Démonstration pour le service commercial
---

[Revenir à l’index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# Démonstration pour le service commercial

**Scénario :**  

Vous faites partie du service commercial d’une entreprise de recharge de véhicules électriques et développez un plan stratégique pour l’année à venir.

## Configuration de la démonstration

Vous trouverez les exemples de documents dans le référentiel GitHub MS-4021 [ici](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles) :

Les fichiers spécifiques nécessaires pour cette démonstration sont les suivants :

- [Charger_sales_report_2022-2024.xlsx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Charger_sales_report_2022-2024.xlsx)

> **REMARQUE :** la synchronisation de ces fichiers sur OneDrive peut prendre jusqu’à 10 minutes après le téléchargement. Pour éviter les retards pendant la démonstration, assurez-vous que ces fichiers sont téléchargés et disponibles dans votre OneDrive bien à l’avance. Si les fichiers ne sont pas disponibles, ouvrez les documents et copiez les liens de fichiers partagés à utiliser dans la démonstration.

## Démonstrations

### Copilot Chat

1. Ouvrez un navigateur et accédez à [M365copilot.com](https://m365copilot.com/).

1. Vérifiez que Mode web est sélectionné.

    ![Capture d’écran montrant l’onglet Mode web.](../Prompts/Media/web-mode.png)

1. Commençons par demander à Copilot d’effectuer des recherches sur une métrique clé. Dans le champ d’invite **Copilot Chat**, entrez :

    ```text
    What is the ratio of EV cars to EV chargers by region in the US for the past 3 years? Please show it in a table organized by region.
    ```

    ![Capture d’écran montrant l’invite Copilot Chat sur la recharge de véhicules électriques.](../Demos/Media/copilot-chat-ev-charger-prompt.png)

1. Nous allons maintenant comparer les tendances nationales aux performances des ventes de votre entreprise. Vous allez charger le jeu de données fourni et demander à Copilot de visualiser les données :

    Dans le champ d’invite, tapez :

    ```text
    I need to know the quarterly trends for each of our sales regions. Create a quarterly revenue line graph for the past 2 years based on:
    ```

    > **REMARQUE :** n’envoyez pas encore l’invite. Passez à l’étape suivante pour charger le fichier.

1. Sélectionnez **Ajouter du contenu** et chargez [**Charger_sales_report_2022-2024.xlsx**](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/Resourcefiles/Charger_sales_report_2022-2024.xlsx). Puis envoyez l’invite.

    ![Ajouter du contenu sur Copilot Chat.](../Demos/Media/add-content-copilot-chat.png)

1. Nous allons aller plus loin en demandant à Copilot de suggérer des recommandations exportées dans un document Word:

    Dans le champ d’invite, tapez :

    ```text
    Based on the trend, suggest two ways I can increase EV charger sales in the Mountain and Midwest regions. Export the recommendations to a Word Document.
    ```

1. Sélectionnez le lien hypertexte fourni par Copilot pour le nouveau document Word afin de l’ouvrir.

1. Une fois ouvert, sélectionnez **Activer les modifications**, puis activez l’option « Enregistrement automatique ». Sélectionnez votre compte OneDrive lorsque vous y êtes invité.


### Copilot dans Word

Nous demanderons maintenant à Copilot de développer ces stratégies et de rédiger des propositions sur la façon de les implémenter.

1. Le document Word généré à partir de la démonstration précédente doit déjà être ouvert. Si ce n’est pas le cas, ouvrez-le maintenant (dans votre navigateur ou votre application de bureau).

1. Cliquez dans le corps du document et sélectionnez l’icône Copilot.

    Tapez l’invite suivante :

    ```text
    Draft a detailed proposal on how we could implement each of the strategies outlined in this document. Ensure the plan is actionable and includes resource requirements, timelines, and key stakeholders.
    ```

1. Sélectionnez **Conserver** ou, si le temps le permet, montrez comment adapter le document à l’aide de Copilot.

1. Une fois terminé, enregistrez le document sous **EV Sales Proposal.docx** et copiez l’URL partagée à utiliser à l’étape suivante (activez l’enregistrement automatique et sélectionnez votre compte OneDrive).

    ![Partagez un lien.](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

    > **Conseil pour le formateur :** utilisez cette étape pour montrer comment Copilot s’appuie sur des sorties antérieures, en affinant des idées dans une proposition cohérente.

### Copilot dans PowerPoint

1. Lancez Microsoft PowerPoint à partir de votre navigateur [PowerPoint.new](https://PowerPoint.new) ou utilisez l’application de bureau.

1. Ouvrez une nouvelle présentation vierge.

1. Dans le volet Copilot, sélectionnez l’invite « Créez une présentation à partir d’un fichier ».

1. Collez le lien **EV Sales Proposal.docx** après « Créer une présentation à partir de » et sélectionnez **Envoyer**.

    L’invite complète doit ressembler à ce qui suit :

    ```text
    Create a presentation from [Link to EV Sales Proposal.docx].
    ```

1. Copilot commence à générer des diapositives basées sur l’appel d’offres pour véhicules électriques, en fournissant un plan avec des caractéristiques telles que les notes de l’intervenant, les images, les dispositions des diapositives et une étiquette de confidentialité générale.

    > **REMARQUE :** la génération de diapositives peut prendre jusqu’à deux minutes, en fonction de la complexité et du nombre de diapositives du document.

[Revenir à l’index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
