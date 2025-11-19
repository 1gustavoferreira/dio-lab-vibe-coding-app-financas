# 💸 FinAmigo - Organização Financeira Simplificada

![Status do Projeto](https://img.shields.io/badge/Status-MVP%20Desenvolvido-brightgreen)
![Design](https://img.shields.io/badge/Design-Universal-blue)
![Challenge](https://img.shields.io/badge/Desafio-DIO_Vibe_Coding-purple)

> Este projeto foi desenvolvido como parte do **Desafio de Projeto da DIO (Vibe Coding)**, explorando o potencial da programação assistida por IA com **Lovable** e **Copilot**.

---

## 📸 Resultado Final

Acesse o protótipo funcional no Lovable:  
🔗 **[Clique aqui para testar o FinAmigo](https://chatty-cents-app.lovable.app/)**

<div align="center">
  <img width="100%" alt="Dashboard do FinAmigo" src="https://github.com/user-attachments/assets/7430db5c-6e01-45ef-bf33-573c8f2e3d9e" />
</div>

---

## 📖 Sobre o Projeto

O **FinAmigo** é uma solução de organização de finanças pessoais focada em **Design Universal**. O objetivo é tornar o controle financeiro intuitivo e acessível para todos, eliminando a complexidade de planilhas e formulários através de **interações em linguagem natural**.

### 🎯 Problema Solucionado
Muitas pessoas desistem de organizar as finanças pela complexidade dos apps tradicionais. O FinAmigo resolve isso permitindo que o usuário apenas diga: *"Gastei 30 reais na padaria"* e a IA cuida do resto.

---

## 🧠 Processo de Desenvolvimento (Vibe Coding)

O desenvolvimento seguiu um fluxo de **Engenharia de Prompt**, começando pela definição dos requisitos com auxílio de LLMs e partindo para a geração de código visual.

### 1. Refinamento do PRD
O documento de requisitos foi refinado utilizando o **Copilot/Gemini** para garantir clareza antes de ser enviado para a IA geradora de código.

<details>
  <summary>📄 <strong>Clique para ver o PRD/Prompt Completo utilizado</strong></summary>

  ### PRD - App de Organização Financeira com Conversa Natural
  
  **Visão Geral** Criar um aplicativo de organização de finanças pessoais que funcione por meio de conversas em linguagem natural, tornando o controle financeiro livre de burocracias.

  **Público-Alvo** Pessoas que desejam organizar finanças sem complicações, especialmente iniciantes ou pessoas com dificuldades com interfaces complexas.

  **Funcionalidades-Chave**
  1. **Registro via chat:** "Gastei R$ 30 no mercado".
  2. **Classificação automática:** O app categoriza sozinho.
  3. **Metas:** "Economizar R$ 500 até o fim do mês".
  4. **Design Universal:** Interface acessível, alto contraste e compatibilidade com leitores de tela.

  **Stack Sugerida pela IA**
  - React + Tailwind CSS
  - Shadcn UI + Lucide React
</details>

### 2. Geração com Lovable
Com o PRD refinado, o prompt foi enviado ao **Lovable.dev**, que gerou a interface e a lógica de frontend em React.

> **Prompt Inicial:** "Crie um App de Finanças Pessoais com base no seguinte PRD: {Conteúdo do PRD}..."

---

## ✨ Funcionalidades do MVP

### 📊 Painel Financeiro (Dashboard)
* **Visão Imediata:** Cards claros de Saldo, Receitas e Despesas.
* **Feedback Visual:** Cores intuitivas (Verde para ganhos, Vermelho para gastos, Azul para saldo).
* **Transações Recentes:** Lista simplificada com ícones de fácil leitura.

### 💬 Assistente Financeiro
* **Interação Natural:** Interface estilo chat para registro de dados.
* **Acessibilidade:** Botões grandes e tipografia legível (Inter/Sans-serif).

---

## 🛠️ Tecnologias Utilizadas

* **IA Generativa:** [Lovable.dev](https://lovable.dev/) & Copilot
* **Frontend:** React
* **Estilização:** Tailwind CSS
* **Componentes:** Shadcn UI
* **Ícones:** Lucide React

---

## 🧠 Reflexão sobre o Desafio

Este projeto demonstrou como a IA pode acelerar drasticamente a prototipagem de interfaces complexas.

* **O que funcionou bem?**
    O refinamento prévio do PRD (feito no Gemini/Copilot) foi crucial. Como o PRD estava detalhado, o Lovable gerou uma interface quase pronta na primeira tentativa, economizando créditos.

* **O que não funcionou como o esperado?**
    A limitação de interações no plano gratuito do Lovable exigiu precisão cirúrgica nos prompts. Não houve margem para "tentativa e erro".

* **Aprendizado principal:**
    Conversar com IAs de geração de código é similar a liderar uma equipe técnica: **quanto mais claro, estruturado e detalhado for o seu pedido (Contexto + Requisito), melhor será a entrega.**

---

<div align="center">
  <sub>Desenvolvido por Gustavo Ferreira para o Desafio DIO Vibe Coding</sub>
</div>
