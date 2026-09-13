# Neon Apex — Traffic Racer

Kompletna, lokalna gra przeglądarkowa w stylu *Traffic Racer*, zbudowana na Three.js i Vite. Nie wymaga serwera, konta ani zewnętrznych assetów — środowiska oraz pojazdy są generowane proceduralnie w WebGL.

## Uruchomienie

```bash
npm install
npm run dev
```

Otwórz **dokładnie** `http://localhost:5173/` w przeglądarce na tym samym komputerze, na którym uruchomiono polecenie. Sama nazwa `localhost` bez portu nie działa. `localhost` wpisane na iPhonie wskazuje na iPhone’a, nie na komputer ani środowisko Claude CLI; aby grać na iPhonie, uruchom projekt bezpośrednio na nim albo udostępnij serwer w swojej sieci lokalnej. Do produkcyjnej kompilacji użyj `npm run build`.

## Sterowanie

- **Komputer:** `W` / `↑` gaz, `S` / `↓` hamowanie, `A` / `←` i `D` / `→` zmiana pasa.
- **Telefon / tablet:** przytrzymaj przyciski ekranowe.
- **Żyroskop:** naciśnij ikonę `◉` w HUD gry, potem zezwól przeglądarce na dostęp do czujników (jeśli go wymaga).

## Zawartość

- Cztery tryby: Endless, Two-Way, Time Trial i Police Chase.
- Pięć środowisk: miasto, noc, deszcz, śnieg i pustynia; nawierzchnie deszczu/śniegu obniżają prowadzenie.
- Dynamiczny ruch aut osobowych, SUV-ów, ciężarówek i autobusów, kolizje, bliskie wyprzedzania oraz combo.
- Garaż z czterema samochodami, zakupami, lakierem i trzema kategoriami ulepszeń.
- Punkty, kredyty i postęp są zapisywane lokalnie w `localStorage`.
