# Vanilla GAN for MNIST Dataset (PyTorch)

## Overview
This project implements a **Vanilla Generative Adversarial Network (GAN)** using **PyTorch** to generate realistic images of handwritten digits from the **MNIST** dataset. The GAN consists of two main components:

- **Generator**: Takes random noise as input and generates fake MNIST images.
- **Discriminator**: Classifies images as real (from the MNIST dataset) or fake (generated by the Generator).

---

## How to Run

### Prerequisites:
Ensure that you have the following installed:
- Python 3.x
- Jupyter Notebook
- PyTorch
- torchvision
- matplotlib
- numpy

### Steps:
1. **Clone the repository**:
   Clone the project to your local machine:
   ```bash
   git clone https://github.com/MOSTAFA1172m/mnist-vanilla-gan.git
   
   ```

2. **Install dependencies**:
   Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook**:
   Start Jupyter Notebook in the project directory:
   ```bash
   jupyter notebook
   ```

4. **Open and run the notebook**:
   Open the `mnist_gan.ipynb` file and run each cell step by step.

---

## How it Works

- **Generator**: Takes a 100-dimensional random noise vector and passes it through several layers (fully connected, ReLU, BatchNorm) to generate a 28x28 image.
- **Discriminator**: Takes a 28x28 image and uses several layers to classify it as either real or fake.

---

## Visualizing Results

- During training, the model generates fake images and saves them periodically.
- After each training phase, you can check the generated images to see the improvement.

Example of generated images after epoch 100:
![Generated Image](Here’s an updated **README** that includes the MIT License and reflects that you’re using it for your Vanilla GAN project in PyTorch:

---

# Vanilla GAN for MNIST Dataset (PyTorch)

## Overview
This project implements a **Vanilla Generative Adversarial Network (GAN)** using **PyTorch** to generate realistic images of handwritten digits from the **MNIST** dataset. The GAN consists of two main components:

- **Generator**: Takes random noise as input and generates fake MNIST images.
- **Discriminator**: Classifies images as real (from the MNIST dataset) or fake (generated by the Generator).

---

## How to Run

### Prerequisites:
Ensure that you have the following installed:
- Python 3.x
- Jupyter Notebook
- PyTorch
- torchvision
- matplotlib
- numpy

### Steps:
1. **Clone the repository**:
   Clone the project to your local machine:
   ```bash
   git clone https://github.com/your-username/Vanilla-GAN-MNIST-PyTorch.git
   cd Vanilla-GAN-MNIST-PyTorch
   ```

2. **Install dependencies**:
   Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook**:
   Start Jupyter Notebook in the project directory:
   ```bash
   jupyter notebook
   ```

4. **Open and run the notebook**:
   Open the `Vanilla_GAN_MNIST.ipynb` file and run each cell step by step.

---

## How it Works

- **Generator**: Takes a 100-dimensional random noise vector and passes it through several layers (fully connected, ReLU, BatchNorm) to generate a 28x28 image.
- **Discriminator**: Takes a 28x28 image and uses several layers to classify it as either real or fake.

---

## Visualizing Results

- During training, the model generates fake images and saves them periodically.
- After each training phase, you can check the generated images to see the improvement.

Example of generated images:
![Generated Image](generated_image_epoch_1000.png)

---

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.

---

This version of the README should be simple and clear for a Jupyter Notebook project with the MIT License. Let me know if you need any further adjustments!

---

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.

---

This version of the README should be simple and clear for a Jupyter Notebook project with the MIT License. Let me know if you need any further adjustments!
