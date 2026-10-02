# Ask My Notes: Retrieval-Augmented Q&A with an LLM

**Skill:** Large Language Models, prompt engineering, retrieval-augmented generation (RAG).

Answers questions only from your documents, cites its sources, and says "I don't know" when the answer is missing. Includes chunking, TF-IDF retrieval, a strict system prompt, a small evaluation set and a prompt comparison experiment.

## Run
1. Open Google Colab and choose File, then Upload notebook, and pick `3-llm_ask_my_notes.ipynb`.
2. Click the key icon (Secrets), add `ANTHROPIC_API_KEY`, and allow notebook access.
3. Runtime, then Run all.

## Ideas to extend
Embeddings instead of TF-IDF, PDF loading, chat history, a Streamlit or Gradio front end, LLM-based answer grading.
