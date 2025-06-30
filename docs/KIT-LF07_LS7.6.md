# KIT - Lernfeld 7

## LS 7.6: Datenbanken modellieren

| Lernfeld | Bildungsgang | Ausbildungsjahr |
| :--- | :--- | :---: |
| LF 7:</br>Softwareprojekte durchführen | Kaufleute für Digitalisierungsmanagement (KDM) &<br> Kaufleute für IT-System-Management (KSM) | 2 |

### Kompetenzformulierung

"Die Schülerinnen und Schüler verfügen über die Kompetenz, Software zu entwerfen, zu implementieren und zu testen. Die Schülerinnen und Schüler erfassen die Zielsetzung des Kundenauftrags und leiten daraus Anforderungen für eine anzupassende Software ab. Sie analysieren relevante Schnittstellen, Prozesse und Datenbestände bei den Kunden. [...]

Sie entwerfen und implementieren Datenstrukturen [...] zur Umsetzung des Kundenauftrags. Mithilfe von Visualisierungstechniken dokumentieren sie für die Kunden und das Projektteam den Stand des Softwareentwurfs. Sie übernehmen Verantwortung im Team, halten sich an Vereinbarungen und kommunizieren unter Einsatz von Fachsprache situationsangemessen. Die Schülerinnen und Schüler testen ihre Software systematisch und korrigieren Fehler."

| Curricularer Bezug | Titel der Lernsituation (Kurzfassung) | Geplanter Zeitrichtwert |
| :--- | :--- | :---: |
| Rahmenlehrplan für Kaufleute für Digitalisierungsmanagement & Kaufleute für IT-System-Management in der Fassung vom 13.12.2019, S. 11 | LS 7.6: Datenbanken modellieren | 6 Unterrichtsstunden |

### Handlungssituation

Die Autowerkstatt AutoFix bietet Reparaturen, Wartungen und Inspektionen für PKW an. Kunden vereinbaren Termine, bringen ihr Fahrzeug vorbei und erhalten nach Abschluss der Arbeiten eine Rechnung. In der Werkstatt arbeiten mehrere Mechaniker, die auf verschiedene Fahrzeugtypen spezialisiert sind. Durch die zunehmende Digitalisierung der gesamten Mobilitätsbranche sowie einem steigenden Anteil von Elektromobilität und der damit verbundenen neuen Diagnosegeräte nimmt der Transformationsdruck auf die klassischen Autowerkstätten zu.

Die ChangeIT GmbH wird als langjähriger Partner in der IT-System-Beschaffung und Wartung der IT-Systeme durch die Werkstatt beauftragt, ein maßgeschneidertes digitales Dienstleistungsangebot für die Endkunden zu realisieren. Nach der Beschaffung moderner Endgeräte in dem Werkstattbüro und der Aktualisierung eines in der Cloud betriebenen Servers soll nun eine Anwendung entstehen, die die Prozesse der AutoFix abbildet.

Sie arbeiten in dem Projekt als Datenbankentwickler in enger Abstimmung mit den weitern Softwareentwicklern zusammen.

### Handlungsergebnis

- Überführung eines unsystematischen, redundaten und fehlerhaften Datenbestands über ein ER-Diagramm in ein **relationales Datenbankschema** der 3. Normalform.

<div style="page-break-after: always;"></div>

### Vorausgesetzte Fähigkeiten und Kenntnisse

- keine

### Handlungskompetenz

