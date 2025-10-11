---
demo:
  title: Créez un agent avec Copilot Studio Lite
---

[Revenir à l’index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

---

# Créez et publiez un agent à l'aide de Copilot Studio Lite

Cette démonstration explique comment créer un assistant virtuel à l'aide de Copilot Studio Lite via Copilot Chat et le publier sur Microsoft 365 Copilot.

## Configuration de la démonstration

Pour réaliser ces démonstrations, vous devrez télécharger les fichiers suivants :

- [**Delivery Drone Press Release.docx**](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/raw/master/ResourceFiles/Delivery_Drone_Press_Release.docx)
- [**Delivery Drone Troubleshooting.docx**](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/raw/master/ResourceFiles/Delivery_Drone_Troubleshooting.docx)
- [**Delivery Drone SOP.docx**](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/raw/master/ResourceFiles/Delivery_Drone_SOP.docx)
- [**Upselling Opportunities.docx**](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/raw/master/ResourceFiles/Upselling_Opportunities.docx)
- [**Delivery Drone FAQ.docx**](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/raw/master/ResourceFiles/Delivery_Drone_FAQ.docx)

> **CONSEIL :** Avant de présenter la démonstration, vous pouvez créer un site SharePoint dans votre environnement de démonstration pour y stocker tous les fichiers et y accéder facilement. Vous pouvez également stocker les fichiers localement et les référencer directement dans vos prompts à l’aide de **/**.

## Points de discussion

Copilot Studio Lite nous permet de créer des copilotes personnalisés, adaptés à des projets, des services ou des bases de connaissances spécifiques. Nous pouvons leur attribuer une personnalité, définir leurs limites et leur fournir des documents spécifiques afin de garantir des réponses de haute qualité et détaillées.

Dans cette version de démonstration, nous allons créer un assistant virtuel pour le projet de livraison par drone ReleCloud. L’assistant connaîtra tout ce que nous avons téléchargé et aidera à répondre aux questions de l’équipe, ce qui permettra de gagner du temps et d’améliorer la productivité.

## Étapes de la version de démonstration

### Étape 1 – Accédez à Copilot Studio Lite

1. Accédez à [https://m365.cloud.microsoft/chat](https://m365.cloud.microsoft/chat) et sélectionnez **Créer un agent** dans le volet de navigation.

    ![Capture d’écran montrant le lien pour créer un assistant.](../Prompts/Media/create-agent.png)

1. Connectez-vous à l'aide de vos informations d'identification.

### Étape 2 : définissez votre assistant

1. Ajoutez la description suivante lorsque vous y êtes invité :

    ```text
    You're a virtual project manager assistant for our drone delivery project. You know everything about the project from the documents we've shared with you, and are happy to help team members get the information they need.
    ```

   ![Capture d’écran montrant la fonctionnalité Décrire.](../Prompts/Media/create-agent-through-describe.png)

1. Nommez l’assistant :

    ```text
    Drone Delivery Assistant
    ```

1. Si une confirmation est demandée :

    ```text
    Yes, thank you
    ```

1. Si l’on vous demande ce qu’il faut éviter ou mettre en avant :

    ```text
    Please be clear and concise and avoid long answers. Where possible, refer primarily to the knowledge shared with you. If you don't know the answer, refer them to the drone delivery project manager.
    ```

1. Si l’on vous demande le ton à adopter :

    ```text
    Friendly and professional
    ```

> **IMPORTANT :**  Selon votre environnement, toutes ces options ne vous seront pas nécessairement proposées. Si vous n’y êtes pas invité, vous pouvez ajouter ces informations à l’aide de l’onglet **Configurer** dans Copilot Studio lite.

### Étape 3 : configurez l’assistant

1. Cliquez sur **Configurer** pour ouvrir l’éditeur d’assistant.
1. Passez en revue et mettez éventuellement à jour la section **Instructions** :

    ```text
    Your name is Drone Delivery Project Manager Assistant. You serve as a virtual project manager for the ReleCloud drone delivery project, with comprehensive knowledge from shared documents. Be clear and concise, avoiding long answers. If the answer is unknown, refer to the drone delivery project manager.
    ```

1. Faites défiler vers le bas jusqu’à la section **Connaissances** et cliquez sur la bulle de texte **Rechercher par nom ou entrer une URL**. Sélectionnez **Fichiers** et ajoutez les documents suivants à la base de connaissances de l’assistant :

    - **Delivery Drone Press Release.docx**
    - **Delivery Drone Troubleshooting.docx**
    - **Delivery Drone SOP.docx**
    - **Upselling Opportunities.docx**
    - **Delivery Drone FAQ.docx**

        ![Capture d’écran montrant les sources de connaissances.](../Prompts/Media/knowledge-sources.png)

### Étape 4 : testez votre assistant

Dans le volet de test droit, essayez de poser quelques-unes des questions suivantes :

- `Tell me about the ReleCloud Delivery Drone.`
- `How do I fix the drone error code D-101?`
- `What are the upsell opportunities for ReleCloud?`
- `What’s the duration of Phase 1 of the delivery drone project?`

> **IMPORTANT :**   L’assistant peut mettre un certain temps à traiter les documents et à fournir des réponses précises. Si vous recevez un message d’erreur, veuillez patienter quelques minutes et réessayer.

> **CONSEIL :** Vous pouvez également effectuer un test via Microsoft Teams une fois que l’assistant est en ligne.

### Étape 5 : publier et partager

1. Cliquez sur **Créer** pour publier l’agent.
1. Sélectionnez **Modifier les paramètres de partage** et choisissez **Tout le monde dans votre organisation**.
1. Copiez le lien de partage et collez-le dans une conversation Teams pour y accéder facilement.

Une fois en ligne, vous pouvez interagir avec l’assistant dans la conversation Teams ou via @mentions.

[Revenir à l’index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
