# Knowledge Graph Builder using NLP and Web Scraping

## Overview

The **Knowledge Graph Builder using NLP and Web Scraping** is a Python application designed to create and visualize knowledge graphs. It combines web scraping, natural language processing (NLP), and graph theory to extract and represent entities and their relationships from web content. The application processes text data, builds knowledge graphs, and provides visualization to explore the relationships between entities.

## Components

1. **Web Scraping**: Utilizes Beautiful Soup to scrape textual data from web pages.
2. **Data Processing**: Cleans and processes text data, extracting sentences and relevant information.
3. **Knowledge Graph Creation**: Builds a knowledge graph by identifying entities and relationships using NLP.
4. **Visualization**: Generates visual representations of the knowledge graph using NetworkX and Matplotlib.

## How It Works

1. **Web Scraping**:
   - Uses Beautiful Soup to scrape paragraphs (`<p>` tags) from a specified web page.
   - Cleans the scraped text to remove unnecessary spaces and punctuation.

2. **Data Processing**:
   - Extracts sentences from the cleaned text.
   - Processes each sentence to identify entities and relationships using NLP techniques.

3. **Knowledge Graph Creation**:
   - Builds a directed graph using NetworkX with nodes representing entities and edges representing relationships.
   - Adds nodes and edges to the graph based on the extracted information.

4. **Visualization**:
   - Visualizes the knowledge graph using Matplotlib.
   - Highlights specific nodes and relationships for clarity.
