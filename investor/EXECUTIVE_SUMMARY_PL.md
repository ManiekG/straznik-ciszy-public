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

Docelowi klienci to szkoły i przedszkola w Polsce, docelowo w całej UE — segment EdTech/GovTech, gdzie zakupy często odbywają się w trybie zamówień publicznych. Produkt celuje w salę/oddział, nie w placówkę jako całość: **≈45 000 placówek, ale ≈344 000 sal** w Polsce (GUS, 2025/26) — pełna metodologia i źródła w `MARKET_ANALYSIS_EN.md`.

## Model biznesowy

**Wyłącznie sprzedaż urządzeń (hardware)** — jednorazowa transakcja, **bez abonamentu/SaaS** (potwierdzone przez założyciela 2026-09-15; wcześniejszy szkic błędnie zakładał powtarzalny komponent subskrypcyjny). Panel i analityka są częścią urządzenia, nie osobnym produktem. *Cennik i jednostkowa rentowność znane założycielowi — nieujawniane w tym dokumencie na jego wyraźną prośbę; pełny model jednostkowy dostępny w repo prywatnym pod NDA.*

## Trakcja i IP

- Zarejestrowana domena `cotakglosno.pl`.
- Zgłoszony wzór przemysłowy w Urzędzie Patentowym RP (UPRP) — chroni wygląd urządzenia.
- Istnieje działający sprzęt i firmware (ESP32 + MQTT), zgodnie z potwierdzeniem twórcy ("hardware i sygnalizacja już działają").

## Czego szukamy

Sprzedaż całości projektu (kod, firmware, IP, platforma, domena) za **4 000 000 PLN** — nie poszukiwanie inwestycji/rundy finansowania, lecz wyjście (exit) właściciela z projektu. Szczegóły oferty: `PITCH_DECK_PL.md`, slajd 8.

*Kwota przeniesiona z `../../straznik-ciszy-private/investor/VALUATION_EN.md`, gdzie jest oznaczona jako niezweryfikowana metodologicznie — potencjalny kupiec może o to zapytać.*

---
*Kontakt: Mariusz Głowacki.*
