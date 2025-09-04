---
task:
  title: Expérience immersive – Assistants (utilisateurs professionnels)
---

## Expérience immersive – Assistants (utilisateurs professionnels)

Découvrez comment Microsoft 365 Copilot et Copilot Studio peuvent vous aider à relever les défis quotidiens en matière de productivité en concevant un simple **assistant basé sur la récupération**. Cet exercice simplifié vous guidera dans l’identification d’un problème courant, l’exploration de la façon dont l’IA pourrait aider, puis la création d’un assistant simple à tester.  

Vous effectuerez trois tâches :

- Identifiez un point faible en matière de productivité  
- Découvrez comment l’IA peut faciliter la recherche et l’organisation  
- Générez et testez un assistant simple dans **Copilot Studio**  

> **REMARQUE :** Des exemples de prompts sont fournis pour vous aider à démarrer. N’hésitez pas à les personnaliser pour les adapter à votre situation.  
>
> Si vous avez besoin d’aide pour générer ou améliorer vos prompts, essayez l’<a href="https://appsource.microsoft.com/en-us/product/office/WA200007578" target="_blank">Assistant de requêtes</a>, qui peut suggérer, améliorer et évaluer les prompts afin que vous obteniez de meilleurs résultats avec Copilot.

### Tâche 1 : Identifiez un défi en matière de productivité  

Réfléchissez à un problème courant dans votre travail quotidien, quelque chose qui vous ralentit ou qui rend plus difficile la recherche ou l’organisation des informations. Vous pouvez y réfléchir individuellement ou utiliser **Copilot Chat** comme partenaire pour vous aider à générer des idées et à mettre en évidence les points faibles courants.

Exemples :

- Rechercher la dernière version d’un document  
- Rassembler les mises à jour provenant de plusieurs e-mails ou conversations  
- Se rappeler les détails des réunions ou projets passés  

**Étapes :**  

- Ouvrez un nouvel onglet dans votre navigateur et accédez à [m365.cloud.microsoft/chat](https://m365.cloud.microsoft/chat). 

- Veillez à ce que l’onglet **Mode de travail** soit sélectionné dans **Copilot Chat**.  

   ![Capture d’écran montrant l’onglet Mode de travail dans Copilot Chat.](../Prompts/Media/work-mode.png)  

    **Exemple de prompt :**

    ```text
    Summarize the top challenges I face in my daily work, based on recent emails, chats, and documents. Show results in a simple list with: 
    
    - Title (short label for the issue) 
    - Description (1–2 sentences) 
    ```  

### Tâche 2 : Explorez les idées de solutions IA avec Recherche  

Utilisez l’**Assistant de recherche** pour découvrir comment Copilot ou les assistants peuvent vous aider à relever le défi que vous avez choisi.

**Étapes :**  

- Dans le menu Copilot Chat, développez **Assistants** et sélectionnez **Chercheur**.  

   ![Capture d’écran montrant Chercheur sélectionné dans le menu M365 Copilot.](../Prompts/Media/researcher.png)  

- Essayez un exemple de prompt comme celui-ci :  

   ```text
   Explore possible AI solutions to help with [insert productivity issue]. Focus on retrieval-based approaches using Focus on retrieval-based approaches using Microsoft Copilot or Copilot Studio agents. Summarize two or three ways an agent could help me find, organize, or summarize information more efficiently.
   ```  

    > **CONSEIL :** Concentrez-vous sur des cas d’utilisation pratiques et quotidiens, comme afficher rapidement un document ou extraire des mises à jour de plusieurs sources.  

### Tâche 3 : Générez et testez votre assistant  

Maintenant, créez un assistant de récupération simple dans **Copilot Studio** pour répondre à votre problème.  

**Étapes :**  

1. Dans le menu **Copilot Chat**, sélectionnez **Créer un assistant**.

   ![Capture d’écran montrant le lien pour créer un assistant.](../Prompts/Media/create-agent.png)  

1. Dans l’onglet **Décrire**, rédigez le rôle de votre assistant. Par exemple :  

   ```text
   You’re a virtual assistant that helps me with [key task]. Be concise and always reference my recent files or resources when possible.
   ```  

   ![Capture d’écran montrant l’assistant de description avec un exemple de prompt rempli.](../Prompts/Media/create-agent-through-describe.png)  

1. Sélectionnez l’onglet **Configurer** et ajoutez une source de connaissances (par exemple, **Mes e-mails** ou **Mes conversations et réunions Teams**).

    ![Capture d’écran montrant la section « Sources de connaissances » dans le générateur d’assistants.](../Prompts/Media/knowledge-sources.png)

1. Testez votre assistant à l’aide du volet **Test** et améliorez-le si nécessaire.  
1. Sélectionnez **Créer** pour publier votre assistant et commencer à l’utiliser.  

> **CONSEIL :** Même un assistant très simple, tel que celui qui vous aide à trouver des fichiers de projet récents, peut démontrer la puissance de la récupération dans votre travail quotidien.
