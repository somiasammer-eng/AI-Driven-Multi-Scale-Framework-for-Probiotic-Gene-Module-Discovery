probiotic-ai-framework/
│
├── pyproject.toml
├── README.md
├── LICENSE
├── CITATION.cff
├── INSTALL.md
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── MANUSCRIPT.md
│
├── .github/
│   ├── workflows/
│   │   ├── ci.yml
│   │   └── test.yml
│   │
│   ├── ISSUE_TEMPLATE.md
│   ├── PULL_REQUEST_TEMPLATE.md
│   └── FUNDING.yml
│
├── docs/
│   ├── installation.md
│   ├── user_guide.md
│   ├── api_reference.md
│   ├── troubleshooting.md
│   ├── performance_guide.md
│   └── tutorials/
│
├── src/
│   └── probiotic_discovery/
│       │
│       ├── __init__.py
│       ├── cli.py                          # (2) CLI ENTRY POINT
│       │
│       ├── core/
│       │   └── pipeline.py                # (1) MAIN PIPELINE
│       │
│       ├── annotation/
│       │   ├── prokka_wrapper.py         # (3) GENOME ANNOTATION
│       │   ├── kegg_mapper.py
│       │
│       ├── protein_analysis/
│       │   ├── esm2_embeddings.py        # (3) PROTEIN EMBEDDINGS
│       │   ├── functional_prediction.py
│       │   ├── benchmarking.py           # (4) VALIDATION
│       │
│       ├── module_detection/
│       │   ├── module_finder.py          # (3) GENE MODULE DETECTION
│       │   ├── cooccurrence_analysis.py
│       │
│       ├── metabolic_modeling/
│       │   ├── model_builder.py          # (3) METABOLIC VALIDATION
│       │   ├── flux_analysis.py
│       │
│       ├── prediction/
│       │   ├── feature_engineering.py    # (3) ML PIPELINE
│       │   ├── ensemble_models.py
│       │   ├── strain_ranking.py
│       │   ├── cross_validation.py       # (4) VALIDATION
│       │
│       ├── visualization/
│       │   ├── figure_generation.py
│       │   └── report_builder.py
│       │
│       └── utils/
│           ├── data_processing.py        # (5) UTILITIES
│           ├── file_io.py
│           └── logging_config.py
│
├── tests/
│   ├── test_pipeline.py
│   ├── test_prediction.py
│   └── test_imports.py
│
├── data/
│   ├── example_genomes/
│   ├── reference_databases/
│   └── validation_sets/
│
├── results/
│   ├── example_run/
│   └── validation/
│
└── environment/
    ├── requirements.txt
    ├── conda_env.yml
    └── Dockerfile
