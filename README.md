# Medix App [OCR(Azure),NLP(Entity Extraction),LLM(OpenAi)]

Medix is an innovative app that assists users in identifying medical tablets, extracting important information, and providing usage recommendations through a conversational interface.

📸 Stage 1: Text Extraction
  #Data Collection
   Gather a diverse dataset of medical tablet images from hospitals, pharmacies, and online retailers.
   
   #Data Extraction
   Utilize OCR (Optical Character Recognition) to extract text from images. We employ EasyOCR and Azure Computer Vision for accurate extraction.

🧬 Stage 2: Entity Extraction using NLP
    #Entity Extraction
    Use Natural Language Processing (NLP) techniques to extract important entities from the OCR output. 
    Filter the data using medical terms.
    Filter the data based on chemicals and drugs present in the tablets. We use DOLO-650 as an example for demonstration.

🤖 Stage 3: Chatbot Development
    #Conversational Interface
    Develop a user-friendly conversational interface allowing users to interact naturally.
    
  #Chatbot Integration
  Integrate the chatbot with our AI model to provide accurate responses.

  #Chatbot Training
  Train the chatbot using data from the CIMS (Central Drugs Standard Control Organization) book for comprehensive medical knowledge.

  #Chatbot Deployment
  Deploy the chatbot to a production environment for public use.

 ℹ️ Information and Recommendations
 #Information Retrieval
 Retrieve detailed information about identified tablets from a medical knowledge database.

 #Usage Recommendations
 Offer guidance on tablet usage, including dosages, timings, and precautions.

 #Pros and Cons
 Present information on the benefits and potential side effects of tablets.

 #Privacy and Security
 Ensure user data is handled securely and complies with privacy regulations.

Feel free to contribute to our project or reach out with any questions or feedback! 🚀
