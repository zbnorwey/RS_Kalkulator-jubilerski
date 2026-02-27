# 💍 ROSSO - Kalkulator Mas i Kosztów

Profesjonalna aplikacja typu **PWA (Progressive Web App)** stworzona dla pracowni jubilerskiej. Pozwala na precyzyjne obliczanie masy obrączek oraz generowanie eleganckich specyfikacji dla klientów.

## 🚀 Główne Funkcje

* **Precyzyjne Obliczenia**: Kalkulator uwzględnia kruszec (złoto 333, 585, 750, srebro 925), rozmiar, szerokość, grubość oraz profil obrączki (płaska, soczewka, półokrągła).
* **Tryb Pary/Pojedynczy**: Możliwość wyceny jednej obrączki lub pary jednocześnie.
* **Widok Klienta**: Specjalny tryb prezentacji, który ukrywa panel edycji i przygotowuje ofertę do zrobienia zrzutu ekranu lub wydruku.
* **Wydruk na dwie strony**: Zoptymalizowany podział strony (CSS Print), który dzieli specyfikację na dwie części bez ucinania kart.
* **Działanie Offline**: Dzięki technologii Service Worker aplikacja działa bez dostępu do internetu po pierwszym uruchomieniu.

## 📱 Instalacja (PWA)

Aplikację można zainstalować na smartfonie:
1. Otwórz link do aplikacji w przeglądarce Chrome (Android) lub Safari (iOS).
2. Wybierz opcję **"Dodaj do ekranu głównego"**.
3. Aplikacja pojawi się na pulpicie z dedykowaną ikoną i będzie działać w trybie pełnoekranowym.

## 🛠️ Technologie

* **HTML5 / CSS3** (Flexbox, Grid, Media Queries)
* **JavaScript** (Logika obliczeń, Service Worker)
* **JSON** (Web App Manifest)

## 📁 Struktura plików

* `index.html` - Główny plik aplikacji i style.
* `manifest.json` - Konfiguracja instalacji i ikony.
* `sw.js` - Skrypt obsługujący tryb offline.
* `assets/icons/` - Folder z autorskimi ikonami aplikacji.

---
*Projekt stworzony na potrzeby pracowni ROSSO.*
