# Modelowanie decyzji kredytowych przy użyciu uczenia maszynowego i selekcji cech

## Opis projektu
Celem projektu było zbudowanie oraz porównanie różnych modeli uczenia maszynowego w kontekście predykcji statusu wniosków pożyczkowych (akceptacja/odrzucenie). Analizowane dane zawierają informacje o klientach oraz parametrach wniosku kredytowego.

Projekt obejmuje pełny proces analizy danych:

 - wstępne przygotowanie danych,
 - czyszczenie danych i obsługa braków,
 - eksploracyjną analizę danych i wizualizacje zależności,
 - selekcję cech z użyciem algorytmu Boruta,
 - budowę modeli klasyfikacyjnych (Regresja Logistyczna i Random Forest),
 - zastosowanie metody undersamplingu w celu przeciwdziałania problemowi niezrównoważonych klas,
 - ocenę modeli z wykorzystaniem metryk: Accuracy, Precision, Recall, F1-score,
 - porównanie modeli na zbiorach treningowych i testowych,
 - interpretację wyników oraz podsumowanie wniosków.

## Wykorzystane narzędzia i biblioteki
Projekt został wykonany w języku R z użyciem następujących pakietów:

 - tidyverse (dplyr, ggplot2, tidyr) — manipulacja i wizualizacja danych
 - Boruta — selekcja istotnych cech
 - caret oraz yardstick — budowa modeli i ewaluacja
 - ranger — Random Forest
 - themis — undersampling
 - tidymodels — pipeline modelowania
 - knitr — przygotowanie raportu
