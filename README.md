# -Text-Summarization-Tool
Build a tool that generates concise summaries from long-form text using classical NLP techniques (without using any LLMs or external AI APIs).
                                                                 
Overview
This project implements a classical NLP-based Text Summarization Tool that generates concise summaries from long-form text without using any Large Language Models (LLMs) or external AI APIs. The system uses the TextRank algorithm to extract important sentences and produce a short summary and key bullet points. The tool is designed as a lightweight web application that runs directly in the browser and demonstrates classical Natural Language Processing techniques.
Objective
•	Build a text summarization tool using classical NLP techniques
•	Avoid the use of LLMs and external AI APIs
•	Generate concise summaries from long-form text
•	Provide 2-3 sentence summaries and up to 5 key bullet points
•	Create a simple and interactive web interface
Features
•	Classical NLP-based summarization
•	TextRank algorithm implementation
•	Sentence similarity using word overlap
•	Stopword removal and text preprocessing
•	Summary generation (2-3 sentences)
•	Bullet point extraction (up to 5 points)
•	Built-in dataset for testing
•	Clean and responsive web interface
•	Copy and download summary option
Dataset
The project includes a small dataset of 10 long-form text samples used for testing and demonstration purposes. Users can either select a sample article or provide their own input text.
Procedure
1. Define the project objective to build a classical NLP-based text summarization tool without LLMs.
2. Prepare a small dataset of long-form text samples for testing.
3. Design the system as a web-based application with a TextRank summarization engine.
4. Develop the user interface using HTML and Tailwind CSS.
5. Implement NLP preprocessing including sentence tokenization, lowercasing, punctuation removal, and stopword removal.
6. Construct a similarity matrix using word overlap between sentences.
7. Apply the TextRank algorithm using PageRank to rank sentences based on importance.
8. Select top-ranked sentences to generate summary and bullet points.
9. Display results and allow users to copy or download the summary.
10. Test the system using dataset samples and custom input text.
System Workflow
Input Text → Sentence Tokenization → Text Cleaning → Stopword Removal → Similarity Matrix → TextRank Algorithm → Sentence Ranking → Summary Generation → Output Display
Assumptions
Input text is in English
Sentences contain proper punctuation
Extractive summarization is sufficient
Stopwords do not contribute to sentence importance
Single document summarization is used
No external APIs or LLMs are required
Design Decisions
Use of TextRank: TextRank was selected because it is an unsupervised and widely used classical NLP algorithm for extractive summarization.
Extractive Summarization: Extractive summarization was chosen to comply with the requirement of not using LLMs.
JavaScript Implementation: The algorithm is implemented in JavaScript to allow fast browser-based execution.
Stopword Removal: Stopwords are removed to improve sentence similarity and reduce noise.
Word Overlap Similarity: Jaccard similarity is used for sentence comparison due to its simplicity and efficiency.
Fixed Summary Length
Summary: 2-3 sentences
Bullet Points: Maximum 5
This ensures concise output.
Technologies Used
•	HTML
•	Tailwind CSS
•	JavaScript
•	Classical NLP (TextRank Algorithm)
Installation
1. Clone the repository
git clone https://github.com/Saaki-Rasool/-Text-Summarization-Tool.git
2. Open the project folder
cd -Text-Summarization-Tool
3. Open index.html in browser
Usage
1. Open the application in browser
2. Enter long-form text or select sample article
3. Click on Generate Summary
4. View summary and bullet points
5. Copy or download the result

                                                                                                                                                                                       
                                                                                                                                                                                             Author
                                                                                                                                                                                           Saaki Rasool
                             
                                                                                                                    

