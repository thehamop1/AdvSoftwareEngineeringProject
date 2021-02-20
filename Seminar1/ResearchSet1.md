# Research Set 1

## Key Points
    - Types of bots
    - History
    - Vocab
    - Measuring performance
    - Design

## How is this significant to designing conversational interfaces?
    - These papers give a basic outline for the current state of chat bot technologies. They also give background on the history of bots in order to give context to modern tech. 


## Points to bring up during seminar

# Types of chatbots
    - Dialogic Agent
        - Understands the user and generate appropriate responses. 
    - Rational Agent
        - This type of bot must understand the user and also retrieve data from an external source of knowldge often refered to as a corpora of data. In a buisness context this could be a database or an external API.
    - Embodied Agent
        - This type of agent is the final extension of the first two. It not only understands the user and can provide relavant data back to the user but it can also be percived as human-like by the user. The first chat bots (which were rule based) were even given names in order to create this illusion. Today in the UX design of conversational interfaces the concept of a persona still exists. Think of the voices you can select in personal assistants. (Immitation Game via Turing)
# History
    - Plenty of historical bots exist and were often created as proofs of concepts and toys. For example ELIZA, ALICE, and even the emacs Psycotherapist were chatbots created during the early days of chat bots. Many of these used markup languages in order to perform pattern matching. For example ALICE had its own markup language (an extension of XML) created in order for maintainers to add patterns to match against. These are commonly known today as intenets and something found in IBM watson and DialogFlow (Google). It wasnt until later that Machine Learning techniques were devleoped in order to solve the maintability issue of pattern matching techniques. These two types of technologies are the methods that most APIs use now. 
# Performance
    - Depending on the lense that you choose to evaluate a chat bot from you might get varying levels of performance. In the context of software engineering in most buisness contexts the metric that should be used is user satisfaction.
        - Other criteria may be human-likeness (AI Researchers)
        - Information Retrival
        - ETC.
    - Other Metrics to consider:
      - PARIDASE framework (Mostly theoretical)
        - Uses confusions matricies based on wrong responses from bot
      - "Visual Look" (human-likeness Van Vugt)
      - User survey
      - Right vs Wrong responses based on both general and domain-specific knowledge
      - Easy of navigation
      - Ability to repair converstaion
      - Personality 
        - In this case it refers to the bots ability to do things like:
          - Recall the user's name
          - User empowered to select gender of the bot (CHATBOT_Architecture)
          - The user can see chat history
          - The user can export data from the bot
          - The bot can access external body of knowldege
# Design
    - 