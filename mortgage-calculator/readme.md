# Kalkulator Kredytu Hipotecznego - Dokumentacja Użytkownika

## Spis treści
1. [Wprowadzenie](#wprowadzenie)
2. [Pierwsze kroki](#pierwsze-kroki)
3. [Parametry podstawowe](#parametry-podstawowe)
4. [Parametry dodatkowe](#parametry-dodatkowe)
5. [Dokonywanie nadpłat](#dokonywanie-nadpłat)
6. [Zmiana oprocentowania](#zmiana-oprocentowania)
7. [Harmonogram spłat](#harmonogram-spłat)
8. [Podsumowanie i analityka](#podsumowanie-i-analityka)
9. [Trwałość danych](#trwałość-danych)
10. [Kompatybilność z przeglądarkami](#kompatybilność-z-przeglądarkami)

## Wprowadzenie

Kalkulator Kredytu Hipotecznego to kompleksowa aplikacja internetowa zaprojektowana, aby pomóc Ci analizować kredyty hipoteczne, symulować różne scenariusze spłat i podejmować świadome decyzje finansowe. Kalkulator umożliwia:

- Obliczanie rat kredytu ze stałymi lub malejącymi ratami
- Dodawanie jednorazowych lub cyklicznych nadpłat, aby zobaczyć ich wpływ
- Symulowanie zmian oprocentowania
- Porównywanie oryginalnego harmonogramu spłat ze zmodyfikowanymi scenariuszami
- Analizę całkowitego kosztu, uwzględniając odsetki i ubezpieczenie
- Obliczanie ceny za metr kwadratowy z uwzględnieniem wszystkich kosztów

## Pierwsze kroki

Kalkulator działa całkowicie w Twojej przeglądarce - nie wymaga instalacji. Twoje dane są automatycznie zapisywane w lokalnej pamięci przeglądarki dla wygody.

Aby rozpocząć:
1. Wprowadź podstawowe parametry kredytu
2. Ustaw dodatkowe parametry według potrzeb
3. Kliknij "Oblicz harmonogram"
4. Przejrzyj swój harmonogram spłat i podsumowanie

## Parametry podstawowe

W sekcji "Parametry podstawowe" wprowadź:

- **Kwota kredytu (PLN)**: Kwota kredytu w złotych polskich
- **Oprocentowanie (%)**: Roczna stopa procentowa jako wartość procentowa
- **Okres kredytowania (miesiące)**: Czas trwania kredytu w miesiącach
- **Data rozpoczęcia kredytu**: Data rozpoczęcia kredytu
- **Typ rat**: Wybierz rodzaj rat
    - **Raty stałe**: Równe miesięczne płatności
    - **Raty malejące**: Stała część kapitałowa + malejące odsetki

## Parametry dodatkowe

Sekcja "Parametry dodatkowe" pozwala na:

- **Cena nieruchomości (PLN)**: Wprowadź cenę nieruchomości
- **Metraż (m²)**: Wprowadź powierzchnię nieruchomości w metrach kwadratowych
- **Miesięczna kwota ubezpieczenia na życie (PLN)**: Miesięczna kwota ubezpieczenia na życie

Ubezpieczenie można ustawić na trzy sposoby:
1. Stała kwota miesięczna
2. Procent od początkowej kwoty kredytu (zaznacz "Ubezpieczenie jako % od kwoty kredytu")
3. Procent od pozostałego kapitału (zaznacz "Ubezpieczenie od pozostałego kapitału")

Przy korzystaniu z opcji procentowych należy określić stawkę procentową.

## Dokonywanie nadpłat

Aby dodać nadpłaty do harmonogramu:

1. Przejdź do sekcji "Dodaj nadpłatę"
2. Wprowadź kwotę nadpłaty w PLN
3. Określ, od której raty ma być zastosowana nadpłata
4. W przypadku nadpłat cyklicznych:
    - Zaznacz "Nadpłata cykliczna"
    - Określ, co ile miesięcy nadpłata powinna się powtarzać
    - Opcjonalnie ogranicz liczbę nadpłat, zaznaczając "Ograniczona liczba nadpłat" i określając liczbę
5. Kliknij "Dodaj nadpłatę"

Wszystkie dodane nadpłaty będą wymienione w sekcji "Zmiany w harmonogramie".

## Zmiana oprocentowania

Aby symulować zmiany stóp procentowych:

1. Przejdź do sekcji "Dodaj zmianę oprocentowania"
2. Wprowadź nową stopę procentową (%)
3. Określ, od której raty ma obowiązywać nowa stawka
4. Kliknij "Dodaj zmianę oprocentowania"

Wszystkie zmiany oprocentowania będą wymienione w sekcji "Zmiany w harmonogramie".

## Harmonogram spłat

Po obliczeniu kredytu, szczegółowy harmonogram spłat zostanie wyświetlony w tabeli pokazującej:

- Numer raty
- Datę płatności
- Całkowitą kwotę raty
- Część kapitałową
- Część odsetkową
- Kwotę ubezpieczenia
- Całkowity spłacony kapitał do danej daty
- Całkowite zapłacone odsetki do danej daty
- Pozostały kapitał do spłaty
- Wszelkie zastosowane zmiany (nadpłaty lub zmiany oprocentowania)

Tabela jest przewijalna dla łatwego przeglądania kredytów długoterminowych.

## Podsumowanie i analityka

Sekcja "Podsumowanie" zapewnia:

1. **Porównanie między oryginalnym a zmodyfikowanym harmonogramem**:
    - Różnice w okresie kredytowania (miesiące/lata)
    - Różnice w kwocie odsetek (całkowite i procentowe)
    - Koszty ubezpieczenia

2. **Analiza ceny za metr kwadratowy**:
    - Oryginalna cena za metr kwadratowy
    - Cena za metr kwadratowy z uwzględnieniem odsetek (oryginalny harmonogram)
    - Cena za metr kwadratowy z uwzględnieniem odsetek (zmodyfikowany harmonogram)
    - Różnica w cenie za metr kwadratowy

3. **Analityka wizualna**:
    - Wykres słupkowy porównujący okresy kredytowania
    - Wykres słupkowy porównujący całkowite zapłacone odsetki

Te informacje pomagają zrozumieć finansowy wpływ nadpłat i zmian oprocentowania.

## Trwałość danych

Kalkulator automatycznie zapisuje wszystkie Twoje dane w lokalnej pamięci przeglądarki. Gdy wrócisz do aplikacji później, Twoje wcześniej wprowadzone dane zostaną automatycznie załadowane.

Powiadomienie pojawi się na krótko, gdy dane zostaną zapisane.

## Edytowanie i usuwanie zmian

Aby edytować lub usunąć wcześniej dodane nadpłaty lub zmiany oprocentowania:

1. Znajdź element w sekcji "Zmiany w harmonogramie"
2. Kliknij ikonę edycji (ołówek), aby zmodyfikować element
3. Kliknij ikonę usuwania (kosz), aby usunąć element

Po edycji lub usunięciu, harmonogram zostanie automatycznie przeliczony.

## Kompatybilność z przeglądarkami

Ten kalkulator działa najlepiej w nowoczesnych przeglądarkach:
- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari

Dla najlepszego doświadczenia, upewnij się, że Twoja przeglądarka jest aktualna.

---

Korzystając z tego kalkulatora kredytu hipotecznego, możesz uzyskać cenne informacje na temat struktury Twojego kredytu, podejmować świadome decyzje dotyczące nadpłat i lepiej zrozumieć długoterminowe skutki finansowe Twojego kredytu hipotecznego.