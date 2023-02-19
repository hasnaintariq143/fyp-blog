# fyp-blog
link to blog is
https://medium.com/@hasnain.tariq143/summslides-8e9b7718a586

here is the blod....

SummSlides
My Final Year Project


Introduction:
Our project is going to convert pdf form of any book into slides (.pptx) form displaying important key points. Slides will contain headings and sub-headings.

Objective:
The objective of the project is to help students who have to make notes and teachers who have to make slides for teaching. Our project is going to help both teachers and students.

Scope:
SummSlides is limited to some scope. Here are the some limitations and constraints of our project.
1. Only pdf files will be entertained. No other formats of files will be accepted.
2. Project will make slides of maximum 40 pages.
3. Standard pdf documents will be entertained only.
4. File size should not be greater than 1 MB.

Final Product:
Final product will be a web based application on which users will upload pdf document and get slides of the document.

Methodology:
Python is used as for the project and for the front-end, React-Js is used. To link React-Js with python as backend programming language, Flask has been used.

Technical Challenges:
There are many technical challenges for the project. The main technical challenge was how and on what basis, the key points from the text/paragraph should be extracted. For this, we studied and observed many NLP algorithms. The first one was BERT algorithm. Here we thought the summary of a paragraph should be a key point for slides. But the issue here was, when we implement the BERT algorithm, it sometimes collapses on the text we provided. After some research, we came to know that BERT is trained for larger paragraphs and texts. On small paragraphs, it does not work properly.
Then we implement LDA algorithm, but there was the same issue. LDA requires smaller text than BERT but it was still not a perfect algorithm because our dataset was still a much shorter than the dataset LDA requires.
Then we came up with a new idea that instead of summarizing the text, we should find the most ranked sentence or the sentence with the most importance and make that sentence as bullet/key point in the slides. For this, we used LexRank and TextRank algorithms. Now, next we are going to make slides.
