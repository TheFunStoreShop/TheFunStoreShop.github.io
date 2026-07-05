<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Fun Store</title>
    <style>
        /* Flat Minimalist All-White Style */
        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: sans-serif;
            background-color: #ffffff;
            color: #000000;
            margin: 0;
            padding: 0 40px 120px 40px;
            line-height: 1.6;
        }

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
        }

        /* Sticky Navigation Bar with One Button */
        nav {
            position: sticky;
            top: 0;
            background-color: #ffffff;
            padding: 25px 0;
            margin: 0 auto 40px auto;
            max-width: 800px;
            border-bottom: 2px solid #000000;
            z-index: 1000;
        }

        nav a {
            color: #000000;
            text-decoration: none;
            font-size: 1.15rem;
            font-weight: bold;
            display: inline-block;
        }

        nav a:hover {
            text-decoration: underline;
        }

        /* Content Container */
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
        }

        /* Why Us Layout Structure */
        .why-us-list {
            margin-top: 10px;
        }

        .why-us-item {
            margin-bottom: 50px;
            max-width: 650px;
        }

        .why-us-number {
            font-size: 2rem;
            font-weight: bold;
            display: block;
            margin-bottom: 5px;
            color: #000000;
        }

        .why-us-title {
            font-size: 1.3rem;
            font-weight: bold;
            display: block;
            margin-bottom: 8px;
        }
    </style>
</head>
<body>

    <!-- Business Name Header -->
    <header>
        <h1>The Fun Store</h1>
    </header>

    <!-- Top Sticky Navigation Bar -->
    <nav>
        <a href="#why-us">Why Us</a>
    </nav>

    <!-- Scroll Container -->
    <div class="page-container">

        <!-- ================= WHY US SECTION ================= -->
        <section id="why-us" class="section-block">
            <h2>Why Us?</h2>
            <div class="why-us-list">
                
                <div class="why-us-item">
                    <span class="why-us-number">01</span>
                    <span class="why-us-title">Hands-On Play</span>
                    <p style="margin: 0;">We prioritize creative, screen-free entertainment, carrying unique toy items and creative building sets that keep minds active and engaged.</p>
                </div>

                <div class="why-us-item">
                    <span class="why-us-number">02</span>
                    <span class="why-us-title">Community & Hobbies</span>
                    <p style="margin: 0;">Our storefront layout is built to support local hobby enthusiasts, makers, and groups looking to share ideas and engineer custom craft projects.</p>
                </div>

                <div class="why-us-item">
                    <span class="why-us-number">03</span>
                    <span class="why-us-title">Prime Main Street Location</span>
                    <p style="margin: 0;">Situated right in the heart of our community's main walking district, making it easy to drop in during your neighborhood travels.</p>
                </div>

                <div class="why-us-item">
                    <span class="why-us-number">04</span>
                    <span class="why-us-title">Upper-Level Spaces</span>
                    <p style="margin: 0;">Beyond retail, our building structure features beautifully kept, fully modernized options for both residential living and storage convenience.</p>
                </div>

            </div>
        </section>

    </div>

</body>
</html>
