# Test-Junit-case-
This project is for  learn  Junit test case , that is a framework can use in NetBeans IDE, is possible verification all conditions present in algorithm and realize all tests  for condition, Use also  Cyclomatic complexity , your  algorithm is calculate  imc , below preent your chart of Cyclomatic complexity and table with values for test


Algoritimo:
1                                              
if(getSexo()=="F"){
            
      2 if (imc< 20.7) {
           3  resultado = "Abaixo do peso";
            }  4 else if (imc <= 26.4) {
               5  resultado = "No peso normal";
            } 
6 else if (imc <= 27.8) {
           7 resultado = "Marginalmente acima do peso";
            } 8 else if (imc <= 31.1) {
             9  resultado = "Acima do peso ideal";
            } 
10 else {
           11 resultado = "Obeso";
            }
          }
          
          	12                                    
          else if(getSexo()=="F" || getSexo() =="f"){
         
        13  if (imc < 19.1) {
              14 resultado = "Abaixo do peso";
            } 
15 else if (imc  <= 25.8) {
               16  resultado = "No peso normal";
            } 
17 else if (imc <= 27.3) {
              18 resultado = "Marginalmente acima do peso";
            }  19 else if (imc <= 32.3) {
               20 resultado = "Acima do peso ideal";
            } 21 else {
              22  resultado = "Obeso";
            }
                   }



	


Tabela de valores de teste :

Sexo	Altura	Peso
F	1,0	17
F	1,0	19.5
F	1,0	26
F	1,0	27.8
F	1,0	40
M	1,0	20
M	1,0	20.9
M	1,0	27
M	1,0	29
M	1,0	33








Grafo de complexidade :



