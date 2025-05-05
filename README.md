# Decoding Cognitive States from fMRI: Math vs. Story

## 📖 Overview
This project investigates how the brain shifts between **calculation** and **narrative comprehension** by analyzing task-based fMRI data from the Human Connectome Project. We ask:

> **What does the brain reveal about how we switch between a math‑based reasoning task and a story comprehension task?**

## 🧠 Dataset
- **Source:** Human Connectome Project  
- **Task:** Language paradigm with two conditions  
  - 📐 **Math reasoning**  
  - 📚 **Story comprehension**  
- **Parcellation:** 360 cortical regions of interest (ROIs)

## 🔬 Methods
1. **Preprocessing & Parcellation**  
   - Extraction of regional activation time series  
2. **Dimensionality Reduction**  
   - Techniques such as PCA to capture the most informative features  
3. **Classification**  
   - Train machine learning models to decode task condition  
   - Evaluate performance on held‑out data  

## 📊 Results
- Even after dimensionality reduction, **whole‑brain activation patterns** reliably distinguish math vs. story trials.  
- **Classification accuracy** significantly above chance, demonstrating separable, distributed networks for numerical reasoning and narrative understanding.

## 🔎 Conclusions
- **Distributed networks:** Numerical reasoning and narrative comprehension engage distinct but widespread cortical circuits.  
- **Parcel‑level decoding:** Functional signatures at the ROI level carry enough information for task classification.  
- **Implications:** Integrating computational modeling with neuroimaging offers a nuanced map of how key cognitive functions are organized across the cortex.

---

> **Future directions:** Explore cross‑task generalization and extend to other cognitive domains (e.g., attention, memory).
