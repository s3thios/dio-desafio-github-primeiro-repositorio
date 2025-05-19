````markdown
# 🎨🔥 CSS Cheat Sheet MALDITAMENTE COMPLETO

> **CSS (Cascading Style Sheets)** é o que transforma um HTML sem graça em algo digno de aplausos visuais.  
> Aqui vai um resumão insano, cobrindo de **conceitos básicos até dark magic** com um toque sujo e funcional.

---

## 📜 Breve História & Versões

| Versão | Lançamento | Destaques Principais |
|--------|------------|----------------------|
| **CSS1** | 1996 | Cores, fontes, margens, bordas |
| **CSS2** | 1998 | Layouts, pseudo-classes, impressão |
| **CSS3** | 2011+  | Transições, animações, flexbox, grid, media queries |

> ⚠️ Hoje usamos **CSS3 modular**, ou seja: recursos são atualizados por partes.

---

## 🧱 Estrutura Básica

```css
seletor {
  propriedade: valor;
}
````

Exemplo:

```css
body {
  background-color: #111;
  color: #eee;
}
```

---

## 🔎 Seletores

| Tipo            | Exemplo              | Explicação                             |
| --------------- | -------------------- | -------------------------------------- |
| Universal       | `*`                  | Seleciona tudo                         |
| Elemento        | `p`, `h1`, `div`     | Seleciona por tag                      |
| Classe          | `.btn`               | Seleciona elementos com `class="btn"`  |
| ID              | `#menu`              | Seleciona elemento com `id="menu"`     |
| Filho direto    | `div > p`            | Apenas `p` diretamente dentro de `div` |
| Descendente     | `section p`          | Todos os `p` dentro de `section`       |
| Irmão adjacente | `h1 + p`             | `p` logo após `h1`                     |
| Atributo        | `input[type="text"]` | Input tipo texto                       |
| Pseudo-classe   | `a:hover`            | Quando o mouse passa                   |
| Pseudo-elemento | `p::first-line`      | Primeira linha de um parágrafo         |

---

## 🎨 Cores

| Tipo        | Exemplo                |
| ----------- | ---------------------- |
| Nome        | `red`, `blue`, `black` |
| Hexadecimal | `#FF5733`, `#000000`   |
| RGB         | `rgb(255, 0, 0)`       |
| RGBA        | `rgba(0,0,0,0.5)`      |
| HSL         | `hsl(0, 100%, 50%)`    |

---

## 📐 Box Model (Modelo de Caixa)

```text
[ margin ]
  [ border ]
    [ padding ]
      [ conteúdo ]
```

```css
box-sizing: border-box; /* Inclui padding e border no total da caixa */
```

| Propriedade       | Exemplo                  |
| ----------------- | ------------------------ |
| `margin`          | `margin: 10px`           |
| `padding`         | `padding: 20px`          |
| `border`          | `border: 1px solid #000` |
| `width`, `height` | `width: 100%`            |

---

## 🔲 Display & Position

### 🧱 Display

| Valor          | Descrição                       |
| -------------- | ------------------------------- |
| `block`        | Ocupa linha toda                |
| `inline`       | Ao lado de outros elementos     |
| `inline-block` | Inline mas permite tamanho fixo |
| `none`         | Esconde o elemento              |
| `flex`         | Flex container                  |
| `grid`         | Grid container                  |

### 📌 Position

| Valor      | Efeito                                       |
| ---------- | -------------------------------------------- |
| `static`   | Padrão                                       |
| `relative` | Posicionado relativo a si mesmo              |
| `absolute` | Posicionado em relação ao pai com `relative` |
| `fixed`    | Fixa na tela                                 |
| `sticky`   | Fixa ao rolar, conforme o topo               |

---

## 🧭 Flexbox

```css
display: flex;
justify-content: center;
align-items: center;
flex-direction: row;
```

| Propriedade       | Valor                              |
| ----------------- | ---------------------------------- |
| `flex-direction`  | `row`, `column`                    |
| `justify-content` | `start`, `center`, `space-between` |
| `align-items`     | `stretch`, `center`, `flex-end`    |
| `gap`             | Espaço entre os filhos             |

---

## 🧮 Grid Layout

```css
display: grid;
grid-template-columns: repeat(3, 1fr);
grid-gap: 10px;
```

| Propriedade               | Exemplo                       |
| ------------------------- | ----------------------------- |
| `grid-template-columns`   | `1fr 2fr` ou `repeat(3, 1fr)` |
| `grid-template-rows`      | `auto auto`                   |
| `grid-column`, `grid-row` | `1 / 3`                       |

---

## 📱 Media Queries (Responsividade)

```css
@media (max-width: 768px) {
  body {
    background: red;
  }
}
```

---

## 🌈 Estilização Comum

```css
font-family: 'Arial', sans-serif;
font-size: 16px;
line-height: 1.5;
text-align: center;
text-transform: uppercase;
text-decoration: none;
```

```css
background: linear-gradient(to right, #00f, #0ff);
box-shadow: 0 0 10px #000;
border-radius: 8px;
transition: all 0.3s ease;
```

---

## ✨ Animações e Transições

### 🔁 Transições

```css
transition: all 0.3s ease-in-out;
```

### 🔄 Keyframes

```css
@keyframes girar {
  0%   { transform: rotate(0deg); }
  100% { transform: rotate(360deg); }
}

.elemento {
  animation: girar 2s infinite linear;
}
```

---

## 🪛 Outras Propriedades Úteis

| Propriedade  | Função                                     |
| ------------ | ------------------------------------------ |
| `z-index`    | Define ordem na pilha (posição sobreposta) |
| `opacity`    | Transparência                              |
| `overflow`   | Scroll, hidden, auto                       |
| `cursor`     | Tipo de cursor ao passar                   |
| `visibility` | `visible`, `hidden` (ainda ocupa espaço)   |

---

## 📚 Fontes e Referências

* [MDN Web Docs - CSS](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
* [CSS Tricks](https://css-tricks.com/)
* [W3Schools - CSS](https://www.w3schools.com/css/)
* [Guia DevDocs CSS](https://devdocs.io/css/)
* [Flexbox Froggy (jogo)](https://flexboxfroggy.com/)
* [Grid Garden (jogo)](https://cssgridgarden.com/)

---

> **CSS é tipo feitiçaria. Quando você entende, você controla o layout. Quando você não entende, o layout te tortura.**

```
```

