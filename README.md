# Mark-Twain-Corpus

This repo is a corpus of five of Mark Twain's most popular novels. It includes the orginal data sources, data prep, vectorization, unsupervised modeling methods, sentiment analysis, and more. 

The raw data is located in the epubs directory and the sources are linked here: 
* The Adventures of Tom Sawyer (https://www.gutenberg.org/files/74/74-0.txt)
* The Adventures of Huckleberry Finn (https://www.gutenberg.org/files/76/76-0.txt)
* The Gilded Age: A Tale of Today (https://www.gutenberg.org/files/3178/3178-0.txt)
* The Prince and the Pauper (https://www.gutenberg.org/files/1837/1837-0.txt)
* Life on the Mississipp (https://www.gutenberg.org/files/245/245-0.txt)

There are two .ipynb files in the repo that provide all code necessary to convert the raw text files and do analysis on them. The DataPrepF0-F3 jupyter notebook converts the raw text files to the LIB.csv, TOKEN.csv, VOCAB.csv, and LIB.csv. The VectorizeF4-F5 file uses the files created from the previously mentioned jupyter notebook to create the TFIDF.cav and performs analysis. 

There is also a sales_nrc.csv that was used for sentiment analysis and a report.docx that details the findings. 
