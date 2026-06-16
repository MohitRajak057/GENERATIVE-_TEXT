# 🤖 Task 4 — Generative Text Model
### CODTECH IT Solutions Pvt. Ltd. | AI Internship

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)
![Transformers](https://img.shields.io/badge/HuggingFace-Transformers-yellow?style=for-the-badge&logo=huggingface)
![GPT-2](https://img.shields.io/badge/Model-GPT--2-green?style=for-the-badge)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

---

## 📌 Objective

Build a **Text Generation Model** using a GPT-2 Transformer to generate coherent, topic-specific paragraphs based on user-provided prompts — with no API key or internet access required at runtime.

---

## 🧠 Model Used — GPT-2 (Hugging Face)

| Property | Detail |
|---|---|
| Model | GPT-2 Small |
| Parameters | ~117 Million |
| Type | Decoder-only Transformer (GPT-style) |
| Source | Hugging Face `transformers` library |
| Training | Pre-trained on WebText (~40GB web data) |

> GPT-2 was chosen over LSTM because it produces significantly more coherent and human-like text, especially for diverse topics, without needing custom training data.

---

## 📂 Repository Structure

```
task4-generative-text-model/
│
├── task4_generative_text_model.ipynb   ← Main notebook (all code here)
└── README.md                           ← This file
```

---

## 🔬 What the Notebook Does

| Step | Description |
|---|---|
| Step 1 | Install `transformers` and `torch` |
| Step 2 | Import all required libraries |
| Step 3 | Load pre-trained GPT-2 model & tokenizer |
| Step 4 | Define `generate_text()` function with sampling parameters |
| Step 5 | Generate text on **5 different topics** (2 outputs each) |
| Step 6 | Interactive generator — works with any custom prompt |
| Step 7 | Temperature comparison — how parameters affect output |
| Step 8 | Summary of findings |

---

## 🌐 Topics Demonstrated

- 🧠 Artificial Intelligence
- 🌍 Climate Change  
- 🚀 Space Exploration
- 💻 Computer Science & Programming
- 🏥 Healthcare & Medicine

---

## ⚙️ Key Generation Parameters

| Parameter | Value | Effect |
|---|---|---|
| `temperature` | 0.85 | Balances creativity vs coherence |
| `top_k` | 50 | Considers top 50 likely next tokens |
| `top_p` | 0.92 | Nucleus sampling — dynamic vocab filtering |
| `no_repeat_ngram_size` | 3 | Prevents repetitive phrases |
| `max_length` | 180 | Generates ~3–4 sentences per prompt |

---

## ▶️ How to Run

1. Open `task4_generative_text_model.ipynb` in **Google Colab** or **Jupyter Notebook**
2. Run **all cells** from top to bottom
3. GPT-2 will download automatically (~500MB) on first run
4. To generate your own text — edit `my_prompt` in **Step 6**

---

## 📊 Key Findings

- **Low temperature (0.4)** → Focused, predictable, repetitive-safe text  
- **Medium temperature (0.85)** → Best balance of coherence + variety  
- **High temperature (1.2)** → Creative but sometimes off-topic  
- GPT-2 generates convincing paragraphs even **without domain fine-tuning**

---

## 👨‍💻 Intern Details

| Field | Info |
|---|---|
| **Name** | Ritesh |
| **GitHub** | [@riteshcoder02](https://github.com/riteshcoder02) |
| **Company** | CODTECH IT Solutions Pvt. Ltd. |
| **Domain** | Artificial Intelligence |
| **Task** | Task 4 — Generative Text Model |

---

*© 2024 Ritesh | CODTECH IT Solutions Pvt. Ltd. — AI Internship*
