# OdysseyAI: An Agentic AI Platform for Interactive Text Analysis

**Platform:** Palantir Foundry  
**Duration:** July 2025 – Sept. 2025  

OdysseyAI guides users through interactive readings of Ancient Greek texts. It features Professor Mentor, an AI that trains reading fluency through active prediction and contextual understanding. Users can select lines from the object table and ask questions. Mentor uses a structured ontology object with complete lexical, morphological, and syntactic features for each line, as well as next-token prompts and teaching notes. The application's goal is to better align Classical language learning with natural language acquisition.
---
# Ancient Greek Agentic AI Workshop 
## For Users

This platform lets you **read and explore Homeric Greek interactively**. The AI agent can operate in two modes:

1. **Structured Predictive Reading**  
   - Click a line of text in the Workshop App  
   - The agent provides a **missing-word challenge** with hints  
   - Tracks your **progress and correct/incorrect responses**  

2. **Free Exploration Mode**  
   - Enter a passage (Greek text or scholarly reference)  
   - The agent provides **morphology, syntax, and commentary**  
   - Connects to other parts of the text or external references via **ontology and RAG**

**Quick Start**  
1. Open the **Workshop App** in Foundry  
2. Select the text or line you want to study  
3. Choose your **mode**: Predictive Reading or Free Exploration  
4. Follow the AI prompts to **learn vocabulary, grammar, and syntax** interactively  

**Tips for Effective Use**  
- Start with **structured reading** to build foundational understanding  
- Use **free exploration** to dive deeper into morphology and style  
- Revisit lines to see **progress over time**

## Front-Page Summary
An **AI-powered platform** for interactive reading and analysis of Greek with dual modes:  

- **Predictive line-by-line reading** with adaptive feedback and progress tracking  
- **Free exploration** of morphology, syntax, stylistics, and scholarly references  

Designed for students, educators, and scholars, it enables **context-aware guidance**, **active prediction**, and **progress tracking** for natural language acquisition.

---

## Features
- Line-level **JSON annotations**: lexical, syntactic, morphological  
- **Scholarly commentary** integration  
- **Dual AI interaction modes**: structured predictive reading and free exploration  
- **Retrieval-Augmented Generation (RAG)** for external references  
- **Self-evaluation loops** and ontology-driven automations for reliability  
- **Interactive Workshop App** with scrolling/selectable lines  
- Supports texts **not yet formally annotated**

---

## Architecture & Workflow
1. **Pipeline** ingests annotated Ancient Greek texts and produces line-level JSON entries  
2. Each entry includes **lexical, syntactic, and morphological features**, plus **scholarly commentary**  
3. Entries are aggregated into a **structured ontology object**  
4. The **AI agent** operates on the ontology, leveraging:
   - JSON line-level annotations for **context-aware guidance**  
   - **RAG retrieval** for references  
   - Self-evaluation loops and ontology-driven automations  
5. Users interact via the **Workshop App**, selecting lines for guided reading or free exploration  

*Workflow Diagram Placeholder:*  
`Pipeline → Ontology → AI Agent → Workshop App → User Interface`  


---

## Pedagogical Approach
- Emphasizes **active prediction** and **contextual understanding**, reflecting natural language acquisition  
- Tracks **user progress and word-level responses** to adapt guidance

---
