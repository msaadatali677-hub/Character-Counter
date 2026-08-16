# 🔤 Character Counter

A modern, responsive, and lightweight **Character Counter** web application built with **HTML, CSS, and JavaScript**.

It provides real-time text analysis, allowing users to instantly count **characters, characters without spaces, words, sentences, lines, and estimated reading time**.

## 🚀 Live Demo

👉 **[View Live Demo](https://character-counter-umber-mu.vercel.app/)**

> Replace `YOUR-LIVE-DEMO-LINK` with your actual GitHub Pages or Vercel URL.

## ✨ Features

* 🔤 Real-time character counter
* 🚫 Character count without spaces
* 📝 Real-time word counter
* 📄 Sentence counter
* 📑 Line counter
* ⏱️ Estimated reading time
* 📋 Copy text to clipboard
* 🗑️ Clear text button
* 📊 280-character reference progress bar
* 📱 Fully responsive design
* 🌙 Modern dark UI
* 💎 Glassmorphism-style cards
* ⚡ Fast and lightweight
* 🎨 Blue & cyan gradient design
* ♿ Reduced-motion support

## 🛠️ Technologies Used

* **HTML5** – Structure and semantic markup
* **CSS3** – Styling, animations, responsive design, and glassmorphism
* **JavaScript** – Text analysis, DOM manipulation, events, and clipboard functionality

## 📊 Text Statistics

The application analyzes the following:

| Statistic     | Description                                                 |
| ------------- | ----------------------------------------------------------- |
| 🔤 Characters | Total number of characters including spaces and line breaks |
| 🚫 No Spaces  | Characters excluding spaces, tabs, and line breaks          |
| 📝 Words      | Total number of words                                       |
| 📄 Sentences  | Approximate number of sentences                             |
| 📑 Lines      | Number of text lines                                        |
| ⏱️ Read Time  | Estimated reading time based on 200 words per minute        |

## 📈 280-Character Reference

The project includes a visual **Length Pulse** progress bar that compares the entered text against a **280-character reference length**.

The progress is updated automatically as the user types.

## 🎯 How It Works

The application listens for the `input` event on the text area. Every time the user types, pastes, or deletes text, JavaScript recalculates all statistics and updates the interface in real time.

The project uses:

* `.length` to calculate total characters
* Regular expressions to remove whitespace
* Regular expressions to detect sentences
* `split()` to calculate lines
* Word count to estimate reading time
* Clipboard API for copying text

## 📋 Copy & Clear

### Copy

The **Copy** button copies the current text to the clipboard and displays a confirmation message.

### Clear

The **Clear** button removes all text and resets the statistics back to zero.

## 📂 Project Structure

```text
Character-Counter/
│
├── index.html
└── README.md
```

> The current project contains the HTML, CSS, and JavaScript implementation inside `index.html`.

## 💻 How to Run Locally

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/Character-Counter.git
```

### 2. Open the Project

```bash
cd Character-Counter
```

### 3. Run the Website

Open `index.html` in your preferred web browser.

No installation or additional dependencies are required. 🎉


## 📚 What I Learned

While building this project, I practiced:

* HTML5 structure
* CSS3 responsive design
* CSS variables
* CSS gradients
* Glassmorphism UI
* JavaScript DOM manipulation
* Event listeners
* Regular expressions
* Clipboard API
* Real-time UI updates
* Responsive web design
* Accessibility basics

## 🔮 Future Improvements

* [ ] Character limit option
* [ ] Custom character limit
* [ ] Remaining character counter
* [ ] Dark/Light mode toggle
* [ ] Download text as `.txt`
* [ ] Export text statistics
* [ ] Reading time customization
* [ ] Multiple language support

## 👨‍💻 Author

**Saadat Ali**

Frontend Developer | Programmer | Web Development & Software Engineering

### Connect With Me

* 💼 **LinkedIn:** [Saadat Ali](https://www.linkedin.com/in/saadat-ali-3021ab3a5/)
* 🐙 **GitHub:** [msaadatali677-hub](https://github.com/msaadatali677-hub)

## ⭐ Support

If you like this project, please consider giving the repository a ⭐ on GitHub.

It motivates me to build and share more web development projects! 🚀

---

### 📌 Keywords

`Character Counter` `Text Counter` `Word Counter` `Sentence Counter` `JavaScript` `HTML` `CSS` `JavaScript Project` `Frontend Project` `Web Development` `Beginner JavaScript Project`
