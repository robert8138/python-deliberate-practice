# Python Deliberate Practice

## Motivation

[Language war] between Python and R is one of the most frequently discussed topics among the Data Scientist, and there doesn't seem to be a consensus on which one is better. Personally, I used both R and Python, but for very different purposes. I mainly use tidyverse packages (dplyr + ggplot2) to carry out data analyses and data visualization, while using Python for web scraping, task automations, and building [basic web applications in Flask]. 

By now, I have a pretty good working knowledge of the R language. There are obviously many more things that I can learn - in particular building and maintaining R packages as well as more [advanced R materials]. Yet, the appeal of Python has always been there for me for a few reasons: 

* It's a general purpose programming language, so presumably it is a lot easier to learn good software engineering principles. (What are they though?)
* Many of the [data stacks] are built using the tools in the Python ecosystem (ETL using Airflow, Front-end using Flask with RESTful API supports, Machine Learning using scikit-learn) - being able to use the same language for different parts of the data stack will bring prototypes closer to production.

To me, the appeal of Python is not necessarily the Data Analysis part, R is already doing a great job on this. Rather, the appeal of using Python for data work is that you have a higher chance to see how data plays a role within the whole integrated technology stack. Knowing Python is likely to make me a better **end-to-end** Data Scientist and better Software Engineer.

## Deliberate Practice

I am a huge believer in learning by doing, and there are a lot of opportunities on the job where I can hone my Python skills through Deliberate Practice:

* **Identify the Top Performers**: I think there are quite a few people at Work (e.g. Dan F.) who can really be a role model for me to follow. Understand what they've been through to get to where they are today. What is their mental representation that I do not have about Python.

* **Build Practice Plans**: Ideally, based on the rough understanding of that mental representation:

    * Define clear goals and select learning materials
    * Create deadline and milestones for the project
    * Estimate time required and come up weekly schedules

  Augment these insights with your current level of mental representation of Python to improve your understanding.

* **Targeted Practice**: If I force myself to switch over to Python for Data Analysis, Data visualization, Modeling, or contribute to our internal Python Data Analysis packages, I can maximize my time practicing this skill, which is high leverage.

* **Immediate Feedbacks**: We have a culture of code reviews, both for IC work as well as internal package work. The former is harder because most DS on our team are in the R camp. There's also the weekly Python office hours that should be very useful. Find constant opportunities to get feedback as much as you can.

## Performance Goals

* **[Immediate]** Learn to write pythonic code
* **[Shorter term, easiest to practice]** Write re-usable, modular, tested code for my data work and knowledge posts
* **[Medium term, harder to practice]** Achieve efficiency and feature parity on Data Analysis using Python compared to R
* **[Longer term, hardest to practice]** Write tools. Being able to work on projects that span the entire data stack using Python, apply good software engineering principles to these projects

## Project Goals

* **Outcome**: I want to move my data stack to Python completely. This means my day-to-day data analysis work will be done in Python instead of R, make my code as pythonic as possible. Become a Contributor to Airpy / tools, and take on one bigger Python project (ML, Data Viz ...etc).

* **Curriculum**: I want do everything that I can to go through all the basic materials in Pandas/Matplotlib combo. Expose yourself to functional programming, OOP, testing in Python, or even make tools. Get feedbacks from Airpy team members.

* **Timeframe**: Efficiency parity by end of October. One contribution to Airpy by Mid November. One ongoing big project touching different stacks in Python by the end of 2016.

## Project Milestones

* **Learning Python & Best Practices**
    * [Plateau of Productivity]
    * [Columbia Data Scientist Style Guide]

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
        * [More Pandas Questions Answered]
        * [Other resources]
    * [Tom Augspurgur: Pandas]
    * [Coursera: Introduction to Data Science in Python]: This course is basically about Pandas

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

    * [BIDS Intro to Matplotlib]: The 800 pound gorilla, everything is customizable, but very low level
    * [Seaborn]: Good for statistical visualization. I still find it a bit limited on the type of simple plots it can do
    * [Bokeh]: Interactive, web browser base data visualization
    * [A Dramatic Tour through Python’s Data Visualization Landscape (including ggplot and Altair)]

