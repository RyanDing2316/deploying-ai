# StudySmith

StudySmith is a small dictionary-style chat client built for Assignment 2.  
It exposes **three separate services** behind a single conversational interface:

1. A **dictionary API service** for word definitions.
2. A **semantic search service** over locally stored notes using ChromaDB.
3. A **web lookup service** that fetches short summaries from Wiktionary / Wikipedia.

The chat UI is implemented with **Gradio** and all routing is done inside Python code
(`router.py`).

---

## 1. How to run the chat client

From the project root, run:

```bash
cd 05_src/assignment_chat
py app.py