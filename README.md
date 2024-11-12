# 🧮 AI Calculator

## 📝 Overview
The **AI Calculator** is an innovative project that utilizes OpenCV and Google’s Gemini AI to solve mathematical problems. Users can draw mathematical expressions directly on the screen, and the AI model will interpret the input to provide accurate and detailed solutions. This project uses advanced AI and computer vision technologies to enhance user interaction and calculation accuracy.

## ✨ Features
- **Draw Math Problems** ✍️: Draw mathematical expressions directly on the screen.
- **Move Pointer** 🖱️: Use two fingers to move the pointer around the screen.
- **Reset Canvas** 🗑️: Lift the thumb to erase the current drawing.
- **Send to AI Model** 📤: Send the drawing to the AI model by lifting the little finger.
- **Detailed Solutions** 📊: The AI model interprets the drawing and provides a step-by-step solution.

## 📋 Requirements
- **Python** 🐍
- **OpenCV** 👁️
- **Numpy** ➗
- **Pillow** 🖼️
- **Google Generative AI** 🤖
- **CVZone** 🛠️
- **Django** 🌐

## 🚀 Installation

1. **Obtain the Gemini API Key**:
   - Visit [Google AI Studio](https://aistudio.google.com) to obtain your Gemini API key.

2. **Install Required Packages**:
   - Run the following command to install all dependencies listed in `requirements.txt`:
     ```bash
     pip install -r requirements.txt
     ```

3. **Configure the API Key**:
   - Create a `.env` file and add your API key in the file.

5. **Run the Application**:
   - Start the Django web server:
     ```bash
     python manage.py runserver
     ```

6. **Access the Application**:
   - Open a web browser and navigate to [http://127.0.0.1:8000](http://127.0.0.1:8000) to access and use the calculator.

## 🎨 Interaction Guide

Follow these gestures to interact with the AI-powered calculator:
- **Reset Canvas** 🗑️: Lift your thumb to reset or erase the canvas.
- **Draw Math Problems** ✍️: Use one finger to draw a math problem on the screen.
- **Move Pointer** 🖱️: Lift two fingers to move the pointer around the screen.
- **Send to AI Model** 📤: Lift your little finger to send the drawing to the AI model.

The AI model will interpret the input and display a detailed solution.

## 🤝 Contribution

I welcome contributions to improve this project. Feel free to open issues or submit pull requests. Your suggestions and feedback are always appreciated!

## 📜 License

This project is licensed under the MIT License. See the LICENSE file for more information.
