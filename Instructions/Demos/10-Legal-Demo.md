---
demo:
  title: Démonstration pour le service juridique
---

[Revenir à l’index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# Démonstration pour le service juridique

**Scénario :**  

Vous êtes conseiller juridique chez Contoso, et chargé de déterminer si le logiciel d’analyse par IA des C.V. de l’entreprise est conforme à la Législation sur l’IA de l’UE. Votre objectif est d’effectuer des recherches sur les risques juridiques, de rédiger un résumé et de communiquer des recommandations à la direction.

## Configuration de la démonstration

Il n’existe aucun exemple de documents requis pour cette démonstration.

## Démonstrations

### Copilot Chat

Commençons par effectuer des recherches sur la Législation sur l’IA et son impact potentiel sur l’outil IA de recrutement de Contoso.

1. Ouvrez un navigateur et accédez à [M365copilot.com](https://m365copilot.com/).

1. Vérifiez que **Mode web** est sélectionné.

    ![Capture d’écran montrant l’onglet Mode web.](../Prompts/Media/web-mode.png)

1. Dans la fenêtre de l’invite, tapez le texte suivant :

    ```text
      Contoso is launching an AI Resume Screening Software to evaluate job applicants. As a legal advisor, I need to assess whether it complies with the EU Artificial Intelligence Act. Summarize key provisions related to AI in hiring, compliance requirements for high-risk systems, and potential legal risks.
    ```

1. Passez en revue la réponse de Copilot et notez sur les risques juridiques et les exigences de conformité pertinents.

1. Nous allons maintenant poser une série de questions de suivi à Copilot pour recueillir plus d’informations :

    ```text
    Does the AI Act classify resume screening software as a high-risk AI system?
    ```

    ```text
    What are the key obligations for high-risk AI systems under the AI Act?
    ```

    ```text
    Are there any exemptions in the AI Act that could apply to Contoso’s system?
    ```

1. Demandez maintenant au copilote de résumer toutes les informations obtenues jusqu’à présent :

    ```text
    Summarize all the information we've discussed into a structured list, ensuring no key details are missed. Then, export the summary to a Word document
    ```

1. Sélectionnez le lien hypertexte fourni par le copilote pour le nouveau document Word afin de l’ouvrir.

1. Une fois ouvert, sélectionnez **Activer les modifications**, puis activez l’option « Enregistrement automatique ». Sélectionnez votre compte OneDrive lorsque vous y êtes invité.

1. Copiez l’URL partagée pour l’utiliser à l’étape suivante. (Activez l’enregistrement automatique et sélectionnez votre compte OneDrive si vous y êtes invité.)

    ![Partagez un lien.](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Copilot dans Word

À présent, nous allons rédiger un résumé décrivant les risques juridiques et les recommandations pour la direction de Contoso.

1. Ouvrez une nouvelle instance de Word dans votre navigateur ou votre application de bureau.

1. Dans la zone d’invite **« Décrivez ce que vous souhaitez écrire »,** tapez ce qui suit :

    ```text
    Reference the following document [Link to exported Copilot Chat summary from the first task] and draft an executive summary outlining key legal risks, compliance requirements, and recommendations for Contoso’s AI Resume Screening Software.
    ```

    > **REMARQUE :** joignez le document ou collez le lien partagé directement dans l’invite pour vous assurer que Copilot peut accéder au contenu approprié.

1. Passez en revue la sortie de Copilot. Avant de sélectionner **Conserver**, affinez la réponse en demandant à Copilot :

    ```text
    Add a section on the potential business impact of these compliance requirements.
    ```

1. Autres affinements facultatifs :

    - Demandez à Copilot de reformuler des sections pour leur donner un ton plus professionnel.
    - Demandez une version plus courte et plus concise si le résumé est trop long.
    - Complétez par des sections supplémentaires.

1. Après avoir examiné et finalisé le document, **copiez le résumé généré** dans le presse-papiers pour l’utiliser dans la démonstration suivante.

### Copilot dans Outlook

Enfin, nous allons rédiger un e-mail à la direction de Contoso pour résumer nos résultats et les étapes suivantes.

1. Ouvrez Outlook (dans votre navigateur ou votre application de bureau).

1. Sélectionnez **Nouveau courrier**.

1. Sélectionnez **Copilot** dans le ruban. Dans le menu déroulant, choisissez **Rédiger avec Copilot**.

1. Dans la fenêtre d’invite **« Que voulez-vous indiquer dans cet e-mail ? »** tapez :

   ```text
    Draft an email to Contoso’s executive leadership summarizing our legal assessment of the AI Resume Screening Software under the EU AI Act. Use the following executive summary as a reference.

    [paste Executive Summary from the previous task]

    Conclude the email with a request for leadership’s input on the next steps, including a proposed compliance review meeting.
   ```

    > **REMARQUE :** collez le contenu du résumé que vous avez copié dans la démonstration précédente.

1. Une fois le brouillon généré, vous pouvez utiliser la fonctionnalité **Ajuster** pour modifier le ton, la longueur ou le niveau de formalité.

[Revenir à l’index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
