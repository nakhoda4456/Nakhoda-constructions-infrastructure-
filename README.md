<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Nakhoda Constructions | Meri Mitti • Meri Zameen • Mera Ghar</title>

    <style>
        :root {
            --primary: #1a365d;
            --secondary: #d69e2e;
            --dark: #2d3748;
            --light: #f7fafc;
            --white: #ffffff;
            --whatsapp: #25D366;
            --email: #EA4335;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: var(--light);
            color: var(--dark);
            line-height: 1.6;
        }

        header {
            background-color: var(--primary);
            color: var(--white);
            padding: 2.5rem 1rem;
            text-align: center;
        }

        header h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }

        header p.tagline {
            color: var(--secondary);
            font-weight: 600;
            letter-spacing: 1px;
            margin-bottom: 1rem;
        }

        header h2.hero-title {
            color: var(--white);
            font-size: 1.5rem;
            margin-top: 1rem;
            border-bottom: none;
        }

        .lang-switcher {
            display: flex;
            justify-content: center;
            gap: 1rem;
            margin-top: 1.5rem;
            flex-wrap: wrap;
        }

        .lang-btn {
            background: transparent;
            color: var(--white);
            border: 1px solid rgba(255,255,255,0.4);
            padding: 0.4rem 1rem;
            border-radius: 4px;
            cursor: pointer;
            font-size: 0.9rem;
            transition: all 0.2s ease;
        }

        .lang-btn:hover,
        .lang-btn.active {
            background-color: var(--secondary);
            color: var(--primary);
            border-color: var(--secondary);
            font-weight: bold;
        }

        .container {
            max-width: 1100px;
            margin: 2rem auto;
            padding: 0 1rem;
        }

        .intro {
            text-align: center;
            margin-bottom: 3rem;
            font-size: 1.2rem;
            color: #4a5568;
        }

        h2 {
            color: var(--primary);
            border-bottom: 3px solid var(--secondary);
            padding-bottom: 0.5rem;
            margin: 3rem 0 1.5rem;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 1.5rem;
        }

        .card {
            background: var(--white);
            padding: 1.5rem;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
            border-top: 4px solid var(--primary);
            transition: transform 0.2s;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        .card h3 {
            margin-bottom: 0.5rem;
            color: var(--primary);
        }

        .timeline {
            background: var(--white);
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
        }

        .timeline-item {
            margin-bottom: 1.5rem;
            padding-left: 1.5rem;
            border-left: 3px solid var(--secondary);
        }

        .timeline-item:last-child {
            margin-bottom: 0;
        }

        .timeline-item strong {
            color: var(--primary);
            display: block;
            font-size: 1.1rem;
            margin-bottom: 0.25rem;
        }

        .note {
            background-color: #feebc8;
            border-left: 4px solid var(--secondary);
            padding: 1.2rem;
            margin: 2rem 0;
            border-radius: 4px;
            font-style: italic;
        }

        .contact-section {
            background: var(--white);
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
            margin-top: 2rem;
        }

        .contact-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            margin-top: 1.5rem;
        }

        .contact-details p {
            margin-bottom: 0.8rem;
            font-size: 1.05rem;
        }

        .contact-details a {
            color: var(--primary);
            text-decoration: none;
            font-weight: 600;
        }

        .contact-details a:hover {
            text-decoration: underline;
        }

        .action-buttons {
            display: flex;
            flex-direction: column;
            gap: 1rem;
            justify-content: center;
        }

        .btn {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            gap: 0.5rem;
            padding: 0.8rem 1.5rem;
            border-radius: 6px;
            text-decoration: none;
            color: var(--white);
            font-weight: bold;
            font-size: 1.1rem;
            transition: opacity 0.2s;
            text-align: center;
        }

        .btn:hover {
            opacity: 0.9;
        }

        .btn-whatsapp {
            background-color: var(--whatsapp);
        }

        .btn-email {
            background-color: var(--email);
        }

        footer {
            text-align: center;
            padding: 2.5rem;
            margin-top: 5rem;
            background-color: #2d3748;
            color: #a0aec0;
            font-size: 0.95rem;
        }

        @media (max-width: 600px) {
            header h1 {
                font-size: 2rem;
            }

            header h2.hero-title {
                font-size: 1.2rem;
            }

            .intro {
                font-size: 1rem;
            }

            .container {
                padding: 0 0.8rem;
            }
        }
    </style>
</head>

<body>

<header>

    <h1 id="brandName">Nakhoda Constructions</h1>

    <p class="tagline" id="brandTagline">
        MERI MITTI • MERI ZAMEEN • MERA GHAR
    </p>

    <h2 class="hero-title" id="heroTitle">
        BUILD • PLAN • SUPERVISE<br>
        Build Your Home. Build Your Future.
    </h2>

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


