# 🎨 AI-Based Neural Style Transfer

Transform ordinary images into artistic masterpieces using Deep Learning. This project implements **Neural Style Transfer (NST)** to combine the content of one image with the artistic style of another, generating visually stunning artwork.

---

## 📌 Project Overview

Neural Style Transfer is a Deep Learning technique that uses Convolutional Neural Networks (CNNs) to blend the content of one image with the style of another. This project utilizes a pre-trained **VGG19** model to extract content and style features and optimizes a generated image to preserve both.

---

## 🚀 Features

- Upload a content image
- Upload a style image
- Generate artistic images
- Uses pre-trained VGG19 network
- Adjustable content and style weights
- High-quality stylized output
- Easy-to-understand implementation

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Pillow (PIL)
- OpenCV
- Jupyter Notebook

---

## 📂 Project Structure

```
AI-Based-Neural-Style-Transfer/
│
├── images/
│   ├── content/
│   ├── style/
│   └── output/
│
├── neural_style_transfer.ipynb
├── requirements.txt
├── README.md
└── LICENSE
```

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/Suraksha1209/AI-Based-Neural-Style-Transfer.git
```

```bash
cd AI-Based-Neural-Style-Transfer
```

### Create Virtual Environment (Optional)

```bash
python -m venv venv
```

### Activate Environment

Windows

```bash
venv\Scripts\activate
```

Linux / Mac

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

Run the Jupyter Notebook:

```bash
jupyter notebook
```

Open

```
neural_style_transfer.ipynb
```

Select:
- Content Image
- Style Image

Run all cells to generate the stylized image.

The generated image will be saved in the **output** folder.

---

## 🧠 How It Works

1. Load Content Image
2. Load Style Image
3. Extract features using VGG19
4. Compute Content Loss
5. Compute Style Loss using Gram Matrix
6. Optimize the generated image
7. Save the final stylized output

---

## 📸 Sample Results

| Content | Style | Output |
|---------|-------|--------|
| Input Image | Artwork | Stylized Image |

> Add screenshots in the `images/output` folder and update this section.

---

## 📈 Applications

- Digital Art
- Image Editing
- Creative AI
- Graphic Design
- Mobile Photography Filters
- AI Art Generation

---

## 📚 Future Improvements

- Multiple style transfer
- Real-time style transfer
- Fast Neural Style Transfer
- Web application using Flask
- Streamlit interface
- GPU optimization

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit changes

```bash
git commit -m "Added new feature"
```

4. Push to GitHub

```bash
git push origin feature-name
```

5. Create a Pull Request

---

## 👩‍💻 Author

**Suraksha Chaudhari**

- GitHub: https://github.com/Suraksha1209

---

## ⭐ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub.

---

## 📄 License

This project is licensed under the MIT License.
