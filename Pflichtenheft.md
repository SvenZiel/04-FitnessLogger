# **Pflichtenheft**


# 1 Ziele


/Z1/ Unterstützung bei der Trainingsplanerstellung

/Z2/ Erfassung von Leistungsdaten

/Z3/ Erfassung von Gewichtsdaten

/Z4/ Auswertung von Leistungsdaten durch Visualisierung (optional)

/Z5/ Auswertung von Gewichtsdaten durch Visualisierung (optional)
  

# 2 Rahmenbedingungen
Beschreibung der organisatorischen Rahmenbedingungen: Anwendungsbereiche, Zielgruppen, Betriebsbedingungen

#### /R10/ Anwendungsbereich 1 des Systems usw.

Die Anwendung soll für mobile Endgeräte mit dem Betriebssystem Android funktionieren.

#### /R20/ Zielgruppe 1 des Systems usw. 

Zielgruppe des Systems sind fitnessinteressierte Sportler, die für das Festhalten ihrer Leistungsdaten eine digitale Möglichkeit der Datenerfassung und -auswertung präferieren.

#### /R30/ Physikalische Umgebung des Systems 

Das System wird hauptsächlich in Sportstätten genutzt.

#### /R40/ Tägliche Betriebszeit des Systems 

Die tägliche Betriebszeit des Systems beinhaltet die Dauer einer Trainingseinheit mit einer damit verbundenen Nachbearbeitung von Leistungsdaten.

#### /R50/ Ständige Beobachtung des Systems durch Bediener 

// Bei der technischen Produktumgebung sind folgende Festlegungen zu treffen:

# Was ist damit gemeint?

#### /R60/ Eingesetzte Software auf der Zielmaschine 

Die Application "Sweet is the PUMP!!!" soll auf der Zielmaschine eingesetzt werden.

#### /R70/ Eingesetzte Hardware(komponenten) einschl. Konfiguration auf der Zielmaschine  

keine

#### /R80/ Organisatorische Randbedingungen und Voraussetzungen  

Bei den Anforderungen an die Entwicklungsumgebung sind folgende Festlegungen zu treffen:

# Was ist damit gemeint?

#### /R90/ Software auf dem Entwicklungssystem  

Aus der Entwicklungsumgebung .Net werden die Laufzeitumgebungen .NET Core und Xamarin verwendet. Diese benötigen die Komponenten ASP.Net Core und Android.

#### /R100/ Hardware des Entwicklungssystems

# Was ist damit gemeint?

#### /R110/ Orgware des Entwicklungssystems

# Was ist damit gemeint?

#### /R120/ Entwicklungsschnittstellen

# Was ist damit gemeint?
 Softwareschnittstelle?

# 3 Kontext und Überblick
Festlegung der relevanten Systemumgebung (Kontext) und Überblick über das System:

/K10/ Kontext 1 des Systems usw.  

*Zum Beispiel auch: Übergreifendes Use Case Diagramm.*

# 4 Funktionale Anforderungen
Die Kernfunktionalität des Systems ist aus Auftraggebersicht auf oberster Abstraktionsebene zu beschreiben. Auf Detailbeschreibungen ist zu verzichten:

/F10/ Das System muss ausschließlich dem Administrator die Möglichkeit bieten, neue Übungen in das System einzupflegen.

/F20/ Das System darf ausschließlich registrierten Benutzern die Möglichkeit bieten, sich am System anzumelden.

/F30/ Das System muss die Leistungsdaten der Benutzer in einer persistenten Datenbank hinterlegen.

/F40/ Das System muss dem Benutzer die Möglichkeit bieten, Trainingspläne bearbeiten zu können.

/F50/ Das System muss dem Benutzer die Möglichkeit bieten, Übungen in seine Trainingspläne einpflegen zu können.

/F60/ Das System muss dem Benutzer die Möglichkeit bieten, Übungen im Trainingsplan auswählen zu können.

/F70/ Das System muss dem angemeldeten Benutzer die Möglichkeit bieten, sich vom System abzumelden.

*Zum Beispiel auch: Beischreibung einzelner Use Cases in Textform.*

Wenn bereits möglich, sind die funktionalen Anforderungen nach Statik, Dynamik und Logik zu gruppieren.

# 5 Qualitätsanforderungen
Es sollte anhand einer Tabelle eine verfeinerte Qualitätszielbestimmung für das System vorgenommen werden. Es eignen sich dazu die Qualitätsmerkmale der ISO/IEC 9126–1.
Einzelne Qualitätsanforderungen können unter Bezug auf die ISO/IEC 9126–1 wie folgt festgelegt werden:

/QFS10/ Das System muss die Leistungsdaten der Nutzer innerhalb von drei Sekunden speichern.

/QFS20/ Das System soll eine Übung innerhalb von 2 Sekunden einem Trainingsplan hinzufügen.

/QFS30/ Das System soll einen ausgewählten Trainingsplan innerhalb von 2 Sekunden aufrufen.

/QFS40/ Das System muss den Benutzer auf möglichen Datenverlust hinweisen, wenn dieser Transaktionen abbricht.



/QBE10/ Das System muss dem Benutzer eindeutige Möglichkeiten bieten, eine Transaktion weiterzuführen.

/QBE20/ Das System muss den Benutzer auf fehlerhafte Eingaben hinweisen.

