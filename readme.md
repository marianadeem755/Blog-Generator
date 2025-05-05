# 🌟 AI Blog Generator

This is a **Streamlit-based web application** that uses the **LLaMA 3 AI model** to generate high quality blog posts in minutes. The app allows users to input a blog topic, select a tone, and download the generated blog post in their preferred format (Markdown, PDF, or Word).

## 🚀 Features

- **Customizable Blog Generation**: Enter a blog topic and select a tone (Informative, Conversational, Professional, or Casual).
- **Multiple Download Formats**: Download the generated blog post in Markdown, PDF, or Word (.docx) format.
- **AI-Powered Content**: Uses the LLaMA 3 AI model to create engaging, informative, and human-like blog posts.


## 🛠️ Installation
1. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Create a `.env` file in the root directory and add your **GROQ API Key**:
   ```
   GROQ_API_KEY=your_api_key_here
   ```

4. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

## 📖 How to Use

1. **Enter Blog Topic**: Provide a topic for the blog post (e.g., "Future of AI in Education").
2. **Select Tone**: Choose the tone of the blog (Informative, Conversational, Professional, or Casual).
3. **Choose Format**: Select the desired download format (Markdown, PDF, or Word).
4. **Generate Blog**: Click the "🚀 Generate Blog Post" button to create the blog.
5. **Download Blog**: Use the download buttons to save the blog in your preferred format.

## 📦 Dependencies

- **Streamlit**: For building the web application.
- **Requests**: For making API calls to the GROQ API.
- **python-dotenv**: For loading environment variables.
- **python-docx**: For generating Word documents.
- **reportlab**: For generating PDF files.
- **markdown2**: For converting Markdown to HTML.

Install all dependencies using:
```bash
pip install -r requirements.txt
```

- Ensure your **GROQ API Key** is valid and added to the `.env` file.
- The app requires an active internet connection to communicate with the GROQ API.

## 🌟 Acknowledgments

- Powered by the **LLaMA 3 AI model**.
- Built with [Streamlit](https://streamlit.io/).
``