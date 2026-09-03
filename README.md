<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1F6FEB,50:8957E5,100:DB6D28&height=170&section=header&text=Daniel%20Vieira&fontColor=ffffff&fontSize=52&fontAlignY=34&desc=AI%20Full%20Stack%20Engineer&descAlignY=56&descSize=18" alt="Daniel Vieira — AI Full Stack Engineer" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&pause=1200&color=1F6FEB&center=true&vCenter=true&width=760&lines=Agentes+de+LLM+que+aguentam+produ%C3%A7%C3%A3o;Policies+%C2%B7+hooks+%C2%B7+guardrails+%C2%B7+evals;RAG+%C2%B7+MCP+%C2%B7+LangGraph+%C2%B7+FastAPI+%C2%B7+React" alt="Agentes de LLM que aguentam produção — policies, hooks, guardrails, evals" />

<a href="https://www.linkedin.com/in/dv-dev/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:danielvmacedog1@gmail.com"><img src="https://img.shields.io/badge/E--mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail" /></a>
<img src="https://img.shields.io/badge/João_Pessoa,_PB-1F6FEB?style=for-the-badge&logo=googlemaps&logoColor=white" alt="João Pessoa, PB" />
<img src="https://img.shields.io/badge/Aberto_a_vagas_de_Engenheiro_de_IA-2EA043?style=for-the-badge" alt="Aberto a vagas de Engenheiro de IA" />

<br /><br />

**Português** · [English](README.en.md)

</div>

---

> **A distância entre um agente que demonstra bem e um que opera de verdade tem nome: harness.**
> As policies, os hooks, os guardrails e a suíte de avaliação em volta do modelo. É nisso que eu trabalho.
> Full stack não é o meu título — é a razão de eu levar um agente do protótipo ao ar sem depender de mais ninguém.

## O que isso já valeu

<table>
<tr>
<td align="center" width="33%">
<h1>−99,3%</h1>
<b>custo por consulta</b><br />
US$ 6,00 → US$ 0,04<br />
<sub>Catálogo inteiro (600 mil tokens/pergunta) trocado por RAG com banco vetorial.<br />Mesmo orçamento diário: <b>3 → 500 clientes/dia</b>.</sub>
</td>
<td align="center" width="33%">
<h1>+92%</h1>
<b>marcações concluídas</b><br />
~120 → ~230 por mês<br />
<sub>Agendamento de exames de um hospital de grande porte, de n8n para agente em código, com harness fechado em volta do modelo.</sub>
</td>
<td align="center" width="33%">
<h1>−80%</h1>
<b>ciclo de engenharia</b><br />
do escopo ao bot no ar<br />
<sub>Pipeline <i>design-to-bot</i>: plugin de Figma converte o protótipo em JSON, o App Builder o transforma em bot de produção.</sub>
</td>
</tr>
</table>

<div align="center"><sub>Os dois últimos rodam em código privado da Smartspace. O primeiro está aberto aqui embaixo, com o antes e o depois.</sub></div>

## Estudos de caso

| Projeto | O que é |
| :-- | :-- |
| **[emporio-da-musica-agent](https://github.com/dv-dev1/emporio-da-musica-agent)** | Agente de atendimento com *tool calling* sobre SQLite e BM25 no manual de políticas — o modelo sabe a qual das duas fontes cada pergunta pertence. CLI e interface de chat em Streamlit sobre o mesmo objeto `Agent`, testes com Pytest do unitário ao end-to-end, documentação em inglês. |
| **[n8n-rag-catalog-optimizer](https://github.com/dv-dev1/n8n-rag-catalog-optimizer)** | O corte de 99,3% acima, reproduzível: catálogo de 2.000+ produtos servido por RAG + Pinecone no lugar do prompt inteiro. |
| **[chatbot-rag-discord-gaming](https://github.com/dv-dev1/chatbot-rag-discord-gaming)** | Agente de suporte 24/7 em comunidade de jogo online, com recuperação sobre base documental. |
| **[agente-sdr-varejo-cosmeticos](https://github.com/dv-dev1/agente-sdr-varejo-cosmeticos)** | SDR de IA para qualificação de leads e vendas 24/7 no WhatsApp, em arquitetura de agente com ferramentas. |
| **[agente-moderacao-instagram-make](https://github.com/dv-dev1/agente-moderacao-instagram-make)** | Triagem e resposta de comentários no Instagram, implementado em entidades do setor público. |
| **[automacao-relatorio-bi-vendas](https://github.com/dv-dev1/automacao-relatorio-bi-vendas)** | Relatório diário de performance de vendas (D-1) entregue por WhatsApp. |
| **[automacao-content-factory-ia](https://github.com/dv-dev1/automacao-content-factory-ia)** | Fábrica de conteúdo: boletim diário multimodal (texto e áudio) a partir de *web scraping* e IA. |

## Stack

**IA e agentes**

<p>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain" />
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langgraph&logoColor=white" alt="LangGraph" />
<img src="https://img.shields.io/badge/RAG-8957E5?style=for-the-badge" alt="RAG" />
<img src="https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logo=pinecone&logoColor=white" alt="Pinecone" />
<img src="https://img.shields.io/badge/MCP-D97757?style=for-the-badge&logo=anthropic&logoColor=white" alt="MCP" />
<img src="https://img.shields.io/badge/Evals_e_custo_por_token-8957E5?style=for-the-badge" alt="Evals e custo por token" />
<img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI" />
<img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=claude&logoColor=white" alt="Claude" />
<img src="https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logo=groq&logoColor=white" alt="Groq" />
<img src="https://img.shields.io/badge/Botpress-0D6EFD?style=for-the-badge" alt="Botpress" />
<img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" alt="n8n" />
</p>

**Backend e frontend**

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
<img src="https://img.shields.io/badge/React-087EA4?style=for-the-badge&logo=react&logoColor=white" alt="React" />
<img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit" />
<img src="https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" alt="Pytest" />
</p>

**Dados e infraestrutura**

<p>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase" />
<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
<img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
<img src="https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform" />
<img src="https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" alt="Kafka" />
<img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white" alt="RabbitMQ" />
</p>

## Agora

Engenheiro de IA Conversacional e Desenvolvedor Full Stack na **Smartspace**, construindo agentes de LLM em produção e as aplicações em volta deles, do fluxo ao deploy. Padronizando o desenvolvimento assistido por IA do time com um workspace de hooks e skills: a geração por LLM passa a seguir o padrão arquitetural por construção, não por correção caso a caso.

**Aberto a vagas de Engenheiro de IA, AI Engineer e Engenharia de Automação** — remoto no Brasil, com mudança para São Paulo se a vaga pedir.

<div align="center">

<a href="https://www.linkedin.com/in/dv-dev/"><img src="https://img.shields.io/badge/Vamos_conversar-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Vamos conversar no LinkedIn" /></a>
<a href="mailto:danielvmacedog1@gmail.com"><img src="https://img.shields.io/badge/danielvmacedog1@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="danielvmacedog1@gmail.com" /></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:DB6D28,50:8957E5,100:1F6FEB&height=90&section=footer" alt="" />

</div>
