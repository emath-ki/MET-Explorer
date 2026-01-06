# MET-Explorer: Simplifying Museum API Access

A Python-based project for exploring **The Met Museum’s public collection** in a simple, intuitive, and user-friendly way.

> **Overview:** In 2017, The Met launched its **Open Access Initiative**, making over 492,000 images of public-domain artworks freely available.  

This project builds on that generosity by providing a **Python interface that makes exploring the collection easy and engaging**. Using automated data retrieval, it transforms open data into an **experience designed for discovery, curiosity, and learning**, enabling users to search for artworks by artist, culture, or keyword, and view detailed information including images and thumbnails.  

The goal is to make **art exploration accessible and enjoyable for anyone**, from learners to developers and art enthusiasts.

> **Disclaimer:** This project is a personal Python tool built using The Met Museum Open Access API. 
> It is **not an official Met product**. All images and data are sourced from The Met's public domain collection.

---

# Table of Contents
  ## Features & Usage

- **Search the Collection (`run1.py`)**  
  - Search by artist, culture, or keyword  
  - Returns total results and sample object IDs  

- **Fetch Artwork Details (`run2.py`)**  
  - Retrieve title, artist, primary image, and thumbnail for a given object ID  

**How to Run:**

1. Install Python 3.7+ and the `requests` library:

```bash
pip install requests
Open run1.py to search the collection: modify params for your query and run:

bash
Copy code
python run1.py
Open run2.py to fetch artwork details: replace the object ID and run:

bash
Copy code
python run2.py
Optional: loop through multiple object IDs or modify queries for further exploration.

Extending the Project
Retrieve multiple artworks automatically

Include additional metadata: objectDate, medium, dimensions

Integrate into interactive visualizations or web apps

