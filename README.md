# Signale und Systeme – Interaktive Lernmaterialien

**Technische Universität Braunschweig · Institut für Nachrichtentechnik (IfN)**  
**Wintersemester 2026/2027**

- **Vorlesung:** Prof. Dr.-Ing. Eduard A. Jorswieck
- **Übung:** Darius Heerklotz

## Willkommen

Dieses Repository enthält interaktive Animationen und Demonstrationen zur Vorlesung **Signale und Systeme** an der Technischen Universität Braunschweig. Sie helfen dabei, mathematische Zusammenhänge zu visualisieren, Signalparameter selbst zu verändern und die Auswirkungen direkt zu beobachten.

### ▶ [Alle interaktiven Lernmaterialien öffnen](https://jorsey75.github.io/Signale-Systeme/)

## Verfügbare Animationen

### 1. Faltung zeitkontinuierlicher Signale

Die Animation zeigt die Schritte **Spiegeln, Verschieben, Multiplizieren und Integrieren**. Verschiedene Signalpaare können ausgewählt und die Verschiebung kann interaktiv gesteuert werden.

**[Faltungsanimation starten](https://jorsey75.github.io/Signale-Systeme/faltung/)**

### 2. Der Dirac-Impuls

Experimente zur Annäherung des Dirac-Impulses durch schmale Pulse, zur **Siebeigenschaft** und zum Zusammenhang zwischen Dirac-Eingang und Impulsantwort eines LTI-Systems.

**[Dirac-Animation starten](https://jorsey75.github.io/Signale-Systeme/Dirac/)**

### 3. Von der Rechteckfaltung zur Gaußverteilung

Die wiederholte Faltung normierter Rechtecksignale nähert sich bei wachsender Faltungszahl einer **Gaußverteilung** an. Ein Schieberegler und der Vergleich mit der Standardnormalverteilung machen den Zusammenhang zum **zentralen Grenzwertsatz** sichtbar.

**[Gauß-Animation starten](https://jorsey75.github.io/Signale-Systeme/GGZ/)**

## Nutzung

- Die Animationen laufen direkt im Webbrowser; eine zusätzliche Installation ist nicht erforderlich.
- Sie können in der Vorlesung, zum Selbststudium und – soweit freigeschaltet – über die Stud.IP-Courseware verwendet werden.
- Die HTML-Dateien lassen sich auch lokal im Browser öffnen.

## Technische Umsetzung

Die Anwendungen sind mit **HTML, CSS und JavaScript** erstellt und werden über **GitHub Pages** bereitgestellt. Jede Animation liegt in einem eigenen Unterordner mit einer `index.html`.

```text
Signale-Systeme/
├── index.html        # Startseite
├── README.md
├── faltung/
│   └── index.html
├── Dirac/
│   └── index.html
└── GGZ/
    └── index.html
```

**Hinweis:** Bei den Pfaden auf GitHub Pages ist die Groß- und Kleinschreibung wichtig.

## Ausblick

Weitere interaktive Beispiele zu Fouriertransformation, Abtastung und Aliasing, Linearisierung nichtlinearer Systeme sowie Laplace-Transformation sind als mögliche Erweiterungen vorgesehen.

## Kontakt

**Prof. Dr.-Ing. Eduard A. Jorswieck**  
Institut für Nachrichtentechnik, Technische Universität Braunschweig  
[Webseite des IfN](https://www.tu-braunschweig.de/ifn)
