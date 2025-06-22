Notes from the presentation "Digital Humanities Meets Assyriology: A Look at Three Groundbreaking Projects in Vienna
" by Nicla De Zorzi from University of Vienna.


---

### **Digital Humanities Meets Assyriology: Three Groundbreaking Projects in Vienna**

This summary details three interconnected projects based in Vienna that apply digital humanities methods to the study of ancient Mesopotamian cuneiform texts.

---

#### **1. Foundational Concepts: Cuneiform and the Akkadian Language**

* **Cuneiform Script**:
    * The name comes from the Latin *cuneus*, meaning "wedge."
    * It is a writing system characterized by wedge-shaped impressions made with a stylus on soft clay tablets.
    * It was originally invented by the Sumerians to write their language and was later adapted for Akkadian.

* **Akkadian Language**:
    * Akkadian is an ancient Semitic language, part of the same family as modern Hebrew and Arabic.
    * It was the language of ancient Mesopotamia, encompassing the regions of Babylonia and Assyria.
    * The term "Akkadian" includes various dialects defined by region and time period.
    * **Standard Babylonian** was the high-prestige, literary version of the language, used across Western Asia from the 15th to the 4th century BCE. Mastering it required extensive training, typically available only to elite scribes in royal courts or temples.

---

### **Project 1: DigEanna & NaBuCCo – Digitizing the Eanna Temple Archive**

This project focuses on making the vast administrative archive from the Eanna temple in Uruk accessible for historical research.

* **The Eanna Archive**:
    * **Source**: The archive originates from the Eanna temple, dedicated to the goddess Ištar in the southern Babylonian city of Uruk.
    * **Time Period**: It covers the late 7th to 6th century BCE, which is considered the best-documented period in Babylonian history.
    * **Scale**: It is a massive collection, comprising over **9,000 cuneiform tablets** and fragments. These are currently housed in various museums across the United States and Europe.
    * **Content**: The tablets are primarily administrative documents detailing the temple's economic and social activities.

* **Project Goals and Strategy**:
    * **Primary Goal**: To create a comprehensive digital analysis of the Eanna archive.
    * **"Digests over Editions"**: The project's key strategy is to prioritize creating **digests (paraphrases)** and extracting metadata (keywords, names) rather than producing full, line-by-line editions of every tablet.
    * **Efficiency**: This approach offers a practical tradeoff between speed and comprehensiveness, allowing researchers to quickly grasp the content of thousands of simple administrative texts.
    * **Selective Editions**: Full, detailed editions are reserved for only the most important and representative texts.

* **The Digital Workflow**:
    * **DigEanna & eBL**: Editions of selected tablets are created within the **DigEanna-Project** using the **Fragmentarium**, an open-source web application developed by the **Electronic Babylonian Literature (eBL)** project.
    * **NaBuCCo Platform**: The curated data—including metadata, digests, and full editions—is then exported via web services to the **NaBuCCo (A Neo-Babylonian Cuneiform Corpus)** platform, which serves as the main online catalogue.
    * **Interoperability and Export**: Data is available on both the eBL and NaBuCCo platforms for review and reuse. Both allow the export of these richly annotated texts in standard formats like JSON and **TEI XML**.

---

### **Project 2: Bestiarium Mesopotamicum – Unlocking Animal Omens**

Led by Nicla De Zorzi and funded by the FWF, this project creates an open-access digital edition and a comprehensive analysis of animal omens from a major Babylonian divinatory text series.

#### **A. The World of Mesopotamian Divination**

* **The Role of Gods**: It was believed that the gods communicated with humanity by sending signs.
* **Two Forms of Communication**:
    1.  **Provoked Divination**: A diviner could actively seek a sign by asking a question in a formal ritual context.
    2.  **Unprovoked Divination**: The gods could send messages on their own initiative through everyday phenomena, like the sudden appearance of an animal, an earthquake, or an eclipse.
* **The World as a "Text"**: Diviners saw the world as a fabric into which the gods "wrote" messages. For example, the stars were called the "writing of the firmament" (*šiṭir burūmê*), and the liver of a sacrificial sheep was seen as a "tablet of the gods" (*ṭuppu ša ilī*).
* **The Diviners**: Divination experts were highly trained scribes who often served as royal advisors, using their skills as a decision-making tool for kings and elites.

