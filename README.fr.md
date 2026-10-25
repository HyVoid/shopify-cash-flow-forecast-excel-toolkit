[ 🌐 عربي ](README.ar.md) | [ 🇩🇪 Deutsch ](README.de.md) | [ 🇫🇷 Français ](README.fr.md) | [ 🇳🇱 Nederlands ](README.nl.md) | [ 🇪🇸 Español ](README.sp.md) | [ 🇬🇧 English ](README.md)

# Toolkit de Contrôle Financier DTC & Prévision des Flux de Trésorerie sur 12 Semaines | Modèle Excel Shopify & de Rapprochement des Versements
<img width="1920" height="790" alt="image" src="https://github.com/user-attachments/assets/2b140bc1-af18-4481-82c0-d626669f8fe2" />


![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)
![Platform](https://img.shields.io/badge/Platform-Browser%20Sandbox%20%2B%20Excel%20(.xlsx)-success.svg)
![Tool](https://img.shields.io/badge/Category-Ecommerce%20Financial%20Modeling%20%26%20FP%26A-orange.svg)

Une solution tout-en-un de **modélisation financière e-commerce** et de **modèle Excel de prévision des flux de trésorerie glissante sur 12 semaines**, conçue pour les **boutiques Shopify** et les **marques direct-to-consumer (DTC)**. Ce toolkit transforme les **versements Shopify** bruts, les **rapprochements du compte d'attente bancaire**, les **bons de commande d'inventaire (POs)**, les factures de **comptes fournisseurs (AP)** et les **dépenses publicitaires payantes (Meta/Google Ads)** en un **cadre unifié de planification du fonds de roulement et de la liquidité**. Conçu comme une **alternative de soutien à la décision FP&A** légère et sans code, en remplacement des **systèmes ERP** d'entreprise à six chiffres et des rapports comptables statiques **QuickBooks/Xero**.

**Aucune inscription. Aucune installation. Test interactif gratuit dans votre navigateur.**

Testez instantanément les données opérationnelles de votre boutique dans le bac à sable gratuit du navigateur. Pour une gestion de trésorerie mensuelle récurrente, une configuration de paramètres personnalisée et une confidentialité totale des données financières hors ligne, téléchargez le classeur Microsoft Excel entièrement déverrouillé, soutenu par une garantie de remboursement de 30 jours sans questions.

> 🌐 **Lancer le bac à sable web interactif (aucune configuration)**  
> [Testez les métriques de votre boutique dans le simulateur DTC de flux de trésorerie et de liquidité gratuit basé sur navigateur](https://hyvoid.github.io/shopify-cash-flow-forecast-excel-toolkit/)
>
> 📥 **Obtenir le modèle d'exploitation hors ligne complet (.xlsx)**  
> [Téléchargez le modèle Excel réutilisable de Contrôle Financier Shopify & de Flux de Trésorerie sur 12 Semaines](https://www.theseusworkshop.com/l/iybjto?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=dtc-financial-control-cashflow)

---

## Ce que cela vous aide à suivre : points de douleur financiers de l'e-commerce vs. solutions automatisées

Les logiciels comptables standard suivent la rentabilité historique en comptabilité d'engagement, laissant les marques en croissance aveugles aux prochaines crises de trésorerie. Ce cadre de contrôle financier cartographie les fuites opérationnelles spécifiques directement sur des métriques de trésorerie prospectives :

| Point de douleur financier e-commerce (intention de recherche) | Risque de fonds de roulement sous-jacent | Module toolkit automatisé & KPI suivis |
| :--- | :--- | :--- |
| **Gestion aveugle du solde bancaire :** deviner la **piste de trésorerie** réelle sur la seule base du solde statique du compte courant du jour. | Surengager la trésorerie dans l'inventaire ou le marketing juste avant que les salaires et les dettes fournisseurs ne se chevauchent. | **Prévision de flux de trésorerie glissante sur 12 semaines :** calcule la **liquidité opérationnelle nette** et les **ruptures de réserve de sécurité** en échelonnant les dettes à payer futures contre les entrées attendues. |
| **Versements Shopify non rapprochés :** les ventes brutes dans Shopify ne correspondent pas aux dépôts bancaires nets en raison des retenues de passerelle, des remboursements et des frais. | Fuite de revenus cachée, rétrofacturations non enregistrées et erreurs comptables du **compte d'attente** en fin de mois. | **Moteur de rapprochement à trois voies :** suit la **variance commande-à-versement**, les **fonds de passerelle en transit** et les **exceptions de règlement non appariées**. |
| **Factures fournisseurs en double & erreurs AP :** payer accidentellement deux fois le même transitaire ou fabricant sur plusieurs cycles de facturation. | Perte directe de fonds de roulement et échéanciers de **vieillissement des comptes fournisseurs (AP)** déformés. | **Module d'audit AP & de vérification des paiements :** signale les **ID de factures en double**, les **risques de trop-payé** et les **virements en attente d'approbation** avant que la trésorerie ne quitte la banque. |
| **Rupture de stock vs. crise de trésorerie :** payer 30 % d'acomptes initiaux et 70 % de soldes sur les **bons de commande (POs)** des semaines avant que l'inventaire ne se convertisse en trésorerie. | Insolvabilité induite par l'inventaire pendant les pics de production Q3/Q4. | **Simulateur d'impact des PO d'inventaire :** soumet à un test de résistance les **conditions de paiement du coût complet (Net-30/60)** contre votre **seuil minimal de réserve de trésorerie**. |
| **Dépenses publicitaires cloisonnées & reporting ROAS :** les acheteurs média escaladent les budgets publicitaires quotidiens Facebook/Google déconnectés du timing réel de règlement bancaire. | **Ratio d'efficacité marketing (MER)** élevé sur le papier masquant une grave combustion à court terme des cartes de crédit et de la trésorerie. | **Traqueur de liquidité des dépenses publicitaires intégré :** aligne les **sorties hebdomadaires de coût d'acquisition client (CAC)** sur les **entrées retardées des processeurs de paiement**. |

---

## Tutoriel de démarrage rapide : comment automatiser votre analyse de flux de trésorerie et de versements Shopify

Transformez les exports CSV fragmentés de votre pile technologique e-commerce en un **tableau de bord financier FP&A** prêt pour la direction en quatre étapes structurées.

### Étape 1 : configurer les paramètres de base du fonds de roulement (configuration unique)
Ouvrez la feuille **Parameters** pour établir les garde-fous de trésorerie de votre entreprise. Définissez votre **réserve de trésorerie de sécurité minimale**, votre **devise de reporting**, vos **taux de change (FX)**, les conditions de paiement fournisseurs par défaut et l'**horizon de prévision glissant de 12 semaines**. Ces variables globales régissent toutes les alertes de liquidité en aval.

### Étape 2 : importer les données CSV brutes e-commerce, bancaires et comptables
Éliminez la saisie manuelle des données et le copier-coller fragile. Exportez les journaux de transactions CSV standard depuis vos plateformes existantes et déposez-les dans les tableaux d'entrée Excel structurés :
*   **Exports de commandes Shopify et de versements marchands** (ventes brutes, remboursements, frais de passerelle, règlements nets)
*   **Relevés de compte courant commercial et de cartes de crédit** (exports CSV de Mercury, Chase, Relay ou Amex)
*   **Grand livre & factures AP** (exports de **QuickBooks Online**, **Xero** ou Bill.com)
*   **Bons de commande fournisseurs (POs)** (calendriers de production SKU, acomptes initiaux, dates d'échéance des soldes)
*   **Dépenses de marketing de performance** (dépenses publicitaires quotidiennes/hebdomadaires de **Meta Ads Manager**, **Google Ads** et **TikTok Ads**)

### Étape 3 : exécuter le rapprochement automatisé, l'audit AP et les tests de résistance de liquidité
Naviguez vers le **Financial_Dashboard** et les onglets analytiques. Alimenté par les tableaux dynamiques Excel natifs (`LET`, `MAP`, `LAMBDA`, `XLOOKUP`), le modèle calcule et signale automatiquement :
*   les règlements de passerelles de paiement non appariés et les variances de compensation
*   les numéros de factures de comptes fournisseurs (AP) en double et les alertes de double paiement
*   les soldes de trésorerie glissants semaine par semaine sur 12 semaines vs. les seuils de réserve de sécurité
*   les notes de réussite/échec préalables à l'approbation pour les prochains bons de commande d'inventaire

### Étape 4 : verrouiller votre routine de trésorerie mensuelle (télécharger le modèle Excel réutilisable)
Utilisez le [simulateur DTC de flux de trésorerie gratuit basé sur navigateur](https://hyvoid.github.io/shopify-cash-flow-forecast-excel-toolkit/) pour un test diagnostique immédiat de vos chiffres actuels. Une fois que vous avez validé comment le modèle expose les lacunes de trésorerie cachées, passez au tableur complet pour un contrôle financier hebdomadaire et mensuel continu.

👉 **CTA — Construisez votre système d'exploitation financier permanent :**  
**[Téléchargez le modèle Excel de Contrôle Financier Shopify & de Flux de Trésorerie déverrouillé (.xlsx)](https://www.theseusworkshop.com/l/iybjto?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=dtc-financial-control-cashflow)** — Conçu pour des flux de travail mensuels reproductibles. Collez simplement les nouveaux exports CSV par-dessus les tableaux d'entrée chaque semaine ; chaque statut de rapprochement, graphique glissant de 12 semaines et indicateur de risque d'inventaire se rafraîchit automatiquement sans réécrire une seule formule.

---

## À qui cela s'adresse : rôles e-commerce ciblés & cas d'usage à fort impact

Ce toolkit comble le fossé analytique entre la comptabilité historique (QuickBooks/Xero) et les logiciels de trésorerie d'entreprise lourds (NetSuite/Anaplan). Il est conçu spécifiquement pour des décideurs recherchant des **modèles de tableur e-commerce** actionnables :

*   **CFO e-commerce & cabinets de conseil en CFO fractionnel :**  
    *Cas d'usage :* livrer des **modèles de prévision de flux de trésorerie sur 13/12 semaines** standardisés et un reporting mensuel au conseil sur plusieurs comptes clients Shopify Plus à 7 et 8 chiffres, sans construire des tableurs personnalisés à partir de zéro.
*   **Fondateurs DTC, PDG & propriétaires de boutiques Shopify :**  
    *Cas d'usage :* utiliser un **modèle de tableau de bord financier e-commerce** léger pour répondre à la question *« Pouvons-nous nous permettre cette commande d'inventaire de 150 000 $ et escalader simultanément les publicités Meta ? »* sans embaucher un analyste FP&A à temps plein ni payer des frais d'implémentation ERP à six chiffres.
*   **Contrôleurs e-commerce, comptables & directeurs comptables :**  
    *Cas d'usage :* remplacer les feuilles `VLOOKUP` manuelles sujettes aux erreurs par un **modèle de rapprochement des versements Shopify automatisé** qui apparie les règlements au niveau de la commande aux dépôts bancaires et empêche les virements fournisseurs en double.
*   **Planificateurs d'inventaire, directeurs de la chaîne d'approvisionnement & des opérations :**  
    *Cas d'usage :* exécuter un **simulateur de flux de trésorerie d'inventaire** pendant la préparation de la haute saison Q3/Q4 pour négocier les **conditions de paiement fournisseurs Net-30 / Net-60** et fractionner les lots de production afin que les acomptes au coût complet ne franchissent jamais les réserves de trésorerie minimales.
*   **Marketers de croissance, acheteurs média & agences de performance :**  
    *Cas d'usage :* coordonner l'**escalade des dépenses publicitaires sociales payantes** avec les **cycles de conversion de trésorerie (CCC)** réels, en veillant à ce que les campagnes d'acquisition client agressives ne déclenchent pas de gels de fonds de roulement à court terme dus aux retenues des processeurs de paiement.

*Note de portée : ce toolkit ne remplace **pas** votre grand livre statutaire (QuickBooks, Xero) ni les logiciels de conformité fiscale. Il opère comme une **couche de soutien à la décision FP&A** agile posée au-dessus de vos exports comptables existants.*

---

## Scénarios e-commerce réels : quand déployer ce modèle de flux de trésorerie

Les comptes de résultat (P&L) statiques échouent lors des points d'inflexion opérationnels rapides. Déployez ce toolkit face à ces scénarios DTC à enjeux élevés :

### Scénario 1 : financement d'inventaire de haute saison (Q4 / Black Friday Cyber Monday)
Vous devez émettre un bon de commande de fabrication de 200 000 $ en août avec 30 % d'acompte initial et 70 % dus au connaissement, bien avant que les revenus BFCM n'atteignent votre compte bancaire. Utilisez le **simulateur d'impact d'inventaire** pour modéliser les creux de trésorerie hebdomadaires exacts et tester si le fractionnement de l'expédition ou la négociation de conditions Net-45 empêche une rupture de liquidité en semaine 7.

### Scénario 2 : escalade rapide de l'acquisition payante & gestion du décalage des versements
Votre ROAS est rentable et vous escaladez les dépenses publicitaires quotidiennes Meta et Google de 2 000 $/jour à 6 000 $/jour. Cependant, les plateformes publicitaires débitent rapidement votre carte de crédit/banque tandis que les passerelles Shopify Payments, PayPal et Acheter Maintenant Payer Plus Tard (BNPL) retiennent ou retardent les versements de 3 à 7 jours ouvrés. Utilisez la **prévision de flux de trésorerie sur 12 semaines** pour modéliser le pont de fonds de roulement exact requis pour financer l'écart de règlement.

### Scénario 3 : audit du compte d'attente en fin de mois & récupération des rétrofacturations
Votre tableau de bord Shopify rapporte 500 000 $ de ventes mensuelles brutes, mais votre compte courant ne reflète que 442 000 $ de dépôts nets. Au lieu de passer 15 heures à recouper manuellement les lignes CSV, exécutez le **moteur de rapprochement à trois voies** pour isoler immédiatement les commandes exactes affectées par les frais de processeur, les remboursements en attente, les retenues de réserve ou les règlements bancaires manquants.

---

## Comparaison des flux de travail : tableurs manuels & systèmes ERP vs. toolkit automatisé

| Flux de travail financier e-commerce central | Comptabilité manuelle traditionnelle (QuickBooks + VLOOKUPs manuels) | Logiciel ERP/trésorerie d'entreprise (NetSuite, HighRadius) | Ce toolkit Excel de Contrôle Financier DTC |
| :--- | :--- | :--- | :--- |
| **Rapprochement des versements Shopify commande-à-banque** | Les contrôleurs exportent manuellement les CSV et construisent des feuilles `VLOOKUP` fragiles qui cassent lorsqu'un versement couvre plusieurs commandes. | Nécessite des connecteurs middleware coûteux (p. ex. Celigo/A2X) et une configuration complexe des règles de compte d'attente. | Le **moteur de tableaux dynamiques automatisé** (`UNIQUE`/`MAP`/`SUMIFS`) isole instantanément les versements non appariés et les variances dollar exactes. |
| **Détection des factures AP en double** | Les comptables s'appuient sur des contrôles visuels, ne découvrant les virements fournisseurs en double qu'après le rapprochement bancaire de fin de mois. | Imposé via des hiérarchies d'approbation des achats rigides qui ralentissent les chaînes d'approvisionnement DTC agiles. | Le **module de revue AP en temps réel** signale les ID de factures en double et les montants de paiement suspects avant tout décaissement. |
| **Prévision de flux de trésorerie glissante sur 12 semaines** | Construite sur des tableurs statiques mis à jour manuellement qui deviennent obsolètes dès que les dépenses hebdomadaires réelles s'écartent. | Nécessite des administrateurs FP&A dédiés et des semaines d'intégration pour configurer les règles de prévision. | La **chronologie glissante auto-décalée** (`SEQUENCE`/`TODAY`) met à jour automatiquement les projections de liquidité hebdomadaires à partir des collages CSV bruts. |
| **Tests de résistance des PO d'inventaire & du fonds de roulement** | Les équipes opérationnelles approuvent les PO d'usine sur la base du solde bancaire du jour, ignorant les factures publicitaires et les salaires qui se chevauchent à 6 semaines. | Enfermé dans des modules MRP complexes déconnectés des dépenses marketing en temps réel et des retards de règlement des passerelles. | Le **simulateur d'impact de PO interactif** modélise les dates d'acompte et de solde contre votre **réserve de trésorerie de sécurité** configurable. |
| **Temps d'implémentation & coût total de possession** | 0 $ de coût logiciel, mais consomme 20–40 heures/mois de main-d'œuvre financière et de contrôle à haut coût. | De 25 000 $ à 100 000+ $ de licence annuelle plus 3–6 mois d'implémentation par des consultants. | **Test instantané dans le navigateur** + un **modèle Excel réutilisable** abordable et unique, prêt en moins de 15 minutes. |

---

## La logique métier & la méthodologie

Ce toolkit n'est pas un modèle de reporting passif ; il est conçu autour de quatre **méthodologies établies de finance d'entreprise et de trésorerie**, taillées pour résoudre les vulnérabilités structurelles du modèle économique direct-to-consumer (DTC).

### 1. Résoudre le cycle de conversion de trésorerie (CCC) inversé
Dans le e-commerce de détail, le **cycle de conversion de trésorerie (CCC = DIO + DSO - DPO)** est structurellement inversé pendant les phases de croissance. Les marques décaissent de la trésorerie à l'avance pour les acomptes d'inventaire (**jours de stock**) et le marketing de performance quotidien, tout en attendant des jours ou des semaines que les processeurs de paiement (Stripe, Shopify Payments, PayPal, Affirm) règlent les fonds (**jours de crédit client**). La **comptabilité d'exercice (GAAP)** traditionnelle enregistre le revenu au paiement, masquant de graves déficits de timing de trésorerie. Ce toolkit impose une **visibilité de trésorerie en base de trésorerie**, faisant passer les décisions de direction du profit théorique du compte de résultat à la **liquidité du fonds de roulement** critique pour la survie.

### 2. Rapprochement déterministe à trois voies des règlements marchands
*   **La méthode :** adapte les **principes d'appariement à trois voies** d'entreprise à la reconnaissance de revenus e-commerce en recoupant trois livres de données indépendants : l'**origine de la commande** (ventes brutes/nettes Shopify), le **transit de compensation** (rapports de versements des passerelles de paiement) et le **règlement final** (relevés bancaires commerciaux).
*   **Le problème métier résolu :** élimine la fuite silencieuse de revenus et l'enflure du compte d'attente. En isolant mathématiquement les variances au niveau transactionnel, les équipes financières détectent immédiatement les retenues de réserve des processeurs, les rétrofacturations non enregistrées, les pertes de conversion FX et les virements bancaires échoués sans auditer des milliers de lignes appariées.

### 3. Prévision de flux de trésorerie glissante sur 12 semaines par la méthode directe
*   **La méthode :** implémente la **méthode directe de prévision des flux de trésorerie** sur un **horizon glissant de 12 semaines** dynamique et auto-progressif (la norme institutionnelle pour le management de retournement et le contrôle de trésorerie des CFO fractionnels). Au lieu d'estimations de pourcentage descendantes, elle agrège les engagements opérationnels ascendants : acomptes de PO programmés, salaires/OPEX récurrents, vélocité de règlement historique et burn publicitaire hebdomadaire actif.
*   **Le problème métier résolu :** éradique le piège de la « faillite rentable ». Il répond à la question opérationnelle la plus critique six à huit semaines à l'avance : *« Les soldes fournisseurs et les factures marketing qui se chevauchent pousseront-ils notre solde bancaire sous notre réserve d'exploitation minimale en semaine 7 ? »*

### 4. Optimisation de l'inventaire & du fonds de roulement par contraintes
*   **La méthode :** utilise des **tests de résistance de liquidité par scénarios** (inspirés de la modélisation financière de la **théorie des contraintes**). Chaque bon de commande d'inventaire proposé est évalué contre deux portes de trésorerie temporelles — la **date d'acompte initial** et la **date de règlement du solde final** — référencées contre un **plancher de réserve de trésorerie de sécurité** strict.
*   **Le problème métier résolu :** transforme les achats d'un conflit binaire *« acheter vs. geler »* en un levier de négociation structuré. Les dirigeants de la chaîne d'approvisionnement et de la finance peuvent déterminer mathématiquement si l'extension des conditions fournisseurs à **Net-30**, le fractionnement de la production en deux lots décalés ou le report d'une PO de 14 jours préserve 100 % de la vélocité des revenus tout en éliminant le risque d'insolvabilité.

---

## L'origine : pourquoi j'ai construit ce système d'exploitation financier

Beaucoup de marques Shopify en croissance croient avoir une visibilité financière parce qu'elles possèdent des logiciels comptables, des comptes bancaires et des tableaux de bord de ventes. En pratique, chaque système répond à une question isolée :

*   Les **logiciels comptables (QuickBooks/Xero)** expliquent ce qui s'est déjà passé (*enregistrement historique en comptabilité d'engagement*).
*   **Shopify Analytics** explique ce que les clients ont commandé (*valeur marchande brute*).
*   Les **portails bancaires** montrent où se trouve la trésorerie aujourd'hui (*instantané statique*).
*   Les **gestionnaires de publicités (Meta/Google)** expliquent où le budget a été dépensé (*coût d'acquisition attribué*).

Aucun d'eux ne calcule indépendamment si les décisions d'achat et de marketing d'aujourd'hui déclencheront une crise de fonds de roulement dans six semaines. L'inventaire est commandé parce que les ventes semblent fortes ; les budgets publicitaires sont escaladés parce que le ROAS semble sain ; les factures fournisseurs sont payées parce que le solde courant du jour semble élevé — jusqu'à ce que les retards de règlement, les soldes de PO et les factures publicitaires se heurtent la même semaine.

**Avant de déployer ce toolkit :**  
Une marque Shopify générant 480 000 $/mois de revenus approuve une PO d'inventaire de 150 000 $ sur la base d'un solde bancaire sain. Trois semaines plus tard, la facturation publicitaire par carte de crédit, les acomptes fournisseurs et les versements Shopify retardés se chevauchent, faisant tomber la trésorerie sous les exigences de paie.

**Après avoir déployé ce toolkit :**  
La même PO de 150 000 $ est saisie dans le **simulateur d'impact d'inventaire** avant approbation. Le modèle signale que la trésorerie de clôture de la semaine 7 franchira la réserve de sécurité configurée. La direction reporte la moitié de l'expédition de deux semaines et négocie des conditions Net-30 avec l'usine. Les objectifs de revenus sont atteints ; le risque de crise de trésorerie est neutralisé.

---

## Architecture du classeur & référence technique

Le classeur Excel suit une **norme stricte de modélisation financière à trois couches** séparant les **entrées de données brutes**, les **moteurs de calcul par tableaux dynamiques** et la **présentation exécutive**. Chaque feuille de calcul a une responsabilité analytique unique pour empêcher la corruption des formules et assurer l'auditabilité.

| Nom de la feuille | Objet fonctionnel central | Couche d'architecture |
| :--- | :--- | :--- |
| `Parameters` | Paramètres globaux de trésorerie, seuils de réserve de sécurité, taux FX et horizon de prévision | **Entrée & configuration** |
| `Shopify_Data` | Tableau d'import CSV brut pour les commandes Shopify, remboursements, frais de passerelle et versements | **Entrée de données** |
| `Bank_Transactions` | Imports de relevés de compte courant commercial et de processeurs de paiement | **Entrée de données** |
| `Accounting_Data` | Écritures AP du grand livre, factures fournisseurs et suivi des factures | **Entrée de données** |
| `Inventory_Purchases` | Bons de commande (POs) ouverts, pourcentages d'acompte, délais et dates d'échéance | **Entrée de données** |
| `Advertising_Spend` | Dépenses média payantes quotidiennes/hebdomadaires sur Meta, Google, TikTok et les agences | **Entrée de données** |
| `Reconciliation_Engine` | Appariement intersystèmes automatisé des règlements commande-à-banque | **Calcul analytique** |
| `Payment_Review` | Détection automatisée des factures en double et des trop-payés AP | **Calcul analytique** |
| `Cash_Flow_Forecast` | Projection de liquidité directe glissante sur 12 semaines et agrégation du burn de trésorerie | **Calcul analytique** |
| `Inventory_Impact_Simulator` | Tests de résistance des achats préalables à l'approbation contre les réserves de trésorerie de sécurité | **Calcul analytique** |
| `Financial_Dashboard` | Résumé exécutif des KPI CEO/CFO, alertes d'exception et graphiques de liquidité | **Présentation exécutive** |

<details>
<summary><strong>Cliquer pour déplier : diagrammes de flux de données, trois pièges financiers & formules de tableaux dynamiques Excel (LET / LAMBDA / MAP / XLOOKUP)</strong></summary>

---

<details>
<summary><strong>Flux de données système & architecture de validation</strong></summary>

```text
            ┌────────────────────────────┐
            │         Data Input         │
            └─────────────┬──────────────┘
                          │
 Shopify Orders           │
 Bank Transactions        │
 Accounting Entries       │
 Purchase Orders          │
 Advertising Spend        │
 Parameters               │
                          ▼
  ┌───────────────────────────────────────────┐
  │       Analytical Calculation Layer        │
  │                                           │
  │ Reconciliation Engine                     │
  │ Payment Review                            │
  │ Cash Flow Forecast                        │
  │ Inventory Impact Simulator                │
  └───────────────────────┬───────────────────┘
                          │
                          ▼
          ┌───────────────────────────┐
          │ Executive Dashboard (CEO) │
          └───────────────────────────┘
```

Le classeur bloque volontairement le reporting direct à partir des entrées CSV brutes. Chaque KPI sur le `Financial_Dashboard` provient de feuilles analytiques validées, alimentées par des **tableaux Excel** structurés — ce qui signifie qu'à mesure que votre nombre de lignes passe de 100 à 50 000 transactions, les formules de tableaux dynamiques se propagent et s'étendent automatiquement sans glisser ni copier de cellules.

</details>

---

<details>
<summary><strong>Trois pièges qui attrapent même les équipes financières e-commerce expérimentées</strong></summary>

<details>
<summary><strong>Piège 1 — supposer que le solde bancaire du jour représente le fonds de roulement disponible</strong></summary>

*   **La décision erronée :** approuver une commande d'inventaire de 180 000 $ parce que le compte courant détient actuellement 420 000 $ (`$420k - $180k = $240k remaining`).
*   **Pourquoi elle échoue :** le timing de trésorerie importe plus que les soldes statiques. Trois semaines plus tard, les paiements de soldes fournisseurs, les factures publicitaires, les salaires et un retard de règlement Shopify de 4 jours se heurtent en semaine 7, faisant tomber la trésorerie réelle à **82 000 $** (rupture de la **réserve de sécurité de 100 000 $**).
*   **Solution du modèle :** évalue la liquidité projetée à la semaine de l'acompte initial comme à la semaine du paiement final, avant que l'argent ne soit engagé :

```excel
=LET(
min_cash,
XLOOKUP(
"Safety_Cash_Reserve",
Parameters[Param_Name],
Parameters[Param_Value],
50000
),
...
)
```

</details>

<details>
<summary><strong>Piège 2 — traiter chaque commande Shopify terminée comme de la trésorerie encaissée</strong></summary>

* **La décision erronée :** supposer que 615 000 $ de ventes Shopify déclarées équivalent à 615 000 $ de dépôts bancaires.
* **Pourquoi elle échoue :** un versement peut regrouper plusieurs commandes ; une commande peut se diviser en règlements partiels ; les rétrofacturations et les réserves de passerelle créent des variances silencieuses.
* **Solution du modèle :** construit un index de commandes unique et mappe dynamiquement les paiements nets attendus de Shopify contre les flux de référence bancaires agrégés :

```excel
=UNIQUE(
FILTER(
Shopify_Data[Order ID],
Shopify_Data[Order ID]<>""))

```

```excel
=MAP(
A2#,
LAMBDA(order_id,
SUMIFS(
Bank_Transactions[Amount],
Bank_Transactions[Reference ID],
order_id
)))

```

</details>

<details>
<summary><strong>Piège 3 — s'appuyer sur des budgets mensuels statiques pendant une escalade à grande vitesse</strong></summary>

* **Cas pratique (marque Shopify à 520 000 $/mois) :** avec 468 000 $ de trésorerie d'ouverture, une PO de 210 000 $ (30 % d'acompte / 70 % de solde) et 34 000 $/semaine de dépenses publicitaires, les budgets mensuels statiques montrent un trimestre rentable se terminant à **299 400 $**. Cependant, la **prévision glissante sur 12 semaines** expose un creux temporaire en semaine 7 de **95 800 $** (sous le plancher de sécurité de 100 000 $). En reportant le paiement du solde fournisseur de 14 jours ou en fractionnant la PO en deux lots, la marque préserve sa pleine continuité opérationnelle.

| Semaine | Trésorerie d'ouverture | Entrées de trésorerie | Sorties de trésorerie | Trésorerie de clôture | Statut de réserve |
| --- | --- | --- | --- | --- | --- |
| Semaine 1 | 468 000 $ | 92 400 $ | 97 600 $ | 462 800 $ | Sûr |
| Semaine 3 | 459 200 $ | 86 700 $ | 158 500 $ | 387 400 $ | Sûr |
| Semaine 6 | 310 300 $ | 84 900 $ | 176 200 $ | 219 000 $ | Sûr |
| **Semaine 7** | **219 000 $** | **73 600 $** | **196 800 $** | **95 800 $** | **RUPTURE (sous 100 k$)** |
| Semaine 8 | 95 800 $ | 168 700 $ | 118 500 $ | 146 000 $ | Récupéré |
| Semaine 12 | 264 600 $ | 170 500 $ | 135 700 $ | 299 400 $ | Sûr |

</details>

</details>

---

<details>
<summary><strong>Référence des formules de base & règles de validation des entrées</strong></summary>

<details>
<summary><strong>Référence des formules de base</strong></summary>

* **Générateur de chronologie glissante sur 12 semaines :** `=TODAY()+SEQUENCE(1,12,0,7)`

* **Agrégation hebdomadaire dynamique des dépenses publicitaires :**

```excel
=MAP(
C1#,
LAMBDA(
week_start,
SUMIFS(
Advertising_Spend[Cost],
Advertising_Spend[Date],
">="&week_start,
Advertising_Spend[Date],
"<"&week_start+7)))

```

* **Classificateur de variance de rapprochement automatisé :**

```excel
=MAP(
D2#,
LAMBDA(diff,
IFS(
diff=0,
"Matched",
ABS(diff)<0.05,
"Minor Difference",
TRUE,
"Variance")))

```

</details>

<details>
<summary><strong>Règles de validation des entrées</strong></summary>

| Champ d'entrée | Règle de validation intégrée | Comportement de gestion des erreurs système |
| --- | --- | --- |
| `Order ID` | Chaîne non vide | Exclu de l'index de rapprochement dynamique |
| `Invoice Number` | Vérification des doublons `COUNTIF` | Déclenche un avertissement immédiat de double paiement AP |
| `Payment Amount` | Validation numérique stricte | Les enregistrements non numériques sont contournés jusqu'à correction |
| `Purchase Order Value` | Valeur numérique positive | Désactive la simulation de PO pour les lignes invalides |
| `Prepayment Percentage` | Décimale entre `0%` et `100%` | Déclenche un avertissement de plage de paramètres |
| `Safety Cash Reserve` | Seuil numérique positif | Applique la valeur de repli `$50,000` si omis |

</details>

</details>

</details>


---

## À propos du créateur & plus de toolkits de soutien à la décision opérationnelle

Je construis des **modèles financiers Microsoft Excel** légers et des **toolkits de soutien à la décision opérationnelle** basés sur navigateur pour des environnements commerciaux à grande vitesse où les logiciels fragmentés rendent difficile une allocation de capital fiable. Chaque cadre répond à une question fondamentale :

> *« Quelles données interfonctionnelles doivent exister dans un modèle centralisé avant que la prochaine décision financière à enjeux élevés puisse être prise avec confiance ? »*

### Explorez d'autres modèles financiers & opérationnels de cette série :

* **Classeur de contrôle des coûts de projet de construction & de coûts par emploi**
* **Moteur de décision de gestion des revenus & de tarification e-commerce**
* **Automatisation des règlements & de la rentabilité vendeur Amazon FBA**
* **Modèle d'attribution marketing multi-touch CRM & Shopify**
* **Modèle financier d'acquisition immobilière multifamiliale**
* **Tableaux de bord KPI FP&A exécutifs & cadres de prévision glissante**

Parcourez la bibliothèque complète de classeurs de qualité commerciale, de simulateurs web interactifs et de guides de mise en œuvre sur **[Theseus Workshop — Modélisation financière opérationnelle & toolkits Excel de soutien à la décision](https://www.theseusworkshop.com/)**.

---

## Licence

Sous licence **Apache License 2.0**.

Ce projet peut être utilisé, modifié et distribué conformément aux termes de la licence Apache 2.0.

Voir le fichier **LICENSE** inclus dans ce dépôt pour les informations de licence complètes.
