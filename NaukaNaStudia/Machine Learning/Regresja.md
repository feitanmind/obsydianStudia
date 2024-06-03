![[Pasted image 20240603091600.png]]
**Zadanie regresji** to przewidywanie na wyjściu zmiennej o wartości rzeczywistej
Czarna skrzynka to model regresji
Uczenie modelu to znalezienie takich parametrów, żeby model jak najlepiej przewidywał dla nieznanych danych
[[Przykład regresji]]

**Definicja Copilot**
**Regresja** to metoda statystyczna pozwalająca na opisanie współzmienności kliku zmiennych poprzez dopasowanie do nich funkcji. Formalnie, regresja pozwala estymować warunkową wartość oczekiwaną zmiennej losowej (zwanej **zmienną objaśnianą**) dla zadanych wartości innej zmiennej lub wektora zmiennych losowych (tzw. **zmiennych objaśniających**). W praktyce, proces regresji składa się z dwóch faz:
1. **Konstruowanie modelu:** W tej fazie budujemy tzw. **model regresyjny**, czyli funkcję opisującą, jak zależy wartość oczekiwana zmiennej objaśnianej od zmiennych objaśniających. Model może być wyrażony nie tylko matematycznym wzorem, ale także algorytmem, np. w postaci drzewa regresyjnego czyli sieci neuronowej. Konstruujemy go tak, aby jak najlepiej pasował do danych z próby uczącej, zawierającej zarówno zmienne objaśniające, jak i objaśniane.
2. **Stosowanie modelu (scoring)**: Używamy wyliczonego modelu do danych, w których znamy 