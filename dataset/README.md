# ATCTM Dataset (Sample Release)

This folder contains sample data created for the **ATCTM (Adaptive Temporal-Contextual Transformer Model)**, designed for event-based depression detection using NLP.

## 📁 Files Included

- `atctm_dataset_sample.csv`  
  → Sample of 4,000+ user-generated texts with multi-task annotations including:  
  `TEXT`, `EVENT_TYPE`, `EVENT_GROUP`, `SENTIMENT_VALENCE`, `EMOTION`, `SARCASM`, `TENSE`, `CERTAINTY`, `GENERATED`

- `event_types_mapping.csv`  
  → Mapping of all `EVENT_TYPE` entries to their corresponding `EVENT_GROUP` (e.g., employment, relationship, health)

  ## 📦 Full Dataset (In Progress)

The complete ATCTM dataset currently contains over **100,000 annotated entries** across 500+ real-life event types.  
It includes multi-task labels for:
- `SENTIMENT_VALENCE`
- `EMOTION`
- `SARCASM`
- `TENSE`
- `CERTAINTY`

Due to its ongoing nature and quality review process, the full dataset is **not publicly available yet**, but a **sample version is provided** here for research/demo use.

For collaboration or access requests, please contact the author.

## 🎯 Dataset Purpose

The dataset is designed to train and evaluate NLP models for mental health detection by modeling a user’s emotional state based on:

- Real-life **event type** (e.g., got_fired, broke_bone)
- Associated **emotion**, **sentiment valence**, **tense**, **certainty**, and **sarcasm**
- Intended use in **multi-task classification**, **contextual user embeddings**, and **temporal modeling**

## ⚠️ Notes

- This is a **sample version** of the full dataset currently under development (~100K+ rows)
- Generated using human-in-the-loop prompting and manual curation; intended for **research use only**

## 📜 License

This dataset is licensed under [Creative Commons Attribution-NonCommercial 4.0](https://creativecommons.org/licenses/by-nc/4.0/).  
You may use, share, and adapt the data for **non-commercial research**, with proper credit.

## 📌 Citation

If used in academic work or demos, please cite:

> Prajapati, K. (2025). *ATCTM: Adaptive Temporal-Contextual Transformer for Depression Detection*.
