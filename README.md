# Project Title

Taiwan-Smart-Travel-AI

## Project Description

Taiwan Smart Travel AI is designed to elevate tourists’ travel experience by offering personalized and tailor-made holiday recommendations across Taiwan. By understanding each traveler’s unique tastes and preferences, this AI aims to help users discover destinations that best match their interests, ensuring a more fulfilling and memorable journey. The data were manually collected from The Ministry of Transportation and Tourism Bureau. 

## Getting Started

The idea for this project came from noticing that many tourists visiting Taiwan often feel overwhelmed when planning their trip. With so many destinations to choose from and limited time, it’s difficult to find the right spots that match personal interests. We wanted to solve this problem by building an AI tool that can make trip planning easier and more customized.
To begin building our AI model for recommending tourist travel destinations in Taiwan, we first use the DNN model as this model is the most suitable for this project. DNN is able to recognize patterns and relationships between different features like location, attraction type, user preferences, and more. Since our goal is to match user interests with the most suitable travel destinations, a DNN is the most suitable model for this kind of recommendation task. 


## File Structure

Datasets:
Our datasets “Taiwan Destination List 2025” contains 213 travel destinations, This dataset provides detailed information about various tourist destinations in Taiwan, collected from diverse sources. It includes 9 columns, each offering a distinct attribute related to the destinations. The Destination column lists the names of various tourist spots, while the City column specifies the cities where these destinations are located. Each destination is categorized under a specific Category, such as Nature, Historical, or Geology, to give an idea of the type of experience it offers. The Holiday Type column further elaborates on the kind of holiday the destination suits, like Adventure, Relaxation, or Cultural experiences. Additionally, the Weather column provides information on the typical weather conditions of each destination, ranging from cool to mild climates.The dataset also highlights the Activities available at each destination, offering insights into the types of experiences visitors can enjoy, such as hiking, bird watching, or historical tours. The Popular / Hidden Gems column distinguishes between well-known and lesser-known spots, giving travelers options based on their preferences. Budget indicates the financial consideration for visiting each place, categorized as Low or Medium, while the Number of People column suggests whether the destination is best suited for families, couples, or solo travelers.This structured dataset can help tourists make informed decisions based on various factors, such as weather, activities, and budget preferences, making it a valuable resource for personalized travel recommendations.

Code :
In this project, we use a DNN (Deep Neural Network) model that mimics the logic of the human brain by processing data through multiple layers of interconnected neurons. This enables the model to learn complex patterns and effectively map courses to job labels. To further enhance its capability, we integrate RAG (Retrieval-Augmented Generation) using Langchain, which allows the system to dynamically retrieve relevant information from a database and generate contextually appropriate recommendations tailored to the user's needs.
For the "thinking machine" aspect, we rely on GPT-4o, an advanced large language model capable of understanding a wide range of user inputs and generating human-like responses. GPT-4o is instrumental in interpreting complex queries, reasoning, and offering relevant insights based on user interaction. This powerful combination of deep learning for data processing, RAG with Langchain for real-time content generation, and GPT-4o for intelligent language comprehension ensures the system can adapt to diverse user prompts, providing insightful, personalized, and context-aware responses.
By bringing together these cutting-edge technologies, the project delivers a sophisticated, adaptive, and user-friendly course recommendation system. It processes user input efficiently, retrieves the most relevant data, and produces accurate, natural responses, offering a seamless experience while enhancing user decision-making.

## Analysis

The problem we focused on solving is the confusion that tourists often face when deciding which places to visit in Taiwan. With so many options available, it can be overwhelming to find destinations that match one’s personal interests, travel style, and travel companions.

The AI will definitely help tourists pick the most suitable destination that will fit their travel style. It saves them time and effort by giving personalized suggestions instead of them having to search through hundreds of options on their own. It can also boost their travel experience to make it their best travel experience.

This AI will make the trip to Taiwan more organized, enjoyable, memorable and tailored to each individual’s style. This AI will also help tourists find travel destinations easier, with the AI able to give recommendations based on the prompt provided by each user. This AI aims to give users a personalized and improved trip planning experience, all while saving time and effort.

## Results

The AI system uses a Deep Neural Network (DNN), Retrieval-Augmented Generation (RAG), and a Large Language Model (LLM) through LangChain to recommend travel destinations in Taiwan. It has successfully loaded HuggingFace embeddings and initialized a GPT-4o-based model. Using the RAG pipeline, the AI matches user input with the most relevant travel destinations from a dataset of 213 tourist spots across Taiwan. This allows the system to understand user preferences and give accurate, personalized suggestions that help travelers plan more enjoyable and tailored trips.
When a user types something like “I’m planning a trip for 5 days in Taiwan” or “I want to go to Tamsui,” the system understands the request and recommends destinations that fit the travel style and interest. This shows that the AI can help tourists plan their trip more easily and quickly by giving personalized suggestions.
Overall, the system works well and achieves the goal of helping tourists find the best places to visit based on their preferences.


## Contributors

Grace Halim Saputro - 113ZU1005 (poster, finding dataset)
Gregorio Emanuel Jusak - 113ZU1043 (final report, coding)
Maximillian Jauw - 113ZU1036 (dataset labelling, coding)
Teresa Mieko Wijaya - 113ZU1027poster, final report)
Vallencia Angjaya - 113703010 (project manager, poster)


## Acknowledgments

Professor Pien Chung-Pei 
The Ministry of Transportation and Tourism Bureau ( who provided the tourist attraction data that allowed us to build this model)
Chat GPT


## References

https://data.gov.tw/en/datasets/7777
