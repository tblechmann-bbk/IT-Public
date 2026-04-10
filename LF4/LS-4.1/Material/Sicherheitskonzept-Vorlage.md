# Schutzbedarfsanalyse eines Unternehmens

## Hilfreiche Links

* [BSI IT-Grundschutz Schulung](https://www.bsi.bund.de/DE/Themen/Unternehmen-und-Organisationen/Standards-und-Zertifizierung/IT-Grundschutz/Zertifizierte-Informationssicherheit/IT-Grundschutzschulung/Online-Kurs-IT-Grundschutz/Lektion_1_Einstieg/Lektion_1_node.html)
* [BSI Kompendium 2023](https://www.bsi.bund.de/SharedDocs/Downloads/DE/BSI/Grundschutz/IT-GS-Kompendium/IT_Grundschutz_Kompendium_Edition2023.html)
* [BSI Standard 200-2 (IT-Grundschutz Methodik)](https://www.bsi.bund.de/SharedDocs/Downloads/DE/BSI/Grundschutz/BSI_Standards/standard_200_2.pdf?__blob=publicationFile&v=2)
* [Beschreibung der Rectplast GmbH (Beispiel für ein Sicherheitskonzept)](https://www.bsi.bund.de/SharedDocs/Downloads/DE/BSI/Grundschutz/Hilfsmittel/Recplast/Beschreibung_Recplast.pdf?__blob=publicationFile&v=1)


## Verschaffen Sie sich einen Überblick über das Unternehmen

> Lernen Sie das Unternehmen über den Chatbot kennen und machen Sie sich Notizen.
>
> In Fließtext oder in Bulletpoints.

## Strukturanalyse

### Erfassen der Geschäftsprozesse

> Listen Sie **2** Geschäftsprozesse des Unternehmens auf.

| Kürzel | Name | Beschreibung | Prozessart | Verantwortlicher Mitarbeiter |
| -------|------|--------------|------------|------------------------------|
| GP001  | *Der Name des Prozesses* | *Eine kurze Beschreibung* | *Kerngeschäft / Unterstützender Prozess* | *Frau Mustermann* |
| GP002  | *Der Name des Prozesses* | *Eine kurze Beschreibung* | *Kerngeschäft / Unterstützender Prozess* | *Frau Mustermann* |

### Erfassen der Anwendungen

> Listen Sie je Geschäftsprozess mindestens **6** Anwendungen auf, die benötigt werden. Eine Anwendung kann auch von beiden Geschäftsprozessen benötigt werden.
>
> Ziel ist es, bei der Zuordnung von Geschäftsprozessen zu Anwendungen jeweils **6** Einträge zu haben.

| Kürzel | Name | Beschreibung | Anzahl | Benutzer |
| -------|------|--------------|------------|------------------------------|
| A001  | *Der Name der Anwendung * | *Wie oft wird die Anwendung eingesetzt?* | *Kerngeschäft / Unterstützender Prozess* | *Frau Mustermann / Aller Mitarbeiter / Team XY* |
| A002  | *Der Name der Anwendung * | *Wie oft wird die Anwendung eingesetzt?* | *Kerngeschäft / Unterstützender Prozess* | *Frau Mustermann / Aller Mitarbeiter / Team XY* |
| A003  | *Der Name der Anwendung * | *Wie oft wird die Anwendung eingesetzt?* | *Kerngeschäft / Unterstützender Prozess* | *Frau Mustermann / Aller Mitarbeiter / Team XY* |
| A004  | *Der Name der Anwendung * | *Wie oft wird die Anwendung eingesetzt?* | *Kerngeschäft / Unterstützender Prozess* | *Frau Mustermann / Aller Mitarbeiter / Team XY* |
| A005  | *Der Name der Anwendung * | *Wie oft wird die Anwendung eingesetzt?* | *Kerngeschäft / Unterstützender Prozess* | *Frau Mustermann / Aller Mitarbeiter / Team XY* |
| A006  | *Der Name der Anwendung * | *Wie oft wird die Anwendung eingesetzt?* | *Kerngeschäft / Unterstützender Prozess* | *Frau Mustermann / Aller Mitarbeiter / Team XY* |
| ...  | *Der Name der Anwendung * | *Wie oft wird die Anwendung eingesetzt?* | *Kerngeschäft / Unterstützender Prozess* | *Frau Mustermann / Aller Mitarbeiter / Team XY* |

### Zuordnung der Geschäftsprozesse zur Anwendung

> Ergänzen Sie die Anwendungsnamen und entfernen Sie die nicht zutreffende Zeilen.

#### Anwendungen von GP001: <Prozessname>

| Zuordnung  | Kürzel | Anwendungsname |
|------------|--------|----------------|
| benötigt   | A001   | *Name von Anwendung A001* |
| benötigt   | A002   | *Name von Anwendung A002* |
| benötigt   | A003   | *Name von Anwendung A003* |
| benötigt   | A004   | *Name von Anwendung A004* |
| benötigt   | A005   | *Name von Anwendung A005* |
| benötigt   | A006   | *Name von Anwendung A006* |

#### Anwendungen von GP002: <Prozessname>

| Zuordnung  | Kürzel | Anwendungsname |
|------------|--------|----------------|
| benötigt   | A001   | *Name von Anwendung A001* |
| benötigt   | A002   | *Name von Anwendung A002* |
| benötigt   | A003   | *Name von Anwendung A003* |
| benötigt   | A004   | *Name von Anwendung A004* |
| benötigt   | A005   | *Name von Anwendung A005* |
| benötigt   | A006   | *Name von Anwendung A006* |


### Entscheiden Sie sich für den Geschäftsprozess, den Sie im Verlauf genauer analysieren wollen

Gewählter Geschäftsprozess: *GP001 oder GP002*

### Erfassen der IT-Systeme

> Einschränkung : Listen Sie mindestens **6** IT-Systeme auf, die die identifizierten Anwendungen für Ihren GP benötigen.
>
> L001, L002, L003, ... : Prefix für Laptops
> 
> S001, S002, S003, ... : Prefix für Server
>
> D001, D002, D003, ... : Prefix für Desktop-Client
>
> Andere Kürzel sind möglich (z.B. O für IOT Geräte)


| Kürzel | Name | Beschreibung | Anzahl | Platform | Benutzer |
| -------|------|--------------|------------|---------------|-------|
| L001   | *Name der Gruppe L001 (Entwicklerlaptops z.b.)* | *Was sind das für Geräte ? Wozu werden die gebraucht ?* | *Anzahl* | *Windows/Linux/IoS/...* | *Wer nutzt das Gerät?* |
| ...   | ... | ... | ... | ... | ... |
| ...   | ... | ... | ... | ... | ... |
| ...   | ... | ... | ... | ... | ... |
| ...   | ... | ... | ... | ... | ... |
| ...   | ... | ... | ... | ... | ... |

### Erfassen der Netz- und Telekommunikationskomponenten

> Einschränkung : Listen Sie mindestens **2** Netzkomponenten auf, die die Anwendungen/IT-Systeme und damit Ihren GP betreffen.

| Kürzel | Name | Beschreibung | Anzahl | Platform |
| -------|------|--------------|------------|---------------|
| N001   | *Name der Netzkomponente* | *Was ist das für ein Gerät ?* | *Anzahl* | *DSL-Router/Firewall/Switch/Router* | 
| N002   | *Name der Netzkomponente* | *Was ist das für ein Gerät ?* | *Anzahl* | *DSL-Router/Firewall/Switch/Router* |

### Erfassen der Räume

> Einschränkung: Listen Sie mindestens **3** "Räume" auf, in denen die IT-Systeme/Netzkomponenten/ zu finden sind und damit auch Ihren GP betreffen.

| Kürzel  | Name | Art |
|------------|--------|-------|
| R001   | *Bezeichner/Name des Raums*   | *Raum/Flur/...* |
| R002   | *Bezeichner/Name des Raums*   | *Raum/Flur/...* |
| R003   | *Bezeichner/Name des Raums*   | *Raum/Flur/...* |

### Zuordnung der Räume zu IT-Systemen

> Ordnen Sie **alle** IT-Systeme und Netzkomponenten den Räumen zu

### IT-Systeme/Netzkomponenten in R001: <Raumname>

| Zuordnung  | Kürzel | Anwendungsname |
|------------|--------|----------------|
| beinhaltet   | *Kürzel des IT-Systems*   | *Name des IT-Systems* |
| beinhaltet   | ...   | ... |

### IT-Systeme/Netzkomponenten in R002: <Raumname>

| Zuordnung  | Kürzel | Anwendungsname |
|------------|--------|----------------|
| beinhaltet   | *Kürzel des IT-Systems*   | *Name des IT-Systems* |
| beinhaltet   | ...   | ... |

### IT-Systeme/Netzkomponenten in R003: <Raumname>

| Zuordnung  | Kürzel | Anwendungsname |
|------------|--------|----------------|
| beinhaltet   | *Kürzel des IT-Systems*   | *Name des IT-Systems* |
| beinhaltet   | ...   | ... |

## Schutzbedarfsanalyse

> Bei der Schutzbedarfanalyse ermitteln Sie den Schutzbedarf für Ihren GP sowie insgesamt **6** Assets aus den
Asset-Kategorien (Anwendungen, IT-Systeme, Netzkomponenten, Räume) (Pro Kategorie mindestens ein Asset.)
>
> Für die Bewertung der Schutzbedarfskategorien werden die Standardvorgaben aus dem 
[BSI-Standard 200-2, Kap. 8.2.1](https://www.bsi.bund.de/SharedDocs/Downloads/DE/BSI/Grundschutz/BSI_Standards/standard_200_2.html?nn=128640) genutzt.

### Schutzbedarfsfeststellung für den Geschäftsprozess *GP001/GP002*: <Prozessname>

| Grundwert | Schutzbedarf | Begründung |
|-----------|--------------|------------|
| Vertraulichkeit | *Normal/Hoch/Sehr Hoch* | *Eine plausible Begründung für die Einordnung* |
| Integrität | *Normal/Hoch/Sehr Hoch* | *Eine plausible Begründung für die Einordnung* |
| Verfügbarkeit | *Normal/Hoch/Sehr Hoch* | *Eine plausible Begründung für die Einordnung* |

### Schutzbedarfsfeststellung für ...

| Grundwert | Schutzbedarf | Begründung |
|-----------|--------------|------------|
| Vertraulichkeit | *Normal/Hoch/Sehr Hoch* | *Eine plausible Begründung für die Einordnung* |
| Integrität | *Normal/Hoch/Sehr Hoch* | *Eine plausible Begründung für die Einordnung* |
| Verfügbarkeit | *Normal/Hoch/Sehr Hoch* | *Eine plausible Begründung für die Einordnung* |

### Schutzbedarfsfeststellung für ...

| Grundwert | Schutzbedarf | Begründung |
|-----------|--------------|------------|
| Vertraulichkeit | *Normal/Hoch/Sehr Hoch* | *Eine plausible Begründung für die Einordnung* |
| Integrität | *Normal/Hoch/Sehr Hoch* | *Eine plausible Begründung für die Einordnung* |
| Verfügbarkeit | *Normal/Hoch/Sehr Hoch* | *Eine plausible Begründung für die Einordnung* |

### Schutzbedarfsfeststellung für ...

| Grundwert | Schutzbedarf | Begründung |
|-----------|--------------|------------|
| Vertraulichkeit | *Normal/Hoch/Sehr Hoch* | *Eine plausible Begründung für die Einordnung* |
| Integrität | *Normal/Hoch/Sehr Hoch* | *Eine plausible Begründung für die Einordnung* |
| Verfügbarkeit | *Normal/Hoch/Sehr Hoch* | *Eine plausible Begründung für die Einordnung* |

### Schutzbedarfsfeststellung für ...

| Grundwert | Schutzbedarf | Begründung |
|-----------|--------------|------------|
| Vertraulichkeit | *Normal/Hoch/Sehr Hoch* | *Eine plausible Begründung für die Einordnung* |
| Integrität | *Normal/Hoch/Sehr Hoch* | *Eine plausible Begründung für die Einordnung* |
| Verfügbarkeit | *Normal/Hoch/Sehr Hoch* | *Eine plausible Begründung für die Einordnung* |

### Schutzbedarfsfeststellung für ...

| Grundwert | Schutzbedarf | Begründung |
|-----------|--------------|------------|
| Vertraulichkeit | *Normal/Hoch/Sehr Hoch* | *Eine plausible Begründung für die Einordnung* |
| Integrität | *Normal/Hoch/Sehr Hoch* | *Eine plausible Begründung für die Einordnung* |
| Verfügbarkeit | *Normal/Hoch/Sehr Hoch* | *Eine plausible Begründung für die Einordnung* |

## Modellierung

> Für die Modellierung der Assets aus den BSI-Bausteinen entscheiden Sie sich bitte für **3** 
Assets.
>
> Listen Sie alle passenden BSI-Bausteine für diese Assets auf.

### Schicht APP: Anwendungen

| Baustein | Zielobjekt | Begründung         |
|-----------|--------|--------------|
| *APP.X.Y* | *A00X*   | *Die Software ABC wird auf den Rechnern ... eingesetzt.* |
| *...* | *...*   | *...* |


### Schicht SYS: IT-Systeme

| Baustein | Zielobjekt | Begründung         |
|-----------|--------|--------------|
| *SYS.X.Y* | *S00X*   | *Es wird ein Server für ... eingesetzt.* |
| *SYS.X.Z* | *S00X*   | *Der Server basiert auf ...* |
| *...* | *...*   | *...* |

### Schicht ...

*Weitere Schichten bitte ergänzen*

## IT-Grundschutz-Check

> Dokumentieren Sie das angestrebte Schutzniveau.
>
> Führen Sie für die Bausteine oben den **IT-Grundschutz Check** durch. Listen Sie 
insgesamt **10** Anforderungen auf. Mindestens **4** Anforderungen sollten den Status „nicht erfüllt“ haben.

### Schutzniveau

Es soll ein *Basis/Normales/Hohes* Schutzniveau erreicht werden.

### APP.X.Y Bausteinname

Im Folgenden werden die Ergebnisse des IT-Grundschutz-Checks für die *Basis/Standard/Hohen Anforderungen* des Bausteins *SYS.X.Y Bausteinname* aufgeführt. Zielobjekt ist das IT-System *S00X ABC Software*.

| Anforderung | Status | Umsetzung         |
|-----------|--------|--------------|
| *APP.X.Y.A1 Name der Anforderung aus BSI Kompendium (B/S/H) * | *erfüllt/nicht erfüllt*   | *Kommentar zum Stand der Umsetzung* |
| *...* | *...*   | *...* |


### SYS.X.Y

Im Folgenden werden die Ergebnisse des IT-Grundschutz-Checks für die *Basis/Standard/Hohen Anforderungen* des Bausteins *APP.X.Y Bausteinname* aufgeführt. Zielobjekt ist die Anwendung *A00X Server für ...*.

| Anforderung | Status | Umsetzung         |
|-----------|--------|--------------|
| *SYS.X.Y.A1 Name der Anforderung aus BSI Kompendium (B/S/H) * | *erfüllt/nicht erfüllt*   | *Kommentar zum Stand der Umsetzung* |
| *...* | *...*   | *...* |

### ABC.X.Y

*Weitere BSI Baussteine*

## Risikoanalyse

### Zielobjekt für Risikoanalyse wählen

> Für die Riskioanalyse wählen Sie bitte **1 Asset** mit erhöhtem Schutzbedarf.
>

Im folgenden wird die Risikoanalyse für das Asset *X00Y* durchgeführt, dieses besitzt einen hohen Schutzbedarf in den Grundwerten *Vertraulichkeit/Integrität/Verfügbarkeit*

### Gefährdungsübersicht anlegen

> Listen Sie **10** Gefährdungen gemäß der passenden Baussteine für das Asset auf.
> 
> Nutzen Sie dazu die Kreuzreferenztabellen zum IT-Grundschutz-Kompendium.

Für *Name des Assets* sind die Bausteine *ABC.X.Y Name des Bausteins, ABC.X.Z Name des Bausteins, ... relevant. Darin werden die folgenden Gefährdungen betrachtet (Grundwerte: C = Vertraulichkeit, I = Integrität, A = Verfügbarkeit):


| Gefährdung | Betroffene Grundwerte |         |
|-----------|--------|
| *G 0.X Name der Gefährdung* | *C,I,A*   |
| *...* | *...*   |

### Risiken bewerten

Die Kategorien zur Bewertung von Eintrittshäufigkeiten, Schadensauswirkungen und resultierenden
Risiken wurden wie in den folgenden Tabellen dargestellt definiert:

#### Definition Eintrittshäufigkeiten

| Eintrittshäufigkeit | Beschreibung |
| -- | -- |
| Selten | Das Ereignis könnte nach heutigem Kenntnisstand höchstens alle fünf Jahre auftreten. |
| Mittel | Das Ereignis tritt einmal alle fünf Jahre bis einmal im Jahr ein. |
| häufig | Das Ereignis tritt einmal im Jahr bis einmal pro Monat ein. |
| Sehr häufig | Das Ereignis tritt mehrmals im Monat ein. |

#### Definition Schadensauswirkungen

| Schadensauswirkungen | Beschreibung |
| -- | -- |
| vernachlässigbar | Die Schadensauswirkungen sind gering und können vernachlässigt werden. |
| begrenzt | Die Schadensauswirkungen sind begrenz und überschaubar. |
| beträchtlich | Die Schadensauswirkungen können beträchtlich sein. | 
| existenzbedrohend | Die Schadensauswirkungen können ein existenziell bedrohliches, katastrophales Ausmaß annehmen. |

#### Definition Risikokategorien

| Risikokategorie | Definition |
| -- | -- |
| gering | Die bereits umgesetzten oder zumindest im Sicherheitskonzept vorgesehenen Maßnahmen bieten einen ausreichenden Schutz. |
| mittel | Die bereits umgesetzten oder zumindest im Sicherheitskonzept vorgesehenen Maßnahmen reichen möglicherweise nicht aus. |
| hoch | Die bereits umgesetzten oder zumindest im Sicherheitskonzept vorgesehenen Maßnahmen bieten keinen ausreichenden Schutz vor der jeweiligen Gefährdung. Das Risiko kann mit einer großen Wahrscheinlichkeit nicht akzeptiert werden. |
| Sehr hoch | Die bereits umgesetzten oder zumindest im Sicherheitskonzept vorgesehenen Sicherheitsmaßnahmen bieten keinen ausreichenden Schutz vor der jeweiligen Gefährdung. Das Risiko kann mit einer sehr großen Wahrscheinlichkeit nicht akzeptiert werden. |

#### Risikomatrix

Die folgende Risikomatrix zeigt, wie die Bewertungen von Häufigkeiten und Auswirkungen in die
Risikobewertung einfließen:

![Risikomatrix](https://www.bsi.bund.de/SharedDocs/Bilder/DE/BSI/Themen/grundschutzdeutsch/Webkurs2018/Abb_7_07_Risikomatrix.png?__blob=normal&v=1)


Mithilfe dieser Risikodefinition wurden die Risiken für die als relevant angesehenen Gefährdungen für das Asset *X00Y* wie in der folgenden Tabelle dargestellt bewertet:

| Gefährdung | Eintrittshäufigkeit | Auswirkungen | Risiko |
| -- | -- | -- | -- |
| *G 0.X Name der Gefährdung* | *selten/mittel/häufig/sehr häufig* | *vernachlässigbar/begrenzt/beträchtlich/existenzbedrohend* | *gering/mittel/hoch/sehr hoch* |
| ... | ... | ... | ... |

### Risikobehandlung

> Führen Sie eine Risikobehandlung des Assets **X00Y** durch für die **10** Gefährdungen durch.
>

Im Anschluss an die Risikobewertung ist zu entscheiden, wie die identifizierten Risiken zu behandeln sind. Dabei kommen gemäß BSI-Standard 200-3 grundsätzlich vier Möglichkeiten der Risikobehandlung infrage, und zwar

- die Risikovermeidung beispielsweise durch Verzicht auf risikobehaftete Prozesse oder
technische Komponenten,
- die Risikoreduktion beispielsweise durch zusätzliche Maßnahmen zur Verringerung von
Schadensauswirkungen, Eintrittshäufigkeiten oder beidem,
- der Risikotransfer beispielsweise durch Abschluss einer Versicherung zur Vorbeugung gegen
finanzielle Schäden,
- die Risikoakzeptanz beispielsweise, weil die mit dem Risiko verbundenen Chancen genutzt
werden sollen und zusätzliche Maßnahmen zur Reduktion oder Verlagerung des Risikos für
nicht erforderlich angesehen werden.

Im nachfolgenden wird die Risikobehandlung für das Zielobjekt *X00Y Name des Assets* dargestellt:

| Gefährdung | Risikobehandlungsoption |
| -- | -- |
| *G 0.X Name der Gefährdung* | *Risikovermeidung/Risikoreduktion/Risikoakzeptanz* *Begründung der Entscheidung* |
| ... | ... |

## Realisierungsplan

> Der Realisierungsplan soll bitte **4** Maßnahmen auflisten.
>
> Die Maßnahmen ergeben sich aus offenen Anforderungen aus der Basis-(B) und Standard-Anforderungsbausteine (S) sowie ggf. aus der Risikoanalyse, falls ein hohes Risiko bewertet wurde.
>

Als Ergebnis aus IT-Grundschutz-Check und der Entscheidungen zur Risikoplan ergibt sich eine Liste an Maßnahmen, die umgesetzt werden sollen, um die relevanten und dem Schutzbedarf des Informationsverbundes entsprechenden Sicherheitsanforderungen zu erfüllen.

| Zielobjekt | Anforderung | Umzusetzende Maßnahme |
| -- | -- | -- |
| *A00X* | *APP.X.A1 Name der Anforderung* | *Was soll umgesetzt werden ?*  |
| ... | ... | ... |

## Bericht

> Verfassen sie einen kurzen Bericht (etwa 250 Wörter), in der Sie Ihren Eindruck der GAB GmbH festhalten.
>
> Was ist das Geschäftsmodell der GAB-GmbH ?
> 
> Was ist Ihnen positiv aufgefallen ?
> 
> Was ist Ihnen negativ aufgefallen ?
> 
> Welche Probleme sollte die GAB-GmbH Ihrer Meinung nach schnellstmöglichst angehen ?

## (Benotungsfrei) Feedback zur Lernsituation

> Was könnte man für das nächste Jahr für diese Unterrichtseinheit verbessern ?
> 
> Haben Sie andere Anmerkungen ?