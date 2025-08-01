
# Technical Support Performance Dashboard 
Les données sont issues d’un cas réel de centre de support technique

## Objectif du projet

Ce projet vise à analyser le **fonctionnement global et la performance opérationnelle** d’un centre de support technique à travers un tableau de bord interactif Power BI.  
L’analyse repose sur un ensemble de tickets traités via différents canaux (chat, téléphone, e-mail) avec des données complètes sur les délais de traitement, le respect des SLA (Service-Level Agreement), les interactions agents, les résolutions, et les retours clients.

Ce tableau de bord permet de répondre aux questions clés suivantes :
- Quels sont les **pics de création de tickets** ?
- Quels sont les **temps de réponse et de résolution**, et respectent-ils les SLA ?
- Quels sont les **canaux les plus sollicités** ?
- Comment évolue la **satisfaction client** selon les agents, produits ou priorités ?

---

## Fil conducteur de l’analyse  
**Charge et flux de tickets → SLA et délais → Comportement agents → Satisfaction client**

---

## Page 1 : Volume et dynamique des tickets  
![Dashboard Page 1](https://github.com/Lynnexxx/Power-bi-Reporting/blob/bff0b67e06c46a51f267f1e24c9d32bd4c87275c/Technical%20Support%20Analysis/Images/Page%201-Tech%20Support.png)

Cette page permet d’observer comment évolue la charge du centre de support.

### Indicateurs clés :
- Volume total de tickets créés
- Répartition par jour de la semaine et tranche horaire
- Comparaison jour ouvré vs week-end
- Volume par canal (email, chat, téléphone)

### Insights visuels :
- Les **pics de création** sont observés en début de semaine, notamment le lundi matin.
- Le **canal e-mail** domine en volume, mais le **chat** montre une meilleure réactivité.
- Le week-end, les tickets sont rares mais tendent à rester ouverts plus longtemps.

### Résumé :
Cette page met en évidence les **plages horaires critiques**, le **canal dominant**, et les périodes nécessitant un **renfort opérationnel** (notamment les lundis matin et après les heures ouvrées).

---

## Page 2 : Délai de traitement et respect des SLA  
**Dashboard Page 2 – SLA Performance**
![Dashboard Page 2](https://github.com/Lynnexxx/Power-bi-Reporting/blob/bff0b67e06c46a51f267f1e24c9d32bd4c87275c/Technical%20Support%20Analysis/Images/Page%202-Tech%20Support-Priority.png)

--------------------------------------------------------------------

![Dashboard Page 2-Support Day type](https://github.com/Lynnexxx/Power-bi-Reporting/blob/bff0b67e06c46a51f267f1e24c9d32bd4c87275c/Technical%20Support%20Analysis/Images/Page%202-Tech%20Support-dailytype.png)

--------------------------------------------------------------------

![Dashboard Page 2-Support Priority](https://github.com/Lynnexxx/Power-bi-Reporting/blob/bff0b67e06c46a51f267f1e24c9d32bd4c87275c/Technical%20Support%20Analysis/Images/Page%202-Tech%20Support-Priority.png)

Cette section se concentre sur l’**efficacité opérationnelle** et le respect des engagements de service.

### Suivi des SLA :
- Délai moyen de **première réponse** et de **résolution**
- Taux de conformité SLA pour la première réponse et la résolution
- Évolution temporelle de ces indicateurs

### Observations :
- 78 % des tickets reçoivent une première réponse **dans les délais SLA**.
- Le **respect des SLA pour la résolution** est légèrement plus faible (~65 %).
- Les tickets à **haute priorité** ou en **support de niveau 2** prennent plus de temps à être résolus.
- Les délais sont plus longs pour les tickets créés **après 18h** ou pendant le **week-end**.

### Résumé :
Le respect des SLA est globalement bon, mais des **marges de progression existent pour les résolutions**, surtout en dehors des heures normales. Les tickets critiques doivent être **priorisés plus rigoureusement**.

---

## Page 3 : Satisfaction client et efficacité par agent  
**Dashboard Page 3 – Customer Feedback & Agent Performance**

Cette page met en lumière la **satisfaction client** et l’efficacité individuelle et collective des agents.

### KPIs analysés :
- **Score de satisfaction** (1 à 5) par agent, groupe, pays ou produit
- Nombre d’interactions nécessaires avant résolution
- Comparaison des performances entre **support de niveau 1** et **niveau 2**

### Insights :
- Les **scores de satisfaction les plus élevés** sont associés à des **agents ayant un faible nombre d’interactions** et un bon respect des SLA.
- Certains **agents ou groupes** se démarquent par des scores >4,5, tandis que d’autres nécessitent un accompagnement.
- Les **tickets sur certains produits** ou sujets récurrents (ex. bugs techniques) affichent des scores moyens plus faibles.

### Résumé :
La satisfaction client dépend fortement de la **rapidité de traitement**, de la **clarté des échanges** et de **l’agent en charge**. Le suivi par agent permet d’identifier les **points forts à valoriser** et les **axes d’amélioration ciblés**.

---

## Conclusion

L’analyse du support technique révèle une structure globalement performante, mais avec des **points de tension clairement identifiés** :

### Points d’alerte :
- Résolutions parfois lentes en dehors des heures ouvrées
- Taux de non-respect des SLA en résolution à surveiller
- Écart de satisfaction entre les agents ou produits

### Recommandations :
- **Optimiser les ressources** les lundis matin et après 18h
- **Mettre en place des alertes SLA** pour les tickets critiques
- **Analyser les tickets à faible satisfaction** pour détecter les points de friction
- **Encourager les bonnes pratiques des agents les plus performants**
- **Former les nouveaux agents** à la gestion des sujets sensibles

---

Projet réalisé dans le cadre d’une analyse opérationnelle de centre de support technique, à l’aide de Power BI et de visuels interactifs ZoomCharts.  
