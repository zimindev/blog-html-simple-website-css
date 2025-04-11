### **Simple HTML Website with CSS**

Hello, web developer! Let's enhance your HTML website with CSS to make it visually appealing. This is the perfect next step after learning basic HTML. 🎨

---

### 🔥 **Basic Website Structure with CSS**

**📌 1. File Structure**
```
my-website/
├── index.html
├── styles/
│   └── main.css
└── images/
```

**📌 2. HTML Template with CSS Link**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Styled Website</title>
    <link rel="stylesheet" href="styles/main.css">
</head>
<body>
    <header class="site-header">
        <h1>Welcome to My Website</h1>
    </header>
    
    <nav class="main-nav">
        <a href="index.html">Home</a>
        <a href="about.html">About</a>
        <a href="contact.html">Contact</a>
    </nav>
    
    <main class="content">
        <section class="intro">
            <h2>About This Site</h2>
            <p>This is my first styled website!</p>
        </section>
    </main>
    
    <footer class="site-footer">
        <p>© 2023 My Website</p>
    </footer>
</body>
</html>
```

---

### 🌟 **Basic CSS Styling (styles/main.css)**
```css
/* Global Styles */
body {
    font-family: 'Arial', sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    color: #333;
    background-color: #f4f4f4;
}

/* Header Styles */
.site-header {
    background: #35424a;
    color: #ffffff;
    padding: 20px 0;
    text-align: center;
}

.site-header h1 {
    margin: 0;
}

/* Navigation Styles */
.main-nav {
    background: #e8491d;
    padding: 10px;
    text-align: center;
}

.main-nav a {
    color: #ffffff;
    text-decoration: none;
    padding: 0 15px;
}

.main-nav a:hover {
    font-weight: bold;
}

/* Content Styles */
.content {
    width: 80%;
    margin: 20px auto;
    padding: 20px;
    background: #ffffff;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

/* Footer Styles */
.site-footer {
    background: #35424a;
    color: #ffffff;
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}
```

---

### 💡 **Key CSS Concepts Used**
1. **Selectors** - Targeting HTML elements (`.class`, `#id`, `element`)
2. **Box Model** - `margin`, `padding`, `border`
3. **Colors** - Hex codes, named colors
4. **Typography** - `font-family`, `line-height`
5. **Layout** - `width`, `margin: auto` for centering
6. **Pseudo-classes** - `:hover` for interactive elements

---

### 📚 **What to Add Next?**
1. **Responsive Design**
```css
@media (max-width: 768px) {
    .content {
        width: 95%;
    }
}
```

2. **CSS Variables**
```css
:root {
    --primary-color: #35424a;
    --secondary-color: #e8491d;
}
```

3. **Flexbox Layout**
```css
.main-nav {
    display: flex;
    justify-content: center;
    gap: 20px;
}
```

---

### 🚀 **Best Practices**
1. **Separation of Concerns** - Keep CSS in separate files
2. **Mobile-First** - Design for small screens first
3. **Consistent Naming** - Use BEM or other naming conventions
4. **Browser Prefixes** - Include vendor prefixes for better compatibility
5. **Minify CSS** - For production websites

---

Remember: HTML provides the structure, CSS brings it to life with style! Your website should now look much more professional and visually appealing. The next step would be to add interactivity with JavaScript.
