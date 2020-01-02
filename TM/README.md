# Touring Machine Simulator
http://math.hws.edu/eck/js/turing-machine/TM.html

### Somma numeri unari
~~~
01101110 -> 2 + 3 = 01111100
~~~

|Old state|Old symbol|New symbol|New state|Move|
|---|---|---|---|---|
|Q0|0|0|Q1|R|
|Q1|0|0|Q2|R|
|Q1|1|1|Q1|R|
|Q2|1|0|Q3|L|
|Q2|0|B|stop|S|
|Q2|B|B|stop|S|
|Q3|0|1|Q1|R|

