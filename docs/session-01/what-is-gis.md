# Was ist GIS?

---

## Definition

Ein **Geographisches Informationssystem (GIS)** ist ein System zur:

```mermaid
graph TD
    A[Geographisches Informationssystem GIS] --> B[Erfassung<br>räumlicher Daten]
    A --> C[Speicherung<br>räumlicher Daten]
    A --> D[Analyse<br>räumlicher Daten]
    A --> E[Visualisierung<br>räumlicher Daten]
```

Weder Fernerkundung, noch CAD, noch Datenbanken für sich allein sind ein GIS. 
Erst die **Integration aller drei Komponenten** macht ein Geographisches Informationssystem aus.


```mermaid
%%{init: {'theme': 'forest'}}%%
mindmap
  root((Geographische<br>Informationssysteme))
    Fernerkundung
      Satellitenbilder
      Luftbildfotografie
      Drohnendaten
    CAD
      Ingenieursentwurf
      Stadtplanung
      3D-Modellierung
    Datenbanken
      Speicherung räumlicher Daten
      Attributverwaltung
      Abfrageverarbeitung
```


---

## Räumliche Fragestellungen

GIS beantwortet Fragen wie:

| Frage | Beispiel |
|-------|----------|
| **Wo** befindet sich etwas? | Standort von Schulen, Krankenhäusern |
| **Was** liegt in der Nähe? | Supermärkte im Umkreis von 1 km |
| **Wie** verändern sich Strukturen? | Stadtwachstum über 10 Jahre |
| **Welche** Flächen sind betroffen? | Überschwemmungsgebiete |

---
## Typische Anwendungsbereiche

```mermaid
%%{init: {'theme': 'forest'}}%%
graph LR
    subgraph Verwaltung
        A[Flächennutzung]
    end
    subgraph Umwelt
        B[Hochwasseranalyse]
    end
    subgraph Stadtplanung
        C[Infrastruktur]
    end
    subgraph Verkehr
        D[Netzwerkanalyse]
    end
    
    A & B & C & D --> E[GIS-Plattform]
```

---

## Bestandteile eines GIS

Ein GIS besteht aus:

- 🗺 Geodaten
- 💻 Software
- 👤 Anwendern
- 🧠 Analytischen Methoden
