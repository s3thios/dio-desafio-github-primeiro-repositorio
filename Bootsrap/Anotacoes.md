````markdown
# 💀🔥 Bootstrap Cheat Sheet MALDITO, COMPLETO E INSANO

> **Bootstrap** é o framework CSS mais usado no mundo.  
> Criado pelo Twitter, ele **acelera o desenvolvimento front-end** com classes já prontas, responsividade nativa e integração com JS.  
> Aqui está um guia violento, direto ao ponto — **do básico ao cabuloso.**

---

## 📦 Instalação

### CDN (modo turbo):
```html
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
````

### NPM:

```bash
npm install bootstrap
```Windows
Só baixar

---

## 🔰 Estrutura Básica

```html
<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <meta charset="UTF-8" />
    <title>Bootstrap Maldito</title>
    <link href="bootstrap.min.css" rel="stylesheet" />
  </head>
  <body>
    <h1 class="text-center text-danger">Vai na fé, guerreiro do front!</h1>
    <script src="bootstrap.bundle.min.js"></script>
  </body>
</html>
```

---

## ⚙️ Classes de Utilidade Rápida

| Tipo         | Exemplo                         |
| ------------ | ------------------------------- |
| Margem       | `m-3`, `mt-2`, `mx-auto`        |
| Padding      | `p-4`, `pb-1`, `px-5`           |
| Texto        | `text-center`, `text-danger`    |
| Background   | `bg-dark`, `bg-success`         |
| Display      | `d-flex`, `d-none`              |
| Alinhamento  | `align-items-center`            |
| Espaçamento  | `gap-3`, `g-5`                  |
| Bordas       | `border`, `rounded`, `border-0` |
| Visibilidade | `invisible`, `visible`          |

---

## 🎨 Cores

| Tipo   | Exemplo                        |
| ------ | ------------------------------ |
| Texto  | `text-primary`, `text-warning` |
| Fundo  | `bg-light`, `bg-danger`        |
| Bordas | `border-success`               |

---

## 📐 Sistema de Grid (12 colunas)

```html
<div class="container">
  <div class="row">
    <div class="col-md-6">50%</div>
    <div class="col-md-6">50%</div>
  </div>
</div>
```

### Comportamento responsivo:

| Classe     | Significado   |
| ---------- | ------------- |
| `col-`     | Extra pequeno |
| `col-sm-`  | ≥576px        |
| `col-md-`  | ≥768px        |
| `col-lg-`  | ≥992px        |
| `col-xl-`  | ≥1200px       |
| `col-xxl-` | ≥1400px       |

---

## 📦 Componentes Comuns

### 🔘 Botões

```html
<button class="btn btn-primary">Principal</button>
<button class="btn btn-outline-danger">Puro Ódio</button>
```

### 🎛 Cards

```html
<div class="card" style="width: 18rem;">
  <img src="img.jpg" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">Título Maldito</h5>
    <p class="card-text">Texto sujo e funcional.</p>
    <a href="#" class="btn btn-dark">Vai</a>
  </div>
</div>
```

### 🔥 Alertas

```html
<div class="alert alert-warning" role="alert">
  Isso é um aviso, animal.
</div>
```

### 🧭 Navbar

```html
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">NomeDoSite</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
            data-bs-target="#navbarNav">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item"><a class="nav-link active" href="#">Home</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Sobre</a></li>
      </ul>
    </div>
  </div>
</nav>
```

---

## 🧩 JS Integrado (sem depender de jQuery)

### Modal

```html
<button class="btn btn-danger" data-bs-toggle="modal" data-bs-target="#meuModal">
  Abrir o Caos
</button>

<div class="modal fade" id="meuModal" tabindex="-1">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title">Modal do Apocalipse</h5>
        <button type="button" class="btn-close" data-bs-dismiss="modal"></button>
      </div>
      <div class="modal-body">Tá preparado?</div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Fechar</button>
      </div>
    </div>
  </div>
</div>
```

---

## 📱 Breakpoints (Responsivo)

| Breakpoint | Classe     | Largura mínima |
| ---------- | ---------- | -------------- |
| XS         | `col-`     | 0px            |
| SM         | `col-sm-`  | 576px          |
| MD         | `col-md-`  | 768px          |
| LG         | `col-lg-`  | 992px          |
| XL         | `col-xl-`  | 1200px         |
| XXL        | `col-xxl-` | 1400px         |

---

## ✨ Avançado (Somente pros que aguentam)

* `order-*`: controla ordem de colunas
* `flex-grow-1`: crescimento flexível
* `ratio`: vídeos responsivos (`ratio ratio-16x9`)
* `visually-hidden`: para acessibilidade
* `stretched-link`: faz um `<a>` ocupar toda a área do card
* `accordion`, `collapse`, `carousel`: componentes interativos prontos
* `tooltip` e `popover`: com JS ativado via `data-bs-toggle`

---

## 📚 Fontes & Referências

* [Bootstrap 5 Docs](https://getbootstrap.com/docs/5.3/getting-started/introduction/)
* [Bootstrap Cheat Sheet (themaldito.com)](https://bootstrap-cheatsheet.themaldito.com/)
* [Bootstrap Build Tools (Sass, JS)](https://getbootstrap.com/docs/5.3/customize/overview/)
* [Bootstrap Playground](https://play.bootstrap.dev/)

---

> **Bootstrap é trapaça visual de gente esperta. Quem sabe usar, domina o front com meia dúzia de classes e um café forte.**

```
```

