# Credit Risk Analytics Dashboard | Power BI Portfolio Project

Dieses Projekt zeigt ein **Power-BI-Dashboard zur Analyse von Kreditrisiko, Portfolioqualität und Business-Impact**. Es ist als Portfolio-Projekt für Data-Analyst-, BI-Analyst- und Financial-Services-Analytics-Rollen aufgebaut.

## Projektziel

Das Dashboard unterstützt ein fiktives Finanzunternehmen dabei, Kreditentscheidungen und Portfoliorisiken besser zu verstehen.

Zentrale Fragen:

- Wie hoch ist die Ausfallquote im Kreditportfolio?
- Welche Kundengruppen zeigen erhöhtes Risiko?
- Wie unterscheiden sich genehmigte und abgelehnte Anträge?
- Welche Faktoren beeinflussen Score, Approval und Default?
- Wie wirken sich Risiko und Genehmigungen auf Profitabilität aus?

## Repository-Inhalt

```text
credit-risk-powerbi-portfolio/
├── dashboard/
│   └── credit_risk_TEMPLATE.pbix
├── data/
│   ├── raw/
│   └── sample/
│       └── sample_credit_risk_data.csv
├── docs/
│   ├── data_dictionary.md
│   ├── dax_measures.md
│   ├── business_case.md
│   └── github_upload_guide_mac.md
├── images/
│   └── add_dashboard_screenshots_here.md
├── assets/
├── .gitignore
├── LICENSE
└── README.md
```

## Tools

- Power BI Desktop
- DAX
- Power Query
- CSV Data
- Git / GitHub

## Dashboard-Datei

Die Power-BI-Datei befindet sich hier:

```text
dashboard/credit_risk_TEMPLATE.pbix
```

> Hinweis für macOS: Power BI Desktop läuft offiziell nicht nativ auf macOS. Du kannst es über Windows VM, Parallels, Remote Windows-PC oder Power BI Service nutzen.

## Beispiel-Datensatz

Ein synthetischer Beispieldatensatz liegt hier:

```text
data/sample/sample_credit_risk_data.csv
```

Die Daten sind künstlich generiert und enthalten keine echten personenbezogenen Daten.

## Wichtige KPIs

- Default Rate
- Approval Rate
- Average Credit Score
- Total Revenue
- Total Cost
- Estimated Profit
- Debt-to-Income Ratio
- Late Payment Distribution
- Portfolio Profitability

## Projekt-Highlights

- Kreditrisiko-Analyse
- Approval- und Default-Auswertung
- Segmentanalyse nach Region und Beschäftigungsstatus
- Profitabilitätsanalyse
- Business-orientierte Interpretation
- Portfolio-taugliche Repository-Struktur

## Screenshots

Bitte exportiere nach dem Öffnen des Dashboards Screenshots aus Power BI und speichere sie in `images/`.

Empfohlene Dateien:

```text
images/overview.png
images/risk_analysis.png
images/customer_segments.png
images/profitability.png
```

Danach kannst du sie hier einbinden:

```markdown
![Dashboard Overview](images/overview.png)
```

## Business Interpretation

Dieses Projekt ist besonders relevant für:

- Banken
- Kreditinstitute
- Fintechs
- Versicherungen mit Risikomodellen
- Financial-Services-Analytics

## Weiterentwicklungsideen

- SQL-Datenbank als Quelle ergänzen
- Python-Modell zur Default-Prognose anbinden
- Power-BI-Parameter für flexible Kundendaten einbauen
- PDF-Management-Report ergänzen
- Deployment im Power BI Service
- Row-Level Security für Kundengruppen

## Autor

Dieses Projekt wurde als Portfolio-Projekt für Financial Analytics und Business Intelligence erstellt.
