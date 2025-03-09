# 100 pandas puzzles

### [Puzzles notebook](https://github.com/ajcr/100-pandas-puzzles/blob/master/100-pandas-puzzles.ipynb)
### [Solutions notebook](https://github.com/ajcr/100-pandas-puzzles/blob/master/100-pandas-puzzles-with-solutions.ipynb)


## Overview of puzzles

| Section Name  | Description |  Difficulty |
| ------------- | ------------- | ------------- |
| Importing pandas  | Getting started and checking your pandas setup  | Easy |
| DataFrame basics  | A few of the fundamental routines for selecting, sorting, adding and aggregating data in DataFrames  | Easy  |
| DataFrames: beyond the basics  | Slightly trickier: you may need to combine two or more methods to get the right answer  | Medium |
| DataFrames: harder problems  | These might require a bit of thinking outside the box...  | Hard |
| Series and DatetimeIndex  | Exercises for creating and manipulating Series with datetime data  | Easy/Medium |
| Cleaning Data  | Making a DataFrame easier to work with  | Easy/Medium |
| Using MultiIndexes  | Go beyond flat DataFrames with additional index levels  | Medium |
| Minesweeper | Generate the numbers for safe squares in a Minesweeper grid | Hard |
| Plotting | Explore pandas' part of plotting functionality to see trends in data | Medium |

## Setting up

To tackle the puzzles on your own computer, you'll need a Python 3 environment with the dependencies (namely pandas) installed.

One way to do this is as follows. I'm using a bash shell, the procedure with Mac OS should be essentially the same. Windows, I'm not sure about.

1. Check you have Python 3 installed by printing the version of Python:
```
python -V
```

2. Clone the puzzle repository using Git:

```
git clone https://github.com/ajcr/100-pandas-puzzles.git
```

3. Install the dependencies (**caution**: if you don't want to modify any Python modules in your active environment, consider using a virtual environment instead):

```
python -m pip install -r requirements.txt
```

4. Launch a jupyter notebook server:

```
jupyter notebook --notebook-dir=100-pandas-puzzles
```

You should be able to see the notebooks and launch them in your web browser.

