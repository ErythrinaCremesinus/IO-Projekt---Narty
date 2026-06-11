# IO-Projekt---Narty

Projekt systemu dla wypożyczalni i serwisu sprzętu narciarskiego. Repozytorium zawiera dokumentację analityczno-projektową, diagramy UML, makiety interfejsu oraz zrzuty ekranów przedstawiające kluczowe procesy systemu.

## Cel projektu

Celem projektu jest zaprojektowanie systemu wspierającego pracę wypożyczalni nart, snowboardu i akcesoriów zimowych. System ma usprawniać obsługę klienta, wydawanie i zwroty sprzętu, serwis, zarządzanie magazynem oraz raportowanie.

## Zakres funkcjonalny

Na podstawie dostępnej dokumentacji projekt obejmuje między innymi:

- obsługę procesu wypożyczenia sprzętu,
- obsługę zwrotów i dodatkowych opłat,
- dopasowanie sprzętu oraz kalkulację wartości DIN,
- zarządzanie klientami i historią wypożyczeń,
- serwisowanie, konserwację i naprawę sprzętu,
- zarządzanie magazynem,
- raporty i statystyki,
- powiadomienia,
- zarządzanie personelem i organizacją pracy.

## Aktorzy systemu

W projekcie występują następujący aktorzy:

- **Klient** – korzysta z usług wypożyczalni i serwisu,
- **Serwisant** – odpowiada za przygotowanie, dopasowanie i serwis sprzętu,
- **Kasjer** – realizuje płatności i formalności związane z wypożyczeniem,
- **Administrator** – zarządza magazynem, personelem, cennikiem i organizacją działania,
- **System** – wspiera obliczenia i obsługę procesów operacyjnych.

## Główne przypadki użycia

### 1. Wypożyczenie sprzętu
Proces obejmuje wybór sprzętu, pomiar, wprowadzenie danych klienta, kalkulację DIN, przygotowanie sprzętu, płatność i podpisanie umowy.

### 2. Zwrot sprzętu
Proces obejmuje przyjęcie sprzętu, ocenę stanu technicznego, weryfikację kompletności oraz oznaczenie sprzętu jako dostępnego lub wymagającego serwisu.

### 3. Konserwacja i naprawa sprzętu
Proces dotyczy diagnozy technicznej, realizacji prac serwisowych, kontroli jakości i ponownego dopuszczenia sprzętu do użycia.

### 4. Zarządzanie magazynem i personelem
Obejmuje kontrolę stanów magazynowych, zamawianie sprzętu, aktualizację cennika, harmonogramy pracowników oraz organizację pracy wypożyczalni.

## Struktura repozytorium

### `DIAGRAMY/`
Katalog zawierający materiały projektowe i diagramy, w tym m.in.:

- diagram klas,
- diagram przypadku użycia,
- diagramy czynności,
- diagramy przebiegów,
- diagramy stanów.

### `screenshoty/`
Zrzuty ekranów prezentujące przykładowe widoki systemu, m.in.:

- strona główna,
- widok klientów,
- dodawanie klienta,
- historia wypożyczeń,
- nowe wypożyczenie,
- moduł magazynu i serwisu,
- zwroty,
- raporty,
- statystyki,
- powiadomienia,
- zmiana stanowiska.

### `Figma`
Plik z linkiem do makiety/prototypu interfejsu przygotowanego w Figma.

## Materiały projektowe

- **Figma:** plik `Figma` zawiera link do makiety interfejsu,
- **Diagramy UML:** dostępne w katalogach `DIAGRAMY/` oraz `pu_umlet/`,
- **Zrzuty ekranów:** dostępne w katalogu `screenshoty/`.

## Przykładowe obszary interfejsu

Na podstawie dostępnych screenów projekt przewiduje następujące moduły interfejsu:

- panel główny,
- obsługa klientów,
- nowe wypożyczenie,
- zwroty,
- magazyn,
- serwis,
- raporty,
- statystyki,
- powiadomienia,
- zmiana stanowiska.
