
# My Coding Project's

## Description

Welcome! This portfolio is a showcase of my work and skills, where you can explore some of the projects I've developed.

## Skills & Languages

- Web Development 
    - HTML & CSS
    - JavaScript
    - React
    - PHP
    - SQL
- Application Programming Interface
- Object Oriented Programming
    - Java  
- Artificial Intelligence 
    - Python 
    - Computer Vision
    - Autonomous Systems

## My Projects

### AI | Reinforcement Learning (Deep Q-Learning) | Pong Game

Repository: [Pong DQN](https://github.com/marionmck/deep-q-learning-pong)

This project focuses on developing a reinforcement learning model for playing the game Pong. Inspired by the classic Atari game, the aim is to train an agent using the Deep Q-Learning (DQN) algorithm to play against either a computer-controlled or human opponent. The project explores the game mechanics, the challenges of reinforcement learning in reward sparse environments, and the concept of reward shaping. A custom Pong environment is created, allowing the incorporation of additional information and the implementation of reward shaping techniques. The DQN algorithm is implemented using Python and the Keras package from TensorFlow.

#### Technologies Used

- Python
- Keras

#### Installation Instructions

1. Make sure you have Python installed on your computer.
2. Download the PyGame library by running the following command: pip install pygame
3. Download the Keras library by running the following command: pip install keras

#### Usage Instructions

1. Download the ipynb file "Pong DQL Train.ipynb" from the repository below.
2. Open the ipynb file using Jupyter Notebook, JupyterLab or on Google Colab Notebooks.
3. Run the notebook to train the Deep Q-Learning model, watch as the agent get's better!

#### Demo

The right player is controlled by the AI while the left player follows the balls Y position at a fixed velocity.

https://github.com/marionmck/My-Coding-Projects/assets/82905503/a8ebca34-4ac8-4ede-901a-976c4edbbf25

---

### AI | Hybrid Music Recommendation System with PSO

Repository: [Hybrid Music Recommendation System](https://github.com/marionmck/hybrid-music-recommendation-system)

In this project, I utilised a hybrid methodology combining content-based and collaborative filtering techniques to develop a music recommendation system. To train the model, various algorithms from the Surprise Python Library such as k-NN, NMF and Slope One were tested. Howeverr, the SVD (Singular Value Decomposition) algorithm, inspired by Simon Funk who achieved success in the Netflix Prize, had the best performance. To train the model, the Million Song Dataset from Echo Nest and the R2-Yahoo! Music dataset were used. Additional, song metadata from the Spotify API was used to enrich the two datasets with more features.

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

1. Download a ipynb file from the repository.
2. Open the ipynb file using Jupyter Notebook, JupyterLab or on Google Colab Notebooks.
3. Run the notebook (select run all cells) to train the recommendation system model.

---

### Web Development | API and Documentation Website

Repository: [CHI-Conference API](https://github.com/marionmck/api-chi-conference)

I built an API along with a documentation page (see screenshot below) for the CHI2018 conference. The API can retrieve data about presenters, venues and events, with filtering capabilities for customised queries. I created a website that imports data from the API for users to easily find events, their location and who will be presenting, along with an admin section to modify any details. Furthermore, the documentation website provides clear instructions on how to interact with the API and is responsive for mobile devices.

#### Key Features

- Robust API for data access.
- Filtering parameters for tailored queries.
- A user-friendly documentation website with a responsive layout.
- Server-side development using Object-Oriented PHP.
- Client-side development with modern JavaScript frameworks (React).
- Data representation in JSON.
- Token-based authentication for security.
- Adherence to architectural best practices such as REST, MVC, and N-tier for maintainability, scalability, and robustness.

#### Screenshot
![CHI API Documentation Page Screenshot](https://github.com/marionmck/My-Coding-Projects/assets/82905503/11779c31-44d0-448a-8864-f68998ca8c54)

---

### Web Development | Calendar Application

Repository: [Calendar Application](https://github.com/marionmck/calendar-app)

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

#### Screenshot

![Calendar App Screenshot](https://github.com/marionmck/My-Coding-Projects/assets/82905503/3abd8fce-ecde-4e67-bf62-50aebf021bd7)

