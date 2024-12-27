# Neural Networks: Building Deep Understanding

This is a tutorial designed to help learners build deep understanding of neural networks by building one step-by-step from scratch. But, it's more than that. This implementation was painstakingly hand crafted to be the ultimate educational tool. Simplicity, clarity modularity are radically prioritized. The goal is to provide an approachable guide for individuals looking to grasp the fundamental concepts of neural networks and their components through Python code.

## Project Structure

The project is divided into seven parts. Each part builds upon the previous ones to incrementally construct a fully functional neural network capable of solving real-world classification tasks.

### **Part 01: Wiring Up the Network**

This part focuses on the physical structure of the network. It defines a framework that simplifies future challenges by abstracting away concerns about the overall shape of the network, allowing us to focus on individual nodes and their local relationships with neighbors. 

### **Part 02: Forward Propagation**

Here, forward propagation is implemented to demonstrate how inputs pass through the network to produce outputs. The mechanics of weighted sums and activation functions are explored.

### **Part 03: Backpropagating Error Signal**

This section covers part of the backpropagation algorithm, explaining how to quantify each node's impact on the total error by propagating error contributions backward through the network.&#x20;

### **Part 04: Gradient Descent**

Gradient descent is introduced as the optimization algorithm for updating parameters in the network.&#x20;

### **Part 05: Training and Metrics**

This part covers training the neural network on small toy datasets and exploring how performance metrics are calculated.

### **Part 06: Visualization**

Here we build tools for visualization and use them to understand how neural networks model real-world data as a function that can be trained and plotted against the data.

### **Part 07: A Real Classification Task**

The tutorial culminates with a real-world classification task using the MNIST dataset of handwritten digits. The data is loaded, preprocessed, and used to train the network, demonstrating its practical application.

## Features

- Modular code structure for easy understanding and extension.
- Step-by-step demonstration of key neural network concepts.
- Clear examples of forward propagation, backpropagation, and gradient descent.
- Training on real datasets with visualized results.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- scikit-learn
- Matplotlib

### Installation

1. Clone the repository to your local machine:

   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:

   ```bash
   cd <project-directory>
   ```

3. Install requirements.txt:

   ```bash
   python3 -m venv venv
   source /venv/bin/activate
   pip install -r requirements.txt
   ```

## Usage

1. Launch Jupyter Notebook:

   ```bash
   jupyter lab
   ```

2. Study, run, and expiriment with the notebooks in the order of their filenames (Part 01 to Part 07).

## License

This is free and unencumbered software released into the public domain.

---

Happy learning! If you have any questions or need further clarification, feel free to reach out.
