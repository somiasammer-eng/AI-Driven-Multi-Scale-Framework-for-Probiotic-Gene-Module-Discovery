probiotic-ai-framework/
├── README.md                     # Comprehensive overview and quick start
├── LICENSE                       # MIT license terms
├── CITATION.cff                  # Citation metadata (CFF format)
├── INSTALL.md                    # Detailed installation instructions
├── CHANGELOG.md                  # Version history and updates
├── CODE_OF_CONDUCT.md           # Community guidelines
├── CONTRIBUTING.md              # Contribution instructions
├── .github/
│   ├── workflows/               # CI/CD automation (GitHub Actions)
│   ├── ISSUE_TEMPLATE.md       # Standardized bug reports
│   ├── PULL_REQUEST_TEMPLATE.md # PR guidelines
│   └── FUNDING.yml             # Funding information
├── docs/
│   ├── installation.md         # Step-by-step setup guide
│   ├── user_guide.md          # Comprehensive usage documentation
│   ├── api_reference.md       # Complete function documentation
│   ├── tutorials/             # Jupyter notebook tutorials
│   ├── examples/              # Example analyses and use cases
│   ├── troubleshooting.md     # Common issues and solutions
│   └── performance_guide.md   # Optimization recommendations
├── src/
│   ├── probiotic_discovery/   # Main package
│   │   ├── __init__.py
│   │   ├── annotation/        # Genome annotation pipeline
│   │   │   ├── prokka_wrapper.py
│   │   │   ├── rast_integration.py
│   │   │   ├── kegg_mapper.py
│   │   │   └── consensus_annotation.py
│   │   ├── module_detection/  # Gene module identification
│   │   │   ├── module_finder.py
│   │   │   ├── cooccurrence_analysis.py
│   │   │   └── validation.py
│   │   ├── protein_analysis/  # PLM-based prediction
│   │   │   ├── esm2_embeddings.py
│   │   │   ├── prott5_analysis.py
│   │   │   ├── functional_prediction.py
│   │   │   └── benchmarking.py
│   │   ├── metabolic_modeling/# GEM reconstruction and simulation
│   │   │   ├── model_builder.py
│   │   │   ├── matrix_constraints.py
│   │   │   ├── flux_analysis.py
│   │   │   └── validation.py
│   │   ├── ai_clustering/     # Machine learning pipeline
│   │   │   ├── graph_neural_networks.py
│   │   │   ├── variational_autoencoders.py
│   │   │   ├── transformer_attention.py
│   │   │   └── umap_visualization.py
│   │   ├── prediction/        # Host-interaction prediction
│   │   │   ├── feature_engineering.py
│   │   │   ├── ensemble_models.py
│   │   │   ├── cross_validation.py
│   │   │   └── strain_ranking.py
│   │   ├── visualization/     # Plotting and reporting
│   │   │   ├── figure_generation.py
│   │   │   ├── interactive_plots.py
│   │   │   └── report_builder.py
│   │   └── utils/            # Utility functions
│   │       ├── data_processing.py
│   │       ├── file_io.py
│   │       ├── statistics.py
│   │       └── logging_config.py
├── tests/
│   ├── unit_tests/           # Individual function tests
│   ├── integration_tests/    # End-to-end pipeline tests
│   ├── performance_tests/    # Speed and memory benchmarks
│   └── test_data/           # Small datasets for testing
├── data/
│   ├── example_genomes/      # Sample input files
│   ├── reference_databases/  # Curated annotation databases
│   ├── validation_sets/      # Benchmark datasets
│   └── metadata/            # Dataset descriptions
├── models/
│   ├── trained_classifiers/  # Pre-trained ML models
│   ├── protein_embeddings/   # PLM model weights
│   ├── metabolic_templates/  # GEM templates
│   └── model_documentation/ # Model descriptions and performance
├── workflows/
│   ├── snakemake/           # Snakemake workflow files
│   ├── nextflow/            # Nextflow pipeline
│   ├── cwl/                 # Common Workflow Language
│   └── docker/              # Containerization files
├── environment/
│   ├── requirements.txt     # Python dependencies
│   ├── conda_env.yml       # Conda environment
│   ├── Dockerfile          # Docker container
│   └── singularity.def    # Singularity container
└── results/
    ├── manuscript_figures/  # Reproducible figure generation
    ├── supplementary_data/ # Additional analysis results
    ├── benchmarks/         # Performance comparison data
    └── validation_results/ # Experimental confirmation data
