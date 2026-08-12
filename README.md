# Spotify — Imersão Front-End (Alura)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

Interface inspirada no Spotify, desenvolvida durante a **Imersão Front-End da Alura** (Aula 01: revisão de HTML, CSS e JS na prática).

![Screenshot da interface](screenshot.png)

## Sobre

Réplica da tela inicial do Spotify — sidebar de navegação, área principal com listagem de artistas e busca — construída com **HTML, CSS e JavaScript puros**, sem frameworks. Os dados dos artistas vêm de um arquivo JSON local (`api-artists/artists.json`), simulando uma API.

## Funcionalidades

- Layout fiel à interface do Spotify (sidebar + conteúdo principal)
- Listagem de artistas carregada dinamicamente via `fetch` do JSON local
- Busca de artistas por nome
- Ícones via Font Awesome

## Estrutura

```
index.html            Estrutura da página
script.js               Carregamento e renderização dos artistas
search.js                Lógica de busca
api-artists/
  └── artists.json       Dados mockados dos artistas (simula uma API)
src/
  ├── assets/            Ícones e imagens
  └── styles/             CSS (reset, variáveis, sidebar/footer, conteúdo, responsivo)
```

## Como rodar

Não há build nem dependências — basta abrir `index.html` no navegador, ou servir a pasta com um servidor estático simples:

```bash
python -m http.server 8000
# abra http://localhost:8000
```

## Créditos

Projeto desenvolvido a partir da **Imersão Front-End** da [Alura](https://www.alura.com.br/).

## Autor

**Elton Barbosa**

- Portfólio: [eltonbarbosaa.github.io](https://eltonbarbosaa.github.io)
- GitHub: [@eltonbarbosaa](https://github.com/eltonbarbosaa)
