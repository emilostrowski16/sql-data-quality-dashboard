# sql-data-quality-dashboard
Opis projektu: System monitorowania ruchu klientów w sieciach handlowych. Rozwiązanie automatyzuje wykrywanie braków danych i monitoruje jakość raportowania z poszczególnych placówek.

Stack technologiczny:
Baza danych: PostgreSQL 
Wizualizacja: Grafana 
Logika: SQL (JOIN, CTE, agregacje)

Kluczowe funkcjonalności:
Monitoring Staleness: Skrypt identyfikuje sklepy, które przestały raportować dane (np. brak raportu powyżej 7 dni).
Data Quality Score: Klasyfikacja statusów jakościowych (np. WARN_SPIKE, PARTIAL, NO_FILES) w celu szybkiej identyfikacji awarii sensorów.
Dynamiczne rankingi: Tworzenie zestawień popularności sklepów w oparciu o sumaryczną liczbę wejść.
