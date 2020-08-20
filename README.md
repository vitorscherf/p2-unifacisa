#  p2-unifacisa
Estamos  dando inicio á disciplina de programação 2 com p professor eduardo , nos passos iniciais a principal linguagem para esta disciplina será java. com isso estarei expondo osa pontos principais 
sobre os assuntos tratados :

operadores :
Operadores 
- aritméticos :
        Binários: +, -, *,  /, %
       Unário: ++,  --
-logicos :
 binários : &&, ||
unário:  !
-atribuição:  =, +=, -=, *=,  /=,  %=
-relacionais               
Exemplo 
int a = 2 ;
a *= 10;     //  a  = a*10;
outro fator bastante usado é o da igualdade e comparação :  ==,  !=

o ternário é bastante utilizado podemos exemplificar como :
boolean aceso = true;
string infocigarro = “ ”;
if (aceso  == true) {
               infocigarro  =  “cigarro está aceso!”;
} else{
              Infocigarro = “cigarro está apagado!”;
}
Forma ternária :
String infocigarro  = (aceso  == true?  “cigarro está 
 aceso!”  :  “cigarro está apagado );  
 
 Lembrando  dos tipos primitivos podemos citar um exemplo básico de revisão deste componente : 
public class tiposprimitivos{
          public static void main(string[]args){
                       byte idade  =  20;
                       sting nome  = ”vitor” ;
                       system.out.println(“nome + ” tem ” + idade  + “anos!” ) ;

