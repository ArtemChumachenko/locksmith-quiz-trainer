# Locksmith Quiz Trainer

Welcome to the **Locksmith Quiz Trainer** repository!

## Overview

**Locksmith Quiz Trainer** is a lightweight web app for practicing the theory behind working with locks. It is designed to help both new and experienced locksmiths deepen their knowledge and prepare for professional exams.

---

## Features

- Interactive quizzes to check your knowledge
- Simple, focused interface
- Easy to extend with new questions and modules
- Plain JavaScript with no external dependencies

## Stack

The project uses **JavaScript**, **HTML**, and **CSS** only.

---

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/ArtemChumachenko/locksmith-quiz-trainer.git
   ```

2. Open the project directory:

   ```bash
   cd locksmith-quiz-trainer
   ```

3. Open `index.html` in your browser, or serve the folder locally (for example with Python):

   ```bash
   python3 -m http.server 3000
   ```

   Then visit `http://localhost:3000`.

---

## Usage

- Open the app in your browser.
- Start the quiz, choose answers, and review your score.
- Update `quiz-data.js` to add or adjust questions.

---

## Deployment

- FTP deploy option: workflow `.github/workflows/ftp-deploy.yml` uses `samkirkland/ftp-deploy-action@v4.3.0`. Set secrets `FTP_HOST`, `FTP_USER`, `FTP_PASS` (and optionally `FTP_PORT`, `FTP_SERVER_DIR`), then push to `main` or run the workflow manually.

---

## Live Site

Live at: [quiz.keyrescuer.com](http://quiz.keyrescuer.com/)

---

## Contributing

Contributions are welcome! To propose a change:

1. Fork the repository.
2. Create a feature branch:

   ```bash
   git checkout -b feature/my-new-feature
   ```

3. Commit your changes:

   ```bash
   git commit -m "Add new feature"
   ```

4. Push the branch:

   ```bash
   git push origin feature/my-new-feature
   ```

5. Open a pull request.

---

## License

No license is defined yet. Feel free to add one if needed. 115
