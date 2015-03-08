# WSQ09.cpp
/*
#WSQ09
Main: Loops
By: Jorge Cervantes
#TC1017
Referencia: Downey, A. (1999). How to think like a computer scientist : C++ version. [S. l.]: SoHo Books.
---------------------------------------------------------------------
*/

#include <iostream>
#include <vector>
#include <string>
using namespace std;

string done;
int x, i, a, u = 0, sd, formu;
long Total, Thediv;
vector <float> Banana(i); // Declaracion de un vector.

void espa(){

cout << "\n";
cout << "\n";
cout << "\n";

}

int main(){

cout << "Cuantos numeros daras tu numero "; // Declara cuantos numeros el vector sera dividido en. 
	cin >> i;
	u = i - 1;
	i = 0;
	x = u + 1;

do{

	cout << "El valor \n";
	cin >> a;				// En esta parte se le declara la cantidad al vector [i]
	Banana.push_back(a);

	espa();
	Total = Total + Banana [i]; //Como se selecciona un vector
	cout << Banana [i];	// Como se imprime un vector
	espa();
	i = i +1;

	}while( i <= u );

for (int i = 0; i < u; ++i)
{
	sd = sd + ((i - Thediv)^2);

}

formu = (( sd/2 ))^1/2;

Thediv = Total / x;
cout << "La suma de los " << u << " numeros es de "<< Total << "\n";
cout << "Su promedio es de " << Thediv << "\n";
cout << "Y la standard deviation es igaual a " << formu << "\n";

cout << "Bye\n";
	return 0;
}
