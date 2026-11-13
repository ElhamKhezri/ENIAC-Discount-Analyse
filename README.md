
# 📉 ENIAC Rabattstrategie – Datenanalyse
 
---

## 🎯 Projektübersicht

Im Rahmen dieses Projekts haben wir die historische Rabatt- und Preisstrategie von **ENIAC** analysiert, um der zentralen Frage nachzugehen: **„Ist es sinnvoll, weiterhin Rabatte anzubieten?“**

Mithilfe von **Python** und der Visualisierungsbibliothek **Seaborn** haben wir Verkaufsdaten (bis März 2018 ausgewertet, um Muster in der Preisgestaltung, der Saisonalität und den Auswirkungen von Rabatten auf den Umsatz und die Magen zu identifizieren.

---

## 📊 Kernerkenntnisse & Ergebnisse

* **Hoher Rabattanteil:** Rund **93 % aller Produkte** wurden mit irgendeiner Form von Rabatt verkauft.
* **Umsatztreiber vs. Margenverlust:** Zwar generieren stark nachgefragte Produkte (wie der *LG 27" 4K Monitor* oder diverse *Apple iPhones*) hohe Umsätze, jedoch führt die aggressive Preisreduktion zu massiven Margenverlusten.
* **Saisonalität:** Der Umsatz ist stark schwankend. Deutliche Peaks zeigen sich im **November (Black Friday)** sowie im **Dezember/Januar (Weihnachtsgeschäft)**, gefolgt von einem Einbruch von Februar bis April.
* **Durchschnittlicher Rabatt:** Über den gesamten Zeitraum lag der durchschnittliche Produkt-Rabatt konstant bei rund **20 %**.

---

## 💡 Handlungsempfehlungen & Strategie

Statt dauerhafter Rabatte auf das komplette Sortiment lautet unsere Empfehlung: **Ja zu Rabatten – aber nur während der Peak-Saison und auf ausgewählte Produkte!**
1. **Apple Hardware kaum rabattieren** (Zubehör kann hingegen flexibler mit 10–40 % rabattiert werden).
2. **Gezielte saisonale Peaks nutzen** (Black Friday im November, Weihnachtsgeschäft, Sommerschlussverkauf im Juli, Back-to-School im August).
3. **Bundles kreieren** (z. B. Hauptprodukte mit rabattiertem Zubehör).
4. **Kundenbindung stärken** durch Treueprogramme, gezielte Newsletter-Gutscheine und einen speziellen Kundenservice statt permanenter Preissenkungen.

---

## 🛠️ Tech Stack

* **Python** – Datenbereinigung, Analyse und Verarbeitung
* **Seaborn & Matplotlib** – Erstellung der Diagramme und Visualisierungen

---

## 📂 Projektstruktur

```text
├── data/               # Bereinigte Rohdaten / Datensätze
├── notebooks/          # Jupyter Notebooks mit den Analyseschritten
├── ENIAC Discount Analyse.pdf # Abschlusspräsentation
└── README.md           # Projektdokumentation
