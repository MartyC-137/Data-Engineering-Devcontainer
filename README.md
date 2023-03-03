# A development environment for data engineers
A devcontainer for Data Engineers that sets up a development environment with tools such as Python, Terraform, dbt, Jupyter Notebooks for VS Code, the Snowflake extension for VS Code, and the SQL Server extension. This can be used with both VS Code and GitHub Codespaces.

## Getting Started
To continue, make sure you have [Docker Desktop](https://www.docker.com/products/docker-desktop/) installed OR use GitHub Codespaces.

**Option 1: Local VS Code**

1. Clone the repo and connect to it in VS Code:

```bash
$ cd your/desired/repo/location
$ git clone https://github.com/MartyC-137/DataEng_devcontainer
```

1. Download the `Dev Containers` extension from the VS Code marketplace

2. Press Cmd + Shift + P (Mac) or Ctrl + Shift + P (Windows) to open the Command Pallette. Type in `Dev Containers: Open Folder in Container` and select the repo directory.
   
3. Wait for the container to build and the dependencies to install
   
**Option 2: GitHub Codespaces**

1. Fork this repo
   
2. From the repo page in GitHub, select the green `<> Code` button and choose Codespaces
   
3. Click `Create Codespace on Main`, or checkout a branch if you prefer
   
4. Wait for the container to build and the dependencies to install
   
5. Start developing!


## Included Tools and Languages:

* `Python 3.9`
  - `Pandas`
  - `SQLAlchemy`
  - `PySpark`
  - `PyArrow`
  - `Polars`
  - `Prefect` and all required Python dependencies
  - `confluent-kafka`
  - `scikit-learn`
  - `Snowpark`
  - `ipykernel`
* `Google Cloud SDK`
* `Azure` CLI
* `GitHub` CLI
* `GitLens`
* `GitHub` Pull Requests
* `dbt-core`
  - `dbt-postgres`
  - `dbt-bigquery`
* `dbt` extensions for VS Code
* `Snowflake` for VS Code
* `MS SQL Server` for VS Code
* `Terraform`
* `Jupyter Notebooks` for VS Code
* `Docker`
* `Spark`
* `JDK` version 11
* `XML` tools
* `YAML` tools
* [`Oh-My-Posh Powershell themes`](https://github.com/JanDeDobbeleer/oh-my-posh)
* Popular VS Code themes (GitHub, Atom One, Material Icons etc.)

## Customization
Feel free to modify the `Dockerfile`, `devcontainer.json` or `requirements.txt` file to include any other tools or packages that you need for your development environment.

## Contributing
If you'd like to contribute to this project, please open a pull request and I'll review it as soon as possible.