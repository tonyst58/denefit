
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Denefits | Flexible Payment Solutions</title>
  <meta name="description" content="Offer your clients easy payment plans with Denefits. No credit check, instant approval.">

  <!-- Tailwind CSS -->
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">

  <!-- Facebook Pixel -->
  <script>
    !function(f,b,e,v,n,t,s)
    {if(f.fbq)return;n=f.fbq=function(){n.callMethod?
    n.callMethod.apply(n,arguments):n.queue.push(arguments)};
    if(!f._fbq)f._fbq=n;n.push=n;n.loaded=!0;n.version='2.0';
    n.queue=[];t=b.createElement(e);t.async=!0;
    t.src=v;s=b.getElementsByTagName(e)[0];
    s.parentNode.insertBefore(t,s)}(window, document,'script',
    'https://connect.facebook.net/en_US/fbevents.js');
    fbq('init', '108498015837632');
    fbq('track', 'PageView');
  </script>
  <noscript><img height="1" width="1" style="display:none"
    src="https://www.facebook.com/tr?id=108498015837632&ev=PageView&noscript=1"/></noscript>

  <!-- LinkedIn Insight Tag -->
  <script type="text/javascript">
    _linkedin_partner_id = "7922762";
    window._linkedin_data_partner_ids = window._linkedin_data_partner_ids || [];
    window._linkedin_data_partner_ids.push(_linkedin_partner_id);
  </script>
  <script type="text/javascript">
    (function(l) {
      if (!l){window.lintrk = function(a,b){window.lintrk.q.push([a,b])};
      window.lintrk.q=[]}
      var s = document.getElementsByTagName("script")[0];
      var b = document.createElement("script");
      b.type = "text/javascript"; b.async = true;
      b.src = "https://snap.licdn.com/li.lms-analytics/insight.min.js";
      s.parentNode.insertBefore(b, s);
    })(window.lintrk);
  </script>
  <noscript>
    <img height="1" width="1" style="display:none" alt=""
      src="https://px.ads.linkedin.com/collect/?pid=7922762&fmt=gif" />
  </noscript>

  <script>
    // Pass UTM parameters dynamically to CTA buttons
    document.addEventListener("DOMContentLoaded", function() {
      const params = new URLSearchParams(window.location.search);
      const ctaButtons = document.querySelectorAll('.cta-btn');
      ctaButtons.forEach(btn => {
        if (params.toString()) btn.href += `&${params.toString()}`;
        btn.addEventListener('click', function() {
          fbq('track', 'Lead');
          if(typeof window.lintrk === 'function') {
            window.lintrk('track', { conversion_id: 7922762 });
          }
        });
      });
    });
  </script>
</head>
<body class="bg-gray-50 text-gray-900">

  <!-- Header with Denefits Logo -->
  <header class="bg-white py-6 shadow">
    <div class="max-w-5xl mx-auto text-center">
      <img src="https://business.denefits.com/logo.png" alt="Denefits Logo" class="mx-auto h-16">
    </div>
  </header>

  <!-- Hero Section -->
  <section class="bg-blue-50 py-16">
    <div class="max-w-4xl mx-auto text-center px-6">
      <h1 class="text-4xl md:text-5xl font-bold mb-4">Grow Your Business with Denefits</h1>
      <p class="text-lg md:text-xl mb-8">Offer instant, no-credit-check payment plans to your clients and boost your revenue instantly.</p>
      <a href="thank-you.html?utm_source=organic&utm_medium=cta&utm_campaign=denefits_landing" 
         class="cta-btn bg-blue-600 hover:bg-blue-700 text-white font-bold py-4 px-8 rounded-full shadow-lg text-lg transition">
         Get Started
      </a>
    </div>
  </section>

  <!-- Features Section -->
  <section class="py-16">
    <div class="max-w-5xl mx-auto px-6 grid md:grid-cols-3 gap-8 text-center">
      <div class="bg-white p-6 rounded-xl shadow hover:shadow-lg transition">
        <h3 class="text-xl font-bold mb-2">No Credit Checks</h3>
        <p>Approve more clients instantly without any credit barriers.</p>
      </div>
      <div class="bg-white p-6 rounded-xl shadow hover:shadow-lg transition">
        <h3 class="text-xl font-bold mb-2">Guaranteed Payments</h3>
        <p>Receive your payments every time, even if the client pays later.</p>
      </div>
      <div class="bg-white p-6 rounded-xl shadow hover:shadow-lg transition">
        <h3 class="text-xl font-bold mb-2">Increase Revenue</h3>
        <p>More approvals mean higher sales and happier clients.</p>
      </div>
    </div>
  </section>

  <!-- Social Proof Section -->
  <section class="bg-blue-50 py-16">
    <div class="max-w-4xl mx-auto px-6 text-center">
      <h2 class="text-3xl font-bold mb-6">Trusted by Thousands of Businesses</h2>
      <p class="mb-6">Join the growing community of businesses using Denefits to simplify payments and grow faster.</p>
      <a href="thank-you.html?utm_source=organic&utm_medium=cta&utm_campaign=denefits_landing" 
         class="cta-btn bg-green-600 hover:bg-green-700 text-white font-semibold py-4 px-8 rounded-full shadow-lg text-lg transition">
         Sign Up Now
      </a>
    </div>
  </section>

  <!-- Footer CTA -->
  <footer class="text-center py-12">
    <p class="mb-4 text-gray-600">Ready to offer better payment options?</p>
    <a href="thank-you.html?utm_source=organic&utm_medium=cta&utm_campaign=denefits_landing" 
       class="cta-btn bg-blue-600 hover:bg-blue-700 text-white font-bold py-4 px-10 rounded-full shadow-lg text-lg transition">
       Start Free Today
    </a>
    <p class="mt-6 text-gray-500 text-sm">© 2025 Denefits Affiliate Partner</p>
  </footer>

</body>
</html>
