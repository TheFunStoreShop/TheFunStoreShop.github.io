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

        /* Clean Premium Background Split */
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
            background-color: #f8fafc; /* Crisp, ultra-light background for depth */
            color: #000000;
            margin: 0;
            padding: 0 20px 120px 20px;
            line-height: 1.6;
        }

        /* Clean Header Block */
        header {
            padding-top: 80px;
            max-width: 800px;
            margin: 0 auto;
            text-align: left;
        }

        header h1 {
            font-size: 3rem;
            margin-bottom: 5px;
            text-transform: uppercase;
            letter-spacing: 2px;
            font-weight: 900;
        }

        /* Fixed Navigation Menu (Glides with you as you scroll) */
        nav {
            position: sticky;
            top: 0;
            background-color: #ffffff; /* Solid white bar cuts through the light gray backdrop */
            padding: 20px 40px;
            margin: 40px auto;
            max-width: 800px;
            border: 1px solid #000000; /* Bold minimalist outline */
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.03);
            z-index: 1000;
            box-sizing: border-box;
        }

        nav a {
            color: #000000;
            text-decoration: none;
            font-size: 1.1rem;
            font-weight: bold;
            display: inline-block;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        nav a:hover {
            text-decoration: underline;
        }

        /* Structural Content Box Wrapper */
        .page-container {
            max-width: 800px;
            margin: 0 auto;
        }

        .section-block {
            padding: 40px 0;
        }

        .section-block h2 {
            font-size: 1.8rem;
            margin-top: 0;
            margin-bottom: 35px;
            text-transform: uppercase;
            letter-spacing: 1px;
            font-weight: 800;
            border-bottom: 2px solid #000000;
            padding-bottom: 10px;
        }

        /* Structured Why Us Cards Grid Layout */
        .why-us-list {
            display: grid;
            grid-template-columns: 1fr;
            gap: 25px;
        }

        .why-us-item {
            background-color: #ffffff; /* Crisp white blocks that pop out from the light background */
            padding: 35px;
            border: 1px solid #e2e8f0; /* Soft perimeter line */
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.02);
            position: relative;
        }

        .why-us-number {
            font-size: 2.2rem;
            font-weight: 900;
            display: block;
            margin-bottom: 5px;
            color: #000000;
            letter-spacing: -1px;
        }

        .why-us-title {
            font-size: 1.3rem;
            font-weight: bold;
            display: block;
            margin-bottom: 10px;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }

        .why-us-item p {
            margin: 0;
            color: #334155; /* Slightly softer black for easier reading */
            font-size: 1.05rem;
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

    </div>

</body>
</html>
