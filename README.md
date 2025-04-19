## Overview

This blog post presents my Capstone Project for the 5-day Gen AI Intensive Course with Google (March 31 - April 4, 2025). The challenge was to apply at least three Generative AI (Gen AI) capabilities to a real-world use case, documented in a Kaggle Notebook, with optional blog and video components for bonus points. My project tackles a uniquely Indian challenge: making the Companies Act more accessible and actionable for Chartered Accountants (CAs) and businesses.

---

## The Genesis of an Idea

It was a typical day in summer in Delhi when my CA friend Tushar called, frustration evident in his voice. "I've spent three hours trying to find the exact compliance requirements for a project in my internship," he sighed. "The Companies Act is a labyrinth, and I'm tired of getting lost in it."

That conversation sparked my Capstone Project for the 5-day Gen AI Intensive Course with Google (March 31 - April 4, 2025). While others pursued chatbots and content generators, I saw an opportunity to solve a uniquely Indian problem that affects thousands of professionals daily: navigating the behemoth that is the Indian Companies Act, 2013.

## The Mountainous Challenge: India's Companies Act

For those unfamiliar with Indian corporate law, imagine a 470-section legal document, supplemented by hundreds of rules, notifications, and amendments that change frequently. Now imagine being a Chartered Accountant or Company Secretary responsible for ensuring businesses comply with every relevant provision.

The Companies Act governs everything from a company's formation to its dissolution, covering corporate governance, financial disclosures, board responsibilities, and shareholder rights. It's the backbone of corporate regulation in India, and misinterpreting or overlooking any part can result in severe penalties.

### The Status Quo: Drowning in Documentation

Currently, Indian professionals tackle this challenge through:

1. **Expensive subscriptions** to legal databases like SCC Online or Taxmann
2. **Massive physical reference books** that quickly become outdated
3. **Scattered online forums** where advice varies in quality and accuracy
4. **PDF searches** that return hundreds of irrelevant results
5. **Consultations with specialists** that cost thousands of rupees per hour
 
One CA from a Big Four firm admitted spending over 20 hours weekly just researching and interpreting various sections of the Act.

Small businesses suffer the most. Without dedicated legal teams, many entrepreneurs either overpay for professional services or risk non-compliance. As one startup founder in Pune told me, "I'm building a tech product, not studying law. Yet I spend more time understanding compliance than developing my actual business."

## The Solution: Gen AI-Powered Companies Act Assistant

My project leverages Gen AI to build an interactive assistant that demystifies the Companies Act for Indian CAs and businesses. The assistant provides **precise, contextual, and up-to-date information** drawn directly from the Act, using advanced language models and retrieval techniques.

### Core Features

1. **Conversational Q&A:** Users can ask natural language questions like “What is the procedure for increasing share capital under the Companies Act?” and get clear, section-wise answers.
2. **Section Summarization:** The assistant can summarize lengthy sections into plain English, tailored for non-lawyers.
3. **Compliance Checklists:** Generate step-by-step checklists for specific compliance actions (e.g., “Checklist for annual return filing”).
4. **Document Retrieval:** Find relevant sections, schedules, or rules instantly using semantic and keyword search.

---

## Gen AI Capabilities Demonstrated

The solution integrates at least three Gen AI capabilities covered in the course:

- **Document Understanding & Summarization:** The model parses complex legal text and produces concise, actionable summaries.
- **Retrieval-Augmented Generation (RAG):** Combines a vector database (for semantic search) with generative models to ground answers in the Companies Act’s actual text.
- **Few-shot Prompting:** Provides context-aware answers by showing the model how to handle legal queries with relevant examples.
- **(Bonus) Structured Output:** Delivers checklists and compliance steps in JSON or tabular format for easy integration with other tools.

---

## Implementation Details

The assistant is implemented as an interactive Jupyter Notebook using Python, the Gemini 2.0 (for LLMs), and vector search libraries like FAISS or ChromaDB. The Companies Act text is chunked semantically and indexed to allow efficient semantic retrieval.

## Limitations & Future Directions

**Limitations:**
- The assistant’s accuracy depends on the quality and completeness of the Companies Act data ingested.
- Complex legal interpretations or state-specific rules may not be fully captured.
- Requires regular updates as the Act is amended.

**Future possibilities:**
- Integrate with government APIs for real-time compliance updates.
- Expand coverage to other Indian laws (e.g., GST Act, Income Tax Act).
- Provide multi-language support for regional access.

---

## Impact

By leveraging Gen AI, this project aims to democratize access to legal compliance for Indian businesses and professionals. It reduces the cognitive load of navigating dense legalese, minimizes compliance risks, and empowers users to make informed decisions with confidence.

---

## Try It Yourself

Check out the [Kaggle Notebook](#https://www.kaggle.com/code/kingchanana/capstone-project?scriptVersionId=234828470) for code, demos, and to interact with the Companies Act Assistant yourself!

---

## Citation

Addison Howard, Brenda Flynn, Myles O'Neill, Nate, and Polong Lin. Gen AI Intensive Course Capstone 2025Q1. https://kaggle.com/competitions/gen-ai-intensive-course-capstone-2025q1, 2025. Kaggle.

---

*Empowering Indian CAs and companies — one AI answer at a time.*
