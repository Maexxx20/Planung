**Sentiment-Analysetool für Märkte**

_Erstellung einer robusten Analyseplattform für Marktstimmungen auf Basis von Social-Media- und Nachrichten-Quellen_

Dies ist die Dokumentation unseres Sentiment-Analysetools, welches Marktstimmungen anhand von Textdaten aus Social Media (z. B. X) sowie Nachrichtenartikeln identifiziert, bewertet.

**Systemarchitektur und Funktionsumfang**

**Hauptfunktionen:**

*   **Datenerhebung:** Sammeln von Textdaten aus sozialen Netzwerken und Nachrichtenquellen (Tweets, Schlagzeilen, Artikelabschnitte).
*   **Sentiment-Analyse:** Ermittlung von Stimmungswerten (negativ bis positiv) mithilfe Machine-Learning-Modellen.
*   **Datenspeicherung:** Persistente Ablage der Ergebnisse in einer Datenbank (Historisierung für Trendanalysen).
*   **Empfehlungssystem:** Auf Basis der aktuellen Marktstimmung generierte Handlungsempfehlungen.

**Technologiestack**

**1\. Entwicklungsumgebung**

*   **Programmiersprache:** C#
*   **IDE:** Visual Studio und JetBrains Rider
*   **Projekttyp:** .NET Core Konsolenanwendung

**2\. Web Scraping**

*   Nutzen von APIs aus Social Media Apps wie X (ehemals Twitter) oder der Finanzplattform Alpaca.

**3\. Datenbankspeicherung**

*   **Datenbank:** SQLite für eine leichte, portable Lösung

**4\. Frontend**

*   **Framework (Optionen):**
    *   WPF (Windows Presentation Foundation) für Desktop-Anwendungen
    *   Wir belassen es bei Konsolen

**Zeitaufwand und Komplexität**

*   **Prototyp (Grundfunktionalität):** ca. 2-4 Wochen
*   **Vollständige Implementierung (Produktionsreife):** ca. 1-2 Monate
*   **Kontinuierliche Verbesserung & Wartung:** fortlaufend

*   **Entwicklungskosten:** Hauptsächlich Personalkosten für Entwickler
*   **API-Kosten:** Abhängig von den genutzten Datenquellen und deren Preismodellen
