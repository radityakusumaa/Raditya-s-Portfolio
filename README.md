# Raditya's Portfolio
  Personal portfolio website developed using HTML and Tailwind CSS framework to showcase projects and web development skills.


# Built With
   This project was built using these technologies. 
  * **HTML5** - Web content structure
  * **Tailwind CSS v4** - Responsive styling and design
  * **Git & GitHub** - Version control and hosting

# Folders Structure

```text
├── gambar/             # Image assets
├── src/
│   ├── input.css       # Main CSS file (Tailwind configuration & directives)
│   └── output.css      # Compiled CSS output called in HTML
├── index.html          # Portfolio page
├── package.json        # Dependensi proyek (Node.js & Tailwind CLI)
├── package-lock.json   # Dependency version lock
├── .gitignore          # List of files/folders ignored by Git
├── LICENSE             # License by Git
└── README.md           # Project documentation

```

# Installation and Setup Instructions

### 1. Clone Repository

Open a terminal in VS Code, then run the command:

```bash
git clone https://github.com/radityakusumaa/Raditya-s-Portfolio.git

```

Go to the newly cloned project folder:

```bash
cd Raditya-s-Portfolio

```

### 2. Install Dependencies

Make sure Node.js is installed on your computer, then run the command:

```bash
npm install

```

### 3. Run Tailwind CSS Watcher

To automatically compile CSS when there are changes to HTML or CSS files:

```bash
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch

```

### 4. Open in Browser

Open the `index.html` file directly in the browser or use the **Live Server** extension in VS Code.
