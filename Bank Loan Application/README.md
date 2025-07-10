
#  LOAN-APPLICATIONS

Les données sont issues d’un fichier CSV, disponible à l’adresse suivante :  
[🔗 Télécharger les données](https://drive.google.com/uc?export=download&id=1HDRIQEBe30WZdo9gvmz4PH-zcH8CIwsr)

##  Objectif du projet

Ce projet vise à analyser un portefeuille de prêts sur l'année 2021 à travers un tableau de bord Power BI interactif.  
L'objectif est de fournir une vision claire de la **performance globale**, du **profil des emprunteurs**, des **risques associés**, ainsi que des **leviers d’optimisation**.

 **Fil conducteur :** Performance → Profil → Risque → Opportunités

---

## Page 1 : Vue d’ensemble du portefeuille
![Dashboard Page 1](https://github.com/Lynnexxx/Power-bi-Reporting/tree/2c10e3ca7700ad42d0aabe5ea627ab1ecee5f0c4/Bank%20Loan%20Application/images/Page%201.png)

Cette page fournit une lecture synthétique de la **santé globale du portefeuille** à l’aide de KPI clés :

- **14 000 prêts octroyés**, pour un **montant total financé** de **169,02 M€**
- **Montant remboursé** : **183,46 M€**, indiquant une forte capacité de remboursement
- **Encours non perçu** : **14 M€**, nécessitant une vigilance renforcée
- **Taux d’intérêt moyen** : **12,3%**, indiquant une rentabilité brute attractive

###  Insights visuels :
- 66% des prêts sur 36 mois, contre 34% sur 60 mois
- 84% des prêts considérés comme "bons", 16% "mauvais"
- Les scores B, A et C dominent (notamment 4,2K prêts en B)
- Progression mensuelle continue du nombre de prêts, avec un pic en décembre

###  Résumé :
Un portefeuille dynamique, rentable et maîtrisé, qui pose les bases pour analyser plus en profondeur les emprunteurs et les remboursements.

---

##  Page 2 : Profil des emprunteurs
![Dashboard Page 2](https://github.com/Lynnexxx/Power-bi-Reporting/tree/2c10e3ca7700ad42d0aabe5ea627ab1ecee5f0c4/Bank%20Loan%20Application/images/Page%202.png)

Cette page répond à la question **"Qui emprunte ?"** en analysant la solvabilité, les comportements et les opportunités.

- **Ratio d’endettement moyen (DTI)** : 0,13 → Excellent (inférieur au seuil de 0,35)
- Répartition équilibrée des emprunteurs : 46% propriétaires / 47% locataires avec prêt
- Les emprunteurs expérimentés obtiennent en moyenne des montants plus élevés
- Les faibles scores de crédit (E, F, G) ont des mensualités et un DTI plus élevés

###  Comportement par score :
- Meilleurs scores (A, B) : revenus modérés mais faible endettement → profils prudents
- Scores faibles : revenus plus élevés mais comportements financiers plus risqués

### 🏢 Opportunités commerciales :
- Principaux employeurs : U.S. Army, Bank of America, AT&T, Walmart
- Carte géographique : répartition des demandes et scores par État américain

### Résumé :
Les emprunteurs sont stables, solvables et les meilleurs profils présentent des comportements responsables. Ces données permettent de cibler les bonnes entreprises et régions.

---

## Page 3 : Performance et risques
![Dashboard Page 3](https://github.com/Lynnexxx/Power-bi-Reporting/tree/2c10e3ca7700ad42d0aabe5ea627ab1ecee5f0c4/Bank%20Loan%20Application/images/Page%203.png)

Cette dernière page évalue la performance réelle du portefeuille via remboursements, défauts et tendances :

- **Taux de remboursement** : 80,55%  
- **Taux de défaut (Charged Off)** : 15,88%  
- **Montant moyen remboursé** : 13,46 K€

### Observations clés :
- La majorité des prêts sont **"Fully Paid"**, suivis de "Charged Off"
- Les montants prêtés augmentent avec le risque (scores de A vers G)
- Les **scores faibles sont surreprésentés dans les défauts**
- Évolution du taux de remboursement : baisse de 0,851 à 0,772 entre février et décembre
- Les prêts "Debt Consolidation" ou "Home Improvement" sont les plus rentables

### Résumé :
Le scoring reste l’outil central de gestion du risque. Une attention particulière est à porter sur la **dégradation récente du remboursement** et les **motifs de prêts peu rentables**.

---

## Conclusion

Le portefeuille est globalement **solide** et **rentable**, avec des emprunteurs **stables** et un endettement **modéré**.  
Mais certaines alertes émergent :  
- 15,88% de défauts  
- 14 M€ encore non remboursés  
Ces risques concernent principalement les **scores faibles** et certains **motifs de prêts fragiles**.

---

## Recommandations & Opportunités d’action

1. **Optimiser le scoring**  
   → Renforcer les critères sur les scores E, F, G (garanties, plafonds)

2. **Repenser par motif**  
   → Prioriser les prêts avec fort remboursement (ex. Debt Consolidation)

3. **Suivre le cash non perçu**  
   → Mettre en place des relances ciblées sur les 14 M€ restants

4. **Cibler les gros employeurs**  
   → Nouer des partenariats avec les entreprises dominantes (U.S. Army, etc.)

5. **Automatiser les alertes de remboursement**  
   → Déclencher une alerte dès que le taux chute sous un certain seuil mensuel

---

 *Projet réalisé dans le cadre d'une analyse exploratoire avancée sous Power BI.*  
