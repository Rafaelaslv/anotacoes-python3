 ## 📣 Hey!!

---

### Este repositório conterá minhas anotações dos conhecimentos obtidos sobre laços de repeticão através da plataforma Descomplica.

---

#### LAÇOS DE REPETIÇÃO / O CONCEITO DE LAÇO

Os laços são grandes facilitadores na vida do programador, permitindo automatizar várias tarefas que, em tese, seriam executadas de forma manual.

O domínio da lógica por trás dos laços de repetição é uma das características de bons programadores, pois este assunto é um dos corações da programação. 

De forma similar às condicionais, os laços de repetição têm uma estrutura base que sempre analisará uma ou mais afirmações (chamadas de proposição) para avaliar se uma determinada ação deve ser executada ou não.

Ao falarmos de laço, estamos nos referindo especificamente a ações que serão realizadas de forma sequencial em repetição (daí o nome).

Um exemplo interessante é você pensar da seguinte forma: em uma busca pela palavra “Python”, no Google, alguns resultados serão exibidos na tela. Enquanto existir resultados, o Google irá exibi-los.

QUANDO O GOOGLE DEIXARÁ DE EXIBIR RESULTADOS?

QUANDO NÃO TIVER MAIS RESULTADOS PARA MOSTRAR.

MAS ENQUANTO EXISTIREM RESULTADOS PARA SEREM EXIBIDOS, ELE CONTINUARÁ EXIBINDO.

A estrutura é a mesma, todas tem um título, uma URL, uma descrição e o link.

A ESTRUTURA É A MESMA, ELA SE REPETE ENQUANTO TIVER RESULTADOS PARA SEREM EXIBIDOS.

O enquanto é um tipo de laço de repetição, mas não o único. Existe, dependendo da linguagem escolhida, alguns tipos de laço de repetição; no Python especificamente, existem basicamente dois tipos:

Laço do tipo While
Laço do tipo For

O laço do tipo While (enquanto), irá executar uma operação enquanto a análise de uma afirmação (proposição) for verdadeira; já o laço do tipo for (para), de acordo com a documentação oficial, irá executar uma iteração independente de uma instrução aritmética, mas baseada na quantidade de dados disponíveis para exibição:

A instrução for em Python difere um pouco do que você pode estar acostumado em C ou Pascal. Em vez de sempre iterar sobre uma progressão aritmética de números (como em Pascal), ou dar ao usuário a capacidade de definir tanto a etapa de iteração quanto a condição de parada (como C), a instrução for do Python itera sobre os itens de qualquer sequência (uma lista ou uma string), na ordem em que aparecem na sequência. (Python.org)

---

### LAÇO WHILE

while [V] esse trecho que estiver aqui for verdadeiro, ele irá executará
o que está aqui.

O nome laço de repetição também é chamado de loop, porque ele faz 1 volta, 2 , 50, 90, ... enquanto a afirmação for verdadeira.

while[existir paçoca]:
exiba

AINDA TEM PAÇOCA NO BANCO DE DADOS PARA MOSTRAR?

SE SIM, ELE EXIBE NOVAMENTE ATÉ O MOMENTO QUE O ROBOZINHO DO GOOGLE/ALGORITMO IRÁ CHEGAR NO BANCO DE DADOS DO GOOGLE MESMO E PERGUNTARÁ SE AINDA TEM PAÇOCA NO BANCO DE DADOS PARA EXIBIR, SE NÃO TEM, QUANDO A PROPOSIÇÃO/AFIRMAÇÃO SE TORNAR FALSA, ELE DEIXA DE EXECUTAR O QUE ESTÁ DENTRO DO LAÇO DE REPETIÇÃO.

TANTO O LAÇO WHILE, QUANTO O LAÇO FOR SEGUEM A MESMA PREMISSA, DE VERIFICAR SE ALGO AINDA É VERDADEIRO E CONTINUAR EXECUTADO UMA AÇÃO ENQUANTO ESSE MESMO ALGO CONTNUAR SENDO VERDADEIRO.

---

### CONHECENDO OS LAÇOS BÁSICOS

LAÇO WHILE

Variável de controle: É uma variável que irá contar a quantidade de voltas que meu laço irá dar.

Ela que é testada para ver se meu laço para ou continua rodando.

a = 1

while a < 10
    print("Teste")

Executando o teste acima irá gerar um loop infinito pois o 1 é sempre menor do que 10 e você deixando esse algortimo rodar por cerca de 10 segundos no seu computador, já é o suficiente para que você trave a sua máquina, pois sua máquinairá requerer muito processamento, mais do que o seu processador é capaz de ceder.

E O QUE É PRECISO PARA QUE O SEU COMPUTADOR NÃO TRAVE?

PRECISAMOS USAR A NOSSA VARIÁVEL DE CONTROLE MUDANDO O VALOR DELA, IMPRIMINDO A PALAVRA TESTE E APÓS A IMPRESSÃO, IREMOS ALTERAR O VALOR DO A, FALANDO QUE O VALOR DO A RECEBE O PRÓPRIO A + 1.

a = 1

while a < 10
    print("Teste")
    a = a + 1

NA PRIMEIRA VOLTA O VALOR DO A VALE 1, ENTÃO 1 É MAIOR DO QUE 10? SIM, ENTÃO ELE IMPRIME A PALAVRA TESTE E RETOMA LÁ PARA CIMA, SÓ QUE ANTES DE ELE RETOMAR LÁ PARA CIMA TEM MAIS UMA LINHA, E ELE PEGOU O A E FALOU, MEU A VAI VALER A + 1, ENTÃO MEU A IRÁ VALER 2.

ENTÃO NA PRÓXIMA VOLTA A PERGUNTA QUE SERÁ FEITA É A SEGUINTE: 2 É MENOR DO QUE 10? SE SIM, ELE IMPRIME, INCREMENTA O A QUE PASSARÁ A VALER 3 E ASSIM SUCESSIVAMENTE ATÉ CHEGAR NO 9, PERGUNTARÁ SE O 9 É MENOR DO QUE 10 E SIM, IRÁ DAR A ÚLTIMA VOLTA E PERGUNTAR O 10 É MENOR DO QUE O 10? NÃO, ENTÃO NESSE MOMENTO A PROPOSIÇÃO SE TORNARÁ FALSA E ENCERRARÁ A EXECUÇÃO.

---

### LAÇO FOR                                 
