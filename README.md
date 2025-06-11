# pytorch-crashcourse-for-beginners
# PyTorch Fundamentals - Crash Course Progress

Welcome to my **PyTorch learning journey**, following the excellent [PyTorch for Deep Learning](https://github.com/mrdbourke/pytorch-deep-learning) crash course by [Daniel Bourke](https://github.com/mrdbourke), available at [LearnPyTorch.io](https://www.learnpytorch.io/).

This repo will track my progress, experiments, and reflections — with special attention to making it beginner-friendly and practical.

---

## 🔥 Current Phase: PyTorch Fundamentals

This first commit covers the **very basics** of PyTorch:

### ✅ Topics Covered:
- **What is PyTorch?**
- **Tensors**: the building blocks of neural networks
  - Scalars (rank-0 tensors)
  - Vectors (rank-1 tensors)
  - Matrices (rank-2 tensors)
  - Higher-rank tensors
- **Setup + Imports**
  - Setting up a Python environment
  - Installing PyTorch using pip
  - Importing torch and checking version/device availability


### Day 2:

Today we covered generating tensor random numbers, understanding and manipulating that data (image data)

## Tomorrow we will cover:
### CREATING TENSORS WITH ZEROS AND ONES IN PyTorch
---

## 🚧 Project Structure (so far)

PYTORCH_CRASHCODE/
│
├── fundamentals/
│ └── 00_pytorch_fundamentals.ipynb # Covers all the basics listed above
│
├── .gitignore
├── README.md
└── requirements.txt


> **Note:** I aim to organize by module/topic, matching the course layout.

---

## ⚙️ Environment & Device Strategy

Since I'm currently working on a machine **without a dedicated GPU**, I'm writing and testing code **locally using CPU** (via VS Code + virtualenv).

For projects that require longer training or GPU acceleration:
- I will port relevant notebooks or scripts to **Google Colab**, where I can access free GPUs.
- After training and validation, I’ll **sync the results/models back into this repo**.

---

## 💡 Why This Repo Exists

I built this repo for:
- **Practice** — Writing everything out builds real understanding.
- **Portfolio** — This will evolve into real projects over time.
- **Other Beginners** — If you're new to PyTorch, this structure and notes are for you.

---

## 📌 Credit & Source

All credit goes to:
- [Daniel Bourke’s Course](https://github.com/mrdbourke/pytorch-deep-learning)
- Website: [https://www.learnpytorch.io/](https://www.learnpytorch.io/)
- YouTube Series: [PyTorch Deep Learning (YouTube)](https://www.youtube.com/playlist?list=PLy-5gUQx0QkP1nAXA3uVzXuwlKfD9b9iG)

This repo simply contains my structured and personalized implementation of the lessons.

---

## 🧭 What’s Next?

The next commits will include:
- Building simple neural networks from scratch
- Working with datasets and dataloaders
- Model training/evaluation
- Saving/loading models
- Transitioning from local CPU training to Colab for GPU

Stay tuned.

---

### 🚀 For Beginners Like Me

If you're starting from zero:
- **Clone this repo**
- Follow along with each `*.ipynb` file
- Read my comments and notes as you go
- Ask questions — this is for us.

> You're not too late. You’re early.
