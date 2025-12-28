# Wedding-Invitation
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Our Wedding | City Theme</title>
    
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,700;1,400&family=Montserrat:wght@300;400&display=swap" rel="stylesheet">
    
    <script src="https://cdn.tailwindcss.com"></script>
    
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">

    <style>
        body { font-family: 'Montserrat', sans-serif; background-color: #0d1b2a; color: #e0e1dd; }
        .royal-font { font-family: 'Playfair Display', serif; }
        .gold-text { color: #c4a484; }
        .bg-navy { background-color: #0d1b2a; }
        .section-padding { padding: 80px 20px; }
        .divider { width: 60px; height: 2px; background: #c4a484; margin: 20px auto; }
    </style>
</head>
<body>

    <section class="min-h-screen flex flex-col items-center justify-center text-center p-6 bg-[url('https://images.unsplash.com/photo-1519225421980-715cb0215aed?ixlib=rb-1.2.1&auto=format&fit=crop&w=1950&q=80')] bg-cover bg-center bg-no-repeat bg-fixed relative">
        <div class="absolute inset-0 bg-black/50"></div> <div class="relative z-10" data-aos="fade-down" data-aos-duration="1500">
            <h4 class="uppercase tracking-widest text-sm mb-4">We are getting married</h4>
            <h1 class="royal-font text-6xl md:text-8xl gold-text italic">Aditi & Rahul</h1>
            <div class="divider"></div>
            <p class="text-xl uppercase tracking-widest">December 28, 2025</p>
        </div>
    </section>

    <section class="section-padding text-center max-w-2xl mx-auto">
        <div data-aos="fade-up">
            <h2 class="royal-font text-4xl gold-text mb-6">Our Story</h2>
            <p class="leading-relaxed text-lg">
                From coffee dates in the city to forever under the stars. 
                We invite you to celebrate the beginning of our new chapter.
            </p>
        </div>
    </section>

    <section class="section-padding bg-slate-900">
        <div class="max-w-4xl mx-auto grid md:grid-cols-2 gap-8">
            <div class="border border-yellow-900/30 p-8 text-center bg-navy rounded-lg" data-aos="zoom-in">
                <h3 class="royal-font text-2xl gold-text mb-2">The Wedding</h3>
                <p class="mb-4 uppercase text-xs tracking-widest">Sunday, 28th Dec</p>
                <p class="text-sm opacity-80 mb-6">The Grand Plaza, MG Road<br>Bangalore, KA</p>
                <a href="https://maps.google.com" target="_blank" class="border border-stone-500 px-6 py-2 text-xs uppercase hover:bg-stone-500 transition">View Map</a>
            </div>

            <div class="border border-yellow-900/30 p-8 text-center bg-navy rounded-lg" data-aos="zoom-in" data-aos-delay="200">
                <h3 class="royal-font text-2xl gold-text mb-2">The Reception</h3>
                <p class="mb-4 uppercase text-xs tracking-widest">Monday, 29th Dec</p>
                <p class="text-sm opacity-80 mb-6">Sky Lounge Ballroom<br>Indiranagar, Bangalore</p>
                <a href="https://maps.google.com" target="_blank" class="border border-stone-500 px-6 py-2 text-xs uppercase hover:bg-stone-500 transition">View Map</a>
            </div>
        </div>
    </section>

    <section class="section-padding text-center">
        <div data-aos="fade-up">
            <h2 class="royal-font text-4xl gold-text mb-4">RSVP</h2>
            <p class="mb-8">Kindly let us know if you can make it by Dec 1st.</p>
            <a href="https://wa.me/919999999999?text=Hi! We are coming to the wedding!" 
               class="bg-[#c4a484] text-black font-bold py-4 px-10 rounded-full hover:bg-opacity-80 transition uppercase text-sm tracking-widest">
                RSVP via WhatsApp
            </a>
        </div>
    </section>

    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script>
        // Initialize Animations
        AOS.init({
            duration: 1000,
            once: true
        });
    </script>
</body>
</html>
