# Chatbot GoodWe — EV ChargeOps Assistant (Sprint 1)

## Integrantes
- Brenno Gomes — RM: 57052
- Eduardo Moreira — RM: 569923
- Enzo Stahal — RM: 569001
- Matheus Bruno — RM: 572944

## Problema abordado (EV Challenge 2026)
O desafio da GoodWe no EV Challenge 2026 destaca a falta de mecanismos integrados em eletropostos e sistemas de recarga para:
- Orquestrar potência entre múltiplas recargas simultâneas
- Registrar sessões de recarga (ciclos)
- Gerar relatórios e faturamento automatizado
- Melhorar comunicação entre usuários e gestão

Esse problema se torna ainda mais crítico em condomínios, onde o carregamento é compartilhado entre moradores.

## Proposta do Chatbot
O projeto propõe o **GoodWe EV ChargeOps Assistant**, um chatbot operacional com IA para auxiliar:
- Síndicos e administradoras
- Moradores usuários do carregador
- Técnicos de manutenção

O chatbot atua respondendo dúvidas e orientando sobre regras de uso, consumo, custos, relatórios e resolução de falhas comuns.

## Persona e Escopo
### Persona principal: Síndico/Administrador
Justificativa: é o responsável pela gestão do carregador, cobrança, conflitos e regras de uso.

### Persona secundária: Morador
Justificativa: precisa de respostas rápidas sobre uso, agendamento e custos.

## Tecnologias selecionadas e justificativa técnica
### IA (LLM)
- **OpenAI API (GPT-4o-mini / GPT-4.1)**
Justificativa: alta precisão, respostas consistentes, fácil integração via API e bom custo.

### Framework de integração
- **LangChain**
Justificativa: facilita RAG (busca em documentos), memória e pipelines.

### Backend
- **Python + FastAPI**
Justificativa: rápido para APIs, integra bem com IA e banco.

### Banco de dados
- **PostgreSQL**
Justificativa: robusto e ideal para armazenar logs de recarga e usuários.

### Vetorização para RAG
- **FAISS ou ChromaDB**
Justificativa: busca rápida por similaridade para documentos técnicos e regras.

## Fluxograma
O fluxograma está disponível em:
- `docs/fluxograma.mmd`

## Perguntas e respostas de teste
Disponível em:
- `docs/perguntas_respostas.md`

## System Prompt
Disponível em:
- `prompts/system_prompt.txt`

## Objetivo da Sprint 1
- Planejamento do chatbot
- Criação do fluxograma
- Definição de perguntas/respostas esperadas
- Construção do system prompt base
- Organização do repositório GitHub
