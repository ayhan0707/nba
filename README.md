<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Video Sayfası</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="video-container">
        <!-- Video Listesi -->
        <div class="video-list">
            <div class="video-btn-container">
                <button class="video-btn" data-video="1">Video 1</button>
                <span class="video-number">Video 1</span>
            </div>
            <div class="video-btn-container">
                <button class="video-btn" data-video="2">Video 2</button>
                <span class="video-number">Video 2</span>
            </div>
            <div class="video-btn-container">
                <button class="video-btn" data-video="3">Video 3</button>
                <span class="video-number">Video 3</span>
            </div>
        </div>
        
        <!-- Video Ekranı -->
        <div class="video-display">
            <!-- YouTube iframe embedleri -->
            <iframe id="video-player" width="560" height="315" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
    </div>

    <script src="scripts.js"></script>
</body>
</html>
