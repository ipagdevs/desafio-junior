# Desafio iPag - Desenvolvedor(a) Júnior

## Introdução

Bem-vindo(a) ao desafio de programação para desenvolvedores juniores da iPag! Este desafio foi projetado para testar suas habilidades de programação e lógica de programação, bem como sua capacidade de resolver problemas e criar soluções eficientes.

O desafio consiste em uma série de exercícios de programação que abrangem diferentes tópicos e conceitos, como cálculos matemáticos, manipulação de strings, leitura e escrita de arquivos, manipulação de arrays e objetos, requisições HTTP, entre outros.

Você pode escolher entre PHP, Python ou JavaScript para resolver os exercícios.

**Objetivo do Desafio:**

* Demonstrar suas habilidades de programação e lógica de programação.
* Criar soluções eficientes e funcionais para os problemas propostos.
* Avaliar sua criatividade, organização e clareza na resolução dos exercícios.

**Instruções:**

* Leia atentamente a descrição de cada exercício antes de começar a resolvê-lo.
* Escolha entre PHP, Python ou JavaScript para resolver os exercícios, e sinta-se à vontade para utilizar HTML e CSS se necessário.
* Crie um repositório no GitHub para armazenar e compartilhar seu código.
* Crie um arquivo `README.md` na raiz do repositório com as instruções para executar e testar seu código.
* Crie um diretório para cada exercício, com um arquivo `README.md` contendo a descrição do exercício e o código fonte da solução.
* Organize o código fonte e resolva os exercícios de forma clara, eficiente e organizada, com comentários explicativos se necessário.
* Compartilhe seu repositório com a equipe da iPag para revisão e avaliação.
* Esteja preparado(a) para explicar e discutir seu código durante a revisão.
* Divirta-se e desafie-se com os exercícios de programação!
* Boa sorte e bom trabalho!

## Exercícios de Programação

### 1. Calculadora Básica:

* Crie uma calculadora que realize as operações básicas: soma, subtração, multiplicação e divisão.
* Permita a entrada de dois números e a escolha da operação.
* Exiba o resultado da operação na tela.

### 2. Maior e Menor entre Três Números:

* Escreva um programa que peça ao usuário três números.
* Determine o maior e o menor número entre os três e exiba-os na tela.

### 3. Área de Formas Geométricas:

* Crie um programa que seja capaz de calcular a área de formas geométricas.
* O programa deve permitir o cálculo da área de um quadrado, retângulo, triângulo e círculo.
* O usuário deve escolher a forma geométrica e informar os dados necessários para o cálculo da área.

### 4. Jogo da Adivinhação:

* Crie um programa que gere um número aleatório entre 1 e 100.
* O usuário deve tentar adivinhar o número com o mínimo de tentativas possível.
* Dê dicas ao usuário, informando se o seu palpite está "acima", "abaixo" ou se ele adivinhou o número.

### 5. Validador de Senha:

* Escreva um programa que peça ao usuário uma senha.
* A senha deve ter no mínimo 8 caracteres e conter pelo menos uma letra maiúscula, uma letra minúscula e um número.
* Valide a senha e informe ao usuário se ela é válida ou não.

### 6. Lista de Tarefas:

* Crie um programa que permita ao usuário adicionar, remover e visualizar tarefas.
* Cada tarefa deve ter descrição, prioridade e um status (pendente ou concluída).
* O programa deve permitir a navegação, ordenação e edição da lista de tarefas.

### 7. Manipulação e Comunicação de Objetos:

* Crie um programa que conecte controles de marcas diferentes (LG, Samsung, Sony, etc) a uma ou mais TVs.
* O programa deve permitir a seleção de um controle e a comunicação com a TV para ligar e desligar;
* As TVs e controles devem ser representados por objetos, e a comunicação entre eles deve ser feita por métodos.
* O programa deve exibir na tela as ações realizadas e o estado atual da TV.
* Caso o controle selecionado não seja compatível com a TV, o programa deve exibir uma mensagem de erro.

### 8. Estatísticas de Vendas:

* Leia o arquivo em anexo "sales.csv" que contém dados de vendas agrupados por tipo e país.
* Crie um programa que calcule e exiba as seguintes estatísticas:
  * Vendas (total de unidades vendidas, total de receita, custo total, lucro total) por tipo de produto.
  * Vendas por tipo de produto e região.
  * Tipo de produto com maior receita de cada país.

### 9. Simulador de Financiamento:

* Crie um programa que simule o calculo de financiamento de um imóvel ou veículo, baseado na tabela PRICE.
* O programa deve solicitar o valor total do financiamento, a quantidade de parcelas e a taxa nominal de juros anual.
* O programa deve exibir o valor da parcela, o valor total a ser pago, o custo efetivo total do financiamento e a taxa efetiva mensal.
* O programa deve permitir a simulação de diferentes cenários de financiamento.

Para este exercício utilize as seguintes fórmulas:

* **Valor da parcela**: `PMT = PV * (i / (1 - (1 + i)^-n))`, onde `PMT` é o valor da parcela, `PV` é o valor total financiado, `i` é a taxa de juros mensal efetiva e `n` é a quantidade de parcelas.
* **Custo efetivo total**: `CET = (PMT * n) - PV`, onde `CET` é o custo efetivo total, `PMT` é o valor da parcela e `PV` é o valor total financiado.
* **Taxa efetiva mensal**: `im = (1 + i)^(1/12) - 1`, onde `im` é a taxa de juros mensal efetiva e `i` é a taxa de juros nominal anual.

### 10. Manipulação de API:

* Utilizando a API REST do GitHub, desenvolva um script que faça uma requisição para obter os repositórios de um usuário e exiba as informações na tela.
* O usuário deve informar o nome do usuário do GitHub.
* O script deve exibir o nome, descrição, linguagem e quantidade de estrelas de cada repositório.