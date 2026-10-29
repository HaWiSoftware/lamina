# LAMINA — system dla zakładów cięcia laserowego i gięcia blach

Wycena z rysunku, zlecenia, magazyn arkuszy, hala i kadry w jednym programie. Pracujesz w przeglądarce —
na komputerze w biurze, na tablecie przy maszynie i na telefonie — a serwer i dane zostają w Twojej firmie.

Więcej, razem z nagraniami ekranów programu: **[hawi.com.pl](https://hawi.com.pl)**

## Dla kogo

Dla firm obrabiających blachę — cięcie laserowe i gięcie na krawędziarkach CNC — które chcą mieć wyceny,
materiał, zlecenia i dokumentację jakościową w jednym miejscu, bez wdrażania ciężkiego systemu ERP.

## Co potrafi

**Wyceny i oferty**
- Rysunki DXF i DWG wgrywasz przeciągnięciem, kilka naraz. Program sam mierzy każdy detal: wymiary, długość
  cięcia, liczbę przebić i wagę.
- Z rysunku wykonawczego bierze sam detal — ramkę arkusza, tabelkę i wymiarowanie pomija. Rysunek
  w podziałce przelicza na wymiary rzeczywiste, a obrys narysowany dwa razy liczy raz.
- Rysunek, z którego nie da się policzyć detalu, odrzuca i mówi, dlaczego.
- Cenę materiału bierze z Twojego magazynu: medianę rzeczywistych zakupów dla danego gatunku i grubości.
- Cenę gięcia ustawiasz przy pozycji.
- Na końcu oferta PDF z logo Twojej firmy i miniaturą każdego detalu.

**Zlecenia i produkcja**
- Zlecenie z zatwierdzonej wyceny jednym przyciskiem, z numerem według własnego wzoru — z rokiem albo bez.
- Karta zlecenia A4 z kodem QR — operator skanuje kod i od razu widzi zlecenie.
- Panele operatorów lasera i krawędziarki na tablecie. Detal do gięcia po wycięciu trafia sam na krawędziarkę.
- Pozycje faktury przy zleceniu (import i eksport XLSX), cofnięcie zlecenia z archiwum z kompletem danych.

**Magazyn i zakupy**
- Arkusze, kawałki i regały z nośnością półek, rezerwacje pod zlecenia, atesty i pochodzenie materiału.
- Zapotrzebowanie ze stanów minimalnych i numerowane zamówienia do dostawców w PDF.

**Firma**
- Archiwum, paczka atestów i faktury w systemie Comarch ze zrealizowanych zleceń.
- Analityka BI: przychód, kontrahenci, wyniki technologów, wydajność hali, kapitał zamrożony na regałach.
- Kadry: urlopy, nadgodziny, terminy BHP, panel pracownika.
- Czat firmowy i pomoc „?” na każdym ekranie.
- Asystent AI i odczyt zapytania klienta z wklejonego tekstu — opcjonalne, domyślnie wyłączone;
  włącza je administrator.

**Moduł LAMInest (opcjonalny)**
- Rozkrój blach z rysunków DXF i DWG, program LCC dla wycinarki i karta produkcyjna z czasem cięcia
  z tej samej tabeli co wyceny. Odblokowuje go klucz licencyjny, bez ponownej instalacji.

**Fundament**
- Serwer na jednym komputerze w firmie, dostęp z każdego urządzenia w sieci lokalnej, także szyfrowanym
  połączeniem (HTTPS).
- Role i uprawnienia, jedno aktywne logowanie na konto.
- Licencja liczy stanowiska, a nie komputery.
- Trzy motywy wyglądu, tryb dzienny i nocny, trzy gęstości widoku.

## Wymagania

- Windows 10 lub 11, 64-bit — na komputerze, który będzie serwerem.
- PostgreSQL — jeśli go nie ma, instalator sam go pobierze i zainstaluje.
- Na stanowiskach pracowników wystarczy przeglądarka.

## Wersja próbna — miesiąc za darmo

Pełna wersja przez 30 dni, bez opłat i bez zobowiązań — na Twoich rysunkach, Twoim magazynie i prawdziwych
zleceniach.

1. Pobierz instalator z zakładki **[Releases](../../releases/latest)** (`Setup_Lamina_1.0.….exe` — w nazwie
   jest numer wydania) i zainstaluj program.
2. Na ekranie klucza wpisz nazwę firmy i telefon albo e-mail i kliknij **Wyślij prośbę o klucz**
   (albo wyślij ID komputera z tego ekranu na **biuro@hawi.com.pl**).
3. Klucz próbny wejdzie sam tego samego dnia — bez kopiowania i maili.

Wersja próbna co najmniej raz na 3 dni łączy się z internetem, żeby sprawdzić datę. Kupiona licencja
sprawdza się na tym samym serwerze licencji, ale bez internetu działa do 30 dni. Przy sprawdzaniu licencji
program wysyła tylko skrót klucza i liczbę losową — żadnych danych firmy; dane z prośby o klucz idą tylko
po kliknięciu „Wyślij prośbę o klucz”.

## Instalacja i aktualizacja

- Instalator uruchamiasz na komputerze, który będzie serwerem (wymaga uprawnień administratora).
  Przy pierwszym uruchomieniu program sam otwiera w przeglądarce ekran klucza, a gdy nie może połączyć się
  z bazą — ekran połączenia z bazą.
- Aktualizacja: program sam sprawdza raz na dobę listę wydań i pokazuje nową wersję Administratorowi;
  **Ustawienia → Aktualizacje → Zainstaluj** pobiera instalator, sprawdza jego podpis i sumę, robi kopię bazy
  i instaluje po cichu. Ręcznie: zrób kopię bazy danych i uruchom nowy instalator na tym samym serwerze. Dane,
  ustawienia, plik klucza i połączenie z bazą zostają.
- Sumę kontrolną SHA-256 każdego instalatora podajemy w opisie wydania.

## Dokumentacja

Instrukcje dołączamy do każdego wydania — poniższe odnośniki prowadzą zawsze do wersji dla najnowszego programu:

- **[Instrukcja wdrożenia (PDF)](https://github.com/HaWiSoftware/lamina/releases/latest/download/LAMINA_Instrukcja_Wdrozenia.pdf)**
  — dla administratora: instalacja serwera, licencja, stanowiska, ustawienia, rozwiązywanie problemów.
- **[Instrukcja użytkownika (PDF)](https://github.com/HaWiSoftware/lamina/releases/latest/download/LAMINA_Instrukcja_Uzytkownika.pdf)**
  — dla operatorów i technologów: praca na stanowiskach krok po kroku.

## Licencja

Oprogramowanie komercyjne, wszelkie prawa zastrzeżone. Korzystanie wymaga ważnego klucza licencyjnego.
Warunki licencji wyświetla instalator.

## Kontakt

Łukasz Garbacz · HaWi Software
tel. 500 119 551 · biuro@hawi.com.pl · [hawi.com.pl](https://hawi.com.pl)
