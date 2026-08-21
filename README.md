# KOŚCIUSZKO · FREEDOM — baza produkcyjna

Baza wszystkich zależności filmu krótkometrażowego **„Freedom"** (~7 min, produkcja w pełni AI) o Tadeuszu Kościuszce i jego walce o niepodległość Stanów Zjednoczonych: postacie, sceny, wątki, oś czasu, muzyka i referencje generacyjne (Higgsfield).

## Wersje / Versions

PL: `Kosciuszko_Baza_Zaleznosci.html` (oś czasu) + `Kosciuszko_Graf_Zaleznosci.html` (mapa postaci + graf) · EN: `Kosciuszko_Timeline_EN.html` + `Kosciuszko_Graph_EN.html`.

## Dwa widoki tej samej bazy

| Plik | Widok |
|---|---|
| [`Kosciuszko_Baza_Zaleznosci.html`](Kosciuszko_Baza_Zaleznosci.html) | **Pionowa oś czasu z mapą narracyjną** — tory bohaterów (kropka = obecność w scenie, linia = ciągłość, pozioma nić = współobecność), karty 16 scen w 3 aktach, oś historyczna 1746–1817, wątki, cue sheet M1–M10, referencje AI ze statusami |
| [`Kosciuszko_Graf_Zaleznosci.html`](Kosciuszko_Graf_Zaleznosci.html) | **Interaktywny graf powiązań** (vis-network, wszyty — działa offline) — 120 węzłów / 221 krawędzi; węzły można przeciągać i zostają tam, gdzie je upuścisz; „↺ Przetasuj układ" rozkłada graf od nowa; panel szczegółów, filtry typów, wyszukiwarka |

Wszystkie pliki są samodzielne — wystarczy otworzyć w przeglądarce; miniaturki twarzy są wszyte (base64), więc całość działa offline. Graf otwiera się na Mapie postaci (kółka z twarzami + podpisane relacje „kto z kim i dlaczego"); pełna baza pod zakładką „Pełny graf".

## Zawartość bazy

- **12 postaci** — kanon recastingu z sekcjami NOT i kluczowymi kwestiami
- **16 scen** wg scenariusza „Freedom" pl v2 (+ kanony rozbudowane Saratogi i Jeffersona), z timecodami filmowymi 0:00–10:00 i latami historycznymi 1776–1798
- **40 sekwencji Seedance** (mapowanie SEQ ↔ sceny)
- **8 wątków** (Deklaracja, sumienie/niewolnictwo, testament-klamra, inżynier nie wojownik, wartość życia, płomień, pokora, ocean)
- **cue sheet M1–M10** wg koncepcji muzycznej „Płomień" (d-moll → D-DUR)
- **referencje Higgsfield** — media_id / job ID ze statusami produkcyjnymi

## Aktualizacja danych

Dane siedzą w stałych JavaScript na początku sekcji `<script>` każdego pliku:
oś czasu → `POSTACIE / SCENY / WATKI / MUZYKA / REFERENCJE / HISTORIA / TORY / KOLOR_POSTACI`;
graf → `NODES / EDGES / SEQS / PORTRETY`.

---

Projekt: Marcin Rossa · creait.me · 2026
