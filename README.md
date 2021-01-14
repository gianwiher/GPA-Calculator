## Calculates some statistics from the ETH leisungsüberblick html source

### Step 1
Download this repository to your local machine. If you are familiar with git you can do this with the command line, else you can download the zip file by clicking the green button in the top right corner. 

### Step 2:
Go to your [Leistungsüberblick](https://www.lehrbetrieb.ethz.ch/myStudies/studLeistungsueberblick.view?clearRegId=true) and log in with your credentials.

### Step 3:
Right click on the document and save the page as html in the same directory as the jupyter notebook.
**Alternative**: Right click and "View source", then copy-paste the html code into a new text document that you save with the `.html` file extension (something like `grades.html`).


### Step 4: 
Open the `gpacalc.ipynb` notebook and enter the path to the html file. Then run all cells.

**Note** If you have not installed the pandas and matplotlib libraries on your machine, then first run `pip install pandas matplotlib` (This assumes you have a python interpreter on your machine. Else chek out [Anaconda](https://www.anaconda.com/products/individual#Downloads)).
