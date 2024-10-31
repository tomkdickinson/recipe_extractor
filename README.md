# Recipe Extractor

This is an example of how we can use LLMs and Langchain to extract recipes from a variety of different sources online,
and then convert them into the desired Markdown format for personal use.

The objective is to take a URL like this one: https://www.bbcgoodfood.com/recipes/chapli-kebabs-2 and then convert it
into a Markdown file that can be added to a personal recipe book.

# Running the Notebook

To run the examples in this Notebook, I recommend using [Anaconda](https://www.anaconda.com/download) and creating a new
virtual environment.

1. `conda create --name recipe-llms`
1. `conda activate recipe-llms`
1. `conda install pip`
1. `pip install -r requirements.txt`
