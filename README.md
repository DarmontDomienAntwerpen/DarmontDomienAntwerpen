## Domien Darmont

**Frontline commander at Brandweer Zone Antwerpen (Antwerp Fire Department) · BIRD team (Drones, IT, Robotics & Digital Technologies) · Building applied AI systems**

I work where emergency response, technology and implementation meet. For over 16 years I have served with the Antwerp Fire Department, currently as a frontline commander and operational leader of the BIRD team. There I lead teams during real incidents and drive the practical adoption of drones, robotics, data and digital technology in public safety.

In 2026 I completed the Ironhack AI Engineering bootcamp, covering machine learning, computer vision, deep neural networks, large language models and AI-driven automation. The projects below apply that knowledge to real operational problems. AAR and IncidentIQ are built for my own field, public safety. The other projects are practice builds: each one exists to learn and drill a specific technique, such as voice agents, document search (RAG), agent workflows and model fine-tuning. All of them are built to be reliable, traceable and usable by the people who depend on them.

My approach: start from the operational need, test what is possible under realistic conditions, and turn technology into something people can actually use in practice.

---

### Built from operational experience

Operational problems I ran into in emergency response, tackled with the techniques I built up in the skill-building projects below.

| Project | Description | Stack |
|---|---|---|
| [**AAR**](https://github.com/DomienDarmontAntwerpen/AAR) | AI-assisted After Action Review. Reads the reports of everyone involved and builds one debrief: an incident summary, a shared timeline, what went well, points for improvement and lessons learned, each point linked to the exact sentence it came from. Built for fire services, adaptable to any emergency service or team that runs After Action Reviews. | Claude · FastAPI · SQLAlchemy · Pydantic |
| [**IncidentIQ**](https://github.com/DomienDarmontAntwerpen/IncidentIQ) | Turns incident training videos into searchable knowledge, debrief documents and scenarios for XVR, a VR training simulator. | LangGraph · RAG · Pinecone · LangSmith |

### Skill-building projects

Built to learn and practise specific techniques. Each one is a complete, working project, but the goal is the technique, not the product.

| Project | Description | Technique practised | Stack |
|---|---|---|---|
| [**Cordon**](https://github.com/DomienDarmontAntwerpen/cordon)<br><sub>🆕 Latest project · October 2026</sub> | AI gateway between a company's apps and models like ChatGPT: masks personal data before it leaves, blocks prompt injection, keeps each team within its budget and sends a request to a cheaper model **only where that model was proven as good** - 80% saved on a simulated working day, measured live. | LLM cost optimisation and routing, guardrails, evaluation with tests fixed in advance | FastAPI · LiteLLM · scikit-learn · Docker |
| [**Lisa**](https://github.com/DomienDarmontAntwerpen/lisa_ai_assistant) | AI voice receptionist that answers calls, books appointments and escalates to a human. | Real-time voice agents, tool calling | OpenAI Realtime · Twilio · FastAPI · PostgreSQL |
| [**Servix**](https://github.com/DomienDarmontAntwerpen/servix) | Field-service assistant that troubleshoots HVAC fault codes from service manuals, always citing the source page. | RAG with source citations, vision, guardrails | GPT-4o Vision · Qdrant · RAG · Docker |
| [**Lead Scraper**](https://github.com/DomienDarmontAntwerpen/lead-scraper) | B2B prospecting pipeline: finds, scores and drafts outreach for human review. | Agent workflows, human-in-the-loop | LangGraph · Claude · Playwright |
| [**Amazon Review Analyzer**](https://github.com/DomienDarmontAntwerpen/amazon-review-analyzer) | NLP pipeline on 46,000 product reviews: **fine-tuned a BERT sentiment classifier** (77.0% → 79.4% accuracy), clustered products with sentence embeddings and generated buyer's guides with a local LLM. | Fine-tuning, embeddings, local LLMs | Hugging Face Transformers · PyTorch · Llama 3.2 · Streamlit |

Bootcamp exercises: [ironhack-ai-engineering-bootcamp](https://github.com/DomienDarmontAntwerpen/ironhack-ai-engineering-bootcamp)

---

### Background

- **Operational leadership**: station commander and incident leader, coordinating multidisciplinary teams under pressure
- **Public-safety innovation**: testing drones, robotics and digital systems in realistic conditions and turning lessons from exercises and incidents into procedures and training
- **Training & knowledge sharing**: Incident Command System (ICS), and firefighting strategy for urban, tunnel and heavy-industrial environments
- **Belgian Defence**: experience in a structured military environment
- **Ironhack AI Engineering bootcamp (2026)**: 3-month full-time programme covering machine learning, computer vision, deep learning, LLMs, RAG and AI agents, with hands-on projects every week

### Technical skills

- **AI & LLMs:** OpenAI (Realtime, Vision), Anthropic Claude, LangChain, LangGraph, Hugging Face, RAG, agents & tool calling, evaluation (RAGAS, LangSmith)
- **Machine learning:** model fine-tuning (BERT; LoRA / QLoRA with PEFT in coursework), scikit-learn, PyTorch, Keras, NLP, computer vision (coursework)
- **Engineering:** Python, FastAPI, PostgreSQL, Qdrant, Pinecone, Docker, pytest, Pydantic

### Contact

[LinkedIn](https://www.linkedin.com/in/domiendarmont/)

A live demo, a project presentation or answers to any questions about these projects are available on request.
