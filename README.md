/*El área de un triángulo en función del semiperímetro, dada por Herón es:
area = s(s - a)(s -b)(s - c)
y    s = (a +b + c)/ 2
Donde a, b y c son los lados del triángulo. Calcule el área del triángulo aplicando la fórmula.*/

#include<iostream>
#include<math.h>
using namespace std;

      int main(){
      	
      	float a,b,c,suma=0;
      	double area;
      	
      	cout<<"/Ingrese los lados del triangulo: "<<endl;
      	cin>>a>>b>>c;
      	
      	suma= (a+b+c)/2;
      	
      	area= sqrt(suma*(suma-a)*(suma-b)*(suma-c));      	
      	
      	cout<<"El valor del área sera: "<<area;
      	
      	return 0;
	  }
