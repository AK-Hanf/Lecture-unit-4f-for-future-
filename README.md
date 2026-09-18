# Unterrichtseinheit: 4f for Future

Interaktive HTML-Lernmaterialien für eine Unterrichtseinheit zur **Komplexbildung, Farbigkeit und den Anwendungen von Lanthanoiden**. Das Projekt wurde im Rahmen der Masterarbeit von Aleksandar Lubinić erstellt.

## Inhalte

Das Repository enthält eine browserbasierte Lernumgebung ohne Build-Prozess und ohne externe JavaScript-Abhängigkeiten:

- **HSAB-Konzept** – Übungen zur Einordnung harter und weicher Säuren und Basen
- **Farbigkeit** – interaktive Materialien zur Farbigkeit von Komplexverbindungen und Lichtabsorption
- **Anwendungen** – Lerninhalte zu Alltags- und Industrieanwendungen der Lanthanoide
- **Design-System und Assets** – wiederverwendbare Gestaltungskomponenten, Farbschemata und UI-Beispiele
- **Thesis Data** – ergänzende Daten und Dokumente zur Masterarbeit

Die Lernmaterialien unterstützen unter anderem:

- interaktive Multiple-Choice- und Sortieraufgaben
- direkte Rückmeldungen und Fortschrittsanzeigen
- Hell-/Dunkelmodus
- Deutsch-/Englisch-Umschaltung in der erweiterten Version
- zugängliche Bedienelemente und responsive Darstellung für mobile Geräte

## Schnellstart

Da das Projekt aus statischen HTML-Dateien besteht, kann es direkt im Browser geöffnet werden.

### Variante 1: Direkt öffnen

Öffne `index.html` in einem modernen Webbrowser und wähle dort das gewünschte Lernmodul aus.

### Variante 2: Lokaler Webserver

Ein lokaler Webserver ist besonders empfehlenswert, damit relative Pfade und Browserfunktionen zuverlässig funktionieren.

```bash
python3 -m http.server 8000
```

Rufe anschließend <http://localhost:8000> im Browser auf.

## Projektstruktur

```text
.
├── index.html                         # Startseite / Lernmodule-Dashboard
├── HSAB Trainingseinheit 1.html       # HSAB-Übungseinheit
├── assets.html                        # Design-System und UI-Referenz
├── Thesis Data/                       # Daten und ergänzende Arbeitsmaterialien
├── docs                               # Dokumentations-/Deployment-Datei
├── LICENSE                            # Lizenzinformationen
└── README.md
```

Ein Teil der Lernmodule liegt innerhalb der jeweiligen Modul- beziehungsweise Dokumentationsstruktur. Verwende die Links auf der Startseite, um die verfügbaren Inhalte zu öffnen.

## Technologie

- HTML5
- CSS3 mit responsivem Layout
- Vanilla JavaScript
- Keine Installation von Paketen oder Build-Schritte erforderlich

## Anpassungen und Weiterentwicklung

Die Lernmodule sind als eigenständige HTML-Dateien aufgebaut. Inhalte, Aufgaben und Fragen können direkt in den jeweiligen Dateien angepasst werden. Bei größeren Änderungen empfiehlt es sich, wiederverwendbare Styles und Komponenten im Design-System beziehungsweise in `assets.html` zu dokumentieren.

## Lizenz

Siehe [`LICENSE`](LICENSE) für die geltenden Lizenzbedingungen.

## Hinweis zur Nutzung

Die Materialien dienen als interaktive Lern- und Unterrichtsunterstützung. Fachliche Inhalte sollten vor dem Einsatz im Unterricht auf die jeweilige Zielgruppe und den verwendeten Lehrplan abgestimmt werden.
