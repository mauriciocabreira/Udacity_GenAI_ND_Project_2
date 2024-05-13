This is the project for Module 2 of the udacity Generative AI Nanodegree (https://www.udacity.com/course/generative-ai--nd608)

Project: Build Your Own Custom Chatbot
In this project I build a custom OpenAI chatbot using a scenario of my choice (below). 
I have selected the character_descriptions.csv data source. This file contains character descriptions from theater, 
television, and film productions. Each row contains the name, description, medium, and setting. 
All characters were invented by an OpenAI model.

First I ask openAI model questions related to two shows in their respective countries, and store the response.
Then, the goal is to create the embeddings and demonstrate that openAI now returns the correct responses from the input file.


If the model responds the same way regardless of whether custom data is provided, that means that the dataset was not 
appropriate for the task. 

First, at the start of the notebook, I wrote a short paragraph describing your dataset choice and setting up the scenario of when this customization would be useful.
Second, at the end of the notebook, I demoed the model Q&A before and after the customization has been performed in order to highlight the changes.
