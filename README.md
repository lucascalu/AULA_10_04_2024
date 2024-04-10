# AULA_10_04_2024

<pre>

  Nome do Projeto: AT-S02-03B



Objetivo: Desenvolver um site utilizando HTML e JavaScript e apresentar os
dados em uma tabela, utilizando estruturas de decisão.



Descrição: Desenvolver um site utilizando HTML e
JavaScript de forma que o usuário entre com a idade e o sexo de um determinado
usuário, coletando essas informações através do comando “prompt” do JavaScript
e utilizando os mecanismos de estruturas de decisões de Lógica de Programação e
JavaScript, apresentem em uma tabela os dados de acordo com as categorias.






·       SEXO =
‘Masc’ e IDADE > 17 à Apresentar
o nome, foto de um HOMEM;


·       SEXO =
‘Masc’ e IDADE < 18 à Apresentar
o nome, foto de um MENINO/ADOLESCENTE;


·       SEXO = ‘Fem’
e IDADE > 17 à Apresentar
o nome, foto de uma MULHER;


·       SEXO = ‘Fem’
e IDADE < 18 à Apresentar
o nome, foto de uma MENINA/AD;


 


Componentes
Necessários:

- Software Visual Studio Code;

- Acesso à Internet para encontrar imagens
(fotos 3x4) ilustrativas de “homens”, “mulheres”, “meninos” e “meninas”;





Funcionamento:


1. Solicitar ao usuário
que informe seu nome, idade e sexo através de três comandos “PROMPT”s do
JavaScript (um para cada pergunta).

2. Crie uma tabela em HTML contendo três
Colunas/Títulos (Nome, Idade, Sexo e a foto) .

3. Na segunda linha da tabela, dever ser
exibido os dados coletados, de acordo com a descrição das categorias listas
anteriormente. Ou seja: Se o usuário digitou, por exemplo, SEXO = “M”
(masculino) e IDADE maior que 17 anos, a tabela deverá exibir uma foto de um
HOMEM



Considerações Adicionais:


- Garantir que o site valide
os dados de entrada, evitando valores negativos ou inválidos. Caso não atenda a
validação de dados, não deverá ser exibida a tabela. O usuário deverá atualizar
o site para começar desde o início uma nova ‘coleta de dados’.

- Utilizar comentários no código para
facilitar o entendimento do funcionamento de cada parte.



Critérios de avaliação:

(C) O aluno demonstrou compreensão dos
tipos de variáveis necessárias para armazenar dados como nome, idade e sexo



(C) O aluno aplicou corretamente a
estrutura de decisão



(C) O aluno demonstrou habilidade em utilizar operadores
lógico e aritméticos



(C) O aluno demonstrou habilidade em criar
tabelas em HTML



(C) O aluno utilizou operadores de comparação
(>, <, >=, <=) para avaliar as condições de classificação de
idade.



(D) O aluno utilizou formatação na tabela
HTML, como por exemplo cor de fundo nas células da primeira linha
(título/menus)



(D) O aluno utilizou estruturas condicionais
aninhadas para lidar com diferentes faixas de classificação de idade e
sexo.



(D) O aluno utilizou formatação em textos
HTML para apresentar os dados na página
</pre>

<pre>
  LINK PARA DOWNLOAD CONVERSOR HTML PARA JAVASCRIPT
  https://wtools.io/html-to-javascript-converter
</pre>

<pre>

  Nome do Projeto: AT-S02-03C IMC com JavaScript

Objetivo: Desenvolver um programa em JavaScript que calcula o Índice de Massa Corporal (IMC) com base no peso e altura digitados pelo usuário, que simula o "acender um um LED indicativo" de acordo com a classificação do IMC, porém utilizando imagens em HTML.

Descrição: O programa deve solicitar ao usuário que digite seu peso (em kg) e altura (em metros). Em seguida, calcular o IMC utilizando a fórmula IMC = peso / (altura * altura). Com base no resultado do cálculo, o programa deve acender um LED específico para cada classificação de IMC, conforme a seguinte tabela:
IMC < 18,5: LED verde (baixo peso)
18,5 <= IMC < 25: LED amarelo (peso normal)
25 <= IMC < 30: LED laranja (sobrepeso)
IMC >= 30: LED vermelho (obesidade)
Componentes Necessários:
- Imagens de LEDs (para simular LEDS das cores verde, amarelo, laranja, vermelho)
- 
















Software Visual Studio Code;

Funcionamento:
1. Solicitar ao usuário que digite seu peso e altura.
2. Calcular o IMC com base nos valores digitados.
3. Simular o "Acender  do LED" correspondente à classificação do IMC.
4. Repetir o processo sempre que o usuário desejar realizar um novo cálculo. O site deverá perguntar se o usuário deseja ou não.

Considerações Adicionais:- Garantir que o programa valide os dados de entrada, evitando valores negativos ou inválidos.
- Utilizar comentários no código para facilitar o entendimento do funcionamento de cada parte.
- Utilizar uma função para o cálculo do IMC e outra para o controle dos LEDs, facilitando a manutenção e expansão do programa.

Critérios de avaliação:
(C) O aluno demonstrou compreensão dos tipos de variáveis necessárias para armazenar dados como peso, altura e IMC no programa.

(C) O aluno aplicou corretamente os operadores aritméticos (+, -, *, /) para realizar o cálculo do IMC a partir dos dados de entrada.

(C) O aluno demonstrou habilidade em utilizar operadores de atribuição para atualizar os valores das variáveis envolvidas no cálculo do IMC.

(C) O aluno demonstrou compreensão da fórmula matemática do IMC e sua aplicação no contexto do programa.

(C) O aluno aplicou corretamente os operadores aritméticos para realizar o cálculo do IMC a partir dos dados de entrada.

(C) O aluno utilizou operadores de comparação (>, <, >=, <=) para avaliar as condições de classificação do IMC e exibiu as imagens em HTML simulando o "acender dos LEDs" correspondentes.

(D) O aluno utilizou loops de entrada para permitir que o usuário insira múltiplos conjuntos de dados para cálculo do IMC.

(D) O aluno utilizou estruturas condicionais aninhadas para lidar com diferentes faixas de classificação do IMC.

(D) O aluno empregou corretamente operadores lógicos (&&, ||) para combinar múltiplas condições de classificação do IMC.

(D)O aluno utilizou variáveis auxiliares para armazenar resultados intermediários durante o cálculo do IMC.

(D) O aluno implementou uma estrutura de repetição para permitir o cálculo do IMC para múltiplos conjuntos de dados.
</pre>
