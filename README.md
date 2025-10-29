# 🌍 AI CAPSTONE PROJECT — DEEP LEARNING FOR SATELLITE IMAGE CLASSIFICATION  

## 🧠 OVERVIEW  

This **AI Capstone Project** is an exciting hands-on journey into **Deep Learning for Image Classification**, specifically applied to **satellite imagery**.  

Imagine you're a **Data Scientist** for a fertilizer company aiming to expand into new territory. Your mission is to build **AI models** that automatically classify images into **AGRICULTURAL** and **NON-AGRICULTURAL** land.  

This automation saves time and effort compared to manual classification and helps the company design efficient strategies.  

---

## 🚀 PROJECT STRUCTURE  

The project was divided into **FOUR MODULES**, each one increasing in complexity — from basic data handling to advanced neural network architectures and Vision Transformers (ViTs).  

Dataset structure:  

- `class_0_non_agri/` → Non-Agricultural Land  
- `class_1_agri/` → Agricultural Land  

The objective: **Binary Classification** — determine whether an image shows agricultural or non-agricultural land.  

All experiments were conducted using **Jupyter Notebooks** for interactivity and visualization.  

---

## 📚 MODULE BREAKDOWN  

### 🧩 MODULE 1: DATA PREPARATION AND EXPLORATION  

The foundation of any AI project is **data**.  

- Loaded and explored satellite images efficiently.  
- Implemented **lazy loading** for optimal memory management.  
- Prepared **balanced datasets** (equal agri and non-agri samples).  
- Applied **image preprocessing** and **augmentation** (resizing to 64×64 pixels).  

🔍 **Outcome:** A clean, balanced, and memory-efficient dataset ready for deep learning.  

---

### ⚙️ MODULE 2: BUILDING AND COMPARING BASIC CLASSIFIERS  

This module introduced **Convolutional Neural Networks (CNNs)** — the workhorses of image AI.  

#### ✅ KERAS IMPLEMENTATION  

Keras made it simple to:  
- Define **convolutional**, **pooling**, and **dense** layers.  
- Use the **Adam** optimizer and **binary cross-entropy** loss.  
- Evaluate using **accuracy** and **confusion matrices**.  

Training involved DataLoaders, optimizers, and mini-batch iteration loops.

📊 Result:

Both models achieved >95% accuracy.

Keras = faster prototyping.

PyTorch = greater flexibility and debugging control.

### 🧬 MODULE 3: ADVANCED MODELS WITH VISION TRANSFORMERS (VITs)

A leap forward into Vision Transformers (ViTs), inspired by transformer architectures used in NLP models like GPT.

ViTs treat images as sequences of patches, applying self-attention to learn global relationships.

Implemented using Keras layers such as:
