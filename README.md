# ClipScrape
A Streamlit-based web app for scraping images from any webpage, filtering out advertisements using a ResNet model, and enabling semantic image and text-based search using OpenAI's CLIP and FAISS.

# Clip Scraper

Visionary Scraper is an AI-powered web application that allows you to:
- Scrape images from any given URL.
- Automatically filter out advertisement images using a ResNet classifier.
- Generate image embeddings using OpenAI’s CLIP model.
- Perform semantic search via image or text queries using FAISS.
- All wrapped inside an easy-to-use Streamlit interface.


## Features

- **Image Scraping**: Fetch all images from a public webpage.
- **Ad Filtering**: Filter out advertisement images using a pre-trained ResNet-18 model.
- **CLIP Embeddings**: Generate embeddings using OpenAI’s CLIP model (`clip-vit-base-patch32`).
- **Semantic Search**:
  - Image-to-Image Search: Find visually or semantically similar images.
  - Text-to-Image Search: Retrieve images that best match a given text prompt.
- **Fast Retrieval**: Use FAISS for efficient nearest-neighbor search on high-dimensional embeddings.



## Technologies Used

| Library        | Purpose                        |
|----------------|--------------------------------|
| `Streamlit`    | Web app interface              |
| `BeautifulSoup`, `requests` | Web scraping       |
| `torch`, `torchvision` | Deep learning models     |
| `transformers` | CLIP model from Hugging Face   |
| `PIL`          | Image loading and processing   |
| `faiss`        | Efficient similarity search    |
| `datasets`     | Batch encoding and loading     |


## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/visionary-scraper.git
   cd visionary-scraper
