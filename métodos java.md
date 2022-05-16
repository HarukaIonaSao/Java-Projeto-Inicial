Criação

É uma porção de código(sub-rtina) que é disponibilizada por uma classe.
Estaá dentro de uma classe
É executado quando feita uma requisição a ele.
Definem um comportamento.

Padrão de definição

<?visibilidade?><?tipo?><?modificador?>retorno>nome(<?parâmetros?>
<?exceções?>corpo  O q está com interrogação é opcional

V:"public","protected","private"
T:concreto ou abstrato
M:"static" ou "final
R:tipo de dado "void"(retorno)
N:nome fornecido ao método
P: parâmetros que pode receber
E:exceções que pode lançar
C:código que possui ou vazio (corpo)

Ex:
public String getNome(){...}
public double calcularTotalNota(){...}
public Relatorio gerarDadosAnaiticos(Cliente clienteList<Compra>compras){...
}


Utilização

Passa-se uma mensagem através de uma classe ou objeto

nome_da_classe.nome_do_medo();ou nome_da_classe.nome_do_metodo(...)
Math.random()
classe math,método random

classe começa c letra maiúscula objeto começa com minúscula

**Particularidades**

Assinatura: é a forma de identificar de forma única o método

Ass=nome +parâmetros

Método:
public double calcularTotalVenda (double precoItem1, double precoItem2){...}


construtor e Destrutor: São métodos especiais na Orientação a Objetos

Mensagem: Solicita(chama) ao método que o mesmo execute. Pode ser usada por método e objeto

Passagem de parâmetros:

Por valor(cópia)
 Ex: int i = 10; public void fazerAlgo(int i ){

i=1 + 10;
System.out.pintInt("VAlor de i dentro : " + i)
System.out.printIn("Valor de i fora : " + i)



**Boas práticas**

NOMES DEVEM SER DESCRITIVOS E CURTOS,EVITE ARTIGOS E PREPOSIÇÕES
(A,O,DE,DA,DI)
NOTAÇÃO CAMELO
EX:verificarSaldo();
DEVE POSSUIR ENTRE 80 A 120 LINHAS
EVITE LISTA DE PARÂMETROS LONGAS
VISIBILIDADE ADEQUADAS

Por referência (endereço)

 
**Exercício**
Crie um aplicação que resolva as situações

-Calcule as 4 operações básicas.Sempre 2 valores devem se passadas
-A partir da hora, exiba a mensagem adequada:Bom dia, tarde ou noite
-Calcule o valor final de um emprésimo.Taxas e parcelas influenciam.

-Os códigos também estão no projeto do github Java-Projeto-Inicial
https://github.com/HarulaIonaSao1/Java-Projeto-Inicial.git 

:wave: 
**Veja se tem algum erro e coloque no seu relatório e como resolveu. Bons estudos
Lista de emoticons p usar no Github e deixar suas descrições mais amigáveis
https://gist.github.com/rxaviers/7360908

***Sobrecargas***

É a capacidade de definir métodos para diferentes contextos, mas preservando seu nome

Mesmo com o mesmo nome, o comportamento pode ser diferente, mudando a lista de parâmetros.

Alterar a assinatura do método
Ass: nome + parâmetros

Ex: converterParaInteiro(float f);
Ex: valueOf(boolean)
valueOf(char c)

-Sobrecarga x Sobrescrita
Pesquise sobre

:star2:

*Os exercícios estão no Github*