#### **B. The *Šumma ālu* ("If a City...") Omen Series**

* **The Text**: The project focuses on a canonical Babylonian divinatory composition titled *Šumma ālu ina mēlê šakin* ("If a city is set on a height").
* **Massive Scale**: This series originally contained over **13,000 omens** organized into more than 100 thematic chapters.
* **Project Focus**: The *Bestiarium Mesopotamicum* project specifically targets the **47 chapters** that deal with animal behavior.
* **Animals Covered**: The omens feature a wide range of creatures: snakes, scorpions, insects, dogs, pigs, lions, foxes, birds of prey, and aquatic animals.

#### **C. The Internal Logic and Structure of Omens**

* **Fundamental Structure**: Omens are formulated as "if-then" statements:
    * **Protasis (Sign)**: The "if" clause that describes the observed event.
    * **Apodosis (Prediction)**: The "then" clause that gives the outcome.

* **Systematic Generation, Not Empirical Observation**:
    * These lists are not simple records of historical events.
    * They are highly schematic and systematically generated based on a set of intellectual principles.

* **Key Structuring Principles**:
    * **Binary Opposition**: Pairing omens based on opposites like up/down or right/left.
    * **Repetition with Variation**: Creating sequences where an omen repeats elements from the previous one but adds a new variable.
    * **Associative Lists**: Grouping omens by related concepts, such as sequencing predictions based on body parts, colors, or months of the year.
    * **Complex Literary Patterns**: The sequence of predictions (apodoses) can form elaborate structures, such as a **chiasm** or a circular pattern.

* **The Central Rule of Similitude**:
    * The link between the sign and the prediction is **always based on analogy or similarity** (semantic, phonetic, or graphic).
    * **Example**: "If a dog digs in the dirt in front of a man and lies down - his wife will be a serial adulteress." The dog's actions are seen as analogous to the wife's future behavior. This reflects a worldview where the universe is an interconnected web of similarities reflecting the divine will.

#### **D. Case Study: The Birds in *Šumma ālu***

The study of birds in the omen series provides a clear example of how analogical thinking was applied. Birds were seen as significant due to a combination of unique characteristics:
* Mobility in three dimensions.
* Curiosity and articulated sociality.
* Vocal abilities.

This perspective is famously summarized by Claude Lévi-Strauss, who noted that birds form an independent society that appears homologous to human society. The omen texts apply this analogy directly:
* **Positive Social Interaction**: "If a falcon and a raven eat something together – there will be peace that brings good fortune in the land".
* **Negative Social Interaction**: "If a falcon and an eagle don’t agree with each other and fight each other [...]" the prediction would logically relate to strife or conflict among humans.

#### **E. The Digital Philology Workflow**

* **The Challenge of Fragmentation**: The complete text of *Šumma ālu* must be reconstructed from hundreds of broken tablet fragments ("witnesses").
* **The "Score" as a Solution**:
    * The project digitally aligns the text from all parallel witnesses into a **score**.
    * From this score, a reliable **composite text** is created that reconstructs the full omen.
* **Custom Digital Tools and TEI Format**:
    * A custom-built web application processes Excel sheets containing the transliterations from each witness.
    * The final online edition is highly interactive, presenting the transliteration, transcription, and translation in parallel columns and tracking variant readings.
    * The final data can be exported in **TEI format**. The presentation shows a screenshot of the TEI XML file structure, demonstrating how individual witnesses, variant readings, and philological notes are encoded.
* **Advanced Linguistic Analysis**:
    * The project uses tools like **WordNet** to disambiguate the meaning of words.
    * Data visualizations like Sankey diagrams are used to explore the relationships between animals, actions, and the sentiment (positive, negative, uncertain) of the predictions.

![alt text](<image-1 copy.png>)
---

### **Project 3: Comparative Divination Studies (Mesopotamia & Early China)**

* This research extends the analysis to a comparative perspective.
* It explores structural parallels between the generative principles in Mesopotamian omen lists and those found in early Chinese divinatory texts written on bamboo strips, such as the **Shifa 筮法 (Stalk Divination Model)**.
* The core insight is that both cultures developed complex textual traditions that were not designed for simple linear reading but must be engaged with as a **"dynamic hypertext,"** tracing their intricate networks of internal correspondences and recursive loops.