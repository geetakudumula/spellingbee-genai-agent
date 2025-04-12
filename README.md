# 🐝 Spelling Bee Quiz Agent — Powered By DigitalOcean GenAI

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
```bash
📁 spellingbee-genai-agent
│
├── 📄 README.md
├── 📄 instructions.txt       # Agent prompt instructions
├── 📊 1000_spellings.xlsx  # Spelling word list
└── 💡 playground_tests.md    # Sample prompt tests

```

<img width="942" alt="image" src="https://github.com/user-attachments/assets/7d6a9486-785c-4af3-9723-26f1f4dc12ef" />

<img width="529" alt="image" src="https://github.com/user-attachments/assets/05b02d87-32d9-44c3-972f-01e2ba299b4e" />



