[ 🌐 عربي ](README.ar.md) | [ 🇫🇷 Français ](README.fr.md) | [ 🇳🇱 Nederlands ](README.nl.md) | [ 🇪🇸 Español ](README.sp.md) | [ 🇬🇧 English ](README.md)

# Kit de suivi des prêts familiaux et de rapprochement des flux de fonds : modèle Excel de solde courant et de calcul d'intérêts

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](#license)
[![Platform](https://img.shields.io/badge/Platform-Browser%20%2B%20Excel-green.svg)](#access)
[![Tool Type](https://img.shields.io/badge/Tool%20Type-Financial%20Reconciliation%20Spreadsheet-orange.svg)](#what-it-helps-track)

**Un classeur complet de suivi des prêts familiaux et de rapprochement des flux de fonds. Reconstruisez des années de transferts d'argent dans les deux sens entre membres d'une famille sous forme de solde de principal courant traçable, calculez automatiquement les intérêts courus et générez une piste d'audit transparente pour vos accords financiers privés.**

> **Essayez le calculateur web gratuit. Pour les utilisateurs qui ont besoin d'un enregistrement financier permanent, de pistes d'audit hors ligne et d'un suivi de compte mensuel récurrent, vous pouvez télécharger le modèle Excel entièrement débloqué avec une garantie de remboursement de 30 jours.**
>
> 🌐 Ouvrir dans le navigateur → [Essayez l'application web gratuite de suivi des prêts entre membres d'une famille (démo en ligne)](https://hyvoid.github.io/family-loan-tracker-excel/)
> 
> 📥 Télécharger le modèle → [Téléchargez le modèle Excel réutilisable pour le rapprochement des prêts familiaux (version hors ligne)](https://theseusworkshop.com/l/auauhp?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=family-fund-interest-reconciliation)  

## Fonctions principales : points de friction et solutions de suivi

Au lieu de suivre des transferts cumulés qui ne révèlent pas la véritable situation financière, ce kit transforme des relevés bancaires dispersés en un tableau d'amortissement d'emprunt normalisé.

| Point de friction courant (le problème) | Comment ce calculateur le résout (la solution) |
| :--- | :--- |
| **Perte de suivi de l'historique des sommes prêtées et remboursées** | Sépare les avances de trésorerie historiques des remboursements partiels sur l'ensemble du grand livre des transactions. |
| **Relevés bancaires saisis dans le désordre** | Reconstruit automatiquement le **solde de principal courant**, quel que soit l'ordre de saisie des données. |
| **Intérêts forfaitaires appliqués à des soldes variables** | Calcule les **intérêts courus** avec précision sur chaque période en cours, à partir du solde quotidien exact. |
| **Inflation historique ou taux de marché fluctuants** | Applique des grilles de taux de marché historiques personnalisables, en associant chaque taux d'intérêt à ses périodes d'effet exactes. |
| **Soldes finaux en bloc non expliqués** | Répartit le total actuellement dû en colonnes distinctes et auditables : **Capital vs. Intérêts courus**. |
| **Extension manuelle des formules pour de nouveaux paiements** | Prolonge automatiquement la date de calcul jusqu'à « Aujourd'hui », en reportant automatiquement le total actuellement dû. |

## Démarrage rapide : comment reconstruire vos registres financiers

Suivez ce processus pour transformer un historique financier désordonné en un bilan propre et auditable. 

**Étape 1 : Configurez les paramètres d'emprunt et d'intérêt**
Définissez votre base de référence financière dans le tableau de bord des paramètres. Réglez le symbole monétaire, la base de calcul des jours (par ex. Actual/365), la méthode de capitalisation des intérêts et cartographiez la grille historique des taux de marché (par ex. en correspondance avec les IRS Applicable Federal Rates ou avec des taux convenus personnalisés).

**Étape 2 : Importez votre grand livre historique de transactions**
Collez vos données financières brutes dans le tableau de saisie. Le système n'exige que des données de base : identifiant de transaction, date, sens du transfert (entrée/sortie), montant et un court mémo. Vous pouvez copier-coller directement ces éléments depuis vos exports CSV bancaires.

**Étape 3 : Générez le tableau de solde chronologique**
Laissez le moteur de calcul dynamique traiter les données. Il triera automatiquement tous les enregistrements par ordre chronologique, harmonisera les flux de trésorerie positifs et négatifs, reconstruira le principal courant quotidien et calculera les intérêts exacts courus entre chaque période de remboursement.

**Étape 4 : Tenez à jour les remboursements en cours**
À mesure que de nouveaux paiements sont effectués, ajoutez-les simplement en bas du grand livre. Le moteur recalcule instantanément les intérêts courus et le solde total dû jusqu'à la date du jour.

👉 **Prêt à constituer un registre permanent ?** [Téléchargez le modèle Excel](https://theseusworkshop.com/l/auauhp?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=family-fund-interest-reconciliation) pour conserver vos données financières privées en sécurité hors ligne et réutiliser le moteur de calcul dans le cadre de votre rapprochement mensuel.

## Pourquoi j'ai créé cet outil de rapprochement des fonds familiaux

Les arrangements financiers familiaux de longue durée (comme des parents qui financent l'apport de leur enfant, ou des frères et sœurs qui cofinancent un bien) se constituent souvent sans la structure rigide d'un système formel de gestion d'emprunt.

L'argent circule dans les deux sens au fil des années. Les traces s'accumulent dans les relevés bancaires, les messages WhatsApp et la mémoire. Au bout du compte, la question la plus difficile n'est pas *« Combien d'argent a circulé ? »* C'est :

**« Quel était le solde dû exact à une date historique donnée, et combien d'intérêts auraient dû être courus sur ce solde précis ? »**

Un simple `SUM()` des transferts dans un tableur de base ne peut pas y répondre. Si les enregistrements contiennent plusieurs avances de trésorerie suivies de remboursements partiels sporadiques, un total de base ignore la *valeur temporelle de l'argent* et la durée pendant laquelle chaque dollar est resté impayé. 

Ce kit industrialise le raisonnement financier qui sous-tend une comptabilité complexe. Il transforme une décennie de transactions désordonnées et mêlées en un cadre de calcul strictement chronologique et défendable.

## Tableur automatisé vs. comptabilité manuelle sur grand livre

| Obstacles de la comptabilité manuelle (sans outil) | Rapprochement Excel automatisé (avec l'outil) |
| :--- | :--- |
| **Chronologie désorganisée :** calculer des soldes courants à partir d'écritures de grand livre hors ordre provoque des erreurs de calcul composées. | **Tri automatisé :** le moteur de calcul réordonne l'intégralité de l'historique des transactions par date avant d'appliquer les formules d'intérêt. |
| **Signes de flux de trésorerie incohérents :** décider manuellement si un transfert constitue un ajustement positif ou négatif entraîne des ruptures de formule. | **Flux de trésorerie normalisés :** les sens de transaction (avances vs. remboursements) sont analysés selon une convention de mouvement comptable stricte. |
| **Erreurs d'intérêt statiques :** appliquer un taux d'intérêt unique et forfaitaire à un solde dynamique sur plusieurs années majore ou minore les intérêts. | **Comptabilisation par période :** les intérêts composés ou simples sont calculés précisément sur chaque période historique distincte. |
| **Opacité des taux :** utiliser un taux unique moyen masque la réalité des taux d'intérêt macroéconomiques changeants sur une décennie. | **Affectation de taux variables :** chaque période de transaction est automatiquement rapprochée, par recherche, de la grille de taux de marché effectifs définie par l'utilisateur. |
| **Mélange des données :** mélanger capital et intérêts dans une seule colonne rend le montant final de la dette impossible à auditer ou à expliquer à la famille. | **Séparation des données :** soldes de capital, plafonds d'intérêts courus et dettes totales sont calculés dans des colonnes isolées et transparentes. |

## Utilisateurs cibles et cas d'usage spécifiques

Ce tableur est conçu pour les personnes qui gèrent des relations financières de long terme, où les transactions historiques doivent être rétro-calculées en un solde et un échéancier d'intérêts mathématiquement solides. 

**Recherchez et identifiez votre profil :**
* **Parents et tuteurs :** suivre les avances de trésorerie de la *« banque de papa et maman »*, gérer des modèles de remboursement de prêt personnel pour les enfants avec des conditions d'intérêt transparentes.
* **Exécuteurs testamentaires et administrateurs de successions :** rapprocher les prêts historiques entre membres d'une famille, documenter les dettes héritées et générer des pistes d'audit pour les successions ou les distributions de trusts familiaux.
* **Gestionnaires de family office :** exploiter un suivi des flux de fonds entre entités pour surveiller les apports et les retraits de capitaux informels au sein d'entreprises détenues par une famille.
* **Frères et sœurs et co-investisseurs :** tenir un registre d'investissement conjoint informel pour suivre qui a payé quoi au fil des années de propriété partagée ou d'une activité entrepreneuriale commune.
* **Particuliers qui gèrent eux-mêmes leurs finances :** toute personne ayant besoin d'une alternative robuste aux logiciels de comptabilité complexes (comme QuickBooks) pour apurer des registres de prêts entre particuliers (P2P) de long terme.

*(Remarque : ce kit fournit des calculs d'aide à la décision. Il ne remplace ni un service d'expertise comptable certifiée (CPA), ni une documentation juridique formelle de prêt, ni un conseil en matière de conformité fiscale.)*

## À propos de l'architecture

Je conçois des outils de suivi opérationnel légers et des modèles d'aide à la décision pour des environnements qui ont trop de pièces mobiles pour être calculés de tête, mais pas assez de complexité pour justifier un logiciel ERP d'entreprise. 

La philosophie de conception centrale est simple : **les informations doivent être structurées chronologiquement pour prendre la prochaine décision financière en toute confiance.** 

Ce kit rejette la comptabilité générique. C'est un moteur étroitement ciblé, conçu exclusivement pour reconstruire des chronologies, cartographier des taux d'intérêt variables et démontrer la position exacte actuellement due sur des fonds privés.

## Détails techniques

<details>
<summary>Pour les réviseurs techniques, les praticiens d'Excel et les collaborateurs</summary>

### Architecture du classeur

Le classeur utilise cinq feuilles réparties sur quatre couches fonctionnelles :

| Feuille             | Rôle                                                                                                  | Entrée / Sortie                     |
| ----------------- | ----------------------------------------------------------------------------------------------------- | ---------------------------------- |
| `00_Instructions` | Instructions système, informations de version et mode d'emploi                                      | Statique                             |
| `01_Parameters`   | Hypothèses globales, définitions des sens, base de calcul des jours, méthode d'intérêt et grille des taux de marché | Saisie manuelle                       |
| `02_Transactions` | Grand livre historique des mouvements de fonds dans les deux sens                                                               | Saisie manuelle + calcul dynamique |
| `03_CalcEngine`   | Reconstruction chronologique, principal courant, correspondance des taux, décompte des jours et moteur d'intérêts       | Piloté par formule                     |
| `04_Summary`      | Solde actuellement dû et ventilation capital/intérêts                                          | Piloté par formule                     |

Le flux de données principal est :

```text
01_Parameters
      │
      ├──────────────┐
      │              ▼
      │       02_Transactions
      │              │
      │              ▼
      └──────► 03_CalcEngine
                     │
                     ▼
                 04_Summary
```

Le moteur de calcul effectue quatre opérations principales :

1. Trier les transactions historiques par ordre chronologique.
2. Convertir chaque transaction en un mouvement signé normalisé.
3. Reconstruire le principal courant et faire correspondre le taux de marché applicable.
4. Calculer les intérêts de période et les intérêts courus cumulés.

Le résumé extrait ensuite les derniers résultats de capital et d'intérêts courus pour présenter la position actuellement due. L'architecture source définit explicitement la chaîne de dépendances transaction → moteur → résumé.  

### Trois pièges qui piègent même les gestionnaires de registres financiers chevronnés

#### Piège 1 — Considérer les transferts cumulés comme la réponse complète

**1. Une décision a été prise :**
Déterminer le montant actuellement dû en soustrayant le total des remboursements au total des avances.

**2. Le défaut non remarqué :**
Cela établit le capital net, mais ne dit rien sur la durée pendant laquelle différents soldes sont restés dus.

**3. Pourquoi cela change le résultat :**
Les intérêts dépendent à la fois du capital et du temps écoulé.

**4. Pourquoi le raisonnement est incomplet :**
Un solde de $10,000 dû pendant plusieurs années est économiquement différent d'un solde de $10,000 apparu récemment.

**5. Approche corrigée :**
Reconstruire le principal courant après chaque transaction et calculer chaque intervalle séparément.

**6. Résultat corrigé :**
Le résultat actuel contient à la fois le capital restant dû et les intérêts cumulés imputables aux périodes historiques.

<details>
<summary>Logique de la formule</summary>

```excel
=SCAN(0, B2#, LAMBDA(prev_bal, curr_mvmt, prev_bal + curr_mvmt))
```

Ceci crée un solde de principal courant à partir du vecteur de mouvement de transaction normalisé.

</details>

#### Piège 2 — Appliquer un seul taux d'intérêt à tout l'historique

**1. Une décision a été prise :**
Appliquer le taux de marché supposé aujourd'hui à l'ensemble du solde historique.

**2. Le défaut non remarqué :**
Le taux applicable a pu changer au cours de la période historique.

**3. Pourquoi cela change le résultat :**
Différentes périodes peuvent porter des taux annuels différents.

**4. Pourquoi le raisonnement est incorrect :**
Un taux actuel ne représente pas automatiquement toutes les périodes historiques.

**5. Approche corrigée :**
Tenir une grille de taux avec dates d'effet et faire correspondre chaque date de transaction au taux historique applicable.

**6. Résultat corrigé :**
Chaque période est calculée avec le taux défini comme effectif à ce point de la chronologie.

<details>
<summary>Logique de la formule</summary>

```excel
=MAP(A2#, LAMBDA(d,
    XLOOKUP(
        d,
        '01_Parameters'!$A$13:$A$20,
        '01_Parameters'!$B$13:$B$20,
        0,
        -1
    )
))
```

Le mode de correspondance `-1` récupère la date d'effet exacte ou la date d'effet inférieure la plus proche.

</details>

#### Piège 3 — Calculer les intérêts sans reconstruire les intervalles de temps

**1. Une décision a été prise :**
Calculer les intérêts d'une date de transaction à une date de règlement fixe.

**2. Le défaut non remarqué :**
Des transactions ultérieures ont pu modifier le capital dû au cours de cette période.

**3. Pourquoi cela change le résultat :**
Les intérêts doivent refléter le solde applicable pendant chaque intervalle.

**4. Pourquoi le raisonnement est incorrect :**
Un calcul unique d'une date à l'autre ignore les variations du capital entre les transactions.

**5. Approche corrigée :**
Calculer le nombre de jours entre chaque transaction et la suivante, en utilisant la date du jour comme point d'arrivée pour la dernière période ouverte.

**6. Résultat corrigé :**
Les intérêts suivent le solde historique reconstruit plutôt qu'un montant statique supposé.

<details>
<summary>Logique de la formule</summary>

```excel
=LET(
    dates, A2#,
    n, ROWS(dates),
    MAP(SEQUENCE(n), LAMBDA(i,
        IF(
            i = n,
            TODAY() - INDEX(dates, i),
            INDEX(dates, i + 1) - INDEX(dates, i)
        )
    ))
)
```

La dernière transaction continue d'accumuler des intérêts jusqu'à la date du jour.

</details>

### Scénario d'exemple

Considérons une séquence historique simplifiée :

| Date       | Sens       |  Montant |
| ---------- | --------- | ------: |
| 2020-01-15 | Avance     | $20,000 |
| 2020-09-01 | Avance     | $10,000 |
| 2021-06-15 | Remboursement |  $8,000 |
| 2022-03-01 | Remboursement |  $5,000 |

Le mouvement normalisé devient :

```text
2020-01-15    +20,000
2020-09-01    +10,000
2021-06-15     -8,000
2022-03-01     -5,000
```

Le principal courant devient donc :

```text
After 2020-01-15    $20,000
After 2020-09-01    $30,000
After 2021-06-15    $22,000
After 2022-03-01    $17,000
```

Le changement analytique important est que les intérêts ne sont pas calculés sur $17,000 pour toute la période historique.

Le moteur reconnaît plutôt différents intervalles de solde :

```text
$20,000  →  until 2020-09-01
$30,000  →  until 2021-06-15
$22,000  →  until 2022-03-01
$17,000  →  from 2022-03-01 → today
```

Si la grille des taux de marché change entre ces dates, le taux applicable à chaque intervalle est déterminé à partir de la table des dates d'effet.

La sortie obtenue distingue :

```text
Net Outstanding Principal
+ Accrued Interest
----------------------
Current Total Outstanding
```

Cela rend le chiffre final explicable : il peut être reconstitué à partir de la séquence des transactions, des intervalles de solde, des hypothèses de taux et des jours écoulés, plutôt que d'être un montant de règlement saisi manuellement.

### Référence des formules

<details>
<summary>Sens de transaction → mouvement net</summary>

```excel
=LET(
    tx_dates, FILTER(A2:A10000, A2:A10000<>""),
    dirs, FILTER(C2:C10000, A2:A10000<>""),
    amts, FILTER(D2:D10000, A2:A10000<>""),
    out_dir, '01_Parameters'!$B$8,
    in_dir, '01_Parameters'!$B$9,
    MAP(
        dirs,
        amts,
        LAMBDA(d, a,
            IF(d=out_dir, a, IF(d=in_dir, -a, 0))
        )
    )
)
```

**Objet :** convertit les sens de transaction en un mouvement signé normalisé.

**Logique :** le sens d'avance/sortie configuré devient positif ; le sens de remboursement/entrée configuré devient négatif.

</details>

<details>
<summary>Tri chronologique des transactions</summary>

```excel
=LET(
    raw_dates, FILTER('02_Transactions'!B2:B10000, '02_Transactions'!A2:A10000<>""),
    raw_mvmt, FILTER('02_Transactions'!E2:E10000, '02_Transactions'!A2:A10000<>""),
    SORTBY(
        HSTACK(raw_dates, raw_mvmt),
        raw_dates,
        1
    )
)
```

**Objet :** garantit que les transactions historiques sont traitées par ordre chronologique, quel que soit leur ordre de saisie initial.

</details>

<details>
<summary>Principal courant</summary>

```excel
=SCAN(0, B2#, LAMBDA(prev_bal, curr_mvmt, prev_bal + curr_mvmt))
```

**Objet :** construit le solde de principal courant à partir de la séquence de mouvements normalisée.

</details>

<details>
<summary>Correspondance des taux de marché historiques</summary>

```excel
=MAP(A2#, LAMBDA(d,
    XLOOKUP(
        d,
        '01_Parameters'!$A$13:$A$20,
        '01_Parameters'!$B$13:$B$20,
        0,
        -1
    )
))
```

**Objet :** associe chaque date de transaction au taux de marché effectif applicable.

**Important :** la table des dates d'effet doit être tenue sous forme de grille de taux ordonnée.

</details>

<details>
<summary>Jours par période</summary>

```excel
=LET(
    dates, A2#,
    n, ROWS(dates),
    MAP(SEQUENCE(n), LAMBDA(i,
        IF(
            i = n,
            TODAY() - INDEX(dates, i),
            INDEX(dates, i + 1) - INDEX(dates, i)
        )
    ))
)
```

**Objet :** détermine le nombre de jours représenté par chaque intervalle de calcul.

</details>

<details>
<summary>Intérêts de période</summary>

```excel
=LET(
    principals, C2#,
    rates, D2#,
    days, E2#,
    day_base, '01_Parameters'!$B$4,
    principals * rates * (days / day_base)
)
```

**Objet :** calcule les intérêts de chaque période à partir du capital reconstruit, du taux associé, des jours écoulés et de la base de calcul des jours configurée.

</details>

<details>
<summary>Intérêts courus</summary>

```excel
=SCAN(0, F2#, LAMBDA(prev_int, curr_int, prev_int + curr_int))
```

**Objet :** cumule tous les intérêts de période historiques dans le solde d'intérêts courus actuel.

</details>

<details>
<summary>Total dû courant</summary>

```excel
=C2# + G2#
```

**Objet :** combine le principal courant et les intérêts courus à chaque point de calcul.

</details>

### Règles de validation

| Champ / Zone              | Règle                                                                | Comportement en cas d'erreur                                                      |
| ------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- |
| Identifiant de transaction | Doit identifier de manière unique chaque transaction historique                | Les identifiants en double exigent une vérification                                        |
| Date                      | Doit contenir une date de transaction valide                               | Des dates invalides ou vides peuvent empêcher un traitement chronologique correct |
| Sens                 | Doit correspondre à l'une des définitions de sens configurées              | Un texte non reconnu peut produire un mouvement incorrect                 |
| Montant                    | Le montant de la transaction historique doit être une valeur absolue positive   | Des montants sources négatifs peuvent inverser la convention de signe prévue    |
| Date d'effet            | Doit représenter le début d'une période de taux                       | Des dates incorrectes peuvent appliquer le mauvais taux historique                |
| Taux annuel               | Doit être saisi sous forme de pourcentage annuel                             | Un formatage incorrect modifie le calcul des intérêts               |
| Base de calcul des jours           | La configuration prise en charge est généralement 360 ou 365                     | Une configuration invalide modifie les intérêts de période                       |
| Zone de sortie en tableau dynamique | Doit rester dégagée                                            | Les cellules bloquées produisent `#SPILL!`                                    |
| Mode de calcul          | Excel doit rester en mode de calcul automatique                   | Le mode manuel peut laisser des résultats affichés obsolètes                       |
| Libellés de sens          | Les définitions de paramètres et les sélections de transactions doivent correspondre exactement | Un texte non concordant peut inverser ou annuler le mouvement                    |

La conception source identifie expressément les conflits de débordement des tableaux dynamiques, le mode de calcul manuel, les discordances de libellés de sens et les problèmes de mise en forme comme cas de dépannage opérationnel. 

</details>

## Logique métier et méthodologie

Le modèle repose sur un principe commercial simple : **un solde financier historique est une chronologie, pas seulement un total.**

Plusieurs méthodes se combinent :

* **Normalisation des transactions** convertit différents sens de transaction en une convention de mouvement unique et cohérente. Cela évite qu'un même événement financier soit interprété différemment dans les différentes parties du classeur.
* **Reconstruction du solde courant** montre comment le capital dû a évolué après chaque transaction. Cela rend visibles les remboursements partiels et les avances complémentaires, au lieu de les noyer dans un total cumulé.
* **Calcul des intérêts par période** rattache les intérêts au solde qui existait effectivement pendant chaque période. Le résultat est plus traçable que l'application d'un seul taux à un seul solde de fin de période.
* **Correspondance des taux par date d'effet** permet de faire évoluer les hypothèses de taux de marché au fil du temps. Un nouveau taux peut être introduit sans avoir à reconstruire le grand livre historique des transactions.
* **Séparation du capital et des intérêts** rend le montant de règlement explicable. Le décideur peut distinguer le montant de capital restant dû des intérêts cumulés selon les hypothèses retenues.

Le résultat est un processus de rapprochement pragmatique : reconstruire d'abord la position historique, appliquer ensuite les hypothèses énoncées, et ne présenter le solde actuel qu'une fois la chronologie sous-jacente établie.

## Autres outils de cette série

Des outils légers d'aide à la décision commerciale et financière sont disponibles au sein du projet.

* **Kits de décision d'entreprise** — cadres réutilisables fondés sur Excel pour les questions opérationnelles et financières récurrentes.
* **Outils de planification financière et de rapprochement** — modèles ciblés qui transforment des enregistrements bruts en informations financières prêtes à la décision.
* **Kits de construction et d'exploitation** — classeurs pratiques pour l'estimation, le calcul des coûts, la planification et le contrôle opérationnel.

Consultez le profil GitHub et la collection de produits pour découvrir l'ensemble de la série d'outils.

## Licence

Ce projet est publié sous **Apache License 2.0**.

Consultez le fichier de licence du dépôt pour connaître les conditions générales complètes.

