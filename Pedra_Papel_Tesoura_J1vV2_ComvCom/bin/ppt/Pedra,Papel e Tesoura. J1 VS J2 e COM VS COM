package ppt;

import java.util.Random;
import java.util.Scanner;

public class Game {
	
	public static void main(String[] Args) {
		String playermove;
		String playermove2;
		Scanner scanner = new Scanner(System.in);
		Scanner options = new Scanner(System.in);
		boolean playAgain = false;
		int option = 0;
		String ppt [] = {"pedra", "papel", "tesoura"};

		
		//Fiz um jogo onde o usuário, através de um menu, pode escolher se ele quer Jogador 1 vs Jogador2
		//ou Computador vs Computador!
		
		System.out.println("Bem vindo ao Pedra Papel ou Tesoura! \n Tecle [1] para J1 VS J2 \n Tecle [2] para COM VS COM");
		option = options.nextInt();
		
		if (option == 1) {
			
		while (playAgain == false) {
		// esse programa é o que dois jogadores se enfrentam.
		System.out.println("Jogador 1, faça sua jogada!");
		while (true) {
			playermove = scanner.nextLine();
			if (playermove.equals("pedra") || playermove.equals("papel") || playermove.equals("tesoura")){
				break;
			}
			 System.out.println(playermove + " não é uma entrada válida");
		    }
		
		while (true) {
			System.out.println("Jogador 2, faça sua jogada!");
			playermove2 = scanner.nextLine();
			if (playermove2.equals("pedra") || playermove2.equals("papel") || playermove2.equals("tesoura")) {
				break;
			}
			System.out.println(playermove2 + " não é uma entrada válida");
		    }
		
		if(playermove.equals(playermove2)) {
			System.out.println("Empate!");
		}else if(playermove.equals("pedra")) {
			if(playermove2.equals("papel"))
				System.out.println("Jogador 2 ganhou!");
			break;
		}else if (playermove2.equals("tesoura")) {
			System.out.println("Jogador 1 ganhou");
			break;
		}else if (playermove.equals("papel")) {
			if (playermove2.equals("tesoura")) {
				System.out.println("Jogador 2 ganhou!");
				break;
			}else if (playermove2.equals("pedra")) {
				System.out.println("Jogador 1 ganhou!");
				break;
			}
		}else if (playermove.equals("tesoura")) {
			if (playermove2.equals("pedra")) {
				System.out.println("Jogador 2 ganhou!");
				break;
			}else if (playermove2.equals("papel")) {
				System.out.println("Jogador 1 ganhou!");
				break;
			}
			// criei a variavel pra jogada do jogador 1 e do jogador 2, criei um laço de repetição ao redor de todo o programa
			// para que ele possa reiniciar em caso de empate ou de entrada inválida
			// simplesmente eu coloco uma condição de parada que o programa não irá encontrar, ele só consegue sair do loop pelos breaks
			// em caso de vitória e/ou derrota.
		}
}
}
		else if (option == 2) {
			
			while (playAgain == false) {
			
			String ComputerMove = ppt[new Random().nextInt(ppt.length)];
			String ComputerMove2 = ppt[new Random().nextInt(ppt.length)];
			
			// Lá em cima, eu criei uma array com as opções pedra, papel e tesoura. Aqui o Computador 1 e 2 randomizam uma opção a partir desse array.
			
			System.out.println("A jogada do computador 1 foi " + ComputerMove);
			System.out.println("A jogada do computador 2 foi " + ComputerMove2);
		 if(ComputerMove.equals(ComputerMove2)) {
			System.out.println("Empate!");
		}else if(ComputerMove.equals("pedra")) {
			if(ComputerMove2.equals("papel"))
				System.out.println("Computador 2 ganhou!");
			    playAgain = false;
			break;
		}else if (ComputerMove.equals("tesoura")) {
			System.out.println("Computador 1 ganhou");
			break;
		}else if (ComputerMove.equals("papel")) {
			if (ComputerMove2.equals("tesoura")) {
				System.out.println("Computador 2 ganhou!");
				break;
			}else if (ComputerMove2.equals("pedra")) {
				System.out.println("Computador 1 ganhou!");
				break;
			}
		}else if (ComputerMove.equals("tesoura")) {
			if (ComputerMove2.equals("pedra")) {
				System.out.println("Computador 2 ganhou!");
				break;
			}else if (ComputerMove2.equals("papel")) {
				System.out.println("Computador 1 ganhou!");
				break;
				//Agora, o computador sempre vai inserir entradas válidas
				//Fiz com que as jogadas fossem printadas, para que o usuário saiba que o output foi correto
				// Mesma lógica do loop que só sai pelos breaks
}
}
}
}
}
}

