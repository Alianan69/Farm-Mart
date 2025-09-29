
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Farm Mart - Fresh Local Products with Partial Payment Options</title>
<meta name="description" content="Browse our selection of fresh, local products. Items with partial payment collect only a portion upfront.">
<script src="https://cdn.tailwindcss.com/3.4.16"></script>
<script>tailwind.config={theme:{extend:{colors:{primary:'#22c55e',secondary:'#16a34a'},borderRadius:{'none':'0px','sm':'4px',DEFAULT:'8px','md':'12px','lg':'16px','xl':'20px','2xl':'24px','3xl':'32px','full':'9999px','button':'8px'}}}}</script>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/remixicon/4.6.0/remixicon.min.css">
<style>
:where([class^="ri-"])::before { content: "\f3c2"; }
</style>
</head>
<body class="bg-gray-50">
<header class="bg-white shadow-sm border-b border-gray-100">
<div class="w-full px-6 lg:px-8">
<div class="flex items-center justify-between h-16">
<div class="flex items-center space-x-3">
<div class="w-8 h-8 flex items-center justify-center">
<i class="ri-shopping-bag-line text-2xl text-primary"></i>
</div>
<div class="font-['Pacifico'] text-2xl text-gray-900">Farm Mart</div>
<span class="text-sm text-gray-500 ml-2">Partial Payment Plugin Demo</span>
</div>
<div class="flex items-center space-x-6">
<a href="#" class="text-gray-700 hover:text-primary transition-colors">Products</a>
<a href="#" class="flex items-center text-gray-700 hover:text-primary transition-colors">
<div class="w-5 h-5 flex items-center justify-center mr-1">
<i class="ri-user-line"></i>
</div>
Admin
</a>
<a href="#" class="flex items-center text-gray-700 hover:text-primary transition-colors">
<div class="w-5 h-5 flex items-center justify-center mr-1">
<i class="ri-shopping-cart-line"></i>
</div>
Cart
</a>
</div>
</div>
</div>
</header>
<main class="min-h-screen py-8">
<div class="max-w-7xl mx-auto px-6 lg:px-8">
<div class="mb-8">
<h1 class="text-3xl font-bold text-gray-900 mb-2">Farm Fresh Products</h1>
<p class="text-gray-600">Browse our selection of fresh, local products. Items with partial payment collect only a portion upfront.</p>
</div>
<div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6">
<div class="bg-white rounded-xl shadow-sm hover:shadow-md transition-shadow overflow-hidden">
<div class="p-6">
</div>
<div class="relative">
<div class="h-48 bg-gray-200" style="background-image: url('https://readdy.ai/api/search-image?query=Fresh%20organic%20red%20tomatoes%20on%20vine%20with%20green%20leaves%2C%20vibrant%20red%20color%2C%20farm%20fresh%20produce%2C%20natural%20lighting%2C%20clean%20white%20background%2C%20high%20quality%20vegetables%2C%20healthy%20organic%20food%2C%20garden%20fresh%20tomatoes%2C%20premium%20quality%20produce&width=400&height=300&seq=tomato001&orientation=landscape'); background-size: cover; background-position: center;"></div>
</div>
<div class="px-6 pb-6">
<h3 class="text-lg font-semibold text-gray-900 mb-2">Organic Tomatoes</h3>
<p class="text-sm text-gray-600 mb-3">Fresh organic tomatoes from local farms</p>
<div class="flex items-center justify-between mb-4">
<span class="text-sm text-gray-500">Full Price</span>
<span class="text-lg font-bold text-gray-900">$4.99</span>
</div>
<button class="w-full bg-gray-900 text-white py-3 !rounded-button hover:bg-gray-800 transition-colors text-sm font-medium whitespace-nowrap flex items-center justify-center">
<div class="w-4 h-4 flex items-center justify-center mr-2">
<i class="ri-shopping-cart-line text-sm"></i>
</div>
Add to Cart
</button>
</div>
</div>
<div class="bg-white rounded-xl shadow-sm hover:shadow-md transition-shadow overflow-hidden">
<div class="p-6 relative">
<div class="absolute top-3 right-3 bg-primary text-white px-2 py-1 rounded text-xs font-medium">
Partial Payment
</div>
</div>
<div class="relative">
<div class="h-48 bg-gray-200" style="background-image: url('https://readdy.ai/api/search-image?query=Fresh%20free%20range%20chicken%20eggs%20in%20wooden%20crate%2C%20brown%20and%20white%20eggs%2C%20farm%20fresh%20organic%20eggs%2C%20natural%20lighting%2C%20rustic%20wooden%20background%2C%20healthy%20protein%20source%2C%20premium%20quality%20eggs%2C%20countryside%20farm%20produce&width=400&height=300&seq=eggs001&orientation=landscape'); background-size: cover; background-position: center;"></div>
</div>
<div class="px-6 pb-6">
<h3 class="text-lg font-semibold text-gray-900 mb-2">Free Range Eggs</h3>
<p class="text-sm text-gray-600 mb-3">Farm fresh free range eggs, dozen</p>
<div class="flex items-center justify-between mb-2">
<span class="text-sm text-gray-500">Full Price</span>
<span class="text-lg font-bold text-gray-900">$6.99</span>
</div>
<div class="flex items-center justify-between mb-4">
<span class="text-sm text-primary">Collect Now</span>
<span class="text-sm font-medium text-primary">$5.00</span>
</div>
<button class="w-full bg-primary text-white py-3 !rounded-button hover:bg-green-600 transition-colors text-sm font-medium whitespace-nowrap flex items-center justify-center">
<div class="w-4 h-4 flex items-center justify-center mr-2">
<i class="ri-shopping-cart-line text-sm"></i>
</div>
Add to Cart
</button>
</div>
</div>
<div class="bg-white rounded-xl shadow-sm hover:shadow-md transition-shadow overflow-hidden">
<div class="p-6 relative">
<div class="absolute top-3 right-3 bg-primary text-white px-2 py-1 rounded text-xs font-medium">
Partial Payment
</div>
</div>
<div class="relative">
<div class="h-48 bg-gray-200" style="background-image: url('https://readdy.ai/api/search-image?query=Pure%20raw%20honey%20in%20glass%20jar%20with%20wooden%20dipper%2C%20golden%20amber%20color%2C%20natural%20organic%20honey%2C%20clean%20white%20background%2C%20premium%20quality%20honey%2C%20local%20beekeepers%20product%2C%20healthy%20natural%20sweetener%2C%20artisanal%20honey%20jar&width=400&height=300&seq=honey001&orientation=landscape'); background-size: cover; background-position: center;"></div>
</div>
<div class="px-6 pb-6">
<h3 class="text-lg font-semibold text-gray-900 mb-2">Raw Honey</h3>
<p class="text-sm text-gray-600 mb-3">Pure raw honey from local beekeepers</p>
<div class="flex items-center justify-between mb-2">
<span class="text-sm text-gray-500">Full Price</span>
<span class="text-lg font-bold text-gray-900">$12.99</span>
</div>
<div class="flex items-center justify-between mb-4">
<span class="text-sm text-primary">Collect Now</span>
<span class="text-sm font-medium text-primary">$5.00</span>
</div>
<button class="w-full bg-primary text-white py-3 !rounded-button hover:bg-green-600 transition-colors text-sm font-medium whitespace-nowrap flex items-center justify-center">
<div class="w-4 h-4 flex items-center justify-center mr-2">
<i class="ri-shopping-cart-line text-sm"></i>
</div>
Add to Cart
</button>
</div>
</div>
<div class="bg-white rounded-xl shadow-sm hover:shadow-md transition-shadow overflow-hidden">
<div class="p-6">
</div>
<div class="relative">
<div class="h-48 bg-gray-200" style="background-image: url('https://readdy.ai/api/search-image?query=Premium%20grass%20fed%20beef%20steak%20with%20marbling%2C%20raw%20red%20meat%2C%20butcher%20shop%20quality%2C%20clean%20white%20background%2C%20high%20quality%20beef%20cuts%2C%20organic%20grass%20fed%20meat%2C%20premium%20protein%20source%2C%20fresh%20butcher%20meat&width=400&height=300&seq=beef001&orientation=landscape'); background-size: cover; background-position: center;"></div>
</div>
<div class="px-6 pb-6">
<h3 class="text-lg font-semibold text-gray-900 mb-2">Grass Fed Beef</h3>
<p class="text-sm text-gray-600 mb-3">Premium grass fed beef, 1lb</p>
<div class="flex items-center justify-between mb-4">
<span class="text-sm text-gray-500">Full Price</span>
<span class="text-lg font-bold text-gray-900">$18.99</span>
</div>
<button class="w-full bg-gray-900 text-white py-3 !rounded-button hover:bg-gray-800 transition-colors text-sm font-medium whitespace-nowrap flex items-center justify-center">
<div class="w-4 h-4 flex items-center justify-center mr-2">
<i class="ri-shopping-cart-line text-sm"></i>
</div>
Add to Cart
</button>
</div>
</div>
<div class="bg-white rounded-xl shadow-sm hover:shadow-md transition-shadow overflow-hidden">
<div class="p-6">
</div>
<div class="relative">
<div class="h-48 bg-gray-200" style="background-image: url('https://readdy.ai/api/search-image?query=Fresh%20organic%20carrots%20with%20green%20tops%2C%20bright%20orange%20color%2C%20farm%20fresh%20vegetables%2C%20clean%20white%20background%2C%20healthy%20root%20vegetables%2C%20organic%20produce%2C%20garden%20fresh%20carrots%2C%20natural%20lighting%2C%20premium%20quality%20vegetables&width=400&height=300&seq=carrots001&orientation=landscape'); background-size: cover; background-position: center;"></div>
</div>
<div class="px-6 pb-6">
<h3 class="text-lg font-semibold text-gray-900 mb-2">Organic Carrots</h3>
<p class="text-sm text-gray-600 mb-3">Fresh organic carrots with greens</p>
<div class="flex items-center justify-between mb-4">
<span class="text-sm text-gray-500">Full Price</span>
<span class="text-lg font-bold text-gray-900">$3.49</span>
</div>
<button class="w-full bg-gray-900 text-white py-3 !rounded-button hover:bg-gray-800 transition-colors text-sm font-medium whitespace-nowrap flex items-center justify-center">
<div class="w-4 h-4 flex items-center justify-center mr-2">
<i class="ri-shopping-cart-line text-sm"></i>
</div>
Add to Cart
</button>
</div>
</div>
<div class="bg-white rounded-xl shadow-sm hover:shadow-md transition-shadow overflow-hidden">
<div class="p-6 relative">
<div class="absolute top-3 right-3 bg-primary text-white px-2 py-1 rounded text-xs font-medium">
Partial Payment
</div>
</div>
<div class="relative">
<div class="h-48 bg-gray-200" style="background-image: url('https://readdy.ai/api/search-image?query=Fresh%20organic%20spinach%20leaves%20in%20bundle%2C%20dark%20green%20leafy%20vegetables%2C%20farm%20fresh%20greens%2C%20clean%20white%20background%2C%20healthy%20organic%20produce%2C%20nutritious%20leafy%20greens%2C%20garden%20fresh%20spinach%2C%20premium%20quality%20vegetables&width=400&height=300&seq=spinach001&orientation=landscape'); background-size: cover; background-position: center;"></div>
</div>
<div class="px-6 pb-6">
<h3 class="text-lg font-semibold text-gray-900 mb-2">Fresh Spinach</h3>
<p class="text-sm text-gray-600 mb-3">Organic fresh spinach leaves</p>
<div class="flex items-center justify-between mb-2">
<span class="text-sm text-gray-500">Full Price</span>
<span class="text-lg font-bold text-gray-900">$4.29</span>
</div>
<div class="flex items-center justify-between mb-4">
<span class="text-sm text-primary">Collect Now</span>
<span class="text-sm font-medium text-primary">$2.50</span>
</div>
<button class="w-full bg-primary text-white py-3 !rounded-button hover:bg-green-600 transition-colors text-sm font-medium whitespace-nowrap flex items-center justify-center">
<div class="w-4 h-4 flex items-center justify-center mr-2">
<i class="ri-shopping-cart-line text-sm"></i>
</div>
Add to Cart
</button>
</div>
</div>
<div class="bg-white rounded-xl shadow-sm hover:shadow-md transition-shadow overflow-hidden">
<div class="p-6">
</div>
<div class="relative">
<div class="h-48 bg-gray-200" style="background-image: url('https://readdy.ai/api/search-image?query=Fresh%20whole%20milk%20in%20glass%20bottle%2C%20creamy%20white%20dairy%20product%2C%20farm%20fresh%20milk%2C%20clean%20white%20background%2C%20organic%20dairy%20product%2C%20premium%20quality%20milk%2C%20local%20dairy%20farm%2C%20healthy%20calcium%20rich%20beverage&width=400&height=300&seq=milk001&orientation=landscape'); background-size: cover; background-position: center;"></div>
</div>
<div class="px-6 pb-6">
<h3 class="text-lg font-semibold text-gray-900 mb-2">Farm Fresh Milk</h3>
<p class="text-sm text-gray-600 mb-3">Whole milk from local dairy farm</p>
<div class="flex items-center justify-between mb-4">
<span class="text-sm text-gray-500">Full Price</span>
<span class="text-lg font-bold text-gray-900">$5.49</span>
</div>
<button class="w-full bg-gray-900 text-white py-3 !rounded-button hover:bg-gray-800 transition-colors text-sm font-medium whitespace-nowrap flex items-center justify-center">
<div class="w-4 h-4 flex items-center justify-center mr-2">
<i class="ri-shopping-cart-line text-sm"></i>
</div>
Add to Cart
</button>
</div>
</div>
<div class="bg-white rounded-xl shadow-sm hover:shadow-md transition-shadow overflow-hidden">
<div class="p-6 relative">
<div class="absolute top-3 right-3 bg-primary text-white px-2 py-1 rounded text-xs font-medium">
Partial Payment
</div>
</div>
<div class="relative">
<div class="h-48 bg-gray-200" style="background-image: url('https://readdy.ai/api/search-image?query=Artisanal%20sourdough%20bread%20loaf%20with%20crusty%20exterior%2C%20golden%20brown%20crust%2C%20fresh%20baked%20bread%2C%20clean%20white%20background%2C%20handmade%20bakery%20product%2C%20organic%20flour%20bread%2C%20traditional%20sourdough%2C%20premium%20quality%20bread&width=400&height=300&seq=bread001&orientation=landscape'); background-size: cover; background-position: center;"></div>
</div>
<div class="px-6 pb-6">
<h3 class="text-lg font-semibold text-gray-900 mb-2">Sourdough Bread</h3>
<p class="text-sm text-gray-600 mb-3">Artisanal sourdough bread loaf</p>
<div class="flex items-center justify-between mb-2">
<span class="text-sm text-gray-500">Full Price</span>
<span class="text-lg font-bold text-gray-900">$7.99</span>
</div>
<div class="flex items-center justify-between mb-4">
<span class="text-sm text-primary">Collect Now</span>
<span class="text-sm font-medium text-primary">$4.00</span>
</div>
<button class="w-full bg-primary text-white py-3 !rounded-button hover:bg-green-600 transition-colors text-sm font-medium whitespace-nowrap flex items-center justify-center">
<div class="w-4 h-4 flex items-center justify-center mr-2">
<i class="ri-shopping-cart-line text-sm"></i>
</div>
Add to Cart
</button>
</div>
</div>
</div>
<div class="mt-12 bg-white rounded-xl p-8 shadow-sm">
<h2 class="text-2xl font-bold text-gray-900 mb-4">About Partial Payment</h2>
<div class="grid md:grid-cols-3 gap-8">
<div class="flex items-start space-x-4">
<div class="w-12 h-12 flex items-center justify-center bg-primary bg-opacity-10 rounded-lg flex-shrink-0">
<i class="ri-money-dollar-circle-line text-xl text-primary"></i>
</div>
<div>
<h3 class="font-semibold text-gray-900 mb-2">Flexible Payments</h3>
<p class="text-sm text-gray-600">Pay a portion upfront and complete the payment when you receive your order.</p>
</div>
</div>
<div class="flex items-start space-x-4">
<div class="w-12 h-12 flex items-center justify-center bg-primary bg-opacity-10 rounded-lg flex-shrink-0">
<i class="ri-shield-check-line text-xl text-primary"></i>
</div>
<div>
<h3 class="font-semibold text-gray-900 mb-2">Secure Process</h3>
<p class="text-sm text-gray-600">Your payment information is protected with industry-standard security measures.</p>
</div>
</div>
<div class="flex items-start space-x-4">
<div class="w-12 h-12 flex items-center justify-center bg-primary bg-opacity-10 rounded-lg flex-shrink-0">
<i class="ri-truck-line text-xl text-primary"></i>
</div>
<div>
<h3 class="font-semibold text-gray-900 mb-2">Fresh Delivery</h3>
<p class="text-sm text-gray-600">All products are delivered fresh from local farms directly to your doorstep.</p>
</div>
</div>
</div>
</div>
</div>
</main>
<footer class="bg-white border-t border-gray-200 py-8 mt-16">
<div class="max-w-7xl mx-auto px-6 lg:px-8">
<div class="flex flex-col md:flex-row justify-between items-center">
<div class="flex items-center space-x-3 mb-4 md:mb-0">
<div class="w-6 h-6 flex items-center justify-center">
<i class="ri-shopping-bag-line text-xl text-primary"></i>
</div>
<div class="font-['Pacifico'] text-xl text-gray-900">Farm Mart</div>
</div>
<div class="flex items-center space-x-6 text-sm text-gray-600">
<a href="#" class="hover:text-primary transition-colors">Privacy Policy</a>
<a href="#" class="hover:text-primary transition-colors">Terms of Service</a>
<a href="#" class="hover:text-primary transition-colors">Contact Support</a>
</div>
</div>
<div class="mt-6 pt-6 border-t border-gray-200 text-center text-sm text-gray-500">
© 2025 Farm Mart. All rights reserved. Partial Payment Plugin Demo.
</div>
</div>
</footer>
<script id="cart-functionality">
document.addEventListener('DOMContentLoaded', function() {
const addToCartButtons = document.querySelectorAll('button[class*="bg-primary"], button[class*="bg-gray-900"]');
addToCartButtons.forEach(button => {
button.addEventListener('click', function() {
const productCard = this.closest('.bg-white');
const productName = productCard.querySelector('h3').textContent;
const isPartialPayment = productCard.querySelector('.bg-primary.text-white.px-2.py-1') !== null;
const originalText = this.innerHTML;
this.innerHTML = '<div class="w-4 h-4 flex items-center justify-center mr-2"><i class="ri-check-line text-sm"></i></div>Added!';
this.classList.add('opacity-75');
setTimeout(() => {
this.innerHTML = originalText;
this.classList.remove('opacity-75');
}, 1500);
console.log(`Added ${productName} to cart. Partial payment: ${isPartialPayment}`);
});
});
});
</script>
<script>
    !function (t, e) { var o, n, p, r; e.__SV || (window.posthog = e, e._i = [], e.init = function (i, s, a) { function g(t, e) { var o = e.split("."); 2 == o.length && (t = t[o[0]], e = o[1]), t[e] = function () { t.push([e].concat(Array.prototype.slice.call(arguments, 0))) } } (p = t.createElement("script")).type = "text/javascript", p.crossOrigin = "anonymous", p.async = !0, p.src = s.api_host.replace(".i.posthog.com", "-assets.i.posthog.com") + "/static/array.js", (r = t.getElementsByTagName("script")[0]).parentNode.insertBefore(p, r); var u = e; for (void 0 !== a ? u = e[a] = [] : a = "posthog", u.people = u.people || [], u.toString = function (t) { var e = "posthog"; return "posthog" !== a && (e += "." + a), t || (e += " (stub)"), e }, u.people.toString = function () { return u.toString(1) + ".people (stub)" }, o = "init capture register register_once register_for_session unregister unregister_for_session getFeatureFlag getFeatureFlagPayload isFeatureEnabled reloadFeatureFlags updateEarlyAccessFeatureEnrollment getEarlyAccessFeatures on onFeatureFlags onSessionId getSurveys getActiveMatchingSurveys renderSurvey canRenderSurvey getNextSurveyStep identify setPersonProperties group resetGroups setPersonPropertiesForFlags resetPersonPropertiesForFlags setGroupPropertiesForFlags resetGroupPropertiesForFlags reset get_distinct_id getGroups get_session_id get_session_replay_url alias set_config startSessionRecording stopSessionRecording sessionRecordingStarted captureException loadToolbar get_property getSessionProperty createPersonProfile opt_in_capturing opt_out_capturing has_opted_in_capturing has_opted_out_capturing clear_opt_in_out_capturing debug".split(" "), n = 0; n < o.length; n++)g(u, o[n]); e._i.push([i, s, a]) }, e.__SV = 1) }(document, window.posthog || []);
    posthog.init('phc_t9tkQZJiyi2ps9zUYm8TDsL6qXo4YmZx0Ot5rBlAlEd', {
        api_host: 'https://us.i.posthog.com',
        autocapture: false,
        capture_pageview: false,
        capture_pageleave: false,
        capture_performance: {
            web_vitals: false,
        },
        rageclick: false,
    })
</script>
</body>
</html>
