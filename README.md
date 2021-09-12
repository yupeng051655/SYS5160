# SYS5160
the final project of SYS5160 (System Integration)


Configuration:
1. You need to install python3 before installation
2. open the project and activate the python environment: source env/bin/activate
	- source env/bin/activate
3. install the python libraries
	- pip install -r requirements.txt
4. run the Django server
	- cd mysite
	- python manage.py runserver


The project implement data mining and machine learning to develop recommendation system using content-based filtering and collaborate filtering.

1. Data preprocessing 
In the data clearning, the RS converts all letters into lower cases. It removes punctuations from each chunk and tokenized the documents to remove stopwords. We relied on the ‘nltk’ library to identify stopwords. In addition, we do lemmatization to transform words into their baseform according to the intended meaning and context surrounding that sentence.



