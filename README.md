# SuperMind

SuperMind is a web application that integrates a Django backend with a React frontend. It provides functionalities for analyzing website content, generating summaries, and handling video data.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Running the Application](#running-the-application)
- [Project Structure](#project-structure)
- [API Endpoints](#api-endpoints)
- [Deployment](#deployment)
- [License](#license)

## Features

- Analyze website content and generate summaries
- Handle video data and generate tags
- Integrated Django backend and React frontend

## Prerequisites

- Python 3.8+
- Node.js 14+
- npm 6+
- pip (Python package installer)

## Installation

1. **Clone the repository:**

   ```sh
   git clone https://github.com/yourusername/SuperMind.git
   cd SuperMind
   ```
2. **Set up the Django backend:**
    - Install the required Python packages:
    ```
    pip install -r requirements.txt
    ```

## Running the Application
1. Move into the "SuperMind" directory:
   ```sh
   cd SuperMind
   ```
2. Install required dependencies using pip:
   ```sh
   pip install -r requirements.txt
   ```
3. Apply database migrations:
   ```sh
   python manage.py migrate
   ```
4. Start the Django development server:
   ```sh
   python manage.py runserver
   ```
5. Running React Frontend (open another Terminal):
   ```sh
   cd UI/supermind-ui
   ```

   ```sh
   npm install
   ```
   ```
   npm start
   ```
