
# SURGE: Exploring LLMs, Detection, and GAN-Augmented Models

> A SURGE through the world of large language models (LLMs), text-detection, and GAN-based attention methods.

**Repository:** https://github.com/HARSHITJAIS14/SURGE

---

## 🗂️ Repository Structure

```

harshitjais14-surge/
├── README.md
├── Week1/
│   └── LLMIntro-2024-07-22-1743.excalidraw
├── Week2/
│   └── Code/
│       ├── mpi.ipynb
│       └── mpi\_120.csv
├── Week3/
│   └── LLMTextDetectionSurvey.pdf
├── Week4/
│   ├── bert-pretrainingdetector.ipynb
│   ├── description.md
│   └── merged\_dataset.csv
├── Week6/
│   ├── gan-detection.ipynb
│   └── gan\_bertattention.ipynb
└── Week7/
└── GANBERT\_pytorch.ipynb

````

---

## 📖 Week-by-Week Summary
### Week 1: Introduction to LLMs  
In Week 1, we dove into the fundamentals and workflow of large language models—from pretraining to supervised fine-tuning, and finally to reinforcement learning (including RLHF). Along the way, we covered key concepts such as base architectures, dataset creation, instruction tuning, and common pitfalls like hallucinations. We also did a hands-on quickstart with the OpenAI API.

**Topics Covered:**
- LLM architecture & pretraining stages  
- Supervised Fine-Tuning (SFT)  
- Reinforcement Learning & RLHF  
- Prompting basics  
- Hallucination in LLMs  
- OpenAI API usage  

**Resources:**
1. [Busy Person's Intro to LLMs (YouTube)](https://youtu.be/zjkBMFhNj_g?si=EEgU8appT5EwWb9n)  
2. [Deep Dive into LLMs (YouTube)](https://youtu.be/7xTGNNLPyMI?si=4T-RtDVmZLvDNrjM)  
3. [Basics of Prompting (YouTube)](https://youtu.be/1Faf1cTe3T8?si=aKsLxljDJJGr5s-e)  
4. [OpenAI API Quickstart Guide](https://platform.openai.com/docs/quickstart)  

**Artifacts:**
- Diagrammed workflow in Excalidraw: `Week1/LLMIntro-2024-07-22-1743.excalidraw`


### Week 2: MPI Personality Evaluation  
- Implemented a **Machine Personality Inventory** tool using **Big Five Personality Factors (OCEAN)** for assessment of ChatGPT model on text data.  
- Notebook [`mpi.ipynb`](Week2/Code/mpi.ipynb) walks through data preprocessing, feature extraction, and personality inference.  
- Dataset sample in `mpi_120.csv`.

### Week 3: Survey on LLM Text Detection  
- Read a literature survey of **LLM text-detection** approaches (PDF in Week3) which gave a full view over the works done over LLM Text Detection till 2023.  
- Summarized methods, benchmarks, and open challenges in a concise report and added it to the merged pdf.

### Week 4: BERT-Based Pretraining Detector  
- Developed a detector to distinguish pretrained vs. fine-tuned text using **BERT**.  
- Notebook [`bert-pretrainingdetector.ipynb`](Week4/bert-pretrainingdetector.ipynb) includes model training and evaluation.  
- `merged_dataset.csv` is a smaller version of the CHEAT dataset; `description.md` details dataset construction.
### Week 5: Exploring Datasets
- Learnt about a lot of dataset for LLM Text Detection and listed some of the major datasets and their papers in the [Week5 Directory](Week5/).

### Week 6: GAN-Based Detection & Attention  
- Explored **GAN-based methods** for generating and detecting synthetic text/images.  
- [`gan-detection.ipynb`](Week6/gan-detection.ipynb) builds a basic GAN over word co-occurence matrix as shown in the pdf of the research paper [gan_detection_compressed.pdf](Week7/gan_detection_compressed.pdf) for adversarial examples.  
- [`gan_bertattention.ipynb`](Week6/gan_bertattention.ipynb) adds a BERT-attention module to enhance detection robustness.

### Week 7: GAN-BERT in PyTorch  
- Full PyTorch implementation of [**GANBERT**](Week7/ganbertacl.pdf) paper: integrating GAN-generated data into BERT training loops.  
- Notebook [`GANBERT_pytorch.ipynb`](Week7/GANBERT_pytorch.ipynb) demonstrates training and performance analysis over the short version of RAID dataset.

---
