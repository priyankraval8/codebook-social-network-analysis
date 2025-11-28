# CodeBook — Social Network Data Analysis Project (Pure Python)

This project is part of my Data Science Journey. 
The goal is to analyse raw social-network data, clean it, and build recommendation features using only **pure Python** (no pandas, no NumPy).

---

## 🚀 Project Features

### ✔ 1. Load & Explore Data  
- Read JSON file  
- Print users, their friends, and liked pages  

### ✔ 2. Data Cleaning  
Tasks performed:  
- Removed users with missing names  
- Removed duplicate friends  
- Removed inactive users  
- Deduplicated page IDs  
- Saved cleaned dataset

### ✔ 3. People You May Know  
Algorithm:  
- If two users share mutual friends → recommend them  
- More mutual friends = higher priority  

Example:  
Amit → should connect with Sara (mutual friend: Priya)

### ✔ 4. Pages You Might Like  
Collaborative filtering logic:  
- Users who like similar pages → may like more similar pages  
- Recommend pages liked by similar users  

Example:  
If Amit & Priya like “AI World”, recommend “Data Science Daily”.

---

## 🧪 How to Run  
Just open the notebooks in Jupyter Notebook:

Run them in order:  
**01 → 02 → 03 → 04**

---

## 🛠 Skills Demonstrated  
- Python (without external libraries)  
- JSON data processing  
- Data cleaning  
- Recommendation algorithms  
- Jupyter Notebook workflow  

---

## 📞 Contact  
**Priyank Raval**  
Email: priyankraval322@gmail.com  
  
