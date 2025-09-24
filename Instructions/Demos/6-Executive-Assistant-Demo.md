---
demo:
  title: Démonstration pour l’assistant de direction
---

[Revenir à l’index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# Démonstration pour l’assistant de direction

**Scénario :**

Vous avez été chargé de résumer la dernière transcription de la téléconférence sur les bénéfices pour les cadres. Cette tâche comprend l’extraction d’informations clés, la création d’un résumé et la préparation d’une réunion de suivi.

## Configuration de la démonstration

Vous trouverez les exemples de documents dans le référentiel GitHub MS-4021 [ici](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles) :

Les fichiers spécifiques nécessaires pour cette démonstration sont les suivants :

- [Microsoft_FY24_Second_Quarter_Earnings_Conference_Call_Transcript.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Microsoft_FY24_Second_Quarter_Earnings_Conference_Call_Transcript.docx)

> **REMARQUE :** la synchronisation de ces fichiers sur OneDrive peut prendre jusqu’à 10 minutes après le téléchargement. Pour éviter les retards pendant la démonstration, assurez-vous que ces fichiers sont téléchargés et disponibles dans votre OneDrive bien à l’avance. Si les fichiers ne sont pas disponibles, ouvrez les documents et copiez les liens de fichiers partagés à utiliser dans la démonstration.

## Étapes de la version de démonstration

### Copilot dans Word

Nous allons commencer par examiner la transcription de l’appel sur les revenus le plus récent et résumer les points clés pour les cadres.

1. Sélectionnez et ouvrez le fichier **Microsoft_FY24_Second_Quarter_Earnings_Conference_Call_Transcript.docx** dans Word (dans votre navigateur ou votre application de bureau).

    > **REMARQUE :** parcourez rapidement le document pour montrer à quel point il est volumineux et que le résumer n’est pas une tâche facile.

1. Dans le ruban, sélectionnez l’icône Copilot :

    ![Icône Copilot dans Word](../Demos/Media/Copilot-in-word-ribbon.png)

1. Le volet Copilot doit s’ouvre. Entrez le prompt suivant à l’endroit indiqué **+ Que souhaitez-vous que Copilot rédige ?**  :

    ```text
    Summarize the key points from the Microsoft FY24 Second Quarter Earnings Conference Call.
    ```

1. Imaginez que les cadres veulent connaître les propos de Satya Nadella lors de l’appel. Utilisez l’invite suivante :

    ```text
    Provide a brief summary of Satya Nadella's remarks during the earnings call.
    ```

   - Montrez comment Copilot inclut des références pour chaque puce, ce qui permet une navigation rapide vers des sections spécifiques.  
   - Cliquez sur une référence pour montrer comment Copilot vous amène instantanément au contenu pertinent dans le document.

1. Pour créer un rapport détaillé, demandez à Copilot :

    ```text
    Analyze the Microsoft FY24 Second Quarter Earnings Conference Call document to provide a comprehensive report that includes:
    - A summary of the key points from each speaker
    - Identification of the top three growth areas and their contributing factors.
    - A detailed breakdown of the financial performance, including revenue, operating income, and earnings per share.
    - Trends in AI adoption and its influence on Microsoft's business strategy.
    - A comparison of this quarter's performance with the same quarter last year, highlighting significant changes.
    - Key strategic initiatives and future outlook as discussed in the call.
    ```

    > **Conseil :** mentionnez qu’il s’agit d’une invite complexe. Copilot peut prendre un certain temps pour générer la réponse.

1. Une fois que Copilot a terminé l’analyse, sélectionnez l’icône **Copier** pour enregistrer les résultats en vue de l’étape suivante.

    ![Copiez les résultats.](../Demos/Media/Copilot-in-word-copy-results.png)

### Copilot Chat

Le rapport fourni par Word est un excellent point de départ, mais maintenant nous voulons utiliser Copilot Chat pour nous aider à créer un résumé.

1. Ouvrez un navigateur et accédez à [M365copilot.com](https://m365copilot.com/).

1. Vérifiez que **Mode web** est sélectionné.

    ![Capture d’écran montrant l’onglet Mode web.](../Prompts/Media/web-mode.png)

1. Collez la réponse de Copilot pour Word dans Copilot Chat avec l’invite suivante :

    ```text
    Based on the following information, provide an executive summary on the following information:

    [paste the Word output here]
    ```

    > **Remarque :** supprimez tout texte superflu du contenu copié pour plus de clarté.

1. Affinez le résumé dans un format concis :

    ```text
    Summarize this executive summary into a more concise format by focusing on the most critical insights and metrics for each speaker. Use a structured format with headings and bullet points to improve readability. Export to a Word document.
    ```

   - Si Copilot n’exporte pas le document, reformulez la demande : « Enregistrez ce résumé sous forme de document Word ».

1. Une fois le résumé terminé, demandez à Copilot :

    ```text
    Based on the summarized executive summary, generate 5-7 concise and impactful talking points my manager can use in their next leadership call. Focus on key achievements, growth areas, and strategic priorities.
    ```

### Copilot pour Outlook

Dans cette démonstration, nous allons utiliser Copilot pour Outlook afin d’organiser une réunion avec les cadres pour les informer de tout ce qui s’est passé au cours de la téléconférence sur les bénéfices du deuxième trimestre.

1. Ouvrez un navigateur et accédez à [outlook.office.com](https://outlook.office.com.com/).

1. Dans le ruban Copilot, sélectionnez l’icône Copilot pour ouvrir le volet Copilot.

1. Utilisez l’invite suivante pour planifier une synchronisation :

    ```text
    I need to schedule a 30-minute meeting with [/Pick a colleague] tomorrow afternoon to discuss the Second Quarter Earnings Conference Call. Can you suggest a time that works? If they are unavailable, provide an alternative.
    ```

1. Copilot suggère une heure et une date pour la réunion. L’invite affiche un élément de calendrier qui peut être envoyé ou modifié. Sélectionnez **Modifier**.

1. Passez à l’assistant Planification pour montrer que l’heure suggérée par Copilot convient au chef de projet. Vous êtes tous deux être libres.

1. Revenez à l’onglet événement, puis sélectionnez **Rédiger avec Copilot** dans le corps de l’événement.

1. Dans la fenêtre de l’invite, tapez le texte suivant :

    ```text
    I’m meeting with my boss to discuss key updates and strategic initiatives they missed from the Second Quarter Earnings Conference Call. Create an agenda to discuss financial performance, AI and technology integration, strategic acquisitions, productivity updates, and future outlook.
    ```

1. Si vous le souhaitez, avant de sélectionner **Conserver**, vous pouvez demander à Copilot d’allonger ou de raccourcir sa durée, ou de modifier le ton de l’agenda rédigé.

[Revenir à l’index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
