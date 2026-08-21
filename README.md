<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Great Barrier Reef</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #e0f7fa 0%, #b2ebf2 100%);
            color: #1a5276;
            line-height: 1.6;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        header {
            background: linear-gradient(135deg, #0288d1 0%, #01579b 100%);
            color: white;
            padding: 40px 20px;
            text-align: center;
            border-radius: 0 0 20px 20px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.2);
        }

        header h1 {
            font-size: 3em;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        header p {
            font-size: 1.2em;
            opacity: 0.9;
        }

        .nav {
            background: white;
            padding: 15px 0;
            position: sticky;
            top: 0;
            z-index: 100;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        .nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 30px;
            flex-wrap: wrap;
        }

        .nav a {
            text-decoration: none;
            color: #0288d1;
            font-weight: 600;
            padding: 8px 16px;
            border-radius: 20px;
            transition: all 0.3s ease;
        }

        .nav a:hover {
            background: #e1f5fe;
            color: #01579b;
        }

        .section {
            background: white;
            margin: 30px 0;
            padding: 40px;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
        }

        .section h2 {
            color: #01579b;
            font-size: 2em;
            margin-bottom: 20px;
            border-bottom: 3px solid #0288d1;
            padding-bottom: 10px;
        }

        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .stat-card {
            background: linear-gradient(135deg, #e1f5fe 0%, #b3e5fc 100%);
            padding: 25px;
            border-radius: 12px;
            text-align: center;
            transition: transform 0.3s ease;
        }

        .stat-card:hover {
            transform: translateY(-5px);
        }

        .stat-card h3 {
            font-size: 2.5em;
            color: #01579b;
            margin-bottom: 5px;
        }

        .stat-card p {
            color: #0277bd;
            font-weight: 500;
        }

        .wildlife-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .wildlife-card {
            background: linear-gradient(135deg, #fff3e0 0%, #ffe0b2 100%);
            padding: 25px;
            border-radius: 12px;
            border-left: 4px solid #ff9800;
        }

        .wildlife-card h3 {
            color: #e65100;
            margin-bottom: 10px;
        }

        .threats-list {
            list-style: none;
        }

        .threats-list li {
            background: #ffebee;
            padding: 15px;
            margin: 10px 0;
            border-radius: 8px;
            border-left: 4px solid #f44336;
        }

        .threats-list li strong {
            color: #c62828;
        }

        .conservation-box {
            background: linear-gradient(135deg, #e8f5e9 0%, #c8e6c9 100%);
            padding: 30px;
            border-radius: 12px;
            border-left: 4px solid #4caf50;
        }

        .conservation-box h3 {
            color: #2e7d32;
            margin-bottom: 15px;
        }

        footer {
            background: #01579b;
            color: white;
            text-align: center;
            padding: 30px;
            margin-top: 40px;
            border-radius: 20px 20px 0 0;
        }

        .emoji {
            font-size: 1.5em;
            margin-right: 10px;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 2em;
            }
            
            .nav ul {
                gap: 15px;
            }
            
            .section {
                padding: 25px;
            }
        }

        .fade-in {
            animation: fadeIn 0.5s ease-in;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
    </style>
</head>
<body>
    <header>
        <h1>🐠 Great Barrier Reef 🐠</h1>
        <p>World's Largest Coral Reef System</p>
    </header>

    <nav class="nav">
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#stats">Statistics</a></li>
            <li><a href="#wildlife">Wildlife</a></li>
            <li><a href="#threats">Threats</a></li>
            <li><a href="#conservation">Conservation</a></li>

        </ul>
    </nav>

    <div class="container">
        <section id="about" class="section fade-in">
            <h2>About the Great Barrier Reef</h2>
            <p>The Great Barrier Reef is the world's largest coral reef ecosystem, composed of over 2,900 individual reefs and 900 islands. It stretches for over 2,300 kilometers along the coast of Queensland, Australia, and covers an area of approximately 344,400 square kilometers.</p>
            <br>
            <p>This incredible natural wonder is visible from space and is one of the seven natural wonders of the world. It was designated a UNESCO World Heritage Site in 1981.</p>
            <p>Many tourists visit the Great Barrier Reef every year to experience its beauty and biodiversity but it is also under threat from climate change, pollution, and other human activities. Some orginisations are starting to help conserve and lower over fishing to protect this amazing ecosystem.
            </p>
        </section>

        <section id="stats" class="section fade-in">
            <h2>Key Statistics</h2>
            <div class="stats-grid">
                <div class="stat-card">
                    <h3>2,300+</h3>
                    <p>Kilometers Long</p>
                </div>
                <div class="stat-card">
                    <h3>1,500+</h3>
                    <p>Fish Species</p>
                </div>
                <div class="stat-card">
                    <h3>400+</h3>
                    <p>Coral Species</p>
                </div>
                <div class="stat-card">
                    <h3>3,000+</h3>
                    <p>Reef Systems</p>
                </div>
            </div>
        </section>

        <section id="wildlife" class="section fade-in">
            <h2>Threats</h2>
            <div class="wildlife-grid">
                <div class="wildlife-card">
                    <h3> 🏭 Pollution 🏭 </h3>
                    <p>Plastic waste and chemical runoff harm marine life and coral health. 
                        You can help by reducing your plastic use and supporting sustainable practices, 
                        and by choosing eco-friendly products and services, 
                        and by supporting organizations that work to protect the reef.
                    </p>
                </div>
                <div class="wildlife-card">
                    <h3>🐟 Overfishing🐟</h3>
                    <p>Overfishing disrupts the delicate balance of the reef ecosystem and can lead to the decline of fish populations.
                        You can help by supporting sustainable fishing practices and by choosing sustainably sourced seafood,
                        and by supporting organizations that work to protect the reef, 
                        and by advocating for stronger fishing regulations.
                    </p>
                </div>
                <div class="wildlife-card">
                    <h3>🌡️ Climate change 🌡️</h3>
                    <p>Climate change causes coral bleaching and threatens reef health.
                        You can help by reducing your carbon footprint and supporting organizations that work to protect the reef,
                        and by advocating for stronger climate policies.
                        you can help by using public transportation, carpooling, or driving electric vehicles.
                    </p>
                </div>
                <div class="wildlife-card">
                    <h3>⛽ Oil dumping ⛽</h3>
                    <p>Oil spills and dumping harm marine life and coral health. You can help by supporting organizations that work to protect the reef, and by advocating for stronger environmental regulations.
                        You can also reduce your own environmental impact by using public transportation, carpooling, or driving electric vehicles.
                        The main reason is beacause of petrol cars that require gasoline to run, which is a major contributor to oil consumption.
                    </p>
                </div>
            </div>
        </section>

        <section id="threats" class="section fade-in">
            <h2>Environmental Threats</h2>
            <ul class="threats-list">
                <li><strong>Climate Change:</strong> Rising sea temperatures cause coral bleaching and threaten reef health.</li>
                <li><strong>Water Quality:</strong> Runoff from agriculture and coastal development affects water clarity.</li>
                <li><strong>Shipping:</strong> Marine traffic risks oil spills and physical damage to coral structures.</li>
                <li><strong>Overfishing:</strong> Unsustainable fishing practices disrupt the delicate food chain.</li>
            </ul>
        </section>

        <section id="conservation" class="section fade-in">
            <h2>Conservation Efforts</h2>
            <div class="conservation-box">
                <h3>🛡️ Reef 2050 Plan</h3>
                <p>Australia's long-term sustainability plan to protect and manage the reef for future generations.</p>
                <br>
                <h3>🏝️ Marine Parks</h3>
                <p>Protected zones where fishing and tourism are carefully regulated to minimize human impact.</p>
                <br>
                <h3>🔬 Research Programs</h3>
                <p>Ongoing scientific studies to monitor reef health and develop innovative conservation solutions.</p>
            </div>
        </section>


    </div>

    <footer>
        <p>© 2024 Great Barrier Reef Information | Protect Our Oceans 🌊</p>
    </footer>

    <script>
        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });

        // Add fade-in animation on scroll
        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -50px 0px'
        };

        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('fade-in');
                }
            });
        }, observerOptions);

        document.querySelectorAll('.section').forEach(section => {
            observer.observe(section);
        });

        // Dynamic year in footer
        const footer = document.querySelector('footer p');
        const currentYear = new Date().getFullYear();
        footer.textContent = `© ${currentYear} Great Barrier Reef Information | Protect Our Oceans 🌊`;

        // Add interactive hover effect to stat cards
        document.querySelectorAll('.stat-card').forEach(card => {
            card.addEventListener('mouseenter', function() {
                this.style.transform = 'translateY(-10px) scale(1.02)';
                this.style.boxShadow = '0 8px 25px rgba(0,0,0,0.2)';
            });
            
            card.addEventListener('mouseleave', function() {
                this.style.transform = 'translateY(0) scale(1)';
                this.style.boxShadow = 'none';
            });
        });

        // Add click effect to wildlife cards
        document.querySelectorAll('.wildlife-card').forEach(card => {
            card.addEventListener('click', function() {
                this.style.background = 'linear-gradient(135deg, #fff8e1 0%, #ffecb3 100%)';
                setTimeout(() => {
                    this.style.background = 'linear-gradient(135deg, #fff3e0 0%, #ffe0b2 100%)';
                }, 300);
            });
        });
    </script>
</body>
</html>