| | Handlungskompetenz</br>(Fachkompetenz und Personale Kompetenz) | Inhalte | Sozialform/Methoden |
| :--- | :--- | :--- | :--- |
| Informieren bzw. Analysieren | ➡️ Die SuS analysieren den Kundenauftrag.<br>➡️ Die SuS informieren sich über die Vorteile  digitaler Datenbanken.<br>➡️ Die SuS informieren sich über Grundbegriffe zu Datenbanken.<br> ➡️ Die SuS informieren sich über die Elemente eines Entity-Relationship-Model (ERM).<br> ➡️ Die SuS informieren sich über den Prozess der Normalisierung (1.-3. NF).<br>➡️ Die SuS informieren sich über den Aufbau des relationalen Datenbankschemas. <br> ➡️ Die SuS informieren sich über die MySQL-Datentypen. | ✅ Vorteile von digitalen Datenbanken <br> ✅ Grundbegriffe zu Datenbanken (Referenzielle Integrität, Anomalien, Redundanz, Konsistenz, Atomarität, ... ) <br> ✅ ERM: Entitäten, Beziehungen, Attribute, Beziehungsentitäten, Primärschlüssel, Fremdschlüssel, Kardinaliäten <br> ✅ Normalformen (1.-3. NF)<br> ✅ Relationales Datenbankschema<br>✅ Datentypen in MySQL| ☑️ Informationsmaterialien zur zielgerichteten Recherche werden vorausgewählt.<br> ☑️ Präsenzunterricht: Arbeit in Kleingruppen<br>☑️ Distanzunterricht: Bearbeitung in Kleingruppen unter hierfür eingerichteten Kanälen in MS Teams<br>☑️ Die Gruppen können asynchron im Gruppentempo die einzelnen Kompetenzen erarbeiten. |
| Planen / Entscheiden | ➡️ Die SuS identifizieren Probleme und Brüche in der aktuellen Datenhaltung.<br> ➡️ Die SuS strukturieren die vorliegenden Sachverhalte und Daten als Planungsgrundlage für die zu schaffende Datenbankstruktur. | s.o. | ☑️ Präsenzunterricht: Arbeit in Kleingruppen<br>☑️ Distanzunterricht: Bearbeitung in Kleingruppen unter hierfür eingerichteten Kanälen in MS Teams<br>☑️ Die Gruppen können asynchron im Gruppentempo die einzelnen Kompetenzen erarbeiten. |
| Durchführen | ➡️ Die SuS erläutern dem Kunden unter Verwendung von Fachbegriffen die Vorteile einer digitalen Datenhaltung in Form einer Datenbank. <br> ➡️ Die SuS führen den Prozess der Normalisierung bis zur 3. NF mit den zur Verfügung stehenden Daten durch.<br> ➡️ Die SuS modellieren eine Datenbank als Resultat aus dem Normalisierungsprozess in Form eines ER-Diagramms.<br> ➡️ Die SuS entwickeln aus dem ER-Diagramm ein relationales Datenbankschema unter Auflösung aller N:M-Beziehungen. | s.o. | ☑️ Präsenzunterricht: Arbeit in Kleingruppen<br>☑️ Distanzunterricht: Bearbeitung in Kleingruppen unter hierfür eingerichteten Kanälen in MS Teams<br>☑️ Die Gruppen können asynchron im Gruppentempo die einzelnen Kompetenzen erarbeiten. |
| Kontrollieren / Bewerten | ➡️ Die SuS kontrollieren die als ERM geplanten Datenbanken anhand einer Checkliste.<br> ➡️ Die SuS kontrollieren die als relationales Datenbankschema geplanten Datenbanken anhand einer Checkliste. <br> ➡️ Die SuS kontrollieren die schrittweise Überführung des Datenbestands im Rahmen der Normalisierung anhand einer Checkliste. | s.o. | ☑️ Präsenzunterricht: Arbeit in Kleingruppen<br>☑️ Distanzunterricht: Bearbeitung in Kleingruppen unter hierfür eingerichteten Kanälen in MS Teams<br>☑️ Die Gruppen können asynchron im Gruppentempo die einzelnen Kompetenzen erarbeiten. |
| Reflektieren | ➡️ Die SuS reflektieren den Arbeitsprozess in den Kleingruppen mithilfe von Reflexionsfragen. | s.o. | ☑️ Reflexionsfragen werden gestellt, um eine Hilfestellung zu geben und in den Gruppen eine gemeinsame Diskussionsgrundlage zu schaffen. <br> ☑️ Präsenzunterricht: Erst in einzeln, dann in den zuvor genutzten Gruppen. <br>☑️ Distanzunterricht: Erst in einzeln, dann in den zuvor genutzten Gruppen unter hierfür eingerichteten Kanälen in MS Teams. |

## Bearbeitungsverlauf der Lernsituation

| Verantwortliche / Verantwortlicher | Version | Bearbeitungsdatum |
| :--- | :---: | :---: |
| Neumann (NM) | 1.0 | 30.06.2025 |

### Arbeitsmaterialien / Links

- Moodle-Kurs: [LF7DB: Softwareprojekte durchführen](https://moodle.mm-bbs.de/moodle/course/view.php?id=3566)

### Schulische Entscheidungen

- Inhaltlich eng mit dem Projekt im LF7 und zur Softwareentwicklung mit Python abgestimmt.
- Nicht-relationale Datenbanken folgen im LF11

<div style="page-break-after: always;"></div>

### Leistungsnachweise

- Klassenarbeit im Rahmen des KIT GoPilot am Ende des 3. Blocks
- Test am Ende des 4. Blocks
- Mitarbeit (kontinuierlich)

### Mögliche Verknüpfungen zu anderen Lernfeldern / Fächern

- Lernfeld 7 (Projektmanagement & Programmierung in Python  )
- Lernfeld 11 (Nicht-relationale Datenbanken)

!!!info "Lizenz<br><br><a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons Lizenzvertrag" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Das KIT Curriculum</span> vom <a xmlns:cc="http://creativecommons.org/ns#" href="https://herr-nm.github.io/KIT-Curriculum/" property="cc:attributionName" rel="cc:attributionURL">Team KIT der MMBbS</a> ist lizenziert unter einer <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Namensnennung - Nicht-kommerziell - Weitergabe unter gleichen Bedingungen 4.0 International Lizenz</a>. Fragen, Hinweise etc. an neumann@mmbbs.de."