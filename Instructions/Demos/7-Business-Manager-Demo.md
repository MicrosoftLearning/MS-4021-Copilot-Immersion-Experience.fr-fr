---
demo:
  title: Démonstration pour les directeurs commerciaux
---

[Revenir à l’index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# Démonstration pour les directeurs commerciaux

**Scénario :**

Analysez les performances des ventes et les avis des clients pour résoudre un problème de produit, puis collaborez avec votre équipe pour planifier des améliorations.

## Configuration de la démonstration

Vous trouverez les exemples de documents dans le référentiel GitHub MS-4021 [ici](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles) :

Les fichiers spécifiques nécessaires pour cette démonstration sont les suivants :

- [EV_Charger_Sales_Analysis_v1.xlsx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/EV_Charger_Sales_Analysis_v1.xlsx)

> **REMARQUE :** la synchronisation de ces fichiers sur OneDrive peut prendre jusqu’à 10 minutes après le téléchargement. Pour éviter les retards pendant la démonstration, assurez-vous que ces fichiers sont téléchargés et disponibles dans votre OneDrive bien à l’avance. Si les fichiers ne sont pas disponibles, ouvrez les documents et copiez les liens de fichiers partagés à utiliser dans la démonstration.

## Étapes de la version de démonstration

### Copilot dans Excel

1. Lancez Excel (dans votre navigateur ou votre application de bureau) et ouvrez le fichier **EV_Charger_Sales_Analysis_v1.xlsx**.

1. **Accédez à l’onglet « Ventes par produit »** dans le fichier Excel.

1. Utilisez Copilot pour calculer les revenus mensuels :  

   Commençons par déterminer quelle catégorie de votre entreprise entraîne le plus de revenus. Cette feuille contient trois années de données de ventes, avec des milliers de lignes affichant les ventes par produit par mois. Bien qu’il s’agisse d’une tâche de routine, ce volume de données peut être complexe. Vous pouvez demander à Copilot de calculer rapidement les revenus mensuels par produit.

   Utilisez l’invite suivante :

   ```text
   Calculate monthly revenue by product and add a column with total revenue - refer to the Prices worksheet.
   ```

    - Copilot sait comment procéder et quelles données référencer dans les différents onglets.
    - Copilot crée un plan pour l’exécution de ces nombres, exécute ce plan en montrant son travail au fur et à mesure et vous invite à poser des questions ou à itérer sur la solution trouvée.
    - Cliquez sur **+Insérer une colonne**, puis revenez à l’onglet **Ventes par produit**.

1. Utilisez Copilot pour analyser les revenus en entrant l’invite suivante dans le volet Copilot :

    ```text
    What is the total revenue for each category so far in 2024?
    ```

    - Copilot exécute les nombres et crée un graphique à barres que vous pouvez ajouter à votre classeur.
    - Cliquez sur **+Ajouter à une nouvelle feuille**, puis revenez à l’onglet **Ventes par produit**.

1. À présent, utilisez Copilot pour mettre en évidence les produits avec des ventes faibles en entrant cette invite :

    ```text
    Highlight rows where the value in column H is less than $100K.
    ```

    - Copilot applique une mise en forme conditionnelle, ce qui vous aide à identifier les produits qui ne sont pas performants selon vos normes.

1. **Accédez à l’onglet « Commentaires »** pour analyser les commentaires des clients.

1. Demandez à Copilot de résumer les principales préoccupations en entrant l’invite suivante :

    ```text
    Summarize the top 3 customer concerns we should focus on.
    ```

    - Copilot analyse les commentaires et fait apparaître les trois principaux problèmes des clients. Il semble que la vitesse de chargement soit un problème émergent.

1. Ensuite, mettez en évidence les commentaires mentionnant la vitesse de chargement en entrant cette invite :

    ```text
    Highlight reviews that mention issues related to charging speeds.
    ```

    - Copilot met en évidence tous les commentaires pertinents dans le jeu de données.

### Copilot Chat

Maintenant que nous avons identifié la lenteur de charge comme un problème clé, utilisez **Copilot Chat** pour en savoir plus sur le problème et identifier les solutions potentielles.

1. Ouvrez un navigateur et accédez à [M365copilot.com](https://m365copilot.com/).  

1. Vérifiez que **Mode web** est sélectionné.  

    ![Capture d’écran montrant l’onglet Mode web.](../Prompts/Media/web-mode.png)

1. Pour résoudre ce problème, entrez l’invite suivante :
  
    ```text
    Research common issues with EV charger speeds and identify potential causes or solutions. Summarize findings in a format suitable for a business presentation. Highlight any relevant industry benchmarks or competitor data.
    ```

   - Passez en revue le résumé de Copilot et demandez des précisions sur le contexte ou des tendances récentes, si nécessaire.  

1. Si vous le souhaitez, affinez la sortie :
   - Demandez à Copilot d’indiquer les tendances ou technologies récentes en matière d’efficacité des chargeurs de véhicules électriques :

    ```text
    What are the latest innovations or technologies addressing slow EV charger speeds in 2024?
    ```

   - Demandez des informations sur les concurrents :

    ```text
    Assuming competitors in the EV charging market are improving speed by 20% annually, suggest how we could position our CC-2001 and CC-2000 models to stay competitive.
    ```

1. Demandez au copilote de trouver cinq questions stratégiques à poser au chef du projet concernant les chargeurs des véhicules électriques :

    ```text
    Based on this information, suggest 5 strategic questions to ask the product team during our meeting tomorrow. Focus on identifying root causes, assessing risks, and brainstorming potential improvements.
    ```

### Copilot dans Outlook

Dans cette démonstration, nous allons utiliser Copilot pour Outlook afin d’organiser une réunion avec le chef de projet responsable de la gamme de produits des chargeurs des véhicules électriques pour discuter des solutions potentielles.

1. Ouvrez un navigateur et accédez à [outlook.office.com](https://outlook.office.com.com/).

1. Dans le ruban Copilot, sélectionnez l’icône Copilot pour ouvrir le volet Copilot.

1. Dans la fenêtre de l’invite, tapez le texte suivant :

    ```text
    I need to schedule a meeting with [/Pick a colleague] tomorrow afternoon to discuss the EV charger issue reports. Can you suggest a time that works? If they are unavailable, please suggest an alternative time.
    ```

1. Copilot suggère une heure et une date pour la réunion. L’invite affiche un élément de calendrier qui peut être envoyé ou modifié, sélectionnez **Modifier**.

1. Passez à l’assistant Planification pour montrer que l’heure suggérée par Copilot convient au chef de projet. Vous êtes tous deux être libres.

1. Revenez à l’onglet événement, puis sélectionnez **Rédiger avec Copilot** dans le corps de l’événement.

1. Dans la fenêtre de l’invite, tapez le texte suivant :

    ```text
    Create an agenda for a meeting to discuss slow charging speeds with our CC-2001 and CC-2000 models. Include time for an introduction to the issue, a review of any available data or customer feedback, and a brainstorming session for potential solutions.  
    ```

1. Si vous le souhaitez, avant de sélectionner **Conserver**, vous pouvez demander au copilote d’allonger ou de raccourcir sa durée, ou de modifier le ton de l’agenda rédigé.

[Revenir à l’index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
