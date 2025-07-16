# IRBasics-VectorSpaceProximity-Workshop

## 👥 Who Made This?

- Kapil Bhardwaj  
- Parag Shah  
- Preetpal Singh  

**Team 3**

---

## 📚 What’s This Project About?

This project is part of the **IR Basics & Vector Space Proximity Foundations Workshop** for the PROG8245 course.  
We built a full **NLP pipeline** from scratch and implemented six foundational concepts used in **information retrieval (IR)** systems, including search engines and recommendation tools.

We explored how raw text becomes structured data that machines can understand and used this to calculate similarities between documents and queries.

---

## 🛠️ What Did We Build?

We implemented and demonstrated six core IR concepts:
1. **Term-Document Incidence Matrix** – shows which terms appear in which documents (binary)
2. **Term Frequency (TF)** – counts how often terms occur in each document
3. **Log Frequency Weighting** – smooths extreme term frequencies using log scale
4. **Document Frequency (DF)** – counts how many documents contain each term
5. **Inverse Document Frequency (IDF)** – gives more weight to rare, informative terms
6. **TF-IDF Weighting** – combines TF and IDF to score term importance

✨ Plus:
- Preprocessed real `.txt` files using tokenization, stopword removal, and stemming  
- Ran phrase queries (like `"machine learning"`) using the term-document incidence matrix  
- Computed all metrics in a clean, well-commented **Jupyter Notebook**

---

## 📂 About the Data

- All input `.txt` documents are in the `./data/` folder  
- The corpus contains over 20 English documents sourced from public datasets  
- After preprocessing, we built a vocabulary with hundreds of unique tokens  

---

## 🚀 How to Run This Project

1. Clone the repo:
   ```bash
   git clone https://github.com/KapilBhardwaj2702/IRBasics-VectorSpaceProximity-workshop.git
   cd IRBasics-VectorSpaceProximity-workshop
