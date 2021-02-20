# Research Set 2

## Key Points

## How is this significant to designing conversational interfaces?


## Points to bring up during seminar
# Formal Definition
    - A computer program designed to simulate conversation with human users, especially over the internet.

# Benefits of chat bots
    - Offer seemless integration for companies to tie their services into different platforms.
        - For example a buisness can use facebook messanger in order to sell things directly to customers

# History
    - ALICE's AIML markup system was eventually replaced with Chatscript, an expert system, which consists of its own scripting language and interpreter. 
        - This was a means of engineering around a problem with rule based systems who did not keep any memory of previous statements in the conversation. Chatscript gave the bot a means of remembering previous statemtns in order to move the conversation forwards.
        - Further advancements in these scripting languages came about like RiveScript that gave support for more modern languages such as Go, Java, Python, etc
        - The most recent technology to try to tackle this problem has been machine learning in the form of NLP/NLU.

# Conversational Interface Concepts
    - Entity: A tool for extracting parameter values:
        Eg: What is the weather in Greece?
            - The intenet of the user is to retrieve the weather
            - The entity value is greece
    - Context: 
      - Eg: 
        - User: Turn off the fan
        - User: Turn it on
        - The second sentence should have the intent of the last command. This is what is meant by context.

# Knowledge Domains
    - Knowledge Domain: knowledge domain considers the knowledge a chatbot can access or the amount of data it is trained upon
    - Open Domain: General topics that a bot may talk about
    - Closed Domain: Domain specific knowledge that may come from a database/3rd party api

# Informative ChatBots vs Conversational Bots
    - The main difference here is that informative chatbots are meant to robtically retrieve data from a source whereas conversational bots are meant to appear human and respond to the user appropriatley. 

# Design: Human-likeness
    - The context of where the bot lives drives the designers to either add or remove human likeness. Bias metrics may lead to skewed metrics in bot effectiveness. 
      - Example: While driving a bot may have its human-likeness via gendered voice removed becuase in the context of driving the user only really cares about executing tasks.
    - Although domain experts may design the conversational flow in chat bots the fact that humans are interacting with computers and not the experts always leaves some amount of friction in the conversation. This is largely due to the fact that the conversation has to gneeralized across all users. 

# Dissonance
    - Providing the user with the context and intenet can reduce dissonance in the conversation
    - Providing options can make it easier for the user to navigate when things are unclear or go wrong.