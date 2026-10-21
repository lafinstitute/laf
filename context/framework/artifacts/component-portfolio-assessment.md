# Component Portfolio Assessment (CPA) i Component Passport (CP)

**Źródło: LAF 1.6, sekcja 3.1.3.**

CPA to praktyka zbierania i oceny informacji o aktualnych komponentach. Wyniki są zapisywane w Component Passport — zwięzłym opisie komponentu, który wspiera decyzje o jego dalszym kierunku.

Ocena obejmuje trzy perspektywy:

- **Biznesową:** krytyczność komponentu dla procesów.
- **Techniczną:** jakość kodu, efektywność pipeline'u, zgodność ze standardami i trendami, stos i wersje.
- **Finansową:** koszty licencji, infrastruktury, utrzymania i rozwoju; guide dopuszcza uproszczoną skalę pięciopunktową względem średnich organizacji.

Rezultatem jest jedna z kategorii cyklu życia:

| Kategoria | Wartość biznesowa / kondycja techniczna | Kierunek |
|---|---|---|
| Investment | wysoka / wysoka | rozwijać i inwestować |
| Tolerance | niższa krytyczność / wysoka | utrzymywać, m.in. ze względu na niski koszt i dobry stan |
| Migration | wysoka / niska | migrować zdolności do preferowanych systemów |
| Elimination | niska / niska lub nadmiarowa funkcjonalność | wycofać |

Proces obejmuje ocenę techniczną architekta, zebranie opinii użytkowników, ocenę finansową, ocenę biznesową właściciela, kategoryzację i komunikację zmian statusu. Oceny komponentów istotnych biznesowo powinny być uzgodnione z właścicielami biznesowymi; atrybuty techniczne powinny być regularnie aktualizowane przez zespoły wytwórcze.

LAF 1.6 dodaje **AI Footprint** — udział kodu lub logiki komponentu wygenerowanej przez AI — jako dodatkowy wymiar rozważań o utrzymywalności i ryzyku dostawcy.

## Zastrzeżenie

Progi kategoryzacji, częstotliwość ocen i konkretna zawartość CP zależą od organizacji. Kategorie nie zastępują uzgodnionej oceny biznesowej i technicznej.
