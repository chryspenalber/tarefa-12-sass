[Versão em Português](#portugues) | [English Version](#english)

---

<a id="portugues"></a>

# 💼 Agência Criativa Web — Refatoração com SASS + BEM  
### Projeto desenvolvido por Chrys Penalber

Este projeto faz parte da **Tarefa 12 do curso de Engenheiro Front-End da EBAC**.

O objetivo principal foi **refatorar o CSS do projeto Agência Criativa Web**, transformando um código CSS tradicional em uma **arquitetura moderna, modular e escalável**, utilizando **SASS (SCSS)** aliado à metodologia **BEM (Block, Element, Modifier)**.

---

## 🔗 Links

* 🔴 [Live Site](https://chryspenalber.github.io/tarefa-12-sass/)
* 💻 [Repositório no GitHub](https://github.com/chryspenalber/tarefa-12-sass)

---

## 🎯 Objetivo do Exercício

✔ Refatorar o CSS existente utilizando **SASS**  
✔ Aplicar **boas práticas de organização e escalabilidade**  
✔ Utilizar **partials**, **variáveis**, **mixins**, **aninhamento** e **operadores**  
✔ Manter a **metodologia BEM** para nomeação das classes  
✔ Gerar um **CSS final compilado** a partir do SCSS  

---

## 🗂️ Estrutura de Pastas

O projeto foi organizado separando claramente os arquivos de desenvolvimento (**SCSS**) do CSS final compilado:

```

📦 projeto
┣ 📂 scss
┃ ┣ _base.scss
┃ ┣ _variaveis.scss
┃ ┣ _mixins.scss
┃ ┣ _layout.scss
┃ ┣ _componentes.scss
┃ ┗ estilos.scss
┣ 📂 css
┃ ┣ estilos.css
┃ ┗ estilos.css.map
┣ 📄 index.html

````

---

## 🧩 Organização dos Partials (SCSS)

- **_base.scss**  
  Estilos base do projeto (reset, body, tipografia global)

- **_variaveis.scss**  
  Variáveis de cores, fontes, espaçamentos e tamanhos

- **_mixins.scss**  
  Mixins reutilizáveis para padrões de layout e componentes  
  _(ex: espaçamentos, botões, alinhamentos)_

- **_layout.scss**  
  Estrutura geral da página (header, seções, grids, footer)

- **_componentes.scss**  
  Componentes reutilizáveis como botões, cards, menus e formulários

- **estilos.scss**  
  Arquivo principal que importa todos os partials utilizando `@use`

---

## 🎨 Metodologia BEM

Todo o projeto mantém a **metodologia BEM**, garantindo clareza, reutilização e fácil manutenção do código.

Exemplos de classes utilizadas:

```css
.header__menu
.banner__title
.services__card
.testimonials__item
.contact__form
.button--primary
````

---

## ⚙️ Recursos do SASS Utilizados

✔ Variáveis para padronização visual

✔ Mixins reutilizáveis

✔ Aninhamento de seletores com boas práticas

✔ Operadores para cálculos proporcionais

✔ Arquitetura modular com partials

✔ Compilação via linha de comando (Node.js)

---

## 🛠️ Tecnologias Utilizadas

* **HTML5** — Estrutura semântica
* **SASS (SCSS)** — Arquitetura de estilos modular e escalável
* **CSS3** — Layout responsivo
* **Flexbox & Grid**
* **Metodologia BEM**
* **Node.js** — Compilação do SASS
* **Source Maps** — Auxílio no debug do CSS

---

## 📲 Responsividade

O layout é totalmente responsivo, adaptando-se a:

* 📱 Mobile
* 💻 Tablet
* 🖥️ Desktop

Utilizando:

* Containers flexíveis
* Media queries
* Componentização visual

---

## 👩‍💻 Autora

* GitHub — [@chryspenalber](https://github.com/chryspenalber)
* LinkedIn — [Chrystiana Penalber](https://www.linkedin.com/in/chrystiana-penalber/)


---


<a id="english"></a>

# 💼 Creative Web Agency — Refactored with SASS + BEM

### Project developed by Chrys Penalber

This project is part of **Task 12 of the EBAC Front-End Engineering course**.

The main goal was to **refactor the CSS of the Creative Web Agency project**, converting a traditional CSS structure into a **modular, scalable, and maintainable architecture** using **SASS (SCSS)** combined with the **BEM methodology**.

---

## 🔗 Links

* 🔴 [Live Site](https://chryspenalber.github.io/tarefa-12-sass/)
* 💻 [GitHub Repository](https://github.com/chryspenalber/tarefa-12-sass)

---

## 🎯 Project Goal

✔ CSS refactoring using **SASS**

✔ Modular architecture with partials

✔ Use of variables, mixins, nesting and operators

✔ BEM methodology for class naming

✔ Generation of a final compiled CSS file

---

## 🛠️ Technologies Used

* HTML5
* SASS (SCSS)
* CSS3
* Flexbox & Grid
* BEM Methodology
* Node.js (SASS compilation)

---

## 👩‍💻 Author

* GitHub — [@chryspenalber](https://github.com/chryspenalber)
* LinkedIn — [Chrystiana Penalber](https://www.linkedin.com/in/chrystiana-penalber/)
