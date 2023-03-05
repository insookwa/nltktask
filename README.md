# nltktask
Task on the discipline "Methods of intellectual analysis of natural language" 
Task on the discipline "Methods of intellectual analysis of natural language"
1. Find 100 texts distributed in various categories (for example, 50 positive and 50 negative reviews).
2. Create two own text corpora (or one with categories), each in its own catalog (each catalog has its own category of texts). Text encoding is UTF-8.
3. Using the NLTK toolkit, perform the following experiments:
• analyze similar contexts for positive and negative reviews (with and without stop words);
• plot variance graphs for positive and negative reviews (with and without stop words);
• calculate measures of lexical diversity for positive and negative reviews (with and without stop words);
• build cumulative frequency graphs for positive and negative reviews (with and without stop words);
• select words by their length and frequency for positive and negative reviews (with and without stop words).
4. Develop a naive Bayesian classifier for 100 texts from previously defined categories. Using the developed classifier to perform experiments, varying the following parameters:
• with stop words / without stop words;
• unigrams / bigrams;
• test sample size: 10%, 15%, 20%, 25%, 30%;
As experimental results, output: the value of classification accuracy. All the results of the experiments are summarized in a table (or several tables).
5. Perform thematic modeling of the corpus of texts by the LDA (Latent Dirichlet Allocation) method with subsequent visualization of the generated classes.
6. Using the Owlready2 library (https://owlready2.readthedocs.io/en/v0.37 /) develop an ontology that should be used in the classification procedure of the corpus of texts. It should be possible to save the ontology in RDF/XML format and upload it in the Protégé editor. Be sure to use logical inference!
7. As a result of the research, make a report on the work done.
