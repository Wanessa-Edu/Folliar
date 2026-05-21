# 🧠 Pensamento Computacional & Inteligência Artificial

> **Aula prática** · 18 de maio de 2026 · Análise e Desenvolvimento de Sistemas

---

## 📌 Sobre esta aula

Nesta aula unimos os **pilares do Pensamento Computacional** com o uso prático de **Inteligência Artificial**, partindo de um problema real do mercado e chegando até a geração de um prompt funcional que produziu uma solução tecnológica completa.

---

## 🏛️ Os 4 Pilares do Pensamento Computacional

| Pilar | O que é | Como aplicamos |
|---|---|---|
| **Decomposição** | Dividir um problema grande em partes menores | Separamos o problema do mercado literário em dores específicas: spoilers, organização, histórico |
| **Reconhecimento de Padrões** | Identificar semelhanças e repetições | Percebemos que todo clube de leitura enfrenta os mesmos problemas de fragmentação |
| **Abstração** | Focar no essencial, ignorar o irrelevante | Definimos o diferencial central: bloqueio de spoilers por progresso individual |
| **Algoritmo** | Criar um passo a passo para resolver o problema | Estruturamos o fluxo: problema → prompt → solução → MVP |

---

## 🌍 O Problema Real do Mercado

Trabalhamos com uma dor **real, verificável e cotidiana**:

> Clubes de leitura hoje funcionam de forma fragmentada entre WhatsApp, Discord, Google Docs e redes sociais — causando spoilers acidentais, perda de engajamento, desorganização e ausência de histórico das discussões.

### Por que esse problema importa?

- 🏛️ **3.000+** clubes de leitura mapeados no Brasil
- 📚 Mercado editorial brasileiro movimentou **R$ 2,97 bilhões** em 2023
- 📱 **7 milhões** de usuários ativos no Skoob
- 📈 Crescimento de **+340%** em clubes pós-pandemia

---

## 💬 O Prompt que Geramos

O prompt foi construído aplicando os pilares do pensamento computacional:

```
Você é um Product Designer e Desenvolvedor Full Stack especialista em MVPs modernos.

Crie o MVP de uma plataforma chamada "Foliar", focada na organização de
clubes de leitura.

CONTEXTO
Hoje clubes de leitura funcionam de forma desorganizada entre WhatsApp,
Discord e Google Docs, causando:
- spoilers;
- perda de engajamento;
- dificuldade de organização;
- ausência de histórico das discussões.

O diferencial do Foliar é permitir leitura coletiva com:
- cronograma de leitura;
- progresso individual;
- comentários bloqueados por spoiler conforme o progresso do usuário;
- histórico do clube.
```

### Anatomia do prompt (Pensamento Computacional aplicado)

```
[DECOMPOSIÇÃO]   → Separamos o pedido em 7 seções claras
[ABSTRAÇÃO]      → Focamos no diferencial real: o spoiler-gate
[PADRÃO]         → Usamos estrutura de briefing de produto real
[ALGORITMO]      → Definimos ordem de entrega: produto → telas → tech → banco → roadmap
```

---

## 🤖 O que a IA Gerou

A partir do prompt estruturado, a IA produziu um **MVP completo** contendo:

### Produto
- Conceito, proposta de valor e branding
- Paleta de cores, tipografia e tom de voz

### Telas (7 telas documentadas)
- Landing Page, Login/Cadastro, Dashboard
- Página do Clube, Livro Atual, Feed de Comentários, Perfil

### Funcionalidades do MVP
- Criação de clubes e rodadas de leitura
- Votação do próximo livro
- **Spoiler-gate inteligente** por capítulo ← *diferencial único*
- Histórico permanente do clube

### Estrutura Técnica
| Camada | Tecnologia |
|---|---|
| Front-end | React + Vite |
| Back-end | Node.js + Express |
| Banco de Dados | PostgreSQL |
| Autenticação | JWT + OAuth Google |
| API de Livros | Google Books API |
| Hospedagem | Railway / Render |

### Banco de Dados
6 entidades relacionais com a lógica do spoiler-gate embutida:
`users` · `clubs` · `club_members` · `reading_rounds` · `user_book_progress` · `comments`

### Roadmap
4 sprints de 2 semanas — do zero ao MVP em **8 semanas**

---

## 🔁 O Ciclo que Percorremos

```
PROBLEMA REAL
     ↓
PENSAMENTO COMPUTACIONAL
(decompor, abstrair, identificar padrões, montar algoritmo)
     ↓
PROMPT BEM ESTRUTURADO
     ↓
IA COMO FERRAMENTA
     ↓
SOLUÇÃO TECNOLÓGICA COMPLETA
```

---

## 💡 Conclusão

> A IA não substituiu o raciocínio — ela **amplificou** ele.

O pensamento computacional foi o que tornou possível transformar uma reclamação comum ("spoilers no WhatsApp") em um produto estruturado, com lógica, arquitetura e diferencial de mercado.

**Sem decomposição, sem abstração, sem padrão reconhecido → o prompt seria genérico → o resultado seria medíocre.**

---

## 📁 Arquivos desta aula

| Arquivo | Descrição |
|---|---|
| `README.md` | Este documento |
| `foliar-mvp.html` | MVP interativo completo gerado pela IA |
| `Foliar_Sintese_Problema.docx` | Documento Word com síntese do problema |

---

*Pensamento Computacional · ADS · 18/05/2026*
