# Estruturas Condicionais

Na aula de hoje dia 24/08/20 , vimos o assunto estruturas condicionais , com isso temos um dos termos mais conhecidos nele  , como : if , elif , else, else if . 
Com  isso devemos praticar este assunto para obter êxito nos nossos códigos desenvolvidos :
Iremos desenvolver um programa que irá nos dizer se você está acima do peso ideal referente á sua altura : 
 
 ```java
 public class IMC {

  public static void main(String[] args) {
     double altura = 1.85;
     double peso = 100;
     double imc = peso / (altura * altura);

     if(imc < 18.5) { 
         systen.out.println("Magreza");
        else if(imc < 25) {
          system.out.println("normal");
        else if(imc<30) {
          system.out.println("sobrepeso 1");
        else if(imc < 40) {
          system.out.println("obesidade 2");
        else 
          system.out.println("obesidade 3 ");
        }
      }
    }
       }
       
```
Nosso segundo exemplo explorado pelo professor Eduardo é bastante interessante , 
Nele, temos um formato de data padrão : 07/03/2000
Além disso temos um formato de data textual : sete de março de 2000
Com isso iremos criar uma classe para converter mês de numero para texto
public static string convertemesnumpratexto(byte mes) {
  if(mes==1) {
    return "janeiro";
  } else if (mes==2){
    return "fevereiro";
  } else if (mes==3) {
    return "março";
  }  else if (mes==4) {
    return "abril";
  } else if (mes==5) {
    return "maio";
  } else if (mes==6) {
    return "junho";
  } else if (mes==7) {
    return "julho";
  } else if (mes==8) {
    return "agosto";
  } else if (mes==9) {
    return "setembro";
  } else if (mes==10) {
    return "outubro";
  } else if (mes==11) {
    return "novembro";
  } else if (mes==12) {
    return "dezembro";

Observando esse mesmo código devemos ter um pouco de lógica que irá facilitar nosso trabalho : elaborando uma forma mais prática de se fazer este mesmo código apresentado :

public static string convertemesnumpratexto(byte mes) {
 switch(mes) {
   case 1 return "janeiro";
   case 2 return "fevereiro";
   case 3 return "março";
   case 4 return "abril";
   case 5 return "maio";
   case 6 return "junho";
   case 7 return "julho";
   case 8 return "agosto";
   case 9 return "setembro";
   case 10 return "outubro";
   case 11 return "novembro";
   case 12 return "dezembro;"
   default: return "mês inexistente";
 }
