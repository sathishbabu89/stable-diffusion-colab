# 🎨 Stable Diffusion Image Generation via Google Colab (Free GPU)

This project demonstrates how to generate images from text using the open-source **Stable Diffusion v1.5** model on **Google Colab**, using Hugging Face’s `diffusers` library.

---

## ✅ Features

- No local GPU or RAM needed
- Powered by Hugging Face 🤗 `diffusers`
- Free-tier compatible
- Custom prompt support

---

## 🧰 Requirements

- A free [Google Colab](https://colab.research.google.com) account
- A free [Hugging Face](https://huggingface.co) account and access token

---

## 🚀 Steps to Run

1. **Open the Notebook**  
   👉 [Click here to open in Colab](https://colab.research.google.com/github/your-repo-url/stable_diffusion_colab.ipynb)

2. **Set GPU Runtime**  
   - In Colab, go to `Runtime > Change runtime type`
   - Set **Hardware Accelerator = GPU**

3. **Login to Hugging Face**
   - Run the login cell in the notebook
   - Enter your Hugging Face Access Token (get one from [here](https://huggingface.co/settings/tokens))

4. **Run the Image Generation Cell**
   - Update the `prompt` variable with any creative text
   - Execute the cell to generate and display the image

---

## ✍️ Example Prompt

```python
prompt = "A futuristic cyberpunk cityscape at night, watercolor style"
```

---

## 🖼️ Sample Output

<p align="center">
  <img src="sample_output.png" width="400"/>
</p>

---

## 📜 License

MIT © 2025 Your Name
