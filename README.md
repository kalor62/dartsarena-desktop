<div align="center">

# 🎯 DartsArena Desktop

**Most między tarczą Autodarts a [DartsArena.pl](https://dartsarena.pl)**

[![Latest Release](https://img.shields.io/github/v/release/kalor62/dartsarena-desktop?label=wersja&color=blue)](https://github.com/kalor62/dartsarena-desktop/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/kalor62/dartsarena-desktop/total?label=pobrania&color=green)](https://github.com/kalor62/dartsarena-desktop/releases)
[![Platforms](https://img.shields.io/badge/platforma-macOS_%7C_Windows_%7C_Linux-orange)](#-pobieranie)

</div>

---

## ✨ Co to jest

Aplikacja desktopowa, która łączy lokalny **Autodarts Board Manager** z platformą **DartsArena.pl**.  
Dzięki niej Twoja tarcza Autodarts automatycznie wysyła rzuty do gier online, treningów i turniejów na DartsArenie — nie musisz nic klikać.

---

## 📥 Pobieranie

> Wybierz wersję dla swojego systemu i kliknij — pobieranie zacznie się od razu.

### 🍎 macOS

| Procesor | Pobierz |
|----------|---------|
| **Apple Silicon** (M1/M2/M3/M4) | **[⬇️ Pobierz dla Maca z Apple Silicon](https://github.com/kalor62/dartsarena-desktop/releases/latest/download/DartsArena-Desktop-0.1.1-arm64.dmg)** |
| **Intel** | **[⬇️ Pobierz dla Maca Intel](https://github.com/kalor62/dartsarena-desktop/releases/latest/download/DartsArena-Desktop-0.1.1.dmg)** |

> 💡 Nie wiesz który Mac masz? Menu **Apple () → About This Mac**. Jeśli widzisz **"Apple M1/M2/M3/M4"** — Apple Silicon. Jeśli **"Intel"** — Intel.

### 🪟 Windows

| Wariant | Pobierz |
|---------|---------|
| **Installer** (zalecane) | **[⬇️ Pobierz instalator Windows](https://github.com/kalor62/dartsarena-desktop/releases/latest/download/dartsarena-desktop-0.1.1-setup.exe)** |
| **Portable** (bez instalacji) | **[⬇️ Pobierz wersję portable](https://github.com/kalor62/dartsarena-desktop/releases/latest/download/DartsArena-Desktop-0.1.1.exe)** |

> ⚠️ **Windows SmartScreen** może pokazać ostrzeżenie ("Windows protected your PC") — kliknij **"More info" → "Run anyway"**. To normalne dla aplikacji bez płatnego certyfikatu EV, aplikacja jest bezpieczna.

### 🐧 Linux

| Format | Pobierz |
|--------|---------|
| **AppImage** (uniwersalny) | **[⬇️ Pobierz AppImage](https://github.com/kalor62/dartsarena-desktop/releases/latest/download/DartsArena-Desktop-0.1.1.AppImage)** |

> 💡 Po pobraniu nadaj uprawnienia do uruchomienia:
> ```bash
> chmod +x DartsArena-Desktop-*.AppImage
> ./DartsArena-Desktop-*.AppImage
> ```

---

## 🔄 Auto-aktualizacje

Aplikacja sprawdza nowe wersje **w tle co 6 godzin** i pobiera je automatycznie. Następnym razem gdy ją zamkniesz i otworzysz — będzie już zaktualizowana. Bez klikania.

---

## 🚀 Pierwsze uruchomienie

1. **Zainstaluj** aplikację (DMG / Installer / AppImage)
2. **Zaloguj się** swoim kontem [DartsArena.pl](https://dartsarena.pl) (jeszcze nie masz? [zarejestruj się tutaj](https://dartsarena.pl/register))
3. **Połącz Autodarts** — aplikacja sama wykryje Twoje urządzenie w sieci lokalnej
4. **Graj** — wszystkie rzuty automatycznie lecą do DartsAreny

---

## 🛠️ Rozwiązywanie problemów

### macOS: "Aplikacja jest uszkodzona / nie można otworzyć"
Aplikacja jest podpisana certyfikatem Apple Developer ID i znotaryzowana, więc nie powinno być problemu. Jeśli jednak macOS marudzi — kliknij PPM na DartsArenę → **Otwórz** → **Otwórz** w okienku.

### Windows: SmartScreen / Defender blokuje
Patrz wyżej — kliknij **More info → Run anyway**. Dla najwyższego komfortu możesz dodać aplikację do wyjątków Defendera.

### Linux: AppImage się nie uruchamia
Upewnij się że jest wykonywalny (`chmod +x`) i masz `libfuse2` zainstalowane:
```bash
sudo apt install libfuse2  # Ubuntu/Debian
```

### Aplikacja nie widzi Autodarts
Sprawdź:
- Tarcza i komputer są w **tej samej sieci Wi-Fi**
- W zaporze nie ma blokady portów 3180 / 8079
- W Autodarts panel admin jest włączone "Allow LAN connections"

---

## 📋 Wszystkie wersje

Pełna historia wydań, changelogi i starsze wersje: **[Releases](https://github.com/kalor62/dartsarena-desktop/releases)**

---

## ℹ️ O projekcie

To repozytorium hostuje **wyłącznie podpisane binarki i manifesty auto-updatera**. Kod źródłowy aplikacji znajduje się w prywatnym repozytorium głównego projektu DartsArena.

- 🌐 Strona: [dartsarena.pl](https://dartsarena.pl)
- 📧 Kontakt: kontakt@dartsarena.pl
- 🐛 Zgłaszanie błędów: [Issues](https://github.com/kalor62/dartsarena-desktop/issues)

---

<div align="center">

Made with 🎯 by **DartsArena Team**

</div>
