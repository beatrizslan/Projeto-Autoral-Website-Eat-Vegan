# Autoral - Desenvolvimento do Projeto Website Eat Vegan

Desenvolvimento próprio do design e codificação do projeto website [Eat Vegan](https://beatrizslan.github.io/Projeto-Autoral-Website-Eat-Vegan/).

## Indíce

**Visão Geral**
>[Desafio](#desafio) |
>[Screenshot](#screenshot) |
>[Links](#links)


**Meu Processo**
>[Construído com](#construído-com) | 
>[O que eu aprendi](#o-que-eu-aprendi) | 
>[Recursos úteis](#recursos-úteis)

**Considerações Finais** 
>[Autor](#autor)

## Visão Geral

### Desafio

O desafio foi construir este projeto por inteiro, incluindo o design e layout. Os usuários devem ser capazes de:

- Vizualizar o layout ideal tanto para dispositivos mobiles quanto para desktops;
- Vizualizar os estados de foco para elementos interativos. 

### Screenshot

![20220704_23033994883](https://user-images.githubusercontent.com/105252003/178909682-768ecbb8-3d7f-4f15-82d1-cbec69f4e122.jpg)

### Links

- URL da solução: [Index](https://github.com/beatrizslan/Projeto-Website-Vegan/blob/main/docs/index.html)
- URL do site: [Site](https://beatrizslan.github.io/Projeto-Autoral-Website-Eat-Vegan/)

## Meu processo

### Construído com

- HTML5 com tags semânticas;
- Propriedades personalizadas de CSS;
- Iframes;
- Flexbox;
- Media-queries.

### O que eu aprendi

- Incorporar iframes no HTML5;
- Linkar fontes externas;
- Utilizar variáveis no CSS;
- Trabalhar com o flexbox;
- Desenvolver uma página responsiva.

```HTML
 <iframe class="secundario__mapa" src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d14629.320005162424!2d-46.6926684!3d-23.5565886!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0xe0954961055dccab!2sL&#39;aper%C3%B4%20Bar%20%26%20Bistrot!5e0!3m2!1spt-BR!2sbr!
4v1653592709837!5m2!1spt-BR!2sbr" width="100%" height="250" style="border:0;" allowfullscreen="" loading="lazy" 
referrerpolicy="no-referrer-when-downgrade"></iframe>
```

```CSS
:root {
  --cor-de-fundo: #EDEEF3;
}

body {
  background-color: var(--cor-de-fundo);
}

.principal__descricao {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}
  
@media screen and (min-width: 1024px) {}
```

### Recursos úteis

- [Guia Completo do Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - Este é um artigo incrível que me ajudou a entender melhor de como funciona o Flexbox e quais são suas propriedades. 
- [Media Queries](https://css-tricks.com/snippets/css/media-queries-for-standard-devices/) - Este é um outro artigo do mesmo autor que também foi muito importante para eu ter uma melhor noção sobre as dimensões de telas dos dispositivos móveis.
  

## Considerações Finais

### Autor

- Website - [Beatriz Slan](https://beatrizslan.github.io/Projeto-Autoral-Website-Eat-Vegan/)
- Linkedin - [in/beatriz-slan](https://www.linkedin.com/in/beatriz-slan-2324a4173/)
