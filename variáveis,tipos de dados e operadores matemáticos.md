*O que são variáveis? :smiley: 
Na linguagem Java
Um espaço na memória do computador, onde se pode guardar valores

Existem 4 tipos:
1- Instância: Objeto
2-Classe:classe
3-Local:dentro de métodos
4-Parâmetro:Na assinatura do método

Padrão de definição:
<?visibilidade?><?modificador?>tipo<?=valorInicial?>;

V:"public","protect",e "private"
M:"static" e "final"
T: tipo de dado(sempre tem que ser definido)
N: nome que é fornecido a variável
Vl:umvalor inicial,caso se deseje

Convenções e  regras

Não devem começar com números;
"$" e "_" devem ser evitados no início ou final.
Diferencia maiúscula e minúsculas
Não colocar espaço no nome da variável
Palavras reservadas Java(não criar variáveis com esses nomes)
*abstract continue for new switch assert default goto package synchronizedboolean di if private this break double case Implements trhow protected byte
*else mport public trhows enum instanceof return transient catch extends int short try volatile const float native super while

Exemplo: int i; int I; int 1a(forma errada, dá erro de compilação); int_1a(não dá erro, mas não é uma boa prática);

*BOAS PRÁTICAS*
Sempre começar com letra minúscula,
Nomes expressivos, fáceis de identificar do que se trata a variável
Notação camelo .Ex: int quantidadeProduto
Na variável constante final pode ser usado o "_"


Exercício

Criar as variáveis 
int quantidadeProduto
int QuantidadeProduto
int final numero_Tentativas = 5;
int NUMERO_TENTATIVAS=5;
int qtdProd;
int i; 
Veja quais os erros que podem apararecer e descreva qual foi

public static viod main(String[] args) {
int i;
int I;
int _1a;
i= 5
I= 5
_1a =20
$aq =7
finla int j=10
j=15
int snvbh1234
int snvbh_1234

}
comente a variação correta embaixo utilizando"//"


*TIPOS DE DADOS*:smiley:

 São valores e operações que as variáveis podem assumir e sofrer, respectivamente

Tipificação:
-Estática(forte) vs Dinâmica(fraco)
Uma linguagem obriga a definir o tipo da variável e não muda. A Dinâmica não obriga a definir a variável no iníci e permite mudanças
-Primitivo vs Composto
Dados mais básicos , valores numéricos, textuais. Composto: eterogêneo, pode conter vários tipos de dados

Opções de tipos:
Textual
Numeral(inteiros ou reais)
Lógico(verdadeiro ou falso)
Objeto

Ex numeral: byte:-128 até 127>byte b =15;
 textual: char:caracteres de 16-bit unicide>char c ='T'
string>String s ="T"
lógico true e false >boolean=false

Exercício 

Criar um projeto simples e duas variáveis para cada tipo de dados



*OPERADORES ARITMÉTICOS

São símbolos especiais capazes de realizar ações específicas, mesclados para chegar a um resultado final

-pós fixados: exp++ ou exp--
-pré fixado:++exp ou --exp
-aritmético +,-,*,/ e %
-atribuição:=,+=,-=,*=,/= e %=

ex: int i =++k>i=k+1
int j =k-->j=k>k=k-1
double d=f
i+=5 i=i+5


Prioridade :exclamation:

pós fixado exp++,exp--
prefixado ++exp,--exp
mulitplicativo *,/,%
aditivo +,-
atribuição =,+=,-=,/=,%=

Exercício

Crie um projeto e as variáveis apresentada. Corrija erros encontrados

public class main {

public static void main (String[] args) {
system.out.printIn("PrePos")
prePos()
System.out.printIn("Aritimético")
aritmetico()
System.out.printIn("Atribuição")
atribuicao()
System.out.printIn("Precedencia")
precedencia()

}

private status void prePos() {
int k = 10

int i=++k
int j=k++
int x= k

System.out.printIn("i" + i)
System.out.printIn("j" + j)
System.out.printIn("x" +x)
}

private static void aritmetica() {

int a=10
int b=20
int c=30
int d=40
int e=50

int r1= a+b
int r2= c-a
int r3= d*b
int r4= e/a
int r5= c%d

System.out.printIn("a+b" + r1)
System.out.printIn("c-a" + r2)
System.out.printIn("d*b" + r3)
System.out.printIn("e/a" + r4)
System.out.printIn("c%d" + r5)

}
private static void main atribuicao(){
 int i = 1500
short j = 11
long l=500
int k = 35
float f = 3.5f
double d=f

System.out.printIn("d" + d)

i+= 5
j-= 3
d /= 2
l*= 3
k%= 2

System.out.printIn("i" + i)
System.out.printIn("j" + j)
System.out.printIn("d" + d)
System.out.printIn("l" + l)
System.out.printIn("k" + k)
  
i = k = j

System.out.printIn("k" + k)
System.out.printIn("i" + i)

}

private static void main precedencias() {

int i =10
int j =20 
int k =30

int a = i++ + --j * k

System.out.printIn ("i++" + --j * k:" + a)

System.out.printIn("i" + 1)

int b = k/ --1 %3 + 1
 System.out.printIn("k / --1 % 3 + 1" + b)

System.out.printIn("i" + 1)

}

}
  

**CASTING(CONVERSÕES)**

É a transformação de uma determinada variável menos específicos para uma mais específico e vice-versa
 
Upcast (Impicito)

Downcast (Explicito)

Ex
long l int i-10 I=1 (está implicito que sera feito o upcast pois a variável cabe dentro da nova)
 
pegar uma variavel real e mudar p inteiro pode ser perigoso e perder dados


*Exercício*

Ciar um projeto e criar variaveis para realizar casting.
Agora é com você :smiley:


