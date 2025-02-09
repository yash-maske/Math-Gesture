# Math Gesture - README

## 📌 Project Overview
**Math Gesture** is a computer vision-based application that allows users to **draw mathematical problems using hand gestures** and get solutions via an AI model. It utilizes **OpenCV** for hand tracking, **cvzone** for gesture recognition, and integrates with Google's **Gemini AI** to interpret and solve the drawn equations.

## 🛠️ Features
- **Hand Gesture Recognition**: Uses OpenCV and cvzone to detect hand motions.
- **Virtual Drawing**: Users can draw mathematical equations in the air.
- **AI-Powered Solutions**: Sends the drawn problem to an AI model (Gemini) for solving.
- **Real-time Feedback**: Displays the problem and solution in a Streamlit web interface.

## 🔧 Installation & Setup
1. **Clone the Repository**  
   ```bash
   git clone https://github.com/yash-maske/Math-Gesture.git
   cd math-gesture
   ```

2. **Install Dependencies**  
   Ensure you have Python installed, then install required packages:
   ```bash
   pip install opencv-python cvzone numpy streamlit google-generativeai pillow
   ```

3. **Set Up Google Gemini API**  
   - Replace `api_key` in the code with your valid Google Gemini API key.

4. **Run the Application**  
   ```bash
   streamlit run math_gesture.py
   ```

## 🎮 How It Works
1. **Start the application**, and a webcam feed will open.
2. **Use hand gestures to draw**:
   - **Index finger up (✋)** → Draw lines.
   - **Thumb up (👍)** → Clear the canvas.
   - **Index, middle, and ring fingers up (🤟)** → Send the drawn problem to AI.
3. **AI processes the drawing** and returns the solution, which is displayed on the screen.

## 🖥️ Technologies Used
- **Python**
- **OpenCV** (for hand tracking)
- **cvzone** (simplified OpenCV functionalities)
- **NumPy** (for image processing)
- **Google Generative AI (Gemini)**
- **Streamlit** (for UI)

## 🚀 Future Enhancements
- Improve AI accuracy with better image processing.
- Support for more mathematical symbols.
- Multi-hand support for complex equations.

## 🤝 Contributing
Pull requests are welcome! Feel free to open issues for suggestions and improvements.


---

