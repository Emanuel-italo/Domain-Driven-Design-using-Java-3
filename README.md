# Domain-Driven-Design-using-Java-3
Treinamento intensivo - Java

import java.util.Scanner;

public class IntesivoJava3 {
public static void main(String[] args) {
Scanner scanner = new Scanner(System.in);

        System.out.println("Qual a quantidade de maçãs compradas?");
        int qtdeMacas = scanner.nextInt();

        double precoPorUnidade;
        if (qtdeMacas < 12) {
            precoPorUnidade = 0.30;
        } else {
            precoPorUnidade = 0.25;
        }

        double total = qtdeMacas * precoPorUnidade;
        System.out.printf("Valor total a pagar é: R$ %.2f%n", total);

        scanner.close();
    }
}