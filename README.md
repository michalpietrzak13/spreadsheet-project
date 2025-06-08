
Projekt polega na stworzeniu zestawu funkcji, które pozwalają na wykonywanie różnych operacji na tablicach liczb, podobnie jak w arkuszu kalkulacyjnym (spreadsheet). Każda funkcja została zaimplementowana w sposób funkcyjny, bez efektów ubocznych, co ułatwia testowanie i rozbudowę kodu.

Projekt powstał jako ćwiczenie praktyczne w ramach nauki JavaScript na Freecodecamp oraz jako element mojego portfolio programistycznego.

Funkcjonalności
Podstawowe operacje matematyczne: sumowanie, średnia, mediana

Filtrowanie: wybieranie liczb parzystych, usuwanie duplikatów

Generowanie zakresów: tworzenie tablic z liczbami z podanego przedziału

Losowanie liczb: generowanie losowej liczby z określonego zakresu

Sprawdzanie warunków: czy tablica zawiera określoną wartość, czy są liczby parzyste

Inne operacje: pobieranie pierwszych/ostatnich elementów, inkrementacja wszystkich wartości

Obsługa przypadków brzegowych: funkcja zwracająca argument bez zmian (dla pustych nazw funkcji)

Jak uruchomić projekt
Sklonuj repozytorium lub pobierz pliki ZIP.

Otwórz plik index.html (jeśli jest interfejs) lub uruchom plik script.js w konsoli przeglądarki.

Testuj funkcje, wywołując je z poziomu konsoli JavaScript, np.:

javascript
spreadsheetFunctions.sum([1, 2, 3]); // 6
spreadsheetFunctions.even([1, 2, 3, 4]); // [2, 4]
Technologie
JavaScript (ES6+)

HTML, CSS (opcjonalnie, jeśli dodałeś interfejs)

Programowanie funkcyjne

Praca z tablicami i obiektami

Przykłady użycia funkcji
javascript
spreadsheetFunctions.sum([1, 2, 3]);          // 6
spreadsheetFunctions.average([2, 4, 6]);      // 4
spreadsheetFunctions.median([1, 3, 2]);       // 2
spreadsheetFunctions.even([1, 2, 4, 5]);      // [2, 4]
spreadsheetFunctions.firsttwo([5, 8, 9]);     // [5, 8]
spreadsheetFunctions.lasttwo([5, 8, 9]);      // [8, 9]
spreadsheetFunctions.has2([1, 3, 2]);         // true
spreadsheetFunctions.increment([1, 2, 3]);    // [2, 3, 4]
spreadsheetFunctions.someeven([1, 3, 5]);     // false
spreadsheetFunctions.random([10, 5]);         // liczba z zakresu 10-14
spreadsheetFunctions.range([2, 6]);           // [2, 3, 4, 5]
spreadsheetFunctions.nodupes([2, 1, 2, 5]);   // [2, 1, 5]
spreadsheetFunctions[""]("dowolna wartość");  // "dowolna wartość"
Plany rozwoju
Dodanie prostego interfejsu graficznego (np. w React lub czystym JS)

Rozszerzenie funkcji matematycznych (np. min, max, potęgowanie)

Dodanie testów jednostkowych (np. w Jest)

Poprawa obsługi błędów i walidacji danych wejściowych

Autor
https://github.com/michalpietrzak13
Projekt stworzony w ramach nauki na Freecodecamp
