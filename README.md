# 🤖 Multimodal AI: Visual Question Answering using `dandelin/vilt-b32-finetuned-vqa`

This project demonstrates a **Visual Question Answering (VQA)** system powered by the pre-trained **ViLT (Vision-Language Transformer)** model from Hugging Face.  
You can upload an image and ask natural language questions such as:  

> “How many people are in this picture?”  
> “What color is the car?”  
> “Is it daytime or nighttime?”  

The model analyzes both the image and your question to generate an accurate answer — bridging the gap between computer vision and natural language understanding.

---

## 🧠 Model Overview

**Model Used:** [`dandelin/vilt-b32-finetuned-vqa`](https://huggingface.co/dandelin/vilt-b32-finetuned-vqa)  

ViLT (Vision-and-Language Transformer) is a multimodal transformer architecture that processes both **image patches** and **text tokens** jointly without requiring convolutional or region-based feature extractors (like CNNs).  

It has been **fine-tuned for the VQA (Visual Question Answering)** task, meaning it can interpret a question about an image and generate a relevant answer.
