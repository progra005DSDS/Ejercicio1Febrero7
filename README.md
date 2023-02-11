# Ejercicio1Febrero7
Ejercicio1
## DESCRIPCION DE PROBLEMA
Se requiere un programa en Java para convertir una cantidad de dinero en otros tipos de monedas (al menos a cinco tipos de monedas distintas). 
## Desarollo del problema
- Entrada
float cantidad
String moneda, moneda2, moneda3 , moneda4, moneda5,
double
-Proceso 
Solicitar moneda a convertir
Solicitar cantidad a moneda
Solivitar moneda a procesas convercion

si la monto es mayor o igual a cero se convertira a la moneda deseada
si el menor que 0 entonces se cancela la operacion
##Diseño de la solucion
##Desarollo de la solucion
!
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {

        Scanner entradamoneda = new Scanner (System.in);
        String monedacambiar = new String(), monedaorigen ;

        System.out.println("Ingrese el tipo de moneda que posee: a)Peso, b)dolar,c)euro, d)Yen, e)bitcoin");
 monedaorigen= entradamoneda.nextLine();
switch (monedaorigen){
    case  "a":

        System.out.println("Ingresa el tipo de moneda al que deseas cambiar:, a)dolar,b)euro, c)Yen, d)bitcoin");
        monedacambiar=entradamoneda.nextLine();
        switch  (monedacambiar){case "a":
        System.out.println("}ingresa el total de moneda ");
            double dineropropio= entradamoneda.nextDouble();
            dineropropio= dineropropio *0.053;
        {System.out.println(dineropropio + "dolar");

        }break;
            case "b":
                System.out.println("}ingresa el total de moneda ");
                double dineropropio1= entradamoneda.nextDouble();
                dineropropio1= dineropropio1 * .049;
            {System.out.println(dineropropio1 + "euro");}
        break;
            case "c":
                System.out.println("ingresa el total de moneda ");
                double dineropropio2= entradamoneda.nextDouble();
                dineropropio2= dineropropio2 * 6.94;
            {System.out.println(dineropropio2+ "yen");}
            break;
            case "d":
                System.out.println("}ingresa el total de moneda ");
                double dineropropio3= entradamoneda.nextDouble();
                dineropropio3= dineropropio3 *.0000023;
            {System.out.println(dineropropio3 + "bitcoin");}
            break;

 }
break;
    case "b": System.out.println("Ingresa el tipo de moneda al que deseas cambiar:, a)peso,b)euro, c)Yen, d)bitcoin");
        monedacambiar=entradamoneda.nextLine();
        switch  (monedacambiar){case "a":
            System.out.println("}ingresa el total de moneda ");
            double dineropropio= entradamoneda.nextDouble();
            dineropropio= dineropropio * 18.92;
        {System.out.println(dineropropio + "pesos");

        }break;
            case "b":
                System.out.println("}ingresa el total de moneda ");
                double dineropropio1= entradamoneda.nextDouble();
                dineropropio1= dineropropio1 * .093;
            {System.out.println(dineropropio1 + "euro");}
            break;
            case "c":
                System.out.println("}ingresa el total de moneda ");
                double dineropropio2= entradamoneda.nextDouble();
                dineropropio2= dineropropio2 * 131.48;
            {System.out.println(dineropropio2+ "yen");}
            break;
            case "d":
                System.out.println("}ingresa el total de moneda ");
                double dineropropio3= entradamoneda.nextDouble();
                dineropropio3= dineropropio3 * .000044;
            {System.out.println(dineropropio3 + "bitcoin");}
            break;

        }
break;
    case  "c":

        System.out.println("Ingresa el tipo de moneda al que deseas cambiar:, a)peso,b)dolar, c)Yen, d)bitcoin");
        monedacambiar=entradamoneda.nextLine();
        switch  (monedacambiar){case "a":
            System.out.println("}ingresa el total de moneda ");
            double dineropropio= entradamoneda.nextDouble();
            dineropropio= dineropropio * 20.31;
        {System.out.println(dineropropio + "pesos");

        }break;
            case "b":
                System.out.println("}ingresa el total de moneda ");
                double dineropropio1= entradamoneda.nextDouble();
                dineropropio1= dineropropio1 * .093;
            {System.out.println(dineropropio1 + "dolares");}
            break;
            case "c":
                System.out.println("}ingresa el total de moneda ");
                double dineropropio2= entradamoneda.nextDouble();
                dineropropio2= dineropropio2 * 140.96;
            {System.out.println(dineropropio2+ "yen");}
            break;
            case "d":
                System.out.println("}ingresa el total de moneda ");
                double dineropropio3= entradamoneda.nextDouble();
                dineropropio3= dineropropio3 * .000048;
            {System.out.println(dineropropio3 + "bitcoin");}
            break;


}
break;
    case  "d":

        System.out.println("Ingresa el tipo de moneda al que deseas cambiar:, a)peso,b)dolar, c)euro, d)bitcoin");
        monedacambiar=entradamoneda.nextLine();
        switch  (monedacambiar){case "a":
            System.out.println("}ingresa el total de moneda ");
            double dineropropio= entradamoneda.nextDouble();
            dineropropio= dineropropio * .014;
        {System.out.println(dineropropio + "pesos");

        }break;
            case "b":
                System.out.println("}ingresa el total de moneda ");
                double dineropropio1= entradamoneda.nextDouble();
                dineropropio1= dineropropio1 * .0076;
            {System.out.println(dineropropio1 + "dolares");}
            break;
            case "c":
                System.out.println("}ingresa el total de moneda ");
                double dineropropio2= entradamoneda.nextDouble();
                dineropropio2= dineropropio2 * .0071;
            {System.out.println(dineropropio2+ "euro");}
            break;
            case "d":
                System.out.println("}ingresa el total de moneda ");
                double dineropropio3= entradamoneda.nextDouble();
                dineropropio3= dineropropio3 * 0.00000034 ;
            {System.out.println(dineropropio3 + "bitcoin");}
            break;
}

    case  "e":

        System.out.println("Ingresa el tipo de moneda al que deseas cambiar:, a)peso,b)dolar, c)euro, d)bitcoin");
        monedacambiar=entradamoneda.nextLine();
        switch  (monedacambiar){case "a":
            System.out.println("}ingresa el total de moneda ");
            double dineropropio= entradamoneda.nextDouble();
            dineropropio= dineropropio * 429096.34;
        {System.out.println(dineropropio + "pesos");

        }break;
            case "b":
                System.out.println("}ingresa el total de moneda ");
                double dineropropio1= entradamoneda.nextDouble();
                dineropropio1= dineropropio1 * 22692.20;
            {System.out.println(dineropropio1 + "dolares");}
            break;
            case "c":
                System.out.println("}ingresa el total de moneda ");
                double dineropropio2= entradamoneda.nextDouble();
                dineropropio2= dineropropio2 * 21149.41;
            {System.out.println(dineropropio2+ "euro");}
            break;
            case "d":
                System.out.println("}ingresa el total de moneda ");
                double dineropropio3= entradamoneda.nextDouble();
                dineropropio3= dineropropio3 * 2981710.85 ;
            {System.out.println(dineropropio3 + "yen");}
            break;
}break;}}}
##Depuracion y prueba
switch  (monedacambiar){case "a":
            System.out.println("}ingresa el total de moneda ");
            double dineropropio= entradamoneda.nextDouble();
            dineropropio= dineropropio * 429096.34;
        {System.out.println(dineropropio + "pesos");

        }break;
            case "b":
                System.out.println("}ingresa el total de moneda ");
                double dineropropio1= entradamoneda.nextDouble();
                dineropropio1= dineropropio1 * 22692.20;
            {System.out.println(dineropropio1 + "dolares");}
            break;
            case "c":
                System.out.println("}ingresa el total de moneda ");
                double dineropropio2= entradamoneda.nextDouble();
                dineropropio2= dineropropio2 * 21149.41;
            {System.out.println(dineropropio2+ "euro");}
            break;
            case "d":
                System.out.println("}ingresa el total de moneda ");
                double dineropropio3= entradamoneda.nextDouble();
                dineropropio3= dineropropio3 * 2981710.85 ;
            {System.out.println(dineropropio3 + "yen");}
            break;
