## **Week 1 — Assignment (Introduction to IR)**

### **1) What is the primary goal of Information Retrieval (IR)?**

* To structure databases
* To seek out unstructured documents that satisfy a user's information need ✅
* To perform numerical computations
* To design user interfaces

---

### **2) What does the term stopword refer to in IR?**

* Words that are rare in documents
* Words that are always capitalized
* Technical terms in a document
* Commonly used words that do not contribute significantly to content understanding ✅

---

### **3) What is the main difference between controlled vocabulary and free-text vocabulary?**

* Controlled vocabulary uses human-assigned topics; free-text uses terms from the document ✅
* Controlled vocabulary is cheaper to implement
* Free-text vocabulary is more ambiguous ✅
* Controlled vocabulary has predefined terms; free-text vocabulary is more flexible and allows any terms ✅

---

### **4) In query optimization for Boolean retrieval, the best practice is to process terms:**

* In alphabetical order
* In order of increasing document frequency ✅
* In order of decreasing document frequency
* Randomly

---

### **5) A key disadvantage of controlled vocabulary is:**

* Too many terms
* Cannot be used for indexing
* Expensive and time-consuming ✅
* Cannot represent topic details

---

### **6) Ad hoc IR means:**

* Using SQL to retrieve documents
* Retrieval done with unlimited queries
* Retrieval evaluated using a finite set of queries ✅
* No evaluation is needed

---

### **7) What is a major drawback of using grep-like linear scanning for IR on large collections?**

* It cannot handle Boolean queries
* It is efficient for ranked retrieval
* It supports proximity queries well
* It requires scanning the entire collection for each query term ✅

---

### **8) Which of the following are stored in the dictionary of an inverted index?**

* The actual term ✅
* Document frequency ✅
* Position of term in each document
* Pointer to the start of the posting list ✅

---

### **9) You have two posting lists:**

T₁ = [3, 10, 24, 40]
T₂ = [1, 10, 15, 24, 35, 40]

**How many comparisons occur during a standard AND merge?**

* 6
* 7 ✅
* 8
* 9

---

### **10) Let us assume two posting list sizes for words “A” and “B” are |A| = 1200 and |B| = 300. Then what will be the size of A AND B?**

* 36
* 1200
* 300 ✅
* 90

---
