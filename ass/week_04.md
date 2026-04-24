Clean extraction:

---

## **1) What is the main risk of using a single analyzer for indexing multilingual documents?**

**Options:**

* Increased index size
* Incorrect tokenization and stemming ✅
* Slower query processing
* Inability to store fields

**Answer:**
✔ Incorrect tokenization and stemming

---

## **2) What does storing a field enable?**

**Options:**

* Faster indexing
* Query-time analysis
* Retrieval of original field value ✅
* Higher ranking score

**Answer:**
✔ Retrieval of original field value

---

## **3) Why might indexing title, abstract, and body as separate fields improve retrieval?**

**Options:**

* Reduces index size
* Enables field-specific boosting ✅
* Avoids stopword removal
* Eliminates need for analyzers

**Answer:**
✔ Enables field-specific boosting

---

## **4) A document has a very long body field and a very short title field. Without field normalization, what is the likely effect?**

**Options:**

* Title dominates scoring
* Body dominates scoring ✅
* Both contribute equally
* Document is ignored

**Answer:**
✔ Body dominates scoring

---

## **5) How does maxDoc() differ from numDocs()?**

**Options:**

* maxDoc() excludes deleted docs
* numDocs() includes deleted docs
* maxDoc() includes deleted docs ✅
* They are always equal

**Answer:**
✔ maxDoc() includes deleted docs

---

## **6) Why might two indexes built from the same corpus appear different in LUKE? (Select all)**

**Options:**

* Different analyzers used ✅
* Different field storage settings ✅
* Different indexing time
* Different OS

**Answer:**
✔ Different analyzers used
✔ Different field storage settings

---

## **7) What additional information is needed in an index to handle (information UW/3 science)?**

**Options:**

* Term frequencies
* Document IDs
* Term positions ✅
* Field mappings

**Answer:**
✔ Term positions

---

## **8) What is a key limitation of basic Boolean retrieval (AND, OR, NOT)?**

**Options:**

* It cannot handle wildcards
* It does not support ranking ✅
* It cannot process non-English text
* It requires too much memory

**Answer:**
✔ It does not support ranking

---

## **9) What does the query (information OW/2 science) require for a match?**

**Options:**

* "information" must appear exactly 2 words before "science"
* "information" must appear within 2 words before "science" ✅
* "information" and "science" must be in the same document
* "information" must appear after "science"

**Answer:**
✔ "information" must appear within 2 words before "science"

---

## **10) If English and German documents are indexed using the same EnglishAnalyzer, what is the most likely consequence?**

**Options:**

* German stopwords will be preserved
* German words may be incorrectly stemmed or removed ✅
* Queries will fail to parse
* Index will not build

**Answer:**
✔ German words may be incorrectly stemmed or removed

---
