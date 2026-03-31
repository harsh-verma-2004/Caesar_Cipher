# 🚀 Caesar Cipher Tool

> Encrypt and decrypt text using a classic shift cipher with a clean interactive UI.


---

# 📌 Overview

This project is a simple web-based implementation of the Caesar Cipher, a classic encryption technique where each character in the text is shifted by a fixed number of positions.

I built this to strengthen my understanding of **basic cryptography concepts, string manipulation, and frontend interaction**. It provides an intuitive UI where users can input text, choose a shift key, and instantly encrypt or decrypt messages.

It’s ideal for beginners exploring **encryption basics and JavaScript-based UI logic**.

---

# 🎥 Demo / Screenshots

## 🔹 Main Interface

<img width="1556" height="883" alt="Screenshot 2025-08-18 095739" src="https://github.com/user-attachments/assets/4ae81900-12ed-4c8e-a2e7-4f11c5d6c0cc" />


## 🔹 Encryption Example

<img width="1134" height="882" alt="Screenshot 2025-08-18 095826" src="https://github.com/user-attachments/assets/abe42ab8-0384-4eb0-9da5-8a1a7483cfb3" />


## 🔹 Decryption Example

<img width="1065" height="882" alt="Screenshot 2025-08-18 095856" src="https://github.com/user-attachments/assets/d5d9e6a9-750d-48b2-995b-203b926e60ff" />


---

# ✨ Features

## Core Features

* Encrypt text using Caesar Cipher
* Decrypt encrypted text
* Adjustable shift key (1–25)
* Instant output display
* Copy-to-clipboard functionality

## Advanced Features

* Handles uppercase and lowercase characters
* Preserves non-alphabet characters (spaces, punctuation)
* Clean responsive UI
* Modular JavaScript logic

---

# 🏗 Architecture

```mermaid
graph TD

User --> UI
UI --> JS_Logic
JS_Logic --> Encrypt_Function
JS_Logic --> Decrypt_Function
Encrypt_Function --> Output
Decrypt_Function --> Output
```

---

# 🔄 System Workflow

```mermaid
flowchart TD

User_Input --> Enter_Text
Enter_Text --> Select_Key
Select_Key --> Choose_Action
Choose_Action --> Encrypt
Choose_Action --> Decrypt
Encrypt --> Display_Result
Decrypt --> Display_Result
Display_Result --> Copy_Option
```

---

# 🛠 Tech Stack

| Layer    | Technology                       |
| -------- | -------------------------------- |
| Frontend | HTML, CSS, JavaScript            |
| Logic    | JavaScript (String manipulation) |

---

# 📂 Project Structure

```
Caesar_Cipher/

├── index.html
├── style.css
├── script.js
├── docs/
│   └── screenshots/
└── README.md
```

---

# ⚙️ Installation

### 1 Clone the repository

```
git clone https://github.com/harsh-verma-2004/Caesar_Cipher.git
```

### 2 Navigate to project

```
cd Caesar_Cipher
```

### 3 Run the project

Just open the file:

```
index.html
```

---

# 📊 Performance Considerations

* Lightweight frontend application
* No backend dependency → instant response
* Efficient string manipulation logic
* Runs entirely in browser

---

# 🗺 Roadmap

* Add support for other ciphers (Vigenère, AES basics)
* Improve UI animations
* Add dark/light theme toggle
* Deploy as a web app

---

# 👨‍💻 Author

Harsh Verma
GitHub: [https://github.com/harsh-verma-2004](https://github.com/harsh-verma-2004)

---

# ⭐ Support

If you like this project, consider giving it a star ⭐
