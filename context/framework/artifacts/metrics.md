# Metryki LAF

**Źródło: LAF 1.6, sekcja 3.1.6.**

Metryki pomagają obserwować postęp i kompromisy między szybkością dostarczania, wartością biznesową i kondycją architektury. LAF podaje cztery przykłady:

| Metryka | Co mierzy | Wzór wg przewodnika |
|---|---|---|
| Reference Implementation Metric (RIM) | udział SV zgodnych | compliant SV / wszystkie SV |
| Application Reference Metric (ARM) | relację liczby aplikacji ogółem do liczby aplikacji Investment i Tolerance | wszystkie aplikacje / (Investment + Tolerance) |
| Implemented Capabilities Redundancy Metric (ICRM) | nadmiar instancji zdolności względem celu | wdrożone instancje / docelowa liczba |
| Capability Reference Metric (CRM) | pokrycie zdolności z RA | używane zdolności / zdolności w RA |

RIM klasyfikuje SV jako **Compliant**, **Neutral** lub **Not compliant**. Przewodnik zaleca ustalanie progów, typowo kwartalny przegląd i analizę po przekroczeniu progu. RIM może być wyliczany programowo w scenariuszach AI z sekcji 5.

## Uwaga interpretacyjna

Metryka nie zastępuje decyzji. Wyższa lub niższa wartość nabiera znaczenia w kontekście, celu, zakresu i trendu. Progi i akceptowalna redundancja powinny być określone przez organizację. Wzory powyżej przepisano zgodnie z opisem przewodnika; przed użyciem operacyjnym warto potwierdzić definicje i danych wejściowych w organizacji.
