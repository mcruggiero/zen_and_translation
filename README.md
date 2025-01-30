**Title:** **The Dao Machine Translation: A Hands-on Workshop for Open-Source Daoist Text Processing**

**Abstract:**
Machine Translation (MT) has made significant strides in recent years, particularly with the advent of Large Language Models (LLMs) and Retrieval-Augmented Generation (RAG). However, many practical MT solutions rely on proprietary models, limiting accessibility and customization. This session will demonstrate how to construct an end-to-end MT pipeline using open-source tools, leveraging RAG to enhance translation accuracy for domain-specific content. As a case study, we will build a translation system for classical and modern Japanese Daoist and Zen Buddhist texts, showcasing how to fine-tune retrieval mechanisms for specialized corpora.

We will begin with a brief historical perspective of MT from the 1940s to the present day, covering key developments, including Statistical Machine Translation (SMT) and vectorization techniques. Then, we will transition to modern methods, starting with a comparative analysis of various open-source models available on Hugging Face, such as mBERT and NLLB-200. Finally, we will demonstrate how to fine-tune these models for domain-specific tasks, using traditional Daoist texts as a practical example.

Additionally, we will briefly build out a RAG that attendees can use on their local laptops, featuring a basic chatbot capable of answering user questions about Daoism. This chatbot will leverage a corpus of texts in three different languages: Chinese, Japanese, and English, demonstrating multilingual retrieval and translation capabilities.

While RAG and chatbot implementation will be briefly covered, the primary focus will be on modern MT techniques, ensuring attendees gain practical insights into translation pipeline construction rather than chatbot development.

RAG is particularly useful in this scenario because it allows us to combine the strengths of retrieval-based approaches with generative modeling, ensuring translations are both contextually accurate and dynamically adapted to domain-specific queries. Traditional MT pipelines often struggle with niche corpora like Daoist texts, but by integrating retrieval mechanisms, we can improve translation quality and relevance.

**Pacing Strategy & Deliverables:**
To ensure efficient use of time, we will follow a structured approach:

- **10 min:** Introduction – Historical context, overview of SMT and vectorization techniques.  
- **20 min:** Fine-Tuning Transformers – Basics & Hugging Face Walkthrough.  
- **15 min:** Comparing Open-Source MT Models – Performance & Tradeoffs.  
- **60 min:** **Hands-On** – Building the MT Pipeline for Classical Daoist Texts.  
  - **Part 1 (30 min):** Data Preparation & Model Setup.  
  - **Part 2 (30 min):** Fine-Tuning & Evaluation.  
- **15 min:** Quick Intro to RAG & Llama-Based Chatbot.

Attendees will leave with:

- A reproducible Jupyter Notebook containing code for MT pipeline construction.
- Access to a curated multilingual dataset of Daoist texts.
- A lightweight, locally deployable chatbot implementation using RAG.

**Key Takeaways:**

- Understand the fundamentals of RAG and its application to MT.
- Learn how to integrate open-source models like NLLB-200 with vector databases.
- Explore domain adaptation strategies for improving translation accuracy.
- Compare different open-source MT models available on Hugging Face (e.g., mBERT, NLLB-200).
- Gain hands-on insights into evaluating MT performance in specialized domains.
- See a real-world implementation of Daoist and Zen Buddhist text translation using open-source tools.
- Build and deploy a basic chatbot using a RAG pipeline that answers questions about Daoism in multiple languages.

**Target Audience:**
Introductory-Intermediate. Ideal for ML engineers, data scientists, and AI practitioners interested in machine translation, LLMs, and open-source AI development. A basic understanding of NLP concepts, such as tokenization, embeddings, and transformer-based models, will be helpful but not required.

**Session Format:**
2-hour talk with a live demo showcasing a RAG-based translation system in action.

**Speaker Commitment:**
I understand the requirements of ODSC and will ensure the proposal adheres to the non-promotional guidelines. I am prepared to actively promote the session on social media and will provide all required presentation materials within the designated timelines.

