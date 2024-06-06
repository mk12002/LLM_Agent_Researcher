# Researcher-Writer Agent System

This repository contains a project on A 2-LLM Agent based system. The 2 agents are News Researcher and News Writer. Upon giving a specific topic, the News Researcher browses Google to find legitimate souces of information on the technical aspects of the topic. The search results, given as output by the first agent, the News Researchers, is used by the second agent, the News Writer, to create an engaging 4-paragraph article, which gets stored in a markdown file. 

CrewAI is used to develop the system. Goolge Gemini API is used as the beckend LLM model and SERPER API has been used as tool to perform Google search on the given topic. 
## Installation
Create environment in local repository with all the required libraries and modules installed.

For environment creation in the specific folder, in command prompt window, run:

```bash
conda create -p venv python==3.10 -y
```

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install required modules.

```bash
pip install -r requirement.txt
```

## Usage

Create a Google Gemini API key from [Google Gemini](https://ai.google.dev/gemini-api/docs/api-key) and SEPER API key from [Serper](https://serper.dev/) and insert them in .env file and save it. 

And you're good to go!!
## License

[MIT](https://choosealicense.com/licenses/mit/)
