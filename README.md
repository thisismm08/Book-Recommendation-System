This repo contains all of the code  "Build a Semantic Book Recommender with LLMs ". There are five components:

Text data cleaning 
Semantic (vector) search and how to build a vector database. This allows users to find the most similar books to a natural language query (e.g., "a book about a person seeking revenge").
Doing text classification using zero-shot classification in LLMs. This allows us to classify the books as "fiction" or "non-fiction", creating a facet that users can filter the books on.
Creating a web application using Gradio for users to get book recommendations.

A requirements.txt file containing all the project dependencies is provided as part of this repo.

In order to create your vector database, you'll need to create a .env file in your root directory containing your OpenAI API key. Instructions on how to do this are part of the tutorial.

The data for this project can be downloaded from Kaggle.
