# 🇩🇪 Nauka słów niemieckich

Aplikacja webowa do nauki słownictwa niemieckiego z fiszkami, quizami i modułem aktywnego przypominania. Działa w całości w przeglądarce — bez backendu, bez instalacji.

🔗 **[Otwórz aplikację →](https://skyllie.github.io/servise.io/)**

---

## ✨ Funkcje

- **📚 Fiszki** — przeglądaj słówka z animacją obrotu karty
- **✍️ Quiz DE → PL i PL → DE** — sprawdź znajomość słówek w obu kierunkach
- **🧠 Aktywne przypominanie** — wypisz z pamięci słówka w ograniczonym czasie, oceń siebie i śledź postępy
- **➕ Własne słowa** — dodawaj swoje słówka do bazy
- **❓ Nie znam** — oznaczaj trudne słówka i filtruj ćwiczenia tylko do nich
- **📊 Statystyki** — procent poprawnych odpowiedzi przy każdym słowie
- **⌨️ Skróty klawiszowe** — wygodna nawigacja bez myszki

---

## 🗂️ Wbudowane słownictwo

Aplikacja zawiera ~65 słów w 4 kategoriach tematycznych:

| Kategoria | Opis |
|-----------|------|
| 🌿 Przyroda | Elementy przyrody, zwierzęta, żywioły |
| 🌍 Geografia | Kontynenty, państwa, formy terenu |
| ♻️ Środowisko | Ekologia, odpady, zanieczyszczenia |
| 🌡️ Przymiotniki | Cechy klimatu i środowiska |

---

## 🚀 Uruchomienie

Nie wymaga instalacji ani serwera. Wystarczy otworzyć plik w przeglądarce:

```bash
git clone https://github.com/skyllie/servise.io.git
cd servise.io
# Otwórz index.html w przeglądarce
open index.html
```

Lub skorzystaj z wersji na żywo: **https://skyllie.github.io/servise.io/**

---

## 🧠 Metoda aktywnego przypominania

Moduł oparty na technice **Retrieval Practice** — jednej z najlepiej udokumentowanych metod zapamiętywania:

1. Wybierz kategorię i liczbę słów
2. Wypisz z pamięci tyle słów ile możesz w ciągu **2 minut**
3. Sprawdź wynik i oceń siebie (😊 Dobrze / 😅 Ciężko / 😬 Słabo)
4. Wróć do powtórki zgodnie z harmonogramem

---

## ⌨️ Skróty klawiszowe

| Tryb | Klawisz | Akcja |
|------|---------|-------|
| Fiszki | `Enter` | Odwróć kartę |
| Fiszki | `→` / `←` | Następna / poprzednia |
| Quiz | `Enter` | Sprawdź / następne |
| Quiz | `?` | Oznacz jako "nie znam" |

---

## 💾 Dane

Wszystkie słowa i statystyki zapisywane są lokalnie w `localStorage` przeglądarki — bez rejestracji i bez wysyłania danych gdziekolwiek.

---

## 🛠️ Technologie

- Czysty HTML / CSS / JavaScript (bez frameworków)
- Czcionki: [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) + [DM Sans](https://fonts.google.com/specimen/DM+Sans) via Google Fonts
- Persystencja: `localStorage`

---

## 📄 Licencja

MIT — możesz swobodnie używać, modyfikować i dystrybuować.
