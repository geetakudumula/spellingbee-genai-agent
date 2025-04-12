# 🐝 Spelling Bee Quiz Agent — DigitalOcean GenAI

A personalized spelling bee tutor built using DigitalOcean’s GenAI platform and Llama 3.3 Instruct (70B). This project helps quiz students from a 1000-word spelling list—ordered from toughest to easiest—while optionally giving definitions, origins, and sentence usage.

---

## 🚀 Features

- ✅ Ingests and indexes a 1000-word `.xlsx` list using OpenSearch
- ✅ Quizzes 5 spelling words per round
- ✅ Progresses from hardest to easiest
- ✅ Provides definitions, origin, and usage (on request)
- ✅ Vocabulary-only quiz mode available
- ✅ Tested in GenAI Playground with real-time prompt execution

---

## 🧰 Tech Stack

| Component            | Stack                      |
|---------------------|----------------------------|
| Cloud Platform       | [DigitalOcean GenAI](https://cloud.digitalocean.com/) |
| Model                | Llama 3.3 Instruct (70B)   |
| Vector Indexing      | OpenSearch Database        |
| Knowledge Base       | Excel (.xlsx) word list    |
| Prompt Execution     | GenAI Playground           |

---

## 📂 Project Structure


# 🧠 Spelling Bee Quiz Agent — Powered by DigitalOcean GenAI

A custom GenAI agent built on DigitalOcean's GenAI platform that quizzes spelling bee students from a curated 1000-word list. Designed for educational use, this agent adapts to the child's progress and quizzes from hardest to easiest words.

## 🚀 Features

- Loads domain-specific knowledge from a 1000-word `.xlsx` file
- Quizzes 5 hard words per round and progressively eases the difficulty
- Offers definitions, language of origin, and usage in sentence (on request)
- Optionally tracks correctness and gives feedback per round
- Switches to vocabulary-based quiz mode when asked

## 🧰 Tech Stack

- **DigitalOcean GenAI Platform**
- **Llama 3.3 Instruct (70B)**
- **OpenSearch Vector Indexing**
- Knowledge Base from `.xlsx` file
- (Optional) Public endpoint for frontend/web embedding

## 🗂️ Folder Structure

```bash
📁 spellingbee-genai-agent
│
├── 📄 README.md
├── 📄 instructions.txt       # Agent prompt instructions
├── 📊 2025R02SSB_Praveen.xlsx  # Spelling word list
└── 💡 playground_tests.md    # Sample prompt tests

```

