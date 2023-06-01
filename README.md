# SI_2023_lab2_206019

## Mario Nikolov 206019

2.
![Untitled Diagram](https://github.com/nikolovmario/SI_2023_lab2_206019/assets/86928940/268dec19-2bde-44af-8afe-741540f4d53e)
#### 3.
#### Цикломатската комплексност се пресметува со формулата:
##### број редови - број јазли + 2 = 37 - 28 + 2 = 11
4.
#### 1 test case: user == null
#### 2 test case: username==null password==123 (nevaliden, pomalku od 8 bukvi) email==marionikolov4u@gmail.com
#### 3 test case: username==marionikolov (valid) password==123 45678 (validen so prazno mesto) email==marionikolov (nevaliden)
#### 4 test case: username==marionikolov (valid) password==123$5667* ( valid, so specijalen znak) email==marionikolov (nevaliden)
#### 5 test case: username==marionikolov (valid) password==12345678 (valid) email==marionikolov (nevaliden)

5.
#### T || X || X (Првиот услов е точен, другите не се проверуваат)
#### F || T || X (првиот усов е неточен, вториот е точен, третиот не се проверува) 
#### F || F || T (првите два услови се неточни, третиот е точен)
#### F || F || F (сите три услови се неточни)
