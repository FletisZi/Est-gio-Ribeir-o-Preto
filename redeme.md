# ESTÁGIO RIBEIRÃO PRETO - 2024 🤖
Repositorio com as respostas para desafio do estágio ribeirão preto 2024
<h1 align="center" >
    <img src='./path/public/gif.gif'>
</h1>


## 📖 Sobre

Este repositório contém as soluções para um teste de lógica de programação, realizado como parte do processo de seleção para um estágio. O teste consiste em cinco questões que abordam diferentes aspectos da lógica de programação.


## Questão 1

Observe o trecho de código abaixo:

```bash
    int INDICE = 13, SOMA = 0, K = 0;

    enquanto K < INDICE faça

    {

        K = K + 1;

        SOMA = SOMA + K;

    }

    imprimir(SOMA);
```

Ao final do processamento, qual será o valor da variável SOMA?

Resposta: **91**


## Questão 2

Dado a sequência de Fibonacci, onde se inicia por 0 e 1 e o próximo valor sempre será a soma dos 2 valores anteriores (exemplo: 0, 1, 1, 2, 3, 5, 8, 13, 21, 34...), escreva um programa na linguagem que desejar onde, informado um número, ele calcule a sequência de Fibonacci e retorne uma mensagem avisando se o número informado pertence ou não a sequência.

**IMPORTANTE:**

Esse número pode ser informado através de qualquer entrada de sua preferência ou pode ser previamente definido no código;

Resposta: Para resolução dessa questão foi utilzado logica de programação para calcular Fibonacci e mostrar quais resultados são verdadeiro passando tudo isso para JAVASCRIPT e HTML para fácil visualização do resultado 

Teste: (https://portifolio.fletiszi.online/Est-gio-Ribeir-o-Preto/exercicio%202/index.html)

Código resolução: (https://github.com/FletisZi/Est-gio-Ribeir-o-Preto/blob/main/exercicio%202/index.html)


## Questão 3

Descubra a lógica e complete o próximo elemento:

a) 1, 3, 5, 7, ___

b) 2, 4, 8, 16, 32, 64, ___

c) 0, 1, 4, 9, 16, 25, 36, ___

d) 4, 16, 36, 64, ___

e) 1, 1, 2, 3, 5, 8, ____

f) 2,10, 12, 16, 17, 18, 19, ____

Resposta: **9 , 128, 49, 100, 13, 200**


## Questão 4

Você está em uma sala com três interruptores, cada um conectado a uma lâmpada em uma sala diferente. Você não pode ver as lâmpadas da sala em que está, mas pode ligar e desligar os interruptores quantas vezes quiser. Seu objetivo é descobrir qual interruptor controla qual lâmpada.

Como você faria para descobrir, usando apenas duas idas até uma das salas das lâmpadas, qual interruptor controla cada lâmpada?

Resposta: Para resolução dessa questão vamos abstrair da seguinte forma: existe os interruptores **A, B e C** e também exite as lampadas **A, B e C**. 

Na primeira ação ligaria o interruptor **A** por 5 min e depois delisgaria o mesmo, em seguida ligaria o interruptor **B**, e iria na sala da lampada **A** caso não etivesse ligado iria com a mão verificar se está quente e dessa forma resolveria, pois a sala que tiver com a lampada quente é referente ao interruptor **A** e a sala que lampada estiver acesa é referente ao interruptor **B** e por fim a sala que não tiver lamapda acesa ou quente é referente a interruptor **C** que não foi acionado nem um vez; 

## Questão 5

Escreva um programa que inverta os caracteres de um string.

**IMPORTANTE:**

a) Essa string pode ser informada através de qualquer entrada de sua preferência ou pode ser previamente definida no código;

b) Evite usar funções prontas, como, por exemplo, reverse;

Resposta: Para resolução dessa questão foi utilzado logica de programação para manipular string e fazer uma pilha reversa, passando tudo isso para JAVASCRIPT e HTML para fácil visualização do resultado 

Teste: (https://portifolio.fletiszi.online/Est-gio-Ribeir-o-Preto/exercico%204/index.html)

Código resolução: (https://github.com/FletisZi/Est-gio-Ribeir-o-Preto/blob/main/exercico%204/index.html)


