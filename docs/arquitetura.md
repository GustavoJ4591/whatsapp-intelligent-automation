# Arquitetura do Sistema

## Visão Geral
A arquitetura do sistema é composta por:
- Backend (Node.js ou Python)
- WhatsApp Business API
- Servidor dedicado
- Banco de Dados
- Webhook
- Integração com ERP (futuro)

## Backend
Responsável por:
- Lógica do bot
- Processamento de mensagens
- Roteamento por setor e região
- Bloqueio de duplicidade
- Coleta de dados

## Banco de Dados
Armazena:
- Clientes
- Atendimentos
- Histórico
- Orçamentos
- Logs

## Integrações
- API Meta
- E-mail
- ERP
