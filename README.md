# Qiskit Workshop (Binder Ready)

English | Deutsch weiter unten

## Launch on Binder
Generic launch (opens JupyterLab file browser; user chooses a notebook):

```
https://mybinder.org/v2/gh/<YOUR_GITHUB_USERNAME>/<YOUR_REPO_NAME>/HEAD
```

Badge Markdown:

```
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/<YOUR_GITHUB_USERNAME>/<YOUR_REPO_NAME>/HEAD)
```

Available notebooks (select after launch):
- `qiskit_workshop_demo_blanks.ipynb`
- `qiskit_workshop_demo_solution.ipynb`

## Repository Files
- `requirements.txt` minimal dependency list (qiskit, aer, matplotlib, pylatexenc)
- (Optional) add a `runtime.txt` if you want to pin Python later
- Notebooks: blanks + solution

## Local Use (Optional)
```
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
jupyter lab
```

---

## Start auf Binder (Deutsch)
Generischer Start (öffnet JupyterLab Datei-Browser; Benutzer wählt Notebook):

```
https://mybinder.org/v2/gh/<IHR_GITHUB_USERNAME>/<IHR_REPO_NAME>/HEAD
```

Badge:
```
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/<IHR_GITHUB_USERNAME>/<IHR_REPO_NAME>/HEAD)
```

Verfügbare Notebooks (nach Start auswählen):
- `qiskit_workshop_demo_blanks.ipynb`
- `qiskit_workshop_demo_solution.ipynb`

## Dateien
- `requirements.txt` Abhängigkeiten

## Lokal (optional)
```
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
jupyter lab
```

Viel Erfolg!
