---
task:
  title: Expérience immersive – Assistants (dirigeants)
---

## Expérience immersive – Assistants (dirigeants)

Découvrez comment Microsoft 365 Copilot et Copilot Studio peuvent vous aider à relever un véritable défi professionnel en concevant un simple **assistant basé sur la récupération**. Cet exercice vous guidera dans l’identification d’un problème, son analyse, l’exploration des façons dont l’IA pourrait aider, puis la création d’un assistant conceptuel pour le résoudre.  

Vous allez effectuer quatre tâches :

- Identifier un problème lié au travail  
- Décomposer le problème et explorer les domaines dans lesquels l’IA pourrait être utile  
- Utiliser **Recherche** pour découvrir des informations et des idées de solutions  
- Concevoir et créer une maquette d’assistant basé sur la récupération dans **Copilot Studio**  

> **REMARQUE :** Des exemples de prompts sont fournis pour vous aider à démarrer. N’hésitez pas à les personnaliser pour les adapter à votre situation. 
>
> Si vous avez besoin d’aide pour générer ou améliorer des prompts, essayez l’<a href="https://appsource.microsoft.com/en-us/product/office/WA200007578" target="_blank">Assistant de requêtes</a><br>, qui peut suggérer, améliorer et évaluer les prompts afin que vous obteniez de meilleurs résultats avec Copilot.

### Tâche 1 : Identifiez un défi lié au travail  

Commencez par réfléchir à un problème réel que vous rencontrez dans votre travail, quelque chose qui vous ralentit ou qui rend l’accès à l’information plus difficile. Vous pouvez réfléchir individuellement ou utiliser **Copilot Chat** comme partenaire pour vous aider à générer des idées et identifier un défi où la récupération et l’organisation des connaissances pourraient faire la différence.  

Pour orienter votre réflexion, considérez les points suivants :  

- **Qu’est-ce qui fonctionne bien aujourd’hui ?**  
- **Qu’est-ce qui ne fonctionne pas bien ?**  
- **Dans quels domaines l’IA *pourrait* être utile ?**  

**Étapes :**  

