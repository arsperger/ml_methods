# Solutions — Intro to ML

solutions for the **Machine Learning** course.

## Contents

| File | Topic |
|------|-------|
| `hw1_solution.ipynb` | Classification (Adult Census Income) |
| `hw2_solution.ipynb` | Regression, Losses & Metrics (Auto MPG) |
| `hw1_doc.md` | Documentation for HW1 |
| `hw2_doc.md` | Documentation for HW2 |
| `hw_projects.md` | ML project ideas |

## Setup

```bash
uv venv --python 3.10
source .venv/bin/activate
uv pip install pandas numpy matplotlib seaborn scikit-learn datasets scipy ipykernel
python -m ipykernel install --user --name .venv
```

Open any `.ipynb` in VS Code and select the `.venv` kernel.
