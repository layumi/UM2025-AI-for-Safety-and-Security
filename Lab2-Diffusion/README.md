# 🖥️ Lab Manual: Generative Visual Forensics with Stable Diffusion

## 🎯 Objectives
- Learn how to use **Stable Diffusion** models for forensic-inspired tasks.  
- Explore **prompt engineering** for generating:  
  1. Age-progressed suspect images  
  2. Enhanced low-quality surveillance frames  
  3. Sketches of reconstructed crime scenes  
- Understand how **positive and negative prompts** affect image quality.  
- Compare outputs across different diffusion models (2.1, XL, 3.5).  

---

## 🔧 Preparation
1. Access to any Stable Diffusion API or demo:  
   - [Stable Diffusion 2.1 (Hugging Face)](https://huggingface.co/stabilityai/stable-diffusion-2)  
   - [Stable Diffusion 2.1 Demo (DeepInfra)](https://deepinfra.com/stabilityai/stable-diffusion-2-1)  
   - [Stable Diffusion-XL](https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0)  
   - [Stable Diffusion 3.5 Medium](https://huggingface.co/spaces/stabilityai/stable-diffusion-3.5-medium)  
   - [Optional: Flux on CivitAI](https://civitai.com/generate)  
   - [Optional: StableDiffusion.fr](https://stablediffusion.fr/txt2img)  

2. Background references:  
   - [Blog: Stable Diffusion 1 vs 2](https://www.assemblyai.com/blog/stable-diffusion-1-vs-2-what-you-need-to-know/)  
   - [Video tutorial](https://www.youtube.com/watch?v=gILYw4spk8U)  

---

## 📝 Tasks

### Task 1: Age Progression of Suspects
- **Prompt Example:**  
  > "A realistic portrait of a young male suspect, age 20, in police mugshot style, neutral background."  
  > "The same suspect, but age 50, wrinkles, grey hair, realistic style."  

- **Objective:**  
  Observe how Stable Diffusion can simulate **age progression/regression** using descriptive prompts.  

- **Variation:**  
  Try adding modifiers like *high fidelity*, *ultra-detailed*, or *4K*.  

---

### Task 2: Surveillance Image Enhancement
- **Prompt Example:**  
  > "Enhance this blurry CCTV frame of a person entering a store, clear face, sharp details, photorealistic."  

- **Negative Prompt Example:**  
  > "bad composition, mutated body parts, blurry image, disfigured, oversaturated, bad anatomy, overexposure"  

- **Objective:**  
  Learn how **negative prompts** improve quality by reducing unwanted artifacts.  

- **Experiment:**  
  Compare the results with and without negative prompts.  

---

### Task 3: 3D Crime Scene Sketch Generation
- **Prompt Example:**  
  > "A rough 3D sketch of a crime scene inside a living room, showing furniture, broken glass on the floor, cinematic lighting."  

- **Variation:**  
  > "3D wireframe crime scene sketch, forensic visualization style, monochrome."  

- **Objective:**  
  Understand how diffusion models can be used for **conceptual reconstructions** when only textual descriptions are available.  

---

## ⚖️ Model Comparison
- Run the same prompt across:  
  - **Stable Diffusion 2.1**  
  - **Stable Diffusion XL**  
  - **Stable Diffusion 3.5**  

- **Observe:**  
  - Which model produces the most realistic human faces?  
  - Which model better handles **details** (e.g., wrinkles, facial features, crime scene objects)?  
  - Which model introduces fewer artifacts?  

---

## 📊 Lab Report Requirements
Each group should submit a short report (2–3 pages) including:  
1. Screenshots of inputs (prompts) and outputs (images).  
2. A **comparison table** of models (2.1, XL, 3.5).  
3. Notes on the effect of **positive modifiers** (e.g., “high-fidelity”, “4K”) and **negative prompts**.  
4. Reflection: What are the **forensic limitations and ethical risks** of using generative AI in this context?  

---

## ⚠️ Notes
- **Fictional only:** All generated content is for **educational purposes**. Do not use real suspects or confidential case materials.  
- **Ethics:** Be aware that generated images may create **false impressions**; they cannot be considered evidence.  
- **Exploration encouraged:** Try creative prompts like *steampunk*, *cyberpunk*, or *sketchbook style* to see how models handle imagination beyond reality.  

---
