# Quest-Avançada Huddle landing-page




## Table of contents

- [Visão Geral](#visão-geral)
  - [Screenshot](#screenshot)
- [Meu processo](#meu-processo)
  - [Como foi feito](#construído-com)
  - [ O que eu aprendi](#o-que-eu-aprendi)
  - [Evolução](#evolução)
  - [Recursos úteis](#recursos-úteis)
- [Autor](#autor)


## Visão geral

### Screenshot

![](/src/design/desktop-design.jpg)


## Meu processo

### Construído com

- HTML5 Semântico
- CSS3 
- Flexbox
- Grid

### O que eu aprendi

Com esse projeto consegui melhorar a criação e uso do Grid juntamente com o Flex e aplicando os dois a um projeto completo;


```css
.container{
    display: grid;
    grid-template-areas:
    "header header header header"
    "esquerdo esquerdo direito direito";
    grid-template-columns: repeat(4, 1fr);
    grid-gap: 10px;
}

.container-esquerdo{
    grid-area: esquerdo;
    display: flex;
    justify-content: center;
    align-items: center;
}
```

### Evolução

Desejo focar mais na área Flex e Grid e na parte de transições do CSS para melhor estilização dos meus projetos, onde tenho certas dificuldades em centralizar os projetos;


### Recursos úteis

- [Resumo](https://angry-helicopter-3a6.notion.site/Resumos-DevQuest-d9c3dc80b08a4037a35ddb6d90355f0c) - Os meus resumos feitos com base no curso DEVQUEST me ajudaram bastante na criação desse projeto;

## Autor

- Github - [Willy-Braga](https://github.com/willy-braga)
- LinkedIn - [Willy Braga](https://www.linkedin.com/in/willy-braga-2861b3270/)
- Intragram - [@braga.wg](https://www.instagram.com/braga.wg/)

## Agradecimentos

Agradeço ao pessoal do curso [DEVQUEST](https://www.linkedin.com/school/devquest-dev-em-dobro/) por me ajudar na solução desse projeto tanto com as aulas do curso quanto com o video reforço sobre o projeto.

