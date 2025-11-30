<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>English Scroll</title>

<!-- Calligraphy Font -->
<link href="https://fonts.googleapis.com/css2?family=Great+Vibes&display=swap" rel="stylesheet">

<style>
    html, body {
        margin: 0;
        padding: 0;
        font-family: Georgia, serif;
        background-color: #f2e6c9;
        min-height: 100vh;
    }

    /* Full-page scroll background */
    body::before {
        content: "";
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background-image: url('https://www.pngall.com/wp-content/uploads/2016/07/Scroll-PNG-Clipart.png');
        background-repeat: repeat-y;
        background-position: left top, right top;
        background-size: 150px 100%;
        z-index: -1;
        opacity: 0.3; /* light scroll effect */
    }

    /* Main content container */
    .container {
        max-width: 1000px;
        margin: 0 auto;
        padding: 20px 40px;
        background: rgba(255, 248, 231, 0.95); /* semi-transparent parchment feel */
        box-shadow: 0px 4px 12px rgba(0,0,0,0.25);
        border-left: 4px solid #b58b4c;
        border-right: 4px solid #b58b4c;
    }

    /* Scroll banner */
    .scroll-banner {
        width: 100%;
        padding: 60px 20px;
        text-align: center;
        background-image: url('https://www.pngall.com/wp-content/uploads/2016/07/Scroll-PNG-Clipart.png');
        background-size: cover;
        background-position: center;
        border-top: 5px solid #8b5a2b;
        border-bottom: 5px solid #8b5a2b;
        margin-bottom: 30px;
    }

    .scroll-banner h1 {
        font-family: 'Great Vibes', cursive;
        font-size: 90px;
        color: #4b2e0f;
        text-shadow: 3px 3px 6px #e8d7b4;
        margin: 0;
        letter-spacing: 3px;
        line-height: 1.2;
        animation: shimmer 3s infinite alternate;
    }

    @keyframes shimmer {
        0% { color: #4b2e0f; text-shadow: 3px 3px 6px #e8d7b4; }
        50% { color: #5a3a12; text-shadow: 3px 3px 10px #f5e0b7; }
        100% { color: #4b2e0f; text-shadow: 3px 3px 6px #e8d7b4; }
    }

    h2 {
        text-align: center;
        color: #4b2e0f;
        font-size: 32px;
    }

    p {
        font-size: 18px;
        line-height: 1.7;
    }

    ul {
        font-size: 18px;
        line-height: 1.7;
        padding-left: 20px;
    }

    a {
        color: #7a4a1f;
        text-decoration: none;
        font-weight: bold;
    }

    a:hover {
        text-decoration: underline;
    }

    /* Responsive adjustments */
    @media (max-width: 768px) {
        .scroll-banner h1 {
            font-size: 60px;
        }
        .container {
            padding: 15px 20px;
        }
    }
</style>
</head>
<body>

<div class="container">
    <div class="scroll-banner">
        <h1>English Scroll</h1>
    </div>

    <h2>English Grammar for College Students</h2>

    <p>Welcome! This site provides clear explanations and helpful links to master English grammar at the college level.</p>

    <p>Use the links below to navigate the main topics:</p>

    <ul>
        <li><a href="parts-of-speech.md">Parts of Speech</a></li>
        <li><a href="sentence-structure.md">Sentence Structure</a></li>
        <li><a href="punctuation.md">Punctuation</a></li>
        <li><a href="academic-grammar.md">Academic Grammar</a></li>
        <li><a href="common-errors.md">Common Errors</a
