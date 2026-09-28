<div align="center">

# 💼 Portfólio & Currículo Pessoal

### Mini Desafio HTML · Desenvolvimento de Sistemas · SENAI

Uma página de portfólio web construída com **HTML5**, reunindo apresentação pessoal, habilidades, projetos e um formulário de contato, seguindo o layout do modelo proposto em sala de aula.

<br>

<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
<img src="https://img.shields.io/badge/SENAI-Desenvolvimento%20de%20Sistemas-004A8D?style=for-the-badge" alt="SENAI - Desenvolvimento de Sistemas">
<img src="https://img.shields.io/badge/status-conclu%C3%ADdo-2EA44F?style=for-the-badge" alt="Status: concluído">

<br><br>

[Sobre](#-sobre-o-projeto) · [Layout](#-visão-geral-do-layout) · [Seções](#-seções-da-página) · [Projetos](#-projetos-do-portfólio) · [Como executar](#-como-executar) · [Autor](#-autor)

</div>

---

## 📋 Índice

- [Sobre o projeto](#-sobre-o-projeto)
- [Objetivo](#-objetivo)
- [Visão geral do layout](#-visão-geral-do-layout)
- [Seções da página](#-seções-da-página)
- [Elementos HTML utilizados](#-elementos-html-utilizados)
- [Formulário de contato](#-formulário-de-contato)
- [Requisitos atendidos](#-requisitos-atendidos)
- [Projetos do portfólio](#-projetos-do-portfólio)
- [Estrutura do repositório](#-estrutura-do-repositório)
- [Como executar](#-como-executar)
- [Aprendizados](#-aprendizados)
- [Próximos passos](#-próximos-passos)
- [Autor](#-autor)

---

## 📌 Sobre o projeto

Este repositório contém a entrega do **Mini Desafio HTML — Portfólio & Currículo Pessoal**, proposto pelo professor **André Luis Denani** na disciplina de Desenvolvimento de Sistemas (turma **1ID-DS**) do SENAI.

A proposta era simular a contratação para criar a página de portfólio de um desenvolvedor web, demonstrando domínio da estrutura do HTML: organização de conteúdo em seções, navegação interna, tabela de dados e um formulário completo.

## 🎯 Objetivo

Criar uma página HTML **limpa, organizada e funcional**, que reproduza os tópicos e a disposição do layout do modelo, aplicando na prática:

- estrutura de documento HTML5 e hierarquia de títulos;
- navegação por âncoras entre seções;
- imagens com dimensões definidas;
- tabelas para apresentação de dados;
- formulários acessíveis, com campos e rótulos vinculados;
- rodapé com caracteres especiais e links de contato.

## 👀 Visão geral do layout

```text
┌────────────────────────────────────────────────┐
│  Nome - Desenvolvedor Web                      │
│  [Sobre]  [Projetos]  [Contato]                │
├────────────────────────────────────────────────┤
│  SOBRE MIM  (#sobre)                           │
│  [ foto 150x150 ]                              │
│  Texto de apresentação + Minhas Habilidades    │
├────────────────────────────────────────────────┤
│  MEUS PROJETOS  (#projetos)                    │
│  Projeto | Tecnologias | Status | Link         │
│  3 linhas de projetos com links                │
├────────────────────────────────────────────────┤
│  ENTRE EM CONTATO  (#contato)                  │
│  fieldset > Nome, Email, Assunto, Mensagem     │
│  [ Enviar Mensagem ]                           │
├────────────────────────────────────────────────┤
│  © 2026 | e-mail | telefone                    │
└────────────────────────────────────────────────┘
```

<!--
  Para exibir um print da página real, salve a imagem em docs/preview.png
  e troque este comentário por:  ![Preview da página](docs/preview.png)
-->

## 🧭 Seções da página

| Seção | Âncora | Conteúdo |
| :-- | :--: | :-- |
| **Cabeçalho e navegação** | — | Título principal com nome e cargo, e menu com links internos para as três seções |
| **Sobre Mim** | `#sobre` | Foto de perfil (150 × 150 px), texto de apresentação com destaque em **negrito** e *itálico*, e lista de habilidades |
| **Meus Projetos** | `#projetos` | Tabela com 4 colunas (Projeto, Tecnologias, Status e Link) e hiperlinks para os repositórios |
| **Entre em Contato** | `#contato` | Formulário agrupado em `fieldset` com campos de nome, e-mail, assunto, mensagem e botão de envio |
| **Rodapé** | `footer` | Direitos autorais com `&copy;`, e-mail (`mailto:`) e telefone (`tel:`) |

### 🧑‍🎓 Minhas habilidades

- Desenvolvimento de Jogos (Game Dev)
- Arte Digital
- Desenvolvimento de Sistemas / Web

## 🧱 Elementos HTML utilizados

| Elemento | Uso no projeto |
| :-- | :-- |
| `<!DOCTYPE html>`, `lang="pt-BR"`, `<meta charset>` e `<meta viewport>` | Base do documento, idioma e codificação corretos |
| `<h1>`, `<h2>`, `<h3>` | Hierarquia de títulos da página |
| `<ul>`, `<li>` e `<a href="#id">` | Menu de navegação e lista de habilidades |
| `<section id="...">` | Divisão do conteúdo em Sobre, Projetos e Contato |
| `<img width="150" height="150" alt="...">` | Foto de perfil com dimensões fixas e texto alternativo |
| `<strong>` e `<em>` | Ênfase em termos importantes do texto |
| `<table>`, `<tr>`, `<th>`, `<td>` | Tabela de projetos |
| `<a target="_blank">` | Links dos projetos abrindo em nova aba |
| `<form>`, `<fieldset>`, `<legend>` | Formulário agrupado com título "Dados do Contato" |
| `<label for>`, `<input>`, `<select>`, `<textarea>`, `<button>` | Campos do formulário, cada um com rótulo vinculado |
| `<hr>` | Separação visual entre as seções |
| `<footer>`, `&copy;`, `mailto:`, `tel:` | Rodapé com caractere especial e contatos clicáveis |
| `<style>` | Cor de fundo da página (`#d3d3d3`) |

## 📝 Formulário de contato

| Campo | Tipo | Obrigatório | Detalhes |
| :-- | :-- | :--: | :-- |
| **Nome** | `text` | ✅ | Campo de texto simples |
| **Email** | `email` | ✅ | Validação nativa do navegador |
| **Assunto** | `select` | — | Oportunidade de Trabalho · Proposta de Projeto · Contato Geral |
| **Mensagem** | `textarea` | ✅ | 4 linhas × 30 colunas |

> [!NOTE]
> O formulário é **demonstrativo**: usa `action="#"` e não possui back-end, portanto nenhuma mensagem é realmente enviada. A validação é feita pelos recursos nativos do HTML5 (`required` e `type="email"`).

## ✅ Requisitos atendidos

- [x] Título principal com nome e cargo
- [x] Menu de navegação com links internos (Sobre, Projetos, Contato)
- [x] Foto de perfil com `width="150"` e `height="150"`
- [x] Texto de apresentação e lista de habilidades
- [x] Tabela com 4 colunas e hiperlinks funcionais
- [x] Formulário com `<fieldset>` e `<legend>` ("Dados do Contato")
- [x] Campos de Nome, Email, Assunto (`<select>`) e Mensagem (`<textarea>`)
- [x] Todos os campos com `<label>` devidamente vinculado
- [x] Botão de envio
- [x] Rodapé com `&copy;`, e-mail e telefone

## 🚀 Projetos do portfólio

Trabalhos desenvolvidos durante o curso e apresentados na tabela da página:

| Projeto | Tecnologias | Status | Repositório |
| :-- | :-- | :--: | :--: |
| **Atividade 4 · Desafio2** — Cadastro de Produtos com Validação | PHP, MySQL, HTML5, XAMPP/Laragon | ✅ Concluído | [Ver projeto](https://github.com/vinyciussilva-cloud/Atividade-4-Cadastro-de-Produtos) |
| **Atividade Aula 5** — HTML parte 1 | HTML | ✅ Concluído | [Ver projeto](https://github.com/vinyciussilva-cloud/Atividade-Aula-5-HTML-Parte-1) |
| **Atividade 3 · Desafio** — Verificador de Maioridade | PHP e HTML5 | ✅ Concluído | [Ver projeto](https://github.com/vinyciussilva-cloud/Atividade-3-Desafio-Verificador-de-Maioridade) |

## 📂 Estrutura do repositório

```text
Mini-Desafio-HTML-Portfolio-Curriculo-Pessoal/
├── assets 3/
│   └── Sobre Mim.png      # foto de perfil (exibida em 150 x 150 px)
├── index.html             # página do portfólio
└── README.md              # documentação do projeto
```

## 💻 Como executar

O projeto é HTML puro, então **não precisa de instalação, build ou servidor**.

**1. Clone o repositório**

```bash
git clone https://github.com/vinyciussilva-cloud/Mini-Desafio-HTML-Portfolio-Curriculo-Pessoal.git
cd Mini-Desafio-HTML-Portfolio-Curriculo-Pessoal
```

**2. Abra a página**

Dê dois cliques no arquivo `index.html` e ele abrirá no seu navegador.

> 💡 **Dica:** no VS Code, a extensão **Live Server** recarrega a página automaticamente a cada alteração salva.

<details>
<summary><b>🌐 Publicar no GitHub Pages (opcional)</b></summary>

<br>

1. No repositório, acesse **Settings → Pages**.
2. Em **Build and deployment**, escolha **Deploy from a branch**.
3. Selecione a branch `main` e a pasta `/ (root)`, e clique em **Save**.
4. Aguarde alguns minutos: o link público da página aparecerá na mesma tela.

</details>

## 📚 Aprendizados

Ao desenvolver este desafio, pratiquei:

- estruturar uma página com hierarquia de títulos e seções identificadas por `id`;
- criar navegação interna com âncoras;
- inserir imagens com dimensões e texto alternativo;
- montar tabelas com cabeçalho, linhas e links;
- construir formulários completos, ligando `label` e campos por `for`/`id`;
- usar entidades HTML (`&copy;`) e links `mailto:` e `tel:`;
- versionar e entregar o trabalho pelo GitHub.

## 🔭 Próximos passos

- [ ] Reorganizar a estrutura com as tags semânticas `<header>`, `<nav>` e `<main>`
- [ ] Usar `<thead>` e `<tbody>` na tabela de projetos
- [ ] Estilizar a página com CSS (layout responsivo, tipografia e cores)
- [ ] Padronizar nomes de pastas e arquivos sem espaços (ex.: `assets/sobre-mim.png`)
- [ ] Adicionar interatividade com JavaScript, como validação personalizada do formulário
- [ ] Conectar o formulário a um back-end para envio real das mensagens

## 🙋 Autor

<div align="center">

**Vinycius Lopes Monteiro da Silva**
Estudante de Desenvolvimento de Sistemas · SENAI

[![GitHub](https://img.shields.io/badge/GitHub-vinyciussilva--cloud-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/vinyciussilva-cloud)
[![E-mail](https://img.shields.io/badge/E--mail-vinycius.silva%40edu.senai.br-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vinycius.silva@edu.senai.br)

</div>

---

<div align="center">

© 2026 Vinycius Lopes Monteiro da Silva · Projeto educacional desenvolvido durante o curso de Desenvolvimento de Sistemas do SENAI.

⭐ Se este projeto te ajudou ou inspirou, deixe uma estrela no repositório!

</div>
