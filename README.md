# Robot autonomiczny
Projekt autonomicznego robota wyposazonego w czujniki odległości. Platforma pod rozbudowę i eksperymenty związane z minisumo (lokalizacja i wypychanie przeszkód)

## Sprzęt
* STM32F4 Discovery
* Serwa SG90 + mostek L293DNE
* Ultradzwiękowy czujnik HC-SR04 (w planach cyfrowy czujnik podczerwieni Sharp)
* Zasilanie podwójnymi ogniwami 18650 (2*3.7V) + stabilizator 7805

## Konstrukcja
Projekt zakłada budowę w formie "kanapki", pierwsza warstwa zawiera przerobione serwa, wyżej znajduje się przestrzeń dla ogniw, a na szczycie - uniwersalna płytka PCB z wyprowadzoną listą goldpin (połączenie z STM). Podwozie to dwa serwa oraz "trzecie koło" podpierajce konstrukcję.
