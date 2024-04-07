# GPT-Agent webapp for substances using Langchain #
Hi!

This prototype Langchain substance GPT-agent webapp uses the LLMChain and WikipediaAPIWrapper functions from Langchain to query Wikipedia for multiple tasks in one run.

If the user enters a specific substance, the GPT-agent will first query Wikipedia for a short summary of the substance and then give information about the physiological effects the substance has on the human body.
Using the ConversationBufferMemory function from Langchain, the app also displays the query history and the specific Wikipedia article.

The webapp is set up through Streamlit, a very good framework for prototype webapps.

The following libraries are needed for the project:

- os (for setting the OpenAI API-key)
  
- langchain

- streamlit

As always, the code is thoroughly commented.

Have fun!

<img width="548" alt="substance_agent_screenshot" src="https://github.com/march038/Langchain-LLMChain-Wikipedia-Agent/assets/140447879/e4a6eb8f-af94-4e2d-b3ca-700a38a29d24">
