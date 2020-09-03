# classes e objetos 

Diante do que vimos em sala de aula , tenho o conhecimento adquirido apartir do principal assunto da disciplina ,
classes e objetos , fator de grande importância é saber o que são cada um deles e como eles estão inclusos diretamente na programação, 
classes : falando superficialmente é o nosso  “código”, podemos usar a comparação de que uma classe é como uma planta baixa e a casa seria o objeto ,
poderemos ter outro exemplo de que um esporte é uma classe e futebol, vôlei, judô  são os objetos dessa classe .
também é importante criarmos construtores com argumentos , outro exemplo possivel, como um de uma refeição sendo uma classe e seus objetos sendo
carboidratos, proteinas , para entender melhor a execução desse conceito temos :  :

```java
class refeicao{
  string nome;
  string carboidrato;
  int gramascarboidrato;
  string proteina;
  int gramasproteina;
  int tempocozimento;
  double preco;

  public refeicao(string nome, string carboidrato, int gramascarboidrato, string proteina, int gramasproteina, int tempocozimento, double preco),
     this.nome = nome;
     this.carboidrato = carboidrato;
     this.gramascarboidrato = gramascarboidrato;
     this.proteina = proteina;
     this.gramasproteina = gramasproteina;
     this.tempocozimento = tempocozimento;
     this.preco = preco;
 }
 
 O outro detalhe de bastante i8mportancia mencionado pelo professor eduardo é a funbção to string que seu objetivo é retornar em string os valores do objeto : exemplo 
 
 ```java
 public string tostring() {
  string saida = "";
  saida += nome+ " R$ " +preco+" /n" ;
  return saida;
