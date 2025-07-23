# LAW - MATE - An Legal AI-Powered Chatbot 

LAW MATE is an AI-driven RAG-based multi-modal chatbot designed to enhance user interaction on the Department of Justice (DoJ) website. It provides accurate, context-aware information on legal matters, court procedures, and DoJ services, utilizing advanced algorithms and Language Models (LLMs) to efficiently process and retrieve relevant data.





## Problem Statement

Developing an AI-based interactive Chatbot or virtual assistant for the Department of Justice's Website(SIH-2024).

## Features

- **Multilingual Support**: Communicate in various Indian languages including English, Hindi, Bengali, and more.
- **AI-Powered Responses**: Utilizes advanced language models to provide accurate legal information.
- **User-Friendly Interface**: Clean and intuitive Streamlit-based UI for easy interaction.
- **Conversation Memory**: Maintains context through conversation history.
- **Legal Text Analysis**: Processes and retrieves information from legal documents.
- **Adaptive Learning**: Continuously updates and expands its knowledge base.
- **Personalized Experience**: Tailors responses based on each user's interaction history.

## How It Addresses the Problem

- Simplifies access to critical information by allowing users to navigate complex legal topics effortlessly.
- Streamlines the process of finding essential legal details, improving the accessibility of information for citizens.
- Reduces dependency on manual searches and costly legal advice by offering initial, reliable guidance.



## Technologies Used

- **Programming Language**: Python
- **Frameworks**: Streamlit, LangChain
- **Libraries**: FAISS, GoogleTranslator, HuggingFace Embeddings, Ollama
- **Embeddings**: law-ai/InLegalBERT


## Challenges and Solutions

### Challenge: Accuracy of LLM Responses
Legal queries require precise and context-aware answers. Incorrect or vague responses could lead to misinformation.

### Solution: Predefined System Prompts
- Use specific prompt instructions to ensure clear and correct answers.
- Implement a prompt design that:
  - Breaks down answers into clear points.
  - Corrects common mistakes and explains exceptions.
  - Focuses on the most relevant information.

## Impact and Benefits

### Social Benefits
- Encourages legal education and awareness, leading to a more legally informed society.

### Economic Benefits
- Reduces dependency on costly legal advice by offering initial, reliable guidance and information.

### Operational Benefits
- Eases the burden on government helpdesks by streamlining access to essential legal resources and information.

### Environmental Benefits
- Minimizes the need for physical documents by providing a digital, eco-friendly alternative for accessing legal materials.

## Future Enhancements

Offline mode for everyone





## References

- G, Shubhashri & N, Unnamalai & G, Kamalika. (2018). LAWBO: a smart lawyer chatbot. 348-351. 10.1145/3152494.3167988. [Link](https://www.researchgate.net/publication/324464758_LAWBO_a_smart_lawyer_chatbot)
- Queudot, Marc & Charton, Éric & Meurs, Marie-Jean. (2020). Improving Access to Justice with Legal Chatbots. Stats. 3. 356-375. 10.3390/stats3030023. [Link](https://www.mdpi.com/2571-905X/3/3/23)

