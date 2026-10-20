[ 🌐 عربي ](README.ar.md) | [ 🇩🇪 Deutsch ](README.de.md) | [ 🇫🇷 Français ](README.fr.md) | [ 🇳🇱 Nederlands ](README.nl.md) | [ 🇪🇸 Español ](README.sp.md) | [ 🇬🇧 English ](README.md)
# Toolkit für Familienkredit- & Geldfluss-Abstimmung: Excel-Vorlage für laufenden Saldo und Zinsrechner

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](#license)
[![Platform](https://img.shields.io/badge/Platform-Browser%20%2B%20Excel-green.svg)](#access)
[![Tool Type](https://img.shields.io/badge/Tool%20Type-Financial%20Reconciliation%20Spreadsheet-orange.svg)](#what-it-helps-track)

**Ein umfassendes Tabellenblatt zur Nachverfolgung von Familienkrediten und Abstimmung von Geldflüssen. Rekonstruieren Sie Jahre zweiseitiger Geldüberweisungen innerhalb der Familie in einen nachvollziehbaren laufenden Kapitalsaldo, berechnen Sie automatisch aufgelaufene Zinsen und erzeugen Sie einen transparenten Prüfpfad für private Finanzvereinbarungen.**

> **Probieren Sie den kostenlosen webbasierten Rechner. Für Nutzer, die dauerhafte Finanzaufzeichnungen, Offline-Prüfpfade und wiederkehrende monatliche Kontobetreuung benötigen, können Sie die vollständig freigeschaltete Excel-Vorlage mit 30-tägiger Geld-zurück-Garantie herunterladen.**
>
> 🌐 Im Browser öffnen → [Kostenlose Web-App für die Nachverfolgung von Familienkrediten ausprobieren (Live-Demo)](https://hyvoid.github.io/family-loan-tracker-excel/)
> 
> 📥 Vorlage herunterladen → [Die wiederverwendbare Excel-Vorlage für die Abstimmung von Familienkrediten herunterladen (Offline-Version)](https://theseusworkshop.com/l/auauhp?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=family-fund-interest-reconciliation)  

## Kernfunktionen: Schmerzpunkte vs. Nachverfolgungslösungen

Anstatt kumulative Überweisungen zu verfolgen, die die tatsächliche Finanzlage nicht zeigen, wandelt dieses Toolkit verstreute Bankaufzeichnungen in einen standardisierten Tilgungsplan um.

| Häufiger Nachverfolgungs-Schmerzpunkt (Das Problem) | Wie dieser Rechner es löst (Die Lösung) |
| :--- | :--- |
| **Den Überblick über historisch verliehenes vs. zurückgezahltes Geld verloren** | Trennt historische Barvorschüsse von Teilrückzahlungen über das gesamte Transaktionsregister. |
| **Unordentliche, außer der Reihenfolge eingegebene Kontoauszüge** | Rekonstruiert den **laufenden Kapitalsaldo** automatisch dynamisch, unabhängig von der Eingabereihenfolge. |
| **Pauschale Verzinsung wechselnder Salden** | Berechnet **aufgelaufene Zinsen** präzise über jede offene Periode auf Basis des exakten Tagessaldos. |
| **Schwankende historische Inflations- oder Marktzinssätze** | Wendet anpassbare historische Marktzinspläne an und ordnet bestimmte Zinssätze ihren exakten Geltungszeiträumen zu. |
| **Unerklärliche Pauschalendsalden** | Teilt den aktuellen offenen Gesamtbetrag in deutlich prüfbare Spalten auf: **Kapital vs. aufgelaufene Zinsen**. |
| **Manuelles Erweitern von Formeln für neue Zahlungen** | Verlängert das Berechnungsdatum automatisch bis „Heute“ und überträgt den aktuellen offenen Gesamtbetrag automatisch. |

## Schnellstart-Tutorial: So rekonstruieren Sie Ihre Finanzaufzeichnungen

Folgen Sie diesem Ablauf, um eine unorganisierte Finanzhistorie in eine saubere, prüfbare Bilanz zu verwandeln. 

**Schritt 1: Kredit- und Zinsparameter konfigurieren**
Definieren Sie Ihre finanzielle Baseline im Parameter-Dashboard. Legen Sie das Währungssymbol, die Tagezählbasis (z. B. Actual/365), die Zinseszins-Methode fest und erfassen Sie den historischen Marktzinsplan (z. B. passend zu den IRS Applicable Federal Rates oder individuell vereinbarten Sätzen).

**Schritt 2: Ihr historisches Transaktionsregister importieren**
Fügen Sie Ihre Rohfinanzdaten in die Eingabetabelle ein. Das System benötigt nur grundlegende Datenpunkte: Transaktions-ID, Datum, Überweisungsrichtung (Zufluss/Abfluss), Betrag und ein kurzes Memo. Sie können diese direkt aus Ihren Bankexport-CSV-Dateien kopieren.

**Schritt 3: Den chronologischen Saldenplan erzeugen**
Lassen Sie die dynamische Berechnungs-Engine die Daten verarbeiten. Sie sortiert automatisch alle Datensätze chronologisch, standardisiert positive/negative Cashflows, baut den laufenden Tagessaldo wieder auf und berechnet die exakt aufgelaufenen Zinsen zwischen jeder Zahlungsperiode.

**Schritt 4: Laufende Rückzahlungsaufzeichnungen pflegen**
Wenn neue Zahlungen erfolgen, hängen Sie sie einfach unten an das Register an. Die Engine berechnet die aufgelaufenen Zinsen und den offenen Gesamtsaldo sofort bis zum aktuellen Datum neu.

👉 **Bereit, ein dauerhaftes Register aufzubauen?** [Laden Sie die Excel-Vorlage herunter](https://theseusworkshop.com/l/auauhp?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=family-fund-interest-reconciliation), um Ihre privaten Finanzdaten sicher offline zu speichern und die Berechnungs-Engine für die laufende monatliche Abstimmung wiederzuverwenden.

## Warum ich dieses Toolkit für die Abstimmung von Familiengeldern gebaut habe

Langjährige finanzielle Arrangements innerhalb der Familie (wie Eltern, die die Anzahlung eines Kindes finanzieren, oder Geschwister, die eine Immobilie gemeinsam finanzieren) entstehen oft ohne die starre Struktur eines formalen Kreditverwaltungssystems.

Geld fließt über die Jahre in beide Richtungen. Aufzeichnungen sammeln sich über Kontoauszüge, WhatsApp-Nachrichten und das Gedächtnis an. Letztlich ist die schwierigste Frage nicht *„Wie viel Geld floss?“*. Sie ist:

**„Wie hoch war der exakte offene Saldo an einem bestimmten historischen Datum, und wie viele Zinsen hätten gegen diesen spezifischen Saldo auflaufen müssen?“**

Ein einfaches `SUM()` der Überweisungen in einem einfachen Tabellenblatt kann dies nicht beantworten. Wenn die Aufzeichnungen mehrere Barvorschüsse gefolgt von sporadischen Teilrückzahlungen enthalten, ignoriert eine einfache Summe den *Zeitwert des Geldes* und die Dauer, in der jeder Dollar unbezahlt blieb. 

Dieses Toolkit produktisiert die finanzielle Denkweise hinter komplexer Buchhaltung. Es verwandelt ein Jahrzehnt unordentlicher, gemischter Transaktionen in einen streng chronologischen, vertretbaren Berechnungsrahmen.

## Automatisiertes Tabellenblatt vs. manuelle Hauptbuchbuchhaltung

| Manuelle Buchhaltungshürden (ohne Tool) | Automatisierte Excel-Abstimmung (mit Tool) |
| :--- | :--- |
| **Unorganisierte Chronologie:** Die Berechnung laufender Salden gegen außer der Reihenfolge stehende Registereinträge verursacht sich fortsetzende Rechenfehler. | **Automatische Sortierung:** Die Berechnungs-Engine ordnet die vollständige Transaktionshistorie nach Datum neu, bevor Zinsformeln angewendet werden. |
| **Inkonsistente Cashflow-Vorzeichen:** Die manuelle Entscheidung, ob eine Überweisung eine positive oder negative Anpassung ist, führt zu Formelbrüchen. | **Standardisierte Cashflows:** Überweisungsrichtungen (Vorschüsse vs. Rückzahlungen) werden in eine strenge buchhalterische Bewegungskonvention geparst. |
| **Statische Zinsfehler:** Die Anwendung eines einzigen pauschalen Zinssatzes auf einen dynamischen mehrjährigen Saldo über- oder unterverzinst. | **Dynamische Periodenaufzinsung:** Zinseszins oder einfache Zinsen werden spezifisch über jede einzelne historische offene Periode berechnet. |
| **Intransparenz der Zinssätze:** Die Verwendung eines einzigen Mischsatzes verschleiert die Realität sich über ein Jahrzehnt ändernder makroökonomischer Zinssätze. | **Variable Zinssatzzuordnung:** Jede Transaktionsperiode wird automatisch per Nachschlagen dem nutzerdefinierten Geltigkeits-Marktzinsplan zugeordnet. |
| **Datenvermischung:** Das Mischen von Kapital und Zinsen in einer Spalte macht die endgültige Schuldzahl unprüfbar oder der Familie nicht erklärbar. | **Datentrennung:** Kapitalsalden, Grenzen aufgelaufener Zinsen und offene Gesamtverbindlichkeiten werden in isolierten, transparenten Spalten berechnet. |

## Zielnutzer & konkrete Anwendungsfälle

Dieses Tabellenblatt wurde für Personen entwickelt, die langfristige finanzielle Beziehungen verwalten, in denen historische Transaktionen in einen mathematisch fundierten Salden- und Zinsplan zurückentwickelt werden müssen. 

**Finden Sie Ihre Persona:**

* **Eltern & Erziehungsberechtigte:** Nachverfolgung der Barvorschüsse der *„Bank of Mom & Dad“*, Verwaltung privater Kreditrückzahlungsvorlagen für Kinder mit transparenten Zinsbedingungen.
* **Testamentsvollstrecker & Nachlassverwalter:** Abstimmung historischer Kredite innerhalb der Familie, Dokumentation geerbter Schulden und Erzeugung von Prüfpfaden für Nachlassverfahren oder Familien-Trust-Ausschüttungen.
* **Family-Office-Manager:** Betrieb eines Geldfluss-Trackers zwischen Einheiten zur Überwachung informeller Kapitaleinlagen und -abhebungen über familieneigene Unternehmen hinweg.
* **Geschwister & Co-Investoren:** Pflege eines informellen gemeinsamen Investitionsregisters, um über Jahre gemeinsamer Immobilienbesitzung oder gemeinsamer Geschäftsunternehmen nachzuverfolgen, wer wofür bezahlt hat.
* **Privatfinanz-Bastler:** Jeder, der eine robuste Alternative zu komplexer Buchhaltungssoftware (wie QuickBooks) benötigt, um langfristige Peer-to-Peer-Kreditregister (P2P) abzurechnen.

*(Hinweis: Dieses Toolkit bietet entscheidungsunterstützende Berechnungen. Es ersetzt keine zertifizierte Wirtschaftsprüfung (CPA), keine formale rechtliche Kreditdokumentation und keine steuerliche Beratung.)*

## Über die Architektur

Ich baue leichtgewichtige operative Tracker und entscheidungsunterstützende Vorlagen für Umgebungen, die zu viele bewegliche Teile für Kopfrechnen haben, aber nicht die Komplexität, die eine Unternehmens-ERP-Software rechtfertigen würde. 

Die zentrale Designphilosophie ist einfach: **Informationen müssen chronologisch strukturiert sein, damit die nächste finanzielle Entscheidung sicher getroffen werden kann.** 

Dieses Toolkit lehnt generische Buchhaltung ab. Es ist eine eng fokussierte Engine, die ausschließlich für die Rekonstruktion von Zeitlinien, die Zuordnung variabler Zinssätze und den Nachweis der exakten aktuellen offenen Position privater Gelder entwickelt wurde.

## Technische Details

<details>
<summary>Für technische Prüfer, Excel-Praktiker und Mitwirkende</summary>

### Architektur der Arbeitsmappe

Die Arbeitsmappe verwendet fünf Blätter über vier funktionale Schichten:

| Blatt             | Rolle                                                                                                  | Eingabe / Ausgabe                     |
| ----------------- | ----------------------------------------------------------------------------------------------------- | ---------------------------------- |
| `00_Instructions` | Systemanweisungen, Versionsinformationen und Betriebsanleitung                                      | Statisch                             |
| `01_Parameters`   | Globale Annahmen, Richtungsdefinitionen, Tagezählbasis, Zinsmethode und Marktzinsplan | Manuelle Eingabe                       |
| `02_Transactions` | Historisches Register zweiseitiger Geldbewegungen                                                               | Manuelle Eingabe + dynamische Berechnung |
| `03_CalcEngine`   | Chronologische Rekonstruktion, laufendes Kapital, Zinssatzzuordnung, Tagezählungen und Zins-Engine       | Formelgesteuert                     |
| `04_Summary`      | Aktueller offener Saldo und Kapital-/Zinsaufschlüsselung                                              | Formelgesteuert                     |

Der zentrale Datenfluss ist:

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

Die Berechnungs-Engine führt vier Hauptoperationen durch:

1. Historische Transaktionen chronologisch sortieren.
2. Jede Transaktion in eine standardisierte vorzeichenbehaftete Bewegung umwandeln.
3. Das laufende Kapital rekonstruieren und den anwendbaren Marktzins zuordnen.
4. Periodenzinsen und aufgelaufene offene Zinsen berechnen.

Die Zusammenfassung extrahiert dann die neuesten Kapital- und Zinsaufzinsungsergebnisse, um die aktuelle offene Position darzustellen. Die Quellarchitektur definiert explizit die Abhängigkeitskette Transaktion-zu-Engine-zu-Zusammenfassung.  

### Drei Fallen, die selbst erfahrene Finanzaufzeichner fangen

#### Falle 1 — Kumulative Überweisungen als die ganze Antwort behandeln

**1. Eine Entscheidung wurde getroffen:**
Den aktuell offenen Betrag bestimmen, indem Gesamtrückzahlungen von Gesamtvorschüssen abgezogen werden.

**2. Der unbemerkte Fehler:**
Dies legt das Nettokapital fest, sagt aber nichts darüber aus, wie lange verschiedene Salden offen blieben.

**3. Warum es das Ergebnis ändert:**
Zinsen hängen sowohl vom Kapital als auch von der verstrichenen Zeit ab.

**4. Warum die Begründung unvollständig ist:**
Ein 10.000-$-Saldo, der mehrere Jahre offen ist, ist wirtschaftlich etwas anderes als ein 10.000-$-Saldo, der kürzlich entstand.

**5. Korrigierter Ansatz:**
Das laufende Kapital nach jeder Transaktion rekonstruieren und jedes Intervall separat berechnen.

**6. Korrigiertes Ergebnis:**
Das aktuelle Ergebnis enthält sowohl das verbleibende Kapital als auch die den historischen Perioden zurechenbaren aufgelaufenen Zinsen.

<details>
<summary>Formellogik</summary>

```excel
=SCAN(0, B2#, LAMBDA(prev_bal, curr_mvmt, prev_bal + curr_mvmt))
```

Dies erzeugt einen laufenden Kapitalsaldo aus dem standardisierten Transaktionsbewegungsvektor.

</details>

#### Falle 2 — Einen Zinssatz auf die gesamte Historie anwenden

**1. Eine Entscheidung wurde getroffen:**
Den heutigen angenommenen Marktzins auf den gesamten historischen Saldo anwenden.

**2. Der unbemerkte Fehler:**
Der anwendbare Zinssatz kann sich während der historischen Periode geändert haben.

**3. Warum es das Ergebnis ändert:**
Verschiedene Perioden können verschiedene Jahreszinssätze tragen.

**4. Warum die Begründung falsch ist:**
Ein aktueller Zinssatz repräsentiert nicht automatisch jede historische Periode.

**5. Korrigierter Ansatz:**
Einen Gültigkeitsdatum-Zinsplan pflegen und jedes Transaktionsdatum gegen den anwendbaren historischen Zinssatz abgleichen.

**6. Korrigiertes Ergebnis:**
Jede Periode wird mit dem Zinssatz berechnet, der zu diesem Zeitpunkt der Zeitlinie als gültig definiert war.

<details>
<summary>Formellogik</summary>

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

Der `-1`-Übereinstimmungsmodus ruft das exakte Gültigkeitsdatum oder das nächstkleinere Gültigkeitsdatum ab.

</details>

#### Falle 3 — Zinsen berechnen, ohne die Zeitintervalle zu rekonstruieren

**1. Eine Entscheidung wurde getroffen:**
Zinsen von einem Transaktionsdatum bis zu einem festen Abrechnungsdatum berechnen.

**2. Der unbemerkte Fehler:**
Nachfolgende Transaktionen können das offene Kapital während dieser Periode geändert haben.

**3. Warum es das Ergebnis ändert:**
Zinsen sollten den Saldo widerspiegeln, der während jedes Intervalls tatsächlich bestand.

**4. Warum die Begründung falsch ist:**
Eine einzelne Datum-zu-Datum-Berechnung ignoriert Kapitaländerungen zwischen Transaktionen.

**5. Korrigierter Ansatz:**
Die Anzahl der Tage von jeder Transaktion zur nächsten Transaktion berechnen, wobei heute als Endpunkt für die letzte offene Periode dient.

**6. Korrigiertes Ergebnis:**
Zinsen folgen dem rekonstruierten historischen Saldo statt eines angenommenen statischen Betrags.

<details>
<summary>Formellogik</summary>

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

Die letzte Transaktion läuft weiter bis zum aktuellen Datum zinslich auf.

</details>

### Beispielszenario

Betrachten Sie eine vereinfachte historische Sequenz:

| Datum       | Richtung |  Betrag |
| ---------- | --------- | ------: |
| 2020-01-15 | Vorschuss   | 20.000 $ |
| 2020-09-01 | Vorschuss   | 10.000 $ |
| 2021-06-15 | Rückzahlung |  8.000 $ |
| 2022-03-01 | Rückzahlung |  5.000 $ |

Die standardisierte Bewegung wird:

```text
2020-01-15    +20,000
2020-09-01    +10,000
2021-06-15     -8,000
2022-03-01     -5,000
```

Das laufende Kapital wird daher:

```text
After 2020-01-15    $20,000
After 2020-09-01    $30,000
After 2021-06-15    $22,000
After 2022-03-01    $17,000
```

Die wichtige analytische Änderung ist, dass Zinsen nicht gegen 17.000 $ über die gesamte historische Periode berechnet werden.

Stattdessen erkennt die Engine verschiedene Saldenintervalle:

```text
$20,000  →  until 2020-09-01
$30,000  →  until 2021-06-15
$22,000  →  until 2022-03-01
$17,000  →  from 2022-03-01 → today
```

Wenn sich der Marktzinsplan zwischen diesen Daten ändert, wird der für jedes Intervall anwendbare Zinssatz aus der Gültigkeitsdatumstabelle bestimmt.

Die resultierende Ausgabe trennt:

```text
Net Outstanding Principal
+ Accrued Interest
----------------------
Current Total Outstanding
```

Das macht die endgültige Zahl erklärbar: Sie kann auf die Transaktionssequenz, die Saldenintervalle, die Zinsannahmen und die verstrichenen Tage zurückverfolgt werden, statt eine manuell eingegebene Abrechnungszahl zu sein.

### Formelreferenz

<details>
<summary>Überweisungsrichtung → Nettobewegung</summary>

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

**Zweck:** Wandelt Überweisungsrichtungen in eine standardisierte vorzeichenbehaftete Bewegung um.

**Logik:** Die konfigurierte Vorschuss-/Abflussrichtung wird positiv; die konfigurierte Rückzahlungs-/Zuflussrichtung wird negativ.

</details>

<details>
<summary>Chronologische Transaktionssortierung</summary>

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

**Zweck:** Stellt sicher, dass historische Transaktionen unabhängig von ihrer ursprünglichen Eingabereihenfolge chronologisch verarbeitet werden.

</details>

<details>
<summary>Laufendes Kapital</summary>

```excel
=SCAN(0, B2#, LAMBDA(prev_bal, curr_mvmt, prev_bal + curr_mvmt))
```

**Zweck:** Baut den laufenden Kapitalsaldo aus der standardisierten Bewegungssequenz auf.

</details>

<details>
<summary>Zuordnung historischer Marktzinssätze</summary>

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

**Zweck:** Ordnet jedes Transaktionsdatum dem anwendbaren gültigen Marktzins zu.

**Wichtig:** Die Gültigkeitsdatumstabelle muss als geordneter Zinsplan gepflegt werden.

</details>

<details>
<summary>Periodentage</summary>

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

**Zweck:** Bestimmt die Anzahl der Tage, die jedes Berechnungsintervall darstellt.

</details>

<details>
<summary>Periodenzinsen</summary>

```excel
=LET(
    principals, C2#,
    rates, D2#,
    days, E2#,
    day_base, '01_Parameters'!$B$4,
    principals * rates * (days / day_base)
)
```

**Zweck:** Berechnet Zinsen für jede Periode mit dem rekonstruierten Kapital, dem zugeordneten Zinssatz, den verstrichenen Tagen und der konfigurierten Tagezählbasis.

</details>

<details>
<summary>Aufgelaufene Zinsen</summary>

```excel
=SCAN(0, F2#, LAMBDA(prev_int, curr_int, prev_int + curr_int))
```

**Zweck:** Kumuliert alle historischen Periodenzinsen in den aktuellen Aufzinsungssaldo.

</details>

<details>
<summary>Gesamter laufender offener Betrag</summary>

```excel
=C2# + G2#
```

**Zweck:** Kombiniert laufendes Kapital und aufgelaufene Zinsen an jedem Berechnungspunkt.

</details>

### Validierungsregeln

| Feld / Bereich              | Regel                                                                | Fehlerverhalten                                                      |
| ------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- |
| Transaktions-ID            | Soll jede historische Transaktion eindeutig identifizieren                | Doppelte IDs erfordern Prüfung                                        |
| Datum                      | Muss ein gültiges Transaktionsdatum enthalten                               | Ungültige oder leere Daten können die korrekte chronologische Verarbeitung verhindern |
| Richtung                 | Muss einer der konfigurierten Richtungsdefinitionen entsprechen              | Unbekannter Text kann eine falsche Bewegung erzeugen                 |
| Betrag                    | Der historische Transaktionsbetrag sollte ein positiver Absolutwert sein   | Negative Quellbeträge können die beabsichtigte Vorzeichenkonvention umkehren    |
| Gültigkeitsdatum            | Muss den Beginn einer Zinsperiode darstellen                       | Falsche Daten können den falschen historischen Zinssatz zuweisen                |
| Jahreszinssatz               | Muss als Jahresprozentsatz eingegeben werden                             | Falsche Formatierung ändert die Zinsberechnung               |
| Tagezählbasis           | Die unterstützte Konfiguration ist typischerweise 360 oder 365                     | Ungültige Konfiguration ändert die Periodenzinsen                       |
| Dynamische-Array-Ausgabebereich | Muss frei bleiben                                            | Blockierende Zellen erzeugen `#SPILL!`                                    |
| Berechnungsmodus          | Excel sollte im automatischen Berechnungsmodus bleiben                   | Manueller Modus kann angezeigte Ergebnisse veralten lassen                       |
| Richtungsbezeichnungen          | Parameterdefinitionen und Transaktionsauswahlen müssen exakt übereinstimmen | Nicht übereinstimmender Text kann die Bewegung umkehren oder auf null setzen                    |

Das Quelldesign identifiziert speziell Konflikte durch Überlaufen dynamischer Arrays, manuellen Berechnungsmodus, nicht übereinstimmende Richtungsbezeichnungen und Formatierungsprobleme als betriebliche Fehlerbehebungsfälle. 

</details>

## Die Geschäftslogik & Methodik

Das Modell ist um ein einfaches kaufmännisches Prinzip aufgebaut: **ein historischer Finanzsaldo ist eine Zeitlinie, nicht nur eine Summe.**

Mehrere Methoden wirken zusammen:

* **Transaktionsnormalisierung** wandelt verschiedene Überweisungsrichtungen in eine konsistente Bewegungskonvention um. Dies verhindert, dass dasselbe finanzielle Ereignis in verschiedenen Teilen der Arbeitsmappe unterschiedlich interpretiert wird.
* **Laufsaldo-Rekonstruktion** zeigt, wie sich das offene Kapital nach jeder Transaktion änderte. Dies macht Teilrückzahlungen und zusätzliche Vorschüsse sichtbar, statt sie in einer Kumulativsumme zu begraben.
* **Periodenbasierte Zinsberechnung** bindet Zinsen an den Saldo, der während jeder Periode tatsächlich bestand. Das Ergebnis ist nachvollziehbarer als die Anwendung eines Zinssatzes auf einen Periodenendsaldo.
* **Gültigkeitsdatum-Zinssatzzuordnung** ermöglicht es, historische Marktzinsannahmen über die Zeit ändern zu lassen. Ein neuer Zinssatz kann eingeführt werden, ohne das historische Transaktionsregister neu aufzubauen.
* **Kapital-Zins-Trennung** macht die Abrechnungszahl erklärbar. Der Entscheider kann den Betrag des noch offenen Kapitals von den unter den gewählten Annahmen aufgelaufenen Zinsen unterscheiden.

Das Ergebnis ist ein praktischer Abstimmungsablauf: rekonstruieren Sie zuerst die historische Position, wenden Sie zweitens die genannten Annahmen an und präsentieren Sie den aktuellen Saldo erst, nachdem die zugrunde liegende Zeitlinie erstellt wurde.

## Weitere Tools in dieser Reihe

Verwandte leichtgewichtige Geschäfts- und Finanz-Entscheidungsunterstützungstools sind in der gesamten Projektsammlung verfügbar.

* **Business-Entscheidungs-Toolkits** — wiederverwendbare Excel-basierte Rahmen für wiederkehrende betriebliche und finanzielle Fragen.
* **Finanzplanungs- & Abstimmungstools** — fokussierte Modelle, die Rohaufzeichnungen in entscheidungsreife Finanzinformationen verwandeln.
* **Bau- & Betriebs-Toolkits** — praktische Arbeitsmappen für Schätzung, Kostenrechnung, Planung und betriebliche Steuerung.

Siehe das GitHub-Profil und die Produktsammlung für die breitere Toolkit-Reihe.

## Lizenz

Dieses Projekt wird unter der **Apache License 2.0** veröffentlicht.

Siehe die Lizenzdatei des Repositorys für die vollständigen Bedingungen.
