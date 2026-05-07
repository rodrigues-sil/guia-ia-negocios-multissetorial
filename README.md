# Guia de IA e Aplicações Práticas para Negócios - DIO

## Desafio DIO: Caderno Temático de IA no NotebookLM - guia-ia-negocios-multissetorial
Miniguia de IA e aplicações práticas utilizando curadoria no NotebookLM e Engenharia de Prompts para resolução de problemas reais.

## 🎯 Contexto e Objetivos
Este projeto prático tem como objetivo explorar o uso da Inteligência Artificial como uma ferramenta de **aprendizagem ativa**. Através da curadoria de fontes de alta relevância sobre IA aplicada a negócios (Marketing, Vendas, Finanças, Contabilidade e Management), criei um Caderno Temático no **NotebookLM** para consolidar conhecimentos, realizar engenharia de prompts e documentar o raciocínio técnico por trás da resolução de problemas.

O objetivo foi arquitetar uma solução baseada em software e agentes (sem investimento inicial em hardware) que conecte áreas críticas como Supply Chain, Logística, Marketing e Finanças, utilizando infraestruturas de ponta.

## 📚 Curadoria de Fontes
Para alimentar o conhecimento deste guia no **NotebookLM**, utilizei as seguintes fontes (disponíveis nos links ou pastas de apoio):
1. **McKinsey Digital (AI)**: https://mckinsey.com/capabilities/quantumblack/our-insights
2. **Gartner (AI Hub)**: https://gartner.com/en/information-technology/topics/artificial-intelligence
3. **IBM Research**: https://research.ibm.com/artificial-intelligence
4. **OpenAI Blog**: https://openai.com/news
5. **Anthropic News**: https://anthropic.com/news
6. **Google Research**: https://research.google
7. **DeepMind**: https://deepmind.google/discover
8. **Deloitte AI Institute**: https://deloitte.com/us/state-of-ai

*Acesse meu caderno de estudos no NotebookLM:* [Link do Notebook](https://notebooklm.google.com/notebook/209e4be4-0903-48e7-a765-a9a0f134a0f7)

## 🧠 Engenharia de Prompts e "Cicatrizes"
Documentação da jornada de aprendizado e os desafios enfrentados (troubleshooting) durante a interação com a IA:

* **Prompt Nível 1 (Básico):** "Por favor, me de um resumo da situação atual da AI, novos desenvolvimentos, capacidades e um overview do que a AI pode fazer na industria a negocios em supply chain, marketing, vendas, compras, finanças, contabilidade"
    * *Resultado:* Respostas pouco profunda.
* **Prompt Nível 2 (Contextualizado):** "Atue como un Chief of Artificial Inteligente Officer de uma grande empresa de bebidas (exemplo Heineken). Crie um roadmap e descrições detalhadas de como é possivel integrar IA desde o setor produtivo, supply chain, logistica, marketing, vendas, finanças, contabilidade etc. Considere que a empresa, nesse primeiro momento fará um investimento em software não em hardware. Ou seja, agentes, softwares, aplicações, programas, ou até mesmo um programa (como o SAP), que será usado por toda a organização onde teremos soluções de IA fazendo a maior parte do trabalho. Descreva o que é possivel fazer, o que é possivel otimizar, o que é possivel delegar a IA, quais as ferramentas deveriam ser usadas e como fazer esse grande projeto. Seja o mais especifico e completo possível. Me dê um relatorio abrangente e profundo."
    * *Resultado:* Resposta mais técnica.
 
* **O Desafio do "Cérebro" da Empresa:** Inicialmente, a IA sugeria agentes isolados. 
* **A Solução (Cicatriz):** Através do NotebookLM, explorei como o **MCP (Model Context Protocol)** pode servir como a ponte para extrair dados brutos do **SAP**. Aprendi que a IA precisa de um "tecido conectivo" (como o **PwC Agent OS**) para que os agentes colaborem em equipes híbridas (Humanos + IA).
* **Refinamento de RAG:** Documentei a necessidade de usar **Grafos de Conhecimento** junto ao RAG para que a IA não apenas "leia" documentos, mas entenda as relações complexas entre fornecedores, preços e logística.


## 🛠️ Miniguia de Estudo (Entrega Final)

### Insights Estratégicos
1. **Sistemas Multi-Agentes:** A tendência de delegar tarefas a agentes especializados, similar a uma gestão de equipe humana.
2. **Conectividade:** A importância da integração via APIs para que a IA não seja apenas um chatbot, mas um motor de automação (end-to-end).
3.  **Orquestração:** Diferença entre usar modelos puros (Claude/Gemini) e plataformas de escala (Vertex AI/Foundry) que garantem segurança e governança.
4.  **Agentes Especialistas:** Como o **crewAI** pode comandar uma equipe de agentes onde um pesquisa o mercado e outro executa a compra no ERP.

### Glossário de Conceitos
* **LLM:** O motor de processamento de linguagem.
* **RAG:** Técnica de ancoragem da IA em documentos específicos para evitar alucinações.
* **Agentes de IA:** Sistemas capazes de executar tarefas autônomas usando ferramentas externas.
* **MCP (Model Context Protocol):** Padrão aberto para conectar IAs a fontes de dados (como SAP).
* **Grafos de Conhecimento:** Estrutura que organiza dados por relacionamentos, permitindo que a IA entenda o contexto do negócio.
* **Streamlit:** Ferramenta para criar interfaces rápidas (Dashboards) para interagir com os agentes.

### Prompts Reutilizáveis (Para futuras revisões)
* *"Atue como Arquiteto de Soluções: Desenhe um fluxo onde um agente monitora o estoque no SAP e, via MCP, aciona um agente de compras ao atingir o estoque de segurança."*
* *"Como integrar o modelo Claude no Microsoft Foundry para análise de conformidade regional?"*



