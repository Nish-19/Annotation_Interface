# Annotation_Interface

## About
* Python based GUI(Graphical User Interface) for annotation of documents. 
* It annotates documents on a sentence level, assigning each sentence with the tags. 
* Can be used for easing annotation of data for certain NLP(Natural Language Processing) tasks, like novelty detection.

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
* Select the file from the file explorer(opens on clicking browse option) and click okay.
![Screenshot from 2019-11-07 18-22-01](https://user-images.githubusercontent.com/41947720/68368222-8f8a1900-015d-11ea-9a41-4e7fe7d24a18.png)
* Sample preview of the window.
![Screenshot from 2019-11-07 17-58-06](https://user-images.githubusercontent.com/41947720/68368287-bea08a80-015d-11ea-9063-d56621505f1a.png)


## Requirements
* Python 3
* nltk package(natural language toolkit)
  * pip/conda install nltk
* Download punkt tokenizer module of nltk
  * Type 'nltk.download('punkt')' in the python terminal after importing nltk
* wxpython(cross platform gui toolkit for python)
  * [Link for downloading](https://wxpython.org/pages/downloads/index.html) OR
  * 'conda install -c anaconda wxpython' in the terminal for conda users  
