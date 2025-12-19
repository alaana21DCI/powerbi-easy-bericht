# Power BI Easy Bericht – Umsatz, Gewinn & Menge (Beispielprojekt)

## Überblick
Dieses Projekt ist ein einfacher Power BI Bericht zur Analyse von **Umsatz**, **Gewinn** und **Menge** nach **Stadt**, **Region** und **Produkt**.  
Es nutzt Standard-Funktionen von Power BI (Slicer/Filter, Diagramme, Tabellen) **ohne eigene DAX Measures**.

## Ziel
- Schnelle Übersicht über Performance nach Region und Stadt
- Vergleich von Umsatz/Gewinn/Menge nach Produkt
- Interaktiver Bericht mit Filtern für einfache Analyse

## Dataset
Tabelle: **EasyTabelle**

Spalten:
- **Stadt**
- **Region**
- **Produkt**
- **Verkaufspreis**
- **Menge**
- **Umsatz**
- **Gewinn**

> Hinweis: Daten sind **Sample/anonymisiert** (falls du echte Daten nutzt, bitte vorher anonymisieren).

## Bericht / Visuals
Der Bericht enthält:
- **Slicer (Filter):** Produkt
- **Donut Chart:** Umsatz-Verteilung nach Region
- **Matrix/Tabelle:** Summe von Umsatz, Gewinn und Menge nach Stadt
- **Balkendiagramm:** Gewinn nach Region
- **Karte:** Städte (z.B. Bubble-Größe nach Umsatz)

## Screenshot
![Power BI Dashboard](dashboard.png)

## Beispiel-Insights (aus dem Bericht ableitbar)
- Umsatzanteile unterscheiden sich stark zwischen den Regionen.
- Einzelne Städte liefern den größten Beitrag zum Gesamtumsatz.
- Gewinn kann je Region/Produkt negativ sein und sollte separat beobachtet werden.

## Dateien & Struktur
- `report/dashboard.png` – Screenshot des Berichts
- `report/dashboard.pdf` – PDF Export (optional)
- `data/` – Datendatei (Excel/CSV; sample/anonymisiert)
- `pbix/` – Power BI Datei (optional, falls keine sensiblen Daten und nicht zu groß)

## How to use (lokal)
1. Power BI Desktop öffnen
2. (Optional) `pbix/easy-bericht.pbix` öffnen
3. Falls nötig: Datenquelle auf Datei in `data/` umstellen
4. Bericht über den Produkt-Slicer filtern und Visuals analysieren

## Nächste Schritte (Ideen)
- Zeitdimension hinzufügen (Datum) für Trends (MoM/YoY)
- Kleine DAX Measures ergänzen (z.B. Profit Margin %)
- Tooltips/Drillthrough Seiten für Produkt-Details

