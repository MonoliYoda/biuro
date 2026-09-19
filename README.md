# Twoje biuro

Ten folder to biuro. Rozmawiasz z **dyrektorem biura**. On ma do dyspozycji personel i zleca mu pracę w Twoim imieniu.

| Kto | Czym się zajmuje |
|---|---|
| Badacz | Szuka w internecie: ceny, wykonawcy, przepisy, porównania |
| Analityk | Liczy: zestawia oferty, kosztorysy, arkusze |
| Redaktor | Pisze: pisma, maile, notatki, podsumowania |
| Sceptyk | Sprawdza gotową pracę, zanim do Ciebie trafi |
| Kontroler | Pilnuje terminów we wszystkich projektach |

## Pierwszy raz

Biuro działa w Claude Code. Pobierz ten folder na swój komputer, otwórz go w Claude Code i napisz `/zaczynamy`:

```
git clone https://github.com/MonoliYoda/biuro.git
cd biuro
claude
```

Dyrektor się przedstawi, zapyta, jak się do Ciebie zwracać i czym się teraz zajmujesz, założy dwa pliki biura (`USTAWIENIA.md` i `REJESTR.md`), a potem pomoże założyć pierwszy projekt.

## Na co dzień

Po prostu napisz, czego potrzebujesz. Na przykład:

- „Mamy trzy oferty na elewację. Która jest najlepsza?”
- „Przygotuj pismo do wspólnoty w sprawie terminu remontu.”
- „Co wiemy o firmie, która chce kupić spółkę?”
- „Co dziś wymaga mojej uwagi?”

Przydatne polecenia:

- `/nowy-projekt` zakłada akta nowej sprawy
- `/przeglad` sprawdza terminy i sprawy otwarte we wszystkich projektach
- `/zatrudnij` dodaje do personelu nową osobę o specjalności, której Ci brakuje

## Trzy zasady biura

1. **Nic nie wychodzi bez Twojej zgody.** Biuro przygotowuje projekty pism i maili. Wysyłasz je Ty.
2. **Decyzje są Twoje.** Dostajesz warianty i rekomendację. Każda Twoja decyzja trafia do dziennika projektu.
3. **Biuro pamięta za Ciebie.** Wszystko jest w aktach w folderze `projekty/`. Możesz tam zajrzeć w każdej chwili: to zwykłe pliki tekstowe.

## Gdzie co leży

- `USTAWIENIA.md` to Twoje dane: jak się do Ciebie zwracać i od kiedy działa biuro
- `REJESTR.md` to lista wszystkich projektów
- `projekty/<nazwa>/` to akta jednej sprawy: brief, dziennik, sprawy otwarte, dokumenty
- `projekty/<nazwa>/materialy/` to miejsce na to, co dostajesz z zewnątrz: oferty, skany, umowy. Wrzuć plik i powiedz o nim dyrektorowi
- `przeglady/` to raporty z przeglądów