<div class="container">

    <p class="intro" id="mainIntro">
        Complete construction solutions for residential, commercial,
        institutional and infrastructure works — from planning and
        estimation to execution and finishing.
    </p>


    <!-- SERVICES -->

    <h2 id="secServices">Our Services</h2>

    <div class="grid">

        <div class="card">
            <h3 id="srvTitle1">🏠 Building Construction</h3>
            <p id="srvDesc1">
                Residential, commercial and institutional construction works.
            </p>
        </div>

        <div class="card">
            <h3 id="srvTitle2">📐 Planning & Estimation</h3>
            <p id="srvDesc2">
                Concept planning, quantity estimation, budgeting and project coordination.
            </p>
        </div>

        <div class="card">
            <h3 id="srvTitle3">🏗 Civil & RCC Works</h3>
            <p id="srvDesc3">
                Foundation, columns, beams, slabs, masonry, plaster and related civil works.
            </p>
        </div>

        <div class="card">
            <h3 id="srvTitle4">👷 Site Supervision</h3>
            <p id="srvDesc4">
                Labour coordination, progress monitoring and quality-focused supervision.
            </p>
        </div>

        <div class="card">
            <h3 id="srvTitle5">🔧 Renovation</h3>
            <p id="srvDesc5">
                Repair, extension, alteration and remodelling of existing buildings.
            </p>
        </div>

        <div class="card">
            <h3 id="srvTitle6">🏢 Infrastructure Works</h3>
            <p id="srvDesc6">
                Institutional and infrastructure-related civil construction works.
            </p>
        </div>

    </div>


    <!-- CONSTRUCTION CATALOGUE -->

    <h2 id="secCatalogue">Construction Catalogue</h2>

    <div class="grid">

        <div class="card">
            <h3 id="catTitle1">🏡 Residential</h3>
            <p id="catDesc1">
                <strong>House Designs:</strong>
                Modern concepts, elevations and practical home layouts.
            </p>
        </div>

        <div class="card">
            <h3 id="catTitle2">🏗 Structure</h3>
            <p id="catDesc2">
                <strong>Foundation & RCC:</strong>
                Foundation, reinforcement, columns, beams and slab systems.
            </p>
        </div>

        <div class="card">
            <h3 id="catTitle3">🧱 Masonry</h3>
            <p id="catDesc3">
                <strong>Brick & Block Work:</strong>
                Wall construction, mortar, alignment, openings and curing.
            </p>
        </div>

        <div class="card">
            <h3 id="catTitle4">🎨 Finishing</h3>
            <p id="catDesc4">
                <strong>Flooring & Painting:</strong>
                Flooring, wall finishes, painting and final finishing choices.
            </p>
        </div>

        <div class="card">
            <h3 id="catTitle5">💧 Waterproofing</h3>
            <p id="catDesc5">
                <strong>Roof & Wet Areas:</strong>
                Roof, wet-area and moisture-control solutions.
            </p>
        </div>

        <div class="card">
            <h3 id="catTitle6">⚡ Electrical & Plumbing</h3>
            <p id="catDesc6">
                <strong>Building Services:</strong>
                Systems coordinated with the construction sequence.
            </p>
        </div>

        <div class="card">
            <h3 id="catTitle7">🪟 Doors & Windows</h3>
            <p id="catDesc7">
                <strong>Openings:</strong>
                Opening planning and practical selection considerations.
            </p>
        </div>

        <div class="card">
            <h3 id="catTitle8">🏢 Commercial & Institutional</h3>
            <p id="catDesc8">
                <strong>Facilities:</strong>
                Reference categories for offices, schools and other institutional buildings.
            </p>
        </div>

    </div>


    <!-- BUILDING TECHNIQUES -->

    <h2 id="secTechniques">Building Techniques</h2>

    <div class="timeline">

        <div class="timeline-item">
            <strong id="techTitle1">01 — Site & Setting Out</strong>
            <p id="techDesc1">
                Understand site conditions, levels, boundaries and the approved layout before excavation.
            </p>
        </div>

        <div class="timeline-item">
            <strong id="techTitle2">02 — Foundation</strong>
            <p id="techDesc2">
                Excavation and foundation construction are carried out according to soil conditions and structural design.
            </p>
        </div>

        <div class="timeline-item">
            <strong id="techTitle3">03 — RCC Frame</strong>
            <p id="techDesc3">
                Reinforcement, formwork and concrete are executed for structural members according to drawings.
            </p>
        </div>

        <div class="timeline-item">
            <strong id="techTitle4">04 — Masonry</strong>
            <p id="techDesc4">
                Walls are constructed with suitable units, mortar, alignment, openings and curing practices.
            </p>
        </div>

        <div class="timeline-item">
            <strong id="techTitle5">05 — Services</strong>
            <p id="techDesc5">
                Electrical, plumbing, drainage and other services are coordinated before closing and finishing.
            </p>
        </div>

        <div class="timeline-item">
            <strong id="techTitle6">06 — Waterproofing</strong>
            <p id="techDesc6">
                Moisture-prone areas receive suitable waterproofing systems and proper surface preparation.
            </p>
        </div>

        <div class="timeline-item">
            <strong id="techTitle7">07 — Finishing</strong>
            <p id="techDesc7">
                Plastering, flooring, painting, doors, windows, fixtures and final quality checks complete the work.
            </p>
        </div>

        <div class="timeline-item">
            <strong id="techTitle8">08 — Handover</strong>
            <p id="techDesc8">
                Final inspection, cleaning, defect correction and documentation prepare the building for handover.
            </p>
        </div>

    </div>

    <div class="note">
        <strong id="technicalNoteTitle">Technical Note:</strong>

        <span id="technicalNote">
            This catalogue is for general information. Dimensions,
            reinforcement, concrete grade, foundation type and other
            structural decisions depend on the project design, site
            conditions and applicable standards.
        </span>
    </div>


    <!-- HOUSE PLANS -->

    <h2 id="secPlans">House Plans & Design Concepts</h2>

    <div class="grid">

        <div class="card">
            <h3 id="planTitle1">🏠 Compact Homes</h3>
            <p id="planDesc1">
                Efficient planning for smaller plots and practical family requirements.
            </p>
        </div>

        <div class="card">
            <h3 id="planTitle2">🏡 Family Homes</h3>
            <p id="planDesc2">
                Balanced spaces for bedrooms, living, dining, kitchen and services.
            </p>
        </div>

        <div class="card">
            <h3 id="planTitle3">🏢 Multi-Floor Homes</h3>
            <p id="planDesc3">
                Planning considerations for G+1, G+2 and other multi-level buildings.
            </p>
        </div>

        <div class="card">
            <h3 id="planTitle4">📐 Custom Concepts</h3>
            <p id="planDesc4">
                Customer requirements can be developed into a project-specific design through qualified professionals.
            </p>
        </div>

    </div>


    <!-- PROJECTS -->

    <h2 id="secProjects">Our Projects</h2>

    <div class="grid">

        <div class="card">
            <h3 id="projectTitle1">🏗 Residential Projects</h3>
            <p id="projectDesc1">
                Residential construction, renovation and improvement works.
            </p>
        </div>

        <div class="card">
            <h3 id="projectTitle2">🏫 Institutional Projects</h3>
            <p id="projectDesc2">
                School, institutional and other civil construction works.
            </p>
        </div>

        <div class="card">
            <h3 id="projectTitle3">🏢 Commercial Projects</h3>
            <p id="projectDesc3">
                Commercial buildings and related construction works.
            </p>
        </div>

        <div class="card">
            <h3 id="projectTitle4">🚧 Infrastructure Works</h3>
            <p id="projectDesc4">
                Infrastructure-related civil works and project coordination.
            </p>
        </div>

    </div>

    <div class="note">
        <strong id="portfolioTitle">Portfolio Note:</strong>

        <span id="portfolioNote">
            Genuine Nakhoda project photographs and project details
            will be added as the portfolio grows.
        </span>
    </div>


    <!-- ABOUT -->

    <h2 id="secAbout">About Nakhoda Constructions</h2>

    <div class="contact-section">

        <p id="aboutText">
            A house is more than concrete and steel. It is built on land,
            family, trust and dreams. Nakhoda Constructions aims to make
            construction easier to understand, plan and coordinate through
            practical construction services and project support.
        </p>

        <br>

        <p>
            <strong id="visionLabel">Vision:</strong>

            <span id="visionText">
                To become a trusted construction partner for people and
                institutions across Tripura and beyond.
            </span>
        </p>

    </div>


    <!-- CONTACT -->

    <h2 id="secContact">Start Your Construction Journey</h2>

    <div class="contact-section">

        <p id="contactIntro">
            Tell us about your project. Whether you are planning a new home,
            commercial building, institutional project, renovation or other
            civil work, contact Nakhoda Constructions.
        </p>

        <div class="contact-grid">

            <div class="contact-details">

                <h3 id="contactTitle">
                    📞 Contact Nakhoda
                </h3>

                <p>
                    📱 <strong id="phoneLabel">Phone:</strong>

                    <a href="tel:+918416081956">
                        8416081956
                    </a>

                    /

                    <a href="tel:+918794912770">
                        8794912770
                    </a>
                </p>

                <p>
                    📧 <strong id="emailLabel">Email:</strong>

                    <a href="mailto:nakhodaconstructions@gmail.com">
                        nakhodaconstructions@gmail.com
                    </a>
                </p>

                <p>
                    📍 <strong id="addressLabel">Office:</strong>

                    <span id="addressText">
                        Durga Chowmuhani, Near Albert Club,
                        Agartala, West Tripura
                    </span>
                </p>

            </div>


            <div class="action-buttons">

                <a class="btn btn-whatsapp"
                   href="https://wa.me/918416081956"
                   target="_blank"
                   rel="noopener noreferrer">
                    💬 WhatsApp Us
                </a>

                <a class="btn btn-email"
                   href="mailto:nakhodaconstructions@gmail.com">
                    📧 Send Email
                </a>

            </div>

        </div>

    </div>

