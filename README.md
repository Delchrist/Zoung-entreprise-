# Zoung-entreprise-
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}

.header-content {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header nav ul {
    list-style: none;
    padding: 0;
    display: flex;
}

header nav ul li {
    margin: 0 10px;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
}

.header-right a {
    margin: 0 10px;
    color: #fff;
    text-decoration: none;
}

.btn {
    background-color: yellow;
    color: #333;
    padding: 5px 10px;
    border: none;
    text-decoration: none;
    border-radius: 5px;
}

#hero {
    background: url('hero-background.jpg') no-repeat center center/cover;
    color: #fff;
    text-align: center;
    padding: 50px 20px;
}

#hero h2 {
    font-size: 2.5em;
    margin-bottom: 20px;
}

#hero form {
    display: flex;
    justify-content: center;
}

#hero input[type="text"] {
    padding: 10px;
    font-size: 1em;
    border: none;
    border-radius: 5px 0 0 5px;
    width: 300px;
}

#hero button {
    padding: 10px;
    font-size: 1em;
    border: none;
    background-color: yellow;
    color: #333;
    cursor: pointer;
    border-radius: 0 5px 5px 0;
}

#promotion {
    text-align: center;
    padding: 50px 20px;
    background-color: #f4f4f4;
}

.promo-item {
    display: inline-block;
    text-align: left;
    margin: 20px;
    padding: 20px;
    background-color: #fff;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.promo-item h3 {
    margin-top: 0;
}

.promo-item img {
    max-width: 100%;
    height: auto;
    border-radius: 5px;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}
