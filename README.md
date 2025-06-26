# Story-Telling-Bot
A comprehensive Story telling and Genration Bot for fariy tale stories
this application is deployed in streamlit, and the models are pulled from ollama and the RAG is supported by ChromaDB

This Project is supposed to help users generate orginial fairy tale stories, based on the prompt which has been prvided by the user
the user can explore by providing different types of prompts and the system will gernerate various stories.

The system works by utilising the Hugging face dataset: FairyTale QA, which has 84 stories, with detailed description of the characters': Name, Age, World detail, genre, Story name, Significane

This data was preprocessed and we create a we chunked the data into 50 to encode that into the RAG system powered by ChromaDB,
then these chunked data is made available to the LLM model when they require it to generate stories.

In this project we have also utilise the capabilities of the multiple model approach where we can use various different LLM offerings,
which helps you explore the storying telling capabilities of those model.
