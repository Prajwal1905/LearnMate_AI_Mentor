# LearnMate AI Mentor
An AI-powered mentor built using IBM Watsonx.ai to help students discover and follow personalized learning pathways. LearnMate understands students’ interests, evaluates their current skill level, and generates adaptive course roadmaps in real time for domains like Frontend Development, Cybersecurity, UI/UX, and more.

## Problem Statement
 Agentic AI for Personalized Course Pathways

Students often feel lost in the sea of online resources. Without structured, personalized guidance, they struggle to identify the most suitable learning path that aligns with their career goals. This results in time wasted, low course completion rates, and lack of clarity in skill development.

## Proposed Solution
LearnMate is an Agentic AI coach powered by IBM Watsonx.ai and Retrieval-Augmented Generation (RAG). It interacts naturally with students to understand their preferences and goals, then creates a customized, evolving course roadmap. It also adapts based on feedback and learning progress, making career building more focused and efficient.

## Technologies Used

- IBM Cloud Lite services  
- Natural Language Processing (NLP)  
- Retrieval-Augmented Generation (RAG)  
- IBM Granite model  

## IBM Cloud Services Used
- IBM Cloud Watsonx AI Studio
- IBM Cloud Watsonx AI runtime
- IBM Cloud Agent Lab
- IBM Granite foundation model


## Target Users
- University students
- Early-career professionals
- Career switchers
- School students exploring technology
- Educators & guidance counselors
- Self-learners and upskillers

## WOW Factors
This agent will empower learners by generating personalized learning roadmaps, aligning educational content with individual goals, and simplifying navigation through vast learning resources. It is designed to support both tech and non-tech pathways, enhance self-paced learning, and adapt dynamically as users progress.

Unique features:
- Personalized roadmap generation based on user interests, goals, and -current skill levels
- Retrieval-Augmented Generation (RAG) using real course data for contextual relevance
- Conversational alignment that refines learning paths through interactive dialogue
- Dynamic roadmap updates that adapt to progress and new goals
- Graceful handling of irrelevant queries to keep the learning journey smooth
- End-to-end built on IBM Cloud Lite & Watsonx.ai, ensuring scalability and robustness


## Key Features
- Conversational skill assessment and interest mapping
- Adaptive course roadmap building
- Natural-language Q&A for roadmap clarification
- Vector Index-based RAG over curated learning content
- Topic restriction and polite redirection for irrelevant questions
- Personalized recommendations across major learning platforms

## How It Works
- Student logs in and initiates a conversation
- LearnMate AI asks for interests and current skill level
- Granite LLM parses input using natural language understanding
- Vector Index fetches trusted course information (from uploaded PDFs or curated metadata)
- AI dynamically creates a course roadmap and explains it in natural language
- Users can ask follow-ups, request adjustments, or track progress

## Screenshots
![image alt](https://github.com/Prajwal1905/LearnMate_AI_Mentor/blob/a7d435fa93c86e2e014c808acdb970944192dd32/Screenshot%202025-08-01%20132023.png)
![image alt](https://github.com/Prajwal1905/LearnMate_AI_Mentor/blob/f28aa6f61df96e74ea4604a0722cd2d83fdc40c6/Screenshot%202025-08-01%20132132.png)

![image alt](https://github.com/Prajwal1905/LearnMate_AI_Mentor/blob/ed8179c36e3534055c041f3ff06d754f91094488/Screenshot%202025-08-01%20132158.png)

![image alt](https://github.com/Prajwal1905/LearnMate_AI_Mentor/blob/1ff0561155e34bfe3381384f28b1243a1620643b/Screenshot%202025-08-01%20132331.png)


## How to Run or Deploy
- Log in to IBM Cloud Lite: https://cloud.ibm.com
- Launch Watsonx.ai Studio
- Create a new AI Agent (LearnMate)
- Upload course PDFs / metadata to a Vector Index
- Configure AI Agent instructions to simulate career counseling
- Restrict off-topic questions and train redirection behavior
- Test in Preview mode
- Deploy using embed snippet, or a custom Streamlit web interface

## Future Scope
- WhatsApp or Telegram chatbot integration
- Voice-based assistant for accessibility
- Integration with IBM Watson Language Translator for regional language support
- Gamified skill tracking and rewards
- Institutional dashboards for counselors or teachers
- User authentication and progress storage

## Useful Links
- [IBM Cloud Lite](https://www.ibm.com/cloud/free)
- [IBM Watsonx.ai](https://www.ibm.com/products/watsonx-ai)
- [IBM Granite Models](https://www.ibm.com/blog/announcement/ibm-granite-models/)
- [IBM SkillsBuild](https://skillsbuild.org/)


## Created By
Crafted with 💙 during the IBM SkillsBuild for Academia Internship 2025
by Prajwal Khade


