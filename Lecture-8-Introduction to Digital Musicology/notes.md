**Introduction to Digital Musicology**

Digital Musicology is a field within the Digital Humanities that deals with the static representation of music. Music in its primary form is a time-ordered set of sounds for a listener or gestures for a performer. Representing this in a static, readable format is a complex process involving many assumptions and conventions. Digital Musicology includes sub-fields like Music Corpus Studies (e.g., creating work catalogues), Digital Music Philology (creating digital editions), Music Performance Analysis, and Computational Music Theory.

**Music Encoding**

A core task in Digital Musicology is music encoding, which aims to represent musical notation in a machine-readable format. This is more complex than text encoding because music involves multiple layers of information, such as pitches, rhythms, articulations, and the physical layout on the page.

To encode music, one must define the score's properties (number of staves, key, meter) and the properties of individual notes (pitch name, octave, duration, stem direction).

Historically, the first encoding format was DARMS in the 1960s. Many others followed, such as Humdrum and Music-XML. Today, a major standard is the Music Encoding Initiative (MEI). MEI is an XML-based system, modeled on the Text Encoding Initiative (TEI), designed to create a machine-readable structure for music documents. It is highly flexible to accommodate a wide variety of musical documents. To visually render an MEI file as a musical score, a tool like Verovio is needed.

**Scholarly Digital Editions**

The goal of a scholarly edition is to publish a musical text based on a critical examination of the historical sources. The process involves several steps:
1. Source research and deciphering the manuscript.
2. Describing and evaluating the sources.
3. Comparing different versions (readings) to determine how sources depend on each other.
4. Using this information to produce a definitive musical text and a critical report detailing editorial decisions.
MEI is used to encode not just the final music but also variations and corrections found in the sources, such as deletions or additions made by the composer.

**The Schubert-digital Project**

Schubert-digital is a new online research platform focused on the autograph manuscripts of Franz Schubert. There are approximately 1,000 surviving compositions from Schubert, with the largest collections in Vienna.

The main aims of the project are:
1.  To create detailed descriptions of all of Schubert's autograph manuscripts.
2.  To digitally reunite scattered manuscript pages into their original, complete form. Many manuscripts were broken up after Schubert's death and are now held in different libraries around the world.

The project uses a sophisticated data model to represent manuscripts. It distinguishes between the "Gesamtmanuskript" (the complete, reconstructed manuscript as it was originally) and the "Bestandteil" (the physical part of the manuscript as it exists today). MEI is used to encode the physical structure of the paper, such as how individual sheets (bifolia) were folded and nested to form a gathering (quire).

**Watermark Digitization and Thermography**

Watermarks are designs embedded in paper during its creation. They are crucial for musicology because they can help date a manuscript and trace its origin to a specific paper mill.

Manual paper production involves dipping a mould, which is a wire mesh screen, into paper pulp. The watermark design is a wire sewn onto this screen. Where the wire is, the paper becomes slightly thinner.

To make these often faint watermarks visible, the Schubert-digital project uses thermography. A sheet of paper is placed on a gently heated copper plate. An infrared camera then takes a picture. The heat passes through the thinner parts of the paper (the watermark) more quickly, making the design clearly visible in the resulting thermogram, even if it is covered by ink or pencil. The project uses a custom-built thermographic camera device for this process.

**Digital Manuscript Reconstruction and Analysis**

The thermographic images are used for several research purposes:

1.  **Digital Reconstruction:** By identifying matching watermarks and paper types, researchers can digitally stitch together images of pages that were originally part of the same sheet of paper but were later separated.

2.  **Automated Clustering:** The project uses automated methods to analyze the physical structure of the paper itself, which acts like a fingerprint for the mould it was made on. This involves two main techniques:
    * **Radon Transformation:** This detects and measures the distance between the vertical "chain lines" in the paper.
    * **Laid Line Density:** This measures the density of the fine horizontal "laid lines."

By plotting these values on a graph, papers made on the same mould cluster together. This allows researchers to group manuscripts with certainty, even if the watermark is different or not visible. This technique is so precise it can even distinguish between "twin" moulds, which were nearly identical moulds used in pairs during paper production. This advanced analysis helps to more accurately date Schubert's works and understand his creative process.