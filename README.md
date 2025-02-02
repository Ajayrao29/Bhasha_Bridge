**# Setup Guide for Bhasha Bridge Language Translator**

## **Overview**
Bhasha Bridge is a web-based application designed to facilitate language translation and communication across different languages. It leverages advanced Natural Language Processing (NLP) techniques to provide real-time translation services, making it easier for users to communicate in multilingual environments.

## **Features**
- 🌐 **Multi-Language Support**: Seamless text translation between multiple languages.
- 💬 **Real-Time Translation**: Instant translation of text input.
- 📜 **Text-to-Speech**: Converts translated text into speech.
- 📝 **History Log**: Keeps a record of previous translations.
- 🔍 **Language Detection**: Auto-detects the source language.
- 📱 **Responsive Design**: Optimized for both desktop and mobile devices.

## **Technologies Used**
- **Python**: Core programming language for backend development.
- **Flask**: Web framework for building the application.
- **Google Cloud Translation API**: Ensures accurate language translation.
- **gTTS (Google Text-to-Speech)**: Converts text to speech.
- **HTML/CSS/JavaScript**: Frontend technologies for UI development.
- **dotenv**: Manages environment variables securely.

---

## **Installation Steps**

### **Step 1: Clone the Repository**
Open your terminal (Command Prompt, PowerShell, or Terminal in VS Code) and clone the GitHub repository:
```bash
git clone <repository_url>
cd <repository_name>
```

### **Step 2: Open in VS Code**
Launch Visual Studio Code and open the cloned repository folder:
- **File > Open Folder...** and select the cloned folder.

### **Step 3: Create a Virtual Environment (.venu)**
Ensure Python (version <= 3.10) is installed on your system, then create a virtual environment:
```bash
python -m venv .venu
```

### **Step 4: Activate the Virtual Environment**
#### **For Windows PowerShell:**
```bash
.\.venu\Scripts\Activate.ps1
```
#### **For Windows Command Prompt:**
```bash
.\.venu\Scripts\activate.bat
```
#### **For macOS/Linux:**
```bash
source .venu/bin/activate
```

### **Step 5: Install Required Packages**
Install dependencies from the `requirements.txt` file:
```bash
pip install -r requirements.txt
```

### **Step 6: Install Any Additional Requirements**
If any additional packages are needed, install them manually:
```bash
pip install <package_name>
```

### **Step 7: Install and Place Additional Files**
Place required files in the correct directories as per the project’s structure.

#### **Example Folder Structure:**
```
CODE
│
├── .venu/                    # Virtual environment directory
├── indictrans2-en-indic-dist-200m/
│   ├── model.safetensors
│   └── pytorch_model.bin
├── indictrans2-indic-en-dist-200M/
│   └── pytorch_model.bin
├── indictrans2-indic-indic-dist-320M/
│   └── pytorch_model.bin
├── static/                   # Static files directory
│   ├── css/
│   ├── javascript/
│   └── data/
├── templates/                # HTML template files
├── app.py                    # Main application file
├── requirements.txt           # Requirements file
└── README.md                  # Project readme file
```

### **Step 8: Run the Application**
Start the Flask application by running:
```bash
python app.py
```
Upon running the command, the terminal will display the local server address (typically `http://127.0.0.1:5000`).

### **Step 9: Access the User Interface**
1. Open your web browser.
2. Navigate to:
```bash
http://127.0.0.1:5000
```
This will open the Bhasha Bridge language translator's web interface.

---

## **Future Enhancements**
- Support for **document translation** and **image-based text translation**.
- Improved **error handling** and **user feedback mechanisms**.
- Integration with additional translation services for **enhanced accuracy**.
- Enhanced UI/UX for better usability.

## **Contributing**
Contributions are welcome! To contribute:
1. **Fork** the repository.
2. **Make your changes**.
3. **Submit a pull request (PR)**.

---

Developed by Ajay Lingampalli and Team
