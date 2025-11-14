---
demo:
  title: Version de démonstration Chercheur et Analyste
---

[Revenir à l’index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# Version de démonstration Chercheur et Analyste

Cette version de démonstration montre comment utiliser**Chercheur** et**Analyste**, deux assistants experts intégrés à l’application Copilot.  

- **Chercheur** vous aide à réaliser des tâches de recherche en plusieurs étapes, en combinant les données web avec les fichiers et connaissances de votre entreprise.  
- **Analyste** pense comme un scientifique des données expérimenté, capable d’effectuer des analyses de données avancées et d’exécuter des scripts Python, même si vous ne savez pas coder.  

## Configuration de la démonstration

Pour réaliser ces démonstrations, vous devrez télécharger le[Pack de contenu de démonstration Recherche et Analyste](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/refs/heads/master/ResourceFiles/Researcher_and_Analyst_Demo_Content_Pack.zip), qui contient tous les fichiers et ressources nécessaires.  

> **CONSEIL :** Avant de présenter la démonstration, vous pouvez créer un site SharePoint dans votre environnement de démonstration pour y stocker tous les fichiers et y accéder facilement. Vous pouvez également stocker les fichiers localement et les référencer directement dans vos prompts à l’aide de**/**.  

Pour accéder à ces assistants :  

- Ouvrez l’**application Copilot** à partir de[m365.cloud.microsoft](https://m365.cloud.microsoft).  
- Sélectionnez**Chercheur** ou**Analyste** dans le volet de navigation.  

> **Remarque :** Vous devrez orienter Recherche et Analyste vers des fichiers internes (SharePoint/OneDrive) pour obtenir des informations détaillées.

---

## Points de discussion

- **Recherche** agit comme un conseiller hautement rémunéré : il peut générer des livrables structurés et bien référencés en combinant des fichiers internes, des informations sur la concurrence et des sources web.  
- **Analyste** équivaut à avoir un scientifique des données à disposition : il crée des modèles, exécute du code Python et visualise instantanément les tendances.  
- Les deux assistants expliquent leur raisonnement de manière transparente afin que vous puissiez valider les résultats.  
- Ensemble, ils accélèrent le travail stratégique (plans marketing, segmentation de la clientèle, projections financières) afin que vous puissiez avancer plus rapidement en toute confiance.  

---

## Étapes de la version de démonstration

### Recherche : Générer un plan marketing

> **IMPORTANT :** Les étapes 1 à 4 doivent être réalisées au début de la formation (comme indiqué dans la diapositive 5) afin de laisser suffisamment de temps à Recherche pour traiter le premier prompt.

1. Ouvrez**Chercheur** à partir du volet de navigation.  

    ![Capture d’écran montrant Chercheur sélectionné dans le menu M365 Copilot.](../Prompts/Media/researcher.png)  

1. Entrez l’invite suivante :

    ```text
    Create a marketing plan for our newest SprintCycle EV charger launch. 
    Emphasize its AI-powered adaptive charging, modular design, and biometric access control. 
    Make sure to include recommendations on the right digital channels and content strategy. 
    Include insights from competitors and our past GTM campaigns.
    ```

1. Joignez les fichiers de référence à l’aide de`/` (pointez vers SharePoint/OneDrive) :  

   - **/SprintCycle Charger Product Launch.docx**  
   - *(Facultatif)***/Contoso - PedalPerks GTM Plan.docx**  

1. Sélectionnez**Soumettre**.  

Chercheur va :  

- Combiner les informations provenant à la fois des fichiers internes et du web.  
- Structurer un plan marketing avec des recommandations sur les canaux et la stratégie de contenu.  
- Citer les sources afin que vous puissiez vérifier son travail.  

> **Remarque :** Chercheur montre son raisonnement (« chaîne de réflexion ») et peut faire appel à d’autres assistants si nécessaire.  

### Analyste : Segmentation client et modélisation financière

**Remarque :** Cette démonstration ne concerne pas la version Executive du contenu. Passez plutôt à la démonstration**Copilot Studio**.

1. Ouvrez**Analyste** à partir du volet de navigation.

    ![Capture d’écran montrant Analyste sélectionné dans le menu M365 Copilot.](../Prompts/Media/analyst.png)  

1. Entrez l’invite suivante :

    ```text
    Find the right customer segment and demographic to sell our new EV charger, 
    include a graph to show how this will maximize our market opportunity.
    ```

1. Joignez le fichier à l’aide de**+**  :  

   - **BoulderEV ebike Internal Market Forecast.xlsx**  

    ![Capture d’écran montrant les fichiers joints dans Analyste.](../Prompts/Media/Analyst-Attach-Files.png)  

1. Cliquez sur**Envoyer**.  

Analyste va :  

- Analyser le jeu de données.  
- Identifier les segments de clients à forte valeur.  
- Fournir des visualisations pour étayer les recommandations.  

### Scénarios supplémentaires pour Analyste

Vous pouvez exécuter ces prompts supplémentaires pour varier les analyses. Chacune suit le même modèle :**Prompt → Joindre un fichier → Soumettre → Examiner les résultats.**

- **Projection financière**  

    ```text
    Build a 5-year financial projection from this data along with a graph to view revenue growth over time.
    ```  

    Fichier :**BoulderEV ebike Internal Market Forecast.xlsx**  

- **Performance de ventes**  

    ```text
    Analyze sales volume across locations to identify our highest and lowest performing stores, 
    along with a visualization of the best-selling products.
    ```  

    Fichier :**BoulderEV ebike Internal Market Forecast.xlsx**  

- **Performance de la campagne**  

    ```text
    Analyze and visualize how the marketing campaign performed across each target segment 
    and help me decide where to re-target our next campaign.
    ```  

    Fichier :**BoulderEV ebike Internal Market Forecast.xlsx**  

## À retenir

- **Chercheur** : accélère la stratégie et la planification avec des recherches de haute qualité.  
- **Analyste** : fournit des informations basées sur les données grâce à des analyses et des visualisations avancées.  

Ensemble, Chercheur et Analyste raccourcissent le chemin de la**question à l’information**, transformant ainsi des semaines de travail en quelques minutes.  

[Revenir à l’index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
