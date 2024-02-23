# Frontida

## Introduction

Frontida is a cutting-edge chatbot initiative designed to empower new mothers navigating the complexities of postpartum depression (PPD). By leveraging sophisticated natural language processing and tailored video recommendation technologies, Frontida delivers empathetic, real-time support and resources aimed at alleviating the impacts of PPD. This project contributes to the UN Sustainable Development Goals, emphasizing Good Health & Well-being, Gender Equality, and Industry, Innovation, & Infrastructure.

## Getting Started

Follow these instructions to set up the Frontida project on your local machine for development and testing purposes.

### Prerequisites

Ensure you have the following prerequisites installed:
- Node.js
- Python 3.8 or higher
- A Firebase account
- Access to Hugging Face and Render.com for deployment purposes

### Installation Guide

#### Clone the Repositories

```bash
git clone https://github.com/Mama-Frontida/FRONTIDA_FRONTEND.git frontend
git clone https://github.com/Mama-Frontida/APIs.git backend
```

#### Backend and YouTube Microservices Setup

```bash
cd backend
pip install -r requirements.txt
python app.py  # Runs the Flask server
```

#### Frontend Setup

```bash
cd frontend  # Assuming you're in the root directory
npm install   # Install dependencies
npm run dev   # Start the development server
```

#### T5-Small Model Setup

To get started with the T5-Small model:

```bash
git clone https://github.com/Mama-Frontida/text-generation-models.git model-repo
cd model-repo  # Navigate to the model repository
# Follow the Jupyter Notebook instructions within the repo
```

For cloning the production repository from our Hugging Face account:

```bash
git clone https://huggingface.co/Danroy/MamaFrontida
```

Ensure you follow the notebook instructions for running the model and generating text. Install any necessary dependencies as specified within the notebook or the repository's documentation.

### Firebase and Other Services Setup

Set up your Firebase project and ensure the `firebase.jsx` file in the frontend directory is updated with your Firebase configuration keys.

## Technology Stack

- **Frontend:** React (JavaScript)
- **Backend:** Python, Flask
- **AI Model:** T5-small model, fine-tuned for PPD support
- **Database & Authentication:** Firebase
- **Deployment:** Vercel (Frontend), Render.com (Backend APIs), Hugging Face (Model)

## How to Use

After initiating the frontend and backend servers, open http://localhost:5173 to access the Frontida web application. Users can engage with the chatbot for support and video recommendations tailored to their needs.

For immediate access, visit our live platform at [https://frontida.vercel.app](https://frontida.vercel.app).

## Contributing

Your contributions to Frontida are highly appreciated. Whether you're improving the application or reporting bugs, please feel free to open an issue or submit a pull request.

## License

Frontida is made available under the MIT License. For more details, see the [LICENSE.md](LICENSE) file.

## Acknowledgments

We extend our gratitude to all individuals and organizations whose contributions have made Frontida a reality. Special thanks to our dedicated team members for their relentless effort and innovation:

- **Danroy Mwangi** - Team Lead & NLP Expert
- **Maria Muthiore** - Backend Development Lead
- **Nelson Kamau** - Frontend Development Lead

Together, we continue to strive towards making a significant impact on the well-being of new mothers worldwide.
