# C-CADENAS-DE-NUMEROS🙂
## EDWIN MORIEL

```cpp
/*REALIZAR UN PROGRAMA QUE FACILITE LA VENTA EN UN COMISARIATO QUE ESTA EN CAMPAÑA DE RECICLAJE; SOLO PERMITE EL INGRESO MAXIMO DE 10 PRODUCTOS Y CUALQUIER CANTIDAD EN UNIDADES ; CASO CONTRARIO HACER CASO OMISO*/

#include<stdio.h> 

main() 
{
float v1, v2, v3, v4, v5, v6, v7, v8, v9, v10, IVA, s1, s2, s3, s4, s5, s6, s7, s8, s9, s10, sub, tot;  
int  telefono, n, c1, c2, c3, c4, c5, c6, c7, c8, c9, c10;   
char nombre, apellido, p1, p2, p3, p4, p5, p6, p7, p8, p9, p10;  


printf ("\n ***************************");
printf ("\n BIENVENIDOS A SUPERMAXI S.A");
printf ("\n ***************************");
printf("\n ");
printf("\n Ingresar Nombre:       ");
printf("\n ");
scanf("%s",&nombre); 

printf("\n Ingresar apellido:       ");
printf("\n ");
scanf("%s",&apellido);

printf("\n Ingresar telefono:       ");
printf("\n ");
scanf("%d",&telefono);
printf("\n Ingrese el numero de producto que desea llevar 'DEBE SER MENOR A 10'");
scanf("%d",& n );
switch(n) 
{
case 1: 
printf("\n PRODUCTO # 1 ");
printf("\n Nombre del Producto");
scanf("%s",& p1);
printf("\n Cantidad");
scanf("%d",& c1);
printf("\n Valor");
scanf("%f",& v1);
sub=c1*v1;  //proceso
IVA=0.12*sub;
tot=sub+IVA;
printf("\n Tu subtotal es: %f , Tu total a pagar es: %f",sub, tot);
break; 

case 2:
printf("\n PRODUCTO # 1 ");
printf("\n Nombre del Producto");
scanf("%s",& p1);
printf("\n Cantidad");
scanf("%d",& c1);
printf("\n Valor");
scanf("%f",& v1);
s1=c1*v1; 
printf("\n PRODUCTO # 2 ");
printf("\n Nombre del Producto");
scanf("%s",& p2);
printf("\n Cantidad");
scanf("%d",& c2);
printf("\n Valor");
scanf("%f",& v2);
s2=c2*v2;
sub=s1+s2;
IVA=0.12*sub;
tot=sub+IVA;
printf("\n Gracias");
printf("\n Tu subtotal es: %f , Tu total a pagar es: %f",sub, tot);
break;

case 3:
printf("\n PRODUCTO # 1 ");
printf("\n Nombre del Producto");
scanf("%s",& p1);
printf("\n Cantidad");
scanf("%d",& c1);
printf("\n Valor");
scanf("%f",& v1);
s1=c1*v1;
printf("\n PRODUCTO # 2 ");
printf("\n Nombre del Producto");
scanf("%s",& p2);
printf("\n Cantidad");
scanf("%d",& c2);
printf("\n Valor");
scanf("%f",& v2);
s2=c2*v2;
printf("\n PRODUCTO # 3 ");
printf("\n Nombre del Producto");
scanf("%s",& p3);
printf("\n Cantidad");
scanf("%d",& c3);
printf("\n Valor");
scanf("%f",& v3);
s3=c3*v3;
sub=s1+s2+s3;
IVA=0.12*sub;
tot=sub+IVA;
printf("\n Tu subtotal es: %f , Tu total a pagar es: %f",sub, tot);
break;

case 4:
printf("\n PRODUCTO # 1 ");
printf("\n Nombre del Producto");
scanf("%s",& p1);
printf("\n Cantidad");
scanf("%d",& c1);
printf("\n Valor");
scanf("%f",& v1);
s1=c1*v1;
printf("\n PRODUCTO # 2 ");
printf("\n Nombre del Producto");
scanf("%s",& p2);
printf("\n Cantidad");
scanf("%d",& c2);
printf("\n Valor");
scanf("%f",& v2);
s2=c2*v2;
printf("\n PRODUCTO # 3 ");
printf("\n Nombre del Producto");
scanf("%s",& p3);
printf("\n Cantidad");
scanf("%d",& c3);
printf("\n Valor");
scanf("%f",& v3);
s3=c3*v3;
printf("\n PRODUCTO # 4 ");
printf("\n Nombre del Producto");
scanf("%s",& p4);
printf("\n Cantidad");
scanf("%d",& c4);
printf("\n Valor");
scanf("%f",& v4);
s4=c4*v4;
sub=s1+s2+s3+s4;
IVA=0.12*sub;
tot=sub+IVA;
printf("\n Tu subtotal es: %f , Tu total a pagar es: %f",sub, tot);
break;

case 5:
printf("\n PRODUCTO # 1 ");
printf("\n Nombre del Producto");
scanf("%s",& p1);
printf("\n Cantidad");
scanf("%d",& c1);
printf("\n Valor");
scanf("%f",& v1);
s1=c1*v1;
printf("\n PRODUCTO # 2 ");
printf("\n Nombre del Producto");
scanf("%s",& p2);
printf("\n Cantidad");
scanf("%d",& c2);
printf("\n Valor");
scanf("%f",& v2);
s2=c2*v2;
printf("\n PRODUCTO # 3 ");
printf("\n Nombre del Producto");
scanf("%s",& p3);
printf("\n Cantidad");
scanf("%d",& c3);
printf("\n Valor");
scanf("%f",& v3);
s3=c3*v3;
printf("\n PRODUCTO # 4 ");
printf("\n Nombre del Producto");
scanf("%s",& p4);
printf("\n Cantidad");
scanf("%d",& c4);
printf("\n Valor");
scanf("%f",& v4);
s4=c4*v4;
printf("\n PRODUCTO # 5 ");
printf("\n Nombre del Producto");
scanf("%s",& p5);
printf("\n Cantidad");
scanf("%d",& c5);
printf("\n Valor");
scanf("%f",& v5);
s5=c5*v5;
sub=s1+s2+s3+s4+s5;
IVA=0.12*sub;
tot=sub+IVA;
printf("\n Tu subtotal es: %f , Tu total a pagar es: %f",sub, tot);
break;

case 6:
printf("\n PRODUCTO # 1 ");
printf("\n Nombre del Producto");
scanf("%s",& p1);
printf("\n Cantidad");
scanf("%d",& c1);
printf("\n Valor");
scanf("%f",& v1);
s1=c1*v1;
printf("\n PRODUCTO # 2 ");
printf("\n Nombre del Producto");
scanf("%s",& p2);
printf("\n Cantidad");
scanf("%d",& c2);
printf("\n Valor");
scanf("%f",& v2);
s2=c2*v2;
printf("\n PRODUCTO # 3 ");
printf("\n Nombre del Producto");
scanf("%s",& p3);
printf("\n Cantidad");
scanf("%d",& c3);
printf("\n Valor");
scanf("%f",& v3);
s3=c3*v3;
printf("\n PRODUCTO # 4 ");
printf("\n Nombre del Producto");
scanf("%s",& p4);
printf("\n Cantidad");
scanf("%d",& c4);
printf("\n Valor");
scanf("%f",& v4);
s4=c4*v4;
printf("\n PRODUCTO # 5 ");
printf("\n Nombre del Producto");
scanf("%s",& p5);
printf("\n Cantidad");
scanf("%d",& c5);
printf("\n Valor");
scanf("%f",& v5);
s5=c5*v5;
printf("\n PRODUCTO # 6 ");
printf("\n Nombre del Producto");
scanf("%s",& p6);
printf("\n Cantidad");
scanf("%d",& c6);
printf("\n Valor");
scanf("%f",& v6);
s6=c6*v6;
sub=s1+s2+s3+s4+s5+s6;
IVA=0.12*sub;
tot=sub+IVA;
printf("\n Tu subtotal es: %f , Tu total a pagar es: %f",sub, tot);
break;

case 7:
printf("\n PRODUCTO # 1 ");
printf("\n Nombre del Producto");
scanf("%s",& p1);
printf("\n Cantidad");
scanf("%d",& c1);
printf("\n Valor");
scanf("%f",& v1);
s1=c1*v1;
printf("\n PRODUCTO # 2 ");
printf("\n Nombre del Producto");
scanf("%s",& p2);
printf("\n Cantidad");
scanf("%d",& c2);
printf("\n Valor");
scanf("%f",& v2);
s2=c2*v2;
printf("\n PRODUCTO # 3 ");
printf("\n Nombre del Producto");
scanf("%s",& p3);
printf("\n Cantidad");
scanf("%d",& c3);
printf("\n Valor");
scanf("%f",& v3);
s3=c3*v3;
printf("\n PRODUCTO # 4 ");
printf("\n Nombre del Producto");
scanf("%s",& p4);
printf("\n Cantidad");
scanf("%d",& c4);
printf("\n Valor");
scanf("%f",& v4);
s4=c4*v4;
printf("\n PRODUCTO # 5 ");
printf("\n Nombre del Producto");
scanf("%s",& p5);
printf("\n Cantidad");
scanf("%d",& c5);
printf("\n Valor");
scanf("%f",& v5);
s5=c5*v5;
printf("\n PRODUCTO # 6 ");
printf("\n Nombre del Producto");
scanf("%s",& p6);
printf("\n Cantidad");
scanf("%d",& c6);
printf("\n Valor");
scanf("%f",& v6);
s6=c6*v6;
printf("\n PRODUCTO # 7 ");
printf("\n Nombre del Producto");
scanf("%s",& p7);
printf("\n Cantidad");
scanf("%d",& c7);
printf("\n Valor");
scanf("%f",& v7);
s7=c7*v7;
sub=s1+s2+s3+s4+s5+s6+s7;
IVA=0.12*sub;
tot=sub+IVA;
printf("\n Tu subtotal es: %f , Tu total a pagar es: %f",sub, tot);
break;

case 8:
printf("\n PRODUCTO # 1 ");
printf("\n Nombre del Producto");
scanf("%s",& p1);
printf("\n Cantidad");
scanf("%d",& c1);
printf("\n Valor");
scanf("%f",& v1);
s1=c1*v1;
printf("\n PRODUCTO # 2 ");
printf("\n Nombre del Producto");
scanf("%s",& p2);
printf("\n Cantidad");
scanf("%d",& c2);
printf("\n Valor");
scanf("%f",& v2);
s2=c2*v2;
printf("\n PRODUCTO # 3 ");
printf("\n Nombre del Producto");
scanf("%s",& p3);
printf("\n Cantidad");
scanf("%d",& c3);
printf("\n Valor");
scanf("%f",& v3);
s3=c3*v3;
printf("\n PRODUCTO # 4 ");
printf("\n Nombre del Producto");
scanf("%s",& p4);
printf("\n Cantidad");
scanf("%d",& c4);
printf("\n Valor");
scanf("%f",& v4);
s4=c4*v4;
printf("\n PRODUCTO # 5 ");
printf("\n Nombre del Producto");
scanf("%s",& p5);
printf("\n Cantidad");
scanf("%d",& c5);
printf("\n Valor");
scanf("%f",& v5);
s5=c5*v5;
printf("\n PRODUCTO # 6 ");
printf("\n Nombre del Producto");
scanf("%s",& p6);
printf("\n Cantidad");
scanf("%d",& c6);
printf("\n Valor");
scanf("%f",& v6);
s6=c6*v6;
printf("\n PRODUCTO # 7 ");
printf("\n Nombre del Producto");
scanf("%s",& p7);
printf("\n Cantidad");
scanf("%d",& c7);
printf("\n Valor");
scanf("%f",& v7);
s7=c7*v7;
printf("\n PRODUCTO # 8 ");
printf("\n Nombre del Producto");
scanf("%s",& p8);
printf("\n Cantidad");
scanf("%d",& c8);
printf("\n Valor");
scanf("%f",& v8);
s8=c8*v8;
sub=s1+s2+s3+s4+s5+s6+s7+s8;
IVA=0.12*sub;
tot=sub+IVA;
printf("\n Tu subtotal es: %f , Tu total a pagar es: %f",sub, tot);
break;

case 9:
printf("\n PRODUCTO # 1 ");
printf("\n Nombre del Producto");
scanf("%s",& p1);
printf("\n Cantidad");
scanf("%d",& c1);
printf("\n Valor");
scanf("%f",& v1);
s1=c1*v1;
printf("\n PRODUCTO # 2 ");
printf("\n Nombre del Producto");
scanf("%s",& p2);
printf("\n Cantidad");
scanf("%d",& c2);
printf("\n Valor");
scanf("%f",& v2);
s2=c2*v2;
printf("\n PRODUCTO # 3 ");
printf("\n Nombre del Producto");
scanf("%s",& p3);
printf("\n Cantidad");
scanf("%d",& c3);
printf("\n Valor");
scanf("%f",& v3);
s3=c3*v3;
printf("\n PRODUCTO # 4 ");
printf("\n Nombre del Producto");
scanf("%s",& p4);
printf("\n Cantidad");
scanf("%d",& c4);
printf("\n Valor");
scanf("%f",& v4);
s4=c4*v4;
printf("\n PRODUCTO # 5 ");
printf("\n Nombre del Producto");
scanf("%s",& p5);
printf("\n Cantidad");
scanf("%d",& c5);
printf("\n Valor");
scanf("%f",& v5);
s5=c5*v5;
printf("\n PRODUCTO # 6 ");
printf("\n Nombre del Producto");
scanf("%s",& p6);
printf("\n Cantidad");
scanf("%d",& c6);
printf("\n Valor");
scanf("%f",& v6);
s6=c6*v6;
printf("\n PRODUCTO # 7 ");
printf("\n Nombre del Producto");
scanf("%s",& p7);
printf("\n Cantidad");
scanf("%d",& c7);
printf("\n Valor");
scanf("%f",& v7);
s7=c7*v7;
printf("\n PRODUCTO # 8 ");
printf("\n Nombre del Producto");
scanf("%s",& p8);
printf("\n Cantidad");
scanf("%d",& c8);
printf("\n Valor");
scanf("%f",& v8);
s8=c8*v8;
printf("\n PRODUCTO # 9 ");
printf("\n Nombre del Producto");
scanf("%s",& p9);
printf("\n Cantidad");
scanf("%d",& c9);
printf("\n Valor");
scanf("%f",& v9);
s9=c9*v9;
sub=s1+s2+s3+s4+s5+s6+s7+s8+s9;
IVA=0.12*sub;
tot=sub+IVA;
printf("\n Tu subtotal es: %f , Tu total a pagar es: %f",sub, tot);
break;

case 10:
printf("\n PRODUCTO # 1 ");
printf("\n Nombre del Producto");
scanf("%s",& p1);
printf("\n Cantidad");
scanf("%d",& c1);
printf("\n Valor");
scanf("%f",& v1);
s1=c1*v1;
printf("\n PRODUCTO # 2 ");
printf("\n Nombre del Producto");
scanf("%s",& p2);
printf("\n Cantidad");
scanf("%d",& c2);
printf("\n Valor");
scanf("%f",& v2);
s2=c2*v2;
printf("\n PRODUCTO # 3 ");
printf("\n Nombre del Producto");
scanf("%s",& p3);
printf("\n Cantidad");
scanf("%d",& c3);
printf("\n Valor");
scanf("%f",& v3);
s3=c3*v3;
printf("\n PRODUCTO # 4 ");
printf("\n Nombre del Producto");
scanf("%s",& p4);
printf("\n Cantidad");
scanf("%d",& c4);
printf("\n Valor");
scanf("%f",& v4);
s4=c4*v4;
printf("\n PRODUCTO # 5 ");
printf("\n Nombre del Producto");
scanf("%s",& p5);
printf("\n Cantidad");
scanf("%d",& c5);
printf("\n Valor");
scanf("%f",& v5);
s5=c5*v5;
printf("\n PRODUCTO # 6 ");
printf("\n Nombre del Producto");
scanf("%s",& p6);
printf("\n Cantidad");
scanf("%d",& c6);
printf("\n Valor");
scanf("%f",& v6);
s6=c6*v6;
printf("\n PRODUCTO # 7 ");
printf("\n Nombre del Producto");
scanf("%s",& p7);
printf("\n Cantidad");
scanf("%d",& c7);
printf("\n Valor");
scanf("%f",& v7);
s7=c7*v7;
printf("\n PRODUCTO # 8 ");
printf("\n Nombre del Producto");
scanf("%s",& p8);
printf("\n Cantidad");
scanf("%d",& c8);
printf("\n Valor");
scanf("%f",& v8);
s8=c8*v8;
printf("\n PRODUCTO # 9 ");
printf("\n Nombre del Producto");
scanf("%s",& p9);
printf("\n Cantidad");
scanf("%d",& c9);
printf("\n Valor");
scanf("%f",& v9);
s9=c9*v9;
printf("\n PRODUCTO # 10 ");
printf("\n Nombre del Producto");
scanf("%s",& p10);
printf("\n Cantidad");
scanf("%d",& c10);
printf("\n Valor");
scanf("%f",& v10);
s10=c10*v10;
sub=s1+s2+s3+s4+s5+s6+s7+s8+s9+s10;
IVA=0.12*sub;
tot=sub+IVA;
printf("\n Tu subtotal es: %f , Tu total a pagar + IVA es: %f",sub, tot);
break;


default: printf("\n Error!!! Ingrese numero del 1 al 10");

}
printf("\n Programa culminado con exito; no hubo errores!!!");
return 0;
}

```

*Demo*


![Demo😶](https://user-images.githubusercontent.com/72156127/120652796-bb5aa700-c445-11eb-91d8-2ffb8cb32467.png)


*Descargar*
(https://github.com/Im-Edwin/C-CADENAS-DE-NUMEROS/raw/main/DIDGITOS.exe)


