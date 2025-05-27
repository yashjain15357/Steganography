# 🖼️ StegoWeb – Hide & Reveal Secret Messages in Images

**StegoWeb** is a simple yet powerful web-based application that uses **LSB (Least Significant Bit) steganography** to encode and decode hidden messages inside image files – all within your browser.

## 🔍 About the Project

This project demonstrates how secret messages can be securely embedded into images by modifying the least significant bits of pixel values – a technique commonly used in digital steganography.

- 🔐 **Message Encoding**: Hide a text message in a selected image file.
- 🧾 **Message Decoding**: Reveal the hidden message from an encoded image.
- 🧠 Fully client-side – no backend or data stored.
- 💻 Built using HTML, CSS, and JavaScript.

---

## 🚀 Features

- ✅ Encode any message with a custom 9-bit character map.
- ✅ Decode messages from previously encoded images.
- ✅ No visible change to the image – stealthy and secure.
- ✅ Easy-to-use, intuitive UI with creative styling.
- ✅ Works entirely in the browser – no file uploads.

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Image Processing**: LSB (Least Significant Bit) Manipulation via Canvas API
- **No frameworks**: Lightweight and fast

---

## 📷 How It Works

1. **Encoding:**
   - Choose an image.
   - Enter a message to encode.
   - Each character is converted to a 9-bit binary code.
   - Bits are embedded into the RGB values of the image pixels.
   - Download the encoded image.

2. **Decoding:**
   - Upload the encoded image.
   - The tool reads the LSBs of each pixel to reconstruct the binary message.
   - Message ends at a marker (`111111111`).

---

## 📁 Project Structure

