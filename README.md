# Neural Networks: Building Deep Understanding

This tutorial is designed to help learners gain a deep understanding of neural networks by building one from scratch. The implementation has been carefully crafted to serve as the most effective educational tool I know how to provide.

In this tutorial, network components are defined as objects that carry, as attributes, all necessary connections to their neighboring components. Building on this foundation, methods related to training and operation are housed within each component itself, eliminating any need for awareness of the broader state of the network. This bottom-up approach allows us to conceptualize the network’s functioning as a set of discrete local operations, clarifying the networks operation as a whole.

It may seem that we’re sacrificing a considerable degree of performance and optimization for the sake of these educational considerations. While that’s true, we will still achieve respectable results when we tackle a real-world classification task in the final section.

## Project Structure

The project is divided into seven parts. Each part builds upon the previous ones to incrementally construct a fully functional neural network capable of solving real-world classification tasks.

### **Part 01: Wiring Up the Network**

This part focuses on the physical structure of the network. It defines a framework that simplifies future challenges by abstracting away concerns about the overall shape of the network, allowing us to focus on individual nodes and their local relationships with neighbors.

### **Part 02: Forward Propagation**

Here, forward propagation is implemented to demonstrate how inputs pass through the network to produce outputs. The mechanics of weighted sums and activation functions are explored.

### **Part 03: Backpropagating Error Signal**

This section covers part of the backpropagation algorithm, explaining how to quantify each node's impact on the total error by propagating error contributions backward through the network.

### **Part 04: Gradient Descent**

Gradient descent is introduced as the optimization algorithm for updating parameters in the network.&#x20;

### **Part 05: Training and Metrics**

This part covers training the neural network on small toy datasets and exploring how performance metrics are calculated.

### **Part 06: Visualization**

Here we build tools for visualization and use them to understand how neural networks model real-world data as a function that can be trained and plotted against the data.

### **Part 07: A Real Classification Task**

The tutorial culminates with a real-world classification task using the MNIST dataset of handwritten digits. The data is loaded, preprocessed, and used to train the network, demonstrating its practical application.

## Getting Started

### **Recommended installation with venv**

### Prerequisites

- git
- python3
- python3-pip
- python3-venv

### Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/EldritchCometh/neural_network_jupyter.git
   ```

2. Navigate to the project directory:

   ```bash
   cd neural_network_jupyter
   ```

3. Install requirements.txt:

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```

### **Optional installation without venv**

### Prerequisites

- git
- python3
- python3-pip

### Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/EldritchCometh/neural_network_jupyter.git
   ```

2. Navigate to the project directory:

   ```bash
   cd neural_network_jupyter
   ```

3. Install requirements.txt:

   ```bash
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
