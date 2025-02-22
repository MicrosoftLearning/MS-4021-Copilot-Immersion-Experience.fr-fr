---
title: Instructions hébergées en ligne
permalink: index.html
layout: home
---

Les liens hypertexte vers chaque version de démonstration sont répertoriés ci-dessous.

## Démonstrations

{% assign demos = site.pages | where_exp:"page", "page.url contains ’/Instructions/Demos’" %}
| Démo |
| --- |
{% for activity in demos  %}| [{{ activity.demo.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}

## Exemples d’invites pour une expérience d’immersion

#### [Cadres](https://learn.microsoft.com/en-us/training/modules/envision-new-ideas-with-microsoft-365-copilot/) (redirections vers Microsoft Learn)

#### [Communications](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Communications-Prompts.html)

#### [RH](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/HR-Prompts.html)

#### [Vente](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Sales-Prompts.html)

#### [INFORMATIQUE](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/IT-Prompts.html)

#### [Assistant de direction](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/EA-Prompts.html)

#### [Directeur commercial](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Business-Manager-Prompts.html)

#### [Marketing](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Marketing-Prompts.html)

#### [Opérations](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Operations-Prompts.html)

#### [Juridique](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Legal-Prompts.html)

#### [Finances](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/Instructions/Prompts/Finance-Prompts.html)