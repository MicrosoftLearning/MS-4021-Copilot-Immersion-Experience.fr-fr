---
demo:
  title: Démonstration informatique
---

[Revenir à l’index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# Démonstration informatique

**Scénario :**  

En tant que responsable de l’infrastructure informatique, vous envisagez d’installer un nouveau produit de sécurité réseau dans votre réseau d’entreprise.

## Configuration de la démonstration

Vous trouverez les exemples de documents dans le référentiel GitHub MS-4021 [ici](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles) :

Les fichiers spécifiques nécessaires pour cette démonstration sont les suivants :

- [Contoso_CipherGuard_Product_Specification.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_CipherGuard_Product_Specification.docx)

> **REMARQUE :** la synchronisation de ces fichiers sur OneDrive peut prendre jusqu’à 10 minutes après le téléchargement. Pour éviter les retards pendant la démonstration, assurez-vous que ces fichiers sont téléchargés et disponibles dans votre OneDrive bien à l’avance. Si les fichiers ne sont pas disponibles, ouvrez les documents et copiez les liens de fichiers partagés à utiliser dans la démonstration.

## Démonstrations

### Copilot Chat

Commençons par demander à Copilot de créer un plan d’implémentation de projet.

1. Ouvrez un navigateur et accédez à [M365copilot.com](https://m365copilot.com/).

1. Vérifiez que Mode web est sélectionné.

    ![Capture d’écran montrant l’onglet Mode web.](../Prompts/Media/web-mode.png)

1. Dans la fenêtre de l’invite, tapez le texte suivant :

    ```text
    You are an IT infrastructure manager at Contoso. Your task is to create a detailed project implementation plan for installing a new network security product in your corporate network. Your plan should include key milestones, resource allocation, potential risks, and a timeline to ensure successful deployment and minimal disruption to operations.
    ```

    > **REMARQUE :** les invites basées sur des rôles aident Copilot à comprendre les responsabilités et le contexte de l’utilisateur, ce qui améliore la pertinence et la spécificité du résultat.

1. Nous allons maintenant affiner le plan de projet en demandant à Copilot d’ajouter de nouvelles sections au plan de projet :

    Entrez l’invite suivante :

    ```text
    Please add the following sections to the existing plan: testing and QA, training, communication, documentation and reporting, stakeholder analysis, project timeline, and risk assessment and mitigation. Ensure these sections provide detailed action steps and align with the existing content. Avoid duplicating any items already included in the original plan.
    ```

1. Enfin, demandez à Copilot de générer le plan de projet proposé dans un document Word :

    Entrez l’invite suivante :

    ```text
    Please export the project plan to a Word document.
    ```

1. Enregistrez le document Word généré sous **Project_Implementation_Plan.docx**. Copiez l’URL partagée à partir du document (activez l’enregistrement automatique et sélectionnez votre compte OneDrive si vous y êtes invité).

    ![Partagez un lien.](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Copilot dans Word

Nous demanderons maintenant à Copilot de développer ces stratégies et de rédiger des propositions sur la façon de les implémenter.

1. Ouvrez Word (dans votre navigateur ou votre application de bureau).

1. Dans la zone d’invite **Décrivez ce que vous souhaitez écrire**, tapez ce qui suit :

    ```text
    Using the Contoso [/CipherGuard Product Specification.docx] and the 'Project Implementation Plan' template provided in [paste in link to Project_Implementation_Plan.docx], draft a comprehensive project implementation plan for deploying Contoso CipherGuard. Ensure the plan aligns with the product specifications and follows the structure outlined in the template.
    ```

    > **REMARQUE :** les crochets indiquent qu’un document est référencé.
    > 1. CipherGuard Product Specification.docx = [Contoso_CipherGuard_Product_Specification.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_CipherGuard_Product_Specification.docx)
    > 1. Project Implementation Plan.docx = Utiliser le lien copié dans la démonstration précédente.
    > Lorsque vous référencez un document, vous pouvez coller le lien directement ou référencer le nom du fichier s’il est disponible dans votre OneDrive.

1. Sélectionnez **Conserver** ou, si le temps le permet, montrez comment adapter le document à l’aide de Copilot.

1. Une fois terminé, enregistrez le document sous **Contoso_Project_Plan.docx** et copiez l’URL partagée (activez l’enregistrement automatique et sélectionnez votre compte OneDrive si vous y êtes invité).

    ![Partagez un lien.](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Copilot dans PowerPoint

Nous allons maintenant utiliser Copilot pour générer une présentation PowerPoint basée sur la nouvelle proposition d’implémentation du produit Contoso CipherGuard.

1. Lancez Microsoft PowerPoint à partir de votre navigateur [PowerPoint.new](https://PowerPoint.new) ou utilisez l’application de bureau.

1. Ouvrez une nouvelle présentation vierge.

1. Dans le volet Copilot, sélectionnez l’invite « Créez une présentation à partir d’un fichier ».

1. Collez le lien partagé du document **Contoso_Project_Plan.docx**, puis sélectionnez **Envoyer**.

    L’invite complète doit ressembler à ce qui suit :

    ```text
    Create a presentation from [Link to Contoso_Project_Plan.docx].
    ```

1. Copilot commence à générer des diapositives basées sur le plan de projet, en fournissant un plan avec des caractéristiques telles que les notes de l’intervenant, les images, les dispositions des diapositives et une étiquette de confidentialité générale.

    > **REMARQUE :** la génération de diapositives peut prendre jusqu’à deux minutes, en fonction de la complexité et du nombre de diapositives du document.

[Revenir à l’index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
