# 📚 BookSpin AI: Intelligent Literary Transformer Workflow

> *"Spin, Review, Perfect — with AI and You in the Loop."*

BookSpin AI is a fully automated **literary transformation pipeline** that reimagines any book or story with the help of advanced LLMs (LLaMA3-70B via Groq) while incorporating **human-in-the-loop (HITL)** editing for quality assurance. Built on the powerful [LangGraph](https://python.langchain.com/docs/langgraph/) orchestration and [Playwright](https://playwright.dev/) for real-time content scraping, BookSpin AI is an end-to-end system for creating, reviewing, and polishing AI-generated literature — and storing it intelligently with rich metadata in ChromaDB.

---

## 🚀 Features

✅ Scrape any online book content via Playwright  
✅ Spin creative versions of the content using LLMs  
✅ Review the output for literary quality  
✅ Edit based on review with optional human refinement  
✅ Store every version with versioning, scores, and quality tags in ChromaDB  
✅ Track metadata such as source, quality, score, agent, and timestamp  
✅ Human-In-The-Loop Feedback integrated at every major step  

---

## 🧠 Powered By

- **LangGraph** for workflow orchestration  
- **LangChain + Groq (LLaMA 3)** for generation, review, and editing  
- **Playwright (async)** for scraping live book text  
- **ChromaDB** for versioned vector storage with custom metadata  
- **Python** as the orchestration language with editable CLI interaction  

---

### 🛠️ How It Works

```mermaid
graph TD
    A[Scrape Book Content] --> B[Spin with LLM - BookSpin AI]
    B --> C[User Edits or Approves Spin]
    C --> D[Review with LLM - Reviewer AI]
    D --> E[User Edits or Approves Review]
    E --> F[Final Edit with LLM - Editor AI]
    F --> G[User Final Approval]
    G --> H[Store in ChromaDB with Metadata]
