# 🤖 Automação de Respostas no WhatsApp com n8n + ChatGPT
# 🤖 WhatsApp Response Automation with n8n + ChatGPT

**PT:** Este projeto foi desenvolvido no [n8n](https://n8n.io/) com o objetivo de automatizar o recebimento e resposta de mensagens recebidas no WhatsApp via API, utilizando o ChatGPT para gerar mensagens inteligentes e personalizadas.  
**EN:** This project was developed using [n8n](https://n8n.io/) to automate the reception and response of WhatsApp messages via API, using ChatGPT to generate intelligent and personalized messages.

---

## ⚙️ Funcionalidades / Features

- Recebe mensagens via Webhook da API do WhatsApp (Z-API) / Receives messages via WhatsApp API Webhook (Z-API)  
- Extrai nome, número e mensagem recebida / Extracts name, phone number, and received message  
- Usa o ChatGPT (OpenAI) para gerar uma resposta inteligente / Uses ChatGPT (OpenAI) to generate intelligent responses  
- Envia a resposta de volta automaticamente via WhatsApp / Sends the response back automatically via WhatsApp  
- Registra os dados do cliente em uma planilha do Google Sheets / Records customer data in a Google Sheets spreadsheet

---

## 🔗 Tecnologias utilizadas / Technologies Used

- n8n (self-hosted)  
- OpenAI GPT-4.1  
- Z-API (WhatsApp)  
- Google Sheets API

---

## 📂 Workflow

O fluxo completo está disponível no arquivo / The full workflow is available at:  
[`workflows/WhatsApp.json`](workflows/WhatsApp.json)

Você pode importá-lo diretamente no seu ambiente n8n / You can import it directly into your n8n environment.

---

## 🧪 Pré-requisitos / Prerequisites

- Conta na OpenAI com chave de API / OpenAI account with API key  
- Instância do n8n rodando / Running n8n instance  
- Conta Z-API (ou outro provedor de WhatsApp) / Z-API account (or another WhatsApp provider)  
- Conexão com Google Sheets / Google Sheets connection

---

## 👨‍💻 Autor / Author

Vinícius Adrian Siqueira de Oliveira  
[LinkedIn](https://www.linkedin.com/in/vinicius-adrian) • [Portfólio](https://github.com/viniciusadrian1)

---

## 🧠 Observação / Note

**PT:** Este projeto foi desenvolvido como parte de estudo e aplicação prática de automações com n8n e IA. Ideal para empresas que desejam automatizar atendimento e coleta de dados via WhatsApp.  
**EN:** This project was developed as part of a study and practical application of automations with n8n and AI. Ideal for companies that want to automate customer service and data collection via WhatsApp.
