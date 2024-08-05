# Kidney-Disease-Classification-MLflow-DVC

This repository contains the workflow for Kidney Disease Classification using MLflow and DVC for managing machine learning experiments and data versioning.

## Workflows

1. **Update `config.yaml`**
2. **Update `secrets.yaml`** [Optional]
3. **Update `params.yaml`**
4. **Update the entity**
5. **Update the configuration manager in `src/config`**
6. **Update the components**
7. **Update the pipeline**
8. **Update `main.py`**
9. **Update `dvc.yaml`**
10. **Update `app.py`**

## How to Run?

### Steps:

1. **STEP 01** - Create a conda environment after opening the repository:

    ```bash
    conda create -n kidney-app python=3.10 -y
    ```

    Activate the environment:

    ```bash
    conda activate kidney-app
    ```

2. **STEP 02** - Install the requirements:

    ```bash
    pip install -r requirements.txt
    ```

3. Finally, run the following command to start the application:

    ```bash
    python app.py
    ```

4. Open your local host and port to access the application.

## MLflow

- [MLflow Documentation](https://mlflow.org/docs/latest/index.html)
- [MLflow Tutorial](https://youtu.be/qdcHHrsXA48?si=bD5vDS60akNphkem)

### MLflow Commands

To start the MLflow UI:

```bash
mlflow ui
