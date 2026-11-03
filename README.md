# Bazownik

Aplikacja na Windows do nauki z quizów, w stylu Testownika. Działa w całości offline i otwiera pliki JSON Testownika.

## Instalacja

1. Pobierz **Bazownik-Setup-3.8.0.exe** z zakładki **[Releases](../../releases/latest)**. Jest tam też wersja przenośna bez instalacji (*Bazownik-Portable*).
2. Uruchom pobrany plik. Windows może pokazać okno „System Windows ochronił komputer”, bo instalator nie ma płatnego podpisu cyfrowego. Kliknij **Więcej informacji → Uruchom mimo to**.
3. Przejdź przez instalator. Na pulpicie i w menu Start pojawi się skrót **Bazownik**.

**Aktualizacje:** aplikacja sama sprawdza nowe wydania w zakładce *Releases* i proponuje **Pobierz i zainstaluj**. Quizy i postęp nauki zostają na komputerze.

## Co potrafi

**Quizy**
- Import plików JSON Testownika (także przez przeciągnięcie na okno) i starych baz Testownika z plikami `.txt`.
- Eksport do pliku Bazownika albo do formatu Testownika. Do pliku Bazownika możesz opcjonalnie dołączyć swój postęp nauki, np. żeby przenieść go na inny komputer.
- Dzielenie quizu na części, łączenie kilku quizów w jedną sesję, archiwum.

**Edytor pytań**
- Typy pytań: jednokrotny i wielokrotny wybór, prawda/fałsz z wieloma stwierdzeniami, pytania otwarte i „uzupełnij luki”.
- Zdjęcia wklejasz przez **Ctrl+V**, a **Ctrl+Shift+V** wkleja listę linii jako osobne odpowiedzi (bez „a)”, „●” i podobnych).
- Wzory w wyjaśnieniach, np. `$A \setminus B$`.
- Oznaczenia pytań: gwiazdka („brak w wykładach”) i zakładka („niezgodność baz / LLM”).

**Nauka**
- Powtórki do skutku z ustawianą liczbą powtórzeń i limitem.
- Wznawianie przerwanej sesji, pasek opanowania i seria dni nauki.
- Tryb egzaminu z limitem czasu i oceną.
- Tryb przeglądania z zaznaczonymi poprawnymi odpowiedziami.
- Podgląd poprzednich pytań (**←**) z kopiowaniem i edycją.
- Przycisk **„Miałem rację”** po pomyłce.
- Zaznaczanie błędów w odpowiedziach otwartych.
- Skróty klawiszowe, m.in. **1–9** wybór, **Enter** sprawdź / dalej, **G** / **Z** oznaczenia, **E** edycja, **K** kopiuj.

**Synchronizacja między komputerami (OneDrive)**
- Profil z postępem, serią dni i statystykami zapisujesz w wybranym folderze OneDrive.
- Każdą bazę zapisujesz osobno, w wybranym miejscu w OneDrive. Na drugim komputerze dodajesz te same pliki.
- Przy starcie i zamykaniu pasek postępu pokazuje rzeczywisty stan synchronizacji plików. Aplikacja zamyka się dopiero po wysłaniu zmian.

**Wygląd i statystyki**
- Wykresy czasu nauki, skuteczności i opanowania quizów.
- Motyw jasny i ciemny, przybliżanie przez **Ctrl + kółko myszy**.

## Wymagania

Windows 10 lub 11 (64-bit).
