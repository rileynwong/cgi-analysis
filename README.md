# Collective Governance: SCCS CGI Analysis

Notebook for collective governance analysis. Covers:

1. **Governance features × outcomes**: correlations within 28 CGI communities
2. **Clustering**: whether communities form distinct governance types
3. **CGI vs non-CGI**: outcome comparisons across 70 communities, including within-region tests

## View or run online

- **View** (read-only): [nbviewer](https://nbviewer.org/github/rileynwong/cgi-analysis/blob/main/CGI_Replication_Manual.ipynb)
- **Run** in the browser: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/rileynwong/cgi-analysis/main?labpath=CGI_Replication_Manual.ipynb)

## Files

| File | Description |
|---|---|
| `CGI_Replication_Manual.ipynb` | Analysis notebook |
| `SCCS_CGI_recoded_v6.xlsx` | 28 CGI communities: governance features and outcomes |
| `SCCS_CGI_70_recoded_v1.xlsx` | 70 communities (CGI and non-CGI): outcomes |
| `figures/` | Saved figures (`BOOK_` = for the book, `APPENDIX_` = supplementary) |
| `requirements.txt` | Python packages |

## Setup

Requires Python 3.10 or newer.

```bash
git clone https://github.com/rileynwong/cgi-analysis.git
cd cgi-analysis

python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Run

```bash
source .venv/bin/activate
jupyter notebook CGI_Replication_Manual.ipynb
```

To run all cells: Kernel -> Restart & Run All. 
Figures are saved to `figures/`.
