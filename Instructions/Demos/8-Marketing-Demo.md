---
demo:
  title: Démonstration pour le service marketing
---

[Revenir à l’index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# Démonstration pour le service marketing

**Scénario :**  

Vous êtes responsable des opérations chez Contoso, responsable de la gestion de l’approvisionnement des fournisseurs et de l’exécution des projets. Votre objectif est d’analyser les anciens appels d’offres, d’extraire les critères de sélection clés et de développer un nouvel appel d’offre pour une initiative à venir.

## Configuration de la démonstration

Vous trouverez les exemples de documents dans le référentiel GitHub MS-4021 [ici](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles) :

Les fichiers spécifiques nécessaires pour cette démonstration sont les suivants :

- [Promotion_Plan_for_Chai_Tea_in_Latin_America.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Promotion_Plan_for_Chai_Tea_in_Latin_America.docx)

- [Mystic_Spice_Premium_Chai_Tea_product_description.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Mystic_Spice_Premium_Chai_Tea_product_description.docx)

- [Contoso_Chai_Tea_market_trends.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_Chai_Tea_market_trends.docx)

- [Contoso_Chai_Tea_social_marketing_trends.xlsx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_Chai_Tea_social_marketing_trends.xlsx)

> **REMARQUE :** la synchronisation de ces fichiers sur OneDrive peut prendre jusqu’à 10 minutes après le téléchargement. Pour éviter les retards pendant la démonstration, assurez-vous que ces fichiers sont téléchargés et disponibles dans votre OneDrive bien à l’avance. Si les fichiers ne sont pas disponibles, ouvrez les documents et copiez les liens de fichiers partagés à utiliser dans la démonstration.

## Démonstrations

### Copilot dans Word

Utilisez Copilot pour Word afin de rédiger un rapport détaillé d’analyse du marché et de réfléchir à des idées de campagne marketing créatives adaptées au marché latino-américain.

1. Ouvrez Word (dans votre navigateur ou votre application de bureau).

1. Dans la zone d’invite **Décrivez ce que vous souhaitez écrire**, tapez ce qui suit :

    ```text
    Create a Market Analysis report for Mystic Spice Premium Chai Tea using the attached files. Include the product description, market trend analysis, and a promotion plan for Latin America.

    [Promotion_Plan_for_Chai_Tea_in_Latin_America.docx], [Mystic_Spice_Premium_Chai_Tea_product_description.docx], [Contoso_Chai_Tea_market_trends.docx]
    ```

    > **REMARQUE :** les crochets indiquent qu’un document est référencé. Lorsque vous référencez un document, vous pouvez coller le lien partagé directement ou référencer le nom du fichier s’il est disponible dans votre OneDrive.

1. Demandez à Copilot de créer une section pour ajouter des idées de campagne sur les réseaux sociaux :

    Entrez l’invite suivante :

    ```text
    Draft a new section for social media campaigns to promote Mystic Spice Premium Chai Tea. Include a brief description of 2-3 campaign ideas, each with a unique focus. For each campaign, provide a tagline that reflects its theme and resonates with our target audience of young professionals and tea enthusiasts.
    ```

1. Enregistrez ce nouveau document sous **LATAM_Market_Analysis.docx**.

### Copilot Chat

Utilisez Copilot Chat pour évaluer l’efficacité des campagnes sur les réseaux sociaux proposées et affiner les stratégies de pertinence culturelle sur le marché LATAM.

1. Ouvrez un navigateur et accédez à [M365copilot.com](https://m365copilot.com/).

1. Vérifiez que Mode web est sélectionné.

    ![Capture d’écran montrant l’onglet Mode web.](../Prompts/Media/web-mode.png)

1. Dans la fenêtre de l’invite, tapez le texte suivant :

    ```text
    Review the social media campaigns outlined in the Market Analysis Report for Mystic Spice Premium Chai Tea.docx. Evaluate which campaign might resonate best with the LATAM market based on cultural relevance, target audience preferences, and alignment with regional trends. Provide reasons for your choice and suggest any adjustments to improve its impact.
    ```

    > **REMARQUE :** n’envoyez pas encore l’invite. Passez à l’étape suivante pour charger le fichier.

1. Sélectionnez **Ajouter du contenu** et chargez **LATAM_Market_Analysis.docx** que vous avez enregistré dans votre OneDrive dans la démonstration précédente. Puis envoyez l’invite.

    ![Ajouter du contenu sur Copilot Chat.](../Demos/Media/add-content-copilot-chat.png)

1. Copilot recommande l’une des campagnes sur laquelle se concentrer et fournit des suggestions d’amélioration. Dans l’invite suivante, nous voulons que Copilot suggère un slogan de campagne marketing pour cette nouvelle idée :

    ```text
    Generate a catchy marketing slogan for the [Campaign name - e.g., 'Morning Motivation'] campaign that highlights its unique value proposition and resonates with the LATAM market. Ensure the slogan reflects a vibrant and culturally relevant tone that appeals to young professionals.
    ```

1. Si vous le souhaitez, pour la dernière invite, vous pouvez demander à Copilot de générer une nouvelle vidéo pour la campagne :

    Dans Copilot Chat, sur le côté droit, sélectionnez l’**agent Créateur visuel** :

    ![Agent de créateur de vidéo.](../Demos/Media/video-creator.png)

    Ensuite, entrez l’invite suivante :

    ```text
    Create a captivating social media video for Mystic Spice Chai Tea that highlights its unique flavor and vibrant appeal. The video should feature eye-catching visuals, with colors, and themes that resonate with young professionals and tea enthusiasts.
    ```

### Copilot dans Excel

1. Vérifiez que vous avez téléchargé [Contoso_Chai_Tea_market_trends_2023.xlsx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/Contoso_Chai_Tea_market_trends_2023.xlsx) et ouvrez le document dans Excel (sur le web ou dans l’application de bureau).

1. Dans le ruban, sélectionnez **Copilot** pour ouvrir le volet Copilot.

1. Tapez l’invite suivante dans Excel :

    ```text
    On average, how many sales do we get per social media campaign view?
    ```

1. Ensuite, demandez à Copilot de comparer les ventes à l’engagement sur les réseaux sociaux :

    ```text
    Can you show a correlation between social media engagement and sales?
    ```

1. Tapez ensuite l’invite suivante :

    ```text
    How many social media campaign views did we have from September to December?
    ```
