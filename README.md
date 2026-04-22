# climate-challenge-week0

Week 0 repository for the African Climate Trend Analysis challenge.

## Environment Setup

1. Create and activate a virtual environment:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

## Project Structure

```text
.
├── .github/workflows/ci.yml
├── .gitignore
├── README.md
├── requirements.txt
├── notebooks/
├── scripts/
├── src/
└── tests/
```

## Notes

- Raw and cleaned data files should stay inside `data/` and must not be committed.
- Use feature branches such as `setup-task`, `eda-ethiopia`, and `compare-countries`.
