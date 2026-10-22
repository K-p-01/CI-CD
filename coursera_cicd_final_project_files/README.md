# OpenShift CI/CD Sample Application

## Project overview
This repository demonstrates a CI/CD workflow for a sample application using GitHub Actions, Tekton, and Red Hat OpenShift.

## Required submission paths
- `README.md`
- `.github/workflows/workflow.yml`
- `.tekton/tasks.yml`

## Run checks locally
```bash
python -m pip install -r requirements.txt
flake8 .
nosetests
```

> Keep the original sample application's source files. Adapt the starter configuration to the exact lab instructions and your application's test commands. Do not report success until the workflow and pipeline actually pass.
