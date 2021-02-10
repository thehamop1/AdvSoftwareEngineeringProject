# Business Goal/Objective of the proposed application
    - The goal of this project is to implement a conversational interface to source control. The application will use either voice or text as a means for the user to interface with the source control application. The application will allow the user to make queries to the source control database (git history). This should allow non-experienced users to gain information about their projects.  

# Technology Stack
    - Python (If a backend is needed)
    - Javascript/React
    - Google Diagflow ES
    - Github API
    - AWS S3 Bucket

# Sprint 0
## Business Goal/Objective
    - Research various reference architectures/methogologies 
        - Papers will be split into groups. Members will read each set of papers in order to understand various architectures. 
        - Set 1:
            -Chatbots: Are they really useful?: https://www.academia.edu/download/35586044/Bayan_Abu-Shawar_and_Eric_Atwell.pdf
            - CHATBOT: Architecture, design, & development:  https://www.academia.edu/download/57035006/CHATBOT_thesis_final.pdf
        - Set 2:
            - An Overview of Chatbot Technology: https://link.springer.com/chapter/10.1007/978-3-030-49186-4_31
            - Designing Conversational Interfaces to Reduce Dissonance: https://dl.acm.org/doi/abs/10.1145/3197391.3205439
        - Set 3:
            - Measuring User Experience in Conversational Interfaces: A Comparison of Six Questionnaires: https://www.scienceopen.com/document_file/24d11410-aa32-4601-b8f5-0e781135d61a/ScienceOpen/BHCI-2018_Kocaballi%20A.pdf
            - A Smart Advisor for Software Delivery - A Bot Framework for Awareness, Alerts and Advice: https://ieeexplore.ieee.org/abstract/document/8823628
        - Set 4:
            - Medbot: Conversational  Artificial Intelligence Powered Chatbot for Delivering Tele-Health after COVID-19: https://ieeexplore.ieee.org/abstract/document/9137944
    - Setup project in source control
    - Setup API accounts
    - Verify all devs have environment setup

## User Stories
    - As a user I want to be able to clearly understand how the application is structured

## Technical Tasks
    - Set a VS Code on everyones machine
    - Verify all members have access to the repository
    - Fill in backlog
    - Read API docs
    - Find resources for the stack we're using
    - Distribute tasks among members
    - Design an interface (voice/text GUI)

# Sprint 1
## Business Goal/Objective
    - Get something tangible working. The basic interface for the application should be working for users to evaluate.

## User Stories
    - I want to be able to speak/text and interact with my project

## Technical Tasks
    - Get basic functionality for the rest APIs working
    - Get a basic GUI running/Converstaional Interface
    - Understand how to add actions to the diagflow dashboard
    - Have queries working with the github api

## Sprint 2
## Business Goal/Objective
    - Get a functional set of end to end actions working for the user to begin testing.

## User Stories
    - As a user i want to get meaningful interaction with my project and perform basic tasks with my source control.

## Technical Tasks
    - Design an end to end test
    - Have a set of actions a user can perform
    - Have a fully designed interface for the application
        - At the very least this should be a full mock-up depending on the complexity 
    - A basic set of unit tests