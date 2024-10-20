body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: white;
    padding: 1rem 0;
    text-align: center;
}

nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

h1, h2 {
    color: #333;
}

section {
    padding: 2rem;
}

#inventory {
    background-color: #fff;
    padding: 2rem 0;
}

.car-list {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}

.car {
    background-color: #e3e3e3;
    padding: 1rem;
    margin: 1rem;
    text-align: center;
    border: 1px solid #ccc;
    width: 200px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    transition: transform 0.2s ease-in-out;
}

.car:hover {
    transform: translateY(-5px);
}

.car img {
    max-width: 100%;
    height: auto;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1rem 0;
    margin-top: 2rem;
}

@media (max-width: 768px) {
    .car-list {
        flex-direction: column;
        align-items: center;
    }

    .car {
        width: 80%;
        max-width: 300px;
    }
}
