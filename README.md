# Olá, sou o Albert 👋

Analista de Sistemas em Imperatriz-MA. Tecnólogo em Análise e Desenvolvimento de Sistemas (concluído em 08/2026) e cursando Ciência da Computação.

Sou proprietário da Ótica Nova Visão e uso IA todos os dias para criar projetos e automatizar rotinas do negócio (ERP, CRM).

## O que construí com IA
No [DocsIA](https://github.com/ColdAlchemy/docs-ia-laravel), um arquivo de cartório em Laravel + Vue 3:
- **Extração estruturada**: a IA devolve JSON validado por JSON Schema (tipo, partes, prazos e valores).
- **Busca semântica (RAG)**: documentos divididos em trechos com posição no texto original e embeddings, consulta por cosseno, sempre dentro do espaço de trabalho.
- **Agente com tool calling**: laço com ferramentas (`search_documents`, `get_document`, `list_prazos`) e respostas com notas de rodapé que apontam o trecho citado.
- **Avaliação das respostas**: um avaliador confere se toda citação vem de um trecho recuperado, e um painel de qualidade acompanha a taxa de respostas fundamentadas.
- **Driver de IA intercambiável**: interface `AiClient` com driver real da Anthropic e driver offline para testes. A demonstração usa IA simulada; o driver real está testado com HTTP simulado.

Também uso IA para automatizar rotinas da Ótica Nova Visão (ERP e CRM).

## Projetos
- [docs-ia-laravel](https://github.com/ColdAlchemy/docs-ia-laravel): DocsIA, um arquivo de cartório com IA em Laravel + Vue 3: login e espaços de trabalho, leitor de documentos com notas de margem, extração estruturada, busca semântica (RAG), agente com tool calling e painel de qualidade das respostas (desenvolvido por mim com o auxílio do Claude Code, com 67 testes; a demonstração usa uma IA simulada, e o driver real da API está implementado e testado com HTTP simulado).
- [mini-crm-laravel](https://github.com/ColdAlchemy/mini-crm-laravel): Balcão, mini CRM para o comércio em Laravel: painel com indicadores e gráficos, funil kanban com arrastar e soltar, retornos, etiquetas, botão do WhatsApp e importação de CSV (desenvolvido por mim com o auxílio do Claude Code, com 54 testes).
- [Estoque API](https://github.com/ColdAlchemy/Crud-usando-o-Express): API REST de estoque com Node.js, Express e SQLite: JWT, paginação, movimentações transacionais, especificação OpenAPI e console com playground (desenvolvido por mim com o auxílio do Claude Code, com 35 testes).
- [Consultas Médicas](https://github.com/ColdAlchemy/Sistema-de-Gerenciamento-de-Consultas-M-dicas): API REST em Java/Spring Boot + PostgreSQL (2024, feita sem IA). A cópia original está no repositório com sufixo `-original`.
- [Atividades de JavaScript](https://github.com/ColdAlchemy/Atividade-Desv.Web): exercícios de lógica (sem IA).

## Tecnologias
PHP · Laravel · Vue.js · LLMs via API · RAG · Node.js · Express · Java · Spring Boot · SQL/PostgreSQL · Python · JavaScript · Linux · IA aplicada (Claude)

📫 albrtx23@gmail.com
