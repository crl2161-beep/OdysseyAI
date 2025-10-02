# OdysseyAI: An Agentic AI Platform for Interactive Text Analysis

**Platform:** Palantir Foundry  
**Duration:** July 2025 – Sept. 2025  

OdysseyAI is an AI-driven platform that aligns Ancient Greek learning with natural language acquisition, training fluency through active prediction and contextual understanding rather than rote memorization. Users interact with the AI Agent, Professor Mentor, which draws from a structured ontology object containing the complete lexical, morphological, and syntactic features, for each line as well as next-token prompts, and teaching notes. The platform combines this ontology, the AI Agent, and an interactive Workshop App to enable both guided line-by-line exercises and free-form conversation modes. 
---

## Features

- **Foundry-native pipeline**: Ingests annotated Ancient Greek texts via multi-LLM workflows, producing line-level JSON entries with full lexical, syntactic, and morphological tags plus scholarly commentary; outputs a structured ontology object.  
- **AI Agent**: Supports two interaction modes:  
  1. Line-by-line predictive reading with adaptive feedback and progress tracking  
  2. Free-form exploration for morphology, syntax, stylistic analysis, or embedded scholarly references  
 Operates directly on the ontology object, leveraging its JSON-based line-level annotations for accurate, context-aware guidance; supported by retrieval-augmented generation (RAG), self-evaluation loops, and ontology-driven automations to ensure accuracy.  
- **Interactive Workshop App**: User interface for engaging with the Agent in either mode; supports scrolling through or selecting lines, including texts not yet processed.  
- **Pedagogical design**: Emphasizes active prediction and contextual comprehension, mirroring how humans acquire language.

---

## Live Demo

The full interactive Workshop App is hosted online for exploration without local setup:  
[Try the demo here](https://share.streamlit.io/yourusername/odysseyai/main/src/app/app.py)

---

