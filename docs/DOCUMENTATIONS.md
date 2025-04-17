# DOCUMENTATIONS.md

## FILE STRUCTURE

### ( annotations )
------------------
├ └ ─ │

### ( File structure | details )
-----------------------------
/project-root
├── README.md                # Project overview and instructions
├── requirements.txt         # Python dependencies



documentation
├── /docs                    # documents
├── /media                   # Image files

code
├── /chapter1_cli_and_setup      # The CLI and Web Framework
    ├── client.py                # The main client code
    ├── run.sh                   # Helper script to start code
    ├── sitevars.env             # .dotenv file for secrets
    ├── /core                    # main logic.  handles user command

    ├── /lib                     # custom python libraries

    ├── /templates               # HTML

    ├── /static
        ├── css/                 # stylesheets

        └── js/                  # javascript






├── /v1_class2
    ├── /lib
    ├── /templates
    ├── /static
        ├── css/                 # stylesheets
        └── js/                  # javascript

├── /v1_Final
    ├── /lib
    ├── /templates
    ├── /static
        ├── css/                 # stylesheets
        └── js/                  # javascript



# ---------------------------------------
# EXAMPLE
# ---------------------------------------
│   ├── raw/                 # Original unprocessed data files
│   ├── processed/           # Cleaned and structured data for analysis
│   └── archive/             # Old datasets stored for backup/reference
├── /scripts
│   ├── data_cleaning.py     # Script for cleaning raw data
│   ├── analysis.py          # Script for performing data analysis
│   └── visualization.py     # Script for generating graphs/charts
├── /notebooks
│   ├── EDA.ipynb            # Exploratory Data Analysis notebook
│   └── model_training.ipynb # Notebook for training machine learning models
└── /outputs
    ├── figures/             # Saved plots and visualizations
    └── reports/             # PDF or HTML reports generated from analysis
