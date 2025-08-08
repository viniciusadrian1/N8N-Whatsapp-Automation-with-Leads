# 🤖 Automação de Respostas no WhatsApp com n8n + ChatGPT

Este projeto foi desenvolvido no [n8n](https://n8n.io/) com o objetivo de automatizar o recebimento e resposta de mensagens recebidas no WhatsApp via API, utilizando o ChatGPT para gerar mensagens inteligentes e personalizadas.

---

## ⚙️ Funcionalidades

- Recebe mensagens via Webhook da API do WhatsApp (Z-API)
- Extrai nome, número e mensagem recebida
- Usa o ChatGPT (OpenAI) para gerar uma resposta inteligente
- Envia a resposta de volta automaticamente via WhatsApp
- Registra os dados do cliente em uma planilha do Google Sheets

---

## 🔗 Tecnologias utilizadas

- n8n (self-hosted)
- OpenAI GPT-4.1
- Z-API (WhatsApp)
- Google Sheets API

---

## 📂 Workflow

O fluxo completo está disponível no arquivo:  
[`workflows/WhatsApp.json`](workflows/WhatsApp.json)

Você pode importá-lo diretamente no seu ambiente n8n.

---

## 🧪 Pré-requisitos

- Conta na OpenAI com chave de API
- Instância do n8n rodando
- Conta Z-API (ou outro provedor de WhatsApp)
- Conexão com Google Sheets

---

## 👨‍💻 Autor

Vinícius Adrian Siqueira de Oliveira  
[LinkedIn](https://www.linkedin.com/in/vinicius-adrian) • [Portfólio](https://https://github.com/viniciusadrian1)

---

## 🧠 Observação

Este projeto foi desenvolvido como parte de estudo e aplicação prática de automações com n8n e IA. Ideal para empresas que desejam automatizar atendimento e coleta de dados via WhatsApp.

