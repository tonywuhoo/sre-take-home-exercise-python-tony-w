# Endpoint Availability Checker

This Python tool checks the availability of HTTP endpoints defined in a YAML configuration file.  
Endpoints are considered available if they return a **2xx status code** and respond in **under 500 milliseconds**.

Availability is tracked cumulatively over time and logged every **15 seconds** by domain (ignoring port numbers).

---

## Requirements

- Python **3.8 or higher**
- `requests` (HTTP client library)
- `PyYAML` (YAML parsing library)

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Setup Instructions

### 1. Clone the Repository

```bash
git clone <your_repo_url_here>
cd <your_repo_directory>
```

### 2. Set Up Virtual Environment

#### Unix (Mac/Linux)

```bash
python3 -m venv .venv
source .venv/bin/activate
```

#### Windows (PowerShell)

```bash
python -m venv .venv
.venv\Scripts\Activate
```

---

## Usage

Run the checker by specifying your configuration YAML:

```bash
python3 main.py sample.yml
```

Example:

```bash
python3 main.py sample.yaml
```

---

## Notes

- Endpoints are evaluated based on:
  - Successful 2xx HTTP responses
  - Response times under 500 milliseconds
- Results are **logged every 15 seconds** grouped by domain.
