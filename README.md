<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Fun Store</title>
    <style>
        html { scroll-behavior: smooth; }
        body { font-family: sans-serif; background-color: #f8fafc; color: #000000; margin: 0; padding: 0 20px 140px 20px; line-height: 1.6; }
        header { padding-top: 80px; max-width: 800px; margin: 0 auto; }
        header h1 { font-size: 2.8rem; margin: 0; text-transform: uppercase; font-weight: 800; }
        nav { position: sticky; top: 0; background-color: #ffffff; padding: 20px 40px; margin: 40px auto; max-width: 800px; border: 1px solid #16a34a; box-shadow: 0 4px 12px rgba(22, 163, 74, 0.05); z-index: 1000; box-sizing: border-box; display: flex; flex-wrap: wrap; gap: 15px 35px; }
        nav a { color: #000000; text-decoration: none; font-size: 1.1rem; font-weight: bold; text-transform: uppercase; }
        nav a:hover { color: #16a34a; }
        .page-container { max-width: 800px; margin: 0 auto; }
        .section-block { padding: 80px 0 20px 0; }
        .section-block h2 { font-size: 2rem; margin: 0 0 30px 0; text-transform: uppercase; border-bottom: 2px solid #16a34a; padding-bottom: 10px; }
        .why-us-list, .product-grid, .rental-grid { display: grid; grid-template-columns: 1fr; gap: 25px; }
        @media(min-width: 650px) { .product-grid, .rental-grid { grid-template-columns: repeat(2, 1fr); } }
        .why-us-item, .product-card, .rental-card, .suggestion-panel { background-color: #ffffff; padding: 35px; border: 1px solid #e2e8f0; box-sizing: border-box; }
        .why-us-number, .product-label, .rental-label { font-size: 2rem; font-weight: bold; display: block; color: #16a34a; }
        .product-label, .rental-label { font-size: 1.05rem; text-transform: uppercase; margin-bottom: 12px; }
        .status-badge { display: inline-block; padding: 4px 10px; font-size: 0.85rem; font-weight: bold; text-transform: uppercase; border-radius: 4px; margin-bottom: 15px; }
        .status-available { background-color: #dcfce7; color: #15803d; }
        .status-leased { background-color: #fee2e2; color: #b91c1c; }
        .why-us-title, .product-title, .rental-title { font-size: 1.3rem; font-weight: bold; display: block; margin-bottom: 8px; }
        .why-us-item p, .product-card p, .rental-card p, .suggestion-panel p { margin: 0; color: #334155; }
        .rental-specs { margin: 15px 0 0 0; padding-left: 20px; color: #475569; }
        .rental-specs li { margin-bottom: 5px; }
        .suggestion-input { width: 100%; height: 120px; padding: 15px; border: 1px solid #cbd5e1; font-size: 1.05rem; margin: 15px 0; box-sizing: border-box; }
        .suggestion-btn { background-color: #16a34a; color: #ffffff; border: none; padding: 12px 28px; font-size: 1rem; font-weight: bold; cursor: pointer; text-transform: uppercase; }
        .suggestion-btn:hover { background-color: #15803d; }
        .confirmation-msg { color: #16a34a; font-weight: bold; margin-top: 15px; display: none; }
    </style>
</head>
<body>
    <header><h1>The Fun Store</h1></header>
    <nav>
        <a href="#why-us">Why Us</a>
        <a href="#what-we-sell">What We Sell</a>
        <a href="#rentals">Rentals</a>
        <a href="#suggestions">Suggestions</a>
    </nav>
    <div class="page-container">
        <section id="why-us" class="section-block">
            <h2>Why Us?</h2>
            <div class="why-us-list">
                <div class="why-us-item">
                    <span class="why-us-number">01</span><span class="why-us-title">Hands-On Play</span>
                    <p>We prioritize creative, screen-free entertainment, carrying unique toy items and creative building sets.</p>
                </div>
                <div class="why-us-item">
                    <span class="why-us-number">02</span><span class="why-us-title">Community & Hobbies</span>
                    <p>Our storefront layout is built to support local hobby enthusiasts, makers, and groups looking to share ideas.</p>
                </div>
                <div class="why-us-item">
                    <span class="why-us-number">03</span><span class="why-us-title">Prime Main Street Location</span>
                    <p>Situated right in the heart of our community's main walking district, making it easy to drop in.</p>
                </div>
                <div class="why-us-item">
                    <span class="why-us-number">04</span><span class="why-us-title">Upper-Level Spaces</span>
                    <p>Beyond retail, our building structure features beautifully kept, fully modernized options for residential living.</p>
                </div>
            </div>
        </section>
        <section id="what-we-sell" class="section-block">
            <h2>What We Sell</h2>
            <div class="product-grid">
                <div class="product-card">
                    <span class="product-label">Tactical Series</span><span class="product-title">50pc Green Army Men Bucket</span>
                    <p>Classic military soldier figurines packaged in a durable storage bucket setup.</p>
                </div>
                <div class="product-card">
                    <span class="product-label">Tactical Series</span><span class="product-title">50pc Tan Army Men Bucket</span>
                    <p>Desert-style military soldier figures matching our regulatory squad sizes, complete with a bucket.</p>
                </div>
                <div class="product-card">
                    <span class="product-label">Wood Hobby</span><span class="product-title">Wooden Car Building Set</span>
                    <p>Pre-milled high-grade wooden vehicle bodies ready for custom sanding and creative paint work.</p>
                </div>
                <div class="product-card">
                    <span class="product-label">Wood Hobby</span><span class="product-title">Wooden Boat Assembly Set</span>
                    <p>Premium raw wood watercraft blanks designed for structural detailing and local fleet races.</p>
                </div>
                <div class="product-card">
                    <span class="product-label">Sensory Series</span><span class="product-title">Squishy Toys & Fidgets</span>
                    <p>An assortment of satisfying tactile focus tools and stretchable stress-relief accessories.</p>
                </div>
                <div class="product-card">
                    <span class="product-label">Miniature Packs</span><span class="product-title">Plastic Animal Buckets</span>
                    <p>Collectible miniature plastic animal figures arranged neatly inside travel buckets.</p>
                </div>
                <div class="product-card" style="grid-column: 1 / -1; max-width: 100%; border-left: 5px solid #16a34a;">
                    <span class="product-label" style="color: #16a34a; font-weight: 800;">🔥 Limited Release Drops</span><span class="product-title">Authentic NeeDoh Collections</span>
                    <p>Genuine, ultra-satisfying squeeze balls and rare drop designs. These sell out fast, keep an eye on our schedules!</p>
                </div>
            </div>
        </section>
        <section id="rentals" class="section-block">
            <h2>Apartment & Building Rentals</h2>
            <div class="rental-grid">
                <div class="rental-card">
                    <span class="rental-label">Residential Suite</span><span class="status-badge status-available">🟢 Available Now</span><span class="rental-title">Apartment Unit A</span>
                    <p>Spacious, fully renovated upper-level residential apartment space featuring premium structural layouts.</p>
                    <ul class="rental-specs">
                        <li>2 Bedrooms / 1 Full Bath</li>
                        <li>Beautifully restored hardwood floors</li>
                        <li>Water, trash, and heating utilities included</li>
                    </ul>
                </div>
                <div class="rental-card">
                    <span class="rental-label">Residential Suite</span><span class="status-badge status-leased">🔴 Currently Leased</span><span class="rental-title">Apartment Unit B</span>
                    <p>Modernized town-view studio apartment space sitting quietly above the ground level retail environment.</p>
                    <ul class="rental-specs">
                        <li>2 Bedrooms / 1 Full Bath</li>
                        <li>Updated kitchen cabinetry layouts</li>
                        <li>Private rear entrance access line</li>
                    </ul>
                </div>
                <div class="rental-card" style="grid-column: 1 / -1; max-width: 100%;">
                    <span class="rental-label">Secure Off-Street Units</span><span class="status-badge status-available">🟢 Available Now</span><span class="rental-title">Private 1.5-Car Storage Garage</span>
                    <p>Highly secure detached garage space accessible directly from the main premises area. Ideal for vehicle protection, hobby workshop layouts, or local contractor equipment storage.</p>
                </div>
            </div>
        </section>
        <section id="suggestions" class="section-block">
            <h2>Inventory Suggestions</h2>
            <div class="suggestion-panel">
                <p>Want a specific licensed toy brand or custom craft supply kit added to our physical storefront? Drop your product ideas directly below!</p>
                <textarea class="suggestion-input" id="user-textbox" placeholder="Type specific toy lines or fidget varieties you want to see..."></textarea>
                <button class="suggestion-btn" onclick="sendIdea()">Submit Request</button>
