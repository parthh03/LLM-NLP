
                        YouTube-Summarizer

YouTube Summarizer is a small Natural Language Processing (NLP) project that offers a solution to quickly summarize the content of YouTube videos. It aims to save time by providing a concise understanding of a video's content in a short period. The project combines NLP techniques and extractive summarization to condense the essential parts of the video, making it easy to grasp.


## Key Features
Subtitle Extraction: The project uses the YouTube Transcript API to obtain video subtitles, allowing it to work with any video that has subtitles available.

TF-IDF Summarization: Utilizing Term Frequency-Inverse Document Frequency (TF-IDF), the system extracts important sentences from the subtitles to create a summary.

BART Summarization: BART (Bidirectional and Auto-Regressive Transformer) is employed for another summarization approach. It's particularly suitable for sequence-to-sequence tasks like summarization.
## Demo

Subtitles are extracted using the YouTube Transcript API.

For TF-IDF summarization, the system tokenizes sentences and calculates TF-IDF scores.

The top sentences with the highest scores are selected to create the summary.

For BART summarization, the subtitle is encoded using BART Tokenizer.

The BART model generates the output summarization.


## Usage

For a quick summary of a YouTube video's content, simply provide the video's link to the YouTube Summarizer.

The project is designed to be user-friendly, making it easy to get started.


## Dependencies
Python,
Hugging Face Transformers,
YouTube Transcript API,
NLTK,
scikit-learn,
NumPy.