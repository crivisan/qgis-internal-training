# Koordinatenreferenzsysteme (CRS)

---

## Was ist ein CRS?

Ein CRS definiert:

- Projektion
- Bezugssystem
- Einheit (Meter oder Grad)

---

## Warum sind CRS wichtig?

Wenn Layer unterschiedliche CRS besitzen:

- liegen sie falsch übereinander
- entstehen Verzerrungen
- Analysen werden ungenau

---

## Wichtige Beispiele

| CRS | EPSG-Code | Einheit |
|------|------------|----------|
| WGS84 | 4326 | Grad |
| ETRS89 / UTM Zone 32N | 25832 | Meter |

---

📸 *Hier Diagramm Projektion einfügen*

---

## Typische Probleme

- Falsche Projektion
- Layer verschoben
- Unterschiedliche Einheiten

---

## Mini-Quiz

<form>
<input type="checkbox"> A) CRS sind nur für GPS relevant<br>
<input type="checkbox"> B) CRS definieren Projektion und Einheit<br>
<input type="checkbox"> C) Unterschiedliche CRS können zu Verschiebungen führen<br>
</form>

??? info "Lösung anzeigen"

    ✅ Richtig sind B und C