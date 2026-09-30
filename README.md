# ✨ Portal das Estrelas

Uma pequena página de login criada para praticar **HTML e CSS**, explorando posicionamento, estilização, animações e elementos visuais.

O projeto tem uma proposta fofa e delicada, com gradiente em tons de azul e rosa, estrelas animadas e um gatinho como detalhe decorativo. 🐱💖

---

## 🌟 Preview

> Uma tela de login simples com:
>
> * ✨ Estrelas decorativas
> * 🐱 Gatinho animado
> * 💗 Cores em tons pastel
> * 🌸 Título com fonte personalizada
> * 🔐 Campos de usuário e senha
> * 🎀 Botão com efeitos ao passar o mouse e clicar

---

## 🛠️ Tecnologias utilizadas

* **HTML5** — estrutura da página
* **CSS3** — estilização e animações
* **Google Fonts** — fontes `Poppins` e `Lobster`

---

## 📚 O que pratiquei

### HTML

Neste projeto pratiquei:

* Estrutura básica de um documento HTML
* `head` e `body`
* Títulos com `<h1>` e `<h2>`
* Campos de formulário com `<input>`
* Associação entre `<label>` e `<input>` usando `for` e `id`
* Botão com `<button>`
* Imagens com `<img>`
* Uso do atributo `alt`
* Classes com `class`

### CSS

Também explorei diversos conceitos de CSS:

* `display: flex`
* Centralização horizontal e vertical
* `padding` e `margin`
* `border-radius`
* `box-shadow`
* `linear-gradient`
* `position: relative`
* `position: absolute`
* `transform`
* `transition`
* `:hover`
* `:focus`
* `:active`
* `@keyframes`
* Animações com `animation`
* Transparência usando `rgba()`
* Personalização de fontes
* `text-shadow`
* `letter-spacing`

---

## ✨ Animações

Uma das partes que mais explorei nesse exercício foram as animações.

### 🐱 Gatinho

O gatinho utiliza `@keyframes` para criar um pequeno movimento de balanço:

```css
@keyframes balancar {
    0% {
        transform: rotate(-10deg);
    }

    50% {
        transform: rotate(-15deg);
    }

    100% {
        transform: rotate(-10deg);
    }
}
```

### ⭐ Estrela 1

A primeira estrela possui um efeito de flutuação:

```css
@keyframes flutuar {
    from {
        transform: translateY(0px) rotate(10deg);
    }

    to {
        transform: translateY(-10px) rotate(10deg);
    }
}
```

### ⭐ Estrela 2

A segunda estrela possui um efeito de brilho, alterando sua opacidade e tamanho:

```css
@keyframes brilho {
    from {
        opacity: 0.7;
        transform: scale(1) rotate(10deg);
    }

    to {
        opacity: 1;
        transform: scale(1.1) rotate(10deg);
    }
}
```

---

## 🎨 Estilização

O fundo utiliza um gradiente:

```css
background: linear-gradient(to right, #c9d6ff, #fbc2eb);
```

O card central recebeu:

* Fundo branco
* Cantos arredondados
* Sombra
* Borda suave
* Conteúdo centralizado

O botão também possui um gradiente e interações:

```css
button:hover {
    transform: scale(1.03);
}
```

Ao passar o mouse, ele aumenta levemente.

Ao clicar, o botão diminui um pouco:

```css
button:active {
    transform: scale(0.97);
}
```

---

## 🧠 Conceitos que estou aprendendo

Este projeto faz parte dos meus estudos de desenvolvimento web e foi criado para entender **na prática como HTML e CSS trabalham juntos**.

A ideia foi construir a página aos poucos, testando propriedades, alterando valores e observando como cada mudança afeta o resultado final.

> 💡 O objetivo não foi apenas fazer a página funcionar, mas entender o que cada propriedade faz e como combiná-las para criar uma interface.
---
## 💖 Projeto

**Portal das Estrelas**
Um exercício de HTML + CSS feito durante meus estudos de desenvolvimento web. ✨

🐱 🌟 💗
