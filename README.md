# Case 25 – Real-Time Healthcare Facility Disruption Chatbot (Halifax, NS)

This project uses the Ollama + AnythingLLM stack to create a domain-specific chatbot that helps users in Halifax, Nova Scotia, navigate real-time healthcare facility disruptions. The chatbot provides updates on closures, service interruptions, and alternative urgent care locations.

⚠️ **Disclaimer: This chatbot does NOT provide medical diagnoses or treatment advice.**  
It is intended strictly for educational and research use only.

---

## 🔧 Project Structure

```
📂 /case-25---real-time-healthcare-facility-disruption/chatbox
├─ knowledge_base/
│  ├─ knowledge_document_1.pdf         # Real-time facility status
│  ├─ knowledge_document_2.md          # Weather and road access
│  └─ knowledge_document_3.txt         # Local care options near landmarks
├─ prompt/
│  └─ system_prompt.txt                # Chatbot behavior, tone, scope, disclaimers
├─ documentation/
│  └─ case-25---real-time-healthcare-facility-disruption.md  # Provided scenario file
│  └─ use_case_description.md          # User pain points and success criteria
├─ demo/
│  └─ LLM-Video.mp4                    # 1–1.5 minute walkthrough video
└─ README.md                           # This file
```

---

## 📌 How to Use

### Local Deployment Instructions

1. **Install Ollama**  
   Download and run a local LLM like `llama3` or `mistral`.  
   https://ollama.com

2. **Install AnythingLLM**  
   Follow instructions from [https://docs.anythingllm.com](https://docs.anythingllm.com)  
   Set up the UI, upload documents from `/knowledge_base`, and apply the system prompt from `/prompt/system_prompt.txt`.

3. **Start Testing**  
   Try questions such as:
   - “Are there any emergency room closures in Halifax tonight?”
   - “What urgent care is open near Halifax Shopping Centre?”
   - “Any road issues that affect getting to QEII?”

---

## 👩‍💻 Authors

- Project Author: Rachel Li  
- Date: July 31, 2025  
- For: MBAN SMU

---

## ⚠ Legal & Ethical Notes

- This project is **strictly for academic research and demonstration use.**
- It must **not** be used to provide medical diagnosis or treatment.
- The chatbot includes guidance to contact **911 or 811** in the event of serious symptoms.

---

## 📎 License

Open source for educational use only. See LICENSE (if applicable).
