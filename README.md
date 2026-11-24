# Rodzinne Mikołajki 2026

React + TypeScript + Vite, bez backendu. Node.js 22.

## Lokalnie

```sh
npm install
npm run dev
```

## GitHub Pages

1. Utwórz publiczne repozytorium na GitHubie (darmowe Pages).
2. Wgraj zawartość projektu, w tym ukryty katalog `.github`, na gałąź `main`.
3. Settings → Pages → Build and deployment → Source → GitHub Actions.
4. Actions → Deploy GitHub Pages → Run workflow (jeśli nie uruchomił się automatycznie).
5. Otwórz adres z udanego wdrożenia. Wygeneruj losowanie tylko raz na docelowej stronie HTTPS i prześlij każdemu jego link.

## Prywatność

Każdy link zawiera jeden wynik zaszyfrowany AES-GCM oraz jego klucz w fragmencie URL, który nie jest wysyłany do serwera HTTP. Nie zawiera pozostałych wyników. Każdy posiadacz linku może go odczytać. Organizator i osoba mająca dostęp do jego przeglądarki mogą otworzyć wszystkie zapisane linki. Nie ma globalnej blokady ponownego losowania: inna przeglądarka może utworzyć niezależne losowanie. Wysłanych linków nie da się unieważnić. Imiona i przypisania z 2025 są w publicznym kodzie; wyniki 2026 nie trafiają do repozytorium. Wygeneruj linki na docelowym adresie, nie na localhost. Nie udostępniaj listy linków publicznie.

Algorytm wylicza wszystkie poprawne permutacje i wybiera jedną równomiernie za pomocą Web Crypto. Wyklucza siebie i zeszłorocznego odbiorcę, nie wyklucza partnerów ani odwrotnych par.
