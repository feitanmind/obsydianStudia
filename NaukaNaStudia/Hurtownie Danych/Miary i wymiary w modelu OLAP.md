**Miara** jest podstawowym pojęciem schematu pojęciowego, ma charakter liczbowy (np. ilość sprzedanych produktów, średnia ocen studentów, średnie zarobki)
Z każdą miarą jest związany zbiór wymiarów, od których zależy wartość danej miary (np. ilość sprzedanych produktów w zależności od produktu, czasu sprzedaży, czy miejsca sprzedaży). Wymiarami mogą być: produkt, lokalizacja, czas.
Relacja wiążąca wymiary z miarą (zbiorem miar) nazywamy **tablicą faktów**.
Informacja o wymiarach jest reprezentowana przez zbiór tablic nazywanych **tablicami wymiarów**.
<u>Z każdym wymiarem związany jest zbiór atrybutów.</u> Atrybuty opisujące pojedynczy wymiar tworzą hierarchię wymiaru, która umożliwia definiowanie różnych poziomów agregacji danych (zasadniczy cel budowy systemu OLAP)