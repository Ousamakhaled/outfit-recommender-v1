# Outfit Recommender V1

## Overview
This project recommends visually similar outfits based on dominant color features.

## How it works
- Extract dominant colors from images using KMeans
- Convert colors into feature vectors
- Compare images using cosine similarity
- Filter recommendations by style group

## Features
- Color-based similarity matching
- Style-based filtering (e.g., streetwear, minimal)
- Visual output of similar outfits

## Limitations
- Understands color similarity only
- Does not capture full fashion semantics (shape, texture, clothing type)

## Technologies
- Python
- NumPy
- Scikit-learn
- Matplotlib
- PIL

## Future Work
- Add brightness and contrast (V2)
- Improve feature representation
- Build a more advanced recommender system

## Author
Ousama



