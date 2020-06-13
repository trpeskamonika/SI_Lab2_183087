# Втора лабораториска вежба по Софтверско инженерство

## Моника Трпеска, бр. на индекс 183087

### Група на код: 

Ја добив групата на код 5

###  Control Flow Graph

Сликата од графот стои во фолдерот Images. ![](images/183087.png)

### Цикломатска комплексност

Цикломатската комплексност на овој код е 2, истата ја добив преку формулата P+1, каде што P е бројот на предикатни јазли. Во случајoв P=1, па цикломатската комплексност изнесува 2.

### Тест случаи според критериумот  Every statement 

if(i–1>=0 && list.get(i-1).equals(“#”))
izraz1=(i-1>= 0) izraz2=(list.get(i-1).equals(“#”))
Test Case1:izraz1=TRUE izraz2=FALSE Decision Outcome: FALSE
Test Case2:izraz1=FALSE izraz2=TRUE  Decision Outcome:FALSE
Test case3:izraz1=TRUE izraz2=TRUE Decision Outcome:TRUE
Test case4:izraz1=FALSE izraz2=FALSE Decision Outcome: FALSE

if(i+1 <list.size() && list.get(i+1).equals(“#”))
izraz1=(i+1 >= 0) izraz2=(list.get(i+1).equals(“#”))
Test Case1:izraz1=TRUE izraz2=FALSE Decision Outcome: FALSE
Test Case2:izraz1=FALSE izraz2=TRUE  Decision Outcome:FALSE
Test case3:izraz1=TRUE izraz2=TRUE Decision Outcome:TRUE
Test case4:izraz1=FALSE izraz2=FALSE Decision Outcome: FALSE

### Тест случаи според критериумот Every path

.... 

### Објаснување на напишаните unit tests

...
...
