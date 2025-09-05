---
demo:
  title: Démonstration pour le service financier
---

[Revenir à l’index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# Démonstration pour le service financier

**Scénario :**  

Vous êtes analyste financier chez Contoso, responsable de l’évaluation des performances des ventes et du positionnement sur le marché dans le secteur de la recharge des véhicules électriques. Votre objectif est d’analyser les données des ventes, de générer des informations et de préparer un résumé pour votre équipe.

## Configuration de la démonstration

Vous trouverez les exemples de documents dans le référentiel GitHub MS-4021 [ici](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles) :

Les fichiers spécifiques nécessaires pour cette démonstration sont les suivants :

- [EV_Charger_Sales_Analysis_v1.xlsx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/EV_Charger_Sales_Analysis_v1.xlsx)

### Copilot pour Excel  

Utilisez Copilot pour Excel afin d’analyser les données de vente, d’identifier les tendances clés et de calculer les mesures financières.

1. Lancer Excel et ouvrir le fichier  

1. Ouvrez **EV_Charger_Sales_Analysis_v1.xlsx** dans Excel (dans votre navigateur ou votre application de bureau).  

1. Accédez à l’onglet **« Ventes par produit »**.  

1. Utilisez Copilot pour trier le tableau en entrant l’invite suivante :  

    ```text
    Sort the table by date in descending order, from the most recent to the oldest entry.
    ```  

    - Copilot trie le tableau et met à jour le jeu de données.  
    - Sélectionnez **« Appliquer »** après le tri.  

1. Insérer une colonne « Chiffre d’affaires total »  

    Dans le volet Copilot, utilisez l’invite suivante :  

    ```text
    Add a new column named 'Total Revenue'. Populate it by multiplying 'Units Sold' by 'Product Price' for each row.
    ```  

    - Copilot crée la nouvelle colonne et applique la formule.  
    - Sélectionnez **« Insérer une colonne »**.  

1. Générer un tableau récapitulatif des ventes pour 2024  

    Dans le volet Copilot, entrez l’invite suivante :  

    ```text
    Create a summary table for total sales in 2024. The table should include Product ID, total units sold, and total revenue.
    ```  

    - Copilot génère un tableau récapitulatif.  
    - Sélectionnez **« Ajouter à une nouvelle feuille de données »** pour enregistrer le tableau séparément.  
    - Vérifiez que le tableau inclut **uniquement les données de 2024**.  
    - Revenez à l’onglet **« Ventes par produit »** ou sélectionnez **« Revenir aux données »** sous la dernière réponse de Copilot.  

1. Identifier le produit le mieux vendu  

    Dans le volet Copilot, entrez l’invite suivante :  

    ```text
    Identify the product ID with the highest total revenue in 2024. Provide both total revenue and total units sold for better comparison.
    ```  

    - Copilot analyse le jeu de données et indique le produit le plus vendu.
    - Revenez à l’onglet **« Ventes par produit »** ou sélectionnez **« Revenir aux données »** sous la dernière réponse de Copilot.  

1. Trier les clients par chiffre d’affaires

    - Accédez à la feuille **« Clients »** dans Excel.

    Dans le volet Copilot, entrez l’invite suivante :  

    ```text
    Sort the 'Customers' tab by annual revenue in descending order.
    ```  

    - Copilot trie les clients par **chiffre d’affaires annuel**.  
    - Sélectionnez **« Appliquer »** après le tri.  

1. Calculer le chiffre d’affaires moyen par client

    Entrez l’invite suivante :  

    ```text
    Calculate the average revenue per customer.
    ```  

    - Copilot calcule la moyenne et ajoute le résultat.  
    - Sélectionnez **« Insérer une ligne »** pour enregistrer la valeur moyenne du chiffre d’affaires.  

1. Rechercher le secteur consommant le plus d’énergie  

    Dans le volet Copilot, entrez l’invite suivante :  

    ```text
    Analyze the data to determine which industry has the highest total power consumption. Provide the industry name and total power usage.
    ```  

    - Copilot traite les données et retourne le secteur qui consomme le plus d’énergie.

1. Enregistrez le document. Copiez l’URL partagée à partir du document (activez l’enregistrement automatique et sélectionnez votre compte OneDrive si vous y êtes invité).

    ![Partagez un lien.](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Copilot Chat

Utilisez Copilot Chat pour comparer les performances financières avec les benchmarks et les concurrents du secteur.

1. Ouvrez un navigateur et accédez à [M365copilot.com](https://m365copilot.com/).

1. Vérifiez que Mode web est sélectionné.

    ![Capture d’écran montrant l’onglet Mode web.](../Prompts/Media/web-mode.png)

1. Dans la fenêtre de l’invite, tapez le texte suivant :

    ```text
    Our total revenue for [EV chargers] exceeded $50,000,000 for firth half of 2024. Compare this to the industry average and provide insights on whether we are above or below industry standards. If possible, include market share estimates and trends
    ```

1. Demandez maintenant à Copilot Chat de comparer ces résultats avec ceux des concurrents :

    ```text
    Summarize the key financial statements of two major competitors in the [EV charging] industry. Include revenue, net profit, and any other relevant financial insights. If available, provide comparisons to our financial performance.
    ```

1. Enfin, demandez au copilote d’exporter l’historique des conversations à ce jour dans un document Word :

    ```text
    Export this conversation, including financial insights, to a Word document for further review.
    ```

1. Sélectionnez le fichier lié à télécharger, puis ouvrez le document.

1. Cliquez sur **Activer la modification**.

1. Le titre du fichier doit ressemble à « **Charging_industry_Financial_Summary.docx** ». Copiez l’URL partagée à partir du document (activez l’enregistrement automatique et sélectionnez votre compte OneDrive si vous y êtes invité).

    ![Partagez un lien.](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Copilot dans Word

Utilisez Copilot pour Word afin de résumer les informations financières dans un e-mail pour notre équipe.

1. Ouvrez un nouveau document Word (dans votre navigateur ou votre application de bureau).

1. Dans la zone d’invite **« Décrivez ce que vous souhaitez écrire »,** tapez ce qui suit :

    ```text
    Draft an email to my team summarizing the key insights from [Charging_industry_Financial_Summary.docx].
    ```

    > **REMARQUE :** joignez le fichier Charging_industry_Financial_Summary.docx créé dans la tâche précédente ou collez le lien partagé directement dans l’invite pour vous assurer que Copilot a accès au contenu approprié.

1. Passez en revue la sortie de Copilot. Avant de sélectionner **Conserver**, affinez la réponse en demandant à Copilot :

    ```text
    Shorten this email draft
    ```

1. Autres affinements facultatifs :

    - Demandez à Copilot de reformuler des sections pour leur donner un ton plus professionnel.
    - Complétez par des sections supplémentaires.
    - Utiliser un ton moins formel

1. Une fois terminé, vous pouvez sélectionner **Conserver**.

[Revenir à l’index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
