# 📄 Portfólio & Currículo Pessoal

Página web de currículo e portfólio pessoal, desenvolvida em **HTML puro** durante o curso de **Desenvolvimento de Sistemas do SENAI**. O objetivo é apresentar quem eu sou, minhas habilidades, meus projetos e oferecer um formulário de contato.

---

## 📌 Sobre o projeto

Este projeto foi criado para praticar os fundamentos do HTML, explorando os principais elementos da linguagem em um caso real: um currículo online.

A página é dividida em três seções principais:

| Seção | Descrição |
|-------|-----------|
| **Sobre Mim** | Foto, breve apresentação e lista de habilidades |
| **Meus Projetos** | Tabela com nome, tecnologias, status e link de cada projeto |
| **Entre em Contato** | Formulário com nome, e-mail, assunto e mensagem |

---

## 🛠️ Tecnologias e recursos utilizados

- **HTML5** — estrutura semântica da página
- **CSS inline** — estilização básica (cor de fundo e estilo de listas)

### Elementos HTML praticados

- Cabeçalhos (`h1`, `h2`, `h3`) e parágrafos
- Ênfase de texto (`strong`, `em`)
- Listas não ordenadas (`ul`, `li`)
- Links internos (âncoras com `id`) e externos (`target="_blank"`)
- Imagens (`img`) com atributo `alt`
- Tabelas (`table`, `thead`, `tbody`, `tr`, `th`, `td`)
- Formulários (`form`, `fieldset`, `legend`, `label`, `input`, `select`, `textarea`, `button`)
- Validação nativa de campos (`required`, `type="email"`)
- Rodapé (`footer`) e contato (`address`, links `mailto:` e `tel:`)

---

## 🧰 Habilidades destacadas

- HTML
- CSS
- PHP
- Banco de Dados
- Figma
- Projetos e Apresentações

> Também estou aprendendo um pouco de JavaScript.

---

## 🚀 Projetos apresentados

| Projeto | Tecnologias | Status |
|---------|-------------|--------|
| Projeto de lógica e algoritmo Java | HTML, CSS | ✅ Concluído |
| Projeto de filme Hulk | JavaScript | ✅ Concluído |
| Atividade em HTML — Projeto Lima | HTML, CSS | ✅ Concluído |

Os links para cada repositório estão disponíveis na própria página.

---

## 📁 Estrutura de arquivos

```
📦 projeto
 ┣ 📂 assets
 ┃ ┗ 🖼️ eu.jpg          # Foto de perfil
 ┣ 📄 curriciulo.html    # Página principal
 ┗ 📄 README.md
```

---

## ▶️ Como executar

Não é necessário instalar nada.

1. Clone o repositório ou baixe os arquivos:
   ```bash
   git clone <url-do-repositorio>
   ```
2. Confirme que a foto está em `assets/eu.jpg`.
3. Abra o arquivo `curriciulo.html` em qualquer navegador (Chrome, Firefox, Edge...).

---

## 📬 Formulário de contato

O formulário envia os dados pelo método `POST` para o arquivo `processar.php`.

**Campos:**
- Nome (obrigatório)
- E-mail (obrigatório, com validação)
- Assunto (Oportunidade de Trabalho, Dúvidas ou Questão Pessoal)
- Mensagem

> ⚠️ Para o envio funcionar, é preciso rodar o projeto em um servidor com PHP (como XAMPP ou WAMP) e criar o arquivo `processar.php`. Abrindo apenas o HTML no navegador, o formulário é exibido, mas não processa os dados.

---

## 🔮 Melhorias futuras

- [ ] Separar o CSS em um arquivo externo (`style.css`)
- [ ] Tornar o layout totalmente responsivo
- [ ] Criar o `processar.php` para tratar e salvar as mensagens
- [ ] Adicionar seção de formação e experiências
- [ ] Incluir animações e interações com JavaScript
- [ ] Publicar a página com GitHub Pages

---

## 📄 Licença

Projeto desenvolvido para fins educacionais durante o curso do SENAI.

© 2026 — Todos os direitos reservados.
