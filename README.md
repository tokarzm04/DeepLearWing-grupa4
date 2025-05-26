# Predykcja współczynników aerodynamicznych (Cₗ, C₅, Cₘ) z LSTM

## Opis projektu
Model wykorzystuje:
- Punkty (x,y) opisujące kształt lotki (LSTM),
- Liczbę Reynoldsa (Re) i kąt ataku (AoA),
do przewidywania współczynników aerodynamicznych.

## Struktura repozytorium
- `data/`: Zawiera surowe dane (CSV).
- `notebooks/`: Notebook Jupyter z implementacją modelu.
- `docs/`: Sprawozdanie w formacie PDF.

## Uruchomienie
1. Sklonuj repozytorium:
   ```bash
   git clone https://github.com/twoja_nazwa_użytkownika/airfoil-lstm-prediction.git
