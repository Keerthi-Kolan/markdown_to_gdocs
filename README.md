# Markdown to Google Docs Converter

This project converts structured markdown meeting notes into a well-formatted Google Doc using the Google Docs API.  
It preserves headings, nested bullet points, checklists, and basic styling while running entirely in Google Colab.

---

## Features
- Creates a new Google Doc programmatically
- Converts markdown headings to Google Docs headings
- Preserves bullet points and hierarchy
- Converts markdown checkboxes into Google Docs checkboxes
- Handles basic formatting using Google Docs batchUpdate API
- Runs fully in Google Colab with OAuth authentication

---

## Setup Instructions

### 1. Open the notebook in Google Colab
Upload or open `markdown_to_gdocs.ipynb` in Google Colab.

### 2. Authenticate with Google
Run the authentication cell when prompted and sign in with your Google account.

### 3. Run the notebook
Execute the notebook cells top to bottom.  
A new Google Doc will be created automatically in your Google Drive.

---