* **Writing Object Oriented Programming Python Code**
    
    * [Jeff Knupp's OOP Post]
    * Simeon Franklin's Twitter University Class
    * [Objected Oriented Programming For Scientist]
    * [BIDS Python Bootcamp OOP section]

* **Writing Functional Programming Python Code**
    
    * Simeon Franklin's Twitter University Class
    * [What generators are for]
    * [Nate Batchelder: Loop like a native]

* **Other Parts Of Python Data Stacks** 
    
    * [Scikit-learn Machine Learning Library]
    * Writing ETL Jobs

* More Software Engineering Principles
    
    * [Testing]
    * [Testing For Scientist]
    * [Automation And Make]


## Reference

* [Python Tutor Visualizer]
* [Python For Data Analysis]
* [Stanford CS 41: Python]
* [Berkeley CS 88: Python Data Structure]
* [Harvard CS 109: Data Science]
* [Berkeley BIDS Python bootcamp]
* [Python Computing For Data Science]
* [Writing Idiomatic Python - Jeff Knupp]
* [Another tutorial on how to write pythonic code]
* [Pandas Cookbook]
* [Udemy course]
* [Chris Albon's notes]

[Language war]:http://www.dataschool.io/python-or-r-for-data-science/
[advanced R materials]:http://adv-r.had.co.nz/
[basic web applications in Flask]:https://github.com/robert8138/flask-google-calendar-api-project
[data stacks]:https://lab.getbase.com/productive-data-science-python/

[Plateau of Productivity]:http://pbpython.com/plateau-of-productivity.html
[Columbia Data Scientist Style Guide]:http://columbia-applied-data-science.github.io/pages/lowclass-python-style-guide.html

[iPython Notebook Keybinding]:https://www.webucator.com/blog/wp-content/uploads/2015/07/IPython-Notebook-Shortcuts.pdf

[Build On Top of the Basics]:http://stackoverflow.com/questions/2573135/python-progression-path-from-apprentice-to-guru
[Nate Batchelder: Loop like a native]:https://www.youtube.com/watch?time_continue=14&v=EnSu9hHGq5o
[What generators are for]:http://simeonfranklin.com/blog/2012/may/22/what-generators-are-for/

[Brandon Rhode's Pandas From The Groud Up]:https://www.youtube.com/watch?v=5JnMutdy6Fw
[dplyr/pandas vignette comparison]:http://nbviewer.jupyter.org/gist/TomAugspurger/6e052140eaa5fdb6e8c0
[Data School Pandas Tutorials]:http://www.dataschool.io/easier-data-analysis-with-pandas/
[Data School Pandas Github iPython notebook]:https://github.com/justmarkham/pandas-videos
[More Pandas Questions Answered]:https://www.youtube.com/watch?v=CWRKgBtZN18&list=PL5-da3qGB5ICCsgW1MxlZ0Hq8LL5U3u9y&index=31
[Other resources]:http://www.dataschool.io/best-python-pandas-resources/
[Tom Augspurgur: Pandas]:https://www.youtube.com/watch?v=otCriSKVV_8
[Coursera: Introduction to Data Science in Python]:https://www.coursera.org/learn/python-data-analysis/home/welcome
[Scikit-learn Machine Learning Library]:http://www.dataschool.io/machine-learning-with-scikit-learn/

[BIDS Intro to Matplotlib]:https://www.youtube.com/watch?v=j5P822TSCKs
[Seaborn]:https://stanford.edu/~mwaskom/software/seaborn/
[Bokeh]:http://bokeh.pydata.org/en/latest/
[A Dramatic Tour through Python’s Data Visualization Landscape (including ggplot and Altair)]:https://dansaber.wordpress.com/2016/10/02/a-dramatic-tour-through-pythons-data-visualization-landscape-including-ggplot-and-altair/

[Objected Oriented Programming For Scientist]:http://tjelvarolsson.com/blog/object-oriented-programming-for-scientists/
[Jeff Knupp's OOP Post]:https://jeffknupp.com/blog/2014/06/18/improve-your-python-python-classes-and-object-oriented-programming/
[BIDS Python Bootcamp OOP section]:https://www.youtube.com/watch?v=HQ0q6oMpOEs

[Testing]:http://katyhuff.github.io/python-testing/
[Testing For Scientist]:http://tjelvarolsson.com/blog/test-driven-develpment-for-scientists/
[Automation And Make]:http://swcarpentry.github.io/make-novice/

[Python Tutor Visualizer]:http://www.pythontutor.com/visualize.html#mode=edit
[Python For Data Analysis]:http://www3.canisius.edu/~yany/python/Python4DataAnalysis.pdf
[Stanford CS 41: Python]:http://stanfordpython.com/
[Berkeley CS 88: Python Data Structure]:http://cs88-website.github.io/
[Harvard CS 109: Data Science]:http://cs109.github.io/2015/
[Berkeley BIDS Python bootcamp]:https://bids.berkeley.edu/news/python-boot-camp-fall-2016-training-videos-available-online
[Python Computing For Data Science]:http://profjsb.github.io/python-seminar/
[Writing Idiomatic Python - Jeff Knupp]:http://share.sm3.su/writing_idiomatic_python_3.pdf
[Another tutorial on how to write pythonic code]:http://safehammad.com/downloads/python-idioms-2014-01-16.pdf
[Pandas Cookbook]:http://pandas.pydata.org/pandas-docs/stable/cookbook.html
[Udemy course]:https://www.udemy.com/learning-python-for-data-analysis-and-visualization/?ccManual=&couponCode=DEAL19
[Chris Albon's notes]:http://chrisalbon.com/