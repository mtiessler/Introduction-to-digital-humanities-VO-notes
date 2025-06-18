### **Digital Humanities Meets Assyriology: Three Vienna Projects**

---

#### **1. Introduction to Cuneiform and Akkadian**

* **Cuneiform Script**: An ancient writing system using (cuneus = wedge) wedge-shaped impressions made by a stylus on soft clay tablets. It was invented by the Sumerians and later adapted for the Akkadian language.
* **Akkadian Language**: An ancient Semitic language (related to Hebrew and Arabic) spoken in Mesopotamia (Assyria and Babylonia). The term covers various regional and chronological dialects.
* **Standard Babylonian**: A refined, literary form of the language used from the 15th to the 4th century BCE. Mastery required a high level of scribal education.

---

### **Project 1: DigEanna & NaBuCCo (The Eanna Temple Archive)**

This project focuses on the massive archive of the Eanna temple in the city of Uruk from the late 7th-6th century BCE.

* **The Archive**:
    * Consists of over 9,000 cuneiform tablets and fragments.
    * These are administrative documents from the temple of the goddess Ištar.
    * It is the most multifaceted collection from the best-documented period of Babylonian history.
* **Project Strategy**:
    * Instead of creating full editions of every text, the project builds its online catalogue around **digests/paraphrases** and metadata.
    * This approach is faster and more comprehensive for making a large volume of simple administrative texts accessible for research.
    * Full editions are created only for the most important and representative texts.
* **Digital Workflow**:
    * Editions of selected tablets are created using the **Fragmentarium**, a web application from the Electronic Babylonian Literature (eBL) project.
    * This data (editions, metadata, digests) is then exported to the **NaBuCCo (A Neo-Babylonian Cuneiform Corpus)** platform.
    * Data is available for review and re-use on both platforms and can be exported in formats like JSON and TEI XML.

---

### **Project 2: Bestiarium Mesopotamicum (Animal Omens)**

This project creates an open-access digital edition and analysis of the animal omen sections from a major Babylonian divinatory series.

#### **A. Mesopotamian Divination**

* **Core Belief**: The gods communicate with humans by sending signs, which can be interpreted by trained experts (diviners).
* **How Signs Appear**:
    1.  In response to a direct question posed in a ritual.
    2.  On the gods' own initiative, through natural phenomena (e.g., an eclipse, an animal's behavior).
* **The "Writing of the Gods"**: Diviners believed the gods "wrote" messages into the world. The liver of a sacrificial animal was called a "tablet of the gods," and constellations were the "writing of the firmament."

#### **B. The *Šumma ālu* Omen Series**

* **Title**: The series is named after its first line: *"If a city is set on a height"* (in Babylonian: *Šumma ālu ina mēlê šakin*).
* **Content**: A massive composition of over 13,000 omens across more than 100 thematic chapters.
* **Project Focus**: This project concentrates on the **47 chapters** dealing specifically with animal behavior, covering everything from snakes and insects to dogs, lions, and birds.

#### **C. The Logic and Structure of Omens**

* **Structure**: Omens consist of two parts:
    1.  **Protasis**: The "if" clause, describing the sign (e.g., "If a dog digs in the dirt...").
    2.  **Apodosis**: The "then" clause, stating the prediction (e.g., "...his wife will be a serial adulteress.").
* **Systematic, Not Empirical**: The omen lists are not records of real-life observations. They are highly schematic and generated through a set of intellectual rules.
* **Structuring Principles**:
    * **Binary Opposition**: Omens are often paired based on opposites (e.g., up/down, right/left).
    * **Repetition with Variation**: A sequence of omens will repeat elements from the previous one while adding new details.
    * **Associative Lists**: Omens are organized by lists of related concepts, such as body parts, colors, or months of the year.
    * **Complex Patterns**: The predictions (apodoses) can follow complex literary patterns like chiasm (A-B-B'-A') or circular structures.
* **The Rule of Similitude**: The connection between the sign (protasis) and the prediction (apodosis) is **always based on some form of analogy or similarity** on a semantic, phonetic, or graphic level. The universe was seen as a web of similarity-based interconnections reflecting the will of the gods.

#### **D. The Digital Philology Workflow**

* **Challenge**: The omen series is preserved across many broken clay tablet fragments (called "witnesses"). A single omen might be partially attested on several different fragments.
* **Solution: The Score**:
    * To reconstruct the full text, the project aligns the text from all relevant fragments in a **score**.
    * From this score, a **composite text** is created.
* **Digital Tools**:
    * A custom-made web application is used where cuneiform readings from the tablets are input via Excel sheets.
    * This allows the digital edition to display the composite text, the individual readings from each fragment, and compare new readings to previous editions.
    * The final online presentation includes the transliteration, transcription, and translation side-by-side, along with philological commentary.
* **Linguistic Analysis**:
    * The project uses tools like **WordNet** to disambiguate word senses (e.g., distinguishing "fall" as in gravity from "fall" as in a decline of strength).
    * This allows researchers to find conceptual similarities even when different words are used.
    * Data visualizations (Sankey diagrams) are used to explore patterns, like the relationship between certain animals, their actions, and whether the prediction is positive, negative, or uncertain.

---

### **Project 3: Comparative Studies (Mesopotamia & China)**

* The lecture briefly mentions a comparative project that explores structural similarities between Mesopotamian omen lists and early Chinese divinatory manuscripts (the *Shifa*).
* Both traditions created complex texts that were not meant to be read only linearly but also recursively, through networks of correspondences, like a "dynamic hypertext."