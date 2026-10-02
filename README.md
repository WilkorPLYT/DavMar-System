<p align="center">
  <img src="portfolio-assets/davmar-logo.png" alt="DavMar — Transport, Spedycja, Logistyka" width="230" />
</p>

<h1 align="center">DavMar</h1>

<p align="center">
  <strong>Cyfrowe zaplecze wirtualnej firmy transportowej w Euro Truck Simulator 2</strong><br />
  Flota, kierowcy i planowanie przewozów — rozwijane w jednym projekcie.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-w%20rozwoju-2563eb?style=for-the-badge" alt="Projekt w rozwoju" />
  <img src="https://img.shields.io/badge/ETS2-1.61%20%7C%20cel-26364a?style=for-the-badge" alt="Docelowo ETS2 1.61" />
  <img src="https://img.shields.io/badge/ProMods-2.84%20%7C%20cel-26364a?style=for-the-badge" alt="Docelowo ProMods 2.84" />
</p>

> **Projekt jest w fazie rozwoju.** Pokazuję tu kierunek, kolejne etapy i umiejętności rozwijane podczas pracy nad DavMar. Makieta, prototyp API i klient Windows nie tworzą jeszcze gotowego systemu produkcyjnego.

## Pomysł

Prowadzenie wirtualnej firmy transportowej to coś więcej niż wybór kolejnego ładunku. DavMar ma z czasem połączyć w czytelnej przestrzeni **zarządzanie flotą, przydziały zestawów, planowanie tras i narzędzia dla kierowców**.

Projekt powstaje z myślą o firmach i społecznościach grających w ETS2. Docelowym środowiskiem jest ETS2 1.61 z ProMods 2.84 — zgodność z tymi wersjami pozostaje do sprawdzenia.

## Co rozwijam

### Flota i zestawy

Katalog ciągników i naczep, ich opisy i zdjęcia oraz przypisywanie kierowcy aktywnego zestawu: jednego ciągnika i jednej naczepy. Powstał już oddzielny prototyp API i ekran zarządzania flotą; rekordy można archiwizować zamiast usuwać.

### Rozpiski i ładunki

Docelowo rozpiska ma prowadzić kierowcę przez ciąg odcinków i dobierać ładunki zgodne z jego naczepą — osobno dla firanki i chłodni. Interfejs zawiera demonstracyjny generator; weryfikacja miast i dystansów względem ProMods oraz rzeczywisty katalog cargo ETS2 1.61 są jeszcze do przygotowania.

### Narzędzia dla kierowcy

Powstaje wczesny klient DavMar Connect dla Windows, który ma uzupełnić panel o lokalne narzędzia przydatne podczas jazdy. Obecny prototyp umożliwia diagnostyczny odczyt gry na komputerze użytkownika; nie wysyła telemetrii do serwera i nie został potwierdzony na ETS2 1.61.

### Panel i uprawnienia

Projekt obejmuje widoki dla kierowców i osób zarządzających firmą. Interaktywna strona demonstracyjna działa na przykładowych danych, a osobny prototyp API rozwijany jest niezależnie. To jeszcze nie jest jedna wdrożona aplikacja.

## Kierunek rozwoju

1. Oprzeć zgodność ładunków na zweryfikowanych definicjach SCS z ETS2 1.61.
2. Przygotować aktualny katalog miast ProMods i wiarygodne dystanse tras.
3. Połączyć zarządzanie flotą i rozpiski w spójny, przetestowany przepływ.
4. Sprawdzić logowanie, role i przechowywanie danych w oddzielnym środowisku testowym.
5. Rozwijać klienta Windows po weryfikacji na prawdziwej instalacji gry i ustaleniu zasad korzystania z telemetrii.
6. Rozważyć integrację z botem Discord dopiero po ustabilizowaniu pozostałych części.

Każdy etap ma prowadzić do praktycznego narzędzia — bez udawania, że demonstracja jest już gotowym produktem.

## Co pokazuje ten projekt

DavMar łączy projektowanie interfejsu z rozwijaniem zaplecza aplikacji. W ramach projektu pracuję nad:

- nowoczesnymi panelami WWW i dashboardami,
- API oraz modelowaniem danych,
- kontami, rolami i kontrolą dostępu,
- katalogami floty i przepływami operacyjnymi,
- prototypami aplikacji desktopowych dla Windows,
- testowaniem oraz dokumentowaniem kolejnych etapów.

**Technologie:** React, Vite, Node.js, Express, PostgreSQL, C# i .NET 8.

## Szukasz wykonawcy do swojego projektu?

Mogę pomóc zaprojektować i zbudować **panel administracyjny, dashboard, narzędzie do obsługi procesów, API lub prototyp aplikacji Windows** — dopasowany do konkretnego problemu i użytkowników.

Napisz przez [mój profil GitHub](https://github.com/WilkorPLYT) i opisz krótko, co chcesz usprawnić. Zakres współpracy ustalimy indywidualnie.

---

<p align="center"><sub>DavMar · projekt portfolio · aktywny rozwój · bez wdrożenia produkcyjnego</sub></p>
