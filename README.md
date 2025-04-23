# Simple Flask App

This is a simple web application built using Python and Flask.

---

## 📦 Features

- Built with Python & Flask
- Simple web interface using HTML
- Easy to run on EC2
- Great starting point for cloud deployment projects

---

## 🚀 Getting Started

### 📁 Clone the Repository

```bash

# Step 1: Make sure required packages are installed
sudo apt update
sudo apt install python3-venv python3-pip -y

# Step 2: Create a virtual environment
python3 -m venv flask-env

# Step 3: Activate the virtual environment
source flask-env/bin/activate

# Step 4: Install Flask inside the virtual environment
pip install flask

git clone https://github.com/your-username/Simple-app.git
cd Simple-app

#Run the application

python3 main.py

#Make sure port 5000 is open in the EC2 security group!


