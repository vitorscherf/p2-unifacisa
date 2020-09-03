#tipos primitivos
Diante do que vimos em sala de aula , gostaria de expressar assuntos importantes para o ambiente de estudo :
Expressões aritméticas foi um assunto bastante abordado em nossa aula :
São elas :  soma, multiplicação , subtração, divisão , resto :  +, * , %,  - , /
Podemos analisar , exemplos  como : int idade = 50 ; números  double  como altura =  1,80
Utilizamos double ou float para os números decimais .
Tipos Primitivos : 
Os tipos numéricos inteiro  temos  :  byte, short, int, long
Tipos numéricos com ponto flutuante  são : float e double 
Strings utilizamos para texto.
Nomes  de variáveis : nunca utilizar acentuação,  sempre utilizar no inicio letra maiúscula .
Com isso : podemos criar um pequeno programa para que podemos ter uma noção do ambiente java :
 ```java
 class Main {
  public static void main(String[] args) {
          byte idade = 20;
          string nome = "vitor";

    System.out.println(nome + " tem " + idade + "anos!");
  }
}
Ternário : 
Podemos analisar essa importante característica para facilitar a execução no ambiente java :
```java
boolean  ligado =  true;
string infocarro  = “ ”;
if (ligado == true) { 
                infocarro = “carro está  ligado!”;
} else { 
              Infocarro  = “carro está  desligado!”;
}
Forma ternária :
```java
String infocarro = (ligado == true?  “ carro  está
Ligado!” :  “ carro está  desligado!”)
