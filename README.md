# Multimodal AI Agent - Video Summarizer

## Overview
The **Multimodal AI Agent - Video Summarizer** is a Streamlit-based application that leverages Google's **Gemini 2.0** and **DuckDuckGo** search capabilities to analyze and summarize video content. The AI agent is designed to provide meaningful insights from uploaded videos by processing them and responding to user queries with supplementary web research.

## Features
- **Upload Video Files**: Supports MP4, MOV, and AVI formats.
- **AI-Powered Analysis**: Uses the **Gemini 2.0** model for video understanding.
- **Web-Based Contextual Research**: Enhances responses with DuckDuckGo.
- **Interactive Query System**: Allows users to specify insights they seek from the video.
- **Streamlit UI**: Simple and user-friendly interface for video summarization.

## Tech Stack
- **Python**
- **Streamlit**
- **Google Gemini AI** (via `google.generativeai`)
- **DuckDuckGo Search API** (via `phi.tools.duckduckgo`)
- **PHI AI Agent Framework** (`phi.agent`)
- **Google Generative AI API**

## Installation
### 1. Clone the Repository
```bash
$ git clone https://github.com/yourusername/video-summarizer-ai.git
$ cd video-summarizer-ai
```

### 2. Create and Activate Virtual Environment
```bash
$ python -m venv venv
$ source venv/bin/activate  # On macOS/Linux
$ venv\Scripts\activate    # On Windows
```

### 3. Install Dependencies
```bash
$ pip install -r requirements.txt
```

### 4. Set Up API Keys
Create a `.env` file in the root directory and add your **Google API Key**:
```ini
GOOGLE_API_KEY=your_google_api_key
```

### 5. Run the Application
```bash
$ streamlit run app.py
```

## Usage
1. **Upload a video file** in MP4, MOV, or AVI format.
2. **Enter your query** in the text area, specifying what insights you need.
3. Click **Analyze Video** to let the AI process and summarize the video.
4. View the **detailed analysis and insights** generated by the AI.

## File Structure
```
video-summarizer-ai/
│── app.py                # Streamlit application
│── requirements.txt      # Python dependencies
│── .env                  # Environment variables (ignored in Git)
│── README.md             # Project documentation
```

## Output
![image](https://github.com/user-attachments/assets/da28e803-8749-410a-99d4-e9f6c8b6f0f9)
![image](https://github.com/user-attachments/assets/a9818016-b18c-461d-916d-59f8e4bbcbea)


## Future Enhancements
- **Speech-to-Text Integration**: Extract and analyze spoken content from videos.
- **Multi-Modal Analysis**: Combine video, audio, and text for deeper insights.
- **Improved UI/UX**: Enhancements for a more interactive user experience.

## License
This project is licensed under the MIT License.

## Contributing
Pull requests are welcome! Please open an issue first to discuss your ideas.

## Contact
For any inquiries, reach out via GitHub Issues or [your email].

