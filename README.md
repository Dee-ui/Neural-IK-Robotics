# Neural-IK-Robotics
Welcome to the NeuralKinematics repository! 🤖🧠  In this project, we explore the exciting fusion of neural networks and robotics, specifically focusing on solving the complex inverse kinematics problem for robot manipulators. 

# Neural networks project for solving inverse kinematics problem of robot manipulators

## Project Description
In the industry, robots are utilized in solving various tasks especially to boost productivity or preserve human labour. This project's primary goal is to develop a machine learning model capable of predicting the various joint parameters that can move a robot arm to a specific end effector position. This can be very helpful because it can better automate the field of industrial robotics especially to improve efficiency and reliability.

## About the Data
The dataset used in this project is generated using the Denavit-Hartenberg forward kinematics method. The DH parameters are gotten and incorporated with the standard transformation matrix. The dataset is generated according to the specific joint constraints of the particular robotic arm. Also in this method of analysis, both the end effector position and the quarternion representation are utilized in training the neural networks model to find patterns in the data in order to accurately solve the inverse kinematics problem.

## Table of Contents
- [Setup](#setup)
- [Contributing](#contributing)
- [License](#license)
- [Authors and Acknowledgments](#authors-and-acknowledgments)
- [Project Status](#project-status)
- [Contact](#contact)

## Setup
It is recommended that this project is ran on [Google colaboratory](colab.research.google.com) using a GPU because of the large computing power required to train and evaluate the neural networks model. [Google colaboratory](colab.research.google.com) also has most of the required tools and libraries needed to execute the project. Any tools that wasn't available was installed using PIP and to do the same, just uncomment and run the required code cell.

To use this repository,
- clone it to your local machine using the code below;
  ```git clone https://github.com/Dee-ui/Nueral-IK-Robotics.git```
- Navigate to project directory;
    ```cd Nueral-IK-Robotics```
- Run the .ipynb Notebook using [Google colaboratory](colab.research.google.com) to explore and execute the project ;
    ```jupyter notebook end-end-bulldozer-price-regression.ipynb```


## Contributing
Contributions are welcome! If you'd like to contribute to this project, please review our contribution guidelines before getting started.

## License
This project is licensed under the MIT License.

## Contacts and Acknowledgments
`Author/programmer` :- [Agbonoga Dauda (Project Lead)](daudaagbonoga@gmail.com)

`Supervisor`:- Engr. Ebunkamaodo Odudu - ```odudu.ebunkamaodo@uniben.edu```

Team members

Ahekobuwa Nosamudianaede Praise 	- ```nosamudianaedeahekobuwa@gmail.com```

Ahueansebhor Emmanuel Osemuahun		- ```emmahueans99@gmail.com```

Aihie Daniel Aisosa	- ```danielaisosaaihie@gmail.com```


Special thanks to the University of Benin and [Engr. Ebunkamaodo Odudu](odudu.ebunkamaodo@uniben.edu)  for providing the inspiration for this project.
