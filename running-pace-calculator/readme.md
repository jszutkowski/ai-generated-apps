# Kalkulator Biegów - Dokumentacja

## Spis treści
1. Wprowadzenie
2. Instalacja
3. Opis funkcjonalności
4. Instrukcja obsługi
5. Technologie
6. Rozwiązywanie problemów
7. Dalszy rozwój

## 1. Wprowadzenie

Kalkulator Biegów to prosta, ale funkcjonalna aplikacja webowa stworzona z myślą o biegaczach, którzy chcą łatwo obliczać tempo biegu lub przewidywany czas ukończenia dystansu. Aplikacja oferuje intuicyjny interfejs, który pozwala na szybkie obliczenia bez zbędnych komplikacji.

## 2. Instalacja

Kalkulator Biegów to aplikacja działająca w przeglądarce internetowej i nie wymaga instalacji. Aby uruchomić aplikację:

1. Zapisz kod HTML do pliku z rozszerzeniem `.html` (np. `kalkulator-biegow.html`)
2. Otwórz zapisany plik w dowolnej nowoczesnej przeglądarce internetowej (Chrome, Firefox, Safari, Edge)

Aplikacja działa lokalnie w przeglądarce i nie wymaga połączenia z internetem (poza początkowymi zasobami, takimi jak czcionki Google i jQuery).

## 3. Opis funkcjonalności

Kalkulator Biegów oferuje dwie główne funkcje dostępne przez system zakładek:

### Obliczanie tempa biegu
Pozwala obliczyć, jakie tempo biegu (minuty na kilometr) należy utrzymać, aby ukończyć wybrany dystans w określonym czasie.

### Obliczanie czasu ukończenia
Pozwala przewidzieć, w jakim czasie ukończysz wybrany dystans, biegnąc z określonym tempem.

## 4. Instrukcja obsługi

### Kalkulator tempa biegu (pierwsza zakładka)

1. Wybierz zakładkę "Oblicz tempo" (aktywna domyślnie)
2. Z rozwijanej listy wybierz dystans (5 km, 10 km, 15 km, półmaraton lub maraton)
3. Wprowadź planowany czas ukończenia:
    - W polu "Godziny" wpisz liczbę godzin
    - W polu "Minuty" wpisz liczbę minut
    - W polu "Sekundy" wpisz liczbę sekund
4. Kliknij przycisk "Oblicz tempo"
5. Wynik pojawi się poniżej formularza w formacie "X:XX min/km"

### Kalkulator czasu ukończenia (druga zakładka)

1. Kliknij zakładkę "Oblicz czas ukończenia"
2. Z rozwijanej listy wybierz dystans (5 km, 10 km, 15 km, półmaraton lub maraton)
3. Wprowadź swoje tempo biegu:
    - W polu "Minuty" wpisz liczbę minut na kilometr
    - W polu "Sekundy" wpisz liczbę sekund na kilometr
4. Kliknij przycisk "Oblicz czas ukończenia"
5. Wynik pojawi się poniżej formularza w formacie "H:MM:SS" lub "MM:SS" dla krótszych czasów

## 5. Technologie

Aplikacja została zbudowana w oparciu o następujące technologie:

- HTML5 - struktura aplikacji
- CSS3 - stylizacja w duchu Material Design
- JavaScript/jQuery - logika obliczeniowa i interakcje
- Google Fonts - czcionka Roboto i ikony Material Design

## 6. Rozwiązywanie problemów

### Nie widzę poprawnie wyświetlonych czcionek i ikon
Upewnij się, że masz dostęp do internetu podczas pierwszego uruchomienia aplikacji. Po załadowaniu zasobów Google Fonts, aplikacja będzie działać również offline.

### Obliczenia nie działają
Upewnij się, że wprowadzasz poprawne wartości liczbowe. W polach można wprowadzać tylko liczby. Pola minut i sekund powinny zawierać wartości od 0 do 59.

### Interfejs wygląda niepoprawnie na moim urządzeniu
Aplikacja jest responsywna i powinna poprawnie działać na różnych urządzeniach. Jeśli masz problemy z wyświetlaniem, spróbuj:
- Zaktualizować przeglądarkę do najnowszej wersji
- Odświeżyć stronę
- W przypadku urządzeń mobilnych, upewnij się, że strona jest wyświetlana w trybie poziomym dla lepszej czytelności

## 7. Dalszy rozwój

Możliwe kierunki rozwoju aplikacji:

- Dodanie możliwości obliczania tempa na milę
- Dodanie opcji zapisywania historii obliczeń
- Dodanie kalkulatora spalanych kalorii
- Eksport wyników do PDF
- Dodanie możliwości udostępniania wyników w mediach społecznościowych
- Stworzenie wersji offline jako aplikacji mobilnej

---

Kalkulator Biegów to narzędzie stworzone przez biegaczy dla biegaczy. Mamy nadzieję, że pomoże Ci w planowaniu treningów i zawodów. Powodzenia na trasie!