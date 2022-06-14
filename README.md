# TP 3 - LP1
Realizado por Eduarda Matias e Stefany Tam

![2022-06-14-16-32-32](https://user-images.githubusercontent.com/85466761/173674238-e00421e1-8e03-42aa-a5aa-75ad49158d65.gif)


# Objetivo

#### Crie a classe Hora conforme especificado abaixo: <br>

![image](https://user-images.githubusercontent.com/85466761/173672175-2b07f1f1-f312-4d92-86fd-645c513fba84.png) <br>

+ O construtor Hora() deve permitir ao usuário digitar os valores de hora, minuto e
segundos e com eles inicializar os atributos da classe. Os valores digitados deverão ser
consistidos e só aceitos se válidos, caso contrário, exigir ao usuário redigitar;
+ O construtor Hora(int h, int m, int s) deverá receber os valores de hora, minuto e
segundos e com eles inicializa as propriedades da classe;
+ Os métodos setHor(int h), setMin(int m) e setSeg(int s) devem receber um valor e
atribuí-lo ao respectivo atributo;
+ Os métodos setHor(), setMin() e setSeg() devem permitir que o usuário digite um
valor e atribuí-lo ao respectivo atributo. Os valores digitados deverão ser consistidos e
só aceitos se válidos, caso contrário, exigir ao usuário redigitar;
+ Os métodos getHor(), getMin() e getSeg() devem devolver as respectivas
propriedades;
+ O método getHora1() deve nos devolver a hora no formato: hh:mm:ss;
+ O método getHora2() deve nos devolver a hora no formato: hh:mm:ss (AM/PM);
+ O método getSegundos() deve nos devolver a quantidade de segundos expressa na
hora em questão, (exemplo: 01:00:01 = 3601 segundos) .
+ Conveniente colocar tratamento de exceção para as possíveis inconsistências na
entrada de dados. 
+ Agora, desenvolva um programa capaz de testar a classe e os métodos desenvolvidos no
exercício anterior.
