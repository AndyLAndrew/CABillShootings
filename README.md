## Welcome to California Legislature Bills and Reported Shootings Database analysis!

This is essentially, my first complete GitHub project on my own, but credit must be given to the origin of this along with prior contributors.

	- Nick Fithen
	- Lupe De Anda
	- Kimberly Alonzo
	- Andres Villegas

While the project was initially started in March 2021 as part of a Data Science project assignment, I've decided to continue this endeavor due to the prominence of police shootings in the United States. There is no assumptions taken with the data and currently no significant findings have come about. Hopefully something changes in the future but for now, this is simply a documentation of the process and tools used along with proposed future steps!

________________________________________________________

#### The main project files are jupyter notebooks (.ipynb) separated into two categories:
	- bill_cleanup_and_webscraping.ipynb (Wrangling/Cleaning)
		- takes all bill data, combines, cleans, and prepares for sorting and removal of bills that do not fall under the date preferences for the study as well as any bills that do not fulfill the term sorter. This will need a lot of optimization if I am to properly sort through the bills based on term analysis vs. a simple title analysis. This used to be the main cleaning section for the analysis, however I am now using it as a test ground for my eventual web scraping and NLP analysis of each bill inputted. Essentially a fork from my initial intentions of this project.
	- main_project.ipynb (Initial Visualizations/Test Analysis)
		= This takes "Bills_Dataframe_2009_2021" and conducts the analyses desired, then exporting visualizations from it. While this is close to the final version of this specific notebook, there will be other variations for other forms of analysis. It is essentially completed (at least regarding the format and general structure).

Explanations for these two sections will expand as I continue to work on this project, any questions feel free to contact me.
________________________________________________________

#### Here are brief descriptions of the remaining folders:
- finalized_visualizations
	- Exported visualizations which have been, could be, and/or will be used in presentations to explain findings. Because the only analysis conducted was a test linear regression of shooting frequency and bill proposal frequency by month, there is only one visualization. This will be further populated as more analyses are conducted.
- no_longer_used_code & unused_old_data
	- Base code that inspired this project in the first place! Any code that I contributed to within these notebooks should have my name commented. This entire project wouldn't been possible without the original of course! The code itself is a bit of a mess but the roots are there.
	-Any raw data originally used in the project in the past but are no longer needed
- raw_bill_data
	- raw comma separated value (.csv) files containing basic bill data used in the project. They are needed for the notebook to run.
________________________________________________________

### Versions:
- Python Version 3.9 - Jupyter Notebook
- Libraries: Pandas, Numpy, BeautifulSoup4, Scikit-Learn, Seaborn, NTLK
- Mac OS Mojave 10.14.6