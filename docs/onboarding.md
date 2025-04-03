---
title: Bootcamp Introduction
---

**Bootcamp Introduction Document**

Welcome to the Backend Bootcamp! This document will guide you through setting up your development environment and familiarizing yourself with our workflow. By the end of this guide, you will be ready to start coding and submitting assignments.

---

## **1. Bootcamp Enrollment & Workflow**

Since this is a paid bootcamp, participants must enroll before proceeding. Follow these steps to complete your enrollment and get started:

1. **Enroll in the Bootcamp** by completing the payment process on our official platform (details will be provided by the instructor). (GitHub, VS Code, Linux, etc.).
    
2. **Receive access credentials** to join the GitHub courses after successful enrollment. to track your assignments.
    
3. **Work on assigned projects** following the given instructions.
    
4. **Submit your work** through GitHub for review.
    
5. **Receive feedback and improve** your code.
    
6. **Repeat** for each assignment and project.
    

---

## **2. Create a GitHub Account**

1. Visit [GitHub](https://github.com/) and click **Sign up**.
    
2. Enter your details (email, username, password) and verify your email.
    
3. Choose a free plan and complete the setup.
    
4. Configure Git on your system:
    
    ```sh
    git config --global user.name "Your Name"
    git config --global user.email "your-email@example.com"
    ```
    

---

## **3. Install VS Code**

VS Code is the recommended code editor for this bootcamp. Follow the steps based on your operating system:

### **Windows:**

1. Download VS Code from [here](https://code.visualstudio.com/).
    
2. Run the installer and follow the setup instructions.
    
3. Open VS Code and install useful extensions (e.g., GitHub, Python, ESLint).
    

### **Linux:**

1. Open the terminal and run:
    
    ```sh
    sudo apt update && sudo apt install code  # Debian-based (Ubuntu)
    sudo dnf install code  # Fedora
    ```
    
2. Launch VS Code from the applications menu.
    

### **Mac:**

1. Download VS Code from [here](https://code.visualstudio.com/).
    
2. Open the `.dmg` file and drag VS Code to the Applications folder.
    
3. Launch VS Code and install recommended extensions.
    

---

## **4. Install Linux (Dual Boot)**

If you want to dual boot Linux with Windows, follow these steps:

1. **Download a Linux ISO** (e.g., Ubuntu from [here](https://ubuntu.com/download)).
    
2. **Create a bootable USB drive** using [Rufus](https://rufus.ie/) (Windows) or `dd` (Linux/Mac).
    
3. **Backup your important data** to avoid data loss.
    
4. **Restart your system and boot from the USB drive** (access BIOS with `F2`, `F12`, or `DEL`).
    
5. **Follow the installation steps**, selecting "Install alongside Windows" if necessary.
    
6. **Complete the setup**, restart your system, and enjoy Linux!
    

---

## **5. Join GitHub Courses**

To track assignments and collaborate:

1. Log in to GitHub.
    
2. Visit the bootcamp's GitHub classroom link (provided by the instructor).
    
3. Accept the invitation and clone the repository to your local machine:
    
    ```sh
    git clone https://github.com/your-repository.git
    ```
    

---

## **6. Submit an Assignment**

After completing an assignment, follow these steps to submit it:

1. **Stage your changes:**
    
    ```sh
    git add -A
    ```
    
2. **Commit your changes with a meaningful message:**
    
    ```sh
    git commit -m "Completed assignment X"
    ```
    
3. **Push the changes to GitHub:**
    
    ```sh
    git push origin main
    ```
    
4. **Create a pull request** if required by the instructor.
    

---

Congratulations! You are now set up for the bootcamp. Happy coding!
