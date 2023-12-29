
<p align="center">
  <img src="document_search_circle.png" alt="Image" width="200" height="200" style="border-radius: 50&#37;; object-fit: cover; overflow: hidden;" />
</p>

### Project Summary for Vue Quasar Application with AI Chatbot for Guide121

#### Overview
This project was undertaken at Guide121, a startup specializing in creating advanced chatbot solutions, where I am currently employed as a Data Scientist. We aimed to enhance the intelligence of digital assistants provided to clients by developing a Vue Quasar application equipped with a tool and dashboard. This system utilizes semantic search and AI-powered chatbot capabilities to offer user-friendly responses to frequently asked questions (FAQs).

#### Objective
The primary goal was to empower Guide121's platform, which allows clients to configure chatbot flows and functionalities, with advanced response capabilities. This was achieved by integrating semantic search and Large Language Models (LLMs) to enhance the chatbot's ability to understand and respond to user inquiries effectively.

#### Implementation
The developed solution allows users to upload a CSV file containing question-and-answer pairs. These pairs are then transformed into vector embeddings using OpenAI's model, facilitating cosine similarity searches. To further refine the response accuracy, we designed three additional tools:

1. **Similarity Match & ChatGPT-3.5-turbo Integration**: A feature that can be toggled to manage costs, providing the three best similarity match answers as prompts to ChatGPT-3.5-turbo. The AI then selects the most appropriate response based on the user's question.
2. **Validation Layer**: Utilizes the GPT-3.5-turbo model to validate the best answer obtained from the similarity search.
3. **Dashboard & Continuous Learning**: A comprehensive dashboard allows users to view metrics and graphs related to accuracy, performance time, and total number of calls with detailed date granularity. It also includes a reporting feature where users can intuitively add new questions identified as incorrectly answered by the second layer, thereby improving the model's learning capacity.

#### Additional Features
- **Word Cloud Visualization**: To provide insights into the most asked and answered topics, a word cloud was developed. This feature visually represents the topics most prevalent in the chatbot flow related to FAQs.

#### Impact and Benefits
The project significantly enhanced the chatbot's capability to understand and respond to FAQs, improving user experience and the efficiency of Guide121's client chatbots. The addition of continuous learning and validation layers ensures the system evolves and maintains high accuracy and relevance over time.










