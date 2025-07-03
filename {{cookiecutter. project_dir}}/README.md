<a id="readme-top"></a>
<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#{{ cookiecutter.project_name.lower().replace(' ', '-').replace('_', '-') }}">{{ cookiecutter.project_name }}</a>
    </li>
    <li><a href="#author">Author</a></li>
    <li><a href="#key-users">Key Users</a></li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#setup-environment">Setup Environment</a></li>
        <li><a href="#running">Running</a></li>
      </ul>
    </li>
    <li><a href="#key-users">Key Users</a></li>
    <li><a href="#azureml-infos">AzureML Infos</a></li>
    <li><a href="#data">Data</a></li>
    <li><a href="#datafactory-pipeline">DataFactory Pipeline</a></li>
    <li><a href="#structure">Structure</a></li>
  </ol>
</details>


# {{ cookiecutter.project_name }}

{{ cookiecutter.project_desc }}

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Author

- [{{ cookiecutter.full_name }}]({{ cookiecutter.email }})


<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Key Users

- [Nome](email)
- [Nome](email)
- [Nome](email)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### AzureML Infos
```
Workspace: **TODO** 
Job Pipeline: **TODO** 
Custom Environment: **TODO** 
Pipeline Endpoint: **TODO** 
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Data

```
**TODO**
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### DataFactory Pipeline
```
**TODO**
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Structure

```
.
├── LICENSE                     <- Open-source license if one is chosen
├── README.md                   <- The top-level README for developers using this project
│
├── data
│   ├── external                <- Data from third-party sources (e.g., downloaded, scraped)
│   ├── interim                 <- Intermediate data that has been transformed (e.g., cleaned, merged)
│   ├── processed               <- The final, canonical data sets ready for modeling
│   └── raw                     <- The original, immutable data dumps (never modify these)
│
├── notebooks                   <- Jupyter notebooks for development, exploration, and analysis
│   ├── eda                     <- Exploratory Data Analysis (EDA) notebooks
│   ├── postprocessing          <- Notebooks for model output refinement and analysis
│   ├── preprocessing           <- Notebooks for data cleaning, transformation, and feature engineering
│   ├── training                <- Notebooks focused on model training and evaluation
│   └── utils                   <- Utility notebooks with reusable snippets or functions
│
├── pipe                        <- Custom data processing or ML pipelines
│   └── utils                   <- Reusable utility functions or modules for pipeline steps
│
├── references                  <- Data dictionaries, manuals, academic papers, and other explanatory materials
│
├── release                     <- Files related to project releases (e.g., deployment scripts, release notes)
│
├── reports                     <- Generated analysis reports, presentations, or static outputs
│   └── figures                 <- Generated graphics and figures to be used in reports
│
└── src                         <- Source code for this project
    │
    ├── config                  <- Configuration files and environment settings
    │   └── pipe_env            <- Environment-specific configurations for pipelines or services
    │
    ├── modeling                <- Code for machine learning models (training, prediction, evaluation)
    │
    └── services                <- Service classes to connect with external platforms, tools, or APIs
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>


