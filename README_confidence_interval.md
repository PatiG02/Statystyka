[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/eNTHxQ13)
# Przedziały ufności

1. Wczytać dane bezpośrednio z adresu: 'https://static.nbp.pl/dane/kursy/Archiwum/archiwum_tab_a_2023.csv' oraz 'https://static.nbp.pl/dane/kursy/Archiwum/archiwum_tab_a_2024.csv'. Tabele zawierają informacje o średnich dziennych kursach wybranych walut udostępnianych przez Narodowy Bank Polski.
2. Tabele mają tzw. szeroki format (wider). Przekształcić je do formatu długiego (longer) i połączyć w jedną. Wyjściowa tabela ma zawierać tylko kolumny: `date`, `currency`, `value`. Od tej pory to jest bazowa tabela w oparciu której wykonywane są wszelkie przekształcenia i obliczenia.
3. Dla każdej z walut obliczyć: minimalną i maksymalną wartość, kwartyle, średnią, odchylenie standardowe.
4. Wyznaczyć 97% procentowe przedziały ufności dla walut. Wynik zapisać do tabeli.
5. Przedziały ufności z pkt. 4 przedstawić na wykresie.
6. Dla `EUR` wyznaczyć kolejne miesięczne przedziały ufności. Wyniki przedstawić na wykresie. Na wykresie mają być widoczne również średnie wartości.
7. Oszacować współczynnik korelacji dla wszystkich możliwych par walutowych. Wynik zapisać do tabeli, uporządkować względem siły korelacji. Wypisać 10 pierwszych par.