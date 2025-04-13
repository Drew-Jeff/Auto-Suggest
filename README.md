# Concept Recommendation System

## Description
The Concept Recommendation System is an AI-driven application that helps learners discover educational content (specifically videos) related to the concept they are studying. By using Natural Language Processing (NLP) and TF-IDF Vectorization, the system recommends related concepts based on textual similarity. The system also enables seamless navigation between concepts by displaying a list of similar concepts, making the learning experience more interactive and engaging.

### Key Features:
- Concept-Based Video Recommendations: Displays videos that are related to the concept the user enters.
- Top 3 Similar Concepts: Recommends similar concepts based on cosine similarity of their descriptions.
- Intuitive Interface: A user-friendly web interface to interact with, view, and explore educational content.
- Dynamic Content Loading: Fetches relevant video content dynamically, allowing users to easily explore related concepts.

---

## Project Structure

- `app.py`: Main Flask application file containing the logic for recommendation generation, routing, and rendering views.
- `Concepts_Dataset.json`: A JSON file containing the concept descriptions, video links, and popularity scores.
- `templates/`:
  - `index.html`: Main landing page where users input a concept and receive video recommendations.
  - `video.html`: Video player page that displays the selected video and related concept recommendations.
- `static/`:
  - `search.css`: Stylesheet for the `index.html` page.
  
---

## Prerequisites

To run this project locally, you'll need the following installed:

- Python 3.x
- Flask
- pandas
- scikit-learn

---

## Installation

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/concept-recommendation-system.git
