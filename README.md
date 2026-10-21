# 🎯 Quiz App

A simple and interactive Quiz App built using HTML, CSS, Bootstrap 5, and JavaScript. Test your JavaScript knowledge with multiple-choice questions and a timer!

## 📸 Project Screenshot


<img width="1366" height="672" alt="Quiz App" src="https://github.com/user-attachments/assets/29aea698-ef20-47ae-94c1-6b4e3b7e9d65" />

## ✨ Features

- 📝 Multiple-choice JavaScript questions
- ⏱️ 30-second timer for each question
- 🎯 Four answer options for each question
- 📊 Automatic score calculation
- 🏆 Final quiz result screen
- ✏️ Review summary showing selected and correct answers
- 🎨 Attractive pink gradient background
- 📱 Responsive design
- ⚡ Automatic navigation after selecting an answer

## 🛠️ Technologies Used

- HTML5
- CSS3
- Bootstrap 5.3.8
- JavaScript

## 📂 Project Structure

```
Quiz-App/
├── index.html
├── style.css
├── script.js
├── Quiz App.png
└── README.md
```

## 🚀 How to Run the Project

1. Download or clone this repository.
2. Open the project folder in Visual Studio Code.
3. Make sure all project files are in the same folder.
4. Open `index.html` in your browser or use the Live Server extension.
5. Start playing the quiz!

**Note:** An internet connection is required to load Bootstrap from the CDN.

## 🎮 How to Play

1. Read the question displayed on the screen.
2. Select one of the four answer options.
3. The quiz automatically moves to the next question.
4. Answer before the 30-second timer expires.
5. View your final score and review your answers after completing the quiz.

## 💻 Quiz Question Format

Questions are stored in a JavaScript array using the following structure:

```javascript
{
  question: "Which keyword is used to declare a variable in JavaScript?",
  options: ["var", "int", "string", "float"],
  correctAnswerIndex: 0
}
```

The `correctAnswerIndex` starts from `0`, where `0` represents the first option.

## 🎨 Customization

- Add or modify questions in the `quizQuestions` array in `script.js`.
- Change colors, gradients, and layouts in `style.css`.
- Modify the page structure in `index.html`.

## 👩‍💻 Author

**Disha Mehta**

## 📄 License

This project was created for learning and practice purposes.
