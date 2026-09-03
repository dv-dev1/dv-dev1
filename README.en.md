<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1F6FEB,50:8957E5,100:DB6D28&height=170&section=header&text=Daniel%20Vieira&fontColor=ffffff&fontSize=52&fontAlignY=34&desc=AI%20Full%20Stack%20Engineer&descAlignY=56&descSize=18" alt="Daniel Vieira — AI Full Stack Engineer" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&pause=1200&color=1F6FEB&center=true&vCenter=true&width=760&lines=LLM+agents+that+survive+production;Policies+%C2%B7+hooks+%C2%B7+guardrails+%C2%B7+evals;RAG+%C2%B7+MCP+%C2%B7+LangGraph+%C2%B7+FastAPI+%C2%B7+React" alt="LLM agents that survive production — policies, hooks, guardrails, evals" />

<a href="https://www.linkedin.com/in/dv-dev/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:danielvmacedog1@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<img src="https://img.shields.io/badge/João_Pessoa,_Brazil-1F6FEB?style=for-the-badge&logo=googlemaps&logoColor=white" alt="João Pessoa, Brazil" />
<img src="https://img.shields.io/badge/Open_to_AI_Engineer_roles-2EA043?style=for-the-badge" alt="Open to AI Engineer roles" />

<br /><br />

[Português](README.md) · **English**

</div>

---

> **The gap between an agent that demos well and one that actually operates has a name: the harness.**
> The policies, the hooks, the guardrails and the evaluation suite around the model. That is what I work on.
> Full stack is not my title — it is the reason I can take an agent from prototype to production without waiting on anyone else.

## What that has been worth

<table>
<tr>
<td align="center" width="33%">
<h1>−99.3%</h1>
<b>cost per query</b><br />
US$ 6.00 → US$ 0.04<br />
<sub>The whole catalogue (600k tokens per question) replaced by RAG over a vector database.<br />Same daily budget: <b>3 → 500 customers/day</b>.</sub>
</td>
<td align="center" width="33%">
<h1>+92%</h1>
<b>completed bookings</b><br />
~120 → ~230 per month<br />
<sub>Exam scheduling for a large hospital, moved from n8n to an agent in code, with a closed harness around the model.</sub>
</td>
<td align="center" width="33%">
<h1>−80%</h1>
<b>engineering cycle</b><br />
from scope to a live bot<br />
<sub><i>Design-to-bot</i> pipeline: a Figma plugin turns the prototype into structured JSON, and the App Builder turns that JSON into a production bot.</sub>
</td>
</tr>
</table>

<div align="center"><sub>The last two run on Smartspace's private code. The first one is open below, with the before and the after.</sub></div>

## Case studies

| Project | What it is |
| :-- | :-- |
| **[emporio-da-musica-agent](https://github.com/dv-dev1/emporio-da-musica-agent)** | Customer support agent with tool calling over SQLite and BM25 over the policy manual — the model knows which of the two sources a question belongs to. CLI and a Streamlit chat interface over the same `Agent` object, Pytest coverage from unit to end-to-end. |
| **[n8n-rag-catalog-optimizer](https://github.com/dv-dev1/n8n-rag-catalog-optimizer)** | The 99.3% cut above, reproducible: a 2,000+ product catalogue served through RAG + Pinecone instead of the whole prompt. |
| **[chatbot-rag-discord-gaming](https://github.com/dv-dev1/chatbot-rag-discord-gaming)** | 24/7 support agent for an online game community, retrieving over a document base. |
| **[agente-sdr-varejo-cosmeticos](https://github.com/dv-dev1/agente-sdr-varejo-cosmeticos)** | AI SDR for lead qualification and 24/7 sales over WhatsApp, built as an agent with tools. |
| **[agente-moderacao-instagram-make](https://github.com/dv-dev1/agente-moderacao-instagram-make)** | Instagram comment triage and reply, deployed for public sector organisations. |
| **[automacao-relatorio-bi-vendas](https://github.com/dv-dev1/automacao-relatorio-bi-vendas)** | Daily sales performance report (D-1) delivered over WhatsApp. |
| **[automacao-content-factory-ia](https://github.com/dv-dev1/automacao-content-factory-ia)** | Content factory: a daily multimodal bulletin (text and audio) built from web scraping and AI. |

## Stack

**AI and agents**

<p>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain" />
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langgraph&logoColor=white" alt="LangGraph" />
<img src="https://img.shields.io/badge/RAG-8957E5?style=for-the-badge" alt="RAG" />
<img src="https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logo=pinecone&logoColor=white" alt="Pinecone" />
<img src="https://img.shields.io/badge/MCP-D97757?style=for-the-badge&logo=anthropic&logoColor=white" alt="MCP" />
<img src="https://img.shields.io/badge/Evals_and_token_cost-8957E5?style=for-the-badge" alt="Evals and token cost" />
<img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI" />
<img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=claude&logoColor=white" alt="Claude" />
<img src="https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logo=groq&logoColor=white" alt="Groq" />
<img src="https://img.shields.io/badge/Botpress-0D6EFD?style=for-the-badge" alt="Botpress" />
<img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" alt="n8n" />
</p>

**Backend and frontend**

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

**Data and infrastructure**

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

## Right now

Conversational AI Engineer and Full Stack Developer at **Smartspace**, building LLM agents in production and the applications around them, from the flow to the deploy. Standardising the team's AI-assisted development with a workspace of hooks and skills: LLM generation now follows the architectural pattern by construction, instead of by case-by-case correction.

**Open to AI Engineer and Automation Engineering roles** — remote from Brazil, and willing to relocate to São Paulo when a role calls for it.

<div align="center">

<a href="https://www.linkedin.com/in/dv-dev/"><img src="https://img.shields.io/badge/Let's_talk-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Let's talk on LinkedIn" /></a>
<a href="mailto:danielvmacedog1@gmail.com"><img src="https://img.shields.io/badge/danielvmacedog1@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="danielvmacedog1@gmail.com" /></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:DB6D28,50:8957E5,100:1F6FEB&height=90&section=footer" alt="" />

</div>
