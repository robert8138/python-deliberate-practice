# Python Deliberate Practice

## Introduction

There has always been a [language war] between Python and R among the Data Scientist, and there doesn't seem to be a consensus on which one is better in the near future. Personally, I used both R and Python, but for very different purposes. I mainly use Hadleyverse (dplyr + ggplot2) packages in R to carry out data analysis and data visualization, while using Python for web scraping, automating small tasks, and building [basic web applications in Flask]. 

By now, I have a pretty good working knowledge of the R language. There are obviously many more things that I can - in particular building and maintaining R packages as well as more [advanced R materials]. Yet, my tastes for learning is usually insatiable (not necessarily a good thing) and the appeal of Python has always been there, for a few reasons: 

* It's a general purpose programming language. There are a lot of good programming and software engineering lessons to be learned that are applicable (which might not be true for R since it's a specialized language)
* Many of the [data stacks] are built using Python (ETL using Airflow, Front-end using Flask, RESTful API supports), being able to use the same language as the rest of the stack means that you are one step closer to production code.

To me, the appeal of Python is not necessarily the Data Analysis part, R is already doing a great job on this. Rather, the appeal of using Python for data work is that you have a higher chance to see how data plays a role within the whole integrated technology stack. Knowing Python is likely to make me a better **end-to-end** Data Scientist and better Software Engineer.

## Deliberate Practice

I am a huge believer in learning by doing, and I see there are a lot of opportunities on the job where I can hone my Python skills through Deliberate Practice:

* **Identify the Top Performers**: I think there are quite a few people at Work (e.g. Dan F.) who can really be a role model for me to follow.

* **Build Practice Plans**: Understand what they've been through to get to where they are today. What is their mental representation when starting out a project. What are the specific tasks, skills, and techniques that I should master. Augment these insights with your current mental representation of Python.

* **Targeted Practice**: If I force myself to switch over to Python for Data Analysis, or contribute to our internal Python Data Analysis packages, there could be many opportunities to practice this.

* **Immediate Feedbacks**: We have a culture of code reviews, both for IC work as well as internal package work. The former is harder because most DS on our team are in the R camp. There's also the weekly Python office hours that should be very useful.

## Project Goal

* Find Mentors who can share with me their mental representation of Python
* Devise a practice project plan (<-this) and figure out the skills to build along the way
* Find constant opportunities to practice Python
* Get immediate feedbacks on the job

## Performance Goal

* Write Pythonic code that other people can understand
* Achieve efficiency parity in Data Analysis and Data Visualization using R v.s. Python
* Pick up good programming or engineering best practice from this
* Write Python Packages (?)

## Project Milestones

* **[Build On Top of the Basics]: Writing Pythonic Code**

    * Function: Use *args and **kwargs to accept arbitrary arguments in function definition
    * Tuples: effective unpacking, use _ for placeholder, swap values without tmp variables
    * List/Dict/Set: list comprehension, dict comprehension. dict.get, set comprehension
    * Strings: use .format, use .join
    * Classes: use __ __ in function and variable name to mark private variables
    * Generator: use generator to lazily load a infinite sequence
    * Modules: writing modules for encapsulation
    * Formatting: pep8 standards
    * Executable script: __name__ = __main__
    * Import: The right way to do imports

* **iPython Notebook**
    
    * Just start writing all your practices as iPython notebooks
    * [iPython Notebook Keybinding]
    * Using the command history
    * Interacting with the OS

* **Pandas For Data Analysis**
    * [Brandon Rhode's Pandas From The Groud Up]: good explanation on index; (row) set_index, sort_index; (column) stack, unstack
    * [dplyr/pandas vignette comparison]
    * [Data School Pandas Tutorials]
        * [Data School Pandas Github iPython notebook]
    * [Tom Augspurgur: Pandas]
    * Introduction to Numpy
        * creating ndarray, data type of ndarray
        * indexing and slicing: basic, boolean, fancy
        * element wise (vectorized) operations
    
    * Introduction to Pandas
        * DataFrame
        * Reading in Data into Dataframe
        * Indexing, Selection, Filtering, Sorting, Ranking
        * Combine and merge DataFrame
        * Reshape and Pivot DataFrame
        * Group By + Data Aggregation

* **Matplotlib For Data Visualization**

    * Figures and Subplots
    * Colors, markers, and line styles
    * Tick, labels, and legends
    * Annotation and drawing on a subplot
    * line plots, bar plots, histogram, density, and scatterplot

* **Writing Functional Programming Python Code**
    
    * Simeon Franklin's Twitter University Class
    * [What generators are for]
    * [Nate Batchelder: Loop like a native]

* **Writing Object Oriented Python Code**
    
    * Simeon Franklin's Twitter University Class

* **(Optional)** 
    
    * [Scikit-learn Machine Learning Library]
    * Writing ETL Jobs 


## Reference

* [Python Tutor Visualizer]
* [Python For Data Analysis]
* [Stanford CS 41: Python]
* [Berkeley CS 88: Python Data Structure]
* [Harvard CS 109: Data Science]
* [Writing Idiomatic Python - Jeff Knupp]
* [Another tutorial on how to write pythonic code]
* [Pandas Cookbook]
* [Udemy course]


[language war]:http://www.dataschool.io/python-or-r-for-data-science/
[advanced R materials]:http://adv-r.had.co.nz/
[basic web applications in Flask]:https://github.com/robert8138/flask-google-calendar-api-project
[data stacks]:https://lab.getbase.com/productive-data-science-python/

[iPython Notebook Keybinding]:https://www.webucator.com/blog/wp-content/uploads/2015/07/IPython-Notebook-Shortcuts.pdf

[Build On Top of the Basics]:http://stackoverflow.com/questions/2573135/python-progression-path-from-apprentice-to-guru
[Nate Batchelder: Loop like a native]:https://www.youtube.com/watch?time_continue=14&v=EnSu9hHGq5o
[What generators are for]:http://simeonfranklin.com/blog/2012/may/22/what-generators-are-for/

[Brandon Rhode's Pandas From The Groud Up]:https://www.youtube.com/watch?v=5JnMutdy6Fw
[dplyr/pandas vignette comparison]:http://nbviewer.jupyter.org/gist/TomAugspurger/6e052140eaa5fdb6e8c0
[Data School Tutorials]:http://www.dataschool.io/easier-data-analysis-with-pandas/
[Data School Pandas Github iPython notebook]:https://github.com/justmarkham/pandas-videos
[Tom Augspurgur: Pandas]:https://www.youtube.com/watch?v=otCriSKVV_8
[Scikit-learn Machine Learning Library]:http://www.dataschool.io/machine-learning-with-scikit-learn/

[Python Tutor Visualizer]:http://www.pythontutor.com/visualize.html#mode=edit
[Python For Data Analysis]:http://www3.canisius.edu/~yany/python/Python4DataAnalysis.pdf
[Stanford CS 41: Python]:http://stanfordpython.com/
[Berkeley CS 88: Python Data Structure]:http://cs88-website.github.io/
[Harvard CS 109: Data Science]:http://cs109.github.io/2015/
[Writing Idiomatic Python - Jeff Knupp]:http://share.sm3.su/writing_idiomatic_python_3.pdf
[Another tutorial on how to write pythonic code]:http://safehammad.com/downloads/python-idioms-2014-01-16.pdf
[Pandas Cookbook]:http://pandas.pydata.org/pandas-docs/stable/cookbook.html
[Udemy course]:https://www.udemy.com/learning-python-for-data-analysis-and-visualization/?ccManual=&couponCode=DEAL19
