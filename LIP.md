# Das LONOR Improvement Proposal (LIP) Protokoll

## Was ist ein LIP?

Ein LONOR Improvement Proposal (LIP) ist der formale, transparente und von der Gemeinschaft getragene Prozess, um **fundamentale, strategische Änderungen am LONOR-Protokoll** vorzuschlagen, zu diskutieren und zu ratifizieren.

Es ist das primäre Werkzeug unserer dezentralen Governance. Ein LIP wird immer dann benötigt, wenn eine vorgeschlagene Änderung die "Verfassung" unseres Universums berührt. Dies umfasst unter anderem:

* Änderungen an der Kern-Architektur oder den API-Spezifikationen.
* Die Aufnahme eines neuen "Kreises" in die Ontologie des `Ground-Truth`.
* Signifikante Anpassungen an der `$KOR`-Tokenomics.
* Änderungen an den Governance-Regeln der `LONOR-DAO` selbst.

Für die taktische Umsetzung bereits beschlossener Aufgaben ("Quests") nutzen wir das schlankere **Quest-Implementierungs-Protokoll (QIP)**.

## Der Weg einer Idee zur kanonischen Wahrheit

Jedes LIP durchläuft einen rigorosen, mehrstufigen Prozess, der sicherstellt, dass jede Änderung an LONOR wohlüberlegt, von der Gilde geprüft und von der `DAO` legitimiert ist.

**Phase 1: Der Funke (Informelle Diskussion)**
Eine Idee für ein LIP wird zuerst informell in den relevanten Kanälen unseres Discord-Servers diskutiert. Hier wird im "Schmiedefeuer der Gilde" geprüft, ob die Idee auf Resonanz stößt und das Potenzial für einen formalen Vorschlag hat.

**Phase 2: Der Entwurf (Das formale LIP)**
Hat die Idee Substanz, verfasst ein "LIP-Champion" (ein oder mehrere Gildenmitglieder) einen formalen Entwurf nach der untenstehenden Vorlage. Dieser Entwurf wird als Pull Request in unserem `lonor-protokoll/lips`-Repository eingereicht.

**Phase 3: Das Schmiedefeuer (Peer-Review)**
Der eingereichte Entwurf wird von der gesamten Gilde intensiv diskutiert. Kommentare, Kritik und Verbesserungsvorschläge werden direkt im Pull Request gemacht. Der Champion überarbeitet das LIP, bis es einen reifen, konsensfähigen Zustand erreicht hat.

**Phase 4: Der Ratsbeschluss (Die `DAO`-Abstimmung)**
Das finale, ausgereifte LIP wird der `LONOR-DAO` zur offiziellen On-Chain-Abstimmung vorgelegt. Die `$KOR`-Token-Inhaber entscheiden über die Annahme oder Ablehnung des Vorschlags.

**Phase 5: Die Chronik (Das Ergebnis)**
Das Ergebnis der Abstimmung ist final. Das LIP erhält den Status "Angenommen" oder "Verworfen". Angenommene LIPs werden in die offizielle Roadmap aufgenommen und als Quest(s) auf dem Quest-Board für die Umsetzung eingeplant.

## Die Anatomie eines Vorschlags (Die LIP-Vorlage)

Jedes LIP muss der folgenden, standardisierten Struktur folgen, um Klarheit und Vergleichbarkeit zu gewährleisten.

Vorlage:


--
LIP: [Nummer wird vom Kernteam vergeben] 
Titel: [Ein kurzer, prägnanter Titel der Änderung] 
Autor*in: [Dein Name / Deine Gilden-ID] 
Status: Entwurf | Review | Abstimmung | Angenommen | Final | Verworfen 
Datum: YYYY-MM-DD

### Zusammenfassung (Abstract)

Eine kurze, ein- bis zwei Sätze lange Zusammenfassung des Vorschlags.

### Motivation (Das "Warum")

Eine detaillierte Beschreibung des Problems, das dieses LIP löst, oder der Chance, die es eröffnet.

### Spezifikation (Das "Was & Wie")

Die genaue, technische und/oder konzeptionelle Beschreibung der vorgeschlagenen Änderung. Dies ist der Kern des Dokuments.

### Begründung (Rationale)

Eine Erklärung, warum dieser spezifische Lösungsansatz gewählt wurde und welche Alternativen in Betracht gezogen und verworfen wurden.

### Risiken & Konsequenzen

Eine ehrliche Analyse der potenziellen negativen Auswirkungen, Risiken oder unbeabsichtigten Konsequenzen, die diese Änderung haben könnte.

### Abwärtskompatibilität

Eine Beschreibung, wie sich diese Änderung auf bestehende Systeme, APIs oder den `Ground-Truth` auswirkt und ob sie zu "Breaking Changes" führt.
