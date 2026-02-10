<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rahul Technical Solution | Mobile & Software Expert</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        :root { --primary: #0d47a1; --whatsapp: #25d366; --dark: #002171; }
        body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; margin: 0; background: #f0f2f5; color: #333; scroll-behavior: smooth; }
        
        /* Header Section */
        header { background: linear-gradient(rgba(13, 71, 161, 0.9), rgba(0, 33, 113, 0.9)), url('https://images.unsplash.com/photo-1512428559087-560fa5ceab42?auto=format&fit=crop&w=1000&q=80'); background-size: cover; color: white; padding: 80px 20px; text-align: center; }
        
        nav { background: var(--dark); padding: 15px; position: sticky; top: 0; z-index: 1000; display: flex; justify-content: center; gap: 20px; flex-wrap: wrap; }
        nav a { color: white; text-decoration: none; font-weight: bold; font-size: 1rem; transition: 0.3s; }
        nav a:hover { color: #ffab00; }

        /* Buttons */
        .btn-wa { background: var(--whatsapp); color: white; padding: 12px 25px; border-radius: 30px; text-decoration: none; font-weight: bold; display: inline-flex; align-items: center; gap: 10px; margin: 10px; box-shadow: 0 4px 10px rgba(0,0,0,0.2); transition: 0.3s; }
        .btn-wa:hover { transform: scale(1.05); background: #1ebe57; }

        /* Services Grid */
        .section { padding: 60px 20px; max-width: 1200px; margin: auto; }
        .section-title { text-align: center; font-size: 2rem; color: var(--primary); margin-bottom: 40px; }
        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 20px; }
        .card { background: white; padding: 30px; border-radius: 15px; text-align: center; box-shadow: 0 4px 20px rgba(0,0,0,0.08); border-top: 5px solid var(--primary); }
        .card i { font-size: 3rem; color: var(--primary); margin-bottom: 15px; }

        /* Contact Details */
        .contact-info { background: white; padding: 30px; border-radius: 15px; margin-top: 30px; text-align: center; }
        
        footer { background: var(--dark); color: white; text-align: center; padding: 30px; margin-top: 40px; }
        
        /* Floating WA Button for Mobile */
        .floating-wa { position: fixed; bottom: 20px; right: 20px; background: var(--whatsapp); color: white; width: 60px; height: 60px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-size: 30px; box-shadow: 2px 2px 10px rgba(0,0,0,0.3); z-index: 1001; }
    </style>
</head>
<body>

<nav>
    <a href="#"><i class="fas fa-home"></i> Home</a>
    <a href="#services">Services</a>
    <a href="#youtube">My Videos</a>
    <a href="#contact">Contact</a>
</nav>

<header>
    <h1>Rahul Technical Solution</h1>
    <p style="font-size: 1.2rem;">Expert Mobile Repairing & Advanced Software Solutions</p>
    <div style="margin-top: 25px;">
        <a href="https://wa.me/919126847309" class="btn-wa"><i class="fab fa-whatsapp"></i> Chat on 91268...</a>
        <a href="https://wa.me/919085823754" class="btn-wa"><i class="fab fa-whatsapp"></i> Chat on 90858...</a>
    </div>
</header>

<section id="services" class="section">
    <h2 class="section-title">Humari Special Services</h2>
    <div class="grid">
        <div class="card">
            <i class="fas fa-mobile-alt"></i>
            <h3>Mobile Repairing</h3>
            <p>Display change, Charging port, aur Motherboard repair expert solutions.</p>
        </div>
        <div class="card">
            <i class="fas fa-unlock-alt"></i>
            <h3>Software & Unlocking</h3>
            <p>MI Account, Google Bypass (FRP), Flashing aur OS Updates turant karein.</p>
        </div>
        <div class="card">
            <i class="fas fa-desktop"></i>
            <h3>Remote Support</h3>
            <p>Duniya mein kahin bhi hon, hum TeamViewer/AnyDesk se software theek karte hain.</p>
        </div>
    </div>
</section>

<section id="youtube" class="section" style="background: #fff; border-radius: 20px;">
    <h2 class="section-title">YouTube Channel Tutorials</h2>
    <p style="text-align:center;">Nayi tips aur tricks ke liye humara channel dekhein.</p>
    <div style="text-align:center; padding: 20px;">
        <a href="#" class="btn-wa" style="background: #ff0000;"><i class="fab fa-youtube"></i> Subscribe Rahul Technical</a>
    </div>
</section>

<section id="contact" class="section">
    <h2 class="section-title">Humse Sampark Karein</h2>
    <div class="contact-info">
        <p><strong><i class="fas fa-phone"></i> Call/WhatsApp:</strong> 9126847309 / 9085823754</p>
        <p><strong><i class="fas fa-envelope"></i> Email:</strong> rahul.tech.sol@gmail.com</p>
        <p><strong><i class="fas fa-map-marker-alt"></i> Location:</strong> India (Global Remote Service)</p>
    </div>
</section>

<footer>
    <p>&copy; 2026 Rahul Technical Solution | All Rights Reserved.</p>
</footer>

<a href="https://wa.me/919126847309" class="floating-wa" target="_blank">
    <i class="fab fa-whatsapp"></i>
</a>

</body>
</html>
