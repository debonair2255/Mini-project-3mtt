* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: #333;
}

header {
    background: #150555;
    color: #fff;
    padding: 1rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    font-size: 1.5rem;
    font-weight: bold;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin-left: 2rem;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 1rem;
}

nav ul li a:hover {
    color: #ff4d4d;
}

.hero {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 2rem;
    background: #f4f4f4;
    min-height: 80vh;
}

.hero-content {
    max-width: 50%;
}

.hero-content h1 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
    color: #1a1a1a;
}

.hero-content p {
    font-size: 1.2rem;
    margin-bottom: 1.5rem;
}

.cta-button {
    display: inline-block;
    background: #ff4d4d;
    color: #fff;
    padding: 0.8rem 1.5rem;
    text-decoration: none;
    border-radius: 5px;
    font-size: 1rem;
}

.cta-button:hover {
    background: #e63939;
}

.hero-image img {
    max-width: 100%;
    height: auto;
    border-radius: 10px;
}

footer {
    background: #150555;
    color: #fff;
    text-align: center;
    padding: 1rem;
    position: relative;
    bottom: 0;
    width: 100%;
}

@media (max-width: 768px) {
    .hero {
        flex-direction: column;
        text-align: center;
        padding: 1rem;
    }

    .hero-content {
        max-width: 100%;
        margin-bottom: 1rem;
    }

    .hero-content h1 {
        font-size: 2rem;
    }

    .hero-content p {
        font-size: 1rem;
    }

    header {
        flex-direction: column;
    }

    nav ul {
        margin-top: 1rem;
    }

    nav ul li {
        margin: 0 1rem;
    }
}

