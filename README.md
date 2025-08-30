<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Telegram Mini App</title>

    <!-- Telegram SDK -->
    <script src="https://telegram.org/js/telegram-web-app.js?56"></script>

    <!-- Adexium Script -->
    <script type="text/javascript" src="https://cdn.tgads.space/assets/js/adexium-widget.min.js"></script>
    <script type="text/javascript">
        document.addEventListener('DOMContentLoaded', () => {
            const adexiumWidget = new AdexiumWidget({
                wid: 'f987f193-cc4d-4caf-ae20-8f3adab99a4a',
                adFormat: 'interstitial'
            });
            adexiumWidget.autoMode();
        });
    </script>

    <style>
        body { font-family: Arial; text-align: center; padding: 50px; }
    </style>
</head>
<body>
    <h2>Welcome to My Mini App</h2>
    <p>Ads will show automatically using Adexium.</p>
</body>
</html>
