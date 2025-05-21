# AI-Image-Caption-Recommendation-System
AI-powered image caption recommendation system using OpenAI’s CLIP model. It ranks captions by computing cosine similarity between image and text embeddings, recommending the most relevant ones. Built with PyTorch, Transformers, and PIL for intelligent and context-aware captioning.

🧠 AI Image Caption Recommendation System

This project implements an AI-powered image caption recommendation system using OpenAI's CLIP model to suggest the most relevant and meaningful captions for a given image.

🔍 How it Works
Image Preprocessing:
Loads and prepares an image using the CLIPProcessor.
Feature Extraction (Vision):
Extracts image embeddings using OpenAI’s pretrained CLIPModel.
Text Embedding and Matching:
Computes embeddings for a list of candidate captions and uses cosine similarity to find the best matches to the image features.
Caption Ranking:
Captions are ranked based on similarity scores to the image content, and the top 5 most relevant captions are displayed.
🛠 Technologies Used
Python
PyTorch
Hugging Face Transformers (CLIPProcessor, CLIPModel)
scikit-learn (cosine_similarity)
PIL (Python Imaging Library)
