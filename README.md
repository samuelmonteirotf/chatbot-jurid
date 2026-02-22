# Chatbot JurID ⚖️

**Assistente virtual jurídico especializado em Certificados Digitais (A1, A3, Nuvem)**

Chatbot full-stack para triagem e suporte técnico de advogados brasileiros na emissão e instalação de e-CPF, e-CNPJ e certificados Vidaas.

## Tecnologias
- **Frontend**: Vue 3 + Vite + Tailwind CSS (dark/light mode)
- **Backend**: Node.js + Express + Helmet + Rate Limiting
- **IA**: knowledgeBase.json com matching de palavras-chave
- **DevOps**: Docker + docker-compose + PM2

## Funcionalidades
- Respostas instantâneas sobre instalação A1/A3
- Fluxo guiado de troubleshooting
- Suporte a múltiplos certificados
- Totalmente offline-ready

## Integrações LegalTech
Integra com **Lexter.ai**, **Cria.AI** e sistemas de assinatura digital. Pronto pra virar produto SaaS.

## Como rodar
```bash
git clone https://github.com/samuelmonteirotf/chatbot-jurid.git
cd chatbot-jurid
docker-compose up --build