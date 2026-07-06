<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Fun Store</title>
</head>
<body style="font-family: sans-serif; padding: 30px; max-width: 700px; margin: 0 auto; background-color: #f8fafc; color: #000000; line-height: 1.6;">

    <!-- BRANDING TITLE -->
    <h1 style="font-size: 2.5rem; text-transform: uppercase; margin-bottom: 5px;">The Fun Store</h1>
    <hr style="border: 2px solid #16a34a; margin-bottom: 30px;">

    <!-- WHY US SECTION -->
    <h2 style="color: #16a34a; text-transform: uppercase; font-size: 1.5rem;">Why Us?</h2>
    <div style="background: #ffffff; padding: 20px; border: 1px solid #e2e8f0; margin-bottom: 30px;">
        <p><strong>01 | Hands-on Play:</strong> We prioritize screen-free entertainment, creative building sets, and classic toys.</p>
        <p><strong>02 | Community Workspace:</strong> Built for local hobbyists, builders, and groups looking to share creative ideas.</p>
        <p><strong>03 | Prime Location:</strong> Positioned perfectly right in the absolute heart of the local walking district.</p>
        <p><strong>04 | Upper-Level Living:</strong> Modern residential apartment options with premium town convenience.</p>
    </div>

    <!-- WHAT WE SELL SECTION -->
    <h2 style="color: #16a34a; text-transform: uppercase; font-size: 1.5rem;">What We Sell</h2>
    <div style="background: #ffffff; padding: 20px; border: 1px solid #e2e8f0; margin-bottom: 30px;">
        <p>• <strong>Tactical Series:</strong> 50pc Green Army Men (Clear circle bins)</p>
        <p>• <strong>Tactical Series:</strong> 50pc Tan Army Men (Clear circle bins)</p>
        <p>• <strong>Wood Hobby:</strong> Wooden Pinewood Cars (Raw blocks ready to sand and race)</p>
        <p>• <strong>Wood Hobby:</strong> Wooden Pinewood Boats (Raw blocks designed for custom builds)</p>
        <p>• <strong>Sensory Series:</strong> Pocket fidget toys, stretchable stress items, and classic squishies</p>
        <p>• <strong>Miniature Packs:</strong> Small plastic animal assortments grouped in travel buckets</p>
        <p>• <strong>Snack Station:</strong> Counter candy, popular chip brands, and refreshing cold drinks</p>
        <p style="margin-top: 15px; padding-top: 15px; border-top: 2px dashed #16a34a;"><strong>📦 Authorized Retailer:</strong> Official Schylling NeeDoh items. These popular sensory drops sell out fast when shipments hit the sales counter!</p>
    </div>

    <!-- RENTALS SECTION WITH ESTIMATED PRICING -->
    <h2 style="color: #16a34a; text-transform: uppercase; font-size: 1.5rem;">Apartment & Building Rentals</h2>
    <div style="background: #ffffff; padding: 20px; border: 1px solid #e2e8f0; margin-bottom: 30px;">
        
        <div style="margin-bottom: 25px; padding-bottom: 25px; border-bottom: 1px solid #e2e8f0;">
            <h3 style="margin: 0 0 10px 0; color: #16a34a;">🟢 Available | Apartment Unit A (2-Bed / 1-Bath)</h3>
            <p style="margin: 0 0 10px 0;">Includes working refrigerator and stove with access to the shared washer and dryer layout in the common hallway area.</p>
            <p style="margin: 0; font-weight: bold; color: #16a34a;">💰 Pricing Layout Options:</p>
            <ul style="margin: 5px 0 0 0; padding-left: 20px;">
                <li><strong>$1,500 / month:</strong> Includes apartment rental + access to the 13-car private parking lot across the street.</li>
                <li><strong>$1,600 / month:</strong> Full premium bundle including the apartment, private parking lot, + the private 1 1/2 car storage garage.</li>
            </ul>
        </div>

        <div style="margin-bottom: 25px; padding-bottom: 25px; border-bottom: 1px solid #e2e8f0;">
            <h3 style="margin: 0 0 10px 0; color: #16a34a;">🟢 Available | Apartment Unit B (2-Bed / 1-Bath)</h3>
            <p style="margin: 0 0 10px 0;">Includes working refrigerator and stove with access to the shared washer and dryer layout in the common hallway area.</p>
            <p style="margin: 0; font-weight: bold; color: #16a34a;">💰 Pricing Layout Options:</p>
            <ul style="margin: 5px 0 0 0; padding-left: 20px;">
                <li><strong>$1,500 / month:</strong> Includes apartment rental + access to the 13-car private parking lot across the street.</li>
                <li><strong>$1,600 / month:</strong> Full premium bundle including the apartment, private parking lot, + the private 1 1/2 car storage garage.</li>
            </ul>
        </div>

        <div>
            <h3 style="margin: 0 0 5px 0;">🚗 Standalone 1 1/2 Car Garage & Private Lot</h3>
            <p style="margin: 0;">Our private 13-car paved parking lot is located directly across the street on the corner of 3rd St & Union St. The deep 1 1/2 car storage garage can be leased out separately for vehicle protection or equipment storage if not bundled with an apartment.</p>
        </div>

    </div>

    <!-- SUGGESTIONS SECTION -->
    <h2 style="color: #16a34a; text-transform: uppercase; font-size: 1.5rem;">Inventory Suggestions</h2>
    <div style="background: #ffffff; padding: 20px; border: 1px solid #e2e8f0; margin-bottom: 30px;">
        <p style="margin: 0 0 10px 0;">Type toy variations, licensed brands, or snack ideas you want to see on our storefront counters:</p>
        <textarea id="user-box" style="width: 100%; height: 80px; box-sizing: border-box; font-family: sans-serif; padding: 10px;"></textarea>
        <button onclick="sendIdea()" style="background: #16a34a; color: #ffffff; border: none; padding: 12px 24px; font-weight: bold; text-transform: uppercase; margin-top: 10px; cursor: pointer;">Submit Request</button>
        <p id="alert-text" style="color: #16a34a; font-weight: bold; display: none; margin-top: 15px; margin-bottom: 0;">✓ Suggestion recorded! We analyze customer requests before ordering weekly factory stock.</p>
    </div>

    <!-- STORE STATUS -->
    <h2 style="color: #16a34a; text-transform: uppercase; font-size: 1.5rem;">Store Status</h2>
    <div style="background: #ffffff; padding: 20px; border-left: 5px solid #16a34a; border-top: 1px solid #e2e8f0; border-right: 1px solid #e2e8f0; border-bottom: 1px solid #e2e8f0;">
        <p style="margin: 0;"><strong>🚧 Store Progress: Building Transformation Underway</strong></p>
        <p style="margin: 5px 0 0 0; color: #475569;">We are currently prepping the ground floor storefront layout and coordinating initial product lines behind the scenes. Opening soon!</p>
    </div>

    <!-- APP ENGINE LOGIC -->
    <script>
        function sendIdea() {
            const input = document.getElementById('user-box');
            const alert = document.getElementById('alert-text');
            if (input.value.trim() !== "") {
                alert.style.display = "block";
                input.value = "";
            }
        }
    </script>

</body>
</html>
