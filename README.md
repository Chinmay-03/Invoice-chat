# MultiLanguage Invoice Extractor

This **Streamlit web app** utilizes **Google's Gemini AI** to extract and analyze invoice data in multiple languages. Users upload invoice images to receive AI-generated insights.

## Features
- Upload invoice images (JPG, JPEG, PNG).
- Extract multilingual invoice details using **Google Gemini AI**.
- Input custom prompts for invoice-specific questions.

## Technologies
- **Python**: Backend logic
- **Streamlit**: Web UI
- **PIL**: Image handling
- **Google Gemini AI**: NLP and image analysis
- **dotenv**: API key management

## Setup

### Prerequisites
- Python 3.8+
- Required libraries: `streamlit`, `pillow`, `python-dotenv`, `google-generativeai`

### Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/multilanguage-invoice-extractor.git
   cd multilanguage-invoice-extractor
   ```
2. **Set up a virtual environment (optional):**
   ```bash
   python3 -m venv env
   source env/bin/activate  # Windows: env\Scripts\activate
   ```
3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
4. **Configure environment variables:**
   - Create a `.env` file and add your API key:
     ```bash
     GOOGLE_API_KEY=your_google_api_key
     ```

### Running the App
1. Start the app:
   ```bash
   streamlit run app.py
   ```
2. Visit the app at **http://localhost:8501**.

## Usage
- Upload an invoice (JPG, JPEG, PNG).
- Enter a prompt to query invoice details.
- View AI-extracted insights.

## License
This project is licensed under MIT.
