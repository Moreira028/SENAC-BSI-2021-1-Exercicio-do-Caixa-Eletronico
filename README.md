# Algoritmo de Caixa Eletrônico

package Alg.Aula_Algoritmo;

import java.util.Scanner;

public class Ex1 {
        public static void main(String[] args) {
        Scanner leitor = new Scanner(System.in);
        
        double n100, n50, n20, n10, n5 , n2, n1;
        int r100, r50, r20, r10, r5, r2, r1;
        
        System.out.print("Escreva o valor do saque: ");
        int valor = leitor.nextInt();
        
        n100 = valor / 100;
        r100 = valor % 100;
        
        n50 = r100 / 50;
        r50 = r100 % 50;
        
        n20 = r50 / 20;
        r20 = r50 % 20;
        
        n10 = r20 / 10;
        r10 = r20 % 10;
        
        n5 = r10 / 5;
        r5 = r10 % 5;
        
        n2 = r5 / 2;
        r2 = r5 % 2;
        
        n1 = r2 / 1;
        r1 = r2 % 1;        
        
        System.out.println("\nQuantidade de cédulas de R$ 100,00 = "  + n100 + " cédulas");
        System.out.println("Quantidade de cédulas de R$ 50,00 = " + n50 + " cédulas");
        System.out.println("Quantidade de cédulas de R$ 20,00 = " + n20 + " cédulas");
        System.out.println("Quantidade de cédulas de R$ 10,00 = " + n10 + " cédulas");
        System.out.println("Quantidade de cédulas de R$ 5,00 = " + n5 + " cédulas");
        System.out.println("Quantidade de cédulas de R$ 2,00 = " + n2 + " cédulas");
        System.out.println("Quantidade de moedas de R$ 1,00 = " + n1 + " moedas");
        
        }
    
}


Ferreira, Gabriel. moreira028@gmail.com.

Data: 05/05/2021

