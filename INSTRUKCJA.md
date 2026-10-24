# Ochmistrz – instrukcja

Ochmistrz to budżet domowy dla Windows: zapisujesz wydatki, przychody i przekazania na oszczędności, ustalasz miesięczne limity kategorii, pilnujesz stałych opłat. Kilka osób może prowadzić jeden wspólny budżet – każda na swoim komputerze.

## 1. Instalacja
1. Pobierz najnowszy plik `Ochmistrz-…-instalator.exe` ze strony [Wydania](https://github.com/Kargadann/ochmistrz-wydania/releases/latest).
2. Uruchom go. Windows może pokazać okno „System Windows ochronił ten komputer” (program nie ma płatnego podpisu cyfrowego) – kliknij **„Więcej informacji” → „Uruchom mimo to”**.
3. Instalacja trwa kilka sekund i nie wymaga uprawnień administratora. Skróty „Ochmistrz” pojawią się na pulpicie i w menu Start.

Wymagania: Windows 10 lub 11 (64-bit).

## 2. Pierwsze uruchomienie
Program zapyta o Twoje imię – pokazuje ono, kto dopisał wydatek. Od razu utworzy też podstawowe kategorie (żywność, dom i media, transport…, wynagrodzenie, przekazanie na oszczędności). Możesz je potem zmieniać w **Ustawieniach**.

## 3. Miesiąc – wpisy i podsumowanie
- **Dodaj wpis** – wybierz rodzaj (**Wydatek**, **Przychód**, **Oszczędzanie**), wpisz kwotę, datę, kategorię, osobę i opcjonalnie opis. **Zapisz** (albo Enter). „Zapisz i dodaj kolejny” zostawia okno otwarte z tą samą kategorią.
- Kliknięcie wpisu na liście otwiera go do zmiany albo usunięcia.
- Kafle na górze:
  - **Bilans otwarcia** – wynik wszystkich wcześniejszych miesięcy (nadwyżka albo niedobór przechodzi na kolejny miesiąc),
  - **Przychody**, **Wydatki**, **Na oszczędności**,
  - **Do dyspozycji** = bilans otwarcia + przychody − wydatki − oszczędności. Przekazanie na oszczędności nie jest wydatkiem, ale zmniejsza kwotę do dyspozycji.
- Filtry (rodzaj, kategoria, osoba) zawężają listę wpisów; sumy miesiąca się nie zmieniają. Kliknięcie kategorii w panelu „Według kategorii” filtruje listę.
- Strzałki ‹ › przy nazwie miesiąca przełączają miesiące.

## 4. Plan – limity kategorii
Na zakładce **Plan** kliknij kategorię wydatków albo oszczędzania i wpisz limit na miesiąc.
- Limit obowiązuje **od miesiąca, w którym go ustawisz**, także w kolejnych miesiącach – aż do następnej zmiany. Wcześniejsze miesiące się nie zmieniają.
- 0 albo puste pole = bez limitu. Zmianę z danego miesiąca możesz usunąć – wtedy wraca poprzedni limit.
- Na zakładce **Miesiąc** zobaczysz „Plan wydatków: wydano X z Y zł”, a przy kategorii pasek: zielony, **żółty od 80%**, **czerwony po przekroczeniu**.

## 5. Stałe opłaty
Na zakładce **Stałe opłaty** dodaj czynsz, media, abonamenty: kwotę, kategorię, jak często (co miesiąc, co 2/3/4 miesiące, co pół roku, co rok), dzień płatności i miesiąc pierwszej płatności (opcjonalnie ostatniej i osobę, która płaci). Dzień 29–31 w krótszym miesiącu oznacza ostatni dzień miesiąca.
- Panel **Do zapłaty** (na zakładce Miesiąc) pokazuje opłaty zaległe, dzisiejsze i w ciągu 7 dni; liczba zaległych jest przy nazwie zakładki.
- **Zapłacone** otwiera okno wpisu wypełnione danymi opłaty – zmień kwotę, jeśli rachunek był inny, i zapisz. Wpis jest powiązany z terminem.
- Pod kaflem „Do dyspozycji” pojawia się „po opłatach tego miesiąca” – ile zostanie po zapłaceniu pozostałych opłat.
- Jeśli dwie osoby zapłacą ten sam termin, przy terminie pojawi się „zapłacone 2 razy”.

Wskazówka: przy pierwszym wpisywaniu opłat ustaw miesiąc pierwszej płatności od bieżącego miesiąca – inaczej starsze terminy pokażą się jako zaległe.

## 6. Wspólny budżet (kilka osób, kilka komputerów)
Każdy komputer pracuje na własnej kopii budżetu i wymienia zmiany przez **wspólny folder**. Program działa także wtedy, gdy folder jest chwilowo niedostępny – zmiany poczekają.

**Przygotuj folder** dostępny dla wszystkich komputerów, np.:
- udostępniony folder na jednym z komputerów (Eksplorator → prawy przycisk na folderze → *Właściwości* → *Udostępnianie*), ścieżka w rodzaju `\\KOMPUTER\Ochmistrz`,
- folder na dysku sieciowym (NAS) albo na dysku zewnętrznym.

Dostęp do budżetu ma każdy, kto ma dostęp do tego folderu.

**Na pierwszym komputerze:** Ustawienia → Wspólny budżet → **Utwórz wspólny budżet…** → wskaż folder (przycisk „Wybierz…”), podaj nazwę → **Utwórz**. Dotychczasowe dane z tego komputera trafią do wspólnego budżetu.

**Na kolejnych komputerach:** zainstaluj Ochmistrza, podaj imię, potem Ustawienia → Wspólny budżet → **Dołącz do wspólnego budżetu…** → wskaż ten sam folder → **Dołącz**. Jeśli na tym komputerze są już wpisy, program zapyta, czy dołączyć je do wspólnego budżetu.

Synchronizacja odbywa się przy uruchomieniu, chwilę po każdym zapisie, co 2 minuty i przy zamknięciu programu („Synchronizuj teraz” – od razu). Stan widać w nagłówku: „Zsynchronizowano 12:03” albo ostrzeżenie o braku dostępu do folderu z liczbą czekających zmian.

Gdy dwie osoby zmienią ten sam wpis, zostaje późniejsza zmiana; jeśli zastąpiła Twoją, zobaczysz komunikat.

Na wszystkich komputerach używaj **tej samej wersji** programu – jeśli gdzieś jest nowsza, program o tym przypomni.

**Odłącz** (Ustawienia → Wspólny budżet) – dane zostają na tym komputerze, zmiany przestają trafiać do innych. Możesz dołączyć ponownie.

Nie usuwaj i nie zmieniaj ręcznie plików we wspólnym folderze.

## 7. Ustawienia
- **Kategorie** – dodawanie, zmiana nazwy i rodzaju, usuwanie (usunięta kategoria zostaje w dawnych wpisach).
- **Osoby** – osoby z innych komputerów wspólnego budżetu pojawiają się same; osobę bez własnego komputera dodasz ręcznie.
- **O programie** – wersja i folder danych.

## 8. Dane i kopie
- Dane są w folderze `%APPDATA%\Ochmistrz` (menu **Plik → Otwórz folder z danymi**), w pliku `ochmistrz.db`.
- Przed połączeniem ze wspólnym budżetem program robi kopię bazy w podfolderze `kopie`.
- Własna kopia: zamknij program i skopiuj plik `ochmistrz.db` w bezpieczne miejsce. W razie potrzeby zamknij program i podmień plik kopią.
- Przy wspólnym budżecie kopią są też dane na pozostałych komputerach i we wspólnym folderze.

## 9. Aktualizacje
Program raz dziennie sprawdza, czy jest nowa wersja (pyta tylko o numer wersji – bez żadnych danych). Gdy jest, w nagłówku pojawi się przycisk **„Dostępna wersja … – pobierz”** – pobierz instalator i uruchom go; dane zostają. Ręcznie: **Pomoc → Sprawdź aktualizacje**.

## 10. Odinstalowanie
Ustawienia Windows → Aplikacje → Ochmistrz → Odinstaluj. Dane w `%APPDATA%\Ochmistrz` zostają – usuń ten folder ręcznie, jeśli nie są już potrzebne.

## Prywatność
Twoje dane zostają **na Twoim komputerze** i – jeśli go ustawisz – we wspólnym folderze, który wskażesz. Program nie wysyła ich nigdzie. Jedyne połączenie z internetem to raz dziennie pytanie o numer najnowszej wersji.
