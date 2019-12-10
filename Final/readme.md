Knowledge Graph


Python Files:
1. Knowledge-Graph1.ipynb :: The original File
2. Previous-Attempt :: File with KG made using Adjecency Matrix

Instructions:
1. Run the codes in a linear manner from top to bottom.
2. The Input goes in the last section named 'Search Here'.
3. The rules to extract entities and relations in a simple sentence is in the functions 'get_entities' and 'get_relation' respectively.
4. 'get_entities' outputs two strings, sunject and predicate while 'get_relation' outputs the relation between the entities, both from a simple sentence.
5. In the function 'nodes_relation', above two functions have been used to output three strings, sunject, verb and predicate, from a comples sentence and a group of sentences.
6. The above strings has been stored in dataframe with three columns and NetworkX has been used to visualize the KG

Libraries Used::
1. Spacy
2. Pandas
3. NetworkX
4. Matplotlib
5. gensim


Utilities:
1. Gita.csv ::: Contains all the purports of the text, each one in different row.
2. GoogleNews-vectors-negative300.bin  ::: This needs to be DOWNLOADED from this link "https://drive.google.com/file/d/0B7XkCwpI5KDYNlNUTTlSS21pQmM/edit?usp=sharing"
This file is large ~ 3GB 

Both the files should be in the same folder as that of the file Khowledge-Graph1.ipynb


