#  **Conv_GPT**  

Conv_GPT is a lightweight conversational AI model designed to facilitate persona-based interactions. Trained on the DailyDialog dataset, it aims to provide engaging and context-aware responses while delivering reasonably effective performance within its resource constraints.

---

#  **Deployment**
🔗 Deployed Link : **[Huggingface](https://huggingface.co/spaces/nnsohamnn/Conv_GPT)**

---

## 📌 **Features**  

✔️ **Trainable from scratch** (**≈89M parameters**)  
✔️ **Persona-based conversations**  
✔️ **Optimized training with mixed precision**   

---

## 📂 **Dataset**  

Conv_GPT is trained using the **[Daily Dialog Dataset](https://huggingface.co/datasets/li2017dailydialog/daily_dialog)**

---

##  **Training Results**  

### **Training Accuracy & Loss Graphs**  
Here’s the visualization of **training accuracy and loss**:  

![Training Accuracy Results](results.png)  

---

##  **Training Setup**  

- **Framework:** PyTorch  
- **GPU:** T4 (Colab)  
- **Model:** GPT-2 trained from scratch
- **Total Parameters:** **89M**    

### **Model Configuration**  
| Parameter       | Value  |
|----------------|--------|
| **Vocabulary Size** | `50257` |
| **Embedding Dimension** | `384` |
| **Number of Attention Heads** | `16` |
| **Number of Layers** | `12` |
| **Max Sequence Length** | `256` |
---

 

 

