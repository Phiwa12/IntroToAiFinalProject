# IntroToAiFinalProject

# Diet Recommendation Chatbot

This project is a diet recommendation chatbot designed to provide personalized diet plans for users based on their specific needs and preferences. The chatbot uses data on Kenyan foods and their nutritional content to generate daily diet recommendations. It also considers various health conditions such as hypertension, high blood pressure, low blood pressure, lactose intolerance, and vegetarian diets.

 Features

- Personalized diet recommendations for weight loss or weight gain.
- Daily diet plans to encourage users to check back regularly.
- Consideration of allergies and health conditions in the recommendations.
- Prevention of repeated food recommendations using a database.
- User-defined duration for weight changes.
- Management and storage of past recommendations.

 Technologies Used

- Python
- Streamlit (for the web interface)
- OpenAI API (for generating diet recommendations)
- MongoDB (for storing past recommendations)
- FAISS (for vector search and similarity)

Getting Started

Prerequisites

- Python 3.8 or higher
- An OpenAI API key
- MongoDB installed or access to a MongoDB Atlas cluster

 Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/diet-recommendation-chatbot.git
   cd diet-recommendation-chatbot
   ```

2. Create a virtual environment and activate it:

   ```bash
   python -m venv myenv
   source myenv/bin/activate  # On Windows, use `myenv\Scripts\activate`
   ```

3. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

4. Install additional package:

   ```bash
   pip install langchain-openai
   ```

5. Set up your OpenAI API key and MongoDB connection string as environment variables:

   ```bash
   export OPENAI_API_KEY='your_openai_api_key'
   export MONGODB_URI='your_mongodb_connection_string'
   ```

 Running the Application

1. Start the Streamlit application:

   ```bash
   streamlit run app.py
   ```

2. Open your web browser and go to `http://localhost:8501` to interact with the chatbot.

File Structure

- `app.py`: The main application file for the Streamlit interface.
- `data_loader.py`: A script to load and process the data.
- `requirements.txt`: A file listing the required Python packages.

  
