# Computer Programming for Data Scientists**

## **Overview**
This repository contains solutions for **Coursework 1 and Coursework 2** of the **7CCSMCMP - Computer Programming for Data Scientists** module at **King’s College London**. The coursework consists of multiple programming exercises designed to strengthen skills in **data processing, algorithm design, data visualization, and natural language processing**.

## **Coursework Breakdown**
The coursework is divided into two main components:

### **Coursework 1: Python Programming Tasks**
- **Activity 1:** Analysis of Olympic Games Medal Data (**medals.py**)
- **Activity 2:** Development of a Shopping System Prototype (**shopping.py**)
- **Activity 3:** Implementation of a Binary Search Tree and Complexity Analysis (**binarysearchtree.py, complexity.py, linkedlist.py**)

### **Coursework 2: Data Science and Visualization Tasks**
- **Activity 1:** Working with Open Data APIs & COVID-19 Data (**CW2_A1.ipynb**)
- **Activity 2:** Graph Manipulation and Network Analysis using NetworkX (**CW2_A2.ipynb**)
- **Activity 3:** Natural Language Processing with Wikipedia & Turing Award Winners (**CW2_A3.ipynb**)

---

## **Installation & Setup**
### **1. Clone the Repository**
```bash
git clone https://github.com/yourusername/7CCSMCMP_Coursework.git
cd 7CCSMCMP_Coursework
```

### **2. Set Up a Virtual Environment**
```bash
python -m venv env
source env/bin/activate   # Mac/Linux
env\Scripts\activate      # Windows
```

### **3. Install Dependencies**
```bash
pip install -r requirements.txt
```

### **4. Running Python Scripts**
#### **Coursework 1:**
- Run **medals.py** to analyze Olympic medal data:
  ```bash
  python medals.py
  ```
- Run **shopping.py** to interact with the shopping system:
  ```bash
  python shopping.py
  ```
- Execute binary search tree and complexity analysis scripts:
  ```bash
  python binarysearchtree.py
  python complexity.py
  python linkedlist.py
  ```

#### **Coursework 2:**
- Open Jupyter Notebook:
  ```bash
  jupyter notebook
  ```
- Run each notebook for corresponding activities:
  - **Activity 1:** `CW2_A1.ipynb`
  - **Activity 2:** `CW2_A2.ipynb`
  - **Activity 3:** `CW2_A3.ipynb`

---

## **Project Structure**
```
📂 7CCSMCMP_Coursework
│── 📂 coursework_1
│   │── medals.py                 # Olympic medal analysis
│   │── shopping.py               # Shopping system prototype
│   │── binarysearchtree.py       # Binary Search Tree implementation
│   │── complexity.py             # Complexity analysis of BSTs
│   │── linkedlist.py             # Linked list implementation
│── 📂 coursework_2
│   │── CW2_A1.ipynb              # COVID-19 Data API & Visualization
│   │── CW2_A2.ipynb              # NetworkX Graph Processing
│   │── CW2_A3.ipynb              # NLP with Wikipedia & Wikidata
│── 📂 data
│   │── medals.csv                # Olympic Games dataset
│   │── regional.csv              # COVID-19 regional data
│   │── england.csv               # COVID-19 England data
│── requirements.txt              # Dependencies
│── README.md                     # Project documentation (this file)
```

---

## **Coursework 1 Details**
### **Activity 1: Olympic Games Medal Analysis (`medals.py`)**
✅ Reads `medals.csv` containing Olympic medal data  
✅ Implements a **CountryMedals** class with attributes & methods  
✅ Provides functionalities to **sort, compare, and filter medal counts**  
✅ Interactive CLI-based execution loop  

### **Activity 2: Shopping System Prototype (`shopping.py`)**
✅ Implements **Product** and **ShoppingCart** classes  
✅ Supports adding, removing, and exporting products in **JSON format**  
✅ Command-line interface for interacting with the shopping system  

### **Activity 3: Binary Search Tree & Complexity Analysis (`binarysearchtree.py, complexity.py, linkedlist.py`)**
✅ Implements **Binary Search Tree (BST)** with search, insert, delete, and traversal  
✅ Compares **BST vs Linked List** performance for search operations  
✅ Complexity analysis with **matplotlib plots**  

---

## **Coursework 2 Details**
### **Activity 1: Open Data API & COVID-19 Data (`CW2_A1.ipynb`)**
✅ Queries **UK Government API** for COVID-19 case & death statistics  
✅ Transforms raw data into **Pandas DataFrames**  
✅ Generates visualizations for trends in **daily cases & deaths**  

### **Activity 2: Graph Processing with NetworkX (`CW2_A2.ipynb`)**
✅ **Randomly generates a graph** with background/foreground nodes  
✅ Computes **graph metrics** (density, centrality, etc.)  
✅ Exports graph structure to **JSON format**  

### **Activity 3: NLP with Wikipedia & Wikidata (`CW2_A3.ipynb`)**
✅ Fetches **Turing Award winners** from **Wikidata API**  
✅ Performs **Text Preprocessing (Tokenization, Stemming, Lemmatization)**  
✅ Extracts **bigrams, trigrams, synonyms, and antonyms**  
✅ Creates **visualizations** of text statistics using **matplotlib**  

---

## **Future Enhancements**
- ✅ Expand COVID-19 analysis to include **predictive modeling**  
- ✅ Improve **shopping system** with a **GUI-based interface**  
- ✅ Enhance **graph algorithms** for better insights in **Activity 2**  

---

## **License**
This project is licensed under the **MIT License**.

## **Author**
📌 **Hara Georgiou**  


