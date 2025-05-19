````markdown
# 🔥📄 HTML Cheat Sheet MALDITAMENTE COMPLETO (da versão 1 até a 5)

> **HTML (HyperText Markup Language)** é a linguagem de marcação que estrutura todo o conteúdo da web.  
> De site de memes até o painel da NASA, tudo começa com HTML.  
> Aqui vai um resumo que vai te transformar de aspirante a deus do front.

---

## 🧱 HTML: Histórico na Marra

| Versão | Lançamento | Destaques Principais |
|--------|------------|----------------------|
| **HTML 1.0** | 1993 | Primeiras tags: `<p>`, `<a>`, `<h1>`, `<ul>`, `<img>` etc. |
| **HTML 2.0** | 1995 | Formularios (`<form>`, `<input>`) e melhorias estruturais |
| **HTML 3.2** | 1997 | Scripts (`<script>`), estilos inline, tabelas |
| **HTML 4.01** | 1999 | Separação entre conteúdo e estilo (introdução ao CSS) |
| **HTML5** | 2014+  | Semântica, APIs, multimídia nativo, mobile-first, etc. |

---

## 🎯 Estrutura Básica (Esqueleto HTML5)

```html
<!DOCTYPE html>
<html lang="pt-BR">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Meu Site</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <h1>Olá, mundo!</h1>
    <script src="script.js"></script>
  </body>
</html>
````

---

## 🧠 Tags Semânticas (HTML5)

| Tag                         | Descrição                          |
| --------------------------- | ---------------------------------- |
| `<header>`                  | Cabeçalho da página ou seção       |
| `<nav>`                     | Área de navegação                  |
| `<main>`                    | Conteúdo principal                 |
| `<section>`                 | Seções temáticas do conteúdo       |
| `<article>`                 | Conteúdo independente (blog, post) |
| `<aside>`                   | Conteúdo lateral (barra lateral)   |
| `<footer>`                  | Rodapé da página                   |
| `<figure>` / `<figcaption>` | Imagens com legendas               |

---

## 📌 Elementos Essenciais

| Elemento           | Função                             | Exemplo                     |
| ------------------ | ---------------------------------- | --------------------------- |
| `<h1>` até `<h6>`  | Títulos de diferentes níveis       | `<h1>Título Principal</h1>` |
| `<p>`              | Parágrafo                          | `<p>Texto aqui</p>`         |
| `<a href="">`      | Link (âncora)                      | `<a href="https://dio.me">` |
| `<img src="">`     | Imagem                             | `<img src="img.jpg" />`     |
| `<ul>`, `<ol>`     | Listas não ordenadas / ordenadas   | `<li>Item</li>`             |
| `<br>`, `<hr>`     | Quebra de linha / linha horizontal | —                           |
| `<strong>`, `<em>` | Destaques (negrito / itálico)      | —                           |

---

## 🧾 Formulários

| Elemento                | Descrição                 |
| ----------------------- | ------------------------- |
| `<form>`                | Formulário completo       |
| `<input>`               | Campo de entrada genérico |
| `type="text"`           | Texto padrão              |
| `type="email"`          | Validação de e-mail       |
| `type="password"`       | Campo de senha            |
| `type="radio"`          | Botão de opção única      |
| `type="checkbox"`       | Caixa de seleção          |
| `<label>`               | Rótulo para input         |
| `<textarea>`            | Caixa de texto maior      |
| `<select>` / `<option>` | Menu suspenso             |
| `<button>`              | Botão de ação             |

---

## 📹 Multimídia Nativa

```html
<video controls>
  <source src="video.mp4" type="video/mp4">
</video>

<audio controls>
  <source src="audio.mp3" type="audio/mpeg">
</audio>
```

---

## 💪 Tags Avançadas / Poderosas

| Tag                       | Função                                 |
| ------------------------- | -------------------------------------- |
| `<meta>`                  | SEO, charset, viewport                 |
| `<link>`                  | Conecta CSS externo                    |
| `<script>`                | Conecta JavaScript                     |
| `<canvas>`                | Gráficos desenhados por script         |
| `<iframe>`                | Embutir conteúdo externo (ex: YouTube) |
| `<template>`              | Conteúdo HTML oculto até ser chamado   |
| `<details>` / `<summary>` | Acordeões / spoilers interativos       |

---

## 🧠 Atributos Importantes

| Atributo          | Aplicação                        | Exemplo                           |
| ----------------- | -------------------------------- | --------------------------------- |
| `id`              | Identificador único              | `<div id="banner">`               |
| `class`           | Agrupar elementos                | `<p class="destaque">`            |
| `style`           | CSS inline (não recomendado)     | `<h1 style="color:red">`          |
| `href`            | Link em `<a>`                    | `<a href="link.html">`            |
| `src`             | Caminho da imagem, vídeo, script | `<img src="logo.png" />`          |
| `alt`             | Texto alternativo para imagem    | `<img src="logo" alt="Logotipo">` |
| `target="_blank"` | Abre link em nova aba            | `<a href="" target="_blank">`     |
| `required`        | Campo obrigatório no formulário  | `<input required>`                |
| `disabled`        | Desativa o campo ou botão        | `<button disabled>`               |

---

## ⚠️ Boas Práticas

* Usar tags **semânticas** sempre que possível.
* Separar **HTML**, **CSS** e **JS** (arquitetura limpa).
* Incluir o `alt` nas imagens.
* Usar `meta viewport` para **responsividade mobile**.
* Validar seu HTML com: [W3C Validator](https://validator.w3.org/).

---

## 📚 Fontes e Referências

* [MDN Web Docs (Mozilla)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
* [HTML5 Rocks (Google)](https://www.html5rocks.com/)
* [w3schools - HTML](https://www.w3schools.com/html/)
* [Guia de Referência HTML (DevDocs)](https://devdocs.io/html/)
* Cursos de **HTML/CSS** da [Digital Innovation One](https://www.dio.me/)

---

> **HTML é a base de tudo. Quem domina HTML, constrói o esqueleto da internet. Quem ignora, tropeça até no próprio portfólio.**

```
```

