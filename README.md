# Annotation_Interface

## About
* Python based GUI(Graphical User Interface) for annotation of documents. 
* It annotates documents on a sentence level, assigning each sentence with the tags. 
* Can be used for easing annotation of data for certain NLP(Natural Language Processing) tasks.

## Working

* After the environment is set up, run the integration.py python file
* The annotation interface opens, and prompts to select a text file.
* The senteces are tokenized using the nltk tokenizer. Each sentence can be assigned with various tags.
* The four criterion of classification include: -
  * Sentiment Layer
  * Section Aspect
  * Subjective Polarity 
  * Is major comment
* The Section Aspect Layer is multi choice, wheras all the other layers accept a single option.
* To chose other, type the information in the box and tick(select) the other button.
* Click on next to proceed anotating to the next sentence.
* After all sentences are done, a new file with the <file_name>_anotated.txt will be stored in the same location as that of the parent file.

## Window description
The selected sentence is shown on the left with the whole document always present on the right for reference.

## Requirements
* Python 3
* nltk package(natural language toolkit)
  * pip/conda install nltk
* Download punkt tokenizer module of nltk
  * Type 'nltk.download('punkt')' in the python terminal after importing nltk
* wxpython(cross platform gui toolkit for python)
  * [Link for downloading](https://wxpython.org/pages/downloads/index.html)
  * 'conda install -c anaconda wxpython' in the terminal for conda users  
