Втора лабораториска вежба по Софтверско инженерство
Control flow graph фотографија: 

![slikaodCFG](https://user-images.githubusercontent.com/100590098/171403725-4414bd2d-db09-4095-bce3-ebf02dbc861f.jpg)

Цикломатска комплексност: 
Цикломатската комплексност е добиена  со формулата M = E – N + 2, каде бројот на edges e 25 a бројот на јазли е 19. Па така цикломатската комплексност изнесува 25-19+2=8.

Тест случаи според критериум Every Statement
Тест примерите се : "#000", "#00", "0#00" , "0#0#0#000"
![everystatement](https://user-images.githubusercontent.com/100590098/171405706-ed2019c3-defb-4c33-b807-673d1fcb69f4.jpg)

Тест случаи спорет критериум Every Branch!
Тест примерите се : "#00", "#000", "0#00", "0#0#0#000"
[everybranch](https://user-images.githubusercontent.com/100590098/171405732-98a37384-e87b-447c-b4c9-d8852a083ae6.jpg)

Објаснување за напишаните unit tests:

Во секој од наведените тестови има оставено коментар зошто и за кој пример е направен. Истите тестови ги направив за секој statement и за секој branch. Со помош на тест примерите во every stamenet and every branch успеав да формирам тестови со кои ќе го проверам излезот на програмта.
