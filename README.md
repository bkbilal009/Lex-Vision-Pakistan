---
title: Lex-Vision-Pakistan
emoji: ⚖️
colorFrom: pink
colorTo: rose
sdk: gradio
app_file: app.py
pinned: false
license: mit
short_description: Judicial RAG for Pakistan Supreme Court precedents.
---

# ⚖️ Lex-Vision-Pakistan: Judicial Intelligence Engine

> **"Empowering justice through data-driven precedents."**
> 
> Lex-Vision-Pakistan ek specialized RAG system hai jo **Muhammad Bilal** ne develop kiya hai taake Supreme Court of Pakistan ke hazaron legal records ko searchable banaya ja sakay.

![Python](https://img.shields.io/badge/Python-3.10-3776AB?style=for-the-badge&logo=python&logoColor=white)
![ChromaDB](https://img.shields.io/badge/VectorDB-Chroma-003366?style=for-the-badge)
![Gemini](https://img.shields.io/badge/Gemini-2.5_Flash-4285F4?style=for-the-badge&logo=google&logoColor=white)
![HuggingFace](https://img.shields.io/badge/Deployed-HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

---

## 🏛️ Project Vision

Pakistan ka legal system bohot purana aur vast hai. **Lex-Vision-Pakistan** ko **Muhammad Bilal** ne isliye design kiya taake lawyers aur law students ko constitutional articles aur case law precedents dhoondne mein ghanton ke bajaye seconds lagain. Ye system legal document ko "understand" karta hai, sirf keyword search nahi karta.

---

## 🏗️ Technical Architecture (The Vault)

### 1. Document Engineering (The Librarian)
* **Unstructured Data Parsing:** `.txt` aur `.pdf` format ke legal judgments ko process karna.
* **Recursive Character Splitting:** Legal jargon aur sections ko preserve karne ke liye semantic chunking ka istemal.

### 2. Semantic Retrieval (The Searcher)

* **Vector Embeddings:** `HuggingFace/all-MiniLM-L6-v2` ke zariye legal text ko high-dimensional space mein store karna.
* **ChromaDB Integration:** Industry-grade vector storage for lightning-fast similarity search.

### 3. Contextual Generation (The Judge)
* **Gemini 2.5 Flash:** Google ka latest model use kiya gaya hai jo bari legal context windows ko efficiently handle karta hai.
* **Grounded Responses:** AI sirf wahi citations deta hai jo database mein maujood hon.

---

## 🛠️ Tech Stack

| Component | Technology | Role |
| :--- | :--- | :--- |
| **Orchestration** | LangChain (Modular) | Retrieval & QA Chains |
| **Vector Database** | ChromaDB | Legal Precedent Indexing |
| **Embeddings** | Sentence-Transformers | Deep Semantic Understanding |
| **Reasoning Model** | Gemini 2.5 Flash | Constitutional Reasoning |
| **UI Theme** | Rose & Slate Pink | Professional & Elegant Interface |

---

## 🚀 Key Features

* **Case Law Insight:** Purani judgments se fori reference nikalna.
* **Constitutional Support:** Articles aur clauses ki automatic mapping.
* **Zero-Hallucination:** Strict retrieval protocols for 100% factual accuracy.

---

## 👨‍💻 Developer Profile

**Muhammad Bilal**
*Aspiring AI Developer | Stanford Candidate | RAG Specialist.*
Focused on digitizing the judicial landscape of Pakistan.

---
