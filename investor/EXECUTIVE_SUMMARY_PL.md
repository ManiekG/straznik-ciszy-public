# Executive Summary PL — Strażnik Ciszy (Investor Ready v5.2)

> ⚠️ **SZKIC** — napisany przez Claude na bazie znanych faktów o projekcie, nie treść wcześniej wygenerowana. Sprawdź i popraw każde stwierdzenie przed pokazaniem komukolwiek na zewnątrz.

## Problem

Poziom hałasu w klasach szkolnych i częściach wspólnych jest trudny do obiektywnego monitorowania. Nauczyciele i dyrekcja opierają się zwykle na subiektywnej ocenie, bez ciągłych, popartych danymi narzędzi do śledzenia trendów hałasu, wyłapywania problematycznych okresów czy wykazania poprawy w czasie.

## Rozwiązanie

**Strażnik Ciszy** to urządzenie IoT i platforma do monitorowania hałasu, stworzone z myślą o szkołach:

- Czujnik oparty o ESP32 mierzy poziom hałasu w sposób ciągły i publikuje odczyty przez MQTT.
- Dane trafiają do samodzielnie hostowanej infrastruktury (broker EMQX → InfluxDB → Grafana) do przechowywania i wizualizacji.
- **Panel sekretariatu** daje personelowi szkoły prosty widok dashboardu w przeglądarce.
- **Wyświetlacze sygnalizacyjne** (warianty BASIC / PRO) dają uczniom i nauczycielom wizualną informację zwrotną w czasie rzeczywistym (np. sygnalizacja świetlna poziomu hałasu).

## Rynek

Docelowi klienci to szkoły podstawowe i średnie w Polsce, docelowo w całej UE — segment EdTech/GovTech, gdzie zakupy często odbywają się w trybie zamówień publicznych (szczegóły w `MARKET_ANALYSIS_EN.md` — obecnie szkic wymagający realnych danych rynkowych).

## Model biznesowy

Sprzedaż urządzeń (hardware) połączona z powtarzalnym komponentem SaaS (dashboard, przechowywanie danych, analityka) — zgodnie z pierwotnymi założeniami projektu. *Konkretny cennik i jednostkowa rentowność wymagają jeszcze uzupełnienia.*

## Trakcja i IP

- Zarejestrowana domena `cotakglosno.pl`.
- Zgłoszony wzór przemysłowy w Urzędzie Patentowym RP (UPRP) — chroni wygląd urządzenia.
- Istnieje działający sprzęt i firmware (ESP32 + MQTT), zgodnie z potwierdzeniem twórcy ("hardware i sygnalizacja już działają").

## Czego szukamy

*Do uzupełnienia — kwota, przeznaczenie środków i kamienie milowe nie zostały jeszcze określone w materiałach źródłowych do tego szkicu.*

---
*Kontakt: Mariusz Głowacki.*