</div>


<!-- FOOTER -->

<footer>

    <p>
        © 2026 <strong>Nakhoda Constructions</strong>
    </p>

    <p>
        Meri Mitti • Meri Zameen • Mera Ghar
    </p>

    <p id="footerText">
        Construction • Planning • Supervision • Infrastructure
    </p>

</footer>


<!-- LANGUAGE TRANSLATION SCRIPT -->

<script>

const translations = {

    en: {

        brandName: "Nakhoda Constructions",

        brandTagline:
            "MERI MITTI • MERI ZAMEEN • MERA GHAR",

        heroTitle:
            "BUILD • PLAN • SUPERVISE<br>Build Your Home. Build Your Future.",

        mainIntro:
            "Complete construction solutions for residential, commercial, institutional and infrastructure works — from planning and estimation to execution and finishing.",

        secServices: "Our Services",

        srvTitle1: "🏠 Building Construction",
        srvDesc1: "Residential, commercial and institutional construction works.",

        srvTitle2: "📐 Planning & Estimation",
        srvDesc2: "Concept planning, quantity estimation, budgeting and project coordination.",

        srvTitle3: "🏗 Civil & RCC Works",
        srvDesc3: "Foundation, columns, beams, slabs, masonry, plaster and related civil works.",

        srvTitle4: "👷 Site Supervision",
        srvDesc4: "Labour coordination, progress monitoring and quality-focused supervision.",

        srvTitle5: "🔧 Renovation",
        srvDesc5: "Repair, extension, alteration and remodelling of existing buildings.",

        srvTitle6: "🏢 Infrastructure Works",
        srvDesc6: "Institutional and infrastructure-related civil construction works.",

        secCatalogue: "Construction Catalogue",

        catTitle1: "🏡 Residential",
        catDesc1: "<strong>House Designs:</strong> Modern concepts, elevations and practical home layouts.",

        catTitle2: "🏗 Structure",
        catDesc2: "<strong>Foundation & RCC:</strong> Foundation, reinforcement, columns, beams and slab systems.",

        catTitle3: "🧱 Masonry",
        catDesc3: "<strong>Brick & Block Work:</strong> Wall construction, mortar, alignment, openings and curing.",

        catTitle4: "🎨 Finishing",
        catDesc4: "<strong>Flooring & Painting:</strong> Flooring, wall finishes, painting and final finishing choices.",

        catTitle5: "💧 Waterproofing",
        catDesc5: "<strong>Roof & Wet Areas:</strong> Roof, wet-area and moisture-control solutions.",

        catTitle6: "⚡ Electrical & Plumbing",
        catDesc6: "<strong>Building Services:</strong> Systems coordinated with the construction sequence.",

        catTitle7: "🪟 Doors & Windows",
        catDesc7: "<strong>Openings:</strong> Opening planning and practical selection considerations.",

        catTitle8: "🏢 Commercial & Institutional",
        catDesc8: "<strong>Facilities:</strong> Reference categories for offices, schools and other institutional buildings.",

        secTechniques: "Building Techniques",

        techTitle1: "01 — Site & Setting Out",
        techDesc1: "Understand site conditions, levels, boundaries and the approved layout before excavation.",

        techTitle2: "02 — Foundation",
        techDesc2: "Excavation and foundation construction are carried out according to soil conditions and structural design.",

        techTitle3: "03 — RCC Frame",
        techDesc3: "Reinforcement, formwork and concrete are executed for structural members according to drawings.",

        techTitle4: "04 — Masonry",
        techDesc4: "Walls are constructed with suitable units, mortar, alignment, openings and curing practices.",

        techTitle5: "05 — Services",
        techDesc5: "Electrical, plumbing, drainage and other services are coordinated before closing and finishing.",

        techTitle6: "06 — Waterproofing",
        techDesc6: "Moisture-prone areas receive suitable waterproofing systems and proper surface preparation.",

        techTitle7: "07 — Finishing",
        techDesc7: "Plastering, flooring, painting, doors, windows, fixtures and final quality checks complete the work.",

        techTitle8: "08 — Handover",
        techDesc8: "Final inspection, cleaning, defect correction and documentation prepare the building for handover.",

        technicalNoteTitle: "Technical Note:",

        technicalNote:
            "This catalogue is for general information. Dimensions, reinforcement, concrete grade, foundation type and other structural decisions depend on the project design, site conditions and applicable standards.",

        secPlans: "House Plans & Design Concepts",

        planTitle1: "🏠 Compact Homes",
        planDesc1: "Efficient planning for smaller plots and practical family requirements.",

        planTitle2: "🏡 Family Homes",
        planDesc2: "Balanced spaces for bedrooms, living, dining, kitchen and services.",

        planTitle3: "🏢 Multi-Floor Homes",
        planDesc3: "Planning considerations for G+1, G+2 and other multi-level buildings.",

        planTitle4: "📐 Custom Concepts",
        planDesc4: "Customer requirements can be developed into a project-specific design through qualified professionals.",

        secProjects: "Our Projects",

        projectTitle1: "🏗 Residential Projects",
        projectDesc1: "Residential construction, renovation and improvement works.",

        projectTitle2: "🏫 Institutional Projects",
        projectDesc2: "School, institutional and other civil construction works.",

        projectTitle3: "🏢 Commercial Projects",
        projectDesc3: "Commercial buildings and related construction works.",

        projectTitle4: "🚧 Infrastructure Works",
        projectDesc4: "Infrastructure-related civil works and project coordination.",

        portfolioTitle: "Portfolio Note:",

        portfolioNote:
            "Genuine Nakhoda project photographs and project details will be added as the portfolio grows.",

        secAbout: "About Nakhoda Constructions",

        aboutText:
            "A house is more than concrete and steel. It is built on land, family, trust and dreams. Nakhoda Constructions aims to make construction easier to understand, plan and coordinate through practical construction services and project support.",

        visionLabel: "Vision:",

        visionText:
            "To become a trusted construction partner for people and institutions across Tripura and beyond.",

        secContact: "Start Your Construction Journey",

        contactIntro:
            "Tell us about your project. Whether you are planning a new home, commercial building, institutional project, renovation or other civil work, contact Nakhoda Constructions.",

        contactTitle: "📞 Contact Nakhoda",

        phoneLabel: "Phone:",
        emailLabel: "Email:",
        addressLabel: "Office:",

        addressText:
            "Durga Chowmuhani, Near Albert Club, Agartala, West Tripura",

        footerText:
            "Construction • Planning • Supervision • Infrastructure"
    },


    bn: {

        brandName: "নাখোদা কনস্ট্রাকশনস",

        brandTagline:
            "আমার মাটি • আমার জমি • আমার ঘর",

        heroTitle:
            "নির্মাণ • পরিকল্পনা • তদারকি<br>আপনার ঘর গড়ুন। আপনার ভবিষ্যৎ গড়ুন।",

        mainIntro:
            "বাড়ি, বাণিজ্যিক ভবন, প্রতিষ্ঠান এবং অবকাঠামো নির্মাণের জন্য পরিকল্পনা ও হিসাব থেকে শুরু করে কাজের বাস্তবায়ন এবং ফিনিশিং পর্যন্ত সম্পূর্ণ নির্মাণ সহায়তা।",

        secServices: "আমাদের পরিষেবা",

        srvTitle1: "🏠 ভবন নির্মাণ",
        srvDesc1: "আবাসিক, বাণিজ্যিক এবং প্রাতিষ্ঠানিক নির্মাণ কাজ।",

        srvTitle2: "📐 পরিকল্পনা ও হিসাব",
        srvDesc2: "কনসেপ্ট পরিকল্পনা, পরিমাণ নির্ধারণ, বাজেট এবং প্রকল্প সমন্বয়।",

        srvTitle3: "🏗 সিভিল ও RCC কাজ",
        srvDesc3: "ফাউন্ডেশন, কলাম, বিম, স্ল্যাব, গাঁথনি, প্লাস্টার এবং সংশ্লিষ্ট সিভিল কাজ।",

        srvTitle4: "👷 সাইট তদারকি",
        srvDesc4: "শ্রমিক সমন্বয়, কাজের অগ্রগতি পর্যবেক্ষণ এবং গুণমানভিত্তিক তদারকি।",

        srvTitle5: "🔧 সংস্কার",
        srvDesc5: "পুরনো ভবনের মেরামত, সম্প্রসারণ, পরিবর্তন এবং পুনর্গঠন।",

        srvTitle6: "🏢 অবকাঠামো কাজ",
        srvDesc6: "প্রাতিষ্ঠানিক ও অবকাঠামো সম্পর্কিত সিভিল নির্মাণ কাজ।",

        secCatalogue: "নির্মাণ ক্যাটালগ",

        catTitle1: "🏡 আবাসিক",
        catDesc1: "<strong>বাড়ির ডিজাইন:</strong> আধুনিক ধারণা, এলিভেশন এবং ব্যবহারিক বাড়ির পরিকল্পনা।",

        catTitle2: "🏗 স্ট্রাকচার",
        catDesc2: "<strong>ফাউন্ডেশন ও RCC:</strong> ফাউন্ডেশন, রিইনফোর্সমেন্ট, কলাম, বিম এবং স্ল্যাব ব্যবস্থা।",

        catTitle3: "🧱 গাঁথনি",
        catDesc3: "<strong>ইট ও ব্লক কাজ:</strong> দেয়াল নির্মাণ, মর্টার, অ্যালাইনমেন্ট, ওপেনিং এবং কিউরিং।",

        catTitle4: "🎨 ফিনিশিং",
        catDesc4: "<strong>ফ্লোরিং ও পেইন্টিং:</strong> মেঝে, দেয়ালের ফিনিশ, রং এবং চূড়ান্ত ফিনিশিং।",

        catTitle5: "💧 ওয়াটারপ্রুফিং",
        catDesc5: "<strong>ছাদ ও ভেজা এলাকা:</strong> ছাদ, বাথরুম ও আর্দ্রতা নিয়ন্ত্রণের সমাধান।",

        catTitle6: "⚡ ইলেকট্রিক্যাল ও প্লাম্বিং",
        catDesc6: "<strong>বিল্ডিং সার্ভিস:</strong> নির্মাণের ধাপ অনুযায়ী বিভিন্ন সার্ভিসের সমন্বয়।",

        catTitle7: "🪟 দরজা ও জানালা",
        catDesc7: "<strong>ওপেনিং:</strong> দরজা-জানালার অবস্থান ও ব্যবহারিক নির্বাচন।",

        catTitle8: "🏢 বাণিজ্যিক ও প্রাতিষ্ঠানিক",
        catDesc8: "<strong>ভবন:</strong> অফিস, স্কুল এবং অন্যান্য প্রাতিষ্ঠানিক ভবনের জন্য নির্মাণ বিভাগ।",

        secTechniques: "নির্মাণ কৌশল",

        techTitle1: "01 — সাইট ও সেটিং আউট",
        techDesc1: "খননের আগে সাইটের অবস্থা, লেভেল, সীমানা এবং অনুমোদিত লে-আউট বুঝে নেওয়া।",

        techTitle2: "02 — ফাউন্ডেশন",
        techDesc2: "মাটির অবস্থা ও স্ট্রাকচারাল ডিজাইন অনুযায়ী খনন এবং ফাউন্ডেশন নির্মাণ করা হয়।",

        techTitle3: "03 — RCC ফ্রেম",
        techDesc3: "ড্রয়িং অনুযায়ী রিইনফোর্সমেন্ট, ফর্মওয়ার্ক এবং কংক্রিটের মাধ্যমে স্ট্রাকচারাল সদস্য তৈরি করা হয়।",

        techTitle4: "04 — গাঁথনি",
        techDesc4: "উপযুক্ত ইট বা ব্লক, মর্টার, অ্যালাইনমেন্ট, ওপেনিং এবং কিউরিং অনুসরণ করে দেয়াল নির্মাণ করা হয়।",

        techTitle5: "05 — সার্ভিস",
        techDesc5: "ইলেকট্রিক্যাল, প্লাম্বিং, ড্রেনেজ এবং অন্যান্য সার্ভিস ফিনিশিংয়ের আগে সমন্বয় করা হয়।",

        techTitle6: "06 — ওয়াটারপ্রুফিং",
        techDesc6: "আর্দ্রতা প্রবণ এলাকায় উপযুক্ত ওয়াটারপ্রুফিং সিস্টেম ও সঠিক সারফেস প্রস্তুতি ব্যবহার করা হয়।",

        techTitle7: "07 — ফিনিশিং",
        techDesc7: "প্লাস্টার, ফ্লোরিং, পেইন্টিং, দরজা, জানালা, ফিক্সচার এবং চূড়ান্ত গুণমান পরীক্ষা সম্পন্ন করা হয়।",

        techTitle8: "08 — হ্যান্ডওভার",
        techDesc8: "চূড়ান্ত পরিদর্শন, পরিষ্কার, ত্রুটি সংশোধন এবং ডকুমেন্টেশনের মাধ্যমে ভবন হস্তান্তরের জন্য প্রস্তুত করা হয়।",

        technicalNoteTitle: "প্রযুক্তিগত নোট:",

        technicalNote:
            "এই ক্যাটালগ সাধারণ তথ্যের জন্য। মাত্রা, রিইনফোর্সমেন্ট, কংক্রিট গ্রেড, ফাউন্ডেশনের ধরন এবং অন্যান্য স্ট্রাকচারাল সিদ্ধান্ত প্রকল্পের ডিজাইন, সাইটের অবস্থা এবং প্রযোজ্য মান অনুযায়ী নির্ধারিত হবে।",

        secPlans: "বাড়ির প্ল্যান ও ডিজাইন ধারণা",

        planTitle1: "🏠 ছোট বাড়ি",
        planDesc1: "ছোট প্লট এবং ব্যবহারিক পারিবারিক প্রয়োজনের জন্য দক্ষ পরিকল্পনা।",

        planTitle2: "🏡 পারিবারিক বাড়ি",
        planDesc2: "শয়নকক্ষ, বসার ঘর, ডাইনিং, রান্নাঘর এবং সার্ভিসের ভারসাম্যপূর্ণ পরিকল্পনা।",

        planTitle3: "🏢 বহুতল বাড়ি",
        planDesc3: "G+1, G+2 এবং অন্যান্য বহুতল ভবনের পরিকল্পনা।",

        planTitle4: "📐 কাস্টম ডিজাইন",
        planDesc4: "গ্রাহকের প্রয়োজন অনুযায়ী যোগ্য পেশাদারের মাধ্যমে প্রকল্পভিত্তিক ডিজাইন তৈরি করা যায়।",

        secProjects: "আমাদের প্রকল্প",

        projectTitle1: "🏗 আবাসিক প্রকল্প",
        projectDesc1: "আবাসিক নির্মাণ, সংস্কার এবং উন্নয়নমূলক কাজ।",

        projectTitle2: "🏫 প্রাতিষ্ঠানিক প্রকল্প",
        projectDesc2: "স্কুল, প্রতিষ্ঠান এবং অন্যান্য সিভিল নির্মাণ কাজ।",

        projectTitle3: "🏢 বাণিজ্যিক প্রকল্প",
        projectDesc3: "বাণিজ্যিক ভবন এবং সংশ্লিষ্ট নির্মাণ কাজ।",

        projectTitle4: "🚧 অবকাঠামো কাজ",
        projectDesc4: "অবকাঠামো সম্পর্কিত সিভিল কাজ এবং প্রকল্প সমন্বয়।",

        portfolioTitle: "পোর্টফোলিও নোট:",

        portfolioNote:
            "নাখোদার প্রকৃত প্রকল্পের ছবি এবং বিস্তারিত তথ্য ভবিষ্যতে এখানে যোগ করা হবে।",

        secAbout: "নাখোদা কনস্ট্রাকশনস সম্পর্কে",

        aboutText:
            "একটি বাড়ি শুধু কংক্রিট ও স্টিল দিয়ে তৈরি হয় না। এটি জমি, পরিবার, বিশ্বাস এবং স্বপ্নের উপর গড়ে ওঠে। নাখোদা কনস্ট্রাকশনস ব্যবহারিক নির্মাণ পরিষেবা ও প্রকল্প সহায়তার মাধ্যমে নির্মাণকে আরও সহজে বোঝা, পরিকল্পনা করা এবং সমন্বয় করার লক্ষ্য রাখে।",

        visionLabel: "লক্ষ্য:",

        visionText:
            "ত্রিপুরা এবং তার বাইরে মানুষ ও প্রতিষ্ঠানের জন্য একটি বিশ্বস্ত নির্মাণ সহযোগী হিসেবে প্রতিষ্ঠিত হওয়া।",

        secContact: "আপনার নির্মাণ যাত্রা শুরু করুন",

        contactIntro:
            "আপনার প্রকল্প সম্পর্কে আমাদের জানান। নতুন বাড়ি, বাণিজ্যিক ভবন, প্রাতিষ্ঠানিক প্রকল্প, সংস্কার বা অন্য কোনো সিভিল কাজের পরিকল্পনা করলে নাখোদা কনস্ট্রাকশনসের সঙ্গে যোগাযোগ করুন।",

        contactTitle: "📞 নাখোদার সঙ্গে যোগাযোগ",

        phoneLabel: "ফোন:",
        emailLabel: "ইমেইল:",
        addressLabel: "অফিস:",

        addressText:
            "দুর্গা চৌমুহনী, আলবার্ট ক্লাবের কাছে, আগরতলা, পশ্চিম ত্রিপুরা",

        footerText:
            "নির্মাণ • পরিকল্পনা • তদারকি • অবকাঠামো"
    },


    kb: {

        brandName: "Nakhoda Constructions",

        brandTagline:
            "MERI MITTI • MERI ZAMEEN • MERA GHAR",

        heroTitle:
            "BUILD • PLAN • SUPERVISE<br>Nwngni Nokni Nwngni Jibonko Nokni.",

        mainIntro:
            "Nakhoda Constructions ni residential, commercial, institutional aro infrastructure construction khomokha — planning ni, estimation ni, execution aro finishing ni.",

        secServices: "Chini Services",

        srvTitle1: "🏠 Building Construction",
        srvDesc1: "Residential, commercial aro institutional building construction.",

        srvTitle2: "📐 Planning & Estimation",
        srvDesc2: "Concept planning, quantity estimation, budget aro project coordination.",

        srvTitle3: "🏗 Civil & RCC Works",
        srvDesc3: "Foundation, column, beam, slab, masonry, plaster aro civil works.",

        srvTitle4: "👷 Site Supervision",
        srvDesc4: "Labour coordination, progress monitoring aro quality supervision.",

        srvTitle5: "🔧 Renovation",
        srvDesc5: "Old building repair, extension, alteration aro remodelling.",

        srvTitle6: "🏢 Infrastructure Works",
        srvDesc6: "Institutional aro infrastructure-related civil construction works.",

        secCatalogue: "Construction Catalogue",

        catTitle1: "🏡 Residential",
        catDesc1: "<strong>House Designs:</strong> Modern concept, elevation aro practical house layout.",

        catTitle2: "🏗 Structure",
        catDesc2: "<strong>Foundation & RCC:</strong> Foundation, reinforcement, column, beam aro slab system.",

        catTitle3: "🧱 Masonry",
        catDesc3: "<strong>Brick & Block Work:</strong> Wall construction, mortar, alignment, opening aro curing.",

        catTitle4: "🎨 Finishing",
        catDesc4: "<strong>Flooring & Painting:</strong> Flooring, wall finish, painting aro final finishing.",

        catTitle5: "💧 Waterproofing",
        catDesc5: "<strong>Roof & Wet Areas:</strong> Roof, wet area aro moisture-control solution.",

        catTitle6: "⚡ Electrical & Plumbing",
        catDesc6: "<strong>Building Services:</strong> Electrical aro plumbing system construction sequence ni coordinate kora.",

        catTitle7: "🪟 Doors & Windows",
        catDesc7: "<strong>Openings:</strong> Door-window opening planning aro practical selection.",

        catTitle8: "🏢 Commercial & Institutional",
        catDesc8: "<strong>Facilities:</strong> Office, school aro institutional building reference.",

        secTechniques: "Building Techniques",

        techTitle1: "01 — Site & Setting Out",
        techDesc1: "Excavation agor site condition, level, boundary aro approved layout bujha important.",

        techTitle2: "02 — Foundation",
        techDesc2: "Soil condition aro structural design onujayi excavation aro foundation construction kora hoy.",

        techTitle3: "03 — RCC Frame",
        techDesc3: "Drawing onujayi reinforcement, formwork aro concrete diye structural member kora hoy.",

        techTitle4: "04 — Masonry",
        techDesc4: "Suitable brick/block, mortar, alignment, opening aro curing use kore wall construction kora hoy.",

        techTitle5: "05 — Services",
        techDesc5: "Electrical, plumbing, drainage aro other services finishing agote coordinate kora hoy.",

        techTitle6: "06 — Waterproofing",
        techDesc6: "Moisture-prone area ni suitable waterproofing system aro proper surface preparation use kora hoy.",

        techTitle7: "07 — Finishing",
        techDesc7: "Plaster, flooring, painting, door, window, fixture aro final quality checking complete kora hoy.",

        techTitle8: "08 — Handover",
        techDesc8: "Final inspection, cleaning, defect correction aro documentation complete kore handover kora hoy.",

        technicalNoteTitle: "Technical Note:",

        technicalNote:
            "I catalogue general information ni. Structural dimension, reinforcement, concrete grade, foundation type aro other structural decision project design, site condition aro applicable standard onujayi hobo.",

        secPlans: "House Plans & Design Concepts",

        planTitle1: "🏠 Compact Homes",
        planDesc1: "Small plot aro practical family requirement ni efficient planning.",

        planTitle2: "🏡 Family Homes",
        planDesc2: "Bedroom, living, dining, kitchen aro service ni balanced planning.",

        planTitle3: "🏢 Multi-Floor Homes",
        planDesc3: "G+1, G+2 aro other multi-level building planning.",

        planTitle4: "📐 Custom Concepts",
        planDesc4: "Customer requirement qualified professional ni project-specific design kora jabo.",

        secProjects: "Chini Projects",

        projectTitle1: "🏗 Residential Projects",
        projectDesc1: "Residential construction, renovation aro improvement works.",

        projectTitle2: "🏫 Institutional Projects",
        projectDesc2: "School, institutional aro other civil construction works.",

        projectTitle3: "🏢 Commercial Projects",
        projectDesc3: "Commercial building aro related construction works.",

        projectTitle4: "🚧 Infrastructure Works",
        projectDesc4: "Infrastructure-related civil work aro project coordination.",

        portfolioTitle: "Portfolio Note:",

        portfolioNote:
            "Nakhoda ni genuine project photo aro project details future ni ekhane add kora hobo.",

        secAbout: "Nakhoda Constructions somporke",

        aboutText:
            "Nok ekta concrete aro steel ni matro banano noy. Nok land, family, trust aro dream ni build hoy. Nakhoda Constructions practical construction service aro project support diye construction bujha, plan aro coordinate kora easy korte chai.",

        visionLabel: "Vision:",

        visionText:
            "Tripura aro Tripura-r bahire manush aro institution ni trusted construction partner hote chai.",

        secContact:
            "Nwngni Construction Journey Start Koro",

        contactIntro:
            "Nwngni project somporke amade janai. New house, commercial building, institutional project, renovation ba other civil work plan korle Nakhoda Constructions ni contact koro.",

        contactTitle: "📞 Nakhoda ni Contact",

        phoneLabel: "Phone:",
        emailLabel: "Email:",
        addressLabel: "Office:",

        addressText:
            "Durga Chowmuhani, Albert Club ni near, Agartala, West Tripura",

        footerText:
            "Construction • Planning • Supervision • Infrastructure"
    }

};


function switchLang(lang) {

    const t = translations[lang];

    if (!t) {
        return;
    }

    Object.keys(t).forEach(function(key) {

        const element = document.getElementById(key);

        if (element) {
            element.innerHTML = t[key];
        }

    });


    document.querySelectorAll(".lang-btn").forEach(function(button) {

        button.classList.remove("active");

    });


    const buttons = document.querySelectorAll(".lang-btn");

    buttons.forEach(function(button) {

        if (
            (lang === "en" && button.textContent.trim() === "English") ||
            (lang === "bn" && button.textContent.trim() === "বাংলা") ||
            (lang === "kb" && button.textContent.trim() === "Kokborok")
        ) {
            button.classList.add("active");
        }

    });

}


switchLang("en");

</script>

</body>
</html>
