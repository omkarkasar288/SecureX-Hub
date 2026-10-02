# SecureX Hub 🔐

SecureX Hub is a comprehensive, client-side cybersecurity toolkit developed as an internship project. It features a suite of cryptography, security, and utility tools built entirely in the browser using JavaScript. 

## 🚀 Key Features

*   **Password Utilities:** Includes a secure Password Generator and a Password Tester that provides real-time strength evaluation and improvement suggestions.
*   **Cryptography & Ciphers:** 
    *   **AES Encryption:** Securely encrypt and decrypt text using a secret key.
    *   **Classic Ciphers:** Tools for Caesar Cipher, Vigenère Cipher, and Vernam Cipher (One-Time Pad).
    *   **Digital Signature:** Simulates an ECDSA digital signature process (generate key pair, sign, and verify) using the Web Crypto API.
*   **Hashing & Steganography:**
    *   **SHA256 Hasher:** Generates instant cryptographic hashes for text.
    *   **Steganography:** Encodes and decodes hidden text messages within PNG images using Least Significant Bit (LSB) manipulation.
*   **Forensics & Utilities:**
    *   **IP Tracker:** Retrieves location details (city, region, country, ISP) for the user's current IP address.
    *   **Metadata Extractor:** Extracts EXIF data locally from uploaded images.
    *   **QR Generator:** Generates downloadable QR codes from text or URLs.
    *   **Brute Force Simulator:** A visual simulator demonstrating how a brute-force attack attempts to crack a target password.

## 💻 Tech Stack

*   **Frontend:** HTML5, Tailwind CSS (via CDN)
*   **Logic:** Vanilla JavaScript
*   **Libraries:** `crypto-js` for AES/SHA256, `qrcodejs` for QR generation, and `exif-js` for metadata extraction
*   **Font:** EB Garamond (Google Fonts)

## ⚙️ How to Run

Because this is a completely client-side application, no backend server or installation is required:
1. Clone the repository or download the source code.
2. Open `index.html` directly in any modern web browser.

## 👥 Project Credits

This project was created under the guidance of Tanmay Dikshit sir, Cyber Sanskar.

*   **Created by:** Omkar Kasar, Sankalp Kamble, and Vaibhav Jadhav
*   **Department:** Information Technology
*   **HOD:** M.S Karande
