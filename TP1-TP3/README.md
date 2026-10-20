# PresenteFácil (TP1 a TP3)

Este diretório reúne as versões do software PresenteFácil desenvolvidas nos trabalhos de TP1, TP2 e TP3.

## Objetivo

O sistema foi criado para gerenciar:

- usuários
- listas de presentes
- produtos
- relacionamento entre listas e produtos
- busca por palavras-chave e relevância

## Estrutura principal

- `Principal.java`: entrada principal da aplicação
- `CRUDProduto.java`: operações de CRUD de produtos
- `CRUDProdutoListaProduto.java`: gestão da associação entre listas e produtos
- `aeds3/`: estruturas de dados e arquivos indexados
- `model/`: entidades e regras de negócio
- `nanoid/`: geração de identificadores compartilháveis

## Funcionalidades principais

- cadastro e login de usuários
- recuperação de senha
- criação e manipulação de listas
- busca de produtos por nome e GTIN
- relacionamento de produtos com listas
- indexação por hash extensível e árvore B+
- busca por relevância com TF-IDF no TP3

## Execução

```bash
cd TP1-TP3
javac $(find . -name "*.java")
java Principal
```

## Observação

Os TPs 1, 2 e 3 representam o mesmo sistema em evolução, e não devem ser tratados como projetos distintos.
