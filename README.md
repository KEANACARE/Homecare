# Homecare
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Keana’s Home Care | Compassionate Support</title>
    <style>
        :root {
            --primary-blue: #2c3e50;
            --soft-gold: #d4af37;
            --white: #ffffff;
            --light-gray: #f4f4f4;
        }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            line-height: 1.6;
            color: #333;
        }
        header {
            background: var(--primary-blue);
            color: white;
            padding: 1rem 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        .hero {
            background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('https://images.unsplash.com/photo-1581578731522-5b17b9c6565c?auto=format&fit=crop&w=1350&q=80'); /* Placeholder image */
            background-size: cover;
            background-position: center;
            height: 80vh;
            color: white;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 0 20px;
        }
        .hero h1 { font-size: 3.5rem; margin-bottom: 10px; }
        .btn {
            background: var(--soft-gold);
            color: white;
            padding: 12px 30px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            margin-top: 20px;
        }
        .services { padding: 50px 5%; background: var(--white); }
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }
        .service-card {
            background: var(--light-gray);
            padding: 25px;
            border-radius: 10px;
            text-align: center;
            transition: transform 0.3s;
        }
        .service-card:hover { transform: translateY(-5px); }
        .contact-info {
            background: var(--primary-blue);
            color: white;
            padding: 50px 5%;
            text-align: center;
        }
        .contact-info a { color: var(--soft-gold); text-decoration: none; font-size: 1.2rem; }
        footer { text-align: center; padding: 20px; background: #222; color: #777; font-size: 0.9rem; }
    </style>
</head>
<body>

    <header>
        <div class="logo"><strong>KEANA’S HOME CARE</strong></div>
        <nav>
            <a href="mailto:khcservices1@gmail.com" style="color:white; text-decoration:none;">Contact Us</a>
        </nav>
    </header>

    <section class="hero">
        <h1>Care You Can Trust</h1>
        <p>Providing professional and compassionate home care for your loved ones.</p>
        <a href="https://wa.me/18768424587" class="btn">Message us on WhatsApp</a>
    </section>

    <section class="services">
        <h2 style="text-align:center;">Our Services</h2>
        <div class="services-grid">
            <div class="service-card">
                <h3>Personal Care</h3>
                <p>Assistance with daily living activities, hygiene, and grooming with dignity.</p>
            </div>
            <div class="service-card">
                <h3>Companionship</h3>
                <p>Friendly social interaction and emotional support for mental well-being.</p>
            </div>
            <div class="service-card">
                <h3>Specialized Support</h3>
                <p>Tailored care plans for seniors needing extra medical or physical attention.</p>
            </div>
        </div>
    </section>
<!-- Section 3: Animated Hero Slider -->
<div style="position: relative; width: 100%; height: 500px; overflow: hidden; background: #eee;">
  
  <div class="mySlides" style="display: block;">
    <img src="slide1.JPG" style="width:100%; height:500px; object-fit:cover;">
    <div style="position: absolute; top: 50%; width:100%; text-align:center; transform: translateY(-50%);">
      <h1 style="color: #2c3e50; margin: 0; background: rgba(255,255,255,0.7); display: inline-block; padding: 10px; border-radius: 5px;">Compassionate Care</h1>
      <p style="color: #6a11cb; font-weight: bold; background: rgba(255,255,255,0.7); display: block; width: fit-content; margin: 10px auto; padding: 5px; border-radius: 5px;">Professional Support at Home</p>
    </div>
  </div>

  <div class="mySlides" style="display: none;">
    <img src="slide2.JPG" style="width:100%; height:500px; object-fit:cover;">
    <div style="position: absolute; top: 50%; width:100%; text-align:center; transform: translateY(-50%);">
      <h1 style="color: #2c3e50; margin: 0; background: rgba(255,255,255,0.7); display: inline-block; padding: 10px; border-radius: 5px;">Your Health, Our Priority</h1>
      <p style="color: #2575fc; font-weight: bold; background: rgba(255,255,255,0.7); display: block; width: fit-content; margin: 10px auto; padding: 5px; border-radius: 5px;">Tailored to Your Needs</p>
    </div>
  </div>

  <div class="mySlides" style="display: none;">
    <img src="slide3.JPG" style="width:100%; height:500px; object-fit:cover;">
    <div style="position: absolute; top: 50%; width:100%; text-align:center; transform: translateY(-50%);">
      <h1 style="color: #2c3e50; margin: 0; background: rgba(255,255,255,0.7); display: inline-block; padding: 10px; border-radius: 5px;">Trusted Professionals</h1>
      <p style="color: #27ae60; font-weight: bold; background: rgba(255,255,255,0.7); display: block; width: fit-content; margin: 10px auto; padding: 5px; border-radius: 5px;">Expertise You Can Lean On</p>
    </div>
  </div>

  <div class="mySlides" style="display: none;">
    <img src="slide4.JPG" style="width:100%; height:500px; object-fit:cover;">
    <div style="position: absolute; top: 50%; width:100%; text-align:center; transform: translateY(-50%);">
      <h1 style="color: #2c3e50; margin: 0; background: rgba(255,255,255,0.7); display: inline-block; padding: 10px; border-radius: 5px;">Available 24/7</h1>
      <p style="color: #e67e22; font-weight: bold; background: rgba(255,255,255,0.7); display: block; width: fit-content; margin: 10px auto; padding: 5px; border-radius: 5px;">We Are Always Here for You</p>
    </div>
  </div>

</div>

<script>
let slideIndex = 0;
showSlides();
function showSlides() {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  }
  slideIndex++;
  if (slideIndex > slides.length) {slideIndex = 1}    
  slides[slideIndex-1].style.display = "block";  
  setTimeout(showSlides, 4000);
}
</script>
    <section class="contact-info">
        <h2>Get In Touch</h2>
        <p>We are here to answer your questions and provide the support you need.</p>
        <p><strong>WhatsApp:</strong> <a href="https://wa.me/18768424587">+1 (876) 842-4587</a></p>
        <p><strong>Email:</strong> <a href="mailto:khcservices1@gmail.com">khcservices1@gmail.com</a></p>
    </section>

    <footer>
        &copy; 2024 Keana’s Home Care Services. All rights reserved.
    </footer>

</body>
</html>
