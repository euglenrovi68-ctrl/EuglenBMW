body {
    font-family: Arial, sans-serif;
    margin: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #0b3c5d;
    color: white;
    text-align: center;
    padding: 20px;
}

.car {
    background: white;
    margin: 20px;
    padding: 15px;
    border-radius: 10px;
}

.car img {
    width: 100%;
    height: auto;  /* Foto përshtatet me gjerësinë */
    max-width: 500px;
    border-radius: 10px;
    display: block;
    margin: 0 auto;
}

footer {
    text-align: center;
    padding: 10px;
    background: #222;
    color: white;
}

/* Responsive për ekrane të vogla (iPhone, Android) */
@media screen and (max-width: 600px) {
    .car {
        margin: 10px;
        padding: 10px;
    }

    header h1 {
        font-size: 24px;
    }

    header p {
        font-size: 16px;
    }
}
