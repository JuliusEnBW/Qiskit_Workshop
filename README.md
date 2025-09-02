# Qiskit Workshop (Binder Ready)

Deutsch (unten) | English (below)

> Fokus: Ein leicht erfassbares Notebook zum Einstieg in Qubits, Messung, einfache Gate-Manipulation und CNOT (CX) Wahrheitstabelle – komplett lauffähig auf Binder.

## 🚀 Quick Launch (Binder)
Direkt das Notebook öffnen (empfohlen):

https://mybinder.org/v2/gh/JuliusEnBW/Qiskit_Workshop/HEAD?labpath=qiskit_workshop_demo_blanks.ipynb

Badge (generisch auf Repo):

```
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/JuliusEnBW/Qiskit_Workshop/HEAD)
```

## 📓 Notebook Inhalt (Kurz)
`qiskit_workshop_demo_blanks.ipynb`

| Kapitel | Thema | Kernideen |
|---------|-------|-----------|
| 1 | Einzel-Qubit Messung | Hadamard → Superposition, Histogramm, Shots |
| 2 | Messergebnis beeinflussen | X (deterministisch), RY(θ) (Wahrscheinlichkeit), H–Z–H (Phase) |
| 3 | CNOT (CX) | Wahrheitstabelle, Simulation aller 4 Eingaben, Circuit-Diagramme, gemeinsames Histogramm |

Optional erweiterbar um: Bell-State, Bloch-Sphäre, weitere Mehr-Qubit-Gatter.

## 🗂 Repository Struktur
| Datei | Zweck |
|-------|------|
| `qiskit_workshop_demo_blanks.ipynb` | Haupt-Workshop-Notebook (Deutsch) |
| `requirements.txt` | Minimal benötigte Pakete (qiskit, qiskit-aer, matplotlib, pylatexenc) |
| `README.md` | Diese Anleitung |

> Hinweis: Eine frühere Referenz auf ein *solution*-Notebook wurde entfernt, da aktuell nur ein Arbeits-Notebook vorliegt.

## 💻 Lokal ausführen
```powershell
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
jupyter lab
```

Falls Jupyter nicht installiert ist: `pip install jupyterlab`.

---

## 🇩🇪 Deutsch






### Inhalte des Notebooks
1. Kapitel 1: Ein Qubit mit Hadamard – wir sehen 0/1-Verteilung.
2. Kapitel 2: Drei Varianten wie man Messungen erzwingt oder Wahrscheinlichkeiten steuert (X, RY, H–Z–H).
3. Kapitel 3: CNOT Wahrheitstabelle + Visualisierung aller vier Eingabefälle.

Erweiterungsideen (nicht umgesetzt):
- Bell-State nach Kapitel 3 anschließen
- Bloch-Sphäre zur Visualisierung von RY
- Grundlagen zu Mess-Basiswechsel (H vor Messung)

### Lokale Ausführung
```powershell
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
jupyter lab
```

### Anforderungen
Siehe `requirements.txt`. (Qiskit zieht ggf. weitere Abhängigkeiten automatisch.)

---

Direct Binder link:
https://mybinder.org/v2/gh/JuliusEnBW/Qiskit_Workshop/HEAD?labpath=qiskit_workshop_demo_blanks.ipynb

---

### Lizenz / Hinweis
Kein spezieller Lizenztext hinterlegt – bei Bedarf ergänzen.

Viel Erfolg beim Ausprobieren! ✨
