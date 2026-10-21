# Pytania kontrolne i ćwiczenia

Materiały są ćwiczeniami autorskimi opartymi na pojęciach LAF 1.6; nie są oficjalnym egzaminem ani pytaniami kursowymi.

## Pytania kontrolne

1. Jakie trzy części tworzą LAF?
2. Czym różni się Reference Architecture od Solution Vision?
3. Jakie trzy perspektywy ocenia CPA i jakie kategorie cyklu życia opisuje LAF?
4. Kto dostarcza ocenę biznesową komponentu i kto aktualizuje jego atrybuty techniczne?
5. Dlaczego LAF zaleca, by architekt pozostawał w SDLC?
6. W jakich sytuacjach mały Fast Track może być właściwy?
7. Co powinno się stać po przekroczeniu progu metryki?
8. Kiedy wyjątek albo decyzja powinny trafić do Architectural Forum?
9. Czym MRAC różni się od artefaktów RA, ST i CP czytelnych dla ludzi?
10. Co w LAF 1.6 pozostaje poza zakresem sekcji o AI?

## Krótki klucz odpowiedzi

1. Definition, Execution, Improvement and Monitoring.
2. RA opisuje długoterminowy kierunek; SV opisuje przyrost rozwiązania dla konkretnej potrzeby biznesowej.
3. Perspektywy: biznesowa, techniczna, finansowa. Kategorie: Investment, Tolerance, Migration, Elimination.
4. Właściciel biznesowy uzgadnia/ocenia aspekt biznesowy; zespoły wytwórcze regularnie aktualizują atrybuty techniczne.
5. Aby architektura uwzględniała rzeczywiste potrzeby, stan i ograniczenia dostarczania, a nie działała w izolacji.
6. Dla małych zmian w jednej aplikacji, które nie zmieniają podstawowych zdolności.
7. Analiza/przegląd, retrospektywa i działanie korygujące zgodnie z ustaleniami organizacji.
8. Np. przy przekrojowych decyzjach, nowych komponentach/zdolnościach, standardach oraz niezgodnych lub niejednoznacznych przypadkach AI Fast Track.
9. MRAC jest maszynowo czytelną, zsynchronizowaną pochodną; dokumenty dla ludzi pozostają głównym źródłem prawdy.
10. Zarządzanie modelami AI, usługami AI i innymi technologiami AI jako pełny obszar ładu.

## Ćwiczenie: portfel i zmiana

Organizacja ma dwa systemy realizujące tę samą zdolność. Pierwszy jest krytyczny dla biznesu, lecz trudny i kosztowny w utrzymaniu. Drugi ma dobry stan techniczny, ale niską krytyczność. Przygotuj:

1. brakujące dane potrzebne do CPA (biznesowe, techniczne, finansowe, opinia użytkownika);
2. wstępną kategorię dla każdego komponentu, jawnie oznaczając niepewności;
3. pytania biznesowe i architektoniczne do sprawdzenia w RA;
4. zarys SV dla jednego przyrostu, wraz z NFR, zależnościami i oczekiwaną korzyścią;
5. metrykę lub wskaźniki, które pomogą ocenić postęp.

Nie zakładaj, że sama kategoria CPA automatycznie przesądza o decyzji migracji lub wycofania. Uzasadnij trade-off i wskaż, kto powinien zatwierdzić ocenę.

## Ćwiczenie: AI i MRAC

Zaproponuj minimalny zestaw pól w maszynowo czytelnym wyciągu RA i Standards dla agenta generującego kod. Wskaż, jak utrzymać zgodność z wersją ludzką, co można automatycznie walidować, jakie zmiany wymagają przeglądu architekta i co należy eskalować do Forum. Zaznacz, że zaproponowany schemat jest organizacyjną propozycją, a nie narzuconym przez LAF formatem.
