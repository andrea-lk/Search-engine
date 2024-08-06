# Search Engine Project

This project implements a simple search engine that indexes text files and allows users to search for terms within these files. The search engine uses an inverted index to map terms to the files that contain them, and it can handle interactive searches.

## Table of Contents
- [Project Description](#project-description)
- [Features](#features)

## Project Description

The search engine processes a directory of text files, building an inverted index that maps terms to the filenames containing those terms. Users can search for terms, and the engine returns a list of files containing all queried terms. The engine also supports interactive searches through the command line.

## Features
- **Inverted Index Creation**: Processes text files to create an index mapping terms to filenames.
- **File Title Mapping**: Associates each filename with the title of the document it contains.
- **Interactive Search**: Allows users to search for terms interactively through the command line.
- **Search Results**: Displays filenames and document titles matching the search query.
