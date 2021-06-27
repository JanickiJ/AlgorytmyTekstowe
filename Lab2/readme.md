# LAB 2 

### Instrukcje
Celem zadania jest zapoznanie się z konstrukcjami trie oraz drzewem sufiksów.

1. Przyjmij następujący zbiór danych wejściowych:
    * bbbd
    * aabbabd
    * ababcd
    * abcbccd
    * załączony plik.
    
2. Upewnij się, że każdy łańcuch na końcu posiada unikalny znak (marker), a jeśli go nie ma, to dodaj ten znak.
3. Zaimplementuj algorytm konstruujący strukturę trie, która przechowuje wszystkie sufiksy łańcucha danego na wejściu.
4. Zaimplementuj algorytm konstruujący drzewo sufiksów.
5. Upewnij się, że powstałe struktury danych są poprawne. Możesz np. sprawdzić, czy struktura zawiera jakiś ciąg znaków i porównać wyniki z algorytmem wyszukiwania wzorców.
6. Porównaj szybkość działania algorytmów konstruujących struktury danych dla danych z p. 1 w następujących wariantach:
    * Trie (1 pkt) - czas budowy O(n^2), rozmiar drzewa O(n^2), n - długość tekstu
    * Drzewo sufiksów bez wykorzystania procedury fast_find oraz elementów "link" (2 pkt) - czas budowy O(n^2), rozmiar drzewa O(n)
