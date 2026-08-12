<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Nakhoda Constructions | Meri Mitti • Meri Zameen • Mera Ghar</title>

    <meta name="description" content="Nakhoda Constructions - Construction, planning, supervision, civil works and infrastructure services in Tripura.">
    <meta name="keywords" content="Nakhoda Constructions, construction Tripura, Agartala construction, house construction, civil contractor, building construction">
    <meta name="author" content="Nakhoda Constructions">

    <style>
        :root {
            --primary: #12355b;
            --primary-dark: #0b2540;
            --secondary: #d6a52f;
            --secondary-light: #f4d47b;
            --dark: #1f2937;
            --gray: #64748b;
            --light: #f5f7fa;
            --white: #ffffff;
            --border: #e2e8f0;
            --whatsapp: #25D366;
            --email: #EA4335;
            --shadow: 0 10px 30px rgba(15, 23, 42, 0.08);
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
            background: var(--light);
            color: var(--dark);
            line-height: 1.7;
        }

        a {
            text-decoration: none;
        }

        /* HEADER */

        header {
            background:
                linear-gradient(rgba(9, 35, 61, 0.94), rgba(9, 35, 61, 0.97)),
                linear-gradient(135deg, #12355b, #071a2d);

            color: var(--white);
            text-align: center;
            padding: 55px 20px 45px;
            position: relative;
            overflow: hidden;
        }

        header::after {
            content: "";
            position: absolute;
            width: 300px;
            height: 300px;
            border: 1px solid rgba(214,165,47,0.25);
            border-radius: 50%;
            right: -120px;
            top: -120px;
        }

        .brand {
            position: relative;
            z-index: 2;
        }

        .brand h1 {
            font-size: clamp(2.2rem, 6vw, 4rem);
            letter-spacing: 2px;
            margin-bottom: 8px;
            font-weight: 800;
        }

        .tagline {
            color: var(--secondary-light);
            font-weight: 700;
            letter-spacing: 2px;
            font-size: 1rem;
            margin-bottom: 22px;
        }

        .hero-title {
            font-size: clamp(1.3rem, 4vw, 2rem);
            line-height: 1.4;
            margin-bottom: 18px;
        }

        .hero-subtitle {
            max-width: 750px;
            margin: auto;
            color: #dbe7f3;
            font-size: 1.05rem;
        }

        /* NAVIGATION */

        nav {
            background: var(--white);
            box-shadow: 0 3px 15px rgba(0,0,0,0.08);
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        .nav-container {
            max-width: 1200px;
            margin: auto;
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 6px;
            padding: 10px;
            flex-wrap: wrap;
        }

        nav a {
            color: var(--primary);
            font-weight: 700;
            padding: 8px 13px;
            border-radius: 6px;
            font-size: 0.9rem;
        }

        nav a:hover {
            background: var(--primary);
            color: white;
        }

        /* LANGUAGE */

        .lang-switcher {
            display: flex;
            justify-content: center;
            gap: 8px;
            margin-top: 28px;
            flex-wrap: wrap;
            position: relative;
            z-index: 2;
        }

        .lang-btn {
            background: transparent;
            color: white;
            border: 1px solid rgba(255,255,255,0.45);
            padding: 8px 15px;
            border-radius: 25px;
            cursor: pointer;
            font-size: 0.9rem;
            transition: 0.2s;
        }

        .lang-btn:hover,
        .lang-btn.active {
            background: var(--secondary);
            color: var(--primary-dark);
            border-color: var(--secondary);
            font-weight: 700;
        }

        /* CONTAINER */

        .container {
            width: min(1150px, 92%);
            margin: auto;
        }

        .intro {
            text-align: center;
            max-width: 900px;
            margin: 45px auto;
            font-size: 1.15rem;
            color: var(--gray);
        }

        /* SECTION */

        section {
            padding: 25px 0;
            scroll-margin-top: 70px;
        }

        .section-title {
            color: var(--primary);
            font-size: clamp(1.7rem, 4vw, 2.3rem);
            margin-bottom: 28px;
            position: relative;
            padding-bottom: 12px;
        }

        .section-title::after {
            content: "";
            position: absolute;
            left: 0;
            bottom: 0;
            width: 65px;
            height: 4px;
            background: var(--secondary);
            border-radius: 5px;
        }

        /* CARDS */

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .card {
            background: var(--white);
            padding: 25px;
            border-radius: 12px;
            box-shadow: var(--shadow);
            border-top: 4px solid var(--primary);
            transition: transform 0.25s, box-shadow 0.25s;
        }

        .card:hover {
            transform: translateY(-6px);
            box-shadow: 0 15px 35px rgba(15, 23, 42, 0.13);
        }

        .card h3 {
            color: var(--primary);
            margin-bottom: 10px;
            font-size: 1.15rem;
        }

        .card p {
            color: var(--gray);
        }

        /* FEATURE */

        .feature-box {
            background: linear-gradient(135deg, var(--primary), var(--primary-dark));
            color: white;
            border-radius: 16px;
            padding: 38px 30px;
            margin: 25px 0 50px;
            box-shadow: var(--shadow);
            text-align: center;
        }

        .feature-box h2 {
            color: white;
            margin-bottom: 12px;
        }

        .feature-box p {
            max-width: 800px;
            margin: auto;
            color: #dbe7f3;
        }

        /* TIMELINE */

        .timeline {
            background: white;
            padding: 30px;
            border-radius: 14px;
            box-shadow: var(--shadow);
        }

        .timeline-item {
            margin-bottom: 25px;
            padding: 5px 0 5px 25px;
            border-left: 4px solid var(--secondary);
        }

        .timeline-item:last-child {
            margin-bottom: 0;
        }

        .timeline-item strong {
            color: var(--primary);
            display: block;
            font-size: 1.1rem;
            margin-bottom: 4px;
        }

        .timeline-item p {
            color: var(--gray);
        }

        /* NOTE */

        .note {
            background: #fff8e7;
            border-left: 5px solid var(--secondary);
            padding: 20px;
            margin: 25px 0;
            border-radius: 8px;
            color: #5b4a20;
        }

        /* ABOUT */

        .about-box {
            background: white;
            padding: 35px;
            border-radius: 14px;
            box-shadow: var(--shadow);
        }

        .about-box p {
            color: var(--gray);
            margin-bottom: 18px;
        }

        .vision {
            border-left: 4px solid var(--secondary);
            padding-left: 18px;
        }

        .vision strong {
            color: var(--primary);
        }

        /* PROJECTS */

        .project-card {
            min-height: 180px;
        }

        .project-icon {
            font-size: 2rem;
            margin-bottom: 10px;
        }

        /* CONTACT */

        .contact-section {
            background: linear-gradient(135deg, #0f3153, #09213a);
            color: white;
            padding: 40px 30px;
            border-radius: 16px;
            box-shadow: var(--shadow);
        }

        .contact-section h2,
        .contact-section h3 {
            color: white;
        }

        .contact-intro {
            color: #dbe7f3;
            margin-bottom: 25px;
        }

        .contact-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 35px;
        }

        .contact-details p {
            margin-bottom: 13px;
        }

        .contact-details a {
            color: var(--secondary-light);
            font-weight: 700;
        }

        .action-buttons {
            display: flex;
            flex-direction: column;
            justify-content: center;
            gap: 14px;
        }

        .btn {
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 14px 20px;
            border-radius: 8px;
            color: white;
            font-weight: 800;
            font-size: 1rem;
            transition: 0.2s;
        }

        .btn:hover {
            transform: translateY(-2px);
            opacity: 0.92;
        }

        .btn-whatsapp {
            background: var(--whatsapp);
        }

        .btn-email {
            background: var(--email);
        }

        .btn-call {
            background: var(--secondary);
            color: var(--primary-dark);
        }

        /* FOOTER */

        footer {
            text-align: center;
            padding: 40px 20px;
            margin-top: 65px;
            background: #172333;
            color: #b9c4d0;
        }

        footer strong {
            color: white;
        }

        footer .footer-tagline {
            color: var(--secondary-light);
            font-weight: 700;
            margin: 8px 0;
        }

        /* FLOATING WHATSAPP */

        .floating-whatsapp {
            position: fixed;
            right: 18px;
            bottom: 18px;
            width: 58px;
            height: 58px;
            border-radius: 50%;
            background: var(--whatsapp);
            color: white;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 28px;
            box-shadow: 0 5px 20px rgba(0,0,0,0.25);
            z-index: 999;
        }

        /* MOBILE */

        @media (max-width: 700px) {

            header {
                padding: 42px 15px 35px;
            }

            .brand h1 {
                letter-spacing: 1px;
            }

            .tagline {
                font-size: 0.82rem;
                letter-spacing: 1px;
            }

            .nav-container {
                gap: 2px;
            }

            nav a {
                font-size: 0.78rem;
                padding: 6px 8px;
            }

            .contact-grid {
                grid-template-columns: 1fr;
            }

            .about-box,
            .contact-section {
                padding: 25px 20px;
            }

            .timeline {
                padding: 22px;
            }

            .floating-whatsapp {
                width: 52px;
                height: 52px;
                font-size: 24px;
            }
        }
    </style>
</head>

<body>

<!-- HEADER -->

<header>

    <div class="brand">

        <h1 id="brand-name">Nakhoda Constructions</h1>

        <p class="tagline" id="brand-tagline">
            MERI MITTI • MERI ZAMEEN • MERA GHAR
        </p>

        <h2 class="hero-title" id="hero-title">
            BUILD • PLAN • SUPERVISE<br>
            Build Your Home. Build Your Future.
        </h2>

        <p class="hero-subtitle" id="hero-subtitle">
            Practical construction solutions built around your land, your requirements and your vision.
        </p>

    </div>

    <div class="lang-switcher">

        <button class="lang-btn active" onclick="switchLang('en')">
            English
        </button>

        <button class="lang-btn" onclick="switchLang('bn')">
            বাংলা
        </button>

        <button class="lang-btn" onclick="switchLang('kb')">
            Kokborok
        </button>

    </div>

</header>


<!-- NAVIGATION -->

<nav>

    <div class="nav-container">

        <a href="#services">Services</a>
        <a href="#catalogue">Catalogue</a>
        <a href="#techniques">Techniques</a>
        <a href="#plans">House Plans</a>
        <a href="#projects">Projects</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>

    </div>

</nav>


<main class="container">


    <!-- INTRO -->

    <p class="intro" id="main-intro">

        Complete construction solutions for residential, commercial,
        institutional and infrastructure works — from planning and
        estimation to execution and finishing.

    </p>


    <!-- FEATURE -->

    <div class="feature-box">

        <h2 id="feature-title">
            Your Land. Your Dream. Our Responsibility.
        </h2>

        <p id="feature-text">
            From the first idea to the final handover, Nakhoda Constructions
            aims to provide practical coordination, construction support and
            quality-focused execution.
        </p>

    </div>


    <!-- SERVICES -->

    <section id="services">

        <h2 class="section-title" id="sec-services">
            Our Services
        </h2>

        <div class="grid">

            <div class="card">
                <h3 id="srv-title-1">🏠 Building Construction</h3>
                <p id="srv-desc-1">
                    Residential, commercial and institutional construction works.
                </p>
            </div>

            <div class="card">
                <h3 id="srv-title-2">📐 Planning & Estimation</h3>
                <p id="srv-desc-2">
                    Concept planning, quantity estimation, budgeting and project coordination.
                </p>
            </div>

            <div class="card">
                <h3 id="srv-title-3">🏗 Civil & RCC Works</h3>
                <p id="srv-desc-3">
                    Foundation, columns, beams, slabs, masonry, plaster and related civil works.
                </p>
            </div>

            <div class="card">
                <h3 id="srv-title-4">👷 Site Supervision</h3>
                <p id="srv-desc-4">
                    Labour coordination, progress monitoring and quality-focused supervision.
                </p>
            </div>

            <div class="card">
                <h3 id="srv-title-5">🔧 Renovation</h3>
                <p id="srv-desc-5">
                    Repair, extension, alteration and remodelling of existing buildings.
                </p>
            </div>

            <div class="card">
                <h3 id="srv-title-6">🏢 Infrastructure Works</h3>
                <p id="srv-desc-6">
                    Institutional and infrastructure-related civil construction works.
                </p>
            </div>

        </div>

    </section>


    <!-- CATALOGUE -->

    <section id="catalogue">

        <h2 class="section-title" id="sec-catalogue">
            Construction Catalogue
        </h2>

        <div class="grid">

            <div class="card">
                <h3 id="cat-title-1">🏡 Residential</h3>
                <p id="cat-desc-1">
                    <strong>House Designs:</strong>
                    Modern concepts, elevations and practical home layouts.
                </p>
            </div>

            <div class="card">
                <h3 id="cat-title-2">🏗 Structure</h3>
                <p id="cat-desc-2">
                    <strong>Foundation & RCC:</strong>
                    Foundation, reinforcement, columns, beams and slab systems.
                </p>
            </div>

            <div class="card">
                <h3 id="cat-title-3">🧱 Masonry</h3>
                <p id="cat-desc-3">
                    <strong>Brick & Block Work:</strong>
                    Wall construction, mortar, alignment, openings and curing.
                </p>
            </div>

            <div class="card">
                <h3 id="cat-title-4">🎨 Finishing</h3>
                <p id="cat-desc-4">
                    <strong>Flooring & Painting:</strong>
                    Flooring, wall finishes, painting and final finishing choices.
                </p>
            </div>

            <div class="card">
                <h3 id="cat-title-5">💧 Waterproofing</h3>
                <p id="cat-desc-5">
                    <strong>Roof & Wet Areas:</strong>
                    Roof, wet-area and moisture-control solutions.
                </p>
            </div>

            <div class="card">
                <h3 id="cat-title-6">⚡ Electrical & Plumbing</h3>
                <p id="cat-desc-6">
                    <strong>Building Services:</strong>
                    Systems coordinated with the construction sequence.
                </p>
            </div>

            <div class="card">
                <h3 id="cat-title-7">🪟 Doors & Windows</h3>
                <p id="cat-desc-7">
                    <strong>Openings:</strong>
                    Opening planning and practical selection considerations.
                </p>
            </div>

            <div class="card">
                <h3 id="cat-title-8">🏢 Commercial & Institutional</h3>
                <p id="cat-desc-8">
                    <strong>Facilities:</strong>
                    Reference categories for offices, schools and other institutional buildings.
                </p>
            </div>

        </div>

    </section>


    <!-- TECHNIQUES -->

    <section id="techniques">

        <h2 class="section-title" id="sec-techniques">
            Building Techniques
        </h2>

        <div class="timeline">

            <div class="timeline-item">
                <strong id="tech-title-1">
                    01 — Site & Setting Out
                </strong>
                <p id="tech-desc-1">
                    Understand site conditions, levels, boundaries and the approved layout before excavation.
                </p>
            </div>

            <div class="timeline-item">
                <strong id="tech-title-2">
                    02 — Foundation
                </strong>
                <p id="tech-desc-2">
                    Excavation and foundation construction are carried out according to soil conditions and structural design.
                </p>
            </div>

            <div class="timeline-item">
                <strong id="tech-title-3">
                    03 — RCC Frame
                </strong>
                <p id="tech-desc-3">
                    Reinforcement, formwork and concrete are executed for structural members according to drawings.
                </p>
            </div>

            <div class="timeline-item">
                <strong id="tech-title-4">
                    04 — Masonry
                </strong>
                <p id="tech-desc-4">
                    Walls are constructed with suitable units, mortar, alignment, openings and curing practices.
                </p>
            </div>

            <div class="timeline-item">
                <strong id="tech-title-5">
                    05 — Services
                </strong>
                <p id="tech-desc-5">
                    Electrical, plumbing, drainage and other services are coordinated before closing and finishing.
                </p>
            </div>

            <div class="timeline-item">
                <strong id="tech-title-6">
                    06 — Waterproofing
                </strong>
                <p id="tech-desc-6">
                    Moisture-prone areas receive suitable waterproofing systems and proper surface preparation.
                </p>
            </div>

            <div class="timeline-item">
                <strong id="tech-title-7">
                    07 — Finishing
                </strong>
                <p id="tech-desc-7">
                    Plastering, flooring, painting, doors, windows, fixtures and final quality checks complete the work.
                </p>
            </div>

            <div class="timeline-item">
                <strong id="tech-title-8">
                    08 — Handover
                </strong>
                <p id="tech-desc-8">
                    Final inspection, cleaning, defect correction and documentation prepare the building for handover.
                </p>
            </div>

        </div>

        <div class="note">

            <strong id="technical-note-title">
                Technical Note:
            </strong>

            <span id="technical-note">
                This catalogue is for general information. Dimensions,
                reinforcement, concrete grade, foundation type and other
                structural decisions depend on the project design, site
                conditions and applicable standards.
            </span>

        </div>

    </section>


    <!-- HOUSE PLANS -->

    <section id="plans">

        <h2 class="section-title" id="sec-plans">
            House Plans & Design Concepts
        </h2>

        <div class="grid">

            <div class="card">
                <h3 id="plan-title-1">🏠 Compact Homes</h3>
                <p id="plan-desc-1">
                    Efficient planning for smaller plots and practical family requirements.
                </p>
            </div>

            <div class="card">
                <h3 id="plan-title-2">🏡 Family Homes</h3>
                <p id="plan-desc-2">
                    Balanced spaces for bedrooms, living, dining, kitchen and services.
                </p>
            </div>

            <div class="card">
                <h3 id="plan-title-3">🏢 Multi-Floor Homes</h3>
                <p id="plan-desc-3">
                    Planning considerations for G+1, G+2 and other multi-level buildings.
                </p>
            </div>

            <div class="card">
                <h3 id="plan-title-4">📐 Custom Concepts</h3>
                <p id="plan-desc-4">
                    Customer requirements can be developed into a project-specific design through qualified professionals.
                </p>
            </div>

        </div>

    </section>


    <!-- PROJECTS -->

    <section id="projects">

        <h2 class="section-title" id="sec-projects">
            Our Projects
        </h2>

        <div class="grid">

            <div class="card project-card">
                <div class="project-icon">🏗</div>
                <h3 id="project-title-1">
                    Residential Projects
                </h3>
                <p id="project-desc-1">
                    Residential construction, renovation and improvement works.
                </p>
            </div>

            <div class="card project-card">
                <div class="project-icon">🏫</div>
                <h3 id="project-title-2">
                    Institutional Projects
                </h3>
                <p id="project-desc-2">
                    School, institutional and other civil construction works.
                </p>
            </div>

            <div class="card project-card">
                <div class="project-icon">🏢</div>
                <h3 id="project-title-3">
                    Commercial Projects
                </h3>
                <p id="project-desc-3">
                    Commercial buildings and related construction works.
                </p>
            </div>

            <div class="card project-card">
                <div class="project-icon">🚧</div>
                <h3 id="project-title-4">
                    Infrastructure Works
                </h3>
                <p id="project-desc-4">
                    Infrastructure-related civil works and project coordination.
                </p>
            </div>

        </div>

        <div class="note">

            <strong id="portfolio-title">
                Portfolio Note:
            </strong>

            <span id="portfolio-note">
                Genuine Nakhoda project photographs and project details
                will be added as the portfolio grows.
            </span>

        </div>

    </section>


    <!-- ABOUT -->

    <section id="about">

        <h2 class="section-title" id="sec-about">
            About Nakhoda Constructions
        </h2>

        <div class="about-box">

            <p id="about-text">
                A house is more than concrete and steel. It is built on land,
                family, trust and dreams. Nakhoda Constructions aims to make
                construction easier to understand, plan and coordinate through
                practical construction services and project support.
            </p>

            <p class="vision">

                <strong id="vision-label">
                    Vision:
                </strong>

                <span id="vision-text">
                    To become a trusted construction partner for people and
                    institutions across Tripura and beyond.
                </span>

            </p>

        </div>

    </section>


    <!-- CONTACT -->

    <section id="contact">

        <h2 class="section-title" id="sec-contact">
            Start Your Construction Journey
        </h2>

        <div class="contact-section">

            <p class="contact-intro" id="contact-intro">
                Tell us about your project. Whether you are planning a new
                home, commercial building, institutional project, renovation
                or other civil work, contact Nakhoda Constructions.
            </p>

            <div class="contact-grid">

                <div class="contact-details">

                    <h3 id="contact-title">
                        📞 Contact Nakhoda
                    </h3>

                    <br>

                    <p>
                        📱
                        <strong id="phone-label">
                            Phone:
                        </strong>

                        <a href="tel:+918416081956">
                            8416081956
                        </a>

                        /

                        <a href="tel:+918794912770">
                            8794912770
                        </a>
                    </p>

                    <p>
                        📧
                        <strong id="email-label">
                            Email:
                        </strong>

                        <a href="mailto:nakhodaconstructions@gmail.com">
                            nakhodaconstructions@gmail.com
                        </a>
                    </p>

                    <p>
                        📍
                        <strong id="address-label">
                            Office:
                        </strong>

                        <span id="address-text">
                            Durga Chowmuhani, Near Albert Club,
                            Agartala, West Tripura
                        </span>
                    </p>

                </div>


                <div class="action-buttons">

                    <a
                        class="btn btn-whatsapp"
                        href="https://wa.me/918416081956"
                        target="_blank"
                        rel="noopener"
                    >
                        💬 WhatsApp Us
                    </a>

                    <a
                        class="btn btn-call"
                        href="tel:+918416081956"
                    >
                        📞 Call Nakhoda
                    </a>

                    <a
                        class="btn btn-email"
                        href="mailto:nakhodaconstructions@gmail.com"
                    >
                        📧 Send Email
                    </a>

                </div>

            </div>

        </div>

    </section>


</main>


<!-- FOOTER -->

<footer>

    <p>
        © 2026 <strong>Nakhoda Constructions</strong>
    </p>

    <p class="footer-tagline">
        Meri Mitti • Meri Zameen • Mera Ghar
    </p>

    <p id="footer-text">
        Construction • Planning • Supervision • Infrastructure
    </p>

</footer>


<!-- FLOATING WHATSAPP -->

<a
    class="floating-whatsapp"
    href="https://wa.me/918416081956"
    target="_blank"
    rel="noopener"
    aria-label="Chat with Nakhoda Constructions on WhatsApp"
>
    💬
</a>


<!-- LANGUAGE TRANSLATION SCRIPT -->

<script>

const translations = {

    en: {

        "brand-name": "Nakhoda Constructions",

        "brand-tagline":
            "MERI MITTI • MERI ZAMEEN • MERA GHAR",

        "hero-title":
            "BUILD • PLAN • SUPERVISE<br>Build Your Home. Build Your Future.",

        "hero-subtitle":
            "Practical construction solutions built around your land, your requirements and your vision.",

        "main-intro":
            "Complete construction solutions for residential, commercial, institutional and infrastructure works — from planning and estimation to execution and finishing.",

        "feature-title":
            "Your Land. Your Dream. Our Responsibility.",

        "feature-text":
            "From the first idea to the final handover, Nakhoda Constructions aims to provide practical coordination, construction support and quality-focused execution.",

        "sec-services":
            "Our Services",

        "srv-title-1":
            "🏠 Building Construction",

        "srv-desc-1":
            "Residential, commercial and institutional construction works.",

        "srv-title-2":
            "📐 Planning & Estimation",

        "srv-desc-2":
            "Concept planning, quantity estimation, budgeting and project coordination.",

        "srv-title-3":
            "🏗 Civil & RCC Works",

        "srv-desc-3":
            "Foundation, columns, beams, slabs, masonry, plaster and related civil works.",

        "srv-title-4":
            "👷 Site Supervision",

        "srv-desc-4":
            "Labour coordination, progress monitoring and quality-focused supervision.",

        "srv-title-5":
            "🔧 Renovation",

        "srv-desc-5":
            "Repair, extension, alteration and remodelling of existing buildings.",

        "srv-title-6":
            "🏢 Infrastructure Works",

        "srv-desc-6":
            "Institutional and infrastructure-related civil construction works.",

        "sec-catalogue":
            "Construction Catalogue",

        "cat-title-1":
            "🏡 Residential",

        "cat-desc-1":
            "<strong>House Designs:</strong> Modern concepts, elevations and practical home layouts.",

        "cat-title-2":
            "🏗 Structure",

        "cat-desc-2":
            "<strong>Foundation & RCC:</strong> Foundation, reinforcement, columns, beams and slab systems.",

        "cat-title-3":
            "🧱 Masonry",

        "cat-desc-3":
            "<strong>Brick & Block Work:</strong> Wall construction, mortar, alignment, openings and curing.",

        "cat-title-4":
            "🎨 Finishing",

        "cat-desc-4":
            "<strong>Flooring & Painting:</strong> Flooring, wall finishes, painting and final finishing choices.",

        "cat-title-5":
            "💧 Waterproofing",

        "cat-desc-5":
            "<strong>Roof & Wet Areas:</strong> Roof, wet-area and moisture-control solutions.",

        "cat-title-6":
            "⚡ Electrical & Plumbing",

        "cat-desc-6":
            "<strong>Building Services:</strong> Systems coordinated with the construction sequence.",

        "cat-title-7":
            "🪟 Doors & Windows",

        "cat-desc-7":
            "<strong>Openings:</strong> Opening planning and practical selection considerations.",

        "cat-title-8":
            "🏢 Commercial & Institutional",

        "cat-desc-8":
            "<strong>Facilities:</strong> Reference categories for offices, schools and other institutional buildings.",

        "sec-techniques":
            "Building Techniques",

        "tech-title-1":
            "01 — Site & Setting Out",

        "tech-desc-1":
            "Understand site conditions, levels, boundaries and the approved layout before excavation.",

        "tech-title-2":
            "02 — Foundation",

        "tech-desc-2":
            "Excavation and foundation construction are carried out according to soil conditions and structural design.",

        "tech-title-3":
            "03 — RCC Frame",

        "tech-desc-3":
            "Reinforcement, formwork and concrete are executed for structural members according to drawings.",

        "tech-title-4":
            "04 — Masonry",

        "tech-desc-4":
            "Walls are constructed with suitable units, mortar, alignment, openings and curing practices.",

        "tech-title-5":
            "05 — Services",

        "tech-desc-5":
            "Electrical, plumbing, drainage and other services are coordinated before closing and finishing.",

        "tech-title-6":
            "06 — Waterproofing",

        "tech-desc-6":
            "Moisture-prone areas receive suitable waterproofing systems and proper surface preparation.",

        "tech-title-7":
            "07 — Finishing",

        "tech-desc-7":
            "Plastering, flooring, painting, doors, windows, fixtures and final quality checks complete the work.",

        "tech-title-8":
            "08 — Handover",

        "tech-desc-8":
            "Final inspection, cleaning, defect correction and documentation prepare the building for handover.",

        "technical-note-title":
            "Technical Note:",

        "technical-note":
            "This catalogue is for general information. Dimensions, reinforcement, concrete grade, foundation type and other structural decisions depend on the project design, site conditions and applicable standards.",

        "sec-plans":
            "House Plans & Design Concepts",

        "plan-title-1":
            "🏠 Compact Homes",

        "plan-desc-1":
            "Efficient planning for smaller plots and practical family requirements.",

        "plan-title-2":
            "🏡 Family Homes",

        "plan-desc-2":
            "Balanced spaces for bedrooms, living, dining, kitchen and services.",

        "plan-title-3":
            "🏢 Multi-Floor Homes",

        "plan-desc-3":
            "Planning considerations for G+1, G+2 and other multi-level buildings.",

        "plan-title-4":
            "📐 Custom Concepts",

        "plan-desc-4":
            "Customer requirements can be developed into a project-specific design through qualified professionals.",

        "sec-projects":
            "Our Projects",

        "project-title-1":
            "Residential Projects",

        "project-desc-1":
            "Residential construction, renovation and improvement works.",

        "project-title-2":
            "Institutional Projects",

        "project-desc-2":
            "School, institutional and other civil construction works.",

        "project-title-3":
            "Commercial Projects",

        "project-desc-3":
            "Commercial buildings and related construction works.",

        "project-title-4":
            "Infrastructure Works",

        "project-desc-4":
            "Infrastructure-related civil works and project coordination.",

        "portfolio-title":
            "Portfolio Note:",

        "portfolio-note":
            "Genuine Nakhoda project photographs and project details will be added as the portfolio grows.",

        "sec-about":
            "About Nakhoda Constructions",

        "about-text":
            "A house is more than concrete and steel. It is built on land, family, trust and dreams. Nakhoda Constructions aims to make construction easier to understand, plan and coordinate through practical construction services and project support.",

        "vision-label":
            "Vision:",

        "vision-text":
            "To become a trusted construction partner for people and institutions across Tripura and beyond.",

        "sec-contact":
            "Start Your Construction Journey",

        "contact-intro":
            "Tell us about your project. Whether you are planning a new home, commercial building, institutional project, renovation or other civil work, contact Nakhoda Constructions.",

        "contact-title":
            "📞 Contact Nakhoda",

        "phone-label":
            "Phone:",

        "email-label":
            "Email:",

        "address-label":
            "Office:",

        "address-text":
            "Durga Chowmuhani, Near Albert Club, Agartala, West Tripura",

        "footer-text":
            "Construction • Planning • Supervision • Infrastructure"

    },


    bn: {

        "brand-name":
            "নাখোদা কনস্ট্রাকশনস",

        "brand-tagline":
            "আমার মাটি • আমার জমি • আমার ঘর",

        "hero-title":
            "নির্মাণ • পরিকল্পনা • তদারকি<br>আপনার ঘর গড়ুন। আপনার ভবিষ্যৎ গড়ুন।",

        "hero-subtitle":
            "আপনার জমি, প্রয়োজন এবং স্বপ্নকে কেন্দ্র করে ব্যবহারিক নির্মাণ সমাধান।",

        "main-intro":
            "আবাসিক, বাণিজ্যিক, প্রাতিষ্ঠানিক এবং অবকাঠামো নির্মাণের জন্য পরিকল্পনা ও হিসাব থেকে কাজের বাস্তবায়ন এবং ফিনিশিং পর্যন্ত সম্পূর্ণ নির্মাণ সহায়তা।",

        "feature-title":
            "আপনার জমি। আপনার স্বপ্ন। আমাদের দায়িত্ব।",

        "feature-text":
            "প্রথম পরিকল্পনা থেকে চূড়ান্ত হ্যান্ডওভার পর্যন্ত নাখোদা কনস্ট্রাকশনস ব্যবহারিক সমন্বয়, নির্মাণ সহায়তা এবং গুণমানভিত্তিক কাজের উপর গুরুত্ব দেয়।",

        "sec-services":
            "আমাদের পরিষেবা",

        "srv-title-1":
            "🏠 ভবন নির্মাণ",

        "srv-desc-1":
            "আবাসিক, বাণিজ্যিক এবং প্রাতিষ্ঠানিক নির্মাণ কাজ।",

        "srv-title-2":
            "📐 পরিকল্পনা ও হিসাব",

        "srv-desc-2":
            "কনসেপ্ট পরিকল্পনা, পরিমাণ নির্ধারণ, বাজেট এবং প্রকল্প সমন্বয়।",

        "srv-title-3":
            "🏗 সিভিল ও RCC কাজ",

        "srv-desc-3":
            "ফাউন্ডেশন, কলাম, বিম, স্ল্যাব, গাঁথনি, প্লাস্টার এবং সংশ্লিষ্ট সিভিল কাজ।",

        "srv-title-4":
            "👷 সাইট তদারকি",

        "srv-desc-4":
            "শ্রমিক সমন্বয়, কাজের অগ্রগতি পর্যবেক্ষণ এবং গুণমানভিত্তিক তদারকি।",

        "srv-title-5":
            "🔧 সংস্কার",

        "srv-desc-5":
            "পুরনো ভবনের মেরামত, সম্প্রসারণ, পরিবর্তন এবং পুনর্গঠন।",

        "srv-title-6":
            "🏢 অবকাঠামো কাজ",

        "srv-desc-6":
            "প্রাতিষ্ঠানিক ও অবকাঠামো সম্পর্কিত সিভিল নির্মাণ কাজ।",

        "sec-catalogue":
            "নির্মাণ ক্যাটালগ",

        "cat-title-1":
            "🏡 আবাসিক",

        "cat-desc-1":
            "<strong>বাড়ির ডিজাইন:</strong> আধুনিক ধারণা, এলিভেশন এবং ব্যবহারিক বাড়ির পরিকল্পনা।",

        "cat-title-2":
            "🏗 স্ট্রাকচার",

        "cat-desc-2":
            "<strong>ফাউন্ডেশন ও RCC:</strong> ফাউন্ডেশন, রিইনফোর্সমেন্ট, কলাম, বিম এবং স্ল্যাব ব্যবস্থা।",

        "cat-title-3":
            "🧱 গাঁথনি",

        "cat-desc-3":
            "<strong>ইট ও ব্লক কাজ:</strong> দেয়াল নির্মাণ, মর্টার, অ্যালাইনমেন্ট, ওপেনিং এবং কিউরিং।",

        "cat-title-4":
            "🎨 ফিনিশিং",

        "cat-desc-4":
            "<strong>ফ্লোরিং ও পেইন্টিং:</strong> মেঝে, দেয়ালের ফিনিশ, রং এবং চূড়ান্ত ফিনিশিং।",

        "cat-title-5":
            "💧 ওয়াটারপ্রুফিং",

        "cat-desc-5":
            "<strong>ছাদ ও ভেজা এলাকা:</strong> ছাদ, বাথরুম ও আর্দ্রতা নিয়ন্ত্রণের সমাধান।",

        "cat-title-6":
            "⚡ ইলেকট্রিক্যাল ও প্লাম্বিং",

        "cat-desc-6":
            "<strong>বিল্ডিং সার্ভিস:</strong> নির্মাণের ধাপ অনুযায়ী বিভিন্ন সার্ভিসের সমন্বয়।",

        "cat-title-7":
            "🪟 দরজা ও জানালা",

        "cat-desc-7":
            "<strong>ওপেনিং:</strong> দরজা-জানালার অবস্থান ও ব্যবহারিক নির্বাচন।",

        "cat-title-8":
            "🏢 বাণিজ্যিক ও প্রাতিষ্ঠানিক",

        "cat-desc-8":
            "<strong>ভবন:</strong> অফিস, স্কুল এবং অন্যান্য প্রাতিষ্ঠানিক ভবনের জন্য নির্মাণ বিভাগ।",

        "sec-techniques":
            "নির্মাণ কৌশল",

        "tech-title-1":
            "01 — সাইট ও সেটিং আউট",

        "tech-desc-1":
            "খননের আগে সাইটের অবস্থা, লেভেল, সীমানা এবং অনুমোদিত লে-আউট বুঝে নেওয়া।",

        "tech-title-2":
            "02 — ফাউন্ডেশন",

        "tech-desc-2":
            "মাটির অবস্থা ও স্ট্রাকচারাল ডিজাইন অনুযায়ী খনন এবং ফাউন্ডেশন নির্মাণ করা হয়।",

        "tech-title-3":
            "03 — RCC ফ্রেম",

        "tech-desc-3":
            "ড্রয়িং অনুযায়ী রিইনফোর্সমেন্ট, ফর্মওয়ার্ক এবং কংক্রিটের মাধ্যমে স্ট্রাকচারাল সদস্য তৈরি করা হয়।",

        "tech-title-4":
            "04 — গাঁথনি",

        "tech-desc-4":
            "উপযুক্ত ইট বা ব্লক, মর্টার, অ্যালাইনমেন্ট, ওপেনিং এবং কিউরিং অনুসরণ করে দেয়াল নির্মাণ করা হয়।",

        "tech-title-5":
            "05 — সার্ভিস",

        "tech-desc-5":
            "ইলেকট্রিক্যাল, প্লাম্বিং, ড্রেনেজ এবং অন্যান্য সার্ভিস ফিনিশিংয়ের আগে সমন্বয় করা হয়।",

        "tech-title-6":
            "06 — ওয়াটারপ্রুফিং",

        "tech-desc-6":
            "আর্দ্রতা প্রবণ এলাকায় উপযুক্ত ওয়াটারপ্রুফিং সিস্টেম ও সঠিক সারফেস প্রস্তুতি ব্যবহার করা হয়।",

        "tech-title-7":
            "07 — ফিনিশিং",

        "tech-desc-7":
            "প্লাস্টার, ফ্লোরিং, পেইন্টিং, দরজা, জানালা, ফিক্সচার এবং চূড়ান্ত গুণমান পরীক্ষা সম্পন্ন করা হয়।",

        "tech-title-8":
            "08 — হ্যান্ডওভার",

        "tech-desc-8":
            "চূড়ান্ত পরিদর্শন, পরিষ্কার, ত্রুটি সংশোধন এবং ডকুমেন্টেশনের মাধ্যমে ভবন হস্তান্তরের জন্য প্রস্তুত করা হয়।",

        "technical-note-title":
            "প্রযুক্তিগত নোট:",

        "technical-note":
            "এই ক্যাটালগ সাধারণ তথ্যের জন্য। মাত্রা, রিইনফোর্সমেন্ট, কংক্রিট গ্রেড, ফাউন্ডেশনের ধরন এবং অন্যান্য স্ট্রাকচারাল সিদ্ধান্ত প্রকল্পের ডিজাইন, সাইটের অবস্থা এবং প্রযোজ্য মান অনুযায়ী নির্ধারিত হবে।",

        "sec-plans":
            "বাড়ির প্ল্যান ও ডিজাইন ধারণা",

        "plan-title-1":
            "🏠 ছোট বাড়ি",

        "plan-desc-1":
            "ছোট প্লট এবং ব্যবহারিক পারিবারিক প্রয়োজনের জন্য দক্ষ পরিকল্পনা।",

        "plan-title-2":
            "🏡 পারিবারিক বাড়ি",

        "plan-desc-2":
            "শয়নকক্ষ, বসার ঘর, ডাইনিং, রান্নাঘর এবং সার্ভিসের ভারসাম্যপূর্ণ পরিকল্পনা।",

        "plan-title-3":
            "🏢 বহুতল বাড়ি",

        "plan-desc-3":
            "G+1, G+2 এবং অন্যান্য বহুতল ভবনের পরিকল্পনা।",

        "plan-title-4":
            "📐 কাস্টম ডিজাইন",

        "plan-desc-4":
            "গ্রাহকের প্রয়োজন অনুযায়ী যোগ্য পেশাদারের মাধ্যমে প্রকল্পভিত্তিক ডিজাইন তৈরি করা যায়।",

        "sec-projects":
            "আমাদের প্রকল্প",

        "project-title-1":
            "আবাসিক প্রকল্প",

        "project-desc-1":
            "আবাসিক নির্মাণ, সংস্কার এবং উন্নয়নমূলক কাজ।",

        "project-title-2":
            "প্রাতিষ্ঠানিক প্রকল্প",

        "project-desc-2":
            "স্কুল, প্রতিষ্ঠান এবং অন্যান্য সিভিল নির্মাণ কাজ।",

        "project-title-3":
            "বাণিজ্যিক প্রকল্প",

        "project-desc-3":
            "বাণিজ্যিক ভবন এবং সংশ্লিষ্ট নির্মাণ কাজ।",

        "project-title-4":
            "অবকাঠামো কাজ",

        "project-desc-4":
            "অবকাঠামো সম্পর্কিত সিভিল কাজ এবং প্রকল্প সমন্বয়।",

        "portfolio-title":
            "পোর্টফোলিও নোট:",

        "portfolio-note":
            "নাখোদার প্রকৃত প্রকল্পের ছবি এবং বিস্তারিত তথ্য ভবিষ্যতে এখানে যোগ করা হবে।",

        "sec-about":
            "নাখোদা কনস্ট্রাকশনস সম্পর্কে",

        "about-text":
            "একটি বাড়ি শুধু কংক্রিট ও স্টিল দিয়ে তৈরি হয় না। এটি জমি, পরিবার, বিশ্বাস এবং স্বপ্নের উপর গড়ে ওঠে। নাখোদা কনস্ট্রাকশনস ব্যবহারিক নির্মাণ পরিষেবা ও প্রকল্প সহায়তার মাধ্যমে নির্মাণকে আরও সহজে বোঝা, পরিকল্পনা করা এবং সমন্বয় করার লক্ষ্য রাখে।",

        "vision-label":
            "লক্ষ্য:",

        "vision-text":
            "ত্রিপুরা এবং তার বাইরে মানুষ ও প্রতিষ্ঠানের জন্য একটি বিশ্বস্ত নির্মাণ সহযোগী হিসেবে প্রতিষ্ঠিত হওয়া।",

        "sec-contact":
            "আপনার নির্মাণ যাত্রা শুরু করুন",

        "contact-intro":
            "আপনার প্রকল্প সম্পর্কে আমাদের জানান। নতুন বাড়ি, বাণিজ্যিক ভবন, প্রাতিষ্ঠানিক প্রকল্প, সংস্কার বা অন্য কোনো সিভিল কাজের পরিকল্পনা করলে নাখোদা কনস্ট্রাকশনসের সঙ্গে যোগাযোগ করুন।",

        "contact-title":
            "📞 নাখোদার সঙ্গে যোগাযোগ",

        "phone-label":
            "ফোন:",

        "email-label":
            "ইমেইল:",

        "address-label":
            "অফিস:",

        "address-text":
            "দুর্গা চৌমুহনী, আলবার্ট ক্লাবের কাছে, আগরতলা, পশ্চিম ত্রিপুরা",

        "footer-text":
            "নির্মাণ • পরিকল্পনা • তদারকি • অবকাঠামো"

    },


    kb: {

        "brand-name":
            "Nakhoda Constructions",

        "brand-tagline":
            "MERI MITTI • MERI ZAMEEN • MERA GHAR",

        "hero-title":
            "BUILD • PLAN • SUPERVISE<br>Nwngni Nokni Nwngni Jibonko Nokni.",

        "hero-subtitle":
            "Nwngni land, requirement aro dream ni based practical construction solution.",

        "main-intro":
            "Residential, commercial, institutional aro infrastructure construction khomokha — planning, estimation, execution aro finishing ni complete construction support.",

        "feature-title":
            "Nwngni Jomi. Nwngni Dream. Chini Responsibility.",

        "feature-text":
            "First idea ni thake final handover porjonto Nakhoda Constructions practical coordination, construction support aro quality-focused execution ni importance dei.",

        "sec-services":
            "Chini Services",

        "srv-title-1":
            "🏠 Building Construction",

        "srv-desc-1":
            "Residential, commercial aro institutional building construction.",

        "srv-title-2":
            "📐 Planning & Estimation",

        "srv-desc-2":
            "Concept planning, quantity estimation, budget aro project coordination.",

        "srv-title-3":
            "🏗 Civil & RCC Works",

        "srv-desc-3":
            "Foundation, column, beam, slab, masonry, plaster aro civil works.",

        "srv-title-4":
            "👷 Site Supervision",

        "srv-desc-4":
            "Labour coordination, progress monitoring aro quality supervision.",

        "srv-title-5":
            "🔧 Renovation",

        "srv-desc-5":
            "Old building repair, extension, alteration aro remodelling.",

        "srv-title-6":
            "🏢 Infrastructure Works",

        "srv-desc-6":
            "Institutional aro infrastructure-related civil construction works.",

        "sec-catalogue":
            "Construction Catalogue",

        "cat-title-1":
            "🏡 Residential",

        "cat-desc-1":
            "<strong>House Designs:</strong> Modern concept, elevation aro practical house layout.",

        "cat-title-2":
            "🏗 Structure",

        "cat-desc-2":
            "<strong>Foundation & RCC:</strong> Foundation, reinforcement, column, beam aro slab system.",

        "cat-title-3":
            "🧱 Masonry",

        "cat-desc-3":
            "<strong>Brick & Block Work:</strong> Wall construction, mortar, alignment, opening aro curing.",

        "cat-title-4":
            "🎨 Finishing",

        "cat-desc-4":
            "<strong>Flooring & Painting:</strong> Flooring, wall finish, painting aro final finishing.",

        "cat-title-5":
            "💧 Waterproofing",

        "cat-desc-5":
            "<strong>Roof & Wet Areas:</strong> Roof, wet area aro moisture-control solution.",

        "cat-title-6":
            "⚡ Electrical & Plumbing",

        "cat-desc-6":
            "<strong>Building Services:</strong> Electrical aro plumbing system construction sequence ni coordinate kora.",

        "cat-title-7":
            "🪟 Doors & Windows",

        "cat-desc-7":
            "<strong>Openings:</strong> Door-window opening planning aro practical selection.",

        "cat-title-8":
            "🏢 Commercial & Institutional",

        "cat-desc-8":
            "<strong>Facilities:</strong> Office, school aro institutional building reference.",

        "sec-techniques":
            "Building Techniques",

        "tech-title-1":
            "01 — Site & Setting Out",

        "tech-desc-1":
            "Excavation agor site condition, level, boundary aro approved layout bujha important.",

        "tech-title-2":
            "02 — Foundation",

        "tech-desc-2":
            "Soil condition aro structural design onujayi excavation aro foundation construction kora hoy.",

        "tech-title-3":
            "03 — RCC Frame",

        "tech-desc-3":
            "Drawing onujayi reinforcement, formwork aro concrete diye structural member kora hoy.",

        "tech-title-4":
            "04 — Masonry",

        "tech-desc-4":
            "Suitable brick/block, mortar, alignment, opening aro curing use kore wall construction kora hoy.",

        "tech-title-5":
            "05 — Services",

        "tech-desc-5":
            "Electrical, plumbing, drainage aro other services finishing agote coordinate kora hoy.",

        "tech-title-6":
            "06 — Waterproofing",

        "tech-desc-6":
            "Moisture-prone area ni suitable waterproofing system aro proper surface preparation use kora hoy.",

        "tech-title-7":
            "07 — Finishing",

        "tech-desc-7":
            "Plaster, flooring, painting, door, window, fixture aro final quality checking complete kora hoy.",

        "tech-title-8":
            "08 — Handover",

        "tech-desc-8":
            "Final inspection, cleaning, defect correction aro documentation complete kore handover kora hoy.",

        "technical-note-title":
            "Technical Note:",

        "technical-note":
            "I catalogue general information ni. Structural dimension, reinforcement, concrete grade, foundation type aro other structural decision project design, site condition aro applicable standard onujayi hobo.",

        "sec-plans":
            "House Plans & Design Concepts",

        "plan-title-1":
            "🏠 Compact Homes",

        "plan-desc-1":
            "Small plot aro practical family requirement ni efficient planning.",

        "plan-title-2":
            "🏡 Family Homes",

        "plan-desc-2":
            "Bedroom, living, dining, kitchen aro service ni balanced planning.",

        "plan-title-3":
            "🏢 Multi-Floor Homes",

        "plan-desc-3":
            "G+1, G+2 aro other multi-level building planning.",

        "plan-title-4":
            "📐 Custom Concepts",

        "plan-desc-4":
            "Customer requirement qualified professional ni project-specific design kora jabo.",

        "sec-projects":
            "Chini Projects",

        "project-title-1":
            "Residential Projects",

        "project-desc-1":
            "Residential construction, renovation aro improvement works.",

        "project-title-2":
            "Institutional Projects",

        "project-desc-2":
            "School, institutional aro other civil construction works.",

        "project-title-3":
            "Commercial Projects",

        "project-desc-3":
            "Commercial building aro related construction works.",

        "project-title-4":
            "Infrastructure Works",

        "project-desc-4":
            "Infrastructure-related civil work aro project coordination.",

        "portfolio-title":
            "Portfolio Note:",

        "portfolio-note":
            "Nakhoda ni genuine project photo aro project details future ni ekhane add kora hobo.",

        "sec-about":
            "Nakhoda Constructions somporke",

        "about-text":
            "Nok ekta concrete aro steel ni matro banano noy. Nok land, family, trust aro dream ni build hoy. Nakhoda Constructions practical construction service aro project support diye construction bujha, plan aro coordinate kora easy korte chai.",

        "vision-label":
            "Vision:",

        "vision-text":
            "Tripura aro Tripura-r bahire manush aro institution ni trusted construction partner hote chai.",

        "sec-contact":
            "Nwngni Construction Journey Start Koro",

        "contact-intro":
            "Nwngni project somporke amade janai. New house, commercial building, institutional project, renovation ba other civil work plan korle Nakhoda Constructions ni contact koro.",

        "contact-title":
            "📞 Nakhoda ni Contact",

        "phone-label":
            "Phone:",

        "email-label":
            "Email:",

        "address-label":
            "Office:",

        "address-text":
            "Durga Chowmuhani, Albert Club ni near, Agartala, West Tripura",

        "footer-text":
            "Construction • Planning • Supervision • Infrastructure"

    }

};


/* LANGUAGE SWITCH */

function switchLang(lang) {

    const translation = translations[lang];

    if (!translation) {
        return;
    }

    Object.keys(translation).forEach(function(id) {

        const element = document.getElementById(id);

        if (element) {
            element.innerHTML = translation[id];
        }

    });


    document.querySelectorAll(".lang-btn").forEach(function(button) {

        button.classList.remove("active");

    });


    const buttons = document.querySelectorAll(".lang-btn");

    buttons.forEach(function(button) {

        if (button.getAttribute("onclick") === "switchLang('" + lang + "')") {

            button.classList.add("active");

        }

    });


    document.documentElement.lang = lang;

}


/* DEFAULT LANGUAGE */

switchLang("en");

</script>

</body>
</html>
