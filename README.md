# My Music Blog

Welcome to my music blog! Here you can find various sections:

- [Home](Home/README.md)
- [Genres](Genres/README.md)
- [About](About/README.md)
- [Contact](Contact/README.md)

# Home
Welcome to the Home section of my music blog!
# Genres
Explore different music genres here!
# About
Learn more about the blog and the author.
# Contact
Get in touch with me through this section!

body {
    font-family: 'Georgia', serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #000;
    color: #fff;
    padding: 20px;
    text-align: center;
}

header h1 {
    font-size: 3em;
    font-weight: bold;
}

nav ul {
    list-style: none;
    padding: 0;
    display: flex;
    justify-content: center;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 1.2em;
}

main {
    padding: 40px;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

footer {
    background-color: #000;
    color: #fff;
    text-align: center;
    padding: 20px;
    position: fixed;
    bottom: 0;
    width: 100%;
}

/* Carousel Styles */
.carousel {
    width: 80%;
    margin: 20px auto;
    overflow: hidden;
    position: relative;
}

.carousel-inner {
    display: flex;
    transition: transform 0.5s ease;
}

.carousel-item {
    min-width: 100%;
    box-sizing: border-box;
}

.carousel-item img {
    width: 100%;
    height: auto;
}

.carousel-controls {
    position: absolute;
    top: 50%;
    width: 100%;
    display: flex;
    justify-content: space-between;
    transform: translateY(-50%);
}

.carousel-controls button {
    background-color: rgba(0, 0, 0, 0.5);
    border: none;
    color: #fff;
    padding: 10px;
    cursor: pointer;
}
