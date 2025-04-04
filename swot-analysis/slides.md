---
theme: seriph
background: https://source.unsplash.com/collection/94734566/1920x1080
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  ## SWOT-Analyse Präsentation
  Eine detaillierte Erklärung der SWOT-Analyse Methode.
drawings:
  persist: false
transition: slide-left
title: SWOT-Analyse
mdc: true
---

# SWOT-Analyse

Strategisches Planungswerkzeug für Unternehmen und Projekte

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Drücken Sie die Leertaste für die nächste Seite <carbon:arrow-right class="inline"/>
  </span>
</div>

---

---
transition: fade-out
---

# Was ist SWOT?

SWOT steht für:

<v-clicks>

- **S**trengths (Stärken)
- **W**eaknesses (Schwächen)
- **O**pportunities (Chancen)
- **T**hreats (Risiken)

</v-clicks>

<div v-click>

## Zweck

Die SWOT-Analyse hilft Unternehmen und Projekten:

- Aktuelle Situation zu bewerten
- Strategische Entscheidungen zu treffen
- Risiken zu identifizieren
- Chancen zu nutzen

</div>

---

---
layout: two-cols
---

# Interne Faktoren

<v-clicks>

## Stärken (Strengths)

- Positive interne Eigenschaften
- Vorteile gegenüber Wettbewerbern
- Verfügbare Ressourcen
- Unique Selling Points (USPs)

## Schwächen (Weaknesses)

- Negative interne Eigenschaften
- Verbesserungspotenziale
- Ressourcenmängel
- Wettbewerbsnachteile

</v-clicks>

::right::

# Externe Faktoren

<v-clicks>

## Chancen (Opportunities)

- Positive externe Möglichkeiten
- Marktpotenziale
- Technologische Entwicklungen
- Gesellschaftliche Trends

## Risiken (Threats)

- Negative externe Einflüsse
- Wettbewerbsdruck
- Markthindernisse
- Regulatorische Änderungen

</v-clicks>

---

---
layout: center
---

# SWOT Matrix

```mermaid {scale: 0.9}
graph TB
    subgraph SWOT
    A[Stärken<br>Strengths] --> B[Schwächen<br>Weaknesses]
    C[Chancen<br>Opportunities] --> D[Risiken<br>Threats]
    A --> C
    B --> D
    end
```

---

---
layout: default
---

# Praktisches Beispiel: E-Commerce Start-up

<div class="grid grid-cols-2 gap-4">
  <div v-click>

  ### Stärken

  - Innovative Technologieplattform
  - Erfahrenes Entwicklerteam
  - Agile Arbeitsweise
  - Starke UX/UI-Design-Kompetenz

  </div>
  <div v-click>

  ### Schwächen

  - Begrenzte finanzielle Ressourcen
  - Noch keine etablierte Marke
  - Kleines Vertriebsteam
  - Begrenzte Produktpalette

  </div>
  <div v-click>

  ### Chancen

  - Wachsender E-Commerce Markt
  - Zunehmende Digitalisierung
  - Neue Technologietrends (AR/VR)
  - Internationale Expansionsmöglichkeiten

  </div>
  <div v-click>

  ### Risiken

  - Starke Konkurrenz
  - Cybersecurity-Bedrohungen
  - Wirtschaftliche Unsicherheit
  - Sich ändernde Datenschutzvorschriften

  </div>
</div>

---

---
layout: section
---

# Anwendung der SWOT-Analyse

<v-clicks>

1. **Vorbereitung**

   - Team zusammenstellen
   - Relevante Daten sammeln
   - Analysezeitraum festlegen

2. **Durchführung**

   - Brainstorming zu allen vier Bereichen
   - Priorisierung der Punkte
   - Dokumentation der Ergebnisse

3. **Auswertung**

   - Zusammenhänge identifizieren
   - Strategien entwickeln
   - Maßnahmen ableiten

4. **Umsetzung**
   - Aktionsplan erstellen
   - Verantwortlichkeiten zuweisen
   - Regelmäßige Überprüfung

</v-clicks>

---

---
layout: default
---

# Vorteile der SWOT-Analyse

<div class="grid grid-cols-2 gap-4">
  <div v-click>

  ## Einfachheit

  - Leicht verständlich
  - Schnell anwendbar
  - Flexibel einsetzbar
  - Keine speziellen Tools nötig

  </div>
  <div v-click>

  ## Nutzen

  - Ganzheitlicher Überblick
  - Basis für Strategien
  - Risikobewertung
  - Entscheidungshilfe

  </div>
</div>

<div v-click class="mt-12">

## Tipps für erfolgreiche Analyse

1. Ehrlich und objektiv bleiben  
2. Konkret und spezifisch sein  
3. Aktuelle Daten verwenden  
4. Regelmäßig aktualisieren  
5. Team-Input einbeziehen

</div>

---

---
layout: end
---

# Vielen Dank!

[Dokumentation](https://example.com) · [Weitere Ressourcen](https://example.com)
