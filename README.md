# LFA-DSL

[Especificações do trabalho](lfa-trab-final-2019-1.pdf)

### Grupo:
- Ewerson Vieira Nascimento (ewersonv@gmail.com)
- Paulo Ricardo Viana Ferreira (paulo_ricardosf@outlook.com)
- Willian Bruschi Vaneli (willianvaneli@gmail.com)

#### Ambiente de desenvolvimento:
Programa desenvolvido em Python (3.6.7), utilizando a biblioteca [Lark](https://github.com/lark-parser/lark), Ubuntu 18.04 e PyCharm 2019.1.3 (Community Edition).

### Descrição dos arquivos:


### Descrição da linguagem:
A DSL proposta neste trabalho tem como objetivo prover uma linguagem que permita realizar operações matemáticas aritméticos. Optamos por utilizar a linguagem Python para o desenvolvimento, pela simplicidade de criação de artefatos em geral.
A linguagem permite utilizar artefatos de nomeação de variáveis, além de construção de comandos de seleção IF e repetição WHILE. Permitindo também artefatos de abstração conhecidos como função ou procedimento, geralmente utilizados nas diversas outras linguagens de programação. 


### Tabela com Operadores e Expressões

Operador | Descrição
--------- | ------
=     | Atribuição. Ex.: <variável> = <conteúdo>;
" "    | String. Ex.: “<caracteres>”;
{ }    | Área que pertence a um método ou expressão. Ex.: <método>{<operações>} ou <expressão>{<operações>};
+,-,*,/,^ | Operadores aritiméticos;
    
    
Expressão | Descrição
--------- | ------
def     | Expressão que define um método. Ex.: def <nome-do-método>(<argumentos>){ };
if    | Expressão que indica uma bifurcação exclusiva. Ex.: if (<variável-de-origem>, <variável-de-destino>) (<string>){<operações>};
while   | Expressão que indica um loop. Ex.: while (<variável-de-origem>, <variável-de-destino>) (<string>){<operações>*};

#### Instalando o Lark:
Para poder instalar o Lark, primeiro precisamos instalar o [Pip](https://pypi.org/project/pip/).

1. Começamos atualizando a lista de pacotes:

    ``$ sudo apt update``

2. Como estamos utilizando o Python 3, instalaremos o Pip com o seguinte comando:

    ``$ sudo apt install python3-pip``

3. Para verificar se o Pip foi instalado corretamente, fazemos:

    ``$ pip3 --version``c

    Teremos como retorno algo similar a:

    ``pip 9.0.1 from /usr/lib/python3/dist-packages (python 3.6)``

4. Agora, para instalar o Lark, basta fazer:

    ``$ pip3 install lark-parser``
