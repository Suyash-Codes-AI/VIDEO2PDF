# 🎬 Video2PDF

**Video2PDF** is a powerful yet simple tool that allows you to **convert YouTube videos into summarized PDF notes**.  
Just paste a YouTube video link — the app automatically extracts the transcript, summarizes the key content, and generates a clean, downloadable PDF file.

---

## 🚀 Features

- 🎥 **YouTube Link Input** – Just paste the video URL.  
- 🧠 **Automatic Transcript Extraction** – Uses the `ytvideo2pdf` library to fetch the video transcript.  
- ✍️ **AI-Based Summarization** – Generates concise notes from long videos.  
- 📄 **Instant PDF Generation** – Creates a well-formatted, ready-to-download PDF file.  
- ⚡ **Lightweight and Fast** – Minimal setup, quick processing.  

---

## 🛠️ Tech Stack

- **Python 3.10+**  
- **ytvideo2pdf** (core library)  
- **Tesseract OCR** (for text extraction from video frames if needed)  


---

## 📦 Installation

1. **Clone this repository**
   ```bash
   git clone https://github.com/<your-username>/Video2PDF.git
   cd Video2PDF
   ```

2. **Install dependencies**
   ```bash
   pip install ytvideo2pdf
   ```

3. **Install Tesseract OCR**  
   - [Download Tesseract OCR](https://github.com/tesseract-ocr/tesseract) for your OS.  
   - Add the Tesseract executable path to your system environment variables.  

---

## 🧠 Usage

### 🖥️ Command Line
```bash
python -m ytvideo2pdf --input youtube --url "YOUTUBE_VIDEO_URL"
```

The tool will automatically:  
1. Fetch the transcript  
2. Summarize it  
3. Create and save the PDF in the output folder  

---

## 📁 Project Structure

```
Video2PDF/
├── main.py
├── requirements.txt
├── README.md
└── output/
    └── video_summary.pdf
```

---

## 📚 Example Output

> **Title:** How Neural Networks Work  
> **Summary:**  
> - Explained perceptrons and activation functions  
> - Discussed backpropagation and gradient descent  
> - Covered overfitting, regularization, and dropout  
> - Provided real-world applications of deep learning  

---

## 💡 Use Cases

- Quickly generate notes from educational videos  
- Summarize long tutorials or interviews  
- Create study PDFs for offline use  
- Save time revising concepts from video content  

---

## 🤝 Contributing

Contributions are welcome!  
If you’d like to improve this project, please:  
1. Fork the repo  
2. Create a new branch  
3. Commit your changes  
4. Open a pull request  

---

## ⭐ Support

If you find this project useful, don’t forget to **star ⭐ the repository**!  
Your support helps keep this project alive and growing 🚀  
