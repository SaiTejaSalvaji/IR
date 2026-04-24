## **Assignment 1**

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

## **Assignment 2**

### **1) What is document frequency?**

* Number of times a term occurs in a document
* Number of documents containing the term ✅
* Total occurrences of a term in the corpus
* Number of tokens in a document

---

### **2) Posting lists may store:**

* DocIDs ✅
* Document lengths
* Term frequencies ✅
* Term positions ✅

---

### **3) Zipf’s law relates:**

* Term frequency vs document length
* Document rank vs popularity
* Posting length vs dictionary size
* Term rank vs frequency ✅

---

### **4) Heap’s law predicts:**

* Vocabulary size as a function of corpus size ✅
* Posting list compression ratio
* Query popularity distribution
* Document frequency growth

---

### **5) Which dictionary implementation supports prefix/wildcard queries efficiently?**

* Hash-based dictionary
* SPIMI dictionary
* Sort-based dictionary ✅
* Binary heap dictionary

---

### **6) SPIMI does not require sorting because:**

* It never stores docIDs
* It merges lists during query time
* It stores tokens unsorted permanently
* It keeps posting lists in hash tables directly ✅

---

### **7) Zipf’s law implies that:**

* The vocabulary stops growing eventually
* Most words occur rarely ✅
* A few words dominate the corpus ✅
* Word frequency follows a power law ✅

---

### **8) Which scenario makes hash-based dictionaries unsuitable?**

* Very large number of terms
* Need for range/prefix queries ✅
* Need for dynamic updates
* Need for faster lookups

---

### **9) In posting list compression, why are gaps better than storing docIDs directly?**

* Gaps are always smaller numbers, requiring fewer bits to encode ✅
* Gaps eliminate the need for a dictionary
* Gaps allow for lossy compression of the index
* Gaps make range queries faster

---

### **10) According to Zipf's Law (c = 0.1), what percentage of text do top 10 terms account for?**

* 10%
* 20%
* 30% ✅
* 40%
