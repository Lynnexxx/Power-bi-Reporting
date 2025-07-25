# REAL-ESTATE-DENMARK

Les données sont issues de **Google BigQuery** (Google Cloud Platform), à partir d’un entrepôt structuré contenant des informations détaillées sur le marché immobilier danois.  
Elles incluent des données géographiques, transactionnelles et macroéconomiques.

## Objectif du projet

Ce projet vise à analyser le **marché immobilier danois** via un tableau de bord Power BI interactif.  
L'objectif est d'obtenir une vision claire de la **valeur des biens**, des **dynamismes de vente**, des **types de transactions**, ainsi que des **tendances régionales et économiques**.

**Fil conducteur :** Typologie → Performance → Tendances Marché

---

## Page 1 : Analyse par type de bien  
![Dashboard Page 1](https://github.com/Lynnexxx/Power-bi-Reporting/blob/47838b425439bfd4770d0474174b4b7cadb9ae81/Housing%20Data%20Analysis/Images/Page%201.png)

Cette première page offre une vue comparative des différents types de logements danois : prix, surface, rendement, inflation et taux d'intérêt.

- **Farms** : les biens les plus chers (~2,7M DKK), vastes (196 m²), avec le **meilleur rendement brut (4,6%)**
- **Summerhouses** : les moins chers (~1,2M DKK), mais les **plus chers au m²** (15,2K DKK/m² pour 83 m²)
- **Appartements** : les **plus chers au m²** (19,4K DKK/m²), pour une faible surface moyenne (86 m²)
- Le **prix d’achat est très proche du prix d’offre**, signe d’un marché équilibré
- Contexte macroéconomique stable : **taux d’intérêt ~2%**, **inflation ~1,9%**

### Résumé :
Les types de biens influencent fortement la valeur et le rendement. Les "Farms" se démarquent comme actifs rentables à fort potentiel. Les appartements et summerhouses sont plus coûteux en proportion. Le marché est stable avec peu d’écart entre les offres et les achats.

---

## Page 2 : Performance des ventes  
![Dashboard Page 2](https://github.com/Lynnexxx/Power-bi-Reporting/blob/47838b425439bfd4770d0474174b4b7cadb9ae81/Housing%20Data%20Analysis/Images/Page%202.png)

Cette page explore la **valeur totale des ventes**, les **prix au m²** par région et par **type de transaction**.

- **Zealand** domine en volume (95 Mds DKK), suivi de **Jutland** (81 Mds DKK)
- Prix au m² :
  - Zealand : 20,85K DKK/m²
  - Bornholm : 10,6K DKK/m²
- Par type de vente :
  - **Standard** : 15K DKK/m²
  - **Vente forcée** et **enchères** : plus avantageuses (≈11K DKK/m²)

### Résumé :
Les régions urbanisées concentrent les ventes et affichent des prix plus élevés au m². Les ventes aux enchères ou forcées représentent une alternative économique. Les écarts entre les types de transaction doivent être intégrés aux stratégies d’achat.

---

## Page 3 : Vue d’ensemble du marché  
![Dashboard Page 3](https://github.com/Lynnexxx/Power-bi-Reporting/blob/47838b425439bfd4770d0474174b4b7cadb9ae81/Housing%20Data%20Analysis/Images/Page%203.png)

Cette page fournit une lecture macro du marché immobilier danois, incluant tendances temporelles, types de ventes et évolutions régionales.

- **77 unités vendues récemment**, pour un total de **13 Mds DKK**
- **Corrélation forte** entre prix d’offre et prix final → marché prévisible
- Régionalement :
  - **Jutland** en forte croissance (hausse du prix médian)
  - **Bornholm** en recul
- Par type de transaction :
  - **Ventes aux enchères en hausse** (+0,29)
  - **Ventes familiales en forte baisse** (-0,75)

### Résumé :
Le marché reste actif et relativement prévisible. Certaines zones comme Jutland sont en expansion, tandis que d'autres montrent un recul. Les ventes aux enchères gagnent du terrain, contrastant avec la baisse des ventes intrafamiliales.

---

## Conclusion

Le tableau de bord met en lumière les **disparités de valeur entre les types de biens**, les **dynamismes régionaux** et les **types de transactions les plus avantageux**.  
Les indicateurs macroéconomiques restent stables, renforçant la lisibilité du marché.

---

## Recommandations & Opportunités d’action

1. **Cibler les Farms et Villas**  
   → Actifs offrant le meilleur rapport valeur / rendement

2. **Exploiter les ventes aux enchères**  
   → Segment en croissance et plus économique

3. **Investir dans les zones en croissance**  
   → Prioriser les régions comme Jutland

4. **Suivre les baisses de performance**  
   → Notamment Bornholm et les ventes familiales

5. **Intégrer les données macroéconomiques**  
   → Pour ajuster les analyses en fonction de la conjoncture

---

*Projet réalisé dans le cadre d’une analyse immobilière avancée sous Power BI à partir de données BigQuery (GCP).*
