## Veiculo.java

package br.com.estudandoJava.models;

public class Veiculo {
	
	private String placa;
	private String marca;
	private String modelo;
	private String cor;
	private float velocMax;
	private int qtdadeRodas;
	private Motor motor;


​	
	@Override
	public String toString() {
		return "Veiculo [motor=" + motor + "]";
	}
	
	public Veiculo(String placa, String marca, String modelo, String cor, float velocMax, int qtdadeRodas,
			Motor motor) {
		
		this.placa = " ";
		this.marca = " ";
		this.modelo = " ";
		this.cor = " ";
		this.velocMax = 0;
		this.qtdadeRodas = 0;
		this.motor = motor;
	}
	
	public String getPlaca() {
		return placa;
	}
	public void setPlaca(String placa) {
		this.placa = placa;
	}
	public String getMarca() {
		return marca;
	}
	public void setMarca(String marca) {
		this.marca = marca;
	}
	public String getModelo() {
		return modelo;
	}
	public void setModelo(String modelo) {
		this.modelo = modelo;
	}
	public String getCor() {
		return cor;
	}
	public void setCor(String cor) {
		this.cor = cor;
	}
	public Float getVelocMax() {
		return velocMax;
	}
	public void setVelocMax(Float velocMax) {
		this.velocMax = velocMax;
	}
	public int getQtdadeRodas() {
		return qtdadeRodas;
	}
	public void setQtdadeRodas(int qtdadeRodas) {
		this.qtdadeRodas = qtdadeRodas;
	}
	public Motor getMotor() {
		return motor;
	}
	public void setMotor(Motor motor) {
		this.motor = motor;
	}


​	

}