 /// 2) Dado a sequência de Fibonacci, onde se inicia por 0 e 1 e o próximo valor sempre será a soma dos 2 valores anteriores (exemplo: 0, 1, 1, 2, 3, 5, 8, 13, 21, 34...), escreva um programa na linguagem que desejar onde, informado um número, ele calcule a sequência de Fibonacci e retorne uma mensagem avisando se o número informado pertence ou não a sequência.

IMPORTANTE:
Esse número pode ser informado através de qualquer entrada de sua preferência ou pode ser previamente definido no código;/////

/**
 * 
 */


import java.util.Scanner;

public class Fibonacci {
    public static void main(String[] args) {
        int n1 = 0, n2 = 1, proximoTermo = 0;
        
        Scanner scanner = new Scanner(System.in);
        System.out.println("----------------------------(Atividade 2)-----------------------------------");
        System.out.print("Informe um número para verificar se pertence à sequência de Fibonacci: ");
        int numero = scanner.nextInt();
        
        while (proximoTermo < numero) {
            proximoTermo = n1 + n2;
            n1 = n2;
            n2 = proximoTermo;
        }
        
        if (proximoTermo == numero) {
            System.out.println("--------------------Resultado-----------------------------");
        	System.out.println(numero + " pertence à sequência de Fibonacci.");
        } else {
            System.out.println(numero + " não pertence à sequência de Fibonacci.");
        }
    }
}


