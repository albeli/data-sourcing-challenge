To create a `README.md` for your project, you should include an overview of the project, detailed instructions on how to set it up and run it, and any other relevant information. Here's a template to help you get started:

---

# Data Sourcing Challenge

## Overview
This project is focused on preparing data for a movie recommendation system. It involves extracting data from The New York Times API and The Movie Database API, merging and cleaning this data for use in natural language processing methods.

## File Structure
- `retrieve_movie_data.ipynb`: Jupyter notebook with starter code.
- `.env.example`: Example environment file. Rename to `.env` and add your API keys.
- `output`: Folder for the final CSV file.

### Part 1: Access the New York Times API
- Query the New York Times Article Search API for movie reviews.
- Store the retrieved reviews in a list.
- Convert this list into a DataFrame.
- Extract movie titles for the next part of the challenge.

### Part 2: Access The Movie Database API
- Use the movie titles from Part 1 to query The Movie Database.
- Store the movie details in a list.
- Convert this list into a DataFrame.

### Part 3: Merge and Clean the Data for Export
- Merge the DataFrames from the two APIs.
- Clean and format the data.
- Export the final DataFrame to a CSV file.

## Execution Instructions
1. Run `retrieve_movie_data.ipynb` in Jupyter Notebook or JupyterLab.
2. Follow the steps outlined in the notebook for each part of the challenge.
3. The final output will be a merged and cleaned CSV file in the `output` folder.

## Dependencies
- Python 3
- Pandas
- Requests
- Jupyter Notebook or JupyterLab

## Notes
- Respect the API rate limits for both The New York Times and The Movie Database.
- Do not push your API keys to the public repository.

