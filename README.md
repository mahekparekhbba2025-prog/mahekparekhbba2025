# mahekparekhbba2025
# 📝 Wordify

*Wordify* is a smart document conversion and management web app that allows users to:
- Upload multiple *PDF, PPT, and JPG* files
- Convert them automatically into *Word (.docx)* format
- Combine all converted files into *one single Word document*
- Generate a *unique QR code* for each converted file *and* for the merged document — making sharing and downloads effortless.

---

## 🚀 Features

- 📁 *Upload Multiple Files:* Supports PDF, PowerPoint, and Image (JPG) formats.  
- 🔄 *Automatic Conversion:* Each file is converted to Word format using Python libraries.  
- 🔗 *Merge Functionality:* Combines all converted Word files into a single .docx.  
- 🔍 *QR Code Generation:* Creates individual QR codes for each file and one for the merged output.  
- 💾 *Download & Share:* Easily download your files or scan QR codes to access them instantly.  
- 🎨 *Interactive UI:* Clean, modern, and easy to use.

---

## 🧠 Tech Stack

### *Frontend*
- HTML5  
- CSS3 (with transitions and responsive design)  
- JavaScript (for asynchronous file uploads and dynamic QR display)

### *Backend*
- *Python (Flask Framework)*  
- *Libraries Used:*
  - flask → Handles routing, file uploads, and server-side rendering  
  - werkzeug → Secures filenames and manages uploads  
  - python-docx → Converts content into .docx files and merges them  
  - pdf2docx, pptx → For PDF/PPT conversions  
  - Pillow → Converts image (JPG/PNG) files to Word format  
  - qrcode → Generates QR codes for each file and merged document  
  - uuid, os, io → Handle unique file IDs and server storage

---

## ⚙ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/Wordify.git
cd Wordify
