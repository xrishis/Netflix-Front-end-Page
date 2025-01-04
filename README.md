# Netflix Landing Page Clone

This project is a clone of the Netflix landing page, designed to replicate the look and feel of the original Netflix website. It includes a responsive design, interactive elements, and a modern user interface.

---

## **Project Overview**

### **Features**

- **Responsive Design**: The page is fully responsive and works seamlessly on various screen sizes, including mobile, tablet, and desktop.
- **Interactive FAQ Section**: A collapsible FAQ section that allows users to toggle answers to frequently asked questions.
- **Email Signup Form**: A functional email input field with a "Get Started" button.
- **Language Selector**: A dropdown to switch between English and Spanish.
- **Dynamic Navbar**: The navbar changes its background color on scroll for better visibility.
- **Plans Section**: Displays different subscription plans with links to sign up.
- **Footer Links**: Includes links to various Netflix-related pages and resources.

---

## **Technologies Used**

- **HTML5**: For structuring the content of the page.
- **CSS3**: For styling the page, including animations and responsive design.
- **JavaScript**: For adding interactivity, such as the FAQ accordion and navbar scroll effect.
- **Font Awesome**: For icons used in the project.

---

## **File Structure**

```
netflix-landing-page/
├── index.html          # Main HTML file
├── styles.css          # CSS file for styling
├── script.js           # JavaScript file for interactivity
└── README.md           # Project documentation
```

---

## **How to Run the Project**

1. Clone the repository to your local machine:```
   git clone https://github.com/xrishis/netflix-landing-page.git
   
   ```
2. Navigate to the project directory:```
   cd netflix-landing-page
   
   ```
3. Open the ```
   index.html
   ```

    file in your preferred web browser.

---

## **Key Code Snippets**

### **FAQ Accordion (JavaScript)**

```
document.querySelectorAll('.faq-question').forEach(button => {
    button.addEventListener('click', () => {
        const faqItem = button.parentElement;
        faqItem.classList.toggle('active');
    });
});
```

### **Navbar Scroll Effect (JavaScript)**

```
window.addEventListener('scroll', () => {
    const navbar = document.querySelector('.navbar');
    if (window.scrollY > 0) {
        navbar.style.backgroundColor = '#000';
    } else {
        navbar.style.backgroundColor = 'transparent';
    }
});
```

### **Responsive Design (CSS)**

```
@media (max-width: 768px) {
    .header {
        padding: 20px;
    }
    .hero h1 {
        font-size: 32px;
    }
    .email-signup {
        flex-direction: column;
    }
}
```

---

## **Contributing**

Contributions are welcome! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes.
4. Push your branch and submit a pull request.

---

## **License**

This project is licensed under the MIT License.

---

## **Acknowledgements**

- Inspired by the Netflix website.
- Icons provided by [Font Awesome](https://fontawesome.com/).

---

## **Contact**

For any questions or feedback, feel free to reach out:

- **Email**: [rishirajnachiketa@gmail.com]
- **GitHub**: [xrishis]

---

Enjoy exploring the Netflix Landing Page Clone! 🎥🍿
