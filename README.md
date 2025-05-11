 Trend Analysis of Reddit Posts

## Project Overview
This project is designed to analyze trending topics from Reddit posts in real-time. Using **BERTopic** for topic modeling and **Streamlit** for visualization, it allows users to explore and analyze trending topics. The dashboard automatically updates and provides users with insights into what topics are currently being discussed the most.

### Key Features:
- **Trending Topics Dashboard**: Displays the top trending topics based on Reddit data, updated in real-time.
- **Topic Search**: Click on a trending topic to view related Reddit posts.
- **Topic Trend Visualization**: A line graph shows how often a specific topic is mentioned over time.
- **GPT-powered Topic Naming**: Uses OpenAI's GPT to provide meaningful and descriptive names for each topic based on the content.

## Requirements
To run the project, ensure you have Python 3.7 or higher installed. You also need to install the required dependencies.

### Install Dependencies:
1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/GithubSaurabh1/Trend-Analysis-Of-Reddit-Post.git
Navigate into the project directory and install the required dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Requirements:
streamlit

bertopic

joblib

keybert

sentence-transformers

plotly

openai

Setup and Configuration
1. Get OpenAI API Key
This project uses OpenAI's GPT model for generating meaningful topic names. You will need an OpenAI API Key to use this feature.

Sign up on OpenAI and create an API key.

Set the API key in your .env file or in your environment variables.

Example .env file format:

env
Copy
Edit
OPENAI_API_KEY=your-api-key-here
2. Run the Application
After installing the dependencies and configuring your API key, you can start the dashboard by running the following command:

bash
Copy
Edit
streamlit run dashboard.py
This command will start a local server, and you can view the dashboard by visiting http://localhost:8501 in your web browser.

Folder Structure
The project has the following folder structure:

bash
Copy
Edit
.
├── .streamlit/
│   └── secrets.toml    # Stores API keys and sensitive information
├── model/
│   ├── topic_model.pkl  # Pre-trained BERTopic model
│   ├── docs.pkl         # Preprocessed documents
│   └── timestamps.pkl   # Timestamp data for trending topics
├── dashboard.py          # Streamlit app for topic visualization
├── requirements.txt      # List of Python dependencies
└── README.md             # This file
Contributions
Contributions are welcome! If you would like to add new features or fix bugs, feel free to fork the repository and submit a pull request. You can also open issues to report bugs or request new features.

License
This project is open-source and available under the MIT License.

markdown
Copy
Edit

### 4. **Commit the README to Git**

1. Open the **Terminal** in VSCode (using `Ctrl + ~` or through the menu at the top).
2. Check the status of your Git repository:

   ```bash
   git status
