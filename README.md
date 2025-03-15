# Healthiest365 - SG AI Nutritionist (Healthy365 Extension)

Healthiest365 is an intelligent nutritionist extension of the Healthy365 app, designed to promote healthier eating habits with the help of advanced AI technology. This AI-powered solution offers personalized meal suggestions, nutritional analysis, and advices tailored to individual health goals, preferences, and dietary restrictions. Healthiest365 is not just about food, it's about creating a balanced, healthy way of living that supports long-term well-being, perfectly complementing the Healthy365 app ecosystem.

## Project Overview

Healthiest365, a 24/25 Sem 2 NUS IS4261 Project by Group 2, is designed to revolutionize daily nutrition and promote a healthier lifestyle through AI-powered meal nutritionist. This project aims to provide personalized meal suggestions, in-depth nutritional insights, and tailored advice, making healthy eating accessible and convenient for everyone. 

## Table of Contents
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Tech Stack](#tech-stack)
- [Features](#features)
- [Contributing](#contributing)

## Getting Started

### Prerequisites

Before you start, make sure you have the following installed:

- [Python](https://www.python.org/downloads/) (version x.x or higher)
- [Pip](https://pip.pypa.io/en/stable/installation/) (Python package installer)

### Installation

```bash
# Clone the repository
git clone https://github.com/bransometan/Healthiest365.git
cd Healthiest365

# Install dependencies
pip install -r requirements.txt
```
### Setting up the .env file
1) Create a .env file in the root of your project.
2) Add the following configurations to the .env file:
```bash
# Example .env file
# API_KEY: A secret key for securing your application. The secret key can be obtained from https://platform.openai.com/api-keys.
API_KEY=your_secret_key
```
3) Replace your_secret_key with appropriate values.

Note: Make sure to add .env to your .gitignore file to avoid pushing sensitive information to your repository.

## Usage
To run the application locally:

```bash
python app.py
Visit http://localhost:3000 in your browser.
```

## Tech Stack
- Python with Flask
- TailwindCSS
- OpenAI

## Features
- AI-Driven Meal Recommendations: Utilize advanced AI algorithms to generate customized meal suggestions based on user preferences, dietary needs, and health objectives.
- Nutritional Analysis via Search and Image Recognition: Deliver real-time nutritional insights using either search text or uploaded images, supporting users in maintaining a balanced diet and tracking nutrient intake.
- AI-Guided Dietary Advice: Provide personalized dietary tips aligned with users’ current eating habits and health targets, promoting sustainable lifestyle improvements.
- AI Enabled Chatbot (TODO)

Additionally, users can input their health data to receive more tailored nutrition and meal suggestions.

## Contributing
We welcome contributions! If you find a bug or have suggestions for improvement, please open an issue or submit a pull request.
