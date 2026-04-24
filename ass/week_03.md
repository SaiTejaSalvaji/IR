Extracted cleanly:

---

## **1) What is the role of an Analyzer during indexing?**

**Options:**

* It computes relevance scores
* It tokenizes and processes text ✅
* It stores fields on disk
* It merges index segments

**Answer:**
✔ It tokenizes and processes text

---

## **2) In Lucene, a Document is best described as:**

**Options:**

* A single term in the vocabulary
* A query representation
* A container for multiple fields ✅
* A scoring function

**Answer:**
✔ A container for multiple fields

---

## **3) When adding a Field to a Document, which concerns apply? (Select all)**

**Options:**

* Stored: Should the original value be saved so it can be retrieved later? ✅
* Indexed: Should the value be processed so it can be searched? ✅
* Tokenized: If indexed, should the text be broken into keywords? ✅
* Typed: Is the value a string, integer, or date?

**Answer:**
✔ Stored
✔ Indexed
✔ Tokenized

---

## **4) Phrase queries require which IndexOptions setting?**

**Options:**

* TextField
* IndexOptions.DOCS
* IndexOptions.DOCS_AND_FREQS
* IndexOptions.DOCS_AND_FREQS_AND_POSITIONS ✅

**Answer:**
✔ IndexOptions.DOCS_AND_FREQS_AND_POSITIONS

---

## **5) Steps to add 1000 documents to a PyLucene index (Select all)**

**Options:**

* Use lucene.initVM() at the start ✅
* Create a new IndexWriter for each document
* Use writer.addDocument(doc) to add docs ✅
* Close IndexWriter using writer.close() ✅

**Answer:**
✔ lucene.initVM()
✔ writer.addDocument(doc)
✔ writer.close()

---

## **6) Which design choices help efficient indexing?**

**Options:**

* Not storing large text fields ✅
* Using StringField for categorical data ✅
* Tokenizing numeric fields
* Choosing appropriate analyzers ✅

**Answer:**
✔ Not storing large text fields
✔ Using StringField for categorical data
✔ Choosing appropriate analyzers

---

## **7) Which statements about Lucene Documents are correct?**

**Options:**

* A document can have multiple fields with the same name ✅
* Field names must be unique per document
* Documents are immutable once indexed ✅
* Documents directly store posting lists

**Answer:**
✔ A document can have multiple fields with the same name
✔ Documents are immutable once indexed

---

## **8) Why is storing large text fields inefficient?**

**Options:**

* Stored fields affect term statistics
* Stored fields increase index size ✅
* Stored fields reduce recall
* Stored fields cannot be compressed

**Answer:**
✔ Stored fields increase index size

---

## **9) Best field type for document identifiers?**

**Options:**

* TextField
* StoredField
* StringField ✅
* IntPoint

**Answer:**
✔ StringField

---

## **10) Book metadata indexing (ISBN + Description)**

**Question:**

* ISBN → exact lookup, not displayed
* Description → full-text search, must display

**Options:**

* ISBN: TextField (stored=False), Description: StringField
* ISBN: StringField (stored=False), Description: TextField (stored=True) ✅
* ISBN: StringField (stored=True), Description: StringField (stored=True)
* ISBN: TextField (stored=True), Description: TextField (stored=False)

**Answer:**
✔ ISBN: StringField (stored=False), Description: TextField (stored=True)

---
