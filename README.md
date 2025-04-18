# AI Prompt Engineering Tutor

An interactive, AI-powered tutor designed to help users understand and master **prompt engineering** using **Google Gemini 1.5 Pro** and **Streamlit**.

---

## Features

-  Ask questions related to prompt design, optimization, and LLM behavior  
-  Maintains conversation context (up to 10 exchanges)  
-  Built with [Streamlit](https://docs.streamlit.io/) for a simple and elegant UI  
-  Powered by **Google Gemini 1.5 Pro** via the `google-generativeai` library  
-  Easy API key setup via sidebar input  
-  Robust error handling for seamless user experience  

---

## Run the App

To run the app locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/kshitizjangra/aipromptengineeringtutor.git
    ```
2. Navigate into the project directory:
    ```bash
    cd aipromptengineeringtutor
    ```
3. Create a virtual environment:
    ```bash
    python -m venv venv
    ```
4. Activate the virtual environment:
    - On Linux/Mac:
      ```bash
      source venv/bin/activate
      ```
    - On Windows:
      ```bash
      venv\Scripts\activate
      ```
5. Install the required dependencies:
    ```bash
    pip install streamlit langchain google-generativeai google-api-core
    ```
6. Run the Streamlit app:
    ```bash
    streamlit run app.py
    ```

---

## Usage

- Enter your **Google Gemini API Key** in the sidebar.  
- Ask anything about **prompt engineering** in the chat input.  
- Receive intelligent responses from your **AI Tutor** in real-time.  

---

## License

This project is licensed under the **MIT License** – see the [LICENSE](https://github.com/kshitizjangra/aipromptengineeringtutor/blob/main/LICENSE) file for details.

---

## Resources

- [Python Downloads](https://www.python.org/downloads/)  
- [Streamlit Documentation](https://docs.streamlit.io/)  
- [Google Generative AI Python Library](https://github.com/google/generative-ai-python)  

---

## Author

**[Kshitiz Jangra](https://github.com/kshitizjangra)** – feel free to ⭐ the repo if you find it helpful!

