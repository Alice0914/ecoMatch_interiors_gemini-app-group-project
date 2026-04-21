# EcoMatch Interiors - Gemini API APP Developer Competition

<img src="https://github.com/user-attachments/assets/af3ba20a-c090-4da4-88f8-e7abf64cf105" align="left" width="45%" alt="GeminiApp-EcoMatch-gif" style="margin-right: 15px;" />

<b>EcoMatch Interiors</b> is a web application that leverages Gemini AI technology to provide personalized, eco-friendly interior design suggestions. The app analyzes room images and user preferences to offer tailored recommendations and visualizations for sustainable home decor.

<br clear="all" />

## Contributors
- Alexis Hwang 
- Alice Kim
- Chris H
- Joseph Moon
- Ronin Sharma
- Seong Lee

## Project Structure

```plaintext
GEMINI-APP-PROJECT-FLASK
├── shared
│   └── image_desc_list.json
├── static
│   ├── css
│   │   ├── style1.css
│   │   └── style2.css
│   └── js
│       ├── gemini-api.js
│       └── main.js
├── templates
│   └── index.html
├── main.py
└── requirements.txt
```
## Technology Stack Used in This Application

### Frontend

- **JavaScript (JS):** Used for client-side scripting to create interactive and dynamic web pages.
- **HTML & CSS:** Utilizes Tailwind CSS classes for styling and structuring the user interface.

### Backend

- **Python:** Employed as the primary language for server-side development, providing a robust and scalable environment.
- **Flask:** A lightweight web framework for building the web server and API endpoints.

### APIs and Models

- **Gemini API:** Integrated to offer generative AI capabilities for content creation.
- **Sentence Transformer:** A pre-trained model used to perform text similarity comparisons by converting text inputs into embedding vectors.

### Authentication

- **Firebase Authentication:** Provides secure user sign-in, specifically supporting Google accounts for easy authentication.


## Update the Default IDX Directory Structure

Please update the default directory structure in IDX to match the structure provided above. This ensures that the application functions correctly and all files are correctly referenced within the project.

## Components

1. **`main.py`**: The main Flask application file that handles routing and API endpoints.

2. **`requirements.txt`**: Lists all the Python dependencies required for the project.

3. **`shared/image_desc_list.json`**: Contains a list of image descriptions and URLs used for similarity comparisons.

4. **`static/css/`**:
   - **`style1.css`** and **`style2.css`**: CSS files for styling the web application.

5. **`static/js/`**:
   - **`gemini-api.js`**: JavaScript file for interacting with the Gemini API.
   - **`main.js`**: Main JavaScript file for client-side functionality.

6. **`templates/index.html`**: The main HTML template for the web application.

## Setup and Installation

1. **Use IDX Selecting Gemini API with Python (Flask)**

   - Navigate to [idx.google.com](https://idx.google.com) and set up your environment by selecting the Gemini API using Python with Flask.

2. **Install the Required Dependencies:**

   - Run the following command in your terminal to install all the necessary packages:
     ```bash
     pip install -r requirements.txt
     ```

3. **Set Up Your Gemini API Key:**

   - Replace `'Gemini-Api-Key'` in `main.py` with your actual Gemini API key.

4. **Run the Application:**

5. **Sign in through Google email to use all features on the application:**
