##Operadores Relacionais :bowtie:  

São símbolos especiais quais são capazes de realizar comparações entre determinados operandos
e,em seguida,retornar um resultado.

Tipos:
Similaridade:igual,diferente
Tamanho:maior,menor igual,menor,menor igual

Sempre existirão dois operandos, mesmo  iguais.

##Utilizando operadores Relacionais

SIMILARIDADE
-Igualdade: determina se um operando é igual ao outro
-Diferença:determina se um operando não é igual ao outro

SIMBOLOGIA
-Igualdade: ==
-Diferença: !=

TAMANHO
Maior: Determina se um orador é maior do que outro
MAior igual: Determina se um orador é maior ou igual do que outro

SIMBOLOGIA
-Maior: <
-Maior igual : <=


TAMANHO
Maior: Determina se um orador é maior do que outro
MAior igual: Determina se um orador é maior ou igual do que outro



SIMBOLOGIA
-Menor: <
-Menor igual : <=

EXEMPLOS

int i1 = 10;int i2 = 20;float f1 = 4.5f;float f2 = 3.5f; char c1 = 'x',
char c2 = 'y';String s1 = "Fulano";String s2 = "Fulano";boolean b1 = true; boolean b2 = false;
i1==i2, i1!=i2,i1>i2,i1<i2
                           
##Operadores lógicos
São símbolos especiais quais são capazes de realizar comparações 
lógicas enre operandos lógicos ou expressões e , em seguida, retornar um resultado.
Tipos:                           
-Conjunção                           
Disjunção                           
Disjunção exclusiva                           
Negação                           
                           
 ##Como utilizar Operadores Lógicos                          
 -Conjunção:operação lógica que só e verdadeira quando ambos os operandos ou expressões envolvidas são verdade                          
                           
  Simbologia                         
- &&                           
Terminologia
-and(e)                           
O-E       O-E      R                           
  V       V        V          
  V       F        F         
  F       F        F          
  F       F        F          
                           
O--OPERANDO  E- EXPRESSÃO R-RESULTADO
                           
-Disjunção
                           
 -Conjunção:operação lógica que só e falsa quando ambos os operandos ou expressões envolvidas são falsos                        
                           
  Simbologia                         
- ||(tecla ao lado do "z")                           
Terminologia
- or (ou)                          
                           
  O-E       O-E      R                           
  V       V        V          
  V       F        V         
  F       V        V         
  F       F        F                          
                           
  -Disjunção exclusiva
                           
   -Conjunção:operação lógica que só e verdadeira quando ambos os operandos ou expressões  são opostos                          
                         
    Simbologia                         
- ^                         
Terminologia
- xor                         
                           
  O-E       O-E      R                           
  V       V        F         
  V       F        V         
  F       V        V         
  F       F        F                           
                           
-Negação                           
  
   -Conjunção:operação que inverte o valor lógico de um operando ou expressão                         
                         
    Simbologia                         
- !                         
Terminologia
- inverção                         
                           
  O-E    R                            
  V      F                
  F      V             
                     
## Conteúdo Adicional
                           
-Operadores bitwise : & e | (não confunda com os símbolos acimas, mexem com bits)                          
-Operadores Shift: ~,>>,>>>,<< (mexem com os bits ou os zeros antes e depois)                          
                           
Exemplo:                           
boolean b1 = true;boolean b2=false;boolean b3=true,boolean b4=false                           
                           
b1&&b2,b1&&b3;b2||b3,b2||b4;b1^b3,b4^b1;!b1,!b2;                           
                           
 ##Controle de fluxo                          
                           
 São estruturas que tem a capacidade de direcionar o fluxo de execução do código                          
                           
Tipos:                           
Decisão: if, if-else,if-else-if,switch e operador binario                           
Repetição: for,while, do while                           
Interrupção: break,continue e return                           
                           
  ###  Criando estruturas de controle de fluxo                        
 Tipos:                          
-Decisão: estrutura que avalia uma condiçaõ booleana ou variável para direcionar o fluxo de execução                           
-Opções: if(se),switch(escolha), e operador ternário                           

  ##Boas práticas 😃 
  
  🌠
  
  -Switch é para valores exatos e if para expressões booleanas
-Evitar usar defaul do switch para "cases genéricos"                           
-Evitar efeito "flecha" dos if's                           
-Evitas muitos if's alinhados
  -Usar a boa práica da aula 2(operadores lógicos) para diminuir o tamanho do if
  
  
  ##Blocos  :eyes:
  
 É um grupo de0 ou mais códigos que trabalham em conjunto para executar a opração
  -Locais:dentro de métodos
  -Estáticos
  -InstÂncias
  
  Criação
  Locais{
  
  ...
  
  
  }
  
  
  
  if(autorizado) {
  CarregaPerfil
  DirecionarPaginaPrincipal
  }
  
  if (menridade)
  DirecionarPaginaProibido
  
