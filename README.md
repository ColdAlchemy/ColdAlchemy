# Olá, sou o Albert 👋

Analista de Sistemas em Imperatriz-MA. Tecnólogo em Análise e Desenvolvimento de Sistemas (concluído em 08/2026) e cursando Ciência da Computação. Sou proprietário da Ótica Nova Visão e uso IA para automatizar rotinas do negócio (ERP, CRM).

**Foco:** IA aplicada (busca semântica, agentes, avaliação de sistemas de IA) e desenvolvimento de sistemas. Busco a primeira oportunidade em TI.

## Destaques: IA aplicada
| Projeto | Para que serve | Tecnologias |
|---|---|---|
| [docs-ia-laravel](https://github.com/ColdAlchemy/docs-ia-laravel) | **DocsIA**: arquivo de documentos (contratos, notificações) que extrai partes, prazos e valores com IA, responde perguntas com notas de rodapé que citam o trecho e avalia se a resposta é fundamentada. 67 testes. A demonstração usa IA simulada; o driver real da API está testado com HTTP simulado. | Laravel, Vue 3, RAG, tool calling |
| [rag-eval](https://github.com/ColdAlchemy/rag-eval) | Mede se a **busca** de um sistema RAG está boa: compara BM25, TF-IDF e híbrido, calcula Recall, MRR e nDCG e mostra quais perguntas cada método errou. 41 testes. | Python (sem dependências) |
| [agente-ferramentas](https://github.com/ColdAlchemy/agente-ferramentas) | **Agente de IA com ferramentas** escrito do zero, com validação de argumentos, aprovação humana para ações sensíveis e **guardas contra injeção de prompt**. Mede o efeito das guardas: sem elas, 6 ações indevidas; com elas, nenhuma. Modelo simulado. 37 testes. | Python (sem dependências) |
| [triagem-chamados](https://github.com/ColdAlchemy/triagem-chamados) | Classifica mensagens de suporte com Naive Bayes e regressão logística **escritos do zero** e encaminha para uma pessoa quando a confiança é baixa. Dados sintéticos. 24 testes. | Python (sem dependências) |
| [otica-automacao](https://github.com/ColdAlchemy/otica-automacao) | **Automação** de uma ótica fictícia: decide quem contatar (pedido pronto, atrasado, receita vencendo, aniversário), gera rascunhos para revisão humana e um [painel online](https://coldalchemy.github.io/otica-automacao/). Dados fictícios. 27 testes. | Python (sem dependências) |
| [arquivo-mcp](https://github.com/ColdAlchemy/arquivo-mcp) | Servidor **MCP** que deixa o Claude consultar os documentos do DocsIA (somente leitura, isolado por espaço de trabalho). 17 testes. | Node.js, SDK oficial do MCP |

**Artigo:** [Como saber se a busca do seu RAG está boa](https://github.com/ColdAlchemy/rag-eval/blob/main/docs/ARTIGO.md) · **Demonstrações online:** [relatório do rag-eval](https://coldalchemy.github.io/rag-eval/) e [painel da ótica](https://coldalchemy.github.io/otica-automacao/)

## Outros projetos
- [mini-crm-laravel](https://github.com/ColdAlchemy/mini-crm-laravel): Balcão, mini CRM para o comércio: painel com indicadores, funil kanban, retornos, etiquetas, botão do WhatsApp e importação de CSV. 54 testes.
- [estoque-api](https://github.com/ColdAlchemy/estoque-api): API REST de estoque em Node.js, Express e SQLite: JWT, paginação, movimentações transacionais e especificação OpenAPI. 35 testes.
- [consultas-medicas-api](https://github.com/ColdAlchemy/consultas-medicas-api): API REST em Java/Spring Boot + PostgreSQL (2024, feita sem IA). A cópia original está no repositório com sufixo `-original`.
- [Atividades de JavaScript](https://github.com/ColdAlchemy/Atividade-Desv.Web): exercícios de lógica (sem IA).

## Como eu trabalho
Uso o Claude Code como assistente de programação nos projetos de portfólio: eu defino o escopo, reviso e estudo o código, e cada projeto traz testes e um guia de estudo. A declaração completa, projeto por projeto, está em [USO-DE-IA.md](https://github.com/ColdAlchemy/ColdAlchemy/blob/main/USO-DE-IA.md). Os READMEs dizem o que **não** foi feito (por exemplo, dados fictícios ou IA simulada).

## Tecnologias
Python · PHP · Laravel · Vue.js · Node.js · Express · Java · Spring Boot · SQL/PostgreSQL · JavaScript · Linux · RAG · LLMs via API · tool calling · agentes e segurança · MCP · Machine Learning · automação · Git/GitHub

📫 albrtx23@gmail.com · [LinkedIn](https://www.linkedin.com/in/albert-ryan-brito-dos-santos-51614b2ab/)
