[ 🌐 عربي ](README.ar.md) | [ 🇳🇱 Nederlands ](README.nl.md) | [ 🇪🇸 Español ](README.sp.md) | [ 🇬🇧 English ](README.md)

# Familielening & Geldstroom-Afstemmingstoolkit: Lopend Saldo & Rentecalculator Excel-sjabloon

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](#license)
[![Platform](https://img.shields.io/badge/Platform-Browser%20%2B%20Excel-green.svg)](#access)
[![Tool Type](https://img.shields.io/badge/Tool%20Type-Financial%20Reconciliation%20Spreadsheet-orange.svg)](#what-it-helps-track)

**Een uitgebreide familielening-tracker en geldstroom-afstemmingsspreadsheet. Reconstrueer jaren aan tweerichtings-geldoverdrachten tussen familieleden tot een traceerbaar lopend hoofdsom-saldo, bereken automatisch opgebouwde rente, en genereer een transparante audit trail voor persoonlijke financiële afspraken.**

> **Probeer de gratis webgebaseerde calculator. Voor gebruikers die permanente financiële administratie, offline audit trails en maandelijks terugkerend account-onderhoud nodig hebben, kunt u het volledig ontgrendelde Excel-sjabloon downloaden met een 30-dagen geld-terug-garantie.**
>
> 🌐 Open in Browser → [Probeer de Gratis Inter-Familie Lening-Tracker Web App (Live Demo)](https://hyvoid.github.io/family-loan-tracker-excel/)
> 
> 📥 Download Sjabloon → [Download het Herbruikbare Excel-sjabloon voor Familielening-Afstemming (Offline Versie)](https://theseusworkshop.com/l/auauhp?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=family-fund-interest-reconciliation)  

## Kernfuncties: Pijnpunten vs. Tracking-oplossingen

In plaats van cumulatieve overdrachten bij te houden die de werkelijke financiële positie niet tonen, zet deze toolkit verspreide bankgegevens om in een gestandaardiseerd aflossingsschema voor leningen.

| Veelvoorkomend Tracking-Pijnpunt (Het Probleem) | Hoe Deze Calculator Het Oplost (De Oplossing) |
| :--- | :--- |
| **Overzicht verloren van historisch uitgeleend vs. terugbetaald geld** | Scheidt historische kasvoorschotten van gedeeltelijke aflossingen in het hele transactiegrootboek. |
| **Rommelige bankafschriften buiten volgorde ingevoerd** | Reconstrueert automatisch het **lopende hoofdsom-saldo** dynamisch, ongeacht de invoervolgorde van gegevens. |
| **Vlakt rente toegepast op veranderende saldi** | Berekent **opgebouwde rente** nauwkeurig over elke uitstaande periode op basis van het exacte dagelijkse saldo. |
| **Schommelende historische inflatie of marktrentes** | Past aanpasbare historische marktrente-schema's toe, waarbij specifieke rentetarieven aan hun exacte effectieve perioden worden gekoppeld. |
| **Onverklaarde lump-sum eindstanden** | Splitst het huidige totale uitstaande bedrag in duidelijk auditeerbare kolommen: **Hoofdsom vs. Opgebouwde Rente**. |
| **Formules handmatig uitbreiden voor nieuwe betalingen** | Breidt de berekeningsdatum automatisch uit naar "Vandaag," waarbij het huidige totale uitstaande bedrag automatisch wordt doorgerold. |

## Snelstart-tutorial: Hoe U Uw Financiële Administratie Reconstrueert

Volg deze workflow om een ongeorganiseerde financiële geschiedenis om te zetten in een schone, auditeerbare balans. 

**Stap 1: Configureer Lening- & Rente-parameters**
Definieer uw financiële basislijn in het Parameters-dashboard. Stel het valutasymbool in, de dag-telling basis (bijv. Actual/365), de samengestelde rente-methode, en breng het historische marktrente-schema in kaart (bijv. afgestemd op de IRS Applicable Federal Rates of aangepaste overeengekomen tarieven).

**Stap 2: Importeer Uw Historische Transactie-Grootboek**
Plak uw ruwe financiële gegevens in de invoertabel. Het systeem vereist slechts basisgegevens: Transactie-ID, Datum, Overdrachtsrichting (Inkomend/Uitgaand), Bedrag, en een korte Memo. U kunt dit direct kopiëren-plakken vanuit uw bank-export CSV's.

**Stap 3: Genereer het Chronologische Saldo-Schema**
Laat de dynamische berekeningsengine de gegevens verwerken. Het sorteert automatisch alle records chronologisch, standaardiseert positieve/negatieve cashflows, herbouwt de dagelijkse lopende hoofdsom, en berekent de exacte opgebouwde rente tussen elke betaalperiode.

**Stap 4: Onderhoud Doorlopende Aflossingsadministratie**
Wanneer nieuwe betalingen worden gedaan, voegt u ze eenvoudig toe onderaan het grootboek. De engine berekent de opgebouwde rente en het totale uitstaande saldo tot de huidige datum direct opnieuw.

👉 **Klaar om een permanente administratie op te bouwen?** [Download het Excel-sjabloon](https://theseusworkshop.com/l/auauhp?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=family-fund-interest-reconciliation) om uw privé financiële gegevens veilig offline op te slaan en de berekeningsengine opnieuw te gebruiken voor doorlopende maandelijkse afstemming.

## Waarom Ik Deze Familiefonds-Afstemmingstool Bouwde

Langlopende familiale financiële afspraken (zoals ouders die een aanbetaling van een kind financieren, of broers/zussen die samen een woning financieren) ontstaan vaak zonder de rigide structuur van een formeel lening-onderhoudssysteem.

Geld beweegt over de jaren in beide richtingen. Gegevens hopen zich op in bankafschriften, WhatsApp-berichten en het geheugen. Uiteindelijk is de moeilijkste vraag niet *"Hoeveel geld bewoog?"* Het is:

**"Wat was het exacte uitstaande saldo op een willekeurige historische datum, en hoeveel rente had tegen dat specifieke saldo moeten zijn opgebouwd?"**

Een eenvoudige `SUM()` van overdrachten in een basis-spreadsheet kan dit niet beantwoorden. Als gegevens meerdere kasvoorschotten bevatten gevolgd door sporadische gedeeltelijke aflossingen, negeert een basis-totaal de *tijdswaarde van geld* en de duur dat elke dollar onbetaald bleef. 

Deze toolkit maakt het financiële redeneerwerk achter complexe boekhouding product. Het zet een decennium aan rommelige, gemengde transacties om in een strikt chronologisch, verdedigbaar berekeningskader.

## Geautomatiseerde Spreadsheet vs. Handmatige Grootboek-boekhouding

| Handmatige Boekhoud-knelpunten (Zonder Tool) | Geautomatiseerde Excel-Afstemming (Met Tool) |
| :--- | :--- |
| **Ongestructureerde Chronologie:** Het berekenen van lopende saldi tegenover ongeordende grootboek-posten veroorzaakt oplopende rekenfouten. | **Geautomatiseerd Sorteren:** De berekeningsengine ordent de volledige transactiegeschiedenis op datum vóór het toepassen van rente-formules. |
| **Inconsistente Cashflow-tekens:** Handmatig bepalen of een overdracht een positieve of negatieve aanpassing is, leidt tot formule-breuken. | **Gestandaardiseerde Cashflows:** Transactierichtingen (Voorschotten vs. Aflossingen) worden geparseerd naar een strikte boekhoudkundige bewegingsconventie. |
| **Statische Rentefouten:** Het toepassen van één vlak rentetarief op een dynamisch meerjarig saldo over- of onderbelast rente. | **Dynamische Periode-Opbouw:** Samengestelde of enkelvoudige rente wordt specifiek berekend over elke afzonderlijke historische uitstaande periode. |
| **Tarief-Onduidelijkheid:** Het gebruik van één gemengd tarief verbergt de realiteit van veranderende macro-economische rentetarieven over een decennium. | **Variabele Tarief-Toewijzing:** Elke transactieperiode wordt automatisch via lookup gekoppeld aan het door de gebruiker gedefinieerde effectieve marktrente-schema. |
| **Data-vermenging:** Hoofdsom en rente mengen in één kolom maakt het uiteindelijke schuldbedrag onmogelijk te auditeren of aan de familie uit te leggen. | **Data-Scheiding:** Hoofdsom-saldi, opgebouwde rente-limieten en totale uitstaande verplichtingen worden in geïsoleerde, transparante kolommen berekend. |

## Doelgroepen & Specifieke Gebruiksscenario's

Deze spreadsheet is ontworpen voor individuen die langetermijn financiële relaties beheren waarbij historische transacties moeten worden teruggerekend naar een wiskundig onderbouwd saldo- en rente-schema. 

**Zoek & Herken Uw Profiel:**
* **Ouders & Voogden:** Het bijhouden van *"Bank van Pap & Mam"* kasvoorschotten, het beheren van persoonlijke lening-aflossingssjablonen voor kinderen met transparante rentevoorwaarden.
* **Executeurs & Boedel-beheerders:** Het afstemmen van historische inter-familie leningen, het documenteren van geërfde schulden, en het genereren van audit trails voor nalatenschap of familietrust-uitkeringen.
* **Family Office Managers:** Het bedienen van een inter-entiteit geldstroom-tracker om informele kapitaalinjecties en opnames te monitoren binnen familiale ondernemingen.
* **Broers/Zussen & Mede-investeerders:** Het onderhouden van een informeel gezamenlijk-investeringsgrootboek om bij te houden wie wat betaalde over jaren van gedeeld eigendom of zakelijke ondernemingen.
* **Persoonlijke Financiën Doe-Het-Zelvers:** Iedereen die een robuust alternatief nodig heeft voor complexe boekhoudsoftware (zoals QuickBooks) om langetermijn peer-to-peer (P2P) leen-grootboeken te vereffenen.

*(Noot: Deze toolkit biedt besluitvormings-ondersteunende berekeningen. Het vervangt geen gecertificeerde openbare accountantsdienst (CPA), formele juridische leendocumentatie, of belastingnalevings-advies.)*

## Over de Architectuur

Ik bouw lichtgewicht operationele trackers en besluitvormings-sjablonen voor omgevingen met te veel bewegende delen voor hoofdrekenen, maar zonder de complexiteit die enterprise ERP-software rechtvaardigt. 

De kernontwerp-filosofie is eenvoudig: **Informatie moet chronologisch worden gestructureerd om de volgende financiële beslissing met vertrouwen te nemen.** 

Deze toolkit verwerpt generieke boekhouding. Het is een nauw gerichte engine, uitsluitend ontworpen voor het reconstrueren van tijdlijnen, het in kaart brengen van variabele rentetarieven, en het aantonen van de exacte huidige uitstaande positie van privéfondsen.

## Technische Details

<details>
<summary>Voor technische reviewers, Excel-beoefenaars en samenwerkers</summary>

### Werkmap-architectuur

De werkmap gebruikt vijf bladen verdeeld over vier functionele lagen:

| Blad             | Rol                                                                                                  | Invoer / Uitvoer                     |
| ----------------- | ----------------------------------------------------------------------------------------------------- | ---------------------------------- |
| `00_Instructions` | Systeeminstructies, versie-informatie en bedieningsrichtlijnen                                      | Statisch                             |
| `01_Parameters`   | Globale aannames, richtingsdefinities, dag-telling basis, rente-methode en marktrente-schema | Handmatige invoer                       |
| `02_Transactions` | Historisch tweerichtings geldstroom-grootboek                                                               | Handmatige invoer + dynamische berekening |
| `03_CalcEngine`   | Chronologische reconstructie, lopende hoofdsom, tarief-koppeling, dagtellingen en rente-engine       | Formule-gestuurd                     |
| `04_Summary`      | Huidig uitstaand saldo en hoofdsom/rente-uitsplitsing                                          | Formule-gestuurd                     |

De kerngegevensstroom is:

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

De berekeningsengine voert vier hoofdbewerkingen uit:

1. Sorteer historische transacties chronologisch.
2. Converteer elke transactie naar een gestandaardiseerde ondertekende beweging.
3. Reconstrueer de lopende hoofdsom en koppel de toepasselijke marktrente.
4. Bereken periode-rente en opgebouwde uitstaande rente.

De samenvatting haalt vervolgens de meest recente hoofdsom- en opgebouwde rente-resultaten op om de huidige uitstaande positie te presenteren. De bronarchitectuur definieert expliciet de transactie-naar-engine-naar-samenvatting afhankelijkheidsketen.  

### Drie Vallen Die Zelfs Ervaren Financiële Administrateurs Vangen

#### Val 1 — Cumulatieve overdrachten behandelen als het volledige antwoord

**1. Er werd een beslissing genomen:**
Bepaal het momenteel uitstaande bedrag door het totale aflossingen af te trekken van de totale voorschotten.

**2. Het niet-opgemerkte gebrek:**
Dit stelt de netto hoofdsom vast maar zegt niets over hoe lang verschillende saldi uitstonden.

**3. Waarom dit het resultaat verandert:**
Rente hangt af van zowel hoofdsom als verstreken tijd.

**4. Waarom het redeneerwerk onvolledig is:**
Een $10,000 saldo dat jaren uitstond is economisch verschillend van een $10,000 saldo dat recent verscheen.

**5. Gecorrigeerde aanpak:**
Reconstrueer de lopende hoofdsom na elke transactie en bereken elk interval afzonderlijk.

**6. Gecorrigeerd resultaat:**
Het huidige resultaat bevat zowel de resterende hoofdsom als de opgebouwde rente toegeschreven aan de historische perioden.

<details>
<summary>Formule-logica</summary>

```excel
=SCAN(0, B2#, LAMBDA(prev_bal, curr_mvmt, prev_bal + curr_mvmt))
```

Dit creëert een lopend hoofdsom-saldo van de gestandaardiseerde transactie-bewegingsvector.

</details>

#### Val 2 — Eén rentetarief toepassen op de gehele geschiedenis

**1. Er werd een beslissing genomen:**
Pas het huidige veronderstelde marktrente toe op het gehele historische saldo.

**2. Het niet-opgemerkte gebrek:**
Het toepasselijke tarief kan zijn veranderd tijdens de historische periode.

**3. Waarom dit het resultaat verandert:**
Verschillende perioden kunnen verschillende jaarlijkse tarieven hebben.

**4. Waarom het redeneerwerk onjuist is:**
Een huidig tarief vertegenwoordigt niet automatisch elke historische periode.

**5. Gecorrigeerde aanpak:**
Onderhoud een effectieve-datum tariefschema en koppel elke transactiedatum aan de toepasselijke historische rente.

**6. Gecorrigeerd resultaat:**
Elke periode wordt berekend met het tarief dat effectief is gedefinieerd op dat punt in de tijdlijn.

<details>
<summary>Formule-logica</summary>

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

De `-1` match-modus haalt de exacte effectieve datum of de volgende kleinere effectieve datum op.

</details>

#### Val 3 — Rente berekenen zonder de tijdsintervallen te reconstrueren

**1. Er werd een beslissing genomen:**
Bereken rente van één transactiedatum tot een vaste afwikkelingsdatum.

**2. Het niet-opgemerkte gebrek:**
Latere transacties kunnen de uitstaande hoofdsom tijdens die periode hebben gewijzigd.

**3. Waarom dit het resultaat verandert:**
Rente moet het saldo weerspiegelen dat van toepassing is tijdens elk interval.

**4. Waarom het redeneerwerk onjuist is:**
Eén datum-tot-datum berekening negeert veranderingen in hoofdsom tussen transacties.

**5. Gecorrigeerde aanpak:**
Bereken het aantal dagen van elke transactie tot de volgende transactie, waarbij vandaag als eindpunt wordt gebruikt voor de laatste open periode.

**6. Gecorrigeerd resultaat:**
Rente volgt het gereconstrueerde historische saldo in plaats van een verondersteld statisch bedrag.

<details>
<summary>Formule-logica</summary>

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

De laatste transactie blijft rente opbouwen tot de huidige datum.

</details>

### Voorbeeldscenario

Beschouw een vereenvoudigde historische reeks:

| Datum       | Richting |  Bedrag |
| ---------- | --------- | ------: |
| 2020-01-15 | Voorschot   | $20,000 |
| 2020-09-01 | Voorschot   | $10,000 |
| 2021-06-15 | Aflossing |  $8,000 |
| 2022-03-01 | Aflossing |  $5,000 |

De gestandaardiseerde beweging wordt:

```text
2020-01-15    +20,000
2020-09-01    +10,000
2021-06-15     -8,000
2022-03-01     -5,000
```

De lopende hoofdsom wordt daarom:

```text
After 2020-01-15    $20,000
After 2020-09-01    $30,000
After 2021-06-15    $22,000
After 2022-03-01    $17,000
```

De belangrijke analytische verandering is dat rente niet wordt berekend tegen $17,000 voor de gehele historische periode.

In plaats daarvan herkent de engine verschillende saldo-intervallen:

```text
$20,000  →  until 2020-09-01
$30,000  →  until 2021-06-15
$22,000  →  until 2022-03-01
$17,000  →  from 2022-03-01 → today
```

Als het marktrente-schema tussen deze datums verandert, wordt het tarief dat op elk interval van toepassing is bepaald uit de effectieve-datum tabel.

De resulterende uitvoer scheidt:

```text
Net Outstanding Principal
+ Accrued Interest
----------------------
Current Total Outstanding
```

Dit maakt het uiteindelijke getal verklaarbaar: het kan worden teruggevoerd naar de transactiereeks, saldo-intervallen, rente-aannames en verstreken dagen in plaats van een handmatig ingevoerd afwikkelingscijfer.

### Formule-referentie

<details>
<summary>Transactierichting → Netto Beweging</summary>

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

**Doel:** Converteert transactierichtingen naar een gestandaardiseerde ondertekende beweging.

**Logica:** De geconfigureerde voorschot/uitstroom-richting wordt positief; de geconfigureerde aflossing/instroom-richting wordt negatief.

</details>

<details>
<summary>Chronologische Transactie-sortering</summary>

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

**Doel:** Zorgt dat historische transacties chronologisch worden verwerkt ongeacht hun oorspronkelijke invoervolgorde.

</details>

<details>
<summary>Lopende Hoofdsom</summary>

```excel
=SCAN(0, B2#, LAMBDA(prev_bal, curr_mvmt, prev_bal + curr_mvmt))
```

**Doel:** Bouwt het lopende hoofdsom-saldo van de gestandaardiseerde bewegingsreeks.

</details>

<details>
<summary>Historische Marktrente-koppeling</summary>

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

**Doel:** Koppelt elke transactiedatum aan de toepasselijke effectieve marktrente.

**Belangrijk:** De effectieve-datum tabel moet worden onderhouden als een geordend tariefschema.

</details>

<details>
<summary>Periodedagen</summary>

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

**Doel:** Bepaalt het aantal dagen dat door elk berekeningsinterval wordt vertegenwoordigd.

</details>

<details>
<summary>Periode-rente</summary>

```excel
=LET(
    principals, C2#,
    rates, D2#,
    days, E2#,
    day_base, '01_Parameters'!$B$4,
    principals * rates * (days / day_base)
)
```

**Doel:** Berekent rente voor elke periode met de gereconstrueerde hoofdsom, gekoppeld tarief, verstreken dagen en geconfigureerde dag-telling basis.

</details>

<details>
<summary>Opgebouwde Rente</summary>

```excel
=SCAN(0, F2#, LAMBDA(prev_int, curr_int, prev_int + curr_int))
```

**Doel:** Accumuleert alle historische periode-rente in het huidige opgebouwde rente-saldo.

</details>

<details>
<summary>Totaal Lopend Uitstaand</summary>

```excel
=C2# + G2#
```

**Doel:** Combineert lopende hoofdsom en opgebouwde rente op elk berekeningspunt.

</details>

### Validatieregels

| Veld / Gebied              | Regel                                                                | Foutgedrag                                                      |
| ------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- |
| Transactie-ID            | Moet elke historische transactie uniek identificeren                | Dubbele ID's vereisen beoordeling                                        |
| Datum                      | Moet een geldige transactiedatum bevatten                               | Ongeldige of lege datums kunnen correcte chronologische verwerking verhinderen |
| Richting                 | Moet overeenkomen met een van de geconfigureerde richtingsdefinities              | Niet-herkende tekst kan een onjuiste beweging opleveren                 |
| Bedrag                    | Het historische transactiebedrag moet een positieve absolute waarde zijn   | Negatieve bronbedragen kunnen de beoogde tekenconventie omkeren    |
| Effectieve Datum            | Moet het begin van een tariefperiode vertegenwoordigen                       | Onjuiste datums kunnen het verkeerde historische tarief toewijzen                |
| Jaarlijks Tarief               | Moet worden ingevoerd als een jaarlijks percentage                             | Onjuiste opmaak wijzigt de renteberekening               |
| Dag-telling basis           | Ondersteunde configuratie is doorgaans 360 of 365                     | Ongeldige configuratie wijzigt periode-rente                       |
| Dynamisch-array uitvoergebied | Moet onbelemmerd blijven                                            | Blokkerende cellen produceren `#SPILL!`                                    |
| Berekeningsmodus          | Excel moet in Automatische berekeningsmodus blijven                   | Handmatige modus kan weergegeven resultaten verouderd laten                       |
| Richtingslabels          | Parameterdefinities en transactieselecties moeten exact overeenkomen | Niet-overeenkomende tekst kan beweging omkeren of op nul zetten                    |

Het bronontwerp identificeert specifiek dynamisch-array spill-conflicten, handmatige berekeningsmodus, richtingslabel-mismatches en opmaakproblemen als operationele probleemgevallen. 

</details>

## De Bedrijfslogica & Methodologie

Het model is gebouwd rond een eenvoudig commercieel principe: **een historisch financieel saldo is een tijdlijn, niet zomaar een totaal.**

Verschillende methoden werken samen:

* **Transactie-normalisatie** zet verschillende transactierichtingen om in één consistente bewegingsconventie. Dit voorkomt dat hetzelfde financiële gebeuren verschillend wordt geïnterpreteerd in verschillende delen van de werkmap.
* **Lopend-saldo reconstructie** toont hoe de uitstaande hoofdsom na elke transactie veranderde. Dit maakt gedeeltelijke aflossingen en aanvullende voorschotten zichtbaar in plaats van ze te begraven in een cumulatief totaal.
* **Periode-gebaseerde renteberekening** koppelt rente aan het saldo dat daadwerkelijk bestond tijdens elke periode. Het resultaat is beter traceerbaar dan het toepassen van één tarief op één eind-van-periode saldo.
* **Effectieve-datum tarief-koppeling** staat toe dat historische marktrente-aannames in de loop van de tijd veranderen. Een nieuw tarief kan worden geïntroduceerd zonder het historische transactiegrootboek opnieuw op te bouwen.
* **Hoofdsom-en-rente scheiding** maakt het afwikkelingscijfer verklaarbaar. De besluitvormer kan het nog uitstaande hoofdsombedrag onderscheiden van de rente die is opgebouwd onder de geselecteerde aannames.

Het resultaat is een praktische afstemmings-workflow: reconstrueer eerst de historische positie, pas daarna de gestelde aannames toe, en presenteer het huidige saldo pas nadat de onderliggende tijdlijn is vastgesteld.

## Andere Tools in Deze Reeks

Gerelateerde lichtgewicht zakelijke en financiële besluitvormings-ondersteunende tools zijn beschikbaar in de projectcollectie.

* **Zakelijke Besluitvormings-toolkits** — herbruikbare op Excel gebaseerde kaders voor terugkerende operationele en financiële vragen.
* **Financiële Planning & Afstemmingstools** — gefocuste modellen om ruwe gegevens om te zetten in besluitklare financiële informatie.
* **Bouw- & Operations-toolkits** — praktische werkmappen voor schatten, kostprijsbepaling, planning en operationele controle.

Zie het GitHub-profiel en de productcollectie voor de bredere toolkit-reeks.

## Licentie

Dit project wordt uitgebracht onder de **Apache License 2.0**.

Zie het licentiebestand van de repository voor de volledige voorwaarden en bepalingen.
