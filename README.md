# Caesar_Cipher
A sleek, modern web application for encrypting and decrypting messages using the classic Caesar Cipher algorithm. This project is a simple yet educational tool for understanding one of the oldest and most basic forms of cryptography.

✨ Features:

1. Encrypt Text: Secure your messages by shifting each letter forward by a specified key.

2. Decrypt Text: Easily decode encrypted messages with the correct shift key.

3. Intuitive Interface: A clean and stylish user interface, built with HTML, Tailwind CSS, and plain JavaScript, makes it easy to use for anyone.

4. Dynamic and Responsive: The application is fully responsive and looks great on both desktop and mobile devices.

5. Copy to Clipboard: One-click functionality to copy the resulting text for easy sharing.

🚀 How to Use:

1. Simply open the index.html file in your web browser to start using the application. No installation or setup is required!

2. Enter your message into the "Your Message" text area.

3. Choose a shift key (a number between 1 and 25). The default is 3, which is the traditional Caesar cipher key.

4. Click the Encrypt button to encode your message or the Decrypt button to decode an encrypted one.

5. The result will appear in the "Result" text area.

6. Click the Copy button to copy the encrypted or decrypted text to your clipboard.

💻 Technologies Used:

1. HTML5: For the core structure of the web page.

2. CSS3: Custom styles and a beautiful gradient background.

3. Tailwind CSS: A utility-first CSS framework for fast and responsive styling.

4. JavaScript (ES6+): Powers the encryption, decryption, and all interactive features.

5. Google Fonts (Poppins): For a modern and readable typography.

🧠 How the Cipher Works:

The Caesar cipher is a type of substitution cipher where each letter in the plaintext is replaced by a letter some fixed number of positions down the alphabet. For example, with a left shift of 3, D would be replaced by A, E would become B, and so on.

The formula for encryption is:
E 
n
​
 (x)=(x+n)(mod26)

And for decryption:
D 
n
​
 (x)=(x−n)(mod26)

where x is the position of the letter in the alphabet (e.g., A=0, B=1, ...), and n is the shift key.

<img width="1556" height="883" alt="Screenshot 2025-08-18 095739" src="https://github.com/user-attachments/assets/aa46673e-f848-4b53-9ab1-2910b0552c76" />


<img width="1134" height="882" alt="Screenshot 2025-08-18 095826" src="https://github.com/user-attachments/assets/4b57376c-cc08-41a9-b77e-53f2a438469c" />


<img width="1065" height="882" alt="Screenshot 2025-08-18 095856" src="https://github.com/user-attachments/assets/0758fcc4-fd9b-4566-aa66-73b7c8121e44" />


