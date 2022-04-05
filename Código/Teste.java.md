## Teste.java



package br.com.estudandoJava.executavel;

import br.com.estudandoJava.models.Motor;
import br.com.estudandoJava.models.Veiculo;

public class Teste {
	
	public static void main(String[] args) {


​				
		Motor motor1 = new Motor();// instanciando objeto 
		motor1.setPotencia(600); // atribuindo valor
		motor1.setQtdPist(2); //atribuindo valor
		
		System.out.println("------------Dados do motor 1----------");
		System.out.println("Potencia:" + motor1.getPotencia());
		System.out.println("Pistao:" + motor1.getQtdPist());
		
		Motor motor2 = new Motor();
		motor2.setPotencia(500);
		motor2.setQtdPist(500);
		
		System.out.println();
		System.out.println("-----------Dados do motor 2-----------");
		System.out.println("Potencia:" + motor2.getPotencia());
		System.out.println("Pistao:" + motor2.getQtdPist());
		
		Veiculo veiculo1 = new Veiculo(null, null, null, null, 0, 0, motor2); // instanciando objeto
		veiculo1.setPlaca("AAA1111"); //atribuindo valor
		veiculo1.setMarca("Toyota");
		veiculo1.setModelo("EX");
		veiculo1.setCor("branco");
		veiculo1.setVelocMax(500F);
		veiculo1.setQtdadeRodas(4);
		veiculo1.setMotor(motor2); // nao consegui arrumar o que esta imprimindo
		
		System.out.println();
		System.out.println("----------Dados do veiculo 1----------");
		System.out.println("Placa:" + veiculo1.getPlaca());
		System.out.println("Marca:" + veiculo1.getMarca());
		System.out.println("Modelo:" + veiculo1.getModelo());
		System.out.println("Cor:" + veiculo1.getCor());
		System.out.println("Velocidade Maxima:" + veiculo1.getVelocMax());
		System.out.println("Quantidade de rodas:" + veiculo1.getQtdadeRodas());
		System.out.println("Motor:" + veiculo1.getMotor());
		
		Veiculo veiculo2 = new Veiculo(null, null, null, null, 0, 0, motor2); // instanciando objeto
		veiculo2.setPlaca("AAA2222"); //atribuindo valor
		veiculo2.setMarca("Renault");
		veiculo2.setModelo("FX");
		veiculo2.setCor("vermelho");
		veiculo2.setVelocMax(400F);
		veiculo2.setQtdadeRodas(4);
		veiculo2.setMotor(motor2); // nao consegui arrumar o que esta imprimindo
		
		System.out.println();
		System.out.println("----------Dados do veiculo 2----------");
		System.out.println("Placa:" + veiculo2.getPlaca());
		System.out.println("Marca:" + veiculo2.getMarca());
		System.out.println("Modelo:" + veiculo2.getModelo());
		System.out.println("Cor:" + veiculo2.getCor());
		System.out.println("Velocidade Maxima:" + veiculo2.getVelocMax());
		System.out.println("Quantidade de rodas:" + veiculo2.getQtdadeRodas());
		System.out.println("Motor:" + veiculo2.getMotor());
		
		Veiculo veiculo3 = new Veiculo(null, null, null, null, 0, 0, motor2); // instanciando objeto
		veiculo3.setPlaca("AAA3333"); //atribuindo valor
		veiculo3.setMarca("Fiat");
		veiculo3.setModelo("Uno");
		veiculo3.setCor("verde");
		veiculo3.setVelocMax(120F);
		veiculo3.setQtdadeRodas(4);
		veiculo3.setMotor(motor2); // nao consegui arrumar o que esta imprimindo
		
		System.out.println();
		System.out.println("----------Dados do veiculo 3----------");
		System.out.println("Placa:" + veiculo3.getPlaca());
		System.out.println("Marca:" + veiculo3.getMarca());
		System.out.println("Modelo:" + veiculo3.getModelo());
		System.out.println("Cor:" + veiculo3.getCor());
		System.out.println("Velocidade Maxima:" + veiculo3.getVelocMax());
		System.out.println("Quantidade de rodas:" + veiculo3.getQtdadeRodas());
		System.out.println("Motor:" + veiculo3.getMotor());
		
		Veiculo veiculo4 = new Veiculo(null, null, null, null, 0, 0, motor2); // instanciando objeto
		veiculo4.setPlaca("AAA4444"); //atribuindo valor
		veiculo4.setMarca("Chevrolet");
		veiculo4.setModelo("Chevete");
		veiculo4.setCor("azul");
		veiculo4.setVelocMax(200F);
		veiculo4.setQtdadeRodas(4);
		veiculo4.setMotor(motor2); // nao consegui arrumar o que esta imprimindo
		
		System.out.println();
		System.out.println("----------Dados do veiculo 4----------");
		System.out.println("Placa:" + veiculo4.getPlaca());
		System.out.println("Marca:" + veiculo4.getMarca());
		System.out.println("Modelo:" + veiculo4.getModelo());
		System.out.println("Cor:" + veiculo4.getCor());
		System.out.println("Velocidade Maxima:" + veiculo4.getVelocMax());
		System.out.println("Quantidade de rodas:" + veiculo4.getQtdadeRodas());
		System.out.println("Motor:" + veiculo4.getMotor());
		
		Veiculo veiculo5 = new Veiculo(null, null, null, null, 0, 0, motor2); // instanciando objeto
		veiculo5.setPlaca("AAA5555"); //atribuindo valor
		veiculo5.setMarca("Ford");
		veiculo5.setModelo("Fox");
		veiculo5.setCor("amarelo");
		veiculo5.setVelocMax(300F);
		veiculo5.setQtdadeRodas(4);
		veiculo5.setMotor(motor2); // nao consegui arrumar o que esta imprimindo
		
		System.out.println();
		System.out.println("----------Dados do veiculo 5----------");
		System.out.println("Placa:" + veiculo5.getPlaca());
		System.out.println("Marca:" + veiculo5.getMarca());
		System.out.println("Modelo:" + veiculo5.getModelo());
		System.out.println("Cor:" + veiculo5.getCor());
		System.out.println("Velocidade Maxima:" + veiculo5.getVelocMax());
		System.out.println("Quantidade de rodas:" + veiculo5.getQtdadeRodas());
		System.out.println("Motor:" + veiculo5.getMotor());
	
	}

}