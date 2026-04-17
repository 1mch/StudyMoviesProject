# StudyMoviesProject
# 🎬 Analýza filmových dát (Movie Data Analysis)

Tento projekt sa zameriava na jednoduchú dátovú analýzu svetovej kinematografie. Skúmam v ňom vzťahy medzi dĺžkou filmu, dátumom premiéry a popularitou. Dáta sú čerpané z verejne dostupných API.

## 📊 Ciele projektu
- Analyzovať trend dĺžky filmov (runtime) v priebehu desaťročí.
- Zistiť, v ktorých mesiacoch sa premiéruje najviac filmov (sezónnosť).
- Porovnať dĺžku filmov podľa žánrov.
- Vizualizovať získané dáta pomocou grafov.

## 🛠️ Použité technológie
- **Jazyk:** Python 3.x
- **Knižnice:** - `pandas` (spracovanie dát)
  - `matplotlib` / `seaborn` (vizualizácia)
  - `requests` (získavanie dát z API)
- **Zdroj dát:** [TMDb API](https://developer.themoviedb.org/) (alebo OMDb API)

## 🗂️ Štruktúra repozitára
- `data/` - priečinok so surovými dátami (CSV/JSON).
- `notebooks/` - Jupyter Notebooky s postupom analýzy.
- `scripts/` - Python skripty na sťahovanie dát z API.
- `visualizations/` - vygenerované grafy a štatistiky.

## 🚀 Ako spustiť projekt
1. Naklonuj si repozitár:
   ```bash
   git clone [https://github.com/tvoje-meno/meno-projektu.git](https://github.com/tvoje-meno/meno-projektu.git)
