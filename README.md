# LONOR – Das Protokoll für ein Internet der Konsequenzen

> Nervt dich das Internet? Uns auch.
> Deshalb bauen wir einen Ort, an dem du nicht *für* eine Vision arbeitest, sondern deine *eigene* verwirklichst.

---

## Was ist LONOR?

LONOR ist ein dezentrales Protokoll, das darauf abzielt, das Ordnungsprinzip des Internets vom **Hyperlink zur Kausalität** zu verschieben. Als transparentes Denkmodell, geschaffen in **Mensch-KI-Symbiose**, dient es als Kommunikationsbrücke zwischen menschlicher Intention und maschineller Logik, um die "Black-Box"-Systeme der heutigen KI zu überwinden.

Unsere vollständige Vision, die Roadmap und die Gilden-Regeln finden Sie in unserem öffentlichen **[Notion-Workspace](https://harmonious-pineapple-7b1.notion.site/1f426acf759180708b53c1688627afb3?v=1f426acf7591801091ec000cacc201ce&pvs=141](https://harmonious-pineapple-7b1.notion.site/1f426acf759180708b53c1688627afb3?v=1f426acf7591801091ec000cacc201ce&pvs=141))**.


## Status des Projekts

**Phase: 1 (Die Gründung)**

LONOR befindet sich in einer frühen, aber entscheidenden Phase. Das Fundament ist gelegt:

* **Der `Ground-Truth` v1.0:** Das normative Kern-Universum, bestehend aus über 1.175 `.md`-Dateien, ist fertiggestellt.
* **Der Bauplan:** Die vollständige technische, ökonomische und philosophische Architektur ist in über 60 Kerndokumenten ausformuliert.

Unser aktueller Fokus liegt auf der Entwicklung der ersten, fundamentalen Werkzeuge:

1.  **Der `Parser`:** Das Werkzeug, um den `Ground-Truth` maschinenlesbar zu machen.
2.  **Der `Kohärenz-Auditor`:** Das Werkzeug, um die logische Integrität des `Ground-Truth` mathematisch zu beweisen.
3.  **Die `Gilden-Plattform`:** Das Betriebssystem für unsere Gemeinschaft.

## Wie kann ich mitmachen?

LONOR ist ein Projekt, das von seiner Gemeinschaft lebt. Wir suchen keine Mitarbeiter, wir suchen Mit-Architekten. Der beste Weg, um anzufangen, ist:

1.  **Lesen Sie unseren Bauplan:** Tauchen Sie in unseren **[Notion-Workspace](https://harmonious-pineapple-7b1.notion.site/1f426acf759180708b53c1688627afb3?v=1f426acf7591801091ec000cacc201ce&pvs=141](https://harmonious-pineapple-7b1.notion.site/1f426acf759180708b53c1688627afb3?v=1f426acf7591801091ec000cacc201ce&pvs=141))** ein, um unsere Vision wirklich zu verstehen.
2.  **Treten Sie der Gilde bei:** Kommen Sie auf unseren **[Discord-Server](https://discord.gg/FB3fBSEe)**, stellen Sie sich vor und werden Sie Teil des Dialogs.
3.  **Lesen Sie die `CONTRIBUTING.md`:** Dieses Dokument erklärt im Detail, wie Sie an Quests teilnehmen, LIPs/QIPs einreichen und Teil der Bewegung werden können.

## Die Architektur im Überblick

```mermaid
graph TD
    subgraph "Schicht 5: ANWENDUNG"
        UI[Map, Vault, Chat]
    end
    subgraph "Schicht 4: API"
        API[LONOR API / FastAPI]
    end
    subgraph "Schicht 3: INFERENZ & KURATION"
        INFERENZ[Inferenz-Maschine]
        KURATION[Kurations-Maschine]
    end
    subgraph "Schicht 2: SPEICHERUNG"
        NEO4J[(Neo4j Graphendatenbank)]
        WEAVIATE[(Weaviate Vektordatenbank)]
    end
    subgraph "Schicht 1: QUELLE DER WAHRHEIT"
        MD[[.md-Dateien / Ground-Truth]]
    end

    UI --> API
    API --> INFERENZ
    API --> KURATION
    INFERENZ --> NEO4J & WEAVIATE
    KURATION --> NEO4J & WEAVIATE
    NEO4J & WEAVIATE --- MD
