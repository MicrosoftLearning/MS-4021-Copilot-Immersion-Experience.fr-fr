---
demo:
  title: Démonstration pour le service Opérations
---

[Revenir à l’index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# Démonstration pour le service Opérations

## Scénario

Vous êtes un responsable des opérations chez Contoso, responsable de l’approvisionnement des fournisseurs et de l’exécution des projets. Votre objectif est de passer en revue les anciens appels d’offres, d’extraire les critères de sélection clés et de rédiger un nouvel appel d’offres pour une initiative à venir.

## Configuration de la démonstration

Vous trouverez les exemples de documents dans le référentiel GitHub MS-4021 [ici](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles) :

Les fichiers spécifiques nécessaires pour cette démonstration sont les suivants :

- [Contoso_Completed_RFP.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_Completed_RFP.docx)

- [Project_Guidelines_Contoso.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Project_Guidelines_Contoso.docx)

- [Contoso_RFP_Template.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_RFP_Template.docx)

> **REMARQUE :** la synchronisation de ces fichiers sur OneDrive peut prendre jusqu’à 10 minutes après le téléchargement. Pour éviter les retards pendant la démonstration, assurez-vous que ces fichiers sont téléchargés et disponibles dans votre OneDrive bien à l’avance. Si les fichiers ne sont pas disponibles, ouvrez les documents et copiez les liens de fichiers partagés à utiliser dans la démonstration.

## Démonstrations

### Copilot dans Word

Commençons par poser à Copilot pour Word quelques questions sur un document d’appel d’offres.

1. Ouvrez Word (dans votre navigateur ou votre application de bureau).
1
1. Ouvrez le document suivant : [Contoso_Completed_RFP.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_Completed_RFP.docx)

1. Dans le ruban Word, sélectionnez l’icône Copilot pour ouvrir le volet de conversation.

    ![Capture d’écran montrant l’onglet Mode travail.](../Demos/Media/copilot-ribbon-word.png)

1. Dans le volet Conversation, sélectionnez ou entrez l’invite :

   ```text
   Summarize this document
   ```

1. Entrez ensuite l’invite suivante :

   ```text
   Analyze this document and generate a categorized list of required items needed to create an RFP.
   ```

1. Ensuite, demandez à Copilot de créer un modèle d’appel d’offres en entrant :

   ```text
   Analyze this document and create an RFP template based on the content.
   ```

    > **REMARQUE :** il n’est pas nécessaire de copier le contenu généré, car nous allons utiliser un document de modèle précréé dans la démonstration suivante. Toutefois, vous pouvez montrer comment copier la réponse de Copilot ou l’insérer dans le document si cela est pertinent pour votre audience.

### Copilot Chat

Maintenant que nous avons résumé le document d’appel d’offres et créé un modèle d’appel d’offres, utilisons Copilot Chat pour résumer les exigences de projet pour un nouveau appel d’offres.

1. Ouvrez un navigateur et accédez à [M365copilot.com](https://m365copilot.com/).  

1. Vérifiez que **Mode web** est sélectionné.

    ![Capture d’écran montrant l’onglet Mode web.](../Prompts/Media/web-mode.png)

1. Entrez l’invite suivante :

   ```text
   Summarize [Project_Guidelines_Contoso.docx] highlighting the key objectives, scope, implementation timeline, budget, compliance needs, and vendor selection criteria in a bulleted list.
   ```

    > **REMARQUE :** les crochets indiquent qu’un document est référencé. Utilisez le lien : [Project_Guidelines_Contoso.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Project_Guidelines_Contoso.docx)

1. Ensuite, demandez à Copilot d’extraire les critères de sélection des fournisseurs :

   ```text
   Extract and summarize the key vendor selection criteria from this document, including weight percentages and evaluation factors.
   ```

1. Puis demandez à Copilot de créer un appel d’offres en fonction des instructions du projet :

   ```text
   Using the project requirements outlined above, draft an RFP using the following template: [Contoso_RFP_Template.docx].
   ```

    > **REMARQUE :** les crochets indiquent qu’un document est référencé.

1. **Copiez l’appel d’offres généré** dans le presse-papiers pour l’utiliser dans la démonstration suivante.

1. Si vous le souhaitez, demandez à Copilot d’exporter l’appel d’offres généré vers un document Word.

### Copilot dans Outlook

Enfin, utilisez Copilot pour Outlook afin de rédiger un e-mail aux fournisseurs potentiels résumant le document d’appel d’offres.

1. Ouvrez Outlook (dans votre navigateur ou votre application de bureau).

1. Sélectionnez **Nouveau courrier**.

1. Sélectionnez **Copilot** dans le ruban. Dans le menu déroulant, choisissez **Rédiger avec Copilot**.

1. Dans la fenêtre d’invite **« Que voulez-vous indiquer dans cet e-mail ? »** tapez :

   ```text
   Draft an email to potential suppliers summarizing the RFP below:

   [paste contents of RFP]
   ```

    > **REMARQUE :** collez le contenu de l’appel d’offres que vous avez copié dans la démonstration précédente.

1. Une fois le brouillon généré, vous pouvez utiliser la fonctionnalité **Ajuster** pour modifier le ton, la longueur ou le niveau de formalité.

[Revenir à l’index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
