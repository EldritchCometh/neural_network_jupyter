# Neural Networks: Building Deep Understanding

This tutorial is designed to help learners build deep understanding of neural networks by building one step-by-step from scratch. This implementation was hand crafted to be the most effetive educational tool I am capable of making.

Network components are defined as objects and prewired so they have, as attributes in themselves, all of the correct connections to their neihbors. From this foundation methos related to the training and operation of the network are defined inside of the network componenets themselves without any required knowledge of the larger state of the network. In this way a focus and enfacis can be placed on invidual network components and their local role in the operation of the larger structure. From this bottom up approach a clearer understanding of the funcioning of the network as a whole can be obtained. 

It may occur to you that this sounds like we are trading a great deal of performance and optimization in exhchange for previously mentioned considerations. You would be correct. However, despite this, the final part tackles a real-world classification task, delivering some pretty respectable results.

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
   source venv/bin/activate
   pip install -r requirements.txt
   ```

## Usage

1. Launch Jupyter Lab:

   ```bash
   jupyter lab
   ```

2. Study, run, and expiriment with the notebooks in the order from Part 01 to Part 07.

## License

This is free and unencumbered software released into the public domain.
