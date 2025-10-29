🌍 AI Capstone Project — Deep Learning for Satellite Image Classification
🧠 Overview

This AI Capstone Project is an exciting hands-on journey into deep learning for image classification, specifically applied to satellite imagery.

Imagine you're a data scientist for a fertilizer company aiming to expand into new territory. Your mission is to build AI models that automatically classify images into agricultural and non-agricultural land.

This automation saves time and effort compared to manual classification and helps the company design efficient strategies.

🚀 Project Structure

The project was structured into four modules, each building upon the previous one — from basic data handling to advanced neural networks and transformers.
You worked with a dataset of satellite images organized into folders:

class_0_non_agri/ → Non-agricultural land

class_1_agri/ → Agricultural land

The goal: binary classification — determine whether an image shows agricultural or non-agricultural land.

All experiments were conducted using Jupyter Notebooks, making the project interactive and visual.

📚 Module Breakdown
🧩 Module 1: Data Preparation and Exploration

The foundation of any AI project is data.

Loaded and explored satellite images efficiently.

Implemented lazy loading to manage memory effectively.

Prepared balanced datasets for fair training.

Applied image preprocessing and augmentation (resizing to 64×64 pixels).

🔍 Outcome: A clean, memory-efficient dataset ready for deep learning.

⚙️ Module 2: Building and Comparing Basic Classifiers

This module introduced Convolutional Neural Networks (CNNs) — the backbone of image AI.

✅ Keras Implementation

Keras made it easy to:

Define convolutional, pooling, and dense layers.

Use Adam optimizer and binary cross-entropy loss.

Evaluate using accuracy and confusion matrices.

🔧 PyTorch Implementation

PyTorch offered more flexibility:
