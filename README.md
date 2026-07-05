<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Fun Store</title>
    <style>
        /* Smooth Scrolling Configuration */
        html {
            scroll-behavior: smooth;
        }

        /* Clean Background Setup */
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
            background-color: #f8fafc; /* Ultra-light backdrop for depth */
            color: #000000;
            margin: 0;
            padding: 0 20px 120px 20px;
            line-height: 1.6;
        }

        /* Header Branding */
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

        /* Sticky Navigation Bar with Green Highlight */
        nav {
            position: sticky;
            top: 0;
            background-color: #ffffff;
            padding: 20px 40px;
            margin: 40px auto;
            max-width: 800px;
            border: 1px solid #16a34a; /* Sharp green border */
            box-shadow: 0 4px 12px rgba(22, 163, 74, 0.05);
            z-index: 1000;
            box-sizing: border-box;
        }

        nav a {
            color: #000000;
            text-decoration: none;
            font-size: 1.15rem;
            font-weight: bold;
            display: inline-block;
            text-transform: uppercase;
            letter-spacing: 1px;
            margin-right: 35px;
        }

        nav a:hover {
            color: #16a34a; /* Turns green on hover */
        }

        /* Content Container Wrapper */
        .page-container {
            max-width: 800px;
            margin: 0 auto;
        }

        .section-block {
            padding: 80px 0 40px 0;
        }

        .section-block h2 {
            font-size: 2rem;
            margin-top: 0;
            margin-bottom: 30px;
            text-transform: uppercase;
            letter-spacing: 0.5px;
            border-bottom: 2px solid #16a34a; /* Clean green bottom line */
            padding-bottom: 10px;
        }

        /* Lists and Grids Base */
        .why-us-list, .product-grid {
            display: grid;
            grid-template-columns: 1fr;
            gap: 25px;
        }

        /* Responsive Columns for Inventory Menu */
        @media(min-width: 600px) {
            .product-grid {
                grid-template-columns: repeat(2, 1fr);
            }
        }

        .why-us-item, .product-card {
            background-color: #ffffff;
            padding: 35px;
            border: 1px solid #e2e8f0;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.01);
        }

        /* Vibrant Green Numbers & Badges */
        .why-us-number, .product-label {
            font-size: 2rem;
            font-weight: bold;
            display: block;
            margin-bottom: 5px;
            color: #16a34a; /* Bold professional green */
        }

        .product-label {
            font-size: 1.1rem;
            text-transform: uppercase;
            letter-spacing: 1px;
            margin-bottom: 10px;
        }

        .why-us-title, .product-title {
            font-size: 1.3rem;
            font-weight: bold;
            display: block;
            margin-bottom: 8px;
        }

        .why-us-item p, .product-card p {
            margin: 0;
            color: #334155;
        }
    </style>
</head>
<body>

    <!-- Main Header -->
    <header>
        <h1>The Fun Store</h1>
    </header>

    <!-- Navigation Menu Bar -->
    <nav>
        <a href="#why-us">Why Us</a>
        <a href="#what-we-sell">What We Sell</a>
    </nav>

    <!-- Scroll Content Area -->
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
                
                <!-- Item 1 -->
                <div class="product-card">
                    <span class="product-label">Tactical Series</span>
                    <span class="product-title">50pc Green Army Men Bucket</span>
                    <p>Classic military soldier figurines packaged in a durable storage bucket setup. Perfect for custom floor campaigns and strategic setups.</p>
                </div>

                <!-- Item 2 -->
                <div class="product-card">
                    <span class="product-label">Tactical Series</span>
                    <span class="product-title">50pc Tan Army Men Bucket</span>
                    <p>Desert-style military soldier figures matching our regulatory squad sizes, complete with a standalone storage bucket container.</p>
                </div>

                <!-- Item 3 -->
                <div class="product-card">
                    <span class="product-label">Wood Hobby</span>
                    <span class="product-title">Wooden Car Building Set</span>
                    <p>Pre-milled high-grade wooden vehicle bodies ready for custom sanding, track alignment shaping, and creative paint work.</p>
                </div>

                <!-- Item 4 -->
                <div class="product-card">
                    <span class="product-label">Wood Hobby</span>
                    <span class="product-title">Wooden Boat Assembly Set</span>
                    <p>Premium raw wood watercraft blanks designed for structural detailing, family engineering projects, and local fleet races.</p>
                </div>

                <!-- Item 5 -->
                <div class="product-card">
                    <span class="product-label">Sensory Series</span>
                    <span class="product-title">Squishy Toys & Fidgets</span>
                    <p>An assortment of satisfying tactile focus tools and stretchable stress-relief accessories to satisfy all sensory cravings.</p>
                </div>

                <!-- Item 6 -->
                <div class="product-card">
                    <span class="product-label">Miniature Packs</span>
                    <span class="product-title">Plastic Animal Buckets</span>
                    <p>Collectible miniature plastic animal figures arranged neatly inside travel buckets, great for creative dioramas or bedroom safaris.</p>
                </div>

                <!-- Item 7 (Full width feature drop card) -->
                <div class="product-card" style="grid-column: 1 / -1; max-width: 100%; border-left: 5px solid #16a34a;">
                    <span class="product-label" style="color: #16a34a; font-weight: 800;">🔥 Limited Release Drops</span>
                    <span class="product-title">Authentic NeeDoh Collections</span>
                    <p>Genuine, ultra-satisfying squeeze balls and rare drop designs. These specialized sensory favorites sell out incredibly fast, so keep an eye out for our upcoming drop schedules!</p>
                </div>

            </div>
        </section>

    </div>

</body>
</html>
