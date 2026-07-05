<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Fun Store</title>
    <style>
        /* Smooth Scrolling Configurations */
        html {
            scroll-behavior: smooth;
        }

        /* Clean Background System Layout */
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
            background-color: #f8fafc; /* Crisp light-gray backdrop for panel depth */
            color: #000000;
            margin: 0;
            padding: 0 20px 140px 20px;
            line-height: 1.6;
        }

        /* Header Branding Frame */
        header {
            padding-top: 80px;
            max-width: 800px;
            margin: 0 auto;
        }

        header h1 {
            font-size: 2.8rem;
            margin-bottom: 5px;
            text-transform: uppercase;
            letter-spacing: 1px;
            font-weight: 800;
        }

        /* Sticky Navigation Bar with Professional Green Borders */
        nav {
            position: sticky;
            top: 0;
            background-color: #ffffff;
            padding: 20px 40px;
            margin: 40px auto;
            max-width: 800px;
            border: 1px solid #16a34a;
            box-shadow: 0 4px 12px rgba(22, 163, 74, 0.05);
            z-index: 1000;
            box-sizing: border-box;
            display: flex;
            flex-wrap: wrap;
            gap: 15px 35px;
        }

        nav a {
            color: #000000;
            text-decoration: none;
            font-size: 1.1rem;
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        nav a:hover {
            color: #16a34a;
        }

        /* Content Centering Area */
        .page-container {
            max-width: 800px;
            margin: 0 auto;
        }

        .section-block {
            padding: 80px 0 20px 0;
        }

        .section-block h2 {
            font-size: 2rem;
            margin-top: 0;
            margin-bottom: 30px;
            text-transform: uppercase;
            letter-spacing: 0.5px;
            border-bottom: 2px solid #16a34a;
            padding-bottom: 10px;
        }

        /* Layout Grid Environments */
        .why-us-list, .product-grid, .rental-grid {
            display: grid;
            grid-template-columns: 1fr;
            gap: 25px;
        }

        @media(min-width: 650px) {
            .product-grid, .rental-grid {
                grid-template-columns: repeat(2, 1fr);
            }
        }

        /* Premium White Structural Display Cards */
        .why-us-item, .product-card, .rental-card, .suggestion-panel {
            background-color: #ffffff;
            padding: 35px;
            border: 1px solid #e2e8f0;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.01);
            box-sizing: border-box;
        }

        /* Color Accent Classes */
        .why-us-number, .product-label, .rental-label {
            font-size: 2rem;
            font-weight: bold;
            display: block;
            color: #16a34a;
        }

        .product-label, .rental-label {
            font-size: 1.05rem;
            text-transform: uppercase;
            letter-spacing: 1px;
            margin-bottom: 12px;
        }

        .status-badge {
            display: inline-block;
            padding: 4px 10px;
            font-size: 0.85rem;
            font-weight: bold;
            text-transform: uppercase;
            border-radius: 4px;
            margin-bottom: 15px;
        }

        .status-available { background-color: #dcfce7; color: #15803d; }
        .status-leased { background-color: #fee2e2; color: #b91c1c; }

        .why-us-title, .product-title, .rental-title {
            font-size: 1.3rem;
            font-weight: bold;
            display: block;
            margin-bottom: 8px;
        }

        .why-us-item p, .product-card p, .rental-card p, .suggestion-panel p {
            margin: 0;
            color: #334155;
        }

        /* Bullet specs styling for apartments */
        .rental-specs {
            margin: 15px 0 0 0;
            padding-left: 20px;
            color: #475569;
        }

        .rental-specs li {
            margin-bottom: 5px;
        }

        /* Clean Interactive Textbox Sizing */
        .suggestion-input {
            width: 100%;
            height: 120px;
            padding: 15px;
            border: 1px solid #cbd5e1;
            font-size: 1.05rem;
            font-family: sans-serif;
            margin-top: 15px;
            margin-bottom: 15px;
            box-sizing: border-box;
            resize: vertical;
        }

        .suggestion-btn {
            background-color: #16a34a;
            color: #ffffff;
            border: none;
            padding: 12px 28px;
            font-size: 1rem;
            font-weight: bold;
            cursor: pointer;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }

        .suggestion-btn:hover {
            background-color: #15803d;
        }

        .confirmation-msg {
            color: #16a34a;
            font-weight: bold;
            margin-top: 15px;
            display: none;
        }
    </style>
</head>
<body>

    <!-- Main Branding Title Header -->
    <header>
        <h1>The Fun Store</h1>
    </header>

    <!-- Top Sticky Navigation Menus -->
    <nav>
        <a href="#why-us">Why Us</a>
        <a href="#what-we-sell">What We Sell</a>
        <a href="#rentals">Rentals</a>
        <a href="#suggestions">Suggestions</a>
    </nav>

    <!-- Full Vertical Layout Stack -->
    <div class="page-container">

        <!-- ================= WHY US SECTION ================= -->
        <section id="why-us" class="section-block">
            <h2>Why Us?</h2>
            <div class="why-us-list">
                
                <div class="why-us-item">
                    <span class="why-us-number">01</span>
                    <span class="why-us-title">Hands-On Play</span>
                    <p>We prioritize creative, screen-free entertainment, carrying unique toy items and creative building sets that keep minds active and engaged.</p>
                </div>

                <div class="why-us-item">
                    <span class="why-us-number">02</span>
                    <span class="why-us-title">Community & Hobbies</span>
                    <p>Our storefront layout is built to support local hobby enthusiasts, makers, and groups looking to share ideas and engineer custom craft projects.</p>
                </div>

                <div class="why-us-item">
                    <span class="why-us-number">03</span>
                    <span class="why-us-title">Prime Main Street Location</span>
                    <p>Situated right in the heart of our community's main walking district, making it easy to drop in during your neighborhood travels.</p>
                </div>

                <div class="why-us-item">
                    <span class="why-us-number">04</span>
                    <span class="why-us-title">Upper-Level Spaces</span>
                    <p>Beyond retail, our building structure features beautifully kept, fully modernized options for both residential living and storage convenience.</p>
                </div>

            </div>
        </section>

        <!-- ================= WHAT WE SELL SECTION ================= -->
        <section id="what-we-sell" class="section-block">
            <h2>What We Sell</h2>
            <div class="product-grid">
                
                <div class="product-card">
                    <span class="product-label">Tactical Series</span>
                    <span class="product-title">50pc Green Army Men Bucket</span>
                    <p>Classic military soldier figurines packaged in a durable storage bucket setup. Perfect for custom floor campaigns and strategic setups.</p>
                </div>

                <div class="product-card">
                    <span class="product-label">Tactical Series</span>
                    <span class="product-title">50pc Tan Army Men Bucket</span>
                    <p>Desert-style military soldier figures matching our regulatory squad sizes, complete with a standalone storage bucket container.</p>
                </div>

                <div class="product-card">
                    <span class="product-label">Wood Hobby</span>
                    <span class="product-title">Wooden Car Building Set</span>
                    <p>Pre-milled high-grade wooden vehicle bodies ready for custom sanding, track alignment shaping, and creative paint work.</p>
                </div>

                <div class="product-card">
                    <span class="product-label">Wood Hobby</span>
                    <span class="product-title">Wooden Boat Assembly Set</span>
                    <p>Premium raw wood watercraft blanks designed for structural detailing, family engineering projects, and local fleet races.</p>
                </div>

                <div class="product-card">
                    <span class="product-label">Sensory Series</span>
                    <span class="product-title">Squishy Toys & Fidgets</span>
                    <p>An assortment of satisfying tactile focus tools and stretchable stress-relief accessories to satisfy all sensory cravings.</p>
                </div>

                <div class="product-card">
                    <span class="product-label">Miniature Packs</span>
                    <span class="product-title">Plastic Animal Buckets</span>
                    <p>Collectible miniature plastic animal figures arranged neatly inside travel buckets, great for creative dioramas or bedroom safaris.</p>
                </div>

