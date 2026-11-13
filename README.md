# Emotion Prediction Using Deep Learning and NLP

An end-to-end Emotion Prediction web application that uses Natural Language Processing (NLP) and a Bidirectional Gated Recurrent Unit (BiGRU) neural network to predict emotions from textual input.

The project demonstrates the complete workflow of developing a Deep Learning model, building a backend API, integrating it with a frontend, and deploying it as a web application.

## Live Demo

🌐 **Live Application:** https://emotion-prediction-deep-learning-project.onrender.com/

## Project Overview

Understanding emotions expressed through text is an important Natural Language Processing task.

This project aims to build a text-based emotion prediction system that processes user input and predicts its associated emotion using a Deep Learning model.

Rather than limiting the project to model training and experimentation, the goal was to integrate the trained model into a complete web application.

## Model Architecture

**Bidirectional Gated Recurrent Unit (BiGRU)**

The project uses a BiGRU architecture to process textual sequences in both forward and backward directions.

This allows the model to learn contextual information from both directions of a text sequence.

## Technologies Used

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Natural Language Processing | NLP |
| Deep Learning | BiGRU |
| Backend | FastAPI |
| Frontend | HTML, CSS, JavaScript |
| Deployment | Render |

## Project Workflow

1. **Text Processing:** Prepare and preprocess textual input using NLP techniques.
2. **Feature Representation:** Convert processed text into numerical sequences for the neural network.
3. **Model Development:** Train a BiGRU-based Deep Learning model.
4. **Backend Development:** Develop API endpoints using FastAPI to serve predictions.
5. **Frontend Integration:** Connect the frontend application with the backend API.
6. **Deployment:** Deploy the application using Render.


## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/Ramesh-Dhamala/Emotion-Prediction-Deep-Learning-Project.git
```

### 2. Navigate to the project directory

```bash
cd Emotion-Prediction-Deep-Learning-Project
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

Activate it:

**Windows**
```bash
venv\Scripts\activate
```

**Linux / macOS**
```bash
source venv/bin/activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the application

```bash
uvicorn main:app --reload
```

Once running, FastAPI documentation is generally available at:

```text
http://127.0.0.1:8000/docs
```


## Key Learnings

- Practical implementation of NLP techniques.
- Understanding and applying BiGRU architecture.
- Integrating a trained Deep Learning model with FastAPI.
- Connecting frontend and backend components.
- Deploying a Deep Learning application.
- Debugging real-world integration and deployment issues.

## Future Improvements

- Experiment with different Deep Learning architectures.
- Improve model performance and generalization.
- Expand evaluation using additional classification metrics.
- Explore more advanced NLP techniques.

## Author

**Ramesh Dhamala**

Aspiring AI/ML Engineer | Deep Learning | NLP

[GitHub Profile](https://github.com/Ramesh-Dhamala)

---

