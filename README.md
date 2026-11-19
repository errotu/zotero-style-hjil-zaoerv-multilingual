# ZaöRV/HJIL Citation Style for Zotero
 
Citation style (CSL, footnote style) for the *Zeitschrift für ausländisches öffentliches Recht und Völkerrecht* (ZaöRV) and the *Heidelberg Journal of International Law* (HJIL). One file serves both language versions: the footnote format follows the **document language** set in Zotero (Deutsch → Zitierrichtlinien; English or any other language → Style Sheet).
 
Zitierstil (CSL, Fußnotenstil) für die ZaöRV und das HJIL. Eine Datei für beide Sprachfassungen: Die Fußnoten folgen der in Zotero eingestellten **Dokumentsprache** (Deutsch → Zitierrichtlinien; English oder jede andere Sprache → Style Sheet).
 
**Citation guidelines / Zitierrichtlinien:** [Guidelines for authors (English)](https://www.nomos.de/en/journals/zaoerv/#guidelines-for-authors) · [Autorenhinweise (Deutsch)](https://www.nomos.de/zeitschriften/zaoerv/#autorenhinweise)
 
**Contents / Inhalt:** [English guide](#english-guide) · [Deutsche Anleitung](#deutsche-anleitung)
 
---
 
<a id="english-guide"></a>
## English Guide
 
This guide is addressed to authors who prepare their footnotes with Zotero. The citation style implements the Zitierrichtlinien for German-language manuscripts and the Style Sheet for English-language manuscripts (both as of 16 November 2026).
The names of Zotero fields are given in the form **English (Deutsch)**, as they are displayed depending on the language of the programme.
 
 
### 1. Setting Up
1. The citation style is to be installed in Zotero: download [`hjil-zaoerv-multilingual.csl`](hjil-zaoerv-multilingual.csl) and open it (or add it under *Settings → Cite → Styles → +*).
2. In Word or LibreOffice, **Deutsch** or **English** is to be selected once for each document under *Document Preferences (Dokumenteinstellungen) → Language (Sprache)*. For any other language, footnotes are formed according to the English rules.
### 2. Standard Cases
For books, journal articles, contributions to edited volumes, commentaries and blog posts, it is sufficient to complete the usual Zotero fields. Only four points require attention:
- **Pinpoint:** Page numbers or paragraph numbers are to be entered in the citation dialogue, not in the item. With the label *Page (Seite)*, `29-30` produces “29-30”; with the label *Paragraph (Absatz)*, `41` produces “para. 41” or “Rn. 41”.
- **Journals:** The field *Journal Abbr (Zeitschriften-Abkürzung)* is to be completed (`EJIL`, `HJIL`, `AöR`). If it is empty, the full title is printed.
- **Edition:** Only the number is to be entered in *Edition (Auflage)* (`2` produces “2nd edn” or “2. Aufl.”). Text (e.g. `online`) is printed unchanged.
- **Several works by the same author:** For these works, the field *Short Title (Kurztitel)* is to be completed. A short title appears in subsequent references only in this case.
### 3. Court Decisions (Item Type *Case (Gerichtsentscheidung)*): Two Approaches
 
Court decisions are cited very differently depending on the court and the legal system (sources, docket numbers, kinds of decision, chambers). A uniform input scheme cannot cover all of this. The citation style therefore provides **two approaches**:
 
| | **Approach A: Fields** | **Approach B: Free text** |
|---|---|---|
| Scope | Courts regulated by the style sheets (ECJ, ECtHR, ICJ, PCIJ, ICSID, WTO, ITLOS, Federal Constitutional Court), and decisions with the same structure | Decisions of other legal systems, or decisions cited differently in their country of origin |
| Procedure | The usual Zotero fields and a few lines in the field *Extra* | The complete citation as **one** line in the field *Extra* |
| Advantage | Uniform form, automatic subsequent references; date and wording follow the document language | Unrestricted freedom as to the manner of citation |
| Disadvantage | Fixed pattern | All details (date, wording, italics) are to be set manually; Zotero performs no verification |
 
**General rule:** Where the decision conforms to the pattern “court, name, kind of decision of date, docket number, paragraph”, Approach A is to be used; otherwise Approach B.
 
#### Approach A: Fields
 
The entries listed under “Entry” are reproduced in the footnote **unchanged**.
 
| Field | Entry | Example |
|---|---|---|
| *Court (Gericht)* | Court in the form of the first reference | `ECtHR (Grand Chamber)` / `EGMR (Große Kammer)` |
| *Case Name (Titel)* | Name **with the parties in brackets** | `Corfu Channel Case (UK v. Albania)` |
| *Short Title (Kurztitel)* | Short name for the subsequent reference (**always to be completed**) | `Corfu Channel` |
| *History (Geschichte)* | Kind of decision | `judgment` / `Urteil`, `award`, `report` |
| *License (Lizenz)*, in older versions *Rights (Rechte)* | Stage of the proceedings (optional) | `merits` / `Merits` |
| *Date Decided (Entscheidungsdatum)* | Date | |
| *Docket Number (Aktenzeichen)* | Docket number **with prefix**, ECLI at the end. If only a number is entered, the citation style adds `no.` or `Nr.` | `case no. 8/74, ECLI:EU:C:1974:82` / `Rs. 8/74, ECLI:EU:C:1974:82`; ECtHR: `48756/14` |
| *Reporter (Entscheidungssammlung)* / *Reporter Volume (Band)* / *First Page (Erste Seite)* | Source | `ICJ Reports` / `1949` / `4` |
| *Extra (Extra)* | Further addition **with brackets**, as a line without a label | `(prompt release)` |
 
**Information for which the item type provides no field:** The short form of the court and the reference to “juris” are to be entered as **lines in the field *Extra (Extra)***:
 
```
Jurisdiction: ECtHR
Source: juris
```
 
| Line | Meaning | Example |
|---|---|---|
| `Jurisdiction:` | Court in the subsequent reference, only if it differs from the first reference | `ECtHR` / `EGMR`, `WTO` |
| `Source:` | Database; `juris` produces “zitiert nach juris” | `juris` |
 
The following applies to the field *Extra*:
- Only one entry is to be made per line; the colon is followed by a space.
- Apart from the addition in brackets, the field *Extra* must contain no other text. Any further text appears in the footnote.
**Particular constellations**
- **Official collection (BVerfGE):** The field *Court (Gericht)* is to be **left empty**. The entries are *Reporter (Entscheidungssammlung)* `BVerfGE`, *Reporter Volume (Band)* `141` and *First Page (Erste Seite)* `1`; *Case Name (Titel)* contains the nickname (`Treaty Override`). Result: “BVerfGE 141, 1 (Rn. 45) – Treaty Override.”
- **Journal instead of collection:** *Court (Gericht)* `BVerfG`, *History (Geschichte)* `Urteil`, *Docket Number (Aktenzeichen)* `2 BvR 1333/17`, *Reporter (Entscheidungssammlung)* `NJW`, *First Page (Erste Seite)* `1049`; *Reporter Volume (Band)* remains empty (the year is taken from the date).
- **“zitiert nach juris”:** Line `Source: juris` in the field *Extra*.
- **Single ECtHR application number:** Only the number is to be entered (`48756/14`); the citation style adds `no.` or `Nr.`. For all other courts, the prefix is always to be written out (`case no. 14`, `Rs. 8/74`), as otherwise `no.` or `Nr.` is added in error.
- **Subsequent reference to German decisions:** The field *Short Title (Kurztitel)* is to be left empty. The decision is then repeated in full (requirement of the guidelines).
- **Several docket numbers:** All docket numbers are to be entered verbatim in one field (`nos 8675/15 and 8697/15`).
#### Approach B: Free Text
 
The complete citation, as customary in the country of origin, is to be entered as a line in the field *Extra (Extra)*:
 
```
Citation Label: Cour de cassation (France), <i>Arrêt Dassonville</i>, 11 juillet 1974, n° 74-1234
```
 
- Where this line is present, **all other fields** of the item are disregarded for the footnote.
- Italics are to be applied exclusively with `<i>…</i>`. The pinpoint is entered in the citation dialogue as usual and appended with a comma (`…, n° 74-1234, para. 5`).
- **Subsequent reference:** If *Short Title (Kurztitel)* is empty, the entire line is repeated with the new pinpoint. If it is completed, it appears **exactly as entered**, supplemented by `(n. X)` and the pinpoint (`Cass., <i>Dassonville</i> (n. 4), para. 9`).
- The line is **language-dependent**: date format, wording and sources are to be written in the desired form by the author.
### 4. Further Particularities
 
**United Nations documents (item type *Bill (Gesetzentwurf)*)**
- *Resolution:* *Bill Number (Nummer des Gesetzentwurfs)* `S/RES/2537` and *Date (Datum)*. The entire designation is to be entered in the field *Title (Titel)*; the field *Legislative Body (Gesetzgebende Körperschaft)* remains empty. English: `UNSC Resolution 2537` (produces “UNSC Resolution 2537, 28 July 2020, S/RES/2537”). German: `VN, SR Resolution 2537` (produces “VN, SR Resolution 2537, 28. Juli 2020, S/RES/2537”). The same applies to General Assembly resolutions (`UNGA Resolution 74/297`, or `VN, GV Resolution 74/297`).
- *ILC document:* *Legislative Body (Gesetzgebende Körperschaft)* `ILC`, *Title (Titel)* = title of the document, *Date (Datum)* = year, *Code (Code)* `ILCYB`, *Code Volume (Band des Codes)* `Vol. II`, *Section (Teil)* `Part Two`, *Code Pages (Seiten des Codes)* `31`, *Short Title (Kurztitel)* `ARSIWA`. The pinpoint is to be entered in the citation dialogue with the label *Page (Seite)*: `Art. 35 para. 10`.
**Treaties and legal acts (item type *Statute (Gesetz)*)**
- *Name of Act (Name des Erlasses)* is the full designation **with date** (`Vienna Convention on the Law of Treaties of 23 May 1969`).
- *Short Title (Kurztitel)* contains the abbreviation (`Rome I`); *History (Geschichte)* contains the source (`1155 UNTS 331` / `UNTS 1155, 331`, `OJ 2008 L 177/6`).
**Working paper (item type *Preprint (Preprint)*)**
- *Repository (Repositorium)* `SSRN`, *URL (URL)* and *Date (Datum)* are to be entered.
- *Series (Reihe)* contains the complete series text including the number: `… Research Paper No. 2023 – 16` (not in the field *Series Number (Nummer der Reihe)*).
- A full stop follows the date only if both series and URL are given; otherwise a comma follows.
### 5. Language-Dependent Entries
The following fields are printed unchanged and must therefore be entered in the language of the manuscript: *History (Geschichte)*, *License (Lizenz)*, *Docket Number (Aktenzeichen)*, *Extra (Extra)* (including `Citation Label:`), as well as the designations of legal acts and documents. An item cited in both languages is to be created in two versions.
 
### 6. Notes on Incorrect Output
1. Is the document language set correctly (*Deutsch* or *English*)?
2. Is the field *Short Title (Kurztitel)* completed for court decisions?
3. Are the additional entries in the field *Extra (Extra)* written exactly as in the examples, is there only one entry per line, and does the field contain no other text?
---
 
<a id="deutsche-anleitung"></a>
## Deutsche Anleitung
 
Diese Anleitung richtet sich an Autorinnen und Autoren, die ihre Fußnoten mit Zotero erstellen. Der Zitierstil bildet die Zitierrichtlinien für deutschsprachige Manuskripte sowie das Style Sheet für englischsprachige Manuskripte (jeweils Stand 16. November 2026) ab.
Die Namen der Zotero-Felder werden in der Form **English (Deutsch)** angegeben, wie sie je nach Programmsprache angezeigt werden.
 
 
### 1. Einrichtung
1. Der Zitierstil ist in Zotero zu installieren: [`hjil-zaoerv-multilingual.csl`](hjil-zaoerv-multilingual.csl) herunterladen und öffnen (oder unter *Einstellungen → Zitieren → Stile → +* hinzufügen).
2. In Word oder LibreOffice ist unter *Document Preferences (Dokumenteinstellungen) → Language (Sprache)* für jedes Dokument einmalig **Deutsch** oder **English** auszuwählen. Bei jeder anderen Sprache werden die Fußnoten nach den englischen Regeln gebildet.
### 2. Regelfall
Bei Monographien, Aufsätzen, Beiträgen in Sammelbänden, Kommentierungen und Blogbeiträgen genügt es, die üblichen Zotero-Felder auszufüllen. Zu beachten sind lediglich vier Punkte:
- **Fundstelle (Pinpoint):** Seitenzahl oder Randnummer sind im Zitierdialog anzugeben, nicht im Eintrag. Mit dem Label *Page (Seite)* ergibt `29-30` die Angabe „29-30“, mit dem Label *Paragraph (Absatz)* ergibt `41` die Angabe „para. 41“ bzw. „Rn. 41“.
- **Zeitschriften:** Das Feld *Journal Abbr (Zeitschriften-Abkürzung)* ist auszufüllen (`EJIL`, `HJIL`, `AöR`). Ist es leer, wird der vollständige Titel ausgegeben.
- **Auflage:** Im Feld *Edition (Auflage)* ist nur die Zahl einzutragen (`2` ergibt „2nd edn“ bzw. „2. Aufl.“). Text (z. B. `Online-Ausgabe`) wird unverändert ausgegeben.
- **Mehrere Werke derselben Autorin oder desselben Autors:** Bei diesen Werken ist das Feld *Short Title (Kurztitel)* auszufüllen. Nur dann erscheint im Folgezitat ein Kurztitel.
### 3. Gerichtsentscheidungen (Eintragstyp *Case (Gerichtsentscheidung)*): zwei Ansätze
 
Gerichtsentscheidungen werden je nach Gericht und Rechtsordnung sehr unterschiedlich zitiert (Fundstellen, Aktenzeichen, Entscheidungsarten, Spruchkörper). Ein einheitliches Eingabeschema kann dies nicht vollständig abbilden. Der Zitierstil sieht deshalb **zwei Ansätze** vor:
 
| | **Ansatz A: Felder** | **Ansatz B: Freitext** |
|---|---|---|
| Anwendungsbereich | Gerichte, die in den Richtlinien geregelt sind (EuGH/ECJ, EGMR/ECtHR, IGH/ICJ, StIGH, ICSID, WTO, ITLOS, BVerfG), sowie Entscheidungen mit demselben Aufbau | Entscheidungen anderer Rechtsordnungen oder mit abweichender Zitierweise im Herkunftsland |
| Vorgehen | übliche Zotero-Felder und wenige Zeilen im Feld *Extra* | vollständige Zitierweise als **eine** Zeile im Feld *Extra* |
| Vorteil | einheitliche Form, automatisches Folgezitat, Datum und Begriffe folgen der Dokumentsprache | uneingeschränkte Freiheit bei der Zitierweise |
| Nachteil | festes Muster | sämtliche Angaben (Datum, Begriffe, Kursivierung) sind manuell zu setzen; Zotero führt keine Prüfung durch |
 
**Grundregel:** Entspricht die Entscheidung dem Muster „Gericht, Name, Art der Entscheidung vom Datum, Aktenzeichen, Randnummer“, ist Ansatz A zu wählen, andernfalls Ansatz B.
 
#### Ansatz A: Felder
 
Die unter „Eintrag“ aufgeführten Angaben werden **unverändert** in die Fußnote übernommen.
 
| Feld | Eintrag | Beispiel |
|---|---|---|
| *Court (Gericht)* | Gericht in der Form des Erstzitats | `ECtHR (Grand Chamber)` / `EGMR (Große Kammer)` |
| *Case Name (Titel)* | Name **mit Parteien in Klammern** | `Corfu Channel Case (UK v. Albania)` |
| *Short Title (Kurztitel)* | Kurzname für das Folgezitat (**stets auszufüllen**) | `Corfu Channel` |
| *History (Geschichte)* | Art der Entscheidung | `judgment` / `Urteil`, `award`, `report` |
| *License (Lizenz)*, in älteren Versionen *Rights (Rechte)* | Verfahrensabschnitt (optional) | `merits` / `Merits` |
| *Date Decided (Entscheidungsdatum)* | Datum | |
| *Docket Number (Aktenzeichen)* | Aktenzeichen **mit Präfix**, ECLI am Ende. Wird nur eine Nummer eingetragen, ergänzt der Zitierstil `no.` bzw. `Nr.` | `case no. 8/74, ECLI:EU:C:1974:82` / `Rs. 8/74, ECLI:EU:C:1974:82`; EGMR: `48756/14` |
| *Reporter (Entscheidungssammlung)* / *Reporter Volume (Band)* / *First Page (Erste Seite)* | Fundstelle | `ICJ Reports` / `1949` / `4` |
| *Extra (Extra)* | weiterer Zusatz **mit Klammern**, als Zeile ohne Bezeichnung | `(prompt release)` |
 
**Angaben, für die der Eintragstyp kein eigenes Feld vorsieht:** Die Kurzform des Gerichts und der Hinweis auf „juris“ sind als **Zeilen im Feld *Extra (Extra)*** einzutragen:
 
```
Jurisdiction: ECtHR
Source: juris
```
 
| Zeile | Bedeutung | Beispiel |
|---|---|---|
| `Jurisdiction:` | Gericht im Folgezitat, nur wenn es vom Erstzitat abweicht | `ECtHR` / `EGMR`, `WTO` |
| `Source:` | Datenbank; `juris` ergibt „zitiert nach juris“ | `juris` |
 
Für das Feld *Extra* gilt:
- Je Zeile ist nur eine Angabe einzutragen; nach dem Doppelpunkt folgt ein Leerzeichen.
- Außer dem Zusatz in Klammern darf im Feld *Extra* nichts stehen. Jeder weitere Text erscheint in der Fußnote.
**Besondere Konstellationen**
- **Amtliche Entscheidungssammlung (BVerfGE):** Das Feld *Court (Gericht)* ist **leer zu lassen**. Einzutragen sind *Reporter (Entscheidungssammlung)* `BVerfGE`, *Reporter Volume (Band)* `141` und *First Page (Erste Seite)* `1`; *Case Name (Titel)* enthält die Namensbezeichnung (`Treaty Override`). Ergebnis: „BVerfGE 141, 1 (Rn. 45) – Treaty Override.“
- **Zeitschrift anstelle der Sammlung:** *Court (Gericht)* `BVerfG`, *History (Geschichte)* `Urteil`, *Docket Number (Aktenzeichen)* `2 BvR 1333/17`, *Reporter (Entscheidungssammlung)* `NJW`, *First Page (Erste Seite)* `1049`; *Reporter Volume (Band)* bleibt leer (das Jahr wird dem Datum entnommen).
- **„zitiert nach juris“:** Zeile `Source: juris` im Feld *Extra*.
- **Einzelne EGMR-Beschwerdenummer:** Es ist nur die Nummer einzutragen (`48756/14`); der Zitierstil ergänzt `no.` bzw. `Nr.`. Bei allen anderen Gerichten ist das Präfix stets mitzuschreiben (`case no. 14`, `Rs. 8/74`), da andernfalls fälschlich `no.` bzw. `Nr.` vorangestellt wird.
- **Folgezitat deutscher Entscheidungen:** Das Feld *Short Title (Kurztitel)* ist leer zu lassen. Die Entscheidung wird dann vollständig wiederholt (Vorgabe der Zitierrichtlinien).
- **Mehrere Aktenzeichen:** Sämtliche Aktenzeichen sind in einem Feld wörtlich einzutragen (`nos 8675/15 and 8697/15`).
#### Ansatz B: Freitext
 
Die vollständige, im Herkunftsland übliche Zitierweise ist als Zeile im Feld *Extra (Extra)* einzutragen:
 
```
Citation Label: Cour de cassation (France), <i>Arrêt Dassonville</i>, 11 juillet 1974, n° 74-1234
```
 
- Bei Vorliegen dieser Zeile werden **alle übrigen Felder** des Eintrags für die Fußnote nicht berücksichtigt.
- Kursivierungen sind ausschließlich mit `<i>…</i>` vorzunehmen. Die Fundstelle (Pinpoint) wird wie üblich im Zitierdialog angegeben und mit Komma angefügt (`…, n° 74-1234, para. 5`).
- **Folgezitat:** Ist *Short Title (Kurztitel)* leer, wird die gesamte Zeile mit neuer Fundstelle wiederholt. Ist er ausgefüllt, erscheint er **exakt wie eingetragen**, ergänzt um `(n. X)` und die Fundstelle (`Cass., <i>Dassonville</i> (n. 4), para. 9`).
- Die Zeile ist **sprachabhängig**: Datumsformat, Begriffe und Fundstellen sind in der gewünschten Form selbst zu schreiben.
### 4. Weitere Besonderheiten
 
**Dokumente der Vereinten Nationen (Eintragstyp *Bill (Gesetzentwurf)*)**
- *Resolution:* *Bill Number (Nummer des Gesetzentwurfs)* `S/RES/2537` und *Date (Datum)*. Die gesamte Bezeichnung ist in das Feld *Title (Titel)* einzutragen, das Feld *Legislative Body (Gesetzgebende Körperschaft)* bleibt leer. Englisch: `UNSC Resolution 2537` (ergibt „UNSC Resolution 2537, 28 July 2020, S/RES/2537“). Deutsch: `VN, SR Resolution 2537` (ergibt „VN, SR Resolution 2537, 28. Juli 2020, S/RES/2537“). Für Resolutionen der Generalversammlung gilt Entsprechendes (`UNGA Resolution 74/297` bzw. `VN, GV Resolution 74/297`).
- *ILC-Dokument:* *Legislative Body (Gesetzgebende Körperschaft)* `ILC`, *Title (Titel)* = Titel des Dokuments, *Date (Datum)* = Jahr, *Code (Code)* `ILCYB`, *Code Volume (Band des Codes)* `Vol. II`, *Section (Teil)* `Part Two`, *Code Pages (Seiten des Codes)* `31`, *Short Title (Kurztitel)* `ARSIWA`. Die Fundstelle ist im Zitierdialog mit dem Label *Page (Seite)* anzugeben: `Art. 35 para. 10`.
**Verträge und Rechtsakte (Eintragstyp *Statute (Gesetz)*)**
- *Name of Act (Name des Erlasses)* ist die vollständige Bezeichnung **mit Datum** (`Vienna Convention on the Law of Treaties of 23 May 1969`).
- *Short Title (Kurztitel)* enthält die Abkürzung (`Rome I`), *History (Geschichte)* die Fundstelle (`1155 UNTS 331` / `UNTS 1155, 331`, `OJ 2008 L 177/6`).
**Working Paper (Eintragstyp *Preprint (Preprint)*)**
- *Repository (Repositorium)* `SSRN`, *URL (URL)* und *Date (Datum)* sind einzutragen.
- *Series (Reihe)* enthält den vollständigen Reihentext einschließlich der Nummer: `… Research Paper No. 2023 – 16` (nicht im Feld *Series Number (Nummer der Reihe)*).
- Nach dem Datum steht ein Punkt nur, wenn sowohl Reihe als auch URL angegeben sind, andernfalls ein Komma.
### 5. Sprachabhängige Angaben
Die folgenden Felder werden unverändert ausgegeben und müssen daher in der Sprache des Manuskripts angegeben werden: *History (Geschichte)*, *License (Lizenz)*, *Docket Number (Aktenzeichen)*, *Extra (Extra)* (einschließlich `Citation Label:`) sowie die Bezeichnungen von Rechtsakten und Dokumenten. Ein Eintrag, der in beiden Sprachen zitiert wird, ist in zwei Varianten anzulegen.
 
### 6. Hinweise bei fehlerhafter Ausgabe
1. Ist die Dokumentsprache korrekt eingestellt (*Deutsch* oder *English*)?
2. Ist bei Gerichtsentscheidungen das Feld *Short Title (Kurztitel)* ausgefüllt?
3. Sind die Zusatzangaben im Feld *Extra (Extra)* exakt wie in den Beispielen geschrieben, steht je Zeile nur eine Angabe, und enthält das Feld sonst keinen Text?
---
 
## License and Acknowledgement
License: [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
The creation of this style was assisted by Claude Sonnet 5.5.
 
 
