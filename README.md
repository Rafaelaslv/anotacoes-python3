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

O laço for (para) funciona de maneira similar ao While e contrapõe a forma tradicional de outras linguagens. Enquanto a maioria das outras linguagens requerem um incremento numérico, o laço for em Python apenas requer que haja incidência de dados, testados com uma proposição verdadeira,  a serem trabalhados para continuar em execução.

Um exemplo prático desse tipo de estrutura:

Pressuponha que exista uma lista de nomes escritos dentro de um algoritmo Python. Dentre eles, 10 inicial com a letra M. Utilizando o laço For, é possível requerer que sejam exibidos na tela todos os nomes que iniciem com M a partir dessa lista. O Python por si só, fará a seguinte sequência de ações:

Acessará a lista
Verificará a regra imposta (apenas nomes iniciados com a letra M)
Agrupará os resultados
Exibirá os resultados em tela, conforme descrito no algoritmo
A lógica trabalhada pelo laço for analisará, similar ao While, o seguinte: enquanto existirem dados para serem resgatados, o laço permanecerá em execução.

a = {"Python", "PHP", "JavaScript"}
for b in a:
    print(b)

Outra forma de trabalhar com o laço for é por meio de voltas simples do laço. Pode-se perfeitamente requerer que o laço de repetição simplesmente imprima (ou execute) uma sequência de vezes, como demonstrado na Figura 23 (note que novamente foi utilizado o recurso “end” para determinar que ao final da linha deveria haver um espaço em branco, de forma a concentrar a impressão do conteúdo em apenas uma linha.

a = "Python"
for b in a:
    print(a, end = " ")

---

### LAÇOS AVANÇADOS

O laço for segue a mesma linha de raciocínio do laço while. A diferença é que ele tem algumas subdivisões/subcategorias.

ESTRUTURA MAIS BÁSICA DO LAÇO FOR:

for a in 
PARA UMA VARIÁVEL QUALQUER, QUE NO CASO ESTOU CHAMANDO DE a, que estejam dentros de algumas regras.

PEDINDO PARA O LAÇO RODAR 5 VEZES CONSECUTIVAS:

for a in range(5):
    print("marcio")

VETOR É A POSSIBLIDADE DE ARMAZENARMOS VÁRIOS VALORES EM APENAS UM LUGAR.

---

### LAÇOS E VARIÁVEIS

Da mesma maneira que lidamos com dados fixos ou baseados em listas de valores, é possível utilizar os laços de repetição para obter informações de forma automática baseada em variáveis constantes dentro da própria estrutura do laço.

Uma forma prática de se fazer isso é utilizando a própria variável de controle que, via de regra, alterna seu valor a cada volta do laço. Este exemplo foi utilizado na Figura 20, em que a variável “a” era, ao mesmo tempo, a controladora das voltas do laço e o valor impresso em tela.

Esta forma de se trabalhar é bastante recorrente em nosso dia a dia, como por exemplo, em paginações de sites, como demonstrado na Figura 24.

---

### LAÇOS E INPUT/OUTPUT DE DADOS

Os laços de repetição não se limitam a apenas imprimir valores em tela. Eles podem ser utilizados, como você já pôde perceber, para variadas ações dentro de um algoritmo. Uma prática interessante, é dinamizar o processo de inserção de valores sequenciais, digitados pelo usuário. Considere a seguinte situação:

Um professor precisa digitar o nome e a nota de 3 alunos e esses dados precisam ser impressos em tela. O algoritmo poderia ser feito da seguinte forma (note que não foi inserido o casting para inteiro ou número decimal, pois como o objetivo não é fazer cálculos, não há a necessidade que o valor inserido seja considerado número ou caractere):

nome1 = input("Digite o nome do aluno: ")
nota1 = input("Digite a nota do aluno: ")
nome2 = input("Digite o nome do aluno: ")
nota2 = input(Digite a nota do aluno: ")
nome3 = input("Digite o nome do aluno: ")
nota3 = input("Digite a nota do aluno: ")
print(nome1, ": ", nota1)
print(nome2, ": ", nota2)
print(nome3 ": ", nota 3)

O escopo do algoritmo está funcionando perfeitamente e, em tese, não há nada de errado com ele, todavia, o algoritmo está travado e não-escalável. Isso significa que se um novo aluno for inserido na turma, duas novas variáveis precisarão ser criadas: “nome4” e “nota4”. Em programação, a falta de escalabilidade deve ser sumariamente eliminada.

Mas como conseguir dinamizar essas operações? Simples: com laço de repetição.

Observe que ocorre uma repetição do que é requerido do usuário: sempre é solicitada a digitação de um nome e uma nota, logo, uma ação que se repete, ainda que com pequenas alterações, pode ser implementada com laço de repetição, veja:

a = 1

while a <= 3:
    nome = input("Digite o nome do aluno: ")
    nota = input("Digite a nota do aluno: ")
    print(nome, ": ", nota)
    a = a + 1

    Além de o código ficar menor, ser escalável, ele é, em uma visão computacional, mais “elegante”, uma vez que utiliza recursos mais robustos e menos manuais visando o aproveitamento de tempo e reaproveitamento de código. 
    
---

### SIMULANDO LAÇOS EM CASOS REAIS

Na prática, laços de repetição podem ser utilizados em vários cenários, mas listei aqui algumas situações triviais que às vezes você nem perceba:

Paginação de resultados de busca
Feed de posts em uma rede social
Lista de e-mails recebidos
Painéis de senha de atendimento automático
Listagem de clientes de uma loja

Observe que até mesmo em situações comuns do dia a dia os laços de repetição estão presentes, realizando seu trabalho de forma oculta e discreta. A partir de agora, sugiro que você passe a focar sua atenção nessas trivialidades do dia a dia, não apenas com os laços de repetição, mas também com condicionais e outros recursos de programação que veremos mais adiante.

Fazer essas verificações irá aprimorar seu raciocínio computacional e fará você ter uma lógica mais refinada. Tente, quando possível, algoritmizar tudo o que vir no seu dia a dia, transformando situações comuns em pequenos trechos de Python, mentalmente. No começo pode parecer difícil mas com o tempo vai se tornando cada vez mais simples e divertido.

---

### Como aplicar na prática o que aprendeu

A ideia de laços de repetição é algo realmente fascinante e você pode explorar esse novo conhecimento de formas diversas. Alguns exemplos práticos foram passados durante a aula mas você pode (e deve) ir além.

Tente analisar no dia a dia os locais onde poderiam existir laços de repetição e aplique o conhecimento na prática para utilizá-los. Como base, darei alguns exemplos que você pode explorar e que, possivelmente você já utiliza diariamente sem saber:

Listagem de produtos de uma loja virtual
Listagem de e-mails recebidos
Lista de contatos no WhatsApp

---

### Tópicos avançados

Os laços de repetição do tipo FOR são extremamente abrangentes e versáteis, possibilitando uma infinidade de usos e aplicações. Uma maneira interessante de você compreender o uso de laços de repetição de uma maneira diferenciada é a seguinte:

Pressuponha que existam alguns registros em um banco de dados e você precise resgatá-los para exibir em tela. Parta do princípio que este é um banco de dados grande e com uma considerável gama de informações, ou seja, você não sabe a quantidade de conteúdo que este banco armazena.

Se você não sabe a quantidade de dados que deverá “puxar” para a tela, como fazer um laço de repetição de forma a definir a quantidade de voltas que ele deverá dar? Simples: com o laço FOR!

O laço for irá armazenar os dados em uma variável (no formato de vetor) e a única coisa que você precisará fazer é pedir ao laço para ler todos os dados armazenados naquela variável/vetor e exibi-los individualmente em tela.

---


Códigos utilizados na disciplina: https://github.com/FaculdadeDescomplica/Python







































