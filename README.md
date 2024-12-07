# Prognozowanie cen samochodów na rynku białoruskim

Projekt ma na celu przewidywanie cen samochodów na Białorusi na podstawie różnych cech pojazdów, takich jak marka, rok produkcji, pojemność silnika, rodzaj paliwa, skrzynia biegów, przebieg, napęd, kolor oraz segment. Dodatkowo projekt analizuje kluczowe zmienne wpływające na ceny samochodów.

## Zbiór danych

Zbiór danych, pochodzący z Kaggle, składa się z **56 244 wierszy i 12 kolumn**. Zawiera szczegółowe informacje na temat samochodów wystawionych na sprzedaż.

## Kluczowe cechy projektu

- **Eksploracyjna Analiza Danych (EDA):** Analiza struktury danych, identyfikacja brakujących wartości oraz korelacji między zmiennymi.
- **Przygotowanie danych:** Usunięcie wartości odstających, wypełnienie braków, oraz inżynieria cech (np. kodowanie zmiennych kategorycznych, tworzenie nowych zmiennych na podstawie istniejących).
- **Modelowanie:** Trening różnych modeli regresyjnych (np. Random Forest, Gradient Boosting, Linear Regression) w celu przewidywania cen samochodów.
- **Ewaluacja modeli:** Ocena modeli na podstawie metryk takich jak R², RMSE, oraz MAE.
- **Wyjaśnialność modeli:** Analiza wpływu zmiennych na prognozowane ceny przy użyciu narzędzi takich jak SHAP.

## Technologie użyte w projekcie

- **Python:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost
- **Jupyter Notebook:** Analiza i prezentacja wyników
- **Kaggle:** Pobranie i przetwarzanie danych

## Wyniki

- Najbardziej istotne zmienne wpływające na ceny samochodów to: marka, rok produkcji, przebieg, oraz rodzaj paliwa.
- Zastosowany model **Random Forest** osiągnął najlepsze wyniki, z R² na poziomie 0.85 i RMSE wynoszącym 1500 BYN na zbiorze testowym.

## Jak uruchomić projekt?

1. Sklonuj repozytorium:
   ```bash
   git clone https://github.com/your-repository/car-price-prediction
   cd car-price-prediction
