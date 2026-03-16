# howtobeahero-EncounterFightHelper-Fog-Elysium-Horizon-

--------------------------------------------------------------------------

This project is source-available, not Open Source.
Use, modification and free redistribution are allowed.
Paid distribution, paid hosting, SaaS offering, or any other paid offering
of this software or derivative works is prohibited.

--------------------------------------------------------------------------

# Encounter Fight Helper

Ein browserbasierter Encounter- und Kampf-Helper für Spielleitungen.  
Das Tool dient als kompakte **GM-Übersicht** für laufende Kämpfe und Szenen und konzentriert sich auf die Zustände, die während einer Runde schnell sichtbar und pflegbar sein müssen: **Initiative, Lebenspunkte, Attribute, Fähigkeiten, Items, aktive Effekte und Rundenzähler**.

Der Encounter Fight Helper ist nicht als vollständiger Regelsimulator gedacht, sondern als **praktisches Kampfboard für den Spieltisch**.

## Projektvarianten

Das Projekt existiert aktuell in zwei Regelvarianten:

### 1. E.H.-Version
Die ursprüngliche Version ist auf das **Elysium-Horizon-/projektinterne System** ausgelegt.

Im Fokus stehen dort unter anderem:

- **LP**
- **Geist**
- **Körper**
- **Charisma**
- Initiative auf Basis von **1W10 + Geist**
- kampforientierte Gegner- und Heldenkarten
- Status- und Effektverwaltung direkt auf den Karten
- Ausrüstungs- und Itemverwaltung mit „Angelegt“-Status

Diese Variante ist besonders dann nützlich, wenn das Encounter-Management eng an das bestehende E.H.-Regel- und Attributsystem angebunden sein soll.

### 2. HTBAH-Version
Die zweite Variante ist auf die allgemeinen Grundregeln von **How to be a Hero** ausgerichtet.

Hier liegt der Schwerpunkt auf:

- **LP**
- **Handeln**
- **Wissen**
- **Soziales**
- Initiative auf Basis von **1W10 + Handeln**
- Fähigkeiten nach HTBAH-orientierter Struktur
- HTBAH-bezogenen Schnellzugriffen auf Regelwerk und Referenzseiten

Diese Variante ist als pragmatische Kampf- und Spielleitungshilfe für HTBAH gedacht, ohne das gesamte Regelwerk 1:1 technisch nachzubauen.

## Ziel

Der Encounter Fight Helper soll Spielleitungen helfen,

- den aktuellen Kampfzustand schnell zu erfassen,
- mehrere Beteiligte gleichzeitig zu verwalten,
- Buffs, Debuffs und Zustände im Blick zu behalten,
- Items und Ausrüstung direkt an den Einheiten zu sehen,
- und ohne Medienbruch durch eine Kampfrunde zu führen.

Anstatt alle Regeln vollständig zu automatisieren, steht die **schnelle Übersicht im Encounter** im Vordergrund.

## Kernfunktionen

- visuelle **Initiative-Leiste** mit Rundenzähler
- Verwaltung von **Helden** und **Gegnern**
- **LP-Anzeige mit Lebensbalken**
- einklappbare Bereiche für:
  - **Attribute**
  - **Fähigkeiten**
  - **Items**
  - **Effekte**
- **Items mit „Angelegt“-Status**
- kompakte Anzeige angelegter Ausrüstung direkt auf der Karte
- **stackbare Effekte** mit mehreren Änderungen pro Effekt
- rundenbasierte Effektlogik mit automatischem Ablauf
- optionales Zurücksetzen von Werten auf **Basiswert / LP max**
- **Würfelsimulator**
- **Timer**
- **JSON-Import** für Helden und Gegner
- **Schnellzugriff** auf wichtige Regel- und Referenzseiten

## Design-Prinzip

Das Tool ist bewusst als **GM-Helfer** aufgebaut.

Es soll nicht jedes Detail des Regelsystems erzwingen, sondern im Kampf schnell beantworten:

- **Wer ist dran?**
- **Wie stehen die LP?**
- **Welche Effekte laufen gerade?**
- **Was ist angelegt?**
- **Welche Werte sind aktuell verändert?**
- **Wie lange hält ein Zustand noch an?**

Dadurch bleibt das Tool flexibel für:

- Hausregeln
- improvisierte Gegner
- vereinfachte Kampfwerte
- projektspezifische Systeme
- unterschiedliche Regelvarianten wie E.H. und HTBAH
