# ADS-505 Team Project: Pokémon TCG Trade-In Liquidity Risk

**Author:** Amir Badeanlo  
**Course:** ADS-505 Applied Data Science  
**Repository:** [https://github.com/amirarsalan4543/ADS_505](https://github.com/amirarsalan4543/ADS_505)

## Overview
This project models secondary market price spreads in the Pokémon Trading Card Game. By predicting the divergence between TCGplayer market prices and low floor liquidation prices, the analysis provides local game stores (LGS) with a data-driven framework to adjust trade-in margins and reduce illiquid dead-stock risk.

## Repository Structure
```text
├── data/
│   └── pokemon-prices.csv    # Secondary market card pricing dataset
├── pokemon.ipynb             # Main Jupyter notebook (EDA, preprocessing, models)
├── requirements.txt          # Python package dependencies
└── README.md                 # Project documentation
```

## How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/amirarsalan4543/ADS_505.git
   cd ADS_505/proj
   ```

2. **Create and activate a virtual environment:**
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Open and run the notebook:**
   ```bash
   jupyter notebook pokemon.ipynb
   ```

## Data Source
Data is sourced from the open-source [Pokemon-TCG-Data](https://github.com/PokemonTCG/pokemon-tcg-data) repository curated via PokemonTCG.io and synchronized TCGplayer market metrics.
