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
        nav { position: sticky; top: 0; background-color: #ffffff; padding: 20px; margin: 40px auto; max-width: 800px; border: 1px solid #16a34a; box-shadow: 0 4px 12px rgba(22, 163, 74, 0.05); z-index: 1000; box-sizing: border-box; display: flex; flex-direction: row; flex-wrap: wrap; justify-content: flex-start; align-items: center; gap: 15px 30px; }
        nav a { color: #000000; text-decoration: none; font-size: 1.1rem; font-weight: bold; text-transform: uppercase; display: inline-block; white-space: nowrap; }
        nav a:hover { color: #16a34a; }
        .page-container { max-width: 800px; margin: 0 auto; }
        .section-block { padding: 80px 0 20px 0; }
        .section-block h2 { font-size: 2rem; margin: 0 0 30px 0; text-transform: uppercase; border-bottom: 2px solid #16a34a; padding-bottom: 10px; }
        .why-us-item, .product-card, .rental-card, .suggestion-panel, .hours-panel, .team-panel { background-color: #ffffff; padding: 35px; border: 1px solid #e2e8f0; box-sizing: border-box; margin-bottom: 25px; }
        .rental-specs { margin: 15px 0 0 0; padding-left: 20px; color: #475569; }
        .rental-specs li { margin-bottom: 5px; }
    </style>
</head>
<body>

    <header>
        <h1>The Fun Store</h1>
    </header>

    <!-- REPAIRED COHESIVE FLEXIBLE HEADER LINING -->
    <nav>
        <a href="#why-us">Why Us</a>
        <a href="#what-we-sell">What We Sell</a>
        <a href="#rentals">Rentals</a>
        <a href="#contact">Contact</a>
        <a href="#suggestions">Suggestions</a>
    </nav>

    <div class="page-container">

        <!-- WHY US SECTION -->
        <section id="why-us" class="section-block">
            <h2>Why Us?</h2>
            <div class="why-us-item">
                <p style="margin: 0 0 10px 0;"><strong>01 | Hands-on Play:</strong> We prioritize screen-free entertainment, creative building sets, and classic toys.</p>
                <p style="margin: 0 0 10px 0;"><strong>02 | Community Workspace:</strong> Built for local hobbyists, builders, and groups looking to share creative ideas.</p>
                <p style="margin: 0 0 10px 0;"><strong>03 | Prime Location:</strong> Positioned perfectly right in the absolute heart of the local walking district.</p>
                <p style="margin: 0;"><strong>04 | Upper-Level Living:</strong> Modern residential apartment options with premium town convenience.</p>
            </div>
        </section>

        <!-- WHAT WE SELL SECTION -->
        <section id="what-we-sell" class="section-block">
            <h2>What We Sell</h2>
            <div class="product-card">
                <p>• <strong>Tactical Series:</strong> 50pc Green & Tan Army Men (Clear circle counter bins)</p>
                <p>• <strong>Sensory Series:</strong> Kawaii Squishy Toys & Pocket Fidgets (30pc assortment sets)</p>
                <p>• <strong>Sensory Series:</strong> Shape-Changing Telescopic Pop Tube Suction Cup Robots</p>
                <p>• <strong>Sensory Series:</strong> Stretchy Suction Cup People Fidget Toys</p>
                <p>• <strong>Miniature Packs:</strong> Realistic Plastic Insects & Mini Toy Bugs</p>
                <p>• <strong>Miniature Packs:</strong> 2-Inch Plastic Vinyl Toy Goldfish</p>
                <p>• <strong>Novelty Bins:</strong> Mini Bubble Wands & Party Supplies</p>
                <p>• <strong>Snack Station:</strong> Counter candy, popular chip brands, and refreshing cold drinks</p>
                <p style="margin-top: 15px; padding-top: 15px; border-top: 2px dashed #16a34a;"><strong>📦 Authorized Retailer:</strong> Official Schylling NeeDoh items. These popular sensory drops sell out fast when shipments hit the sales counter!</p>
            </div>
        </section>

        <!-- RENTALS SECTION -->
        <section id="rentals" class="section-block">
            <h2>Apartment & Building Rentals</h2>
            
            <div class="rental-card">
                <h3 style="margin: 0 0 10px 0; color: #16a34a;">🟢 Available Now | Apartment Unit A</h3>
                <p style="margin: 0 0 10px 0;">Complete upper-level 2-bedroom / 1-bath residential apartment. Includes working refrigerator and stove with access to the shared washer and dryer layout in the common area. Full access to our private 13-car paved parking lot across the street is included.</p>
                <p style="margin: 0; font-weight: bold; color: #16a34a;">💰 Monthly Rent Structure:</p>
                <ul class="rental-specs">
                    <li><strong>$850 / month:</strong> Base rent (All utility bills are included in this price)</li>
                    <li><strong>$1,050 / month:</strong> Combined premium bundle (Includes apartment, utilities, + private 1 1/2 car storage garage)</li>
                </ul>
            </div>

            <div class="rental-card">
                <h3 style="margin: 0 0 10px 0; color: #16a34a;">🟢 Available Now | Apartment Unit B</h3>
                <p style="margin: 0 0 10px 0;">Complete upper-level 2-bedroom / 1-bath residential apartment. Includes working refrigerator and stove with access to the shared washer and dryer layout in the common area. Full access to our private 13-car paved parking lot across the street is included.</p>
                <p style="margin: 0; font-weight: bold; color: #16a34a;">💰 Monthly Rent Structure:</p>
                <ul class="rental-specs">
                    <li><strong>$850 / month:</strong> Base rent (All utility bills are included in this price)</li>
                    <li><strong>$1,050 / month:</strong> Combined premium bundle (Includes apartment, utilities, + private 1 1/2 car storage garage)</li>
                </ul>
            </div>

            <div class="rental-card">
                <h3 style="margin: 0 0 10px 0; color: #000000;">🚗 Private 1 1/2 Car Storage Garage</h3>
                <p style="margin: 0 10px 10px 0;">Deep standalone storage garage located on-site. Features extra width inside that is perfect for secure vehicle parking, hobby workshops, or equipment storage.</p>
                <p style="margin: 0; font-weight: bold;">💰 Rent: $200 / month</p>
                <span style="font-size: 0.9rem; color: #475569;">(Can be leased separately or combined into an apartment contract bundle for $1,050/mo total)</span>
            </div>
        </section>

        <!-- CONTACT & NEWSLETTER SECTION -->
        <section id="contact" class="section-block">
            <h2>Contact & Newsletter</h2>
            <div class="suggestion-panel">
                <p style="margin: 0 0 10px 0; font-weight: bold; color: #16a34a;">📩 Standard Questions:</p>
                <p style="margin: 0 0 15px 0; color: #334155;">For any basic questions about our toys, counter snacks, or general apartment info, please use our main shop email:</p>
                <p style="margin: 0 0 25px 0; font-size: 1.1rem; font-weight: bold;">👉 <a href="mailto:thefunstoreshop@gmail.com" style="color: #16a34a; text-decoration: none;">thefunstoreshop@gmail.com</a></p>
                
                <p style="margin: 0 0 10px 0; font-weight: bold; color: #b91c1c;">⚠️ Urgent Backup Contact:</p>
                <p style="margin: 0 0 15px 0; color: #334155;">Please only use my personal email if you don't get a response from the business email or if you need an answer right away:</p>
                <p style="margin: 0 0 20px 0; font-size: 1.1rem; font-weight: bold;">👉 <a href="mailto:brycepheasant@icloud.com" style="color: #b91c1c; text-decoration: none;">brycepheasant@icloud.com</a></p>
                
                <div style="border-top: 2px dashed #16a34a; padding-top: 20px; margin-top: 20px;">
                    <h4 style="margin: 0 0 10px 0; text-transform: uppercase; letter-spacing: 0.5px;">📰 Join The Fun Club Newsletter</h4>
                    <p style="margin: 0 0 15px 0; color: #475569; font-size: 0.95rem;">Drop your email address below to join our update wire loop!</p>
                    <style type="text/css">@import url("https://mlcdn.com");</style>
                    <form action="https://mailerlite.com" method="post" target="_blank">
                        <input type="email" name="fields[email]" placeholder="Enter your email address..." required style="width: 100%; padding: 12px; border: 1px solid #cbd5e1; box-sizing: border-box; margin-bottom: 10px; background-color: #ffffff;">
                        <button type="submit" style="background-color: #16a34a; color: #ffffff; border: none; padding: 12px 28px; font-weight: bold; text-transform: uppercase; cursor: pointer;">Subscribe</button>
                    </form>
                </div>
            </div>
        </section>

        <!-- REPAIRED CLEAN TEAM SECTION -->
        <section id="team" class="section-block">
            <h2>Meet The Team</h2>
            <div class="team-panel">
                <p style="margin: 0 0 20px 0; color: #475569;">The friendly crew running our counter lanes and building property lines here on Main Street:</p>
                
                <div style="margin-bottom: 30px; padding-bottom: 25px; border-bottom: 1px dashed #e2e8f0;">
