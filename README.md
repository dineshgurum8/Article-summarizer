# Web Scraping and NLP with Requests, BeautifulSoup, and spaCy

Complete the tasks in the Python Notebook in this repository. Make sure to add and push the pkl or text file of your scraped html (this is specified in the notebook)

This repository is for exploring text using Requests, BeautifulSoup, and spaCy. An article will be scraped from the web and then tokens and lexems will be found from it.

After tokens and lexems are found, the sentences in the article will be scored by how many of the most common tokens and lexems they contain. These scores will be kept in a list and histograms will be made to show the scores' frequencies.

## How to Install and Run the Project
First you must clone the project to your local machine.

    1.Copy the URL of the GitHub Repository you would like
    2.Open Powershell and run the following commands
        cd \
        cd Projects
        git clone https://github.com/**account**/**repo-name**
        cd **repo-name**
        code . 


If .gitignore and/or requirements.txt aren't created, create them.

After creating these files we can now Git add-commit-push using the following code in the terminal
        git add . 
        git commit -m "YOUR MESSAGE HERE"
        git push -u origin main

Once pushed, we now create our virtual environment by running the command:

        py -m venv .venv

Now we will activate the virtual environment using this command:
        .venv\Scripts\activate

Once the virtual environment has been activated, we can install our dependencies from requirements.txt.
Before installing, it's best to update key packages first.
        py -m pip install --upgrade pip setuptools wheel
        py -m pip install -r requirements.txt

Lastly, we will select our VS Code Interpreter

Press Ctrl+Shift+P
Search for "Python: Select Interpreter"
Choose the Interpreter for the local .venv
Now your project is ready and the real fun can begin

Don't forget to regularly Git add-commit-push to keep everything up to date

## Rubric

* (Question 1) Article html stored in separate file that is committed and pushed: 1 pt
* (Question 2) Polarity score printed with an appropriate label: 1 pt
* (Question 2) Number of sentences printed: 1 pt
* (Question 3) Correct (or equivalent in the case of multiple tokens with same frequency) tokens printed: 1 pt
* (Question 4) Correct (or equivalent in the case of multiple lemmas with same frequency) lemmas printed: 1 pt
* (Question 5) Histogram shown with appropriate labelling: 1 pt
* (Question 6) Histogram shown with appropriate labelling: 1 pt
* (Question 7) Cutoff score seems appropriate given histograms: 2 pts (1/score)
* (Question 8) Summary contains a shortened version of the article (less than half the number of sentences): 1 pt
* (Question 8) Summary sentences are in the same order as they appeared in the original article: 1 pt
* (Question 9) Polarity score printed with an appropriate label: 1 pt
* (Question 9) Number of sentences printed: 1 pt
* (Question 10) Summary contains a shortened version of the article (less than half the number of sentences): 1 pt
* (Question 10) Summary sentences are in the same order as they appeared in the original article: 1 pt
* (Question 11) Polarity score printed with an appropriate label: 1 pt
* (Question 11) Number of sentences printed: 1 pt
* (Question 12) Thoughtful answer based on reported polarity scores: 1 pt
* (Question 13) Thoughtful answer based on summaries: 1 pt