# 6 Abnahmekriterien
Abnahmekriterien legen fest, wie Anforderungen bei der Abnahme auf ihre Realisierung überprüft werden können.

### 6.1 Funktionale Anforderungen 

/F10/ Ausgangssituation: Ein Administrator fügt dem System eine neue Übung hinzu.<br>
Ereignis: Das System speichert die neue Übung in der Datenbank.<br>
Akzeptanzkriterium: Der Benutzer hat die Möglichkeit die Übung auswählen zu können.

/F20/ Ausgangssituation: Ein registrierter Benutzer versucht sich am System anzumelden.<br>
Ereignis: Der Benutzer wird am System angemeldet.<br>
Akzeptanzkriterium: Das System prüft ob die Anmeldedaten korrekt sind, sind diese nicht korrekt, wird eine Fehlermeldung ausgegeben.

/F30/ Ausgangssituation: Der Benutzer hat Leistungsdaten erfasst.<br>
Ereignis: Das System speichert die Leistungsdaten in der Datenbank.<br>
Akzeptanzkriterium: Der Benutzer hat die Möglichkeit die Leistungsdaten einsehen zu können.

/F40/ Ausgangssituation: Der Benutzer erstellt einen Trainingsplan.<br>
Ereignis: Das System speichert den Trainingsplan in der Datenbank.<br>
Akzeptanzkriterium: Der Benutzer hat die Möglichkeit, den Trainingsplan einsehen zu können.

/F50/ Ausgangssituation: Der Benutzer fügt seinem Trainingsplan eine Übung hinzu.<br>
Ereignis: Das System speichert die Übung im Trainingsplan.<br>
Akzeptanzkriterium: Der Benutzer hat die Möglichkeit, die Übung im Trainingsplan einsehen und bearbeiten zu können.

/F60/ Ausgangssituation: Der Benutzer bearbeitet einen Trainingsplan.<br>
Ereignis: Das System listet dem Benutzer die verfügbaren Übungen auf.<br>
Akzeptanzkriterium: Der Benutzer hat die Möglichkeit, die Übung im Trainingsplan auswählen zu können.

/F70/ Ausgangssituation: Der Benutzer möchte sich vom System abmelden.<br>
Ereignis: Das System beendet die Datenübertragung.<br>
Akzeptanzkriterium: Der Benutzer wird zum Startbildschirm der Anwendung geleitet.

### 6.2 Qualitätsanforderungen zur Funktion

/QFS10/ Metrik: Maximale Antwortzeit.<br>
Akzeptanzkriterium: Die maximale Antwortzeit des Systems beträgt bei einer Auslastung von 5 Benutzern 3 Sekunden.<br>
Operationalisierung: Gleichzeitiges Speichern von Leistungsdaten von mehreren Benutzern.

/QFS20/ Metrik: Maximale Antwortzeit.<br>
Akzeptanzkriterium: Die maximale Bearbeitungszeit des Systems beträgt 2 Sekunden.<br>
Operationalisierung: Mehrmaliges Hinzufügen von Übungen zu einem Trainingsplan auf verschiedenen Endgeräten.

/QFS30/ Metrik: Maximale Antwortzeit.<br>
Akzeptanzkriterium: Die maximale Bearbeitungszeit des Systems beträgt 2 Sekunden.<br>
Operationalisierung: Mehrmaliges Aufrufen von Trainingsplänen auf verschiedenen Endgeräten.

/QFS40/ Metrik: Anzahl von Datenverlusten durch Transaktionsabbrüche ohne Hinweis.<br>
Akzeptanzkriterium: Ein Transaktionsabbruch darf nicht ohne eine Warnmeldung zum Datenverlust führen.<br>
Operationalisierung: Jede Transaktionen abbrechen.

### 6.3 Qualitätsanforderungen zur Benutzbarkeit

/QBE10/ Metrik: Maximale Anzahl von Klicks zur Erreichung des Transaktionsabschlusses.<br>
Akzeptanzkriterium: Der Benutzer benötigt maximal 5 Klicks um eine Transaktion durchzuführen.<br>
Operationalisierung: Durchführung jeder Transaktion.

/QBE20/ Das System muss den Benutzer auf fehlerhafte Eingaben hinweisen.
/QBE20/ Metrik: Funktionelle Eignung.<br>
Akzeptanzkriterium: Eine Fehlermeldung wird ausgegeben, wenn in der Anmeldetransaktion eine falsche ID-Passwort-Kombination eingegeben wurde.<br>
Operationalisierung: Anmeldetests zur Simulation der Fehlermeldung.

# 7 Subsystemstruktur (optional)
Hier wird eine Aufgliederung des zu entwickelnden Systems beschrieben, wenn die Entwicklung inkrementell (Kernsystem, Ausbaustufe 1, Aufbaustufe 2 usw.) erfolgen soll.

# Glossar
Das Glossar besteht aus Glossarbegriffen mit anschließender Erklärung des jeweiligen Begriffs. Wird auf andere Glossarbegriffe verwiesen, dann wird dies durch einen Pfeil vor dem Begriff, auf den verwiesen wird, angegeben. Übersetzungen in andere Sprachen sowie Synonyme werden in Klammern hinter dem Glossarbegriff  angegeben.
