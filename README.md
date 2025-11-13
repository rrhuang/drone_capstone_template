# drone_capstone_template

Drone Project

[Insert your summary of the capstone here]
---

## Prerequisites

- Python **3.9+**
- `curl` or `pip` (for installing `uv`)
- Git (to clone the repo)

---

## Setup Instructions

### 1. Install `uv`

#### Option A — Recommended (direct installer)
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

#### Option B - Using pip

```pip install uv```


### 2. Setup workflow

```
uv init drone-project
cd drone-project
uv add numpy scipy fastapi opencv-python
uv run python src/drone_project/main.py
```
