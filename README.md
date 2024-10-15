markdown
Copy code
# Voice Message Communication App

This application allows users to send voice messages to others and receive voice messages in their own language. 

## Getting Started

### Prerequisites

- Python 3.7 or higher
- pip (Python package installer)

### Steps to Set Up the Environment

1. **Create a Virtual Environment**:
   To isolate your project's dependencies, it's recommended to create a virtual environment. Run the following command:

   ```bash
   python -m venv venv
Replace venv with your preferred environment name.

Activate the Virtual Environment:

On Windows:
bash
Copy code
venv\Scripts\activate
On macOS/Linux:
bash
Copy code
source venv/bin/activate
Install Dependencies: Use the following command to install the required packages from the requirements.txt file:

bash
Copy code
pip install -r requirements.txt
Configure API Keys: Replace the placeholders in the code for the following APIs:

Assembly AI API: Obtain your API key from Assembly AI.
Eleven Labs API: Get your API key from Eleven Labs.
After acquiring the API keys, insert them into the respective variables in your code.

Choose a Voice Model: You can choose a voice model from the Eleven Labs platform. Make sure to select a suitable voice for your text-to-speech functionality.

Running the Application
To run the application, execute the following command:

bash
Copy code
streamlit run record.py
Replace app.py with the name of your main application file if it differs.
