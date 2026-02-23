# KnowLabel

🧠 KnowLabel – Hybrid AI Ingredient Intelligence System

KnowLabel is a hybrid AI-powered ingredient classification system that labels over 1,000+ food, skincare, and haircare ingredients as Healthy or Unhealthy using supervised machine learning.

To enhance robustness, the system integrates a Llama-based Large Language Model (LLM) that generates intelligent, context-aware responses for ingredients not present in the training dataset — reducing out-of-vocabulary limitations and improving user experience.

🚀 Highlights

Built a supervised ML classifier for multi-domain ingredient health evaluation

Curated and structured a 1,000+ ingredient dataset

Integrated a Llama-based LLM for unseen ingredient handling

Designed a hybrid architecture combining predictive ML + generative AI

Implemented NLP preprocessing and feature engineering

🛠 Tech Stack

Python · Scikit-learn · Pandas · NumPy · NLP · Llama-based LLM

⚙️ How It Works

The application loads a curated dataset of 1,200+ ingredients.

Users enter one or multiple ingredient names in the input field.

When Analyze Ingredients is clicked:

🔎 If the ingredient exists in the dataset:
The system retrieves stored information and displays its classification (Healthy / Unhealthy).

🤖 If the ingredient is not found:
The query is automatically routed to a locally running Llama 3.2 model, which generates a contextual health explanation.

This fallback mechanism ensures:

->No null responses

->Better user experience

->Intelligent handling of unseen inputs

🏗 System Architecture

Dataset → ML Classification →
If Not Found → Llama 3.2 (Local) → Generated Explanation → UI Display

💡 Innovation

Unlike traditional classifiers that fail on unseen inputs, KnowLabel intelligently escalates unknown ingredients to an LLM layer, demonstrating creative AI integration and practical AI system design.
