# QGIS – Oberfläche & erste Schritte

``` mermaid
graph LR
    subgraph QGIS[QGIS Oberfläche]
        A[Menüleiste] --> B[Werkzeugleisten]
        B --> C[Kartenfenster]
        D[Layer-Fenster] --> C
        E[Browser] --> C
        F[Statusleiste] --> C
    end
    
    style QGIS fill:#f5f5f5,stroke:#333,stroke-width:2px
    style A fill:#e1f5fe
    style B fill:#fff3e0
    style C fill:#ffffff,stroke:#333
    style D fill:#e8f5e8
    style E fill:#d1ffd1
    style F fill:#e0e0e0
```
*QGIS-Oberfläche: ![Screenshot](images/qgis_ui.png){ width="600" }*

------------------------------------------------------------------------

### Die wichtigsten Bereiche im Detail

| Bereich                    | Funktion                         | Tipp                             |
|----------------------------|----------------------------------|----------------------------------|
| **Layer-Fenster** (links)  | Verwaltung aller geladenen Layer | Reihenfolge = Zeichenreihenfolge |
| **Browser** (links unten)  | Datenquellen durchsuchen         | Drag & Drop möglich              |
| **Kartenfenster** (Mitte)  | Hauptarbeitsbereich              | Navigation mit Mausrad           |
| **Werkzeugleisten** (oben) | Schnellzugriff auf Werkzeuge     | Rechtsklick → ein-/ausblenden    |
| **Statusleiste** (unten)   | CRS, Koordinaten, Maßstab        | Hier CRS schnell ändern          |



------------------------------------------------------------------------

## Erste Schritte: Projekt anlegen

``` mermaid
flowchart LR
    A["QGIS starten"] --> B["📁 Neues Projekt<br/>Strg+N"]
    B --> C["💾 Projekt speichern<br/>Strg+Umschalt+S"]
    C --> D["⚙️ CRS einstellen"]
    D --> E["🌍 Hintergrundkarte hinzufügen"]
    E --> F["Erste Karte ist fertig!"]

    style A fill:#90EE90,stroke:#333
    style B fill:#87CEEB,stroke:#333
    style C fill:#FFD700,stroke:#333
    style D fill:#FFA07A,stroke:#333
    style E fill:#DDA0DD,stroke:#333
    style F fill:#98FB98,stroke:#333,stroke-width:2px
```

------------------------------------------------------------------------

## Zusammenfassung

``` mermaid
graph TD
    A["QGIS starten"] --> B["Projekt anlegen"]
    B --> C["CRS einstellen<br/>EPSG:25832"]
    C --> D["Hintergrundkarte<br/>OSM via XYZ"]
    D --> E["Layer verwalten<br/>im Layer-Fenster"]
    E --> F["Projekt speichern<br/>.qgz-Datei"]

    style A fill:#e1f5fe
    style B fill:#fff3e0
    style C fill:#ffeb9f
    style D fill:#d1ffd1
    style E fill:#ffcccb
    style F fill:#90EE90
```
