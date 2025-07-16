# Projeto Final: Website do Curso de Sistemas para Internet 🚀

Este repositório contém o projeto final da disciplina de **Frameworks Front-End** do curso de **Tecnologia em Sistemas para Internet** do IFMT Cuiabá - Cel. Octayde Jorge da Silva, referente ao 2º Semestre de 2025.

O objetivo do projeto é desenvolver um website de múltiplas páginas para apresentar informações relevantes sobre a instituição e o curso, além de demonstrar o uso de frameworks Front-End como Bootstrap 4 e jQuery.

-----

## 🎯 Objetivo da Atividade

Criar um site que atenda aos seguintes requisitos:

  * Apresentar informações referentes ao curso.
  * Conter ao menos 3 componentes/recursos/funções de Bootstrap e 3 de jQuery em todo o site.
  * Possuir ao menos 3 páginas principais:
      * Uma página com informações gerais do Campus Cuiabá - Octayde Jorge da Silva (`index.html`).
      * Uma página com informações gerais do curso de Sistemas para Internet (`sistemas.html`).
      * Uma página com informações e exemplos sobre Frameworks Front-End (`tutorial.html`), funcionando como um tutorial com exemplos de código e explicações sobre ao menos 2 componentes/recursos/funções de Bootstrap e 2 de jQuery.

-----

## ✨ Funcionalidades e Páginas

O site é dividido em três páginas principais, acessíveis via barra de navegação:

### 🏠 Página Inicial (`index.html`)

Esta página serve como a porta de entrada para o site, apresentando uma visão geral do IFMT Cuiabá - Cel. Octayde Jorge da Silva.

  * **Boas-vindas:** Título convidativo "Seja Bem Vindo ao IFMT".
  * **Carrossel de Imagens:** Exibe uma sequência de fotos do campus e suas instalações, utilizando o componente Carousel do Bootstrap 4 para uma apresentação visual dinâmica. As imagens alternam automaticamente e possuem controles de navegação.
  * **História do IFMT:** Um texto detalhado sobre a trajetória histórica do Instituto Federal de Mato Grosso.
  * **Linha do Tempo Interativa:** Um botão "Saiba mais" que expande/recolhe uma imagem da linha do tempo do IFMT, utilizando a funcionalidade de Collapse do Bootstrap.

### 💻 Sistemas para Internet (`sistemas.html`)

Dedicada ao curso de Tecnologia em Sistemas para Internet.

  * **Título:** "Tecnologia em Sistemas para Internet - Feito sob medida para você".
  * **Carrossel de Imagens:** Apresenta imagens relacionadas ao curso e salas de aula.
  * **História do Curso:** Detalhes sobre a origem e evolução do curso de Tecnologia em Sistemas para Internet no IFMT, incluindo suas reformulações e a implementação da curricularização da extensão, com informações do PPC (Projeto Pedagógico de Curso).
  * **Grade Curricular Atual:** Uma seção interativa que permite visualizar a estrutura curricular do curso, dividida por semestres e disciplinas eletivas. Utiliza o componente Accordion (colapsável) do Bootstrap para organizar as informações de forma clara e acessível.

### 📚 Tutorial jQuery e Bootstrap 4 (`tutorial.html`)

Esta página funciona como um guia prático para entender e implementar recursos de Bootstrap e jQuery.

  * **Introdução:** Explica a importância do Bootstrap e jQuery no desenvolvimento web.
  * **Componentes Bootstrap 4:**
      * **Sistema de Grade (Grid System):** Explicação sobre como o sistema de colunas do Bootstrap ajuda a criar layouts responsivos em diferentes tamanhos de tela, com um exemplo prático de três colunas de largura igual.
      * **Cards:** Demonstração da estrutura dos Cards do Bootstrap (substitutos dos antigos panels, wells e thumbnails), com um exemplo de card básico contendo cabeçalho, corpo e rodapé.
  * **Funções jQuery:**
      * **Método `toggle()`:** Explica como usar este método para alternar a visibilidade de elementos HTML com animações, acompanhado de um botão interativo.
      * **Método `css()`:** Detalha como manipular as propriedades CSS de elementos HTML dinamicamente, com um exemplo que altera a cor de fundo e o tamanho da fonte de parágrafos.
      * **Método `animate()`:** Explica como usar este método para criar animações personalizadas de propriedades CSS, como mover um elemento ou alterar seu tamanho e opacidade ao longo do tempo.

-----

## 📂 Estrutura do Projeto

```
apresentacaoframeworkjquery.github.io/  (raiz do seu repositório)
├── index.html
├── sistemas.html
├── tutorial.html
├── css/
│   └── formatacao.css
└── imagens/
    ├── logo-ifmt.png
    ├── ifmt1.jpg
    ├── ifmt2.jpg
    ├── ifmt3.jpg
    ├── ifmt4.jpg
    ├── biblioteca.bmp
    ├── sistemas-imagem.jpeg
    ├── sistemas-imagem3.jpg
    └── ifmt-linha-do-tempo.jpg

-----

## 🔗 GitHub Pages


[Acesse o tutorial jQuery e Bootstrap 4](https://nagafe.github.io/apresentacaoframeworkjquery.github.io/tutorial.html){:target="_blank"}



## 🛠️ Tecnologias Utilizadas

  * **HTML5:** Estrutura básica das páginas.
  * **CSS3:** Estilização personalizada (`css/formatacao.css`).
  * **Bootstrap 4.3.1:** Framework CSS para design responsivo e componentes pré-construídos.
      * CDN utilizado: `https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css`
  * **jQuery 3.4.1:** Biblioteca JavaScript para manipulação DOM, eventos e efeitos.
      * CDN utilizado: `https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js`
  * **Popper.js 1.14.7:** Biblioteca auxiliar necessária para alguns componentes do Bootstrap (como tooltips e popovers), carregada via CDN.
      * CDN utilizado: `https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js`

-----

## 📧 Contato

  * **Aluno:** Nagafe Martins
  * **Professor da Disciplina:** rafael.rocha@ifmt.edu.br

-----
