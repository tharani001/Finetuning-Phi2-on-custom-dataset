# 🚀 Phi-2 Fine-Tuning on Amazon Product Data

### Overview  
This project fine-tunes Microsoft’s Phi-2 (1.55B parameters) model to:  
- Tokenize and preprocess Amazon product data with an optimal max token length of 500  
- Use QLoRA to fine-tune the model efficiently, training only ~1.69% (~26M) of total parameters  
- Merge fine-tuned weights back into the Phi-2 base model  
- Generate high-quality product names and descriptions from Amazon product categories  

---

### 🧩 Key Features  
💡 Optimal data prep with token length tuning for efficient training  
⚡ Low-resource fine-tuning using QLoRA with 4-bit quantization  
🔄 Merge fine-tuned parameters seamlessly with the base model  
🛍️ Generate domain-specific product descriptions and titles  

---

### 🛠️ Tech Stack  
- Model: Microsoft Phi-2 (1.55B params) with QLoRA  
- Frameworks: Hugging Face Transformers, PEFT, Accelerate  
- Dataset: Custom Amazon product category data  
- Training: Efficient tokenization and low-parameter fine-tuning  

---
