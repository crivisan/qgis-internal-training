# Selbstlern-Teil: Sitzung 2

## Fragen zum Thema

<details>
<summary><strong>Frage 1: Welches Format liefert ein WMS?</strong></summary>

- [ ] Vektordaten
- [x] Kartenbilder
- [ ] CSV-Tabellen

**Richtig:** Kartenbilder (Pixel).
</details>

<details>
<summary><strong>Frage 2: Was muss in einer CSV enthalten sein, damit QGIS Punkte daraus erzeugen kann?</strong></summary>

- [ ] Eine Spalte "Farbe"
- [x] Koordinaten-Spalten (z.B. lat/lon)
- [ ] Eine ID-Spalte

**Richtig:** Koordinaten-Spalten.
</details>

<details>
<summary><strong>Frage 3: Kann man einen WFS-Layer filtern?</strong></summary>

- [x] Ja, wie bei lokalen Vektordaten
- [ ] Nein, WFS liefert nur Bilder

**Richtig:** Ja, WFS liefert Vektordaten mit Attributen, daher sind Filter möglich.
</details>

<details>
<summary><strong>Frage 4: Wozu dient das Plugin "geobasis_loader"?</strong></summary>

- [ ] Zum Bearbeiten von Fotos
- [x] Zum einfachen Laden von amtlichen Geodaten Deutschlands
- [ ] Zum Konvertieren von PDFs

**Richtig:** Es erleichtert den Zugriff auf WMS/WFS-Dienste der Bundesländer.
</details>

## Hausaufgabe

Führen Sie die folgenden Schritte durch und dokumentieren Sie das Ergebnis mit einem Screenshot.

1. **CSV importieren** – Verwenden Sie die Datei `standorte.csv` aus Block 1.
2. **WMS-Hintergrund hinzufügen** – Nutzen Sie den BKG-Dienst `https://sgx.geodatenzentrum.de/wms_topplus_open?`
3. **WFS-Layer hinzufügen** – Verwenden Sie z.B. den NRW-Dienst `https://www.wfs.nrw.de/geobasis/wfs_nw_alkis_vereinfacht` und wählen Sie einen Layer.
4. **Attributtabelle öffnen** – Für den WFS-Layer.
5. **Ein Objekt auswählen** – Klicken Sie in der Tabelle oder auf der Karte ein Objekt an.
6. **Screenshot** – Erstellen Sie einen Screenshot, der Karte, Layer und die Auswahl zeigt.



### Musterlösung für die Antwort
> WMS liefert Kartenbilder (Pixel) ohne Attribute, geeignet als Hintergrund. WFS liefert Vektordaten mit Attributen, die man analysieren und filtern kann.