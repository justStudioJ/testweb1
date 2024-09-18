<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AI Image Generator Tool</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>AI Image Generator Tool JavaScript</h1>
        <p>Convert your text into an image within a second using this JavaScript-powered AI Image Generator tool.</p>
        <div class="input-container">
            <input type="text" placeholder="Describe what you want to see">
            <select>
                <option value="4">4 Images</option>
                <option value="2">2 Images</option>
                <option value="1">1 Image</option>
            </select>
            <button onclick="generateImages()">Generate</button>
        </div>
    </header>
    <main>
        <div class="gallery">
            <div class="image-container">
                <img src="img4.png" alt="Image 1">
            </div>
            <div class="image-container">
                <img src="img4.png" alt="Image 2">
            </div>
            <div class="image-container">
                <img src="img4.png" alt="Image 3">
            </div>
            <div class="image-container">
                <img src="img4.png" alt="Image 4">
            </div>
        </div>
    </main>
    <script src="script.js"></script>
</body>
</html>

