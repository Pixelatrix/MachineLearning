# MachineLearning

Projektet använder:
- **pandas** – för att läsa och hantera CSV- och tabell-data
- **scikit-learn** – huvudbibliotek för maskininlärning i Python (träning och utvärdering av modeller)
- **matplotlib** – för att visualisera data, hitta mönster och visa resultat

Alla beroenden installeras automatiskt via `requirements.txt`.

## Installationsguide (VS Code + Windows)

### 1. Klona projektet
1. Öppna **VS Code**
2. Klicka på **Clone Git Repository**
3. Klistra in repo-URL
4. Välj var projektet ska sparas på datorn
5. Klicka **Open** när VS Code frågar

Projektet laddas nu ner och sparas lokalt på din dator.

### 2. Skapa virtuell miljö

Öppna **Terminal → New Terminal** i VS Code och kör följande kommandon:

```bash
python -m venv .venv
```

```powershell
.\.venv\Scripts\Activate.ps1
```

Terminalen ska nu börja med:

```text
(.venv)
```

Om du får ett fel om *execution policy*, kör först:

```powershell
Set-ExecutionPolicy -Scope CurrentUser RemoteSigned
```

och försök sedan aktivera miljön igen.

Installera beroenden:

```bash
pip install -r requirements.txt
```

---

### 3. Starta igång projektet

1. Öppna `Projekt.ipynb`
2. Klicka på **Select Kernel** uppe till höger
3. Välj Python-kernel från `.venv`
4. Kör cellerna i notebooken

Om allt är korrekt installerat ska inga `ModuleNotFoundError` visas och du ska få fram tabellen som första koden skapar.
