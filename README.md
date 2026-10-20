# Repositório AEDS3

Este repositório reúne dois projetos distintos desenvolvidos na disciplina de AEDS3, cada um com objetivos e tecnologias diferentes.

## Visão geral

- Projeto principal em Java: PresenteFácil (TP1 a TP3)
- Projeto web independente: CRUD de produtos em memória secundária (TP4)

A organização foi ajustada para refletir essa diferença, evitando misturar um software de console com uma aplicação web.

## Estrutura do repositório

```
.
├── README.md
├── TP1-TP3/
│   ├── Principal.java
│   ├── CRUDProduto.java
│   ├── CRUDProdutoListaProduto.java
│   ├── aeds3/
│   ├── model/
│   └── nanoid/
├── TP4/
│   ├── index.html
│   ├── img/
│   ├── relatorioTP4.pdf
│   └── README.md
├── docs/
│   ├── TP3-video.txt
│   └── TP4-links.txt
└── .git/
```

## 1) PresenteFácil (TP1 ao TP3)

Esse conjunto de entregas representa um mesmo software de gerenciamento de usuários, listas de presentes e produtos.

### Objetivo

- cadastro e autenticação de usuários
- criação e manutenção de listas de presentes
- cadastro de produtos
- busca e relacionamento entre produtos e listas
- uso de estruturas de arquivos indexados, hash extensível e árvore B+

### Arquivos principais

- `TP1-TP3/Principal.java`
- `TP1-TP3/model/`
- `TP1-TP3/aeds3/`
- `TP1-TP3/nanoid/`

### Observação

Os trabalhos TP1, TP2 e TP3 fazem parte do mesmo sistema e devem ser entendidos como uma evolução contínua da mesma aplicação.

## 2) TP4 - CRUD de produtos em memória secundária

O TP4 é um projeto separado, desenvolvido como uma aplicação web estática em HTML, CSS e JavaScript.

### Objetivo

- simular operações de CRUD em arquivo de memória secundária
- explorar registros e campos de produtos em interface visual
- demonstrar a manipulação de dados em uma página interativa

### Arquivos principais

- `TP4/index.html`
- `TP4/img/`
- `TP4/relatorioTP4.pdf`

### Links úteis

- Site de demonstração: consulte o arquivo `docs/TP4-links.txt`
- Vídeo do TP4: consulte o arquivo `docs/TP4-links.txt`
- Vídeo do TP3: consulte o arquivo `docs/TP3-video.txt`

## Equipe

- Fabiano Queiroz Guimarães Almeida
- Mateus Evangelista do Nascimento
- Fernando Theodoro Porto de Paula Dias
- Diogo Patrick Cesário de Oliveira

## Resumo dos entregáveis

### TP1

- CRUD de usuários
- CRUD de listas
- relacionamento entre usuário e lista
- código NanoID para compartilhamento de listas

### TP2

- melhorias no fluxo de usuário logado
- CRUD de produtos
- relacionamento entre listas e produtos
- paginação e navegação de produtos

### TP3

- busca por relevância usando TF-IDF
- índice invertido para busca de termos nos nomes dos produtos
- refinamento da busca por palavras-chave

### TP4

- aplicação web de CRUD de produtos
- simulação de persistência em memória secundária
- interface interativa com visualização dos registros

## Como executar

### Java (TP1-TP3)

No diretório do projeto Java:

```bash
cd TP1-TP3
javac $(find . -name "*.java")
java Principal
```

### Web (TP4)

Abra o arquivo abaixo em um navegador:

```bash
TP4/index.html
```

Se preferir, também é possível hospedar a pasta `TP4` em qualquer servidor estático.
