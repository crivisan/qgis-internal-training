# Sitzung 4 – Einfache Vektoranalysen

## Lernziele dieser Sitzung

Nach dieser Sitzung können Sie:

- Die Geoverarbeitungs-Werkzeuge **Clip**, **Buffer**, **Polygon → Linie** und **Symmetrische Differenz** anwenden
- Verstehen, wann welches Werkzeug eingesetzt wird
- Eine **Analysekette** aus mehreren Schritten aufbauen
- An einem realen Fall aus dem Landkreis Kusel zeigen, wie GIS-Analyse Verwaltungsfragen beantwortet
- Ergebnisse korrekt interpretieren und Fehlerquellen erkennen

## Aufbau der Sitzung

| Block | Thema |
|-------|-------|
| 1 | Theorie – Geoverarbeitungs-Werkzeuge im Überblick |
| 2 | Praxis – LSG-Grenze gegen ALKIS prüfen (realer Fall) |
| 3 | Übung – Eigenständige Anwendung für das LSG Holzbachtal |

## Direkt zu den Blöcken

- [Analyse-Grundlagen (Theorie)](analyse-grundlagen.md)
- [LSG vs. ALKIS – Praxis](lsg-alkis-vergleich.md)
- [Übung – Holzbachtal](self-learning.md)
- [Ressourcen](resources.md)

## Hintergrund: Warum diese Sitzung?

In dieser Sitzung verlassen wir das reine **Darstellen** von Daten und gehen zum **Auswerten** über. Wir beantworten räumliche Fragen wie:

- „Welche Flurstücke liegen ganz oder teilweise im Schutzgebiet?"
- „Wo weicht die neu festgelegte Schutzgebietsgrenze von den Flurstücksgrenzen ab?"
- „Welche Gebäude befinden sich innerhalb von 200 m um eine geplante Baustelle?"

Diese Fragen treten in der Bauabteilung **regelmäßig** auf. Die heute behandelten Werkzeuge sind das Handwerkszeug dafür.

## Was Sie für diese Sitzung brauchen

- QGIS installiert (aktuelle LTR-Version)
- Plugin **Geobasis Loader RLP** (für ALKIS-WFS)
- Die Übungsdaten aus dem [Ressourcen-Bereich](resources.md)
- Ca. 1,5 Stunden Zeit

!!! tip "Hinweis"
    Alle Werkzeuge dieser Sitzung finden Sie unter **Vektor → Geoverarbeitungswerkzeuge** oder über die **Verarbeitungswerkzeuge** (Strg+Alt+T) per Suchfeld.
