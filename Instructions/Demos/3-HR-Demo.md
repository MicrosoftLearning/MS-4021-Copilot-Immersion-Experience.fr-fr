---
demo:
  title: Démonstration pour le service RH
---

[Revenir à l’index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# Démonstration pour le service RH

**Scénario :**  

Simplifiez le processus de recrutement d’une équipe de concepteurs d’expérience utilisateur en créant une description de la tâche personnalisée, en présélectionnant les candidats en fonction de leurs C.V. et en rédigeant une stratégie de recrutement pour une équipe cohérente.

## Configuration de la démonstration

Vous trouverez les exemples de documents dans le référentiel GitHub MS-4021 [ici](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles) :

Les fichiers spécifiques nécessaires pour cette démonstration sont les suivants :

- [Design_Team_Responsibilities.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Graphic_Design_Institute_Design_Team_Responsibilities.docx)

- [Resume_Patti_Fernandez.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Resume_Patti_Fernandez.docx)

- [Resume_Nestor_Wilke.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Resume_Nestor_Wilke.docx)

- [Resume_Holly_Dickson.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Resume_Holly_Dickson.docx)

- [Resume_Alex_Wilber.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Resume_Alex_Wilber.docx)

> **REMARQUE :** la synchronisation de ces fichiers sur OneDrive peut prendre jusqu’à 10 minutes après le téléchargement. Pour éviter les retards pendant la démonstration, assurez-vous que ces fichiers sont téléchargés et disponibles dans votre OneDrive bien à l’avance. Si les fichiers ne sont pas disponibles, ouvrez les documents et copiez les liens de fichiers partagés à utiliser dans la démonstration.

## Démonstrations

### Copilot dans Word

Commençons par demander à Copilot pour Word de générer une description de la tâche.

1. Ouvrez Word (dans votre navigateur ou votre application de bureau).

1. Dans la zone d’invite **« Décrivez ce que vous souhaitez écrire »,** tapez ce qui suit :

    ```text
    I'm the HR Manager at the Graphic Design Institute. We've currently started the hiring process for a new Senior Animation Designer. Please review the attached document outlining the job responsibilities for this role and generate a detailed job description based on this information.

    [copy link or reference file to Design_Team_Responsibilities.docx]
    ```

    > **REMARQUE :** joignez le fichier Design_Team_Responsibilities.docx ou collez le lien partagé directement dans l’invite pour vous assurer que Copilot a accès au contenu approprié.

1. Après avoir examiné et finalisé la description de la tâche, enregistrez le document sous **GDI_Job_Description.docx** et copiez l’URL partagée pour l’utiliser à l’étape suivante. (Activez l’enregistrement automatique et sélectionnez votre compte OneDrive si vous y êtes invité.)

    ![Partagez un lien.](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Copilot Chat

Ensuite, nous allons utiliser Copilot Chat pour comparer les C.V. que nous avons reçus pour la description de la tâche et identifier les meilleurs candidats.

1. Ouvrez un navigateur et accédez à [M365copilot.com](https://m365copilot.com/).

1. Vérifiez que Mode travail est sélectionné.

    ![Capture d’écran montrant l’onglet Mode web.](../Prompts/Media/work-mode.png)

1. Dans la fenêtre de l’invite, tapez le texte suivant :

    ```text
    We are hiring for the position of Senior Animation Designer. Please analyze the attached resumes and compare them to the requirements outlined in the job description provided here: [paste link to GDI_Job_Description.docx]. Rank the candidates from most qualified to least qualified, based on their alignment with the role.

    [Resume - Patti Fernandez
    Resume - Nestor Wilke
    Resume - Holly Dickson
    Resume - Alex Wilber]
    ```

    > **REMARQUE :** joignez les C.V. ou chargez-les dans la fenêtre d’invite. Vous pouvez également référencer chaque fichier à l’aide des liens partagés ou des noms de fichiers dans votre OneDrive.

1. Si vous le souhaitez, vous pouvez demander à Copilot Chat d’exporter sa réponse vers un document Word pour mettre en évidence cette fonctionnalité.

### Copilot pour Outlook

Enfin, utilisez Copilot pour Outlook afin de rédiger un e-mail à l’équipe de recrutement concernant les meilleurs candidats.

1. Ouvrez Outlook (dans votre navigateur ou votre application de bureau).

1. Sélectionnez **Nouveau courrier**.

1. Sélectionnez **Copilot** dans le ruban. Dans le menu déroulant, choisissez **Rédiger avec Copilot**.

1. Dans la fenêtre d’invite **« Que voulez-vous indiquer dans cet e-mail ? »** Fenêtre d’invite, tapez le texte suivant :

    ```text
    Please draft an email to the hiring team to share that Nestor Wilke and Patti Fernandez align best with the Senior Animation Designer role based on their qualifications. Include a recommendation to schedule interviews for these candidates and request feedback on next steps.
    ```

[Revenir à l’index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
