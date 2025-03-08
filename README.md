## Ingredient-Based Recipe Finder  

### Overview  
This project is a **Text-Based Information Retrieval System** that allows users to find the **best recipes** based on the ingredients they provide. Using **TF-IDF Vectorization** and **Cosine Similarity**, the system efficiently retrieves the **Top 5 most relevant recipes** from a dataset of **2 million recipes (RecipeNLG)**.  

### 📊 Methodology  

#### **1️⃣ Data Preprocessing**
- **Stopword Removal** (recipe-specific)  
- **Normalization & Tokenization**  
- **Removing Punctuation & Numbers**  

#### **2️⃣ Feature Extraction**
- **TF-IDF Vectorization** to represent ingredients as feature vectors  
- **Cosine Similarity** to measure similarity between input ingredients and recipe ingredients  

#### **3️⃣ Recipe Retrieval**
- Computes similarity scores and ranks the **Top 5 most relevant recipes**  
- Displays **recipe names, ingredients, directions, and URLs**  

#### **4️⃣ Additional Features**
- **Text-to-Image Synthesis** 🎨 (Stable Diffusion)  
- **ChatGPT Verification** 🤖  

### 📂 Dataset  
- **RecipeNLG Dataset** (2M cooking recipes)  
- Columns: **Recipe Name, Ingredients, Directions, Recipe URL**  

### 🛠️ Technologies Used  
- **Python** (Pandas, NumPy, SciPy, Scikit-learn)  
- **Natural Language Processing (NLP)** (TF-IDF, Cosine Similarity)  
- **Stable Diffusion** for text-to-image synthesis  
- **ChatGPT API** for recipe verification  

### 🚀 Future Scope  
- **Enhancing image generation quality**  
- **Building a user-friendly web interface**  
- **Integrating voice-based search for recipe lookup**  

---
