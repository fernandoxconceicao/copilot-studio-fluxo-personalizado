# 🚀 Criando um Copiloto com Fluxo de Conversa Personalizado no Microsoft Copilot Studio

Este repositório tem como objetivo ensinar, passo a passo, como criar um copiloto (chatbot) com um fluxo de conversa personalizado utilizando o **Microsoft Copilot Studio**.

## Índice

- [Pré-requisitos](#pré-requisitos)
- [O que é o Microsoft Copilot Studio?](#o-que-é-o-microsoft-copilot-studio)
- [Passo a Passo](#passo-a-passo)
  - [1. Acessando o Copilot Studio](#1-acessando-o-copilot-studio)
  - [2. Criando um Novo Copiloto](#2-criando-um-novo-copiloto)
  - [3. Criando um Fluxo de Conversa Personalizado](#3-criando-um-fluxo-de-conversa-personalizado)
  - [4. Testando o Copiloto](#4-testando-o-copiloto)
  - [5. Publicando o Copiloto](#5-publicando-o-copiloto)
- [Dicas e Boas Práticas](#dicas-e-boas-práticas)
- [Referências](#referências)

---

## Pré-requisitos

- Conta Microsoft (organizacional ou educacional)
- Permissão para acessar o [Microsoft Copilot Studio](https://copilotstudio.microsoft.com/)
- Navegador atualizado

---

## O que é o Microsoft Copilot Studio?

O **Microsoft Copilot Studio** é uma plataforma low-code/no-code da Microsoft para criar copilotos (chatbots) inteligentes, integrando fluxos de conversa personalizados, automações e IA generativa.

---

## Passo a Passo

### 1. Acessando o Copilot Studio

1. Acesse: [https://copilotstudio.microsoft.com/](https://copilotstudio.microsoft.com/)
2. Faça login com sua conta Microsoft.

### 2. Criando um Novo Copiloto

1. No painel inicial, clique em **"Criar"** ou **"Novo Copiloto"**.
2. Dê um nome ao seu copiloto (ex: `AtendimentoSuporte`).
3. Escolha o idioma principal do copiloto.
4. Clique em **"Criar"**.

### 3. Criando um Fluxo de Conversa Personalizado

1. No menu lateral, clique em **"Tópicos"**.
2. Clique em **"Novo Tópico"**.
3. Defina um nome para o tópico (ex: `Boas-vindas`).
4. Adicione **frases de gatilho** (ex: "Olá", "Oi", "Bom dia").
5. No editor de fluxo, adicione as mensagens e perguntas que o copiloto deve fazer.
   - Exemplo:
     - Mensagem: "Olá! Como posso ajudar você hoje?"
     - Pergunta: "Você precisa de suporte técnico ou informações sobre produtos?"
6. Adicione ramificações de acordo com as respostas do usuário.
   - Exemplo:
     - Se o usuário escolher "Suporte técnico", direcione para um fluxo específico.
     - Se escolher "Informações sobre produtos", direcione para outro fluxo.
7. Salve o tópico.

### 4. Testando o Copiloto

1. No canto superior direito, clique em **"Testar Copiloto"**.
2. Interaja com o copiloto e verifique se o fluxo de conversa está funcionando conforme esperado.

### 5. Publicando o Copiloto

1. Após testar e ajustar o fluxo, clique em **"Publicar"**.
2. Siga as instruções para disponibilizar o copiloto em canais como Microsoft Teams, site, etc.

---

## Dicas e Boas Práticas

- Use frases de gatilho variadas para melhorar o reconhecimento de intenções.
- Mantenha as mensagens claras e objetivas.
- Teste diferentes cenários de conversa.
- Utilize a integração com Power Automate para automações avançadas.
- Atualize e melhore o fluxo de conversa com base no feedback dos usuários.

---

## Referências

- [Documentação Oficial do Microsoft Copilot Studio](https://learn.microsoft.com/pt-br/microsoft-copilot-studio/)
- [Microsoft Copilot Studio - YouTube](https://www.youtube.com/results?search_query=Microsoft+Copilot+Studio)

---

Sinta-se à vontade para contribuir com sugestões, melhorias ou dúvidas! 🚀

---

**Licença:** MIT
