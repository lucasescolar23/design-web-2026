# Página Pessoal com DaisyUI

## Sobre o projeto

Esta página pessoal foi desenvolvida utilizando **DaisyUI junto com Tailwind CSS**, com o objetivo de criar uma apresentação profissional utilizando componentes prontos da biblioteca DaisyUI, combinando estrutura, organização e responsividade.

A página apresenta informações pessoais, habilidades, projetos desenvolvidos e uma área de contato.

---

# Componentes DaisyUI utilizados

## Navbar

O componente `navbar` foi utilizado no cabeçalho da página para apresentar meu nome e minha área de atuação, além de disponibilizar um botão de contato.

Escolhi esse componente porque ele organiza as informações principais logo no início da página de forma simples e eficiente.

---

## Hero

O componente `hero` foi utilizado na seção inicial de apresentação para destacar minha área de atuação e apresentar uma breve descrição sobre mim.

Ele foi escolhido porque cria uma área de destaque, dando mais importância para a primeira impressão da página.

---

## Badge

Foram utilizadas variações do componente `badge` para destacar habilidades e áreas de interesse.

Componentes utilizados:

* `badge-primary`
* `badge-outline`
* `badge-secondary`

Eles ajudam a visualizar rapidamente minhas principais áreas de conhecimento.

---

## Card

O componente `card` foi utilizado na seção de projetos para organizar as informações de cada trabalho desenvolvido.

Foram criados três cards:

* DoeMais+
* Registro de Comandas
* Portfólio Web

Cada card utiliza:

* `card-body`
* `card-title`
* `card-actions`

O uso dos cards facilita a organização das informações e deixa a apresentação dos projetos mais clara.

---

## Button

O componente `btn` foi utilizado nas ações da página.

Foram utilizadas diferentes variações:

* `btn-primary`
* `btn-secondary`
* `btn-outline`

A utilização de diferentes estilos ajuda a diferenciar ações principais e secundárias.

---

## Input

O componente `input` foi utilizado na área de contato para criar campos de formulário.

Foram adicionados campos para:

* Nome
* Email
* Mensagem

Foi utilizado o estilo:

* `input-bordered`

para melhorar a organização visual do formulário.

---

# Justificativa da escolha do cabeçalho

Foi escolhido o componente `navbar` junto com o `hero` para construir o início da página.

O `navbar` permite apresentar informações importantes de forma organizada, enquanto o `hero` cria uma área de destaque para a apresentação pessoal.

Essa combinação deixa a página mais completa e melhora a experiência inicial do usuário.

---

# Ajustes realizados com Tailwind CSS

Apesar do DaisyUI fornecer os componentes principais, algumas classes do Tailwind foram utilizadas para personalizar o layout.

Exemplos:

* `grid md:grid-cols-3` foi utilizado para organizar os cards de projetos e garantir responsividade em diferentes tamanhos de tela.
* `px-6`, `py-12` e `gap-6` foram utilizados para controlar espaçamento e melhorar a organização visual da página.

O Tailwind foi utilizado como complemento para ajustar o posicionamento e a responsividade dos componentes DaisyUI.

---

# Reflexão sobre temas

A página foi testada utilizando os temas `dark` e `light` do DaisyUI.

O tema `dark` apresentou maior coerência com a proposta da página, pois combina melhor com uma apresentação relacionada à tecnologia e desenvolvimento web, além de destacar melhor os elementos visuais.

Mesmo assim, a estrutura continua funcionando corretamente no tema `light`.

---

# Tecnologias utilizadas

* HTML5
* Tailwind CSS
* DaisyUI
