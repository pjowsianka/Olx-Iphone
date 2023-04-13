# Analiza sprzedaży telefonu iPhone na OLX
W tym repozytorium znajdują się pliki związane z analizą danych sprzedaży telefonów iPhone na serwisie OLX. Analiza została przeprowadzona przy użyciu języka Python i narzędzi takich jak Pandas, Matplotlib i Seaborn.

## Struktura repozytorium
W repozytorium znajdują się następujące pliki:

olx-iphone.ipynb - notebook Jupyter zawierający kod i wyniki analizy danych.
README.md - plik, który właśnie czytasz.

## Przebieg analizy
Notebook olx-iphone.ipynb zawiera cały kod i wyniki analizy danych sprzedaży iPhone na OLX. Analiza składa się z następujących kroków:

* Pobranie danych - w pierwszym kroku został wykorzystany scraper, który pobiera dane takie jak cena, stan, wersja, lokalizacja i inne parametry z serwisu OLX dotyczące sprzedaży iPhone.
* Czyszczenie i przygotowanie danych - w drugim kroku został wykorzystany kod oczyszczający i przetwarzający dane pobrane przez scraper. Przygotowanie danych obejmuje usuwanie duplikatów, uzupełnianie brakujących wartości, konwersję typów danych i inne operacje.
* Prezentacja wykresów - w trzecim kroku zostały zostały przedstawione histogramy i boxplot dla każdej wersji urządzenia, pozwalające na zobrazowanie rozkładu cen na portalu OLX. Użytkownik dzięki temu może lepiej zorientować się jak kształtuje się rynek sprzedaży iPhone na OLX, co pozwoli mu na trafniejsze podjęcie decyzji dotyczącej zakupu lub sprzedaży urządzenia.
* Zasugerowanie okazji kupieckich - na końcu analizy, został zaprezentowany ranking 10 najtańszych telefonów iPhone dla każdej wersji urządzenia.

![image](https://user-images.githubusercontent.com/130370888/231596389-e081210b-a2ef-4742-a581-967a98facde5.png)
