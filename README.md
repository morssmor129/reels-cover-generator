# Kreator okładek do rolek
**Jester Ads | Wersja 1.1.0**

Instrukcja dla asystenta AI: konfiguracja stylu marki, okładki 9:16, poprawki z oryginalnej fotografii i uporządkowane pliki.

## Skopiuj do nowego czatu
```text
Uruchom START.md z tego repozytorium:
https://github.com/morssmor129/reels-cover-generator
```

Asystent powinien odczytać [START.md](START.md), sprawdzić dostępne narzędzia i rozpocząć konfigurację.
Potrzebuje dostępu do linków i narzędzia do składu warstwowego. Sam link nie instaluje edytora ani nie zapewnia dostępu do dysku.
Jeśli nie otwiera linków, otwórz START.md i wklej jego treść do czatu.

1. Podaj nazwę marki i odpowiedz na pięć pytań: czcionki, kolory, klimat, wielkość liter i logo/dodatki.
2. Opcjonalnie załącz 1-3 referencje. Zatwierdź swój **Master Style**.
3. Prześlij **oryginalne zdjęcie**, dokładny nagłówek i opcjonalny podtytuł.

## Pliki kreatora
- [START.md](START.md) - pełna instrukcja i pięć pytań konfiguracyjnych.
- [MASTER_STYLE_SZABLON.txt](MASTER_STYLE_SZABLON.txt) - pusty profil klienta.
- [Instrukcja uruchomienia - PDF, 1 strona](docs/instalacja.pdf).

## Automatyczny porządek, gdy asystent ma dostęp do folderu
W folderze klienta kreator tworzy lub wykorzystuje dwa główne katalogi. Każda okładka ma własny identyfikator z datą i nazwą: `YYYY-MM-DD_nazwa-okladki_01`. Przykład:

```text
folder-klienta/
  01_MATERIALY_ZRODLOWE/
    marka/
      MASTER_STYLE.txt
      referencje/
    2026-11-02_nazwa-okladki_01/
      oryginal.jpg
  02_PRODUKCJA/
    2026-11-02_nazwa-okladki_01/
      projekt/
      robocze/
      final/
      status-zlecenia.txt
```

- **Materiały źródłowe:** oryginalne zdjęcia i zasoby marki, bez nadpisywania.
- **Produkcja:** osobny katalog każdej okładki; wszystkie jej poprawki zostają razem.
- **Final:** tylko wersje wyraźnie zaakceptowane przez klienta. Oględziny asystenta nie zastępują tej akceptacji.

Przy braku dostępu do folderu asystent informuje o ograniczeniu. Nie deklaruje zapisu plików na komputerze.

## Kontrola przed oddaniem
Każda wersja musi przejść kontrolę: oryginalna osoba i scena, dokładny tekst, Master Style, czytelność i kadry, rzeczywisty eksport oraz właściwy zapis.
Wynik trafia do raportu kontroli. Błąd krytyczny zatrzymuje oddanie wersji. Sprawdzony plik otrzymuje status **do_akceptacji**; dopiero decyzja klienta daje status **zaakceptowana** i kopię w `final/`.

## Zawsze z oryginału
Każdy eksport i każda poprawka powstają z **oryginalnego zdjęcia i aktualnych warstw**. Nie przerabiamy kolejnych wygenerowanych okładek.
Teksty, cienie i dodatki są niezależne od fotografii. Zmiana napisów nie oznacza regenerowania twarzy, dłoni, ubrania lub tła.

Zachowaj Master Style i materiały u siebie. Nie dodawaj ich do publicznego repozytorium. W nowym czacie wskaż właściwy profil i folder.

## Obserwuj Jester Ads
[Instagram - porady i kolejne materiały](https://track.jesterads.pl/jesterads-instagram/reels-cover-generator)
