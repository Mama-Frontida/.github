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

2. Set up the backend and Youtube Microservices:

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
4. Frontida's T5-Small Model Guide

Welcome to the guide on accessing and running Frontida's T5-Small model, designed to support new mothers. This model aids in text generation for various purposes related to maternal health and parenting. Below are the steps to get started with the model through a Jupyter Notebook available in the GitHub repository of Frontida's text generation models.

  Cloning the Model Repository

To begin, clone the repository containing the Jupyter Notebook for the T5-Small model. Follow these steps:

```bash
git clone https://github.com/Mama-Frontida/text-generation-models.git model-repo
```

 Accessing the Notebook

Once the repository is cloned, navigate to the directory:

```bash
cd model-repo
```

 Running the Notebook

Once you have accessed the cloned repository, locate the Jupyter Notebook specific to the T5-Small model. Open the notebook using Jupyter Notebook or JupyterLab environment and follow the instructions provided within the notebook to run the model and generate text.

 Additional Notes

Make sure to have the necessary dependencies installed as per the requirements specified in the repository's README or within the notebook itself. You may need to install specific Python libraries or pretrained model weights to successfully run the model.
If you wish to clone the production repository from our huggingface account, here is the link

```bash
git clone https://huggingface.co/Danroy/MamaFrontida
```


For any questions or issues regarding the model or its usage, please refer to the documentation provided within the repository or contact the Frontida team for assistance.

Happy text generation! 🚀

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
