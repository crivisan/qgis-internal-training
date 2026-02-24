# Sitzung 1 – QGIS Grundlagen & Navigation

---

## 🎯 Lernziele dieser Einheit

Nach dieser Sitzung können Sie:

- den Begriff GIS erklären
- Raster- und Vektordaten unterscheiden
- typische GIS-Datenformate benennen
- ein neues QGIS-Projekt anlegen
- ein Koordinatenreferenzsystem (KBS / CRS) einstellen
- Hintergrundkarten (OSM, Luftbilder) einbinden

---

# 1️⃣ Was ist ein GIS?

Ein **Geographisches Informationssystem (GIS)** ist ein System zur:

- Erfassung
- Speicherung
- Analyse
- Visualisierung

von **räumlichen (geographischen) Daten**.

Ein GIS beantwortet Fragen wie:

- Wo befindet sich etwas?
- Was liegt in der Nähe?
- Wie verändern sich räumliche Muster?

---

## Was kann QGIS?

**QGIS** ist eine Open-Source-GIS-Software.

Typische Anwendungsfälle:

- Darstellung von Karten
- Analyse von Entfernungen (Puffer)
- Überlagerung von Layern
- Digitalisierung eigener Daten
- Einbindung von Webdiensten (WMS/WFS)
- Export von Karten als PDF

---

# 2️⃣ Vektor- vs. Rasterdaten

## 🟢 Vektordaten

Bestehen aus Geometrien:

- Punkt
- Linie
- Polygon

Eigenschaften:
- klare Grenzen
- besitzen Attributtabellen
- ideal für Verwaltungsgrenzen, Straßen, Gebäude

📸 *Hier Screenshot einfügen: Punkt/Linie/Polygon-Beispiel*

---

## 🟡 Rasterdaten

Bestehen aus Pixeln (Zellen mit Werten).

Beispiele:
- Luftbilder
- Höhenmodelle
- Temperaturkarten

Eigenschaften:
- kontinuierliche Daten
- jede Zelle besitzt einen Wert
- ideal für Umwelt- oder Fernerkundungsdaten

📸 *Hier Screenshot einfügen: Raster mit Pixelstruktur*

---

## Vergleich

| Merkmal | Vektor | Raster |
|----------|--------|--------|
| Struktur | Geometrien | Pixel |
| Attribute | Ja | Zellwerte |
| Typische Nutzung | Grenzen, Infrastruktur | Luftbilder, Höhenmodelle |

---

# 3️⃣ Wichtige Datenformate

## SHP (Shapefile)
- Klassisches Vektorformat
- Besteht aus mehreren Dateien (.shp, .dbf, .shx)

## GeoPackage (.gpkg)
- Modernes Containerformat
- Mehrere Layer in einer Datei möglich
- Empfohlenes Format

## CSV
- Tabellendaten
- Kann mit Koordinaten zu Punkten werden

## TIFF / GeoTIFF
- Rasterformat
- Enthält Georeferenzierung

---

# 4️⃣ Koordinatenreferenzsysteme (CRS)

Ein CRS definiert:

- Wie Koordinaten im Raum interpretiert werden
- Projektion
- Einheit (Meter / Grad)

Beispiele:

- WGS84 (EPSG:4326)
- UTM
- ETRS89 / UTM Zone 32N

Warum ist das wichtig?

Wenn Layer unterschiedliche CRS haben:
- können sie falsch übereinanderliegen
- entstehen Verzerrungen

📸 *Hier Diagramm einfügen: Kugel → Projektion → Ebene*

---

# 5️⃣ Praktische Übung

## Übung 1 – Neues Projekt erstellen

1. QGIS öffnen
2. Neues Projekt anlegen
3. CRS einstellen (z.B. EPSG:25832)
4. Projekt speichern

---

## Übung 2 – Hintergrundkarte einbinden

### OpenStreetMap über XYZ Tiles

1. Browser-Fenster öffnen
2. XYZ Tiles → Rechtsklick → Neue Verbindung
3. URL: https://tile.openstreetmap.org/{z}/{x}/{y}.png

4. Layer hinzufügen

📸 *Hier Screenshot XYZ-Verbindung einfügen*

---

## Optional: Luftbilder einbinden

Beispiel (je nach Verfügbarkeit in Ihrer Region):
- WMS-Dienst des Landes
- oder bestehende XYZ-Verbindung

---

# 🧠 Selbsttest

## 1) Welche Aussage beschreibt Rasterdaten korrekt?

<form>
<input type="checkbox"> A) Bestehen aus Polygonen<br>
<input type="checkbox"> B) Bestehen aus Pixeln<br>
<input type="checkbox"> C) Haben immer eine Attributtabelle<br>
<input type="checkbox"> D) Werden häufig für Luftbilder verwendet<br>
</form>

??? info "Lösung anzeigen"

    ✅ Richtig sind B und D

    Raster bestehen aus Pixeln mit Zellwerten.
    Luftbilder sind typische Rasterdaten.

---

## 2) Was ist ein CRS?

<form>
<input type="checkbox"> A) Ein Dateiformat<br>
<input type="checkbox"> B) Ein Koordinatenbezugssystem<br>
<input type="checkbox"> C) Definiert Projektion und Einheit<br>
<input type="checkbox"> D) Nur für GPS relevant<br>
</form>

??? info "Lösung anzeigen"

    ✅ Richtig sind B und C

    Ein CRS definiert, wie räumliche Koordinaten interpretiert werden.

---

# 🏠 Hausaufgabe

1. Neues Projekt erstellen.
2. OpenStreetMap als Hintergrund einbinden.
3. Projekt-CRS auf EPSG:25832 setzen.
4. Screenshot vom Projekt erstellen und speichern.
5. Notieren Sie:
   - Welches CRS ist standardmäßig eingestellt?
   - Wo kann man das CRS im Projekt ändern?

---

# 🔍 Reflexionsfragen

- Wann würden Sie Rasterdaten statt Vektordaten verwenden?
- Warum ist es problematisch, wenn Layer unterschiedliche CRS haben?
- Warum ist GeoPackage moderner als Shapefile?

---

## 📌 Vorbereitung für Sitzung 2

Bitte QGIS installiert bereithalten.

In der nächsten Sitzung:
- Laden externer Daten
- Einführung in WMS/WFS
- Arbeiten mit Attributtabellen


### Data for Session 2
- Download: [Files](https://cloud.kv-kus.de/s/Kdn3errWaPiij3c)