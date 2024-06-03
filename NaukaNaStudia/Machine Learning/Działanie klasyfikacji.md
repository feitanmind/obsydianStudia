**Przykład 1: Klasyfikacja zdjęć kotów i psów**
![[Pasted image 20240603091354.png]]
Czarna skrzynka symbolizuje model klasyfikatora
Uczenie klasyfikatora polega na tym, aby model dla niewidzialnych wzorców (w tym przypadku zdjęć dał poprawną etykietę klasy (wyjście jest wartością wyliczeniową)
**Liczba klas jest z góry znana!**

**Przykład 2:**
Każdy wzorzec (punkt na obrazku, dana) należy tylko do jednej klasy (klasy oznaczone kolorami)
**Cel:** Zbudować model,  który separuje klasy. 
Budowanie modelu - architektura i uczenie parametrów
- Model stara się znaleźć granicę podziału, która w ogólności nie jest płaszczyzną tak jak na przedstawionym obok rysunku.
- Zadaniem modeluu dla nowych danych jest predykacja klasy (etap wnioskowania modelu)
- Przykład klasyfikacji: Czy zdjęcie opisywane cechami zrobione jest wewnątrz czy zewnątrz?
![[Pasted image 20240603090544.png]]