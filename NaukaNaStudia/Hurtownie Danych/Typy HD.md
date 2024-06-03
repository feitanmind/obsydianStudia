1. **ROLAP** (Relational OLAP) - HD wykorzystująca model relacyjny
2. **MOLAP** (Multidimensional OLAP) - HD wykorzystująca model wielowymiarowy
3. **HOLAP** (Hybrid OLAP)

<table style="border: 1px white solid; border-collapse: collapse;">
	<tr  style="border: 1px white solid; border-collapse: collapse;">
		<th  style="border: 1px white solid; border-collapse: collapse;">MOLAP</th>
		<th  style="border: 1px white solid; border-collapse: collapse;">ROLAP</th>
	</tr>
	
	<tr  style="border: 1px white solid; border-collapse: collapse;">
		<td  style="border: 1px white solid; border-collapse: collapse;">
			- Dane są rejestrowane jako agregacje<br/>
			- Dane są hierarchiczne<br/>
			- Dane są aktualizowane tylko do ostatniej aktualizacji<br/>
			- Predefiniowane zapytania i funkcje <br/>
			- Wielkie zasoby dancyh w transakcjach
		</td>
		<td  style="border: 1px white solid; border-collapse: collapse;">
			- Dane są rejestrowane jako rekordy <br/>
			- Dane są zgodne z modelem relacyjnycm <br/>
			- Dane są aktualne <br/>
			- Wspomaganie doraźnych zapytań <br/>
			- Małe zasoby danych w transakcjach
		</td>
	</tr>
</table>
