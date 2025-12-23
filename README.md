# sabeena-law-firm
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sabeena Law Firm</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Lato:wght@300;400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        :root {
            --beige: #f5f5dc;
            --cream: #fffdd0;
            --soft-gold: #d4af37;
            --dark-brown: #3e2723;
        }
        body {
            font-family: 'Lato', sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--cream);
            color: var(--dark-brown);
            line-height: 1.6;
        }
        h1, h2, h3 {
            font-family: 'Playfair Display', serif;
        }
        header {
            background-color: var(--beige);
            padding: 20px;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        nav ul {
            list-style: none;
            padding: 0;
            margin: 20px 0 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav a {
            text-decoration: none;
            color: var(--dark-brown);
            font-weight: 700;
            transition: color 0.3s;
        }
        nav a:hover {
            color: var(--soft-gold);
        }
        section {
            padding: 60px 20px;
            max-width: 1200px;
            margin: 0 auto;
        }
        #home {
            text-align: center;
            background-color: var(--cream);
        }
        #home h1 {
            font-size: 3em;
            margin-bottom: 20px;
            color: var(--dark-brown);
        }
        #home p {
            font-size: 1.2em;
            margin-bottom: 30px;
        }
        .cta-button {
            background-color: var(--soft-gold);
            color: var(--dark-brown);
            padding: 15px 30px;
            text-decoration: none;
            font-weight: 700;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        .cta-button:hover {
            background-color: var(--dark-brown);
            color: var(--cream);
        }
        #about {
            background-color: var(--beige);
        }
        #about .content {
            display: flex;
            align-items: center;
            gap: 40px;
        }
        #about img {
            width: 300px;
            height: auto;
            border-radius: 10px;
        }
        #practice-areas {
            background-color: var(--cream);
        }
        .cards {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .card {
            background-color: var(--beige);
            padding: 20px;
            border-radius: 10px;
            text-align: center;
            width: 250px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .card i {
            font-size: 2em;
            color: var(--soft-gold);
            margin-bottom: 10px;
        }
        #why-choose-us {
            background-color: var(--beige);
            text-align: center;
        }
        #why-choose-us ul {
            list-style: none;
            padding: 0;
        }
        #why-choose-us li {
            margin: 10px 0;
            font-size: 1.1em;
        }
        #contact {
            background-color: var(--cream);
        }
        #contact .content {
            display: flex;
            gap: 40px;
        }
        #contact form {
            flex: 1;
        }
        #contact input, #contact textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid var(--dark-brown);
            border-radius: 5px;
            background-color: var(--beige);
        }
        #contact button {
            background-color: var(--soft-gold);
            color: var(--dark-brown);
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-weight: 700;
        }
        #contact button:hover {
            background-color: var(--dark-brown);
            color: var(--cream);
        }
        footer {
            background-color: var(--dark-brown);
            color: var(--cream);
            text-align: center;
            padding: 20px;
        }
        footer a {
            color: var(--soft-gold);
            margin: 0 10px;
        }
        @media (max-width: 768px) {
            #about .content, #contact .content {
                flex-direction: column;
            }
            .cards {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Sabeena Law Firm</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#practice-areas">Practice Areas</a></li>
                <li><a href="#why-choose-us">Why Choose Us</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h1>Justice with Grace & Strength</h1>
        <p>Welcome to Sabeena Law Firm, where we provide expert legal services with integrity and compassion. Advocate Sabeena is dedicated to delivering justice tailored to your needs.</p>
        <a href="#contact" class="cta-button">Book a Consultation</a>
    </section>

    <section id="about">
        <div class="content">
            <div>
                <h2>About Advocate Sabeena</h2>
                <p>Advocate Sabeena has over 15 years of experience in the legal field, specializing in various areas of law. Her journey began with a passion for justice, leading her to advocate for clients with unwavering dedication. She believes in building strong relationships based on trust and transparency.</p>
                <h3>Our Values</h3>
                <ul>
                    <li><strong>Integrity:</strong> Upholding the highest ethical standards in every case.</li>
                    <li><strong>Trust:</strong> Building lasting relationships with our clients.</li>
                    <li><strong>Confidentiality:</strong> Ensuring your information remains secure and private.</li>
                </ul>
            </div>
            <img src="https://via.placeholder.com/300x400?text=Professional+Photo" alt="Advocate Sabeena">
        </div>
    </section>

    <section id="practice-areas">
        <h2>Practice Areas</h2>
        <div class="cards">
            <div class="card">
                <i class="fas fa-home"></i>
                <h3>Family Law</h3>
                <p>Expert guidance in divorce, custody, and family disputes.</p>
            </div>
            <div class="card">
                <i class="fas fa-gavel"></i>
                <h3>Civil Law</h3>
                <p>Handling contracts, property, and civil litigation.</p>
            </div>
            <div class="card">
                <i class="fas fa-balance-scale"></i>
                <h3>Criminal Defense</h3>
                <p>Defending your rights in criminal matters.</p>
            </div>
            <div class="card">
                <i class="fas fa-building"></i>
                <h3>Corporate Law</h3>
                <p>Advising businesses on legal compliance and transactions.</p>
            </div>
        </div>
    </section>

    <section id="why-choose-us">
        <h2>Why Choose Us</h2>
        <ul>
            <li><strong>Years of Experience:</strong> Over 15 years in delivering successful legal outcomes.</li>
            <li><strong>Client-Focused:</strong> Personalized attention to your unique needs.</li>
            <li><strong>Ethical Practice:</strong> Committed to fairness and integrity in all dealings.</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <div class="content">
            <div>
                <p><strong>Phone:</strong> +1 (123) 456-7890</p>
                <p><strong>Email:</strong> info@sabeenalawfirm.com</p>
                <p><strong>Office Address:</strong> 123 Justice Lane, City, State, ZIP</p>
            </div>
            <form action="#" method="post">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" placeholder="Your Message" rows="5" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </div>
    </section>

    <footer>
        <p>&copy; 2023 Sabeena Law Firm. All rights reserved.</p>
        <a href="#"><i class="fab fa-facebook-f"></i></a>
        <a href="#"><i class="fab fa-twitter"></i></a>
        <a href="#"><i class="fab fa-linkedin-in"></i></a>
    </footer>
</body>
</html>

