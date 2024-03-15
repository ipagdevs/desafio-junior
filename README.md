# Desafio iPag - Desenvolvedor(a) Júnior

## Introdução

- Dentro de cada diretório denominado `challenge_n`, há um arquivo `README.md` com indicações de como executar cada aplicação separadamente;
- Todos os desafios foram feitos utilizando JavaScript, mais especificamente Node.js na `versão 20.11.1`;
- Todos os desafios possuem seus testes de unidade implementados, com instruções de execução nos README.md de cada diretório;
- Os desafios foram construídos no Linux Ubuntu `jammy 22.04.4 LTS`, por isso a utilização de conteinerização Docker;
- Neste README.md principal, você conseguirá executar as aplicações através dos scripts abaixo e também poderá executar todos os testes de uma vez;
- Qualquer dúvida acerca do projeto, entrar em contato com: `viniciussouzav@gmail.com`;

### Como Executar com Docker 🐳

> **⚠️ Atenção:** _É necessário ter o Docker e o docker-compose instalados em sua máquina!_

- Suba o contêiner Docker utilizando o comando abaixo:

```bash
docker-compose up -d
```

- Após finalizar a execução, será gerado um container chamado `node-app`, conforme mostrado na figura abaixo:

![imagem de execução do container](/img/imgDocker.png)

- Entre dentro do container executando o comando abaixo:

```bash
docker exec -it node-app bash
```

Após esses passos, siga as instruções conforme descritas nos demais README.md...

### Executando Aplicações a partir da Raiz 🌿

- Com o Node.js ou Docker devidamente instalados em sua máquina, instale as dependências do projeto executando o comando abaixo:

```bash
npm i
```

- Para executar todos os testes unitários, utilize:

```bash
npm test
```

- Para executar as aplicações a partir da raiz execute o comando abaixo, onde `N` é o número do `challenge`:

```bash
npm run challengeN
```