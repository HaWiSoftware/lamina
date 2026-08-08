# LAMINA — system MES/WMS do zarządzania produkcją

**Nowoczesny system do zarządzania produkcją w zakładach cięcia laserowego i gięcia CNC.**
Wyceny i oferty, magazyn blach, zlecenia, etykiety, atesty, analityka BI — wszystko z poziomu
przeglądarki, na komputerze, tablecie i telefonie.

---

## Dla kogo

Dla firm zajmujących się obróbką blach — cięciem laserowym i gięciem na krawędziarkach CNC —
które chcą uporządkować wyceny, magazyn materiału, zlecenia i dokumentację jakościową
w jednym miejscu.

## Kluczowe funkcje

- **Wyceny i oferty** — wgrywasz rysunki klienta, system sam mierzy geometrię detalu (wymiary
  gabarytowe, długość cięcia, liczba przebić) i liczy wagę, czas pracy lasera oraz cenę według
  Twojego cennika. Przyjmuje **DXF**, **wycinek PDF** i **zdjęcie szkicu z kartki**; linie
  wymiarowe i osie odsiewa automatycznie. Na końcu generuje **ofertę PDF** z logo Twojej firmy,
  danymi nabywcy z kartoteki i miniaturą każdego detalu.
- **Magazyn blach** — pełna ewidencja arkuszy, regałów i stanowisk, rozkrój z automatycznym
  liczeniem i zwrotem resztek, kontrola przeciążenia regałów.
- **Zlecenia produkcyjne** — od przyjęcia materiału, przez cięcie i gięcie, po archiwum;
  pełna historia i przypisanie operatorów, którzy pracowali przy zleceniu. Detal z gięciem
  po zakończeniu cięcia trafia automatycznie na panel krawędziarki.
- **Zapotrzebowanie (MRP)** — progi minimalne, wykrywanie braków materiałowych i gotowe
  zamówienie zakupowe w PDF do hurtowni.
- **Etykiety i paczki atestów** — druk etykiet oraz komplet dokumentacji jakościowej materiału.
- **Analityka BI** — wartość zleceń, dynamika przychodu, analiza odpadów (w sztukach
  i kilogramach), top kontrahenci, wyniki wg technologów, zamrożony kapitał na regałach.
- **Kadry** — urlopy, nadgodziny, karty BHP, panel pracownika, raport absencji w PDF.
- **Praca z przeglądarki** — serwer na jednym komputerze, dostęp z dowolnego urządzenia w sieci
  lokalnej (komputer, tablet, telefon), także po szyfrowanym HTTPS.
- **Integracja z ERP** (Comarch) oraz wbudowany asystent AI.

## Wymagania

- Windows 10 / 11 (64-bit)
- Baza danych PostgreSQL — **instalator pobiera i konfiguruje ją automatycznie**, nie trzeba nic
  instalować ręcznie.

## Pobranie i instalacja

1. Pobierz najnowszy instalator z zakładki **[Releases](../../releases)** — plik `Setup_Lamina_v1.exe`.
2. Uruchom instalator (wymaga uprawnień administratora) i postępuj według kreatora.
3. Szczegółowa instrukcja wdrożenia (konfiguracja serwera, drukarki etykiet, dostęp z innych
   urządzeń) jest dołączona do wydania jako `LAMINA_Instrukcja_Wdrozenia.pdf`.

> Przy pierwszym uruchomieniu program tworzy plik `license_key.dat` z ID Twojej maszyny.
> Prześlij to ID dostawcy, aby otrzymać klucz aktywacyjny.

## Wersja demo

Dostępna jest w pełni funkcjonalna wersja **demo** (ograniczona czasowo) — idealna, aby
przetestować system na własnych danych przed zakupem. O klucz demo poproś dostawcę.

## Licencja
