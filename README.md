# Gemini Explorer Project

## Project Description
Gemini Explorer is a project that uses Google Cloud and Gemini to build an interactive AI chat application. It leverages Streamlit to provide an interactive chat interface for users.

## Installation Guide

### Requirements
- Python 
- pip (Python package manager)
- Google Cloud SDK (gcloud CLI) 

### Installation Steps

1. Create a new project on Google Cloud Platform:
    - Enable the Vertex AI API.
    - Create a service account:
        - Assign a name and role to the account.
    - Generate a key:
        - Choose JSON format as the key type, which is required for SDK authentication.

2. Clone this repository:
    ```bash
    git clone https://github.com/youngsunlee07/GeminiExplorer.git
    ```

3. Navigate to the project directory:
    ```bash
    cd GeminiExplorer
    ```

4. Install the required packages:
    ```bash
    pip install streamlit google-cloud-aiplatform
    ```

5. Install and initialize the Google Cloud SDK:
    - Follow the [official installation guide](https://cloud.google.com/sdk/docs/install) to install the Google Cloud SDK.
    - After installation, initialize the SDK using the following command:
      ```bash
      gcloud init
      ```
    - Authenticate and set up your project with the gcloud CLI:
      ```bash
      gcloud auth application-default login
      ```

6. Set the Google Application Credentials:
    ```bash
    export GOOGLE_APPLICATION_CREDENTIALS="/path/to/your/keyfile.json"
    ```

7. List your projects to verify the setup:
    ```bash
    gcloud projects list
    ```

## Usage

Run the application:
```bash
streamlit run GeminiExplorer.py
```

## Contact 

If you have any questions or suggestions about the project, please contact me at youngsun.lee07@gmail.com.