- Ouvrez un nouvel onglet dans votre navigateur et accédez à [m365.cloud.microsoft/chat](https://m365.cloud.microsoft/chat).  
- Veillez à ce que l’onglet **Mode de travail** soit sélectionné dans **Copilot Chat** :  

   ![Capture d’écran montrant l’onglet Mode de travail dans Copilot Chat.](../Prompts/Media/work-mode.png)  

    **Exemple de prompt :**

   ```text
   I’m researching common day-to-day issues I face at work, such as processes, collaboration, or time management. Look at recent conversations from [Teams chats, Outlook emails, or other collaboration tools] related to [your role focus]. Summarize the key issues or pain points mentioned in the last 6 months. Show the results in a table with:  

    - Title: Short label for the issue  
    - Description: Brief summary of the challenge  
    - Frequency: How often it comes up (e.g., number of mentions)
   ```

### Tâche 2 : Décomposez le problème

À l’aide de **Copilot Chat**, prenez le défi que vous avez identifié dans la tâche 1 et divisez-le en plusieurs parties plus petites :

- Qu’est-ce qui rend ce problème difficile ?  
- Où l’information se bloque-t-elle ou se perd-elle ?  
- Qui est le plus impacté ?  

**Essayez un exemple de prompt comme celui-ci :**

```text
Break down the problem of [insert challenge]. Identify root causes, pain points, and which areas of work are most affected.
 ```

> **CONSEIL :** Réfléchissez aux situations dans lesquelles la récupération de connaissances vous ferait gagner du temps ou aiderait votre équipe à prendre des décisions plus rapidement.

### Tâche 3 : Explorez les idées de solutions IA avec Recherche

Utilisez l’**Assistant de recherche** pour découvrir comment Copilot et les assistants peuvent vous aider. Concentrez-vous sur les solutions qui permettent de récupérer, d’organiser ou de résumer les connaissances, et non sur l’automatisation des tâches. 

**Étapes :**

- Ouvrez un nouvel onglet dans votre navigateur et accédez à [m365.cloud.microsoft/chat](https://m365.cloud.microsoft/chat).
- Dans le menu Copilot Chat, développez **Agents** (si nécessaire) et sélectionnez **Chercheur**.

    ![Capture d’écran montrant Chercheur sélectionné dans le menu M365 Copilot.](../Prompts/Media/researcher.png)  

    **Exemple de prompt (Assistant de recherche) :**

    ```text
    Explore possible AI solutions to address [insert problem]. Focus on retrieval-based approaches using Microsoft Copilot, Copilot Studio agents, or connected knowledge sources. Summarize three possible solution approaches, their benefits, and limitations.
    ```

    > **CONSEIL :** Recherchez les cas où un assistant pourrait faciliter la recherche, la réutilisation ou le partage des connaissances.

    > **REMARQUE :** La recherche peut prendre entre 5 et 10 minutes (voire plus), selon votre demande. Ses réponses sont très détaillées, donc pendant qu’elle est en cours d’exécution, essayez d’exécuter la même invite dans Copilot Chat. La comparaison des deux sorties est un excellent moyen de voir comment chaque outil aborde la tâche.

### Tâche 4 : Créez votre agent

Maintenant, utilisez vos connaissances pour créer un agent fictif simple dans **Copilot Studio lite**. Concentrez-vous sur la recherche : votre assistant doit vous aider à trouver, organiser ou résumer les informations.

**Étapes :**

- **Démarrer dans Copilot Studio lite**

    1. Ouvrez votre navigateur et accédez à [m365.cloud.microsoft/chat](https://m365.cloud.microsoft/chat).
    1. Sélectionnez **Créer un agent** dans la barre latérale droite pour lancer **Copilot Studio**.

        ![Capture d’écran montrant le lien pour créer un assistant.](../Prompts/Media/create-agent.png)

- **Définissez votre assistant (onglet Décrire ou Configurer)**

    1. Choisissez l’onglet **Décrire** et utilisez cet exemple de prompt (ou rédigez le vôtre) :

        ```text
        You’re a virtual assistant for our [project/team name]. Your role is to help with [key tasks]. Be concise, stay on-brand, and reference our shared resources when possible.
        ```

        ![Capture d’écran montrant l’assistant de description avec un exemple de prompt rempli.](../Prompts/Media/create-agent-through-describe.png)

        > **REMARQUE :** Vous pouvez partir de zéro ou baser votre assistant sur un modèle, qui préremplit les paramètres et les instructions que vous pourrez personnaliser ultérieurement.

    1. Vous avez effectué l’étape précédente si l’onglet **Décrire** était disponible. Si il n'est pas disponible, passez à l'onglet **Configurer** et saisissez manuellement les mêmes informations : nom, description et instructions pour l'agent.

        ![Capture d’écran montrant la configuration de l’assistant.](../Prompts/Media/name-describe-agent.png)

- **Personnaliser votre assistant**

    Dans l’onglet **Configurer**, explorez les options suivantes :

    1. Ajoutez au moins une source de connaissances (par exemple, un document enregistré sur OneDrive/SharePoint ou vos e-mails).

        ![Capture d’écran montrant la section « Sources de connaissances » dans le générateur d’assistants.](../Prompts/Media/knowledge-sources.png)

    1. Définissez des prompts de démarrage pour aider les autres à se familiariser avec votre assistant

        ![Capture d’écran montrant la section des prompts de démarrage dans le générateur d’assistant.](../Prompts/Media/starter-prompts.png)

        > **CONSEIL :** Les prompts de démarrage aident les utilisateurs à interagir avec votre assistant.

- **Tester et créer**

    1. Utilisez la fonction **Tester** (disponible dans le volet de droite tout au long du processus de création de l’assistant) pour essayer votre agent brouillon et corriger d’éventuels problèmes.
    2. Une fois satisfait, sélectionnez **Créer** pour publier l’assistant.
    3. Partagez votre assistant avec d’autres personnes ou ouvrez-le pour l’utiliser immédiatement.  

> **CONSEIL :** L’objectif n’est pas de générer un assistant parfait aujourd’hui, mais d’explorer comment les assistants axés sur la récupération peuvent faciliter l’accès aux connaissances dans votre travail quotidien.
