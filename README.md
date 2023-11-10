# Exercicio08eleitores
numeros de votos de eleitores


package exercicios;
/*
 * Escreva um algoritmo	para ler o numero total de eleitores de um municipio o numero de votos brancos , nulos e validos.
 * calcular e escrever o percentual que cada um representa em relaçao  ao total do eleitores.
 * 
 */
import java.util.Scanner;

public class Exercicio08 {

	public static void main(String[] args) {
		Scanner scanner = new Scanner(System.in);
		
		float eleitores;
		float votosBracos;
		float votosNulos;
		float votosValidos;
		
		
		System.out.println("Quantidade de eleitores: ");
		float eleitor = scanner.nextFloat();
		
		System.out.println("Quantidade de votos em bracos : ");
		float votobranc = scanner.nextFloat();
		
		System.out.println("Quantidade de votos nulos : ");
		float votonul = scanner.nextFloat();
		
		System.out.println("Quantidade de votos validos : ");
		float votosvalido = scanner.nextFloat();
		//processando
		float porcentagemVotosBracos = votobranc/eleitor*100;
		
		
		//saoda
		System.out.println("A porcentagem de votos brancos correspondem a : " + porcentagemVotosBracos + "%");
		scanner.close();

			}

}
