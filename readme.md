# Wprowadzenie do pakietu statystycznego R

Materiały na kurs "Wprowadzenie do pakietu statystycznego R".

## Informacje:

+ Prowadzący: 
  + dr Maciej Beręsewicz, prof UEP 
  + mgr Wojciech Dopieralski
  + dr Wojciech Roszka
  + dr Kamil Wilak
  

+ [Sylabus](https://esylabus.ue.poznan.pl/pl/11/1/1/105/4?masterElement=105)
  + **Wprowadzenie do pakietu statystycznego R i Rstudio** ([notatnik](https://htmlpreview.github.io/?https://github.com/DepartmentOfStatisticsPUE/intro-R-2024/blob/main/codes/01-wprowadzenie.nb.html) | [ćwiczenia](https://htmlpreview.github.io/?https://github.com/DepartmentOfStatisticsPUE/intro-R-2024/blob/main/exercises/cw-01.html))
      + czysty R, Rstudio i projekty
      + skrypty R, R jako kalkulator
      + szukanie pomocy
      + tworzenie obiektów, symbol `<-`
      + rodzaje obiektów
      + `install.packages()` i `library()`
  + Obiekty i funkcje w R ([notatnik](https://htmlpreview.github.io/?https://github.com/DepartmentOfStatisticsPUE/intro-R-2024/blob/main/codes/02-obiekty.nb.html))
      + wektory ([ćwiczenia #2](https://htmlpreview.github.io/?https://github.com/DepartmentOfStatisticsPUE/intro-R-2024/blob/main/exercises/cw-02.html)), 
      + macierze ([ćwiczenia #3](https://htmlpreview.github.io/?https://github.com/DepartmentOfStatisticsPUE/intro-R-2024/blob/main/exercises/cw-03.html)),
      + ramki danych ([ćwiczenia #4](https://htmlpreview.github.io/?https://github.com/DepartmentOfStatisticsPUE/intro-R-2024/blob/main/exercises/cw-04.html)),
      + listy ([ćwiczenia #5](https://htmlpreview.github.io/?https://github.com/DepartmentOfStatisticsPUE/intro-R-2024/blob/main/exercises/cw-05.html)),
  + Wczytywanie danych:
      + pliki tekstowe (`read.csv`, `read.csv2`, `read.table`) ([notatnik](https://htmlpreview.github.io/?https://github.com/DepartmentOfStatisticsPUE/intro-R-2024/blob/main/codes/03-wczytywanie.nb.html), [ćwiczenia #6](https://htmlpreview.github.io/?https://github.com/DepartmentOfStatisticsPUE/intro-R-2024/blob/main/exercises/cw-06.html)),
      + pliki MS Excel (`readxl::read_excel`).
  + Przetwarzanie danych w R:
      + wybieranie kolumn i wierszy ([notatnik](https://htmlpreview.github.io/?https://github.com/DepartmentOfStatisticsPUE/intro-R-2024/blob/main/codes/04-ramkidanych.nb.html), [ćwiczenia #7](https://htmlpreview.github.io/?https://github.com/DepartmentOfStatisticsPUE/intro-R-2024/blob/main/exercises/cw-07.html)),
      + tworzenie nowych kolumn ([notatnik](https://htmlpreview.github.io/?https://github.com/DepartmentOfStatisticsPUE/intro-R-2024/blob/main/codes/04-ramkidanych.nb.html), [ćwiczenia #7](https://htmlpreview.github.io/?https://github.com/DepartmentOfStatisticsPUE/intro-R-2024/blob/main/exercises/cw-07.html)).
  + Pętle, funkcje ([notatnik](), [ćwiczenia #7](https://htmlpreview.github.io/?https://github.com/DepartmentOfStatisticsPUE/intro-R-2024/blob/main/exercises/cw-08.html)).
  

## Struktura repozytorium

+ `data-raw` -- folder z danymi
+ `notebooks` -- folder z kodami

## Dane na zajęcia

W trakcie zajęć będziemy korzystać z [dziennych statystyk policji](https://policja.pl/pol/form/1,Informacja-dzienna.html). 

Zbiór zawiera 5391 wierszy i 11 następujących kolumn:

+ `data` -- dzień w formacie `YYYY-MM-DD`,
+ `interwencje` -- liczba policyjnych interwencji,
+ `zatrzymani_na_goracym_uczynku` -- liczba zatrzymanych w związku z popełnieniem przestępstwa/wykroczenia,
+ `zatrzymani_poszukiwani` - liczba zatrzymanych będących poszukiwanymi,
+ `kierujacy_po_spozyciu_alkoholu` -- liczba kierujących po spożyciu alkoholu,
+ `wypadki_drogowe` -- liczba wypadków na drogach,
+ `zabici_w_wypadkach` -- liczba zabitych na drogach,
+ `ranni_w_wypadkach` -- liczba rannych na drogach,
+ `dzien_tygodnia` -- dzień tygodnia: `Pon, Wt, Sr, Czw, Pt, So, Nie`,
+ `miesiac` -- miesiąc: 1-styczeń, ..., 12-grudzień,
+ `rok` -- rok: 2008,..., 2023.

## Materiały dla 3 roku

+ [ćwiczenia #2](https://htmlpreview.github.io/?https://github.com/DepartmentOfStatisticsPUE/intro-R-2024/blob/main/exercises/3-rok-cw-01.html)
