### **Digital Approaches to Thomas Bernhard**

---

#### **Part 1: Introduction - Bernhard and the Technicized World**

* **Core Theme**: Bernhard's work reflects a deep engagement with the technicization and rationalization of the world.
    * **The World as a Computer**: He describes humans as "calculating machines" and states, "The world is more and more just a computer."
    * **Science as an Apparatus**: His characters often engage in obsessive, pseudo-scientific studies (e.g., *Das Kalkwerk*, *Korrektur*), reflecting his view that "Life is just science, science from the sciences."
    * **Destruction of the Whole**: Bernhard believed in breaking things down, stating, "There must be nothing whole, one must smash it." This is reflected in his literary style.
* **Bernhard's Writing Process**:
    * He described his own process as a musical and destructive act: building up sentences and ideas like a toy structure, only to "smash everything together again like a child."
* **Perception of his Style**: Other authors, like Josef Winkler, have described Bernhard's repetitive, formulaic style as a "machine" or a "trick" (*Masche*) that, once understood, can lose its appeal. The writer Antonio Fian humorously notes that Bernhard's style is so pervasive it seems all of Austria has adopted it.

---

#### **Part 2: Metadata and Databases**

This section explores projects that collect and analyze metadata about Bernhard's work and its reception.

##### **Project 1: *Global Bernhard***

* **Goal**: To document Thomas Bernhard's international echo and his influence on other writers worldwide.
* **Key Idea**: Bernhard's writing has been described as a "curse," "addiction," and a "virus" by other authors, who often feel they must shield themselves from his powerful influence. The project collects and presents examples of this reception.
* **Platform**: The project website is built on TYPO3 and features a database of authors who have been influenced by Bernhard, including excerpts of their work.
* **Data Analysis**: Visualizations of the project's data show:
    * **Geographic Spread**: The largest number of influenced authors are from Austria, Germany, the USA, and France.
    * **Linguistic Spread**: Most works referencing Bernhard are originally written in German, English, and French.
    * **Chronology**: There was a significant spike in publications related to Bernhard around 1999 (the 10th anniversary of his death).
    * **Demographics**: The data allows for analysis of author demographics, such as a breakdown of gender distribution by decade of birth.

##### **Project 2: *thomas bernhard in translation***

* **Goal**: The first online database of all published translations of Bernhard's works.
* **Scope**: Contains over 1,000 entries covering more than 800 first editions in 42 different languages.
* **Features**:
    * Provides detailed bibliographical information (translators, publishers, original titles, publication years).
    * Allows for targeted searches by title, language, and translator.
    * Includes a focus on book covers, revealing visual trends and how publishers attempt to steer reception in different markets.
* **Data Analysis**: The database shows which works are most frequently translated (*Wittgensteins Neffe*, *Die Ursache*) and maps the distribution of first translations over the decades.

##### **Future: *Forschungsstelle Thomas Bernhard***

* This is a planned Digital Research Platform that will integrate multiple components into a single, flexible data model (using APIS).
* **Components**: Virtual Private Library, Translation Database, Theater Production Database, Audio/Video Recordings, Poster Database, and Digital Editions.

---

#### **Part 3: Text Data and Text Mining**

This section applies computational text analysis methods to a corpus of Bernhard's prose works.

##### **1. Stylometry and Werkphasen (Phases of Work)**

* **Method**: Stylometry uses word frequencies (particularly of common, non-content words) to measure the relative similarity between texts. It does not analyze content or literary quality.
* **Principal Components Analysis (PCA)** was used to visualize the stylistic relationships between Bernhard's texts.
* **Key Findings**:
    * **Early Work (1950s)**: Shows high stylistic variance, reflecting a young author finding his voice.
    * **Middle Work (1960s-70s)**: A period of stylistic experimentation and consolidation. Texts from this era cluster together but show development over time.
    * **Late Work (1980s)**: His late novels cluster very tightly, indicating a highly consistent and established style, confirming the "self-repetition" often ascribed to him.
    * **Autobiographical Works**: These texts form their own distinct stylistic cluster.
* **Conclusion**: The "analog" hypothesis of distinct work phases is supported by the "digital" findings of stylometry.

##### **2. Linguistic Structures and Repetition**

* **Average Sentence Length**: A clear diachronic trend shows that Bernhard's sentences became progressively longer throughout his career. *Korrektur* (1975) contains the longest single sentence (1,156 words).
* **Type-Token Ratio (TTR)**: This metric measures lexical diversity. The analysis shows a decreasing TTR over time, quantitatively confirming that his language became more repetitive.
* **Punctuation**: The use of question marks decreases significantly over his career.
* **"Bernhardisms"**: The analysis tracks the frequency of his favorite words and stylistic tics (e.g., *naturgemäß*, *sogenannt*, *wie ich sagen muss*, *dachte ich in meinem Ohrensessel*), showing how their usage changes across his work phases.

##### **3. Places and Emotions**

* **Method**: This analysis combines **Named Entity Recognition (NER)** to identify locations in the texts with **Sentiment Analysis** (using the SentiArt lexicon) to measure the emotional context of those places.
* **Key Findings**:
    * Bernhard is known for his "city-insults" (*Städtebeschimpfungen*), but the analysis provides a more nuanced picture.
    * **Southern European** locations (e.g., Sicily, Florence) are often associated with a more positive emotional context, especially in his late work.
    * The most emotionally charged places are not necessarily real cities but **"psychological spaces"** or functional locations. The most negative is the *Kindheitsloch* ("childhood hole"), and the most positive is the *Konzerthaus* ("concert hall"), which fits with the role of childhood trauma and art in his autobiography.
    * This method allows for the creation of unique **"emotion profiles"** for each location, visualized in radar charts.