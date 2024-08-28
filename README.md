# MultiModal-Question-Answering
This project combines both text and images to perform queries on a database containing data in different formats
It combines transformers, Optical Character Recognition, Embedding, and a vector database( ChromaDB)
## Why MultiModal QA?
Ever taken a photo, maybe of a receipt or even a screenshot, saved it in your device, and gone a while without using it? Three months later you need it but you can't find it. This happened to me quite a lot and is what led to this project. What if there was a simple way to search for an image simply by the text content the image contained? And you know what the best part is? You don't even need to remember the exact text that was in the image.
  ## WORKFLOW
Create the vector db -> create a multimodal collection inside the database specifying the embedding function and data loader -> read the image files from your folder -> extract information from it and save it -> upload the information into the multimodal collection - > perform a query

## Getting Started

  1. Create and log in to your Google Colab account (it's free :) )
  2. Create a folder images and upload to it the image files you want to index
  3. Run the cells in this notebook
## Technologies used
  1. transformers
  2. chromadb

