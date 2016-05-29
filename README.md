# ralZadanie
____Zadanie____

Vypracovali:Gabriel Kerekeš, Luigino Camastra

Čínska zvyšková veta

Program rieši systémove linearne kongruencie. tzv. (Čínska zvyšková veta)

Používanie programu:

1. Program od Vás požaduje číslo. To číslo bude charakterizovať v akom poli sa budú kongruencie riešiť.  (Definuj pole P: ). 
POZOR!! Zadané číslo musi byť prvočíslo (okrem čísla 1).
Stlačte ENTER.

2. V kroku 2 treba zadať koľko kongruencii chcete načítať. V rozsahu od 2-7.

3. Zobrazí sa Vám menu s možnosťou vygenerovania kongruencie automaticky voľba č.1, alebo si kongruencie budete zadavať sami-manualne, voľba č.2. 
Zadávanie kongruencie je nasledovné: napr.   "[2 10 14 6]" je  2 + 10*X + 14*x^2 +6*X^3
	
4.POZOR!! Pri zadavani kongruencii, kongruencie musia byť navzájom nesúdeliteľné.

5.Vo finalnej fáze by ste mali vidieť tabuľku s vypočítanými hodnotami.



Takto by mala vyzerat finalna podoba pri zadaní pola 3 a pri vygenerovaní 3x kongruencií.

i     0                                                    1                                                    2
---------------------------------------------------------------------------------------------------------------------------------------------------------------
m     [0 1 2 0 1]                                          [1 2 2 0 2 0 2 1]                                    [1 0 1 1 0 0 1 1]
b     [0 2 1 1 1 1 2 1]                                    [0 2 1 1 0 1 2 2]                                    [1 1 0 2 2 0 1]
M     [1 2 0 0 0 2 2 0 0 2 0 2 2 0 1]                      [0 1 2 1 1 2 1 2 0 2 1 1]                            [0 1 1 0 2 1 0 2 1 2 2 1]
y     [1 1 0 1]                                            [1 2 2 1 1 0 2]                                      [2 1 0 1 2 1]
bMy   [0 2 1 2 2 2 2 1 2 0 2 1 0 0 0 1 0 2 0 2 0 1 1 2 1]  [0 0 2 0 1 0 1 1 0 0 2 1 1 0 1 1 1 2 2 1 2 1 1 2 1]  [0 2 2 1 1 1 1 1 1 2 0 0 2 0 2 1 0 2 2 2 0 1 1]


f(x) = [0 0 0 2 1 1 0 0 2 2 2 0 1 1 1 0 1]
