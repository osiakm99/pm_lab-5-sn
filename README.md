# Parametry projektu

Nazwa: pm-lab-5  
Autor: Paweł Dąbal (pawel.dabal@wat.edu.pl)  
Opis: Projekt bazowy repozytorium na piąte spotkanie laboratoryjne z przedmiotu _Techniki mikroprocesorowej_.  
Wersja: v1.0  
Data: 25.01.2021 r.

# Informacje o studencie

Imię i nazwisko studenta: Maciej Osiak  
Numer albumu: 72543  
Grupa studencka: WEL18DE1S1

# Odpowiedzi do pytań z instrukcji
...
Odp zadanie 3.2.6:
Obwód który został przez nas sporządzony na podstawie schematu z punktu 3.1.2 realizuje kilka funkcji w których jedną z główynch zmiennych jest temperatura. Czujnik temperatury odczytuje temperaturę otoczenia (w przypadku tinkercada możemy regulować suwakiem temperaturę) o której informacja jest przekazywana bezpośrednio do mikrokontrolera. Na podsawie otrzymanej wartości płytka wykonuje kilka procesów. Temperatura zostaje wyświetlona na wyświetalaczu LCD. Informacja z płytki również wędruje na diodę RGB która zmienia swój kolor od niebieskiego do czerwonego zgodnie ze zmianą temperatury. Silnik został zaprogramowany w taki sposób aby załączał się (przez tranzystor) w przypadku gdy temperatura otoczenia wynosi 40 stopni.