# hello-world
Algoritmo calculadora_cientifica 
	
	Definir op,opNum1,opNum2,total,acum Como Entero;
	op = 0;
	total=0;
	acum=2;
	
	Escribir "bienvenido";
	Escribir "";
	
	Repetir
		Escribir "ingrese el primer numero";
		Leer opNum1;
	Hasta Que opNum1>0
	
	Mientras op>=0 & op<=6 Hacer
	Repetir
	Escribir "¿que opracion desea realizar?";
	Escribir "";
	Escribir "1.-sumar";
	Escribir "2.-restar";
	Escribir "3.-multiplicar";
	Escribir "4.-dividir";
	Escribir "5.-potencia";
	Leer op;
Hasta Que op>=0 & op<6
	
Repetir
	Escribir "ingrese el numero",acum,"de la operatoria";
	Leer opNum2;
	acum = acum+1;
Hasta Que opNum2>0
	
si op = 1 Entonces
	total = (opNum1 + opNum2);
	Escribir "la suma es :",opNum1,"+",opNum2,"=",total;
	Escribir "";
	opNum1=total;
FinSi
	
si op = 2 Entonces
	total = (opNum1 - opNum2);
	Escribir "la resta es :",opNum1,"-",opNum2,"=",total;
	Escribir "";
	opNum1=total;
FinSi

si op = 3 Entonces
	total = (opNum1 * opNum2);
	Escribir "la multiplicacion es :",opNum1,"*",opNum2,"=",total;
	Escribir "";
	opNum1=total;
FinSi

si op = 4 Entonces
	total = (opNum1 / opNum2);
	Escribir "la dividicion es :",opNum1,"/",opNum2,"=",total;
	Escribir "";
	opNum1=total;
FinSi

si op = 5 Entonces
	total = (opNum1 ^ opNum2);
	Escribir "la potencia es :",opNum1,"^",opNum2,"=",total;
	Escribir "";
	opNum1=total;
FinSi

repetir
Escribir "¿decea salir del programa?";
Escribir "";
Escribir "6.-no";
Escribir "7.-si";
Leer op;
Hasta Que op >=6 & op<=7

FinMientras

si op = 7 Entonces
	Borrar Pantalla;
	Escribir "precione cualquier tecla";
	Esperar Tecla;
	Escribir "cargando";
	Esperar 3 Segundo;
Escribir "gracias por usar esta calculadora";
FinSi

FinAlgoritmo
trabajo final
