# Checklista strony usług AI

## Strategia i konwersja

- Określ głównego odbiorcę, jego problem i pożądany rezultat.
- Upewnij się, że pierwszy ekran wyjaśnia ofertę bez przewijania i bez wiedzy branżowej.
- Dodaj jedno główne CTA z informacją, co wydarzy się po kliknięciu.
- Wyjaśnij zakres usług, etapy współpracy, kryteria dopasowania i następny krok.
- Odpowiedz na realne obiekcje w FAQ; nie twórz pytań tylko po to, aby powtarzać słowa kluczowe.
- Użyj wyłącznie zweryfikowanego social proof. W razie braku przedstaw proces, kompetencje lub demonstrację zamiast fikcyjnych opinii.

## SEO techniczne i on-page

- Zapewnij unikalne `title`, opis, kanoniczny URL i jeden opisowy `h1` na stronę.
- Utrzymuj logiczną strukturę nagłówków i opisowe teksty linków.
- Dodaj Open Graph oraz kartę społecznościową z bezwzględnymi, działającymi adresami zasobów.
- Dodawaj JSON-LD tylko dla prawdziwych danych widocznych na stronie; nie oznaczaj fikcyjnych ocen ani opinii.
- Sprawdź `robots.txt`, mapę witryny, statusy HTTP, przekierowania, stronę 404 i indeksowalność właściwego środowiska.
- Używaj semantycznego HTML. Obrazy treściowe powinny mieć trafny `alt`, a dekoracyjne pusty `alt`.
- Nie upychaj fraz. Dopasuj język do intencji użytkownika i naturalnych polskich zapytań.

## Techniczna checklista strony usług AI

### Renderowanie i indeksowanie

- Sprawdź status HTTP i wyrenderowany HTML każdej istotnej trasy, w tym obecność tytułu, opisu, canonical i głównej treści bez wykonywania interakcji.
- Upewnij się, że środowisko produkcyjne nie ma przypadkowego `noindex`, a wersje testowe nie są indeksowane.
- Zweryfikuj spójność hosta, protokołu, końcowych ukośników, canonicali i przekierowań; unikaj łańcuchów przekierowań.
- Sprawdź mapę witryny, `robots.txt`, stronę 404 oraz linkowanie do ofert, realizacji, informacji o firmie i kontaktu.
- Jeżeli treść powstaje po stronie klienta, potwierdź jej dostępność dla crawlera albo zastosuj obsługiwane przez framework renderowanie serwerowe lub statyczne.

### Metadane i dane strukturalne

- Sprawdź unikalność oraz długość pod kątem czytelności `title` i opisów; nie przycinaj treści mechanicznie do arbitralnego limitu.
- Zweryfikuj podgląd udostępniania i dostępność obrazów Open Graph pod bezwzględnymi URL-ami.
- Upewnij się, że język dokumentu, favicony, manifest i metadane viewport są poprawne.
- Waliduj JSON-LD i zgodność nazw, adresów URL, danych kontaktowych, ofert oraz obrazów z widoczną treścią.

### Core Web Vitals i zasoby

- Zidentyfikuj element LCP i sprawdź jego format, rozmiar, priorytet, ładowanie oraz zależności blokujące renderowanie.
- Zlokalizuj długie zadania i nadmiarowy JavaScript wpływające na INP; sprawdź koszt komponentów klienckich, skryptów analitycznych i widgetów.
- Sprawdź źródła CLS: obrazy bez wymiarów, fonty, bannery cookies, embedy, formularze i treści ładowane asynchronicznie.
- Ogranicz liczbę wariantów fontów, preloadów i skryptów zewnętrznych. Każdemu preloadowi przypisz zasób potrzebny we wczesnym renderze.
- Porównuj pomiary przed i po zmianie w tych samych warunkach; zapisuj osobno wyniki laboratoryjne oraz dane terenowe.

### Komponenty i zachowanie

- Sprawdź hero, CTA, formularz i nawigację bez JavaScriptu, przy wolnej sieci oraz dla stanów ładowania, pustych danych i błędów.
- Upewnij się, że przyciski wykonują akcje, a linki nawigują; nie zamieniaj ich semantyki dla wyglądu.
- Sprawdź poprawność formularza po stronie klienta i serwera, ochronę przed spamem, komunikaty błędów oraz brak sekretów w kodzie klienckim.
- Zweryfikuj brak błędów konsoli, niedziałających żądań, mieszanej zawartości i linków prowadzących donikąd.
- Przetestuj co najmniej mały telefon, szeroki ekran, nawigację klawiaturą, powiększenie 200% i `prefers-reduced-motion`.

## Dostępność i formularze

- Zapewnij widoczny fokus, pełną obsługę klawiaturą i logiczną kolejność tabulacji.
- Powiąż etykiety z polami, opisuj błędy tekstem i utrzymuj je po nieudanej walidacji.
- Nie polegaj wyłącznie na kolorze. Sprawdź kontrast tekstu, kontrolek i stanów interakcji.
- Zapewnij odpowiednio duże cele dotykowe i respektuj ustawienia ograniczenia ruchu.
- Przy danych osobowych pokaż cel przetwarzania i odnośnik do właściwej polityki prywatności.

## Wydajność i implementacja

- Usuń nieużywany kod, ciężkie zależności i zasoby blokujące renderowanie.
- Dobierz rozmiary obrazów, nowoczesny format i lazy loading poza pierwszym ekranem; unikaj przesunięć układu.
- Ładuj fonty oszczędnie, deklaruj fallbacki i nie pobieraj zbędnych odmian.
- Nie dodawaj hydration ani kodu klienckiego do statycznych fragmentów bez potrzeby.
- Sprawdź stronę przy wolniejszej sieci, długich treściach, powiększeniu 200% i błędach API.

## Weryfikacja końcowa

- Uruchom formatter, lint, testy, typecheck i produkcyjny build dostępne w projekcie.
- Sprawdź konsolę, błędne żądania, linki wewnętrzne i formularze.
- Porównaj widoki mobilny oraz desktopowy i wykonaj zrzut finalnego interfejsu.
- W podsumowaniu oddziel wykonane zmiany od rekomendacji wymagających analityki, badań lub danych właściciela.
