# OdysseyAI: An Agentic AI Platform for Interactive Text Analysis

**Platform:** Palantir Foundry  
**Duration:** July 2025 – Sept. 2025  

OdysseyAI guides users through interactive readings of Ancient Greek texts. It features Professor Mentor, an AI that trains reading fluency through active prediction and contextual understanding. Users can select lines from the object table and ask questions. Mentor uses a structured ontology object with complete lexical, morphological, and syntactic features for each line, as well as next-token prompts and teaching notes. The application's goal is to better align Classical language learning with natural language acquisition.
---

## Features

- **Foundry-native pipeline**: Ingests annotated Ancient Greek texts producing line-level JSON entries with full lexical, syntactic, and morphological tags plus scholarly commentary; outputs a structured ontology object.  
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

