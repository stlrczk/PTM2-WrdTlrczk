# Robot autonomiczny
W ramach zajęć z PTM zrealizowaliśmy projekt robota autonomicznego omijającego przeszkody. Jako napęd posłużyły przerobione serwa modelarskie TowerPro SG90 (1.8kg/cm, 100rpm). Po usunięciu elektroniki serwomechanizmu oraz ogranicznika przekładni, oba silniki zostały podpięte do dwukanałowego mostka typu H (L293D). Silniki oraz logika robota są zasilanie z podwójnych ogniw 18650 (2 x 3.7V, realnie około 8.2V) przez stabilizator 5V 7805. Do rozpoznawania przeszkód posłużył nam popularny czujnik ultradźwiękowy HC-SR04, który umożliwiał mierzenie odległości od przeszkody w zakresie 2-200cm.

## Sprzęt
* STM32F4 Discovery
* Serwa SG90 + mostek L293DNE
* Ultradzwiękowy czujnik HC-SR04
* Zasilanie podwójnymi ogniwami 18650 (2*3.7V) + stabilizator 7805

