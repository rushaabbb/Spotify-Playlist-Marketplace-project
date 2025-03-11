# Spotify Playlist Marketplace

## Overview

A marketplace where users can buy and sell curated Spotify playlists. The platform integrates with the Spotify API, allowing users to preview the first three songs before purchasing.

Tech Stack

Frontend: Next.js (React-based UI)

Backend: Flask (Python-based API)

Database: SQLite/PostgreSQL (to store user and playlist data)

Auth: OAuth with Spotify API

Prerequisites

Python 3.x

Node.js & npm

## Spotify Developer Account

Installation

Backend

# Navigate to backend folder
cd backend

# Install dependencies
pip install -r requirements.txt

# Run the Flask API
python app.py

Frontend

# Navigate to frontend folder
cd frontend

# Install dependencies
npm install

# Run the Next.js frontend
npm run dev

# API Endpoints

GET / – Welcome message

GET /playlists – Fetch available playlists

POST /purchase – Purchase a playlist

# License

This project is licensed under the MIT License.

