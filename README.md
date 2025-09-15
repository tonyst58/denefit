
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Thank You | Denefits</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <script>
    document.addEventListener("DOMContentLoaded", function() {
      // Facebook & LinkedIn conversion events
      fbq('track', 'Lead');
      if (typeof window.lintrk === 'function') {
        window.lintrk('track', { conversion_id: 7922762 });
      }

      // Capture UTM parameters for personalization
      const params = new URLSearchParams(window.location.search);
      const source = params.get('utm_source');
      const personalizedMsg = document.getElementById('personalized-msg');
      if (source && personalizedMsg) {
        let platform = '';
        if (source.toLowerCase() === 'facebook') platform = 'Facebook';
        else if (source.toLowerCase() === 'linkedin') platform = 'LinkedIn';
        else platform = 'our website';
        personalizedMsg.textContent = `Thanks for signing up from ${platform}!`;
      }
    });
  </script>
</head>
<body class="bg-gray-50 flex flex-col justify-center items-center h-screen text-center">
  <h1 class="text-4xl font-bold mb-4">Thank You!</h1>
  <p id="personalized-msg" class="text-lg mb-6">Your registration was successful.</p>
  <a href="https://business.denefits.com/register?partner=ANST447" 
     class="bg-blue-600 hover:bg-blue-700 text-white font-bold py-3 px-6 rounded-full shadow">
     Go to Denefits
  </a>
</body>
</html>
