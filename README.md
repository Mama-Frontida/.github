# Frontida

## Introduction

Frontida is an innovative chatbot designed to support new mothers experiencing postpartum depression (PPD). Utilizing advanced natural language processing and video recommendation technologies, Frontida offers real-time, empathetic support and resources to help mitigate the effects of PPD. This project aligns with UN Sustainable Development Goals, specifically targeting Good Health & Well-being, Gender Equality, and Industry, Innovation, & Infrastructure.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software and how to install them:
- Node.js
- Python 3.8+
- Firebase account
- Access to Hugging Face and Render.com for deployment

### Installing

A step-by-step series of examples that tell you how to get a development environment running:

1. Clone the frontend and backend repository:

    ```bash
    git clone https://github.com/Mama-Frontida/FRONTIDA_FRONTEND.git frontend
    git clone https://github.com/Mama-Frontida/APIs.git backend
    ```

2. Set up the backend:

    ```bash
    # Navigate to the backend directory
    cd backend

    # Install dependencies
    pip install -r requirements.txt

    # Run the Flask server
    python app.py
    ```

3. Set up the frontend:

    ```bash
    # Navigate to the frontend directory from the root directory
    cd frontend

    # Install dependencies
    npm install

    # Start the development server
    npm run dev
    ```

### Firebase and Other Services Setup

Ensure you set up your Firebase project and update the firebase.jsx file in the frontend directory with your Firebase account keys.

## Technology Stack

- Frontend: React (Javascript)
- Backend: Python, Flask
- AI Model: T5-small model fine-tuned for PPD support
- Database & Authentication: Firebase
- Deployment: Vercel (Frontend), Render.com (Backend APIs), Hugging Face (Model)

## How to Use

After starting both frontend and backend servers, navigate to http://localhost:5173 to view the Frontida web application. Users can interact with the chatbot immediately, receiving support and video recommendations based on their queries.

For quick use and testing, visit the live platform on [https://frontida.vercel.app](https://frontida.vercel.app).

## Contributing

We welcome contributions to Frontida! If you have suggestions for improving the application or have found a bug, please open an issue or submit a pull request.

    cd frontida_frontend

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgments

Hat tip to anyone whose code was used.
Inspiration, etc.

### Team

- **Danroy Mwangi** - Team Lead and NLP Lead
- **Maria Muthiore** - Backend Lead
- **Nelson Kamau** - Frontend Lead
