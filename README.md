# AI-Image-Generation-using-Diffusion-Models


Diffusion Models are a class of **generative models** that create new data (such as images) by starting from pure noise and gradually removing it step by step — guided by a text prompt or conditioning input.

This project demonstrates how to use **Diffusion Models** for AI image generation using **Python**. You’ll learn the basic concepts, the underlying process, and how to implement and run a simple diffusion-based generator.

---

## 🚀 Features

* Generate images from text prompts
* Understand how diffusion processes denoise random noise into structured images
* Explore pretrained models from libraries like **Hugging Face Diffusers**
* Experiment with parameters (steps, guidance scale, etc.) for creative control

---

## 🧩 How It Works

1. **Start with noise** — a random tensor that looks like static TV noise.
2. **Iteratively denoise** — the model predicts and removes a portion of the noise at each step.
3. **Generate image** — after several iterations, a clear image emerges that matches the input prompt.

---

## 🧰 Requirements

Make sure you have the following installed:

```bash
pip install torch torchvision diffusers transformers accelerate
```

---

## 🧑‍💻 Usage

Run the main script:

```bash
python generate_image.py --prompt "A scenic view of Madina in watercolor painting style"
```

Example output:

```
🖼️ Generating image for prompt: "A scenic view of Madina in watercolor painting style"
✅ Image saved as output.png
```

---

## 📂 Project Structure

```
.
├── generate_image.py     # Main script for generating images
├── requirements.txt      # Dependencies
├── README.md             # Project documentation
└── outputs/              # Generated images
`
If you like this project, ⭐ star it on GitHub and share your feedback!
