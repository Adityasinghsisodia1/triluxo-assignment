README.md for Triluxo Chatbot Assignment
markdown
Copy code
# Triluxo Chatbot Assignment  

This repository contains the **custom chatbot** project built using **Langchain** and **Flask**. The chatbot extracts data, creates embeddings, and offers an API for seamless interaction.

---

## 📑 **Features**  
- Extracts data from [Brainlox Courses](https://brainlox.com/courses/category/technical) using **Langchain URL loaders**.  
- Generates **embeddings** and stores them in a **vector store**.  
- Provides a **Flask RESTful API** to handle user conversations.  
- Includes a multi-page web interface with:
  - **Home Page**  
  - **About Page**  
  - **Services Page**  
  - **Contact Page**  

---

## 🚀 **How to Run the Project**  

### Step 1: Clone the Repository  
```bash
git clone <your-repo-url>
cd triluxo-assignment
Step 2: Install Dependencies
Make sure you have Python installed. Use the following command to install all required packages:

bash
Copy code
pip install -r requirements.txt
Step 3: Run the Flask App
bash
Copy code
py app/app.py
Step 4: Access the App
Open your browser and go to:
http://127.0.0.1:5000

📂 Project Structure
bash
Copy code
triluxo-assignment/
│
├── app/
│   ├── app.py               # Main Flask app
│   ├── templates/           # HTML templates
│       ├── index.html       # Home page
│       ├── about.html       # About page
│       ├── services.html    # Services page
│       └── contact.html     # Contact page
├── requirements.txt         # List of dependencies
└── README.md                # Project documentation
🔧 Technologies Used
Python
Flask
Langchain
HTML & CSS
💡 How It Works
Data Extraction: The chatbot loads course data from Brainlox using Langchain's URL loader.
Embeddings Creation: It processes the data into embeddings and stores them in a vector store for fast retrieval.
REST API: The Flask API provides an interface for chatbot conversations.
📜 License
This project is licensed under the MIT License.

👤 Contact
For any questions or suggestions, feel free to reach out:

Aditya
GitHub: YourUsername