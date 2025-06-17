### **ARITHMETIC Project**

The ARITHMETIC project is a study focused on German arithmetical treatises from the late Middle Ages, specifically the period between 1400 and 1522. It is funded by the European Research Council (ERC) and involves teams from the universities of Innsbruck and Graz. The project's main goal is to investigate how arithmetic knowledge was developed, practiced, and disseminated in the German vernacular during the transition from the Middle Ages to the Modern Period.

**Project Website:** www.arithmetic-project.org
**Digital Edition:** [https://gams-staging.uni-graz.at/context:arithmetic](https://gams-staging.uni-graz.at/context:arithmetic)

### **Core Problem and Significance**

While much is known about the evolution of mathematical theory in Latin, there is a significant gap in understanding how practical arithmetic knowledge spread among new groups of people through vernacular languages in the 15th and early 16th centuries. The ARITHMETIC project addresses this gap by studying handwritten German treatises that were created before printed books became widely available.

The project's significance lies in:
* **Vernacularization of Knowledge:** These texts are crucial for understanding how mathematical knowledge was made accessible to people without higher education, such as those in commerce.
* **Linguistic Development:** The translation and adaptation of these works helped create new forms of scientific abstraction in German, enhancing its potential as a language of science.
* **Cultural History:** The treatises reveal links between mathematics, commerce, and science, and provide insight into the circulation of knowledge and pragmatic literacy of the time.

### **Corpus and Methodology**

The project's research is based on a corpus of 135 manuscripts, of which 116 are considered relevant. The primary focus is on the approximately 60-70 manuscripts dated before or around 1500.

The central output of the project is a semantically enriched digital edition of these treatises. This "Assertive Edition" combines traditional textual criticism with digital annotation methods to analyze the texts from historical, literary, and linguistic perspectives.

### **Project Structure: Subprojects (SP)**

The research is divided into four interconnected subprojects:

* **SP1: Documentation and Context:** This subproject focuses on the physical manuscripts themselves. It involves describing their content, illustrations, history, and paleography to understand their production, circulation, and use. Methods include comparative and structural codicology, as well as digital network analysis and visualization.
* **SP2: Transcription, Encoding, Annotation:** This is the core of the digital edition's creation. It involves transcribing the manuscripts, creating digital images, and developing an ontology of late medieval arithmetic to structure and interpret the knowledge within the texts. The methodology is the "Assertive Edition," which formally annotates and structures the knowledge.
* **SP3: Philological and Historical Analysis:** This subproject analyzes the transcribed texts as a discourse. By using methods like lexeme-analysis and close reading, it examines the cultural and social relevance of the texts and their connections to other discourses of the time, such as religion and trade.
* **SP4: Arithmetical Jargon and Vocabulary:** This part of the project studies the development of a specialized German arithmetic language. It analyzes the influence of Latin, the creation of new German terms (neologisms), and the compilation of a glossary of arithmetic terminology to understand the semantic context. The process involves creating lemma lists during transcription, tracing terms to their Latin origins where possible, and publishing the final glossary.

The subprojects are designed to inform one another; for instance, the contextual data from SP1 and the terminological data from SP4 are incorporated into the analyses in SP2 and SP3.

### **Technical Implementation: Transcription and HTR Model Training**

The project utilizes the **Transkribus** software for Handwritten Text Recognition (HTR) to automate the transcription of the manuscripts.

* **Process:** The team trains HTR models by feeding them "Ground Truth" data, which consists of manually transcribed and corrected text. The training process is iterative:
    * It started with a single hand and required a minimum of 10,000 words per hand for effective training.
    * The models evolved from handling a few manuscripts (Model 2) to including more varied hands (Model 4), which improved accuracy.
    * A breakthrough was achieved with Model 5, which was trained on a larger set of similar 15th-century hands, significantly improving results.
    * The team further developed a "Model 5 plus" and experimented with a "Generic Model" for 15th-century texts, trained on 28 manuscripts and over 286,000 words.
* **Performance:** The Character Error Rate (CER) on the validation set improved with subsequent models, decreasing from 7.60% with Model 2 to 5.71% with "Model 5 plus".
* **Challenges:** The project identified several persistent challenges for automated transcription, including the recognition of complex fractions, multi-line calculations, and pages with non-linear layouts.

### **Annotation and Edition Features**

The annotation process is multi-layered:

1.  **In Transkribus:** Basic structural and content elements are tagged, such as abbreviations, page numbers, headers, and different types of mathematical figures (e.g., multiplication, division, regula_de_tri).
2.  **In Oxygen (XML Editor):** More detailed semantic annotation is performed, tagging entities like people, places (including trade cities), goods, and currencies. The mathematical content of each paragraph is also categorized (e.g., conversion calculation, barter calculation).

The final digital edition will provide users with:
* High-quality images of each manuscript alongside both a diplomatic (as-is) and an expanded transcription.
* A downloadable glossary with a commentary on mathematical and mercantile terms, including their German variants and Latin sources where applicable.
* Detailed descriptions of each manuscript with links to external data and catalogues.

### **Future Work and Analysis**

The project's next steps involve deeper analysis and data visualization:
* **Ontology:** While an initial attempt was made to create an ontology of arithmetics by looking at the Sacrobosco Algorism (a 13th-century university text), this work is currently on hold.
* **Text Mining:** The team plans to use tools like Voyant-Tools and AntConc for similarity analysis to identify clusters of texts and trace knowledge transmission by studying phrasing and terminology.
* **Network Analysis:** The project will visualize networks of trade routes, cities, and goods mentioned in the texts to trace commercial connections.