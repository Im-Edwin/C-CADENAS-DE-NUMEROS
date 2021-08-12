# C-CADENAS-DE-NUMEROS🙂
## EDWIN MORIEL

```cpp
# C-CADENAS-DE-NUMEROS🙂
## EDWIN MORIEL

```cpp
#include <iostream>
#include <string>
//Programa realizado por: EDWIN MORIEL IÑIGA
using namespace std;

string *n;

void imprimir(int inicio,int final,int posicion){

     for(int i = inicio; i<= final; i++)
     {
         cout<<n[posicion][i];
     }

    cout<<" ";

}

int main(){


   n = new string[7];

   n[0] = "  ##    #######   #######   ##         ########   #######   ########   #######   #########   #######        ";
   n[1] = "####   ##     ## ##     ##  ##    ##   ##        ##     ##  ##    ##  ##     ## ##      ##  ##     ##       ";
   n[2] = "  ##          ##        ##  ##    ##   ##        ##              ##   ##     ## ##      ##  ##     ##       ";
   n[3] = "  ##     #######   #######  ##    ##   #######   ########       ##     #######    ########  ##     ##       ";
   n[4] = "  ##    ##              ##  #########        ##  ##     ##     ##     ##     ##         ##  ##     ##       ";
   n[5] = "  ##    ##       ##     ##        ##   ##    ##  ##     ##     ##     ##     ##  #      ##  ##     ##    ###";
   n[6] = "######   #######   #######        ##    ######    #######      ##      #######    ########   #######     ###";

   string numero;
   cout<<"Ingrese una cadena de digitos: ";
   cin>>numero;

   for(int i = 0; i < 7; i++)
   {
       for(int j = 0; j < numero.length(); j++)
       {
          switch(numero[j])
          {
              case '1':
              	imprimir(0,6,i);
              break;
              
              case '2':
              	imprimir(6,15,i);
              break;
              
              case '3':
              	imprimir(16,25,i);
              break;
              
              case '4':
              	imprimir(26,35,i);
              break;
              
              case '5':
              	imprimir(37,45,i);
              break;
              
              case '6':
              	imprimir(47,57,i);
              break;
              
              case '7':
              	imprimir(58,67,i);
              break;
              
              case '8':
              	imprimir(68,79,i);
              break;
              
              case '9':
              	imprimir(80,89,i);
              break;
              
              case '0':
              	imprimir(90,104,i);
              break;
              
              case '.':
              	imprimir(105,107,i);
              break;
              
            
          }
       }

       cout<<endl;
   }
 	
	return 0;
	 getchar( );
	 getchar( );
	 getchar();
}
```

*Demo*


![Demo😶](https://user-images.githubusercontent.com/72156127/120652796-bb5aa700-c445-11eb-91d8-2ffb8cb32467.png)


*Descargar*
(https://github.com/Im-Edwin/C-CADENAS-DE-NUMEROS/raw/main/DIDGITOS.exe)




```

*Demo*


![Demo😶](https://user-images.githubusercontent.com/72156127/120652796-bb5aa700-c445-11eb-91d8-2ffb8cb32467.png)


*Descargar*
(https://github.com/Im-Edwin/C-CADENAS-DE-NUMEROS/raw/main/DIDGITOS.exe)


