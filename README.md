```markdown
# 🎨 ASCII Art Generator

Prosty generator ASCII art, który zamienia tekst na znakowe banery.  
Świetny do ozdabiania plików README, komunikatów w terminalu lub do czystej zabawy.

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![JavaScript](https://img.shields.io/badge/made%20with-JavaScript-F7DF1E.svg)

## ✨ Funkcje

- 🔠 **Obsługiwane znaki**: A–Z, 0–9, oraz `! ? . , - :` (spacja też działa)
- 📏 **Stała wysokość** – każda litera ma 6 wierszy
- 📋 **Kopiuj jednym kliknięciem**
- 💾 **Zapis do pliku `.txt`**
- ↩️ **Obsługa nowych linii** – wpisz `\n` lub naciśnij Enter, aby złamać wiersz
- 📱 **Responsywny interfejs** – działa na desktopie i telefonie

## 🖼️ Przykład

Dla wejścia:

```
HELLO\nWORLD
```

generator wypisze coś w stylu:

```
 █████╗  ███████╗ ██████╗ ██╗
██╔══██╗██╔════╝██╔════╝ ██║
███████║███████╗██║      ██║
██╔══██║╚════██║██║      ██║
██║  ██║███████║╚██████╗ ██║
╚═╝  ╚═╝╚══════╝ ╚═════╝ ╚═╝

██╗   ██╗ █████╗ ██████╗ ████████╗
██║   ██║██╔══██╗██╔══██╗╚══██╔══╝
██║   ██║███████║██████╔╝   ██║   
╚██╗ ██╔╝██╔══██║██╔══██╗   ██║   
 ╚████╔╝ ██║  ██║██║  ██║   ██║   
  ╚═══╝  ╚═╝  ╚═╝╚═╝  ╚═╝   ╚═╝   
```

> Rzeczywisty wygląd zależy od czcionki użytej w przeglądarce – monospace daje najlepsze efekty.

## 🚀 Uruchomienie

1. Pobierz repozytorium:
   ```bash
   git clone https://github.com/twoja-nazwa/ascii-art-generator.git
   cd ascii-art-generator
   ```
2. Otwórz plik `index.html` w dowolnej przeglądarce.
3. Wpisz tekst, naciśnij **Generuj** i gotowe.

Żadnych dodatkowych zależności, serwerów, instalacji.

## 🧩 Użycie

1. Wpisz tekst w pole tekstowe. Możesz używać:
   - wielkich/małych liter (automatycznie zamieniane na wielkie)
   - cyfr
   - znaków specjalnych: `! ? . , - :`
2. Aby uzyskać nową linię:
   - wpisz dosłownie `\n` (ukośnik + litera n), lub
   - naciśnij klawisz **Enter** wewnątrz pola tekstowego.
3. Kliknij **Generuj**.
4. Skopiuj wynik (przycisk **Kopiuj**) lub zapisz do pliku (przycisk **Zapisz TXT**).

## 📂 Struktura

```
ascii-art-generator/
├── index.html      # strona główna
├── style.css       # wygląd i responsywność
├── script.js       # silnik ASCII art
└── README.md       # ten plik
```

## 🛠️ Technologie

- HTML5
- CSS3 (Flexbox, media queries)
- Vanilla JavaScript (ES6)

## 🤝 Współpraca

Jeśli masz pomysł na dodatkowe znaki, lepsze wyrównanie lub nowe funkcje – zapraszam do zgłaszania **issues** i **pull requests**!

## 📄 Licencja

Projekt dostępny na licencji **MIT** – możesz go swobodnie używać i modyfikować.

---

⭐ **Jeśli projekt Ci się podoba, postaw gwiazdkę na GitHubie!** ⭐
```
