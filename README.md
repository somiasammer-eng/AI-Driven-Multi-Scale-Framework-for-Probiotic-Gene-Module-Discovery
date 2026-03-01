omplete Repository Structure:

probiotic-ai-framework/
├── README.md                    # Comprehensive overview and quick start
├── LICENSE                      # MIT license terms  
├── CITATION.cff                 # Citation metadata (CFF format)
├── INSTALL.md                   # Detailed installation guide
├── requirements.txt             # Python package dependencies
├── environment.yml              # Conda environment specification
├── Dockerfile                   # Docker container specification
├── .github/
│   ├── workflows/               # CI/CD automation (GitHub Actions)
│   ├── ISSUE_TEMPLATE.md       # Bug report template
│   └── CONTRIBUTING.md         # Contribution guidelines
├── src/
│   ├── probiotic_discovery/     # Main package
│   │   ├── annotation/          # Genome annotation pipeline
│   │   │   ├── prokka_wrapper.py
│   │   │   ├── rast_integration.py
│   │   │   └── consensus_annotation.py
│   │   ├── module_detection/    # Gene module identification
│   │   │   ├── module_finder.py
│   │   │   └── cooccurrence_analysis.py
│   │   ├── protein_analysis/    # PLM-based functional prediction
│   │   │   ├── esm2_embeddings.py
│   │   │   ├── prott5_analysis.py
│   │   │   ├── functional_prediction.py
│   │   │   └── benchmarking.py
│   │   ├── metabolic_modeling/  # GEM reconstruction and simulation
│   │   │   ├── model_builder.py
│   │   │   ├── matrix_constraints.py
│   │   │   └── flux_analysis.py
│   │   ├── ai_clustering/       # Machine learning pipeline
│   │   │   ├── graph_neural_networks.py
│   │   │   ├── variational_autoencoders.py
│   │   │   └── transformer_attention.py
│   │   ├── prediction/          # Host-interaction prediction
│   │   │   ├── feature_engineering.py
│   │   │   ├── ensemble_models.py
│   │   │   └── strain_ranking.py
│   │   └── visualization/       # Plotting and reporting
│   │       ├── figure_generation.py
│   │       └── interactive_plots.py
├── workflows/
│   ├── snakemake/              # Snakemake workflow management
│   ├── nextflow/               # Nextflow pipeline
│   └── scripts/                # Individual analysis scripts
├── tests/
│   ├── unit_tests/             # Individual function tests
│   ├── integration_tests/      # End-to-end pipeline tests
│   └── test_data/              # Small datasets for testing
├── docs/
│   ├── installation.md         # Setup instructions
│   ├── user_guide.md          # Step-by-step usage guide
│   ├── api_reference.md       # Function documentation
│   └── tutorials/             # Jupyter notebook tutorials
├── models/
│   ├── trained_classifiers/    # Pre-trained ML models
│   ├── protein_embeddings/     # PLM model weights
│   └── metabolic_templates/    # GEM templates
├── data/
│   ├── example_genomes/        # Sample input files
│   └── validation_sets/        # Benchmark datasets
└── examples/
    ├── quick_start.py          # 15-minute demo analysis
    ├── full_pipeline.py        # Complete analysis example
    └── custom_analysis.py      # Customization examples
