<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Premium Subscriptions | Instant Checkout</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body { background-color: #050505; color: #e5e5e5; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; }
        .card { background: #111; border: 1px solid #222; border-radius: 15px; transition: 0.3s; }
        .card:hover { border-color: #3b82f6; box-shadow: 0 0 20px rgba(59, 130, 246, 0.2); }
    </style>
</head>
<body class="p-4 md:p-10">

    <div class="max-w-4xl mx-auto">
        <h1 class="text-3xl font-bold text-center text-blue-500 mb-2">Premium Store</h1>
        <p class="text-center text-gray-500 mb-10">Instant Payment & Automated Processing</p>

        <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
            
            <div class="card p-6">
                <h2 class="text-2xl font-semibold mb-2">YouTube Premium</h2>
                <ul class="text-sm text-gray-400 mb-6 space-y-1">
                    <li>✓ No Ads</li>
                    <li>✓ Background Play</li>
                    <li>✓ YouTube Music Included</li>
                </ul>
                
                <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
                    <input type="hidden" name="cmd" value="_xclick">
                    <input type="hidden" name="business" value="YOUR_EMAIL@GMAIL.COM"> <input type="hidden" name="item_name" value="YouTube Premium Subscription">
                    <input type="hidden" name="currency_code" value="USD">
                    <input type="hidden" name="amount" value="5.00">
                    
                    <label class="block text-xs font-bold uppercase text-gray-500 mb-1">Select Method:</label>
                    <select name="os0" class="w-full bg-black border border-gray-700 p-2 rounded mb-4 text-sm">
                        <option value="I will provide login">I will provide my Gmail/Pass</option>
                        <option value="Create account for me">Create a new account for me</option>
                    </select>

                    <label class="block text-xs font-bold uppercase text-gray-500 mb-1">Your Gmail Address:</label>
                    <input type="email" name="custom" required placeholder="example@gmail.com" class="w-full bg-black border border-gray-700 p-2 rounded mb-6 text-sm">

                    <button type="submit" class="w-full bg-blue-600 hover:bg-blue-700 text-white font-bold py-3 rounded-lg transition">
                        Pay with PayPal
                    </button>
                </form>
            </div>

            <div class="card p-6">
                <h2 class="text-2xl font-semibold mb-2">Instagram Growth</h2>
                <ul class="text-sm text-gray-400 mb-6 space-y-1">
                    <li>✓ Real Followers</li>
                    <li>✓ High Quality Likes</li>
                    <li>✓ Instant Views</li>
                </ul>
                
                <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
                    <input type="hidden" name="cmd" value="_xclick">
                    <input type="hidden" name="business" value="YOUR_EMAIL@GMAIL.COM">
                    <input type="hidden" name="item_name" value="Instagram Growth Pack">
                    <input type="hidden" name="currency_code" value="USD">
                    <input type="hidden" name="amount" value="10.00">
                    
                    <label class="block text-xs font-bold uppercase text-gray-500 mb-1">Target Username:</label>
                    <input type="text" name="custom" required placeholder="@username" class="w-full bg-black border border-gray-700 p-2 rounded mb-10 text-sm">

                    <button type="submit" class="w-full bg-purple-600 hover:bg-purple-700 text-white font-bold py-3 rounded-lg transition">
                        Pay with PayPal
                    </button>
                </form>
            </div>

        </div>
    </div>

</body>
</html>
