<h1><center>Inteligenta computationala - proiect semestrul 2</center></h1>


#### Studenti:
### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Mihai Lacusteanu
### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Alexandru-Florian Ion 
#### Profesor: 
### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Victor-Emil Neagoe


Acest proiect este o comparatie intre clasificarea cu MLP si comprimarea datelor cu algoritmul PCA apoi clasificarea cu MLP



[Retea MLP cu 3 straturi](https://nbviewer.jupyter.org/github/mihailacusteanu/proiect-ic2/blob/master/MLP.ipynb)

[Comprimare cu PCA si retea MLP cu 3 straturi](https://nbviewer.jupyter.org/github/mihailacusteanu/proiect-ic2/blob/master/MLP%20PCA.ipynb)

#### Concluzii
In urma celor 2 experimente se observa ca algoritmul cu PCA reduce semnificativ timpul de antrenare, comprimarea fiind de la 784 de componente la 100 de componente, iar acuratetea pastrandu-se la o valoare destul de ridicata, **97%**, fata de **98-99%** in cazul fara ultilizarea de PCA.

Se poate de asemenea observa ca numarul total de parametri antrenabili in cazul MLP este 669,706 in timp ce pentru cazul in care s-a facut comprimare cu PCA este 30,730
