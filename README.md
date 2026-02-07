# PAF Lab 2

Welcome to the **PAF Lab 2** project repository. This project is part of the Programming Application Frameworks (PAF) course, focusing on web development fundamentals and HTML structure.

## 📋 Project Description

This is a simple web application project that demonstrates basic HTML structure and web page organization. The project includes a sample webpage with sections for introduction and objectives, showcasing fundamental web development concepts.

## 🚀 Features

- Clean and semantic HTML5 structure
- Responsive meta viewport configuration
- Organized content sections (Introduction, Objectives)
- Header and footer elements
- Basic CSS integration (external stylesheet)

## 📁 Project Structure

```
PAF_LAB2/
├── paf_lab2.html    # Main HTML page
├── styles.css       # CSS stylesheet (to be created)
└── README.md        # Project documentation (this file)
```

**Note**: The `styles.css` file is referenced in the HTML but not included in the repository. You'll need to create it to add custom styling to your page.

## 🛠️ Installation

No special installation is required for this project as it's a static HTML website. Simply clone the repository to your local machine:

```bash
git clone https://github.com/Dulara111/PAF_LAB2.git
cd PAF_LAB2
```

## 💻 Usage

### Option 1: Open Directly in Browser

1. Navigate to the project directory
2. Double-click on `paf_lab2.html` to open it in your default web browser

### Option 2: Using a Local Web Server

For a better development experience, you can use a local web server:

#### Using Python (Python 3)
```bash
python -m http.server 8000
```

#### Using Node.js (http-server)
```bash
# Install http-server globally (one-time setup)
npm install -g http-server

# Run the server
http-server
```

#### Using VS Code Live Server Extension
1. Install the "Live Server" extension in VS Code
2. Right-click on `paf_lab2.html`
3. Select "Open with Live Server"

Then open your browser and navigate to:
- Python: `http://localhost:8000/paf_lab2.html`
- http-server: `http://localhost:8080/paf_lab2.html`

## 📝 Setup Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Dulara111/PAF_LAB2.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd PAF_LAB2
   ```

3. **Open the HTML file**:
   - Open `paf_lab2.html` in your preferred web browser
   - Or use any of the local server methods mentioned above

## 📖 HTML Structure

The main HTML file (`paf_lab2.html`) contains:

- **Header**: Contains the main page title "Welcome to PAF Lab 2"
- **Main Section**: 
  - **Introduction**: Brief project introduction
  - **Objectives**: List of lab objectives
- **Footer**: Copyright information

## 🎨 Styling

The HTML file references an external stylesheet (`styles.css`). To add custom styling:

1. Create a `styles.css` file in the project root directory
2. Add your CSS rules to customize the appearance
3. The stylesheet is already linked in the HTML head section

Example `styles.css`:
```css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1rem;
}

main {
    max-width: 800px;
    margin: 2rem auto;
    padding: 0 1rem;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1rem;
    margin-top: 2rem;
}
```

## 🔧 Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Styling (external stylesheet)
- **Meta Viewport**: Responsive design configuration

## 📚 Learning Objectives

This lab project helps you understand:

1. Basic HTML5 document structure
2. Semantic HTML elements (header, main, section, footer)
3. External CSS stylesheet integration
4. Proper page metadata configuration
5. Content organization and hierarchy

## 🤝 Contributing

If you'd like to contribute to this project:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add some feature'`)
5. Push to the branch (`git push origin feature/improvement`)
6. Create a Pull Request

## 📄 License

This project is part of an academic lab exercise. Please check with your institution regarding usage and distribution rights.

## 👤 Author

**Dulara111**
- GitHub: [@Dulara111](https://github.com/Dulara111)

## 📞 Support

For questions or issues related to this lab project:
- Open an issue in the GitHub repository
- Contact your lab instructor or teaching assistant

---

**Note**: This is an educational project created for learning purposes as part of the PAF (Programming Application Frameworks) course.
