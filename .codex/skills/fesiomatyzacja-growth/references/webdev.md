# Moduł webdev

## Audyt

1. Ustal framework, wersje zależności, strategię renderowania i sposób zarządzania metadanymi.
2. Uruchom aplikację i sprawdź najważniejsze trasy w przeglądarce na widoku mobilnym oraz desktopowym.
3. Zapisz problemy jako: dowód, wpływ, proponowana poprawka i sposób weryfikacji. Oddziel problemy potwierdzone od hipotez.
4. Nadaj priorytet błędom blokującym indeksowanie lub kontakt, następnie dostępności i Core Web Vitals, a na końcu dopracowaniu wizualnemu.

## Sekcje marketingowe

### Hero

- Użyj jednego `h1`, który nazywa rezultat i odbiorcę oferty.
- Dodaj krótkie rozwinięcie, główne CTA oraz opcjonalne CTA drugorzędne.
- Umieść najważniejszy dowód blisko obietnicy, o ile istnieje zweryfikowany materiał.
- Utrzymuj czytelny pierwszy ekran bez uzależniania przekazu od animacji lub obrazu.

### Social proof

- Modeluj dowody jako dane, aby można je było później podmienić bez przebudowy komponentu.
- Pokazuj tylko zatwierdzone logotypy, cytaty, rezultaty i studia przypadków.
- Dodaj kontekst wyniku: punkt wyjścia, zakres wdrożenia, okres i sposób pomiaru.
- Gdy brak referencji, pokaż transparentny proces, demonstrację lub technologie zamiast fikcyjnych rekomendacji.

### CTA

- Nazwij działanie i oczekiwany kolejny krok, np. „Umów 20-minutową konsultację”.
- Użyj prawdziwego linku lub działającego przycisku; nie pozostawiaj atrap interakcji.
- Zapewnij stan fokusu, ładowania, sukcesu i błędu odpowiedni do rodzaju działania.
- Powtórz CTA po wyjaśnieniu wartości, ale nie twórz konkurujących akcji o tej samej wadze.

## Implementacja HTML i Tailwind CSS

- Zachowaj semantyczne landmarki oraz logiczną strukturę nagłówków. Wybieraj element według znaczenia, a nie domyślnego wyglądu.
- Używaj istniejących komponentów, breakpointów, kolorów, promieni, cieni i skali odstępów.
- Grupuj treść przez bliskość i wspólny obszar. Stosuj podobieństwo dla elementów o tej samej funkcji, a kontrast dla najważniejszego CTA.
- Utrzymuj sensowną kolejność DOM na wszystkich breakpointach; nie naprawiaj kolejności wizualnej klasami `order-*`, jeśli pogarsza to nawigację.
- Preferuj CSS nad JavaScriptem dla układu i prostych stanów wizualnych. Nie dodawaj biblioteki tylko dla pojedynczego efektu.
- Zachowaj widoczny fokus i wystarczający kontrast. Sprawdź interfejs przy powiększeniu i ograniczeniu animacji.

## Metadane

- Twórz unikalny, opisowy `title` i opis odpowiadający treści konkretnej trasy.
- Ustaw canonical na właściwy publiczny URL i używaj bezwzględnych adresów obrazów społecznościowych.
- Utrzymuj spójność między tytułem, opisem, `h1`, Open Graph i faktyczną treścią strony bez mechanicznego powtarzania fraz.
- Dodawaj JSON-LD zgodny z typem widocznej treści. Waliduj wynik i nie publikuj niepotwierdzonych ocen, cen ani danych firmy.
- Sprawdź wygenerowany HTML, ponieważ poprawny kod komponentu nie gwarantuje poprawnych metadanych po renderowaniu.

## Core Web Vitals

- **LCP:** ustal element LCP; ogranicz jego rozmiar i opóźnienia, nadaj priorytet krytycznemu obrazowi oraz usuń zasoby blokujące pierwszy render.
- **INP:** ogranicz długie zadania, koszt hydratacji i pracę wykonywaną synchronicznie w handlerach; dziel pracę i usuwaj zbędny JavaScript.
- **CLS:** rezerwuj miejsce dla obrazów, embedów, bannerów i treści asynchronicznej; nie wstawiaj elementów nad już wyrenderowaną treścią.
- Rejestruj warunki testu, trasę, urządzenie i narzędzie. Dane CrUX lub RUM nazywaj terenowymi, a Lighthouse lub lokalny pomiar laboratoryjnymi.
- Po poprawce wykonaj ponowny pomiar tą samą metodą. Jeśli pomiar jest niemożliwy, opisz sposób jego wykonania zamiast deklarować wynik.

## Wynik pracy

Przekaż wdrożone zmiany, wyniki dostępnych testów i pomiarów, zrzuty zmienionych widoków oraz krótką listę dalszych działań. Wyraźnie oznacz dane lub decyzje potrzebne od właściciela strony.
