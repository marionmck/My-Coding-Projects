
# My Coding Projects

## Description

This portfolio is a showcase of my work and skills, where you can explore some of the projects I've developed.

## Skills & Languages

- Web Development 
    - HTML & CSS
    - JavaScript
    - React
    - PHP
    - SQL
- Object Oriented Programming
- Application Programming Interface
- Artificial Intelligence 
    - Computer Vision
    - Robotics AI

## <center>My Projects</center>

### AI | Reinforcement Learning (Deep Q-Learning) | Pong Game

This project focuses on developing a reinforcement learning model for playing the game Pong. Inspired by the classic Atari game, the aim is to train an agent using the Deep Q-Learning (DQN) algorithm to play against either a computer-controlled or human opponent. The project explores the game mechanics, the challenges of reinforcement learning in reward sparse environments, and the concept of reward shaping. A custom Pong environment is created, allowing the incorporation of additional information and the implementation of reward shaping techniques. The DQN algorithm is implemented using Python and the Keras package from TensorFlow.

#### Technologies Used

- Python
- Keras

#### Installation Instructions

1. Make sure you have Python installed on your computer.
2. Download the PyGame library by running the following command: pip install pygame
3. Download the Keras library by running the following command: pip install keras

#### Usage Instructions

1. Download the ipynb file (CALLED WHAT?) from the repository below.
2. Open the ipynb file using Jupyter Notebook, JupyterLab or on Google Colab Notebooks.
3. Run the notebook to train and test the Deep Q-Learning model.

#### Screenshots or Demo

[Provide screenshots or a link to a demo if available]

Repository: [Pong DQN](https://github.com/marionmck/deep-q-learning-pong)

---

### AI | Hybrid Music Recommendation System with PSO

In this project, I utilised a hybrid methodology combining content-based and collaborative filtering techniques to develop a music recommendation system. To train the model, the SVD (Singular Value Decomposition) model from the Surprise Python Library was used, inspired by Simon Funk who achieved success in the Netflix Prize using his model (known as Funk-SVD).

The SVD model, based on matrix factorization, predicts a rating (represented as $r_u, i$) that a user ($u$) will assign to an item ($i$), where the item in this case refers to a song. This prediction is determined by calculating the dot product of two matrices: $q_i$ (representing item latent factors) and $p_u$ (representing user latent factors). The SVD model's objective function employs stochastic gradient descent, which iteratively reduces the prediction error.

Various parameters were available to optimise the model's performance. These parameters control the number of epochs (iterations) performed during training, the number of latent factors to be discovered, and hyperparameters such as the learning rate and regularization term, which influence the accuracy and generalisation capabilities of the model. To further refine the recommendation system's accuracy and quality of recommendations, swarm-intelligence algorithms were used to fine-tune the hyperparameters to ensure the best possible results for personalised music recommendations.

#### Technologies Used

- Python 3
- Numpy
- Pandas
- Scikit Learn
- SciPy
- Surprise Python Library
- PySwarms

#### Usage Instructions

1. Download the ipynb file (CALLED WHAT?) from the repository below.
2. Open the ipynb file using Jupyter Notebook, JupyterLab or on Google Colab Notebooks.
3. Run the notebook to train the recommendation system model.
4. Pre-trained model files are also provided for others to improve the existing model.

#### Screenshots or Demo

[Provide screenshots or a link to a demo if available]

Repository:

---

### Web Development | API and Documentation Website

I implemented an API and documentation website for the CHI2018 conference. The API enables users to retrieve data about venues and events, with filtering capabilities for customised queries. Furthermore, the documentation website provides clear instructions on how to interact with the API and is responsive for mobile devices.

#### Key Features

- Robust API for data access.
- Filtering parameters for tailored queries.
- A user-friendly documentation website with a responsive layout.
- Server-side development using Object-Oriented PHP.
- Client-side development with modern JavaScript frameworks (React).
- Data representation in JSON.
- Token-based authentication for security.
- Adherence to architectural best practices such as REST, MVC, and N-tier for maintainability, scalability, and robustness.

#### Screenshots or Demo

[Provide screenshots or a link to a demo if available]

Repository:

---

### Web Development | Calendar Application

The web-based calendar application is designed to help students plan and organise their learning and activities. It features a user log-in system, various calendar views and a responsive and intuitive interface. Users can create, schedule, modify, and delete events using my application.

#### Key Features

1. User Log-In: Students can securely log in using their email and password.
2. User Interface: The interface is clean, intuitive, and responsive for easy navigation.
3. Calendar View: Provides daily, weekly, and monthly views to display important events.
4. Event Creation: Users can create and schedule events such as exams, assignments, and extracurricular activities.
5. Event Modification: Users can edit or delete events to accommodate changes or cancellations.

#### Technologies Used

- HTML, CSS
- JavaScript & Luxon JS library for date and time manipulation.
- PHP: Object-oriented programming and utiliSing autoloading classes.
- MySQL for storing and retrieving student event data.

#### Screenshots or Demo

[Provide screenshots or a link to a demo if available]

Repository:
