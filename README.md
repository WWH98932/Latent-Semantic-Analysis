# Latent-Semantic-Analysis
UCLA Master of Applied Economics Econ 423 Assignment

Download the file LSA.txt from CCLE (2.M.3. LSA). This file consists of 11 class reviews (from a class in the past year) separated by tags 'XXX\<review number\>'. In other words, your corpus consists of 11 documents, and each document is preceded by a heading that indicates the start of a new file and the file number.

#### You will need to write a Python program that meets the following requirements:
---------------------------------------------------------------------------------
- Create a TD Matrix for this corpus (lower case all terms). This will be a NumPy matrix/array with first axis (rows) representing terms that have appeared in the corpus, and the second axis (columns) representing documents in the corpus. 
---------------------------------------------------------------------------------
- After the TD matrix has been built,  your program should print the matrix to a text file called "tdm.txt". Make sure the text file is created by your program, do not assume it has already been built. In addition,  make sure the matrix follows the convention that it has documents as columns and terms as rows sorted by terms in alphabetical order. 
---------------------------------------------------------------------------------
- Your program should include a function to return the term frequency when given a term and document as arguments. Please have the function header for this function is the following:
def returnTermFrequency (term, document):
      #your code here
#### The type of term is a string while the type of document is an integer.
---------------------------------------------------------------------------------
- In addition to creating a TD matrix, have your program create a TFIDF matrix similar in structure to the TD matrix above . Output that matrix to a file called "tfidf.txt".  
---------------------------------------------------------------------------------
- Your program should include a function to return the TFIDF value when given a term and document as arguments. Please have the function header for this function as the following:

def returnTFIDF (term, document):
      #your code here

#### The type of term is a string while the type of document is an integer.
---------------------------------------------------------------------------------

Submit your Python program  along with the 2 txt files that contain your matrices.
