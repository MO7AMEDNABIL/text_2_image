# 🖼️ AI Text-to-Image Generator

This project allows you to generate images from text prompts using **Stable Diffusion XL 1.0**.  
It runs on **Google Colab** (with free T4 GPU) and exposes a Flask server using **ngrok** so you can access it via a public URL.

---

## 🚀 Features
- Text-to-image generation with **Stable Diffusion XL 1.0**
- Flask API endpoint (`/generate`) for prompt-based image generation
- HTML/CSS/JS frontend with a clean UI and loading bar
- Uses **ngrok** to make the server accessible publicly
- Runs seamlessly on **Google Colab with T4 GPU**

---

## 🛠️ Tools & Libraries
- [Diffusers](https://github.com/huggingface/diffusers) (Stable Diffusion XL 1.0)
- PyTorch
- Flask + Flask-CORS
- Ngrok
- HTML, CSS, JavaScript

# ☁️ Running on Google Colab with GPU

Open Google Colab

1) Upload txt_2_imahe.py

2)Select Runtime → Change runtime type → GPU (T4).

3)Install dependencies :

diffusers
Ngrok
Flask + Flask-CORS

4)Run the Flask + ngrok server
5)Copy the ngrok public URL shown in the output.
5)Paste the URL into your frontend fetch request.

# 🎨 Example Usage

Enter a prompt:

"A futuristic flying car in a cyberpunk city"


The system generates a high-quality image in seconds.

🙏 Acknowledgements

Stability AI
 for Stable Diffusion XL 1.0

Hugging Face
 for Diffusers

Google Colab for free T4 GPU

Ngrok for tunneling service
