# 🧠 Portfolio Interaktywne – Makieta Frontendowa

> **Wersja robocza interaktywnego portfolio** tworzonego przez [Hubert Nastachowskiego] jako koncept architektury informacji i demonstracja kreatywnej pracy z technologiami webowymi.

## 📐 Cel projektu

Celem makiety jest zaprezentowanie:
- zdolności do projektowania przemyślanego UI/UX,
- umiejętności technicznych w zakresie animacji, interaktywności i nowoczesnego frontendu,
- konceptów z obszaru architektury informacji i projektowania narracji wizualnej.

## 🛠 Technologie i narzędzia

| Technologia     | Opis |
|-----------------|------|
| `HTML5`         | Struktura strony |
| `TailwindCSS`   | Stylowanie z użyciem utility-first CSS |
| `GSAP`          | Animacje wejścia, przewijania, mikrointerakcje |
| `Three.js`      | Interaktywna scena 3D (np. tło, obiekt, nawigacja) |
| `Figma`         | Wstępna makieta i prototypowanie interfejsu |

## 🚧 Status projektu

🔹 **Etap:** wstępna makieta funkcjonalna (v0.3)  
🔹 **Niegotowe:** brak wersji mobilnej, optymalizacji i dostępności  
🔹 **Planowane:** routing + komponenty, opcjonalna sekcja CMS/API, wersja produkcyjna

## 🧩 Struktura katalogów
Index.html - główna tresć
GFX - Grafiki/Zdjęcia
(Strona jest na tyle mała, że nie widzę sensu rozbijać jej na wiele plików)


## 💡 Funkcje interaktywne

- 🔄 płynne przejścia sekcji za pomocą `GSAP ScrollTrigger`
- 🖱️ efekty na hover i klik z użyciem animowanych klas Tailwind
- 🌐 dynamiczne tło 3D (np. `three.js` z shaderem lub modelem `.glb`)
- 🧭 interfejs oparty o grid i kontrastowe kolory (styl: neobrutalizm)

## ✅ TODO

### 🎨 UI/UX

- [ ] Dodanie wersji responsywnej (mobilnej i tabletowej)
- [ ] Dodanie przełącznika trybu jasny/ciemny
- [ ] Refaktoryzacja struktury komponentów (`/components/`)
- [ ] Ujednolicenie typografii i przestrzeni międzysekcyjnych

### 🧠 Architektura informacji

- [ ] Weryfikacja kolejności sekcji pod kątem narracji użytkownika
- [ ] Dodanie skrótu nawigacyjnego „Przejdź do” (dla dostępności)
- [ ] Testowanie czytelności tekstów w wysokim kontraście (WCAG AA)

### 🔁 Interakcje i animacje

- [ ] Ulepszenie płynności animacji scrollowania (GSAP + debounce)
- [ ] Dodanie animacji przy ładowaniu strony (`gsap.timeline`)
- [ ] Wprowadzenie mikrozachowań UI (hover, kliknięcia, skupienie)

### 🧩 Rozszerzenia funkcjonalne

- [ ] Dodanie trybu prezentacji projektów w modalach lub lightboxie
- [ ] Podpięcie CMS-a do sekcji „projekty” (np. Contentful lub lokalny JSON)
- [ ] Opcjonalne: routing (np. `page.js`, `astro`, `next.js`)

### 🔍 Testowanie i optymalizacja

- [ ] Testy działania w Safari, Firefox i mobilnych Chrome
- [ ] Optymalizacja wag zasobów (`.glb`, fonty, obrazy)
- [ ] Lighthouse score >90 dla Desktop (Performance, SEO, A11y)
- [ ] Analiza użyteczności (heurystyczny audyt własny)

### 📤 Deployment

- [ ] Konfiguracja pod GitHub Pages / Netlify / Vercel
- [ ] Automatyczny deploy po pushu na main (`gh-pages` lub `netlify.toml`)
- [ ] Dodanie favicon + meta-tagów (`og:title`, `description`, `twitter:image`)


## 🧪 Jak uruchomić lokalnie

Wystarczy zainstalować darmowy program webstorm i uruchomić z przeglądarce lub visual studio z rozszerzeniem live..
