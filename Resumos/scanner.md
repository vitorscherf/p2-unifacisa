Diante o que foi apresentado em sala de aula pelo professor eduardo, eu aprendi que:
a classe Scanner tem como objetivo separar a entrada dos textos em blocos,
 gerando os conhecidos tokens:
 que são sequências de caracteres separados por delimitadores que por padrão correspondem aos espaços em branco, tabulações e mudança de linha.
 Com essa classe podem ser convertidos textos para tipos primitivos.
 essa classe conhecida por nós , nos  ajuda na leitura dos dados informados, podemos utilizar um exemplo de programação orientada a objetos,
 neste modo scanner ,
 O objetivo é mostrar o que se pode fazer usando as lições básicas aprendidas na manipulação de objetos.
 Os métodos setters guardam o valor digitado pelo usuário
 que depois são usados para gerar a saída de cada objeto criado na lista.
 
 ```java
 
 public class Pessoa {

  private Integer codigo;
  private String nome;
  private String endereco;
  private Integer idade;

  public Integer getCodigo() {
    return codigo;
  }

  public void setCodigo(Integer codigo) {
    this.codigo = codigo;
  }

  public String getNome() {
    return nome;
  }

  public void setNome(String nome) {
    this.nome = nome;
  }

  public String getEndereco() {
    return endereco;
  }

  public void setEndereco(String endereco) {
    this.endereco = endereco;
  }

  public Integer getIdade() {
    return idade;
  }

  public void setIdade(Integer idade) {
    this.idade = idade;
  }

  @Override
  public String toString() {
    return "Código: "+codigo+ "" +
            "\n"+ "Nome: "+nome+"" +
                "\n"+"Endereço: "+endereco+"" +
                    "\n"+"Idade: "+idade+"\n";
  }
}
