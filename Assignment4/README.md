For the fourth assignment of Digital Media Technology, one of the options is to carry out a small research project based on Text Mining. For this research project, you initially need to compile a small corpus of at least ten different texts. Each text should contain at least 1000 words. The notebook that was developed for this assignment also assumes that the text collection can be divided into two smaller subcorpora. The notebook named ‘Assignment4.ipynb’ uses a number of metrics to compare the texts in these two subcorpora. 
To run the code in the notebook, follow the steps below. 

1. Collect the texts you want to work with from repositories such as [Project Gutenberg](https://www.gutenberg.org/), the [Oxford Text Archive](https://ota.bodleian.ox.ac.uk/repository/xmlui/) or [TextGrid](https://textgridrep.org/). The texts needs to be downloaded as plain TXT files, using UTF-8 encoding. In most cases, you will need to remove the legal conditions and the metadata included in the plain text file. You can do this manually. 
2. Upload the text files to your personal folder on the github repository that was created for the 2024 DMT course. 
3. Collect the URLs of the raw texts
* Click on the text file
* In the menu in the top left corner, click on “Raw”
* Copy the URL form the address bar of the browser. This URL should start with "raw.githubusercontent.com"
4. Open the following URL:
https://github.com/peterverhaar/dmt-2024/blob/main/Assignment4/Assignment4.ipynb
Click on "Download raw file" in the top right corner. 
5. Edit the file in Jupyter Notebook or in VS Code. 
* The URLs of the texts in the first subcorpus should be provided as values for the list named `corpus1_urls`, and the URLs of the texts in the second subcorpus should be in the list named `corpus2_urls`.
* Additionally, provide suitable labels to describe the two subcorpora in the variables named `corpus1_label` and `corpus2_label`.
Save the file. 

The notebook can be run in Google Colab as folows:
1. Open Google Colab via https://colab.research.google.com/
2. Click on "File" > "Upload Notebook" and upload the notebook you have edited in step 4.
3. Click on "Runtime" > "Run All"
4. If the notebook produces error messages, choose "Runtime" > "Restart session and run all"
 
You can also run the notebook using a local installation of Jupyter Notebook or Jupyter Lab. 
Start Jupyter Notebook or Jupyter Lab and open the edited notebook.
1. Click on "Run" > "Run All Cells".
2. If the notebook produces error messages, choose "Runtime" > "Restart kernal and run all cells".
