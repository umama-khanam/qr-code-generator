# 📦 QR Code Generator (Node.js Project)

This is a **Node.js-based QR Code Generator** that takes any user input (like text or URLs) and generates a QR code image (PNG). The project showcases how backend Node.js applications can be created using npm packages, and how server-side scripting works in practice.

---

## 🧠 What I Learned

Through this project, I explored and understood:
- How to create and manage a Node.js project
- The role of `package.json` and `node_modules`
- How to install and use npm packages
- Creating `.gitignore` files to exclude folders like `node_modules`
- Working with the `fs` module to write files in Node.js
- Why Node.js projects are not deployed on GitHub Pages

---

## ⚙️ Tech Stack

| Tool        | Purpose                          |
|-------------|----------------------------------|
| Node.js     | Runtime environment              |
| JavaScript  | Programming language             |
| npm         | Package management               |
| `qrcode`    | NPM package to generate QR codes |
| `fs`        | Built-in module for file handling
| `inquirer`  | NPM package for asking questions  |
---

## 🚀 How to Run This Project

This project is a **Node.js-based QR Code Generator**, which works entirely in the backend. As this is not a frontend web project, it **cannot be deployed via GitHub Pages**, which only supports static frontend content. To view how this project works, follow the steps below to run it on your local machine:

### ✅ Prerequisites

- You must have **Node.js** installed on your system.
- A code editor like **Visual Studio Code (VS Code)** is recommended.

### 🛠️ Step-by-Step Guide

1. **Download or Clone the Repository**  
   Click on the green `Code` button at the top of this GitHub repository and download the ZIP file. Extract it to your local system.  
   _Alternatively, if you're comfortable with Git, you can clone it._

2. **Open the Project in VS Code**  
   Launch VS Code and open the folder where you saved this project.

3. **Install Required Packages**  
   Open the terminal inside VS Code. Run the following command to install all dependencies:  
   → `npm install`

4. **Run the Project**  
   After the packages are installed, in the terminal, run:  
   → `node index.js`

5. **Use the QR Code Generator**  
   You will be prompted in the terminal to enter a URL or text.  
   Once entered, the program will generate a file (e.g., `qrcode.png`) in your project folder.

6. **View the QR Code**  
   Open the generated `.png` file to view your QR code.

---

### 📌 Note

This is a **backend project**. You will not see any browser output or live demo link because this project runs entirely in the terminal and outputs a `.png` image as the result.

---




