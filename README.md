# Gemini Explorer Project

## Project Description
Gemini Explorer is a project that uses Google Cloud and Gemini to build an interactive AI chat application. It leverages Streamlit to provide an interactive chat interface for users.

## Installation Guide

### Requirements
- Python 
- pip (Python package manager)
- Google Cloud SDK (gcloud CLI) 

### Installation Steps

1. Clone this repository:
    ```bash
    git clone https://github.com/youngsunlee07/GoogleGemini.git
    ```

2. Navigate to the project directory 

3. Install the required packages:
    ```bash
    pip install streamlit google-cloud-aiplatform
    ```

4. Install and initialize the Google Cloud SDK:
    - Follow the [official installation guide](https://cloud.google.com/sdk/docs/install) to install the Google Cloud SDK.
    - After installation, initialize the SDK using the following command:
      ```bash
      gcloud init
      ```
    - Authenticate and set up your project with the gcloud CLI:
      ```bash
      gcloud auth application-default login 
      ```

## Usage

Run the application:
```bash
streamlit run GeminiExplorer.py
```

## Contact 

If you have any questions or suggestions about the project, please contact me at youngsun.lee07@gmail.com.
