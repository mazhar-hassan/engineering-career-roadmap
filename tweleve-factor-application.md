
# 12 Factor application
1. Codebase: One codebase (revision controlled) for deployed service    
    * All provisioning scripts should be part of the repository
    * Source code shoudl be part of a repository
    * Version control of the configuration

2. Dependencies: All dependecies should be declared explicitly (Don't assume anything)
3. Config: Configuraton must be maintained separate of the code and should be injected by the environement on which build is running.
4. Backing services: 