# AI-Peer-Review-Assistant

An AI-powered academic writing and peer review assistant designed to improve clarity, structure, and quality of research papers by providing automated feedback, rewriting suggestions, and sentiment-aware analysis.

---

## 📌 Overview

The AI Peer Review Assistant enhances academic and formal writing by correcting grammatical and stylistic issues, refining wording, and generating constructive feedback. It analyzes research paper sections to identify potential weaknesses and produces professional, reviewer-style suggestions aligned with academic standards.

The system is trained on real peer review data, enabling it to mimic human reviewer behavior and guide authors toward higher-quality submissions.

---

## 🛠 Tools & Technologies

- **BERT (Bidirectional Encoder Representations from Transformers)**  
  Used to analyze and classify academic text, identifying weak or problematic sections such as unclear methodologies or missing details.

- **T5 (Text-to-Text Transfer Transformer)**  
  Generates constructive feedback and rewriting suggestions in an academic tone.

- **GPT-2**  
  Supports creative rewriting and content enhancement.

- **Hugging Face Transformers**  
  For accessing and fine-tuning pre-trained NLP models.

- **NLTK**  
  Text preprocessing, tokenization, and stopword removal.

- **Streamlit**  
  Web-based user interface for interacting with the system.

- **Pyngrok**  
  Secure tunneling for sharing the local Streamlit app.

- **Dataset**  
  Peer review data from **OpenReview.net (ICLR)**, including research papers and reviewer comments.

---

## ⚙️ Methodology

1. **Dataset Collection**  
   Academic papers and reviewer feedback were collected from OpenReview (ICLR), focusing on papers with detailed critiques.

2. **Data Preprocessing**  
   Text cleaning, tokenization, and separation of paper sections and reviewer comments.

3. **Text Classification (BERT)**  
   Identifies sections likely to receive reviewer criticism.

4. **Feedback & Rewriting (T5 & GPT-2)**  
   Generates constructive feedback and improved rewritten text.

5. **Modular Model Design**  
   Dedicated models handle rewriting, summarization, sentiment analysis, and topic generation independently for higher accuracy.

---

## 📊 Sample Features

- Academic text rewriting
- Sentiment analysis
- Keyword extraction
- Constructive reviewer-style feedback
- Formal and professional tone enforcement

---

## ⚠️ Challenges

- Large model memory requirements
- Model loading failures due to resource limitations
- Limited support for non-text inputs (tables, images)

---

## 🚀 Future Work

- Integration of specialized academic language models
- Support for APA and MLA citation styles
- Multilingual academic writing support
- Real-time collaboration and cloud storage
- Mobile-friendly interface
- Hardware upgrades for faster processing

---

## ✅ Conclusion

This project demonstrates how NLP and machine learning can support researchers and students by automating peer review feedback and improving academic writing quality. The AI Peer Review Assistant bridges the gap between draft writing and submission-ready research papers.

---
