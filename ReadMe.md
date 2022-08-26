# Computing for Research 2022 Bootcamp Materials
This repo houses data and notebooks for the 2022 DSEER "Computing for Research" bootcamp.

## TO DO BEFORE BOOTCAMP BEGINS:
1) Follow the setup instructions on [this page](https://carpentries.github.io/workshop-template/#setup) titled "The Bash Shell", "Git" and "Python". Basically, everything under "Setup" not including "R" or "text editor." 
      - For python, install Anaconda.
      - The videos may be helpful. 
      - These additional tutorials may also be helpful to skim:
            _Unix shell/command line:_ http://swcarpentry.github.io/shell-novice/
            _Version control with git:_ http://swcarpentry.github.io/git-novice/
2) If you don't already have a preffered text editor, install the free version of BBEdit [here](https://www.barebones.com/products/bbedit/). If you already use a text editor you are familiar with, you can skip this step.
3) Make a github account [here](http://github.com)
4) If you use Windows, get yourself a console emulator like cmder or conemu. Alternatively, you can do this all on RCC login nodes if you prefer. Another alternative is installing a windows subsystem for linux, which may sound like overkill now but is really beneficial in the long run.

Please ping the slack if you have any issues! We will have some time to spend on the first day troubleshooting, but if you can get a jump on solving the problem that's preferred.

# Daily Github Pull

Each day we will pull the most recent version of the daily jupyter notebook from this central Github location. Don't get ahead of yourself -- we're tired overworked grad students and will likely be uploading the final version the night before or morning of class. So we'll perform this pull every day together.

### First day
1) open terminal or other application for the bash/zsh command line 
2) `cd` into the directory you want your bootcamp materials to live in
3) `git clone https://github.com/NRT-DSEER/computing-for-research-2022.git`
4) `cd computing-for-research-2022`
5) `cd notebooks`
6) `jupyter notebook`

### Subsequent days
1) open terminal
2) move into bootcamp directory
3) `git pull`
4) `cd notebooks`
5) `jupyter notebook`

# Syllabus

### Instructors:
All the instructors are also on Slack, we prefer that you send us a slack message if you have any questions over sending an email. Slack is only available for students taking the live version of the course. Please check your email for information on how to join slack. [This video](https://www.youtube.com/watch?v=Xm790AkFeK4&ab_channel=TraversyMedia) and others like it may be helpful.

- Sophia Horigan, she/her, 4th year PhD Candidate in Ecology and Evolution, Biological Sciences Division
- Samantha Lapp, she/her, 4th year PhD Candidate in Physics, Department of Physics + Department of Geophysical Sciences
- Haynes Stephens, he/him, PhD in Atmospheric Sciences, Department of Geophysical Sciences

### Teaching Assistants:
Contact over slack or attend office hours (the final 30 minutes of each day, over zoom or in person)

- Megan Barnett, she/her, PhD in Geophysical Sciences
- Prayut Jain, he/him, MS in Analytics, Physical Sciences Division
- Brinda Sapra, she/her, MS in Computational Analysis and Public Policy, Department of Computer Science and Harris School of Public Policy
- Kabir Dubey, he/him, BS in Math & Minor in Computer Science, Department of Mathematics & Department of Computer Science

### Class Time:
- Aug 29-Sept 9
- 09:30am-12:30pm CT 
- We will not have class on Labor Day 9/5.

-You will receive an email with the zoom link for class.


### Recordings:
The folder for the recordings will be posted over Slack or sent over email. We will add each day's recordings a few hours after classtime.

## Day 1: Course Mechanics and Basics 
- Roadmap for the course
- Philosophy
- Course Mechanics
- Getting Daily Course Materials from Github
- Jupyter Notebook Overview
- Basics: Data Visualization
- Basics: Data Structures

## Day 2: Pandas
- Key advantages to using pandas
- Pandas series and dataframes
- Data wrangling: cleaning and slicing dataframes
- Data processing: groupyby and applying functions to dataframes

## Day 3: Advanced Numpy
- Indexing: slicing, specifying elements, boolean indexing
- Masked arrays
- Linear algebra

## Day 4: Xarray and gridded data
- Intoduction to xarray
- Indexing and selecting data
- Computation
- Some advance cases using Dask

## Day 5: Data Visualization
- Making exploratory plots
- Seaborn
- Plotly Express
- Xarray
- Geoviews

## Day 6: RCC
- What is a computing cluster?
- Overview of UChicago's computing resources
- How to connect to Midway
- Using Midway for research

## Day 7: Git & Github
- What is version control, and why use it?
- Introduction to basic Git
- Introduction to Github
- Using Git & Github for research

## Optional: Machine Learning (9/15)
- Introduction to Random Forests

## Optional: Machine Learning (9/16)
- Introduction to Neural Networks
