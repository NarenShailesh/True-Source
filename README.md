# True-Source

## Overview

**True-Source** is a sophisticated platform designed to help educators and institutions assess the originality of student assignments. The application performs comprehensive plagiarism checks by comparing submitted texts against a vast array of online sources and detecting both direct copying and paraphrasing. It also identifies AI-generated content, ensuring academic integrity and originality.
![image](https://github.com/user-attachments/assets/88dca7c6-92b6-44ef-9d50-e69030966726)

## Features

- **Plagiarism Detection:** Identifies exact matches and paraphrased content by comparing submitted assignments with online sources.
- **AI Content Detection:** Flags content that may have been generated by AI, helping to differentiate between human and machine-generated text.
- **Comprehensive Web Search:** Utilizes Google Custom Search Engine (CSE) for a broad comparison against online content.
- **User-friendly Interface:** Provides a streamlined and intuitive interface for both students and educators to interact with the platform.
- **Detailed Reports:** Generates reports highlighting copied sections, potential sources, and overall similarity percentages.

## Installation

### Prerequisites

- **Python 3.x:** Ensure Python 3.x is installed on your system.
- **API Keys:** Obtain Google Custom Search Engine (CSE) API key and search engine ID.

### Steps

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Padmesh-Coder/True-Source.git
2. **Navigate to the Project Directory:**
   ```bash
   cd True-Source
3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
4. **Configure Google CSE:

   Go to the Google Custom Search Engine (CSE) and create a new search engine.

   Obtain your API key and search engine ID.

   Add these credentials to the .env file:**
   ```bash
   {
   "api_key": "YOUR_API_KEY",
   "search_engine_id": "YOUR_SEARCH_ENGINE_ID"
    }
4. **Configure Google CSE:

   Go to the Google Custom Search Engine (CSE) and create a new search engine.

   Obtain your API key and search engine ID.

   Add these credentials to the .env file:**
   ```bash
   {
   "api_key": "YOUR_API_KEY",
   "search_engine_id": "YOUR_SEARCH_ENGINE_ID"
    }
  **USAGE :**
  ```bash
        python main.py
        python pdf.py
