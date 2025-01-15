# TEXT_SUMMARIZATION_PROJECT
LangChain: Summarize Text from YouTube or Website

This project is a Streamlit application designed to generate concise summaries from YouTube videos or web pages. Powered by LangChain and the Groq API, the app uses state-of-the-art language models for text summarization.

**Features**

**- YouTube Video Summarization:** Extracts and summarizes transcript data from YouTube videos.

**- Web Page Summarization:** Retrieves and summarizes content from web pages.

**- Customizable Prompt:** Uses a predefined prompt to tailor summaries to 300 words.

**- Groq API Integration:** Leverages Groq’s Gemma-7b-It model for high-quality language processing.

**- User-Friendly Interface:** Built with Streamlit for an intuitive and interactive user experience.

**How It Works**

**Input Validation:**
Validates the provided Groq API Key and URL format.
Ensures the URL points to a YouTube video or webpage.

**Content Extraction:**
**For YouTube URLs:** Extracts transcripts using YoutubeLoader.

**For web pages:** Retrieves and parses content using UnstructuredURLLoader.

**Summarization:**
Uses LangChain’s load_summarize_chain to process the extracted content.
Summaries are generated using the Gemma-7b-It model and a predefined prompt.

**Output:**
Displays a concise 300-word summary in the application interface.
