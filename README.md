# **GenEffllux**

![Grad-CAM or Cosine Similarity Plot](https://github.com/mhb1717/efflux/blob/main/Group%2080%20(1).png?raw=true)

**GenEffllux** is a deep learning-based pipeline designed to generate and analyze protein sequences related to efflux mechanisms using fine-tuned ProtGPT2, multi-scale feature extraction, and mCNN architectures.

---

## **🚀 Quick Start**

### **Step 1: Generate Data Features**  
Navigate to the `data` folder and use your FASTA file to generate feature representations. Outputs are saved in the `dataset` folder.

---

### **Step 2: Fine-Tuning ProtGPT2**  
Use `ProtGPT_Model_tuning.ipynb` to fine-tune the ProtGPT2 model on your custom protein data.

---

### **Step 3: Generation of Protein Sequences for Efflux**  
Use the notebook `Proten_Sequence_Generation.ipynb` to generate synthetic efflux-related protein sequences using the fine-tuned model.

---

### **Step 4: PSSM of Efflux Proteins**  
Compute Position-Specific Scoring Matrix (PSSM) features from the generated or collected protein sequences for downstream learning tasks.

---

### **Step 5: Create a Multi-scale Windows mCNN Input**  
Use a sliding window approach to create multi-scale input data for the mCNN model.

**Example script:**

