# Statystyczna analiza danych — projekt poprawiony

Autorzy:
Filip Urban
Oskar Zielonka
Wojciech Ossowski

Projekt zawiera pełną analizę statystyczną danych House Prices: preprocessing, statystyki opisowe, wykresy, sampling, estymację, testy statystyczne, testy różnic, test proporcji, ANOVA, ANCOVA,  oraz interpretacje wyników.

## 1. Import bibliotek i wczytanie danych

Wczytujemy dane treningowe, ponieważ zawierają zmienną docelową `SalePrice`, czyli cenę sprzedaży domu. Dane testowe nie mają ceny, dlatego nie są używane do testów statystycznych.