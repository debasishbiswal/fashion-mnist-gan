# Fashion‑MNIST GAN

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![PyTorch](https://img.shields.io/badge/PyTorch-1.12+-orange.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)

A simple Generative Adversarial Network (GAN) built with **PyTorch** that learns to generate 28×28 grayscale images of clothing items (t‑shirts, shoes, bags, etc.) from the [Fashion‑MNIST dataset](https://github.com/zalandoresearch/fashion-mnist).

---

## Motivation

I built this project to deepen my understanding of Generative Adversarial Networks (GANs) by applying them to a fun and familiar dataset — Fashion‑MNIST.  
Instead of sticking with handwritten digits (MNIST), I wanted to experiment with generating images of clothing items like t‑shirts, shoes, and bags.  
This project helped me practice:
- Setting up and training GANs from scratch in PyTorch,
- Visualizing how a generator improves over time,
- And exploring how GANs can be used for creative image generation tasks.

Feel free to fork this project, experiment with different architectures, or try other datasets!

---

## Features
✅ Trains a basic GAN using linear layers  
✅ Automatically downloads and loads the Fashion‑MNIST dataset  
✅ Visualizes **real vs fake images** after each epoch  
✅ Tracks and plots **generator & discriminator losses**  
✅ Includes code to **generate new images** after training

---

## Requirements
Install these dependencies before running:

```bash
pip install torch torchvision matplotlib
```

---

## How to Run
Clone this repository:

```bash
git clone https://github.com/debasishbiswal/fashion-mnist-gan.git
cd fashion-mnist-gan
```

Open the notebook (Fashion Test GAN.ipynb) in Google Colab or Jupyter Notebook.

➡️ Important:
If using Google Colab, enable GPU:
Runtime > Change runtime type > GPU

Run all cells in order.
Training will start and after each epoch you’ll see:

- Real vs generated images side by side
- Printed Generator and Discriminator losses

---

## Example Outputs
Example training output after several epochs:

Epoch [1/200] Loss D: 0.0040, Loss G: 7.6087
<img width="1588" height="278" alt="image" src="https://github.com/user-attachments/assets/22a5ac45-9440-4a35-96dd-bcca8ca2db19" />

Epoch [6/200] Loss D: 0.0586, Loss G: 4.1694
<img width="1588" height="278" alt="image" src="https://github.com/user-attachments/assets/0c3a91d2-f37a-4490-960f-0ef876fd1320" />

Epoch [200/200] Loss D: 0.5574, Loss G: 1.4600
<img width="1588" height="278" alt="image" src="https://github.com/user-attachments/assets/2fc0faad-d2f7-46f0-906a-262df62d6e78" />

✅ Fake images gradually start to resemble Fashion-MNIST clothing items.

---

## Project Structure

```bash
fashion-mnist-gan/
│
├── Fashion Test GAN.ipynb    # Main notebook with full training and visualization code
├── README.md                 # Project documentation
└── (optional) saved models, images, etc.
```

---

## License

MIT License – feel free to use, modify, and share!




