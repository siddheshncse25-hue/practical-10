<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Embedded Content Demo</title>
    <style>
        body { font-family: sans-serif; padding: 20px; }
        .iframe-section { margin-bottom: 30px; }
        iframe { border: 2px solid #ccc; border-radius: 4px; }
    </style>
</head>
<body>

    <h1>iFrame Demonstration</h1>

    <!-- Example 1: Embedding an external webpage -->
    <div class="iframe-section">
        <h2>1. External Webpage (Wikipedia)</h2>
        <iframe src="https://en.wikipedia.org/wiki/HTML" 
                width="100%" height="400" 
                title="Wikipedia article about HTML">
        </iframe>
    </div>

    <!-- Example 2: Embedding an interactive map -->
    <div class="iframe-section">
        <h2>2. Embedded Google Map</h2>
        <iframe src="https://google.com" 
                width="600" height="450" 
                style="border:0;" allowfullscreen="" loading="lazy">
        </iframe>
    </div>

</body>
</html>
