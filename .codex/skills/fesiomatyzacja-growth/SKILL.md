---
name: fesiomatyzacja-growth
description: Audytuj i rozwijaj polskojęzyczne strony firm oferujących automatyzacje i usługi AI. Używaj przy zadaniach dotyczących Fesiomatyzacja.pro, landing page'y usług AI, SEO, treści marketingowych, CTA, social proof, UX, dostępności, Tailwind CSS, wydajności i optymalizacji konwersji.
---

# Fesiomatyzacja Growth

Udoskonalaj stronę jako produkt marketingowy i działającą aplikację. Łącz trafne komunikaty biznesowe z bezpieczną, dostępną i mierzalną implementacją.

## Przeprowadź pracę

1. Przeczytaj instrukcje repozytorium i rozpoznaj framework, routing, komponenty, system stylów, testy oraz sposób uruchamiania aplikacji.
2. Ustal stan bazowy: uruchom dostępne kontrole, obejrzyj stronę na typowych szerokościach i sprawdź konsolę przeglądarki. Użyj skilli `playwright` i `screenshot`, jeżeli są dostępne.
3. Zbuduj krótką hierarchię komunikacji: odbiorca i problem, obietnica rezultatu, dowód, sposób współpracy, redukcja ryzyka i jednoznaczne CTA.
4. Wprowadź najmniejszy spójny zestaw zmian. Zachowaj istniejący stack i wzorce komponentów; nie wykonuj niepowiązanych refaktorów.
5. Zweryfikuj semantykę HTML, obsługę klawiatury, fokus, kontrast, responsywność, metadane, dane strukturalne i wydajność.
6. Uruchom formatowanie, lint, testy i build przewidziane przez repozytorium. Po zmianie interfejsu wykonaj kontrolę wizualną i zapisz zrzut ekranu.
7. Podsumuj rezultaty, wykonane kontrole i elementy wymagające danych od właściciela firmy.

## Użyj modułu webdev

Przy audycie lub budowie interfejsu przeczytaj [moduł webdev](references/webdev.md) i wykonaj tylko części pasujące do zadania. Traktuj istniejący kod jako źródło prawdy dla frameworka, wersji Tailwind CSS, tokenów, komponentów i sposobu definiowania metadanych.

- Audytuj renderowany dokument, nie tylko kod źródłowy. Sprawdź indeksowalność, strukturę nagłówków, linki, obrazy, metadane i dane strukturalne.
- Generuj hero, CTA i social proof jako semantyczne, responsywne komponenty zgodne z wzorcami projektu. Nie zastępuj komponentów frameworka surowym HTML, jeżeli projekt ma właściwą abstrakcję.
- Optymalizuj `title`, opis, canonical, Open Graph i karty społecznościowe per trasa. Nie dodawaj przestarzałych ani zbędnych meta tagów.
- Mierz Core Web Vitals w reprezentatywnych warunkach, jeśli narzędzia i działająca aplikacja są dostępne. Rozróżniaj dane terenowe od laboratoryjnych i nie przedstawiaj estymacji jako pomiarów.
- Łącz propozycję techniczną z jej wpływem na użytkownika: czytelność, zaufanie, czas dotarcia do CTA, stabilność układu i szybkość reakcji.

## Stosuj zasady treści

- Pisz konkretnie po polsku, językiem korzyści, bez pustych superlatyw i żargonu.
- Nie wymyślaj klientów, opinii, logotypów, certyfikatów, liczb ani rezultatów. Gdy brak dowodów, dodaj wyraźnie oznaczone miejsce na zweryfikowane dane lub użyj uczciwego dowodu procesu.
- Nie obiecuj gwarantowanych wyników biznesowych. Oddzielaj możliwości systemu od potwierdzonych wdrożeń.
- Prowadź użytkownika do jednego głównego działania; drugie CTA może mieć niższy priorytet.
- Zachowuj istniejący ton marki. Zgłaszaj brakujące dane zamiast je zgadywać.

## Projektuj hierarchię

- Grupuj elementy przez bliskość, podobieństwo i wspólny obszar; używaj odstępów przed separatorami.
- Utrzymuj czytelną kolejność: etykieta, nagłówek, rozwinięcie, dowód, CTA.
- Ogranicz liczbę równorzędnych akcentów. Niech rozmiar, kontrast i przestrzeń wynikają z ważności treści.
- Projektuj mobile-first i sprawdzaj co najmniej widok mobilny oraz desktopowy.
- W Tailwind CSS preferuj tokeny i istniejące utility classes. Nie dodawaj arbitralnych wartości, gdy istnieje odpowiednik w systemie projektu.
- Szanuj `prefers-reduced-motion`; animacje mają wspierać orientację, a nie blokować treść.

## Optymalizuj SEO i jakość

Przeczytaj [checklistę audytu](references/audit-checklist.md) przed zmianą SEO lub całej strony. Użyj jej sekcji technicznej jako kryteriów akceptacji, ale pomijaj punkty nieadekwatne do wykrytego stacku. Nie duplikuj metadanych między trasami. Przy API zależnym od wersji frameworka sprawdź lokalną wersję i oficjalną dokumentację.

Traktuj wynik Lighthouse jako sygnał diagnostyczny, nie cel sam w sobie. Najpierw naprawiaj błędy użytkownika, indeksowania i semantyki, potem optymalizuj wskaźniki.

## Zachowaj bezpieczeństwo

Przy formularzach, analityce, integracjach i wdrożeniu użyj skilla `security-best-practices`, jeżeli jest dostępny. Nie ujawniaj sekretów, nie dodawaj danych osobowych do repozytorium i nie wysyłaj formularzy do niezatwierdzonych usług. Nie wdrażaj na produkcję bez jednoznacznej prośby użytkownika.
