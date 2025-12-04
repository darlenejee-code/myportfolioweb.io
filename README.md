# 🌐 Personal Portfolio Website

### **SANDIG, DARLENE JEE A. — Full Stack Developer**

This project is a modern, responsive, and interactive **personal portfolio website** built using **HTML**, **TailwindCSS**, and **vanilla JavaScript**. It showcases skills, projects, experience, and contact information in an elegant UI with animations, gradients, and smooth scrolling.

---

## 🚀 Features

### **✨ Modern UI & Styling**

* Built with **Tailwind CSS** for fast and consistent styling
* Custom gradients and typography
* Hover effects, shadows, and card animations
* Fully responsive across devices

### **🧭 Smooth UX**

* Smooth scrolling navigation
* Sticky navigation bar
* Mobile menu (placeholder alert for demo)

### **🎬 Animations**

* Typing animation in the hero section
* Scroll-activated fade-in elements
* Hover animation for cards

### **📁 Organized Sections**

* **Home / Hero** – Name, developer title, intro, action buttons
* **About** – Personal journey, experience timeline
* **Projects** – 3 featured project cards with descriptions
* **Skills** – Frontend, backend, database, DevOps categories
* **Contact** – Email, GitHub, LinkedIn, message form

### **📨 Contact Form (Demo)**

* Prevents actual submission
* Shows a friendly alert instead

---

## 🛠️ Technologies Used

| Category        | Technologies                 |
| --------------- | ---------------------------- |
| **Frontend**    | HTML5, TailwindCSS           |
| **Animations**  | CSS keyframes, JavaScript    |
| **Icons/Emoji** | Unicode Emojis (lightweight) |
| **Fonts**       | Google Fonts – Inter         |
| **Scripts**     | Vanilla JS                   |

---

## 📂 File Structure

```
project-folder/
│── index.html
│── README.md
└── (contains all HTML, styles, and JS in one file)
```

---

## 🔧 How It Works

### 1. **Animations**

* `.code-animation` handles the typing effect
* `.fade-in` elements become visible when scrolled into view
* Cards use CSS hover transforms

### 2. **Navigation**

* Clicking menu items scrolls to the corresponding section
* Mobile toggle is a placeholder alert (can be expanded into a real sidebar menu)

### 3. **Form Submission**

```js
function handleSubmit(event) {
    event.preventDefault();
    alert('Thank you for your message! This is a demo form.');
}
```

---

## 📌 Future Improvements (Optional)

These can be added later:

* Replace alert with a real backend (PHP, Node.js, Firebase, etc.)
* Add a real mobile navigation drawer
* Add dark mode toggle
* Add project links (GitHub repos / Live demos)
* Modularize CSS and JS into separate files

---

## 🧑‍💻 Author

**SANDIG, DARLENE JEE A.**
*Full Stack Developer & Problem Solver*

 https://darlenejee-code.github.io/myportfolioweb.io/
