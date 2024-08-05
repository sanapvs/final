**CSS stuff is metnioned below and in styles file**

body, h1, h2, p, a {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Montserrat', sans-serif;
    line-height: 1.6;
    background: radial-gradient(circle, rgba(0, 0, 255, 0) 0%, rgba(0, 0, 255, 1) 100%);
    color: #333;
    padding: 0;
    margin: 0;
    background-image: url('logo.png');
    background-size: cover; 
    background-repeat: no-repeat;
    background-attachment: fixed; 
}

header {
    background-image: url('logo.png');
    background-size: cover; 
    background-repeat: no-repeat;
    background-attachment: fixed; 
    color: #fff;
    padding: 20px 0;
    text-align: center;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}

header h1 {
    margin: 0;
    font-size: 2.75rem;
    font-weight: 700;
    text-transform: uppercase;
    letter-spacing: 2px;
}


main {
    max-width: 900px;
    margin: 20px auto;
    padding: 30px;
    background: linear-gradient(to right, #64b3f4, #64b3f4);
    border-radius: 12px;
    box-shadow: 0 6px 16px rgba(0, 0, 0, 0.3);
}

section {
    margin-bottom: 20px;
}

section h2 {
    background: #2a7f9b;
    color: #fff;
    padding: 15px;
    border-radius: 8px;
    font-size: 1.75rem;
    font-weight: 600;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}

section p {
    margin: 10px 0;
    font-size: 1.125rem;
    line-height: 1.8;
}

a {
    color: #000000;
    text-decoration: underline;
    font-weight: 500;
    transition: color 0.3s, text-decoration 0.3s;
}

a:hover {
    color: #b30000;
    text-decoration: underline;
}
