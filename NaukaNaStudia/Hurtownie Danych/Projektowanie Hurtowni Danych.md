W procesie **projektowania hurtowni danych** opracowuje się i wdraża model wymiarów, który pozwala na korzystanie z **analizy wymiarów** (analiza wielowymiarowa).
Pytano osoby decyzyjne o podanie pytań na które żądałyby odpowiedzi związanej z ich organizację i niemal zawsze odpowiadały:
- Analiza podsumowanych informacji według własnych elementów organizacyjnych, takich jak **oddziały** lub **regiony**
- Wyświetlanie informacji w sposób graficzny i **tabelaryczny**
- Możliwość przeglądania informacji **rozłożonych w czasie**
---
Dyrektorzy mogą potrzebować np. raportu pokazującego sprzedaż według produktów lub przedstawiającego sprzedaż według klienta albo nawet produktu i według klienta.
<table border="1">
	<tr>
		<th>Nazwa produktu</th>
		 <th>Sprzedano</th>
		 <th>Cena zakupu</th>
		 <th>Cena sprzedaży</th>
		 <th>Dochód całkowity</th>
		 <th>Koszty całkowite</th>
		 <th>Zysk brutto</th>
	</tr>
	 <tr>
		 <td>Chianti</td>
		 <td>322</td>
		 <td>36</td>
		 <td>40</td>
		 <td>45655</td>
		 <td>8777</td>
		 <td>5677</td>
	</tr>
		 <tr>
		 <td>Barola</td>
		 <td>567</td>
		 <td>54</td>
		 <td>67</td>
		 <td>5666</td>
		 <td>6667</td>
		 <td>56666</td>
	</tr>
		 
</table>

Takie wymiarowe podejście doprowadziło Codd'a do obserwacji:

**"Zwykle istnieje kilka różnych wymiarów, z których użyciem można analizować określony zbiór danych. Ta wielokrotna perspektywa lub wielowymiarowy widok koncepcyjny wydaje się sposobem, w jaki większość przedsiębiorców naturalnie widzi swoje środowisko"** *E.F."Ted" Codd, 1993*

---
Przypominając, HD zorientowane są na **temat** czyli w tym przypadku obszarem tematu będzie **sprzedaż.** Wymiarami analizy będą **klienci** i **produkty**.
Opisać to można za pomocą **kostki trójwymiarowej**
- Wymiar **Klient**
- Wymiar **Produkt**
- Wymiar **Czas** (niezbędny wymiar analizy (zmienność w czasie)
- Oznacza to, że sprzedaż może być analizowana według **klientów, produktów** i **w czasie**
![[Pasted image 20240603185755.png]]
