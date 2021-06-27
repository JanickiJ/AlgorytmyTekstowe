# LAB 3 

### Instrukcje 

Zadanie polega na implementacji dwóch algorytmów kompresji:

* statycznego algorytmu Huffmana (1 punkt)
* dynamicznego algorytmu Huffmana (2 punkty)

Dla każdego z algorytmów należy wykonać następujące zadania:

1. Opracować format pliku przechowującego dane.
2. Zaimplementować algorytm kompresji i dekompresji danych dla tego formatu pliku.
3. Zmierzyć współczynnik kompresji (wyrażone w procentach: 1 - plik_skompresowany / plik_nieskompresowany) dla plików tekstowych o rozmiarach: 1kB, 10kB, 100kB, 1MB, dla różnych typów plików: plik tekstowy z portalu Guttenberga, plik źródłowy z Githubu, plik ze znakami losowanymi z rozkładu jednostajnego.
4. Zmierzyć czas kompresji i dekompresji dla plików z punktu 3 dla każdego algorytmu.