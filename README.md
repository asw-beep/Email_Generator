# AI Email Generation with Mistral-7B ✉️🤖

An AI-powered email generation system fine-tuned on **Mistral-7B-Instruct-v0.2** to produce professional, context-aware emails.  
The model is optimized using **QLoRA and PEFT**, enabling efficient fine-tuning on limited GPU resources and deployed via an interactive **Gradio** interface.

> ⚠️ This project is designed to run on **Google Colab**. The full pipeline executes from a single notebook.

---

## 🔍 Problem Statement

Writing clear, professional emails (cold emails, formal requests, follow-ups) requires time, structure, and tone awareness.  
Generic language models often lack domain-specific tuning for professional communication.

This project addresses that gap by:
- Fine-tuning a large language model specifically for professional email generation
- Optimizing training efficiency for constrained hardware
- Providing an easy-to-use interactive interface

---

## ✨ Key Features

- 🧠 Fine-tuned **Mistral-7B-Instruct-v0.2** for email generation  
- ⚡ Efficient training using **QLoRA + PEFT (LoRA adapters)**  
- ✍️ Context-aware, structured professional emails  
- 🎛️ Interactive **Gradio web application**  
- ⏱️ Generates coherent emails in **under 8 seconds**

---

## 🛠️ Tech Stack

- **Python**
- **PyTorch**
- **Hugging Face Transformers**
- **PEFT (LoRA, QLoRA)**
- **Mistral-7B-Instruct-v0.2**
- **Gradio**
- **Google Colab**

---

## 🧠 Model & Training Details

- **Base Model:** Mistral-7B-Instruct-v0.2  
- **Fine-Tuning Method:** QLoRA with PEFT  
- **LoRA Target Modules:** `q_proj`, `v_proj`  
- **Dataset:**  
  - Custom-curated dataset with **50+ context–response pairs**  
  - Simulates realistic professional email communication scenarios  
- **Training Objective:**  
  - Improve relevance, tone, and structure for professional emails  
  - Maintain efficiency under limited GPU constraints  

This setup allows large-model fine-tuning without full parameter updates, significantly reducing memory usage.

---

## 🚀 How to Run the Project

### 👉 Run on Google Colab (Recommended)

1. Open the notebook in Colab:
   
   👉 **[Open in Google Colab](https://colab.research.google.com/drive/1CESdm7dxOUVeue88TaUkPc8aIX4_ke-z)**

2. Run all cells from top to bottom  
   (`Runtime → Run all`)

3. Launch the **Gradio interface** from the final cell.

4. Enter email context and requirements to generate a professional email draft.

> ⚠️ The entire notebook must be executed for the Gradio app to work correctly.

---

## 🧪 Sample Use Cases

- Internship and job cold emails  
- Formal academic or professional requests  
- Follow-up and escalation emails  
- Business communication drafts  

---

## 📌 Project Highlights (For Recruiters)

- Fine-tuned a **7B parameter LLM** using efficient adaptation techniques  
- Practical application of **LLMs in professional communication**  
- Hands-on experience with **QLoRA, PEFT, and LoRA adapters**  
- End-to-end pipeline (**data → fine-tuning → deployment**)  
- Clean, **reproducible notebook-based workflow**

---

## 📈 Future Improvements

- Expand dataset size for broader email styles  
- Multi-tone support (formal, semi-formal, casual)  
- Email intent classification and prompt routing  
- Deployment as a **standalone production web application**

---

## 👤 Author

**Aswin M**  
AI / ML Enthusiast | Undergraduate Computer Science Student  

🔗 GitHub: https://github.com/asw-beep  

---

## 📄 License

This project is open-source and available under the **MIT License**.

