elastic-security-portfolio/
├── docs/                    # Guides, architecture diagrams, screenshots, and usage notes
│   └── setup.md             # (planned) Full lab deployment walkthrough
├── elasticsearch/           # Core Elastic configurations (exported via Kibana/Dev Tools)
│   ├── ingest-pipelines/    # Custom ingest processors (geoip, threat intel, normalization, drop filters)
│   ├── index-templates/     # Component + index templates (mappings, settings, ILM bindings)
│   ├── ilm-policies/        # Hot/warm/cold/delete policies with rollover and retention examples
│   ├── detection-rules/     # Custom KQL/ES|QL rules, ML jobs, threshold rules (YAML exports)
│   └── saved-objects/       # Exported Kibana dashboards, searches, visualizations
├── scripts/                 # Python/Bash automation (e.g., threat intel feed ingestion, rule testing)
├── LICENSE                  # MIT License
└── README.md                # This file
