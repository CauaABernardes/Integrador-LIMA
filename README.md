# Star Tralhas – Projeto Senai Commerce  

## 1. DESCRIÇÃO DO PÚBLICO ALVO E DO SITE  

Star Tralhas é um site que oferece tudo o que um fã do universo Star Wars precisa; desde action figures que levam para o ambiente do cliente um pedaço da sua franquia favorita, até roupas que demonstram o amor pela saga, além de jogos e diversos outros produtos temáticos.

O objetivo é criar um ambiente imersivo, divertido e visualmente atraente para todos os tipos de fãs, desde colecionadores hardcore até aqueles que apenas desejam adquirir produtos temáticos da franquia.

-------------------------------------------------------------

## 2. DESCRIÇÃO DAS FUNCIONALIDADES BÁSICAS

Como funcionalidades básicas no site há:

- Opção de selecionar a quantidade de um produto baseado no estoque.
- Visualização completa do produto, incluindo nome, imagem, descrição e preço.
- Produtos divididos em quatro categorias diferentes, facilitando a navegação.
- Sistema de cadastro e login de usuários.
- Carrinho de compras que armazena os itens selecionados.
- Check-out exibindo todos os produtos, quantidades e valores finais.
- Área de dashboard exclusiva para administradores, exibindo informações de produtos cadastrados e itens mais vendidos.

-------------------------------------------------------------

## 3. IDENTIDADE DO PROJETO E SUAS JUSTIFICATIVAS

A identidade visual do Star Tralhas foi criada para transmitir a sensação de estar imerso no universo Star Wars.

As cores escolhidas — azul-escuro, preto e amarelo — fazem referência direta à estética da saga, criando uma atmosfera familiar e temática para os fãs.

O nome “Star Tralhas” surge da junção de:

- “Star”, referência direta a Star Wars  
- “Tralhas”, simbolizando a variedade de itens e produtos oferecidos no site  

A proposta é unir diversão, imersão e fácil navegação em uma loja virtual completa.

-------------------------------------------------------------

## 4. REQUISITOS DO PROJETO SENAI COMMERCE

O projeto deve seguir as regras apresentadas no desafio:

- Loja virtual com aparência atrativa e alinhada a padrões de UI/UX.
- Explorar conceitos de cores, fontes e layouts pensando no usuário.
- Ter no mínimo 20 produtos cadastrados.
- Páginas obrigatórias:
  - Home Page com banner, cabeçalho, rodapé e navegação.
  - Página de produtos para exibir categorias ou todos os produtos.
  - Página individual do produto com imagem, descrição, preço e quantidade.
  - Carrinho de compras com itens selecionados.
  - Check-out com valores totais.
  - Login e cadastro de usuário.
  - Página “Sobre Nós”.
  - Página de atendimento.
  - Área administrativa com visualização de produtos e dashboards.

-------------------------------------------------------------

## 5. OBJETIVO DO SITE

O Star Tralhas tem como propósito entregar uma experiência simples e completa, oferecendo:

- Facilidade de navegação
- Visual imersivo do universo Star Wars
- Informações claras dos produtos
- Ambiente confiável para compra
- Área administrativa prática para gestão da loja

-------------------------------------------------------------


## 6. Estrutura do Projeto

```
program
├── admPage
│   ├── index.html
│   └── style.css
│
├── generalProducts
│   ├── index.html
│   ├── style.css
│   └── products
│       ├── actionsFigures
│       │   ├── index.html  <- index da categoria
│       │   ├── product1
│       │   │   └── index.html
│       │   ├── product2
│       │   │   └── index.html
│       │   ├── product3
│       │   │   └── index.html
│       │   ├── product4
│       │   │   └── index.html
│       │   ├── product5
│       │   │   └── index.html
│       │   ├── extra_prd1
│       │   │   └── index.html
│       │   ├── extra_prd2
│       │   │   └── index.html
│       │   └── extra_prd3
│           └── index.html
│
│       ├── costumes
│       │   ├── index.html     <- index da categoria
│       │   ├── product6
│       │   │   └── index.html
│       │   ├── product7
│       │   │   └── index.html
│       │   ├── product8
│       │   │   └── index.html
│       │   ├── product9
│       │   │   └── index.html
│       │   ├── product10
│       │   │   └── index.html
│       │   ├── extra_prd4
│       │   │   └── index.html
│       │   ├── extra_prd5
│       │   │   └── index.html
│       │   └── extra_prd6
│           └── index.html
│
│       ├── games
│       │   ├── index.html     <- index da categoria
│       │   ├── product11
│       │   │   └── index.html
│       │   ├── product12
│       │   │   └── index.html
│       │   ├── product13
│       │   │   └── index.html
│       │   ├── product14
│       │   │   └── index.html
│       │   ├── product15
│       │   │   └── index.html
│       │   ├── extra_prd7
│       │   │   └── index.html
│       
│       └── others
│           ├── index.html     <- index da categoria
│           ├── product16
│           │   └── index.html
│           ├── product17
│           │   └── index.html
│           ├── product18
│           │   └── index.html
│           ├── product19
│           │   └── index.html
│           ├── product20
│           │   └── index.html
│           └── extra_prd8
│               └── index.html
│
├── home
│   ├── index.html
│   └── style.css
│
├── login
│   ├── index.html
│   └── style.css
│
├── register
│   ├── index.html
│   └── style.css
│
├── shoppingCart
│   ├── index.html
│   └── style.css
│
├── src
│   └── images
│       ├── actionsFigures
│       ├── costumes
│       ├── games
│       ├── iconsAndCards
│       └── others
│
└── styles
    ├── global.css
    ├── styleCategories.css
    └── styleProducts.css
```
