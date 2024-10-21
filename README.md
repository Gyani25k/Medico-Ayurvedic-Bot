# Chatbot Setup and Usage

This is a step-by-step guide to setting up and running the chatbot application.

## Prerequisites

Ensure that the following is installed on your system:
- Python 3.8 or higher
- `pip` (Python package manager)

## Installation Guide

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. **Install required dependencies**:
   Use the following command to install all the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

## Configuration

3. **Create a `.env` file**:
   In the root directory of the project, create a `.env` file and add the following API key:
   ```bash
   HUGGINGFACEHUB_API_TOKEN=your_huggingface_api_key
   ```

   Replace `your_huggingface_api_key` with your actual API key from Hugging Face. You can obtain it from [Hugging Face API Tokens](https://huggingface.co/settings/tokens).

## Running the Application

4. **Run the chatbot**:
   Open your terminal, navigate to the project directory, and run the following command:
   ```bash
   chainlit run app.py
   ```

   This will start the chatbot, and it should be accessible at `http://localhost:8000` or the port provided by `Chainlit`.

---

## Additional Information

- **Dependencies**: The `requirements.txt` file contains all the Python libraries needed to run the chatbot.
- **Environment Variables**: The `.env` file ensures the API token is securely provided to the application.

Feel free to reach out if you face any issues setting up or running the chatbot!

--- 

This README provides a clear and straightforward guide for anyone to set up and launch the chatbot.
