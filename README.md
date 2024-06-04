<h2>Hello There</h2>

<h4>
This repository contains a project on A 2-LLM Agent based system. The 2 agents are News Researcher and News Writer. Upon giving a specific topic, the News Researcher browses Google to find legitimate souces of information on the technical aspects of the topic. The search results, given as output by the first agent, the News Researchers, is used by the second agent, the News Writer, to create an engaging 4-paragraph article, which gets stored in a markdown file. 


CrewAI is used to develop the system. Goolge Gemini API is used as the beckend LLM model and SERPER API has been used as tool to perform Google search on the given topic. 


To run the project on your local system, in the LLM_Agent_Researcher folder create a local environment with all the required libraries and modules installed.




In command prompt window, run:

*conda create -p venv python==3.10 -y*

, to create the environment. 




Then run:

*pip install -r requirement.txt*

, to install the required modules in the environment.




Create a Google Gemini API key from [https://ai.google.dev/gemini-api/docs/api-key] and SEPER API key from [https://serper.dev/] and insert them in .env file and save it. 



And you're good to go!! </h4>
