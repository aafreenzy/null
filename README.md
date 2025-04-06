/* General Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background-color: white;
    color: black;
    line-height: 1.6;
}

/* Navigation Bar */
header {
    background-color: red;
    padding: 10px 0;
}

nav ul {
    list-style: none;
    text-align: center;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 20px;
}

nav ul li a {
    text-decoration: none;
    color: white;
    font-size: 18px;
    font-weight: bold;
}

nav ul li a:hover,
nav ul li a.active {
    color: yellow;
}

/* Contact Section */
.contact-info {
    text-align: center;
    margin: 50px 20px;
}

.contact-info h1 {
    font-size: 32px;
    color: red;
    margin-bottom: 20px;
}

.contact-info p {
    font-size: 18px;
    margin-bottom: 10px;
}

.founders {
    margin-top: 30px;
}

.founders h2 {
    color: red;
    font-size: 24px;
    margin-bottom: 20px;
}

.founders p {
    font-size: 20px;
    margin-bottom: 10px;
}

/* Footer */
footer {
    text-align: center;
    padding: 20px;
    background-color: red;
    color: white;
    position: relative;
    width: 100%;
}

/* Responsive Design */
@media (max-width: 768px) {
    /* For tablet and mobile devices */
    nav ul li {
        display: block;
        margin: 10px 0;
    }

    nav ul li a {
        font-size: 16px;
    }

    .contact-info {
        margin: 30px 10px;
    }

    .contact-info h1 {
        font-size: 28px;
    }

    .contact-info p {
        font-size: 16px;
    }

    .founders h2 {
        font-size: 20px;
    }

    .founders p {
        font-size: 18px;
    }
}

@media (max-width: 480px) {
    /* For smaller mobile devices */
    nav ul li a {
        font-size: 14px;
    }

    .contact-info h1 {
        font-size: 24px;
    }

    .contact-info p {
        font-size: 14px;
    }

    .founders h2 {
        font-size: 18px;
    }

    .founders p {
        font-size: 16px;
    }

    footer {
        font-size: 14px;
        padding: 15px;
    }
}
