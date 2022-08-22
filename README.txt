Dependencies:

- csv	:  to manage data
- pandas : for dataset handling
- numpy : support for calculations
- math :  for mathematical operations
- nltk : for tokenization, stemming and using stopwords
- collections : for python dictionary
- unidecode : to convert into ASCII characters
- pickle : to save data objects
- re : for regular expression
- math : for mathematical operations
- string : for string manipulation
-tensorflow:for bert model finetuning
-pytorch: for bert model finetuning
-transformer:for loading the bert model

I have automated those installs but if any other library is missing install them by writing pip install library_name in the command line.
(for Q3 i am sharing the output fies only since program taking alot to run,I used lab system to run the file and generate the output,its not possible with System with 8gb RAM)

Since I have also uploaded pickle file for each ,hence I have commented out the reading of files to decrease the run time,but if asked,I can remove comment and run it.

References:
Since BERT Transformer was new concept for me,I reffered  some blogs to finetune the model.
   1-https://towardsdatascience.com/
   2-https://www.analyticsvidhya.com/
   3-Also referred some github and colab repositories to understand the working of certain libraries.
   
Please put all the required datasets for each Question part of the assignment.

How to run:
1- Unzip 21111005-assignment2.zip
2. Place all the Required  dataset folder in this directory.
3- open the current directory in the terminal and type "make run " this 
command will first install all the packages and then  run the scripts inside it and then make 40 files in the for Q1,1 weight file for Q2 and output files for Q3.
