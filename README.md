e-waste-sna-abm/
│
├── code/ # ABM and analysis source code
│ ├── step00_parameter_setup.py # Modified: Adds SNA parameters and Scenario 6
│ ├── step01_agent_behavior.py # Modified: Adds p_recv and rho attributes to ConsumerAgent
│ ├── step02_model_simulation.py # Modified: Applies SNA dampening and S6 targeting logic
│ ├── step03_scenario_analysis.py# Unmodified: Dynamic scenario analysis
│ ├── step04_statistical_analysis.py # Unmodified: Inferential statistics
│ ├── step05_sensitivity_analysis.py # Unmodified: Sensitivity analysis
│ └── SNA_Analysis.ipynb # Notebook: DEMATEL, BWM, and SNA metric computation
│
├── parameters/ # Parameter configuration files
│ ├── ABM_BASE_PARAMETERS.csv # Baseline parameter values
│ ├── ABM_PARAMETER_CONFIG.json # Authoritative parameter configuration
│ ├── ABM_SCENARIO_PARAMETERS.csv# Scenario-specific parameter adjustments
│ └── SNA_AGENT_PARAMETERS.csv # SNA-derived structural profiles for 100 agents
│
└── outputs/ # Benchmark simulation outputs
├── STEP02_RAW_SIMULATION_RESULTS.csv # Raw outputs for all 7 scenarios
└── SNA_METRICS_ALL.csv # Composite network metrics for 52 actors

