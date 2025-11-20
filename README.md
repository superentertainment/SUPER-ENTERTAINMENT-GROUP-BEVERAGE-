# SUPER-ENTERTAINMENT-GROUP-BEVERAGE-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Super Entertainment Group Beverage - Premium Beverage Catering</title>
    
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Load Lucide Icons -->
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        /* Define custom colors and font for the golden theme */
        :root {
            --color-primary-dark: #1f2937; /* Dark Slate */
            --color-secondary-gold: #f5b041; /* Vibrant Gold */
            --color-accent-teal: #48c9b0; /* Bright Teal/Mint */
        }
        .bg-primary-dark { background-color: var(--color-primary-dark); }
        .text-primary-dark { color: var(--color-primary-dark); }
        .bg-secondary-gold { background-color: var(--color-secondary-gold); }
        .text-secondary-gold { color: var(--color-secondary-gold); }
        .bg-accent-teal { background-color: var(--color-accent-teal); }
        .text-accent-teal { color: var(--color-accent-teal); }
        .border-accent-teal { border-color: var(--color-accent-teal); }

        /* Custom scroll behavior for smooth navigation */
        html {
            scroll-behavior: smooth;
        }

        /* Set the Inter font globally */
        body {
            font-family: 'Inter', sans-serif;
        }

        /* Styling for the custom logo */
        .header-logo {
            height: 60px; /* Adjust height as needed */
            width: auto;
        }

        /* Hide scrollbar but allow scrolling */
        body {
            -ms-overflow-style: none;  /* IE and Edge */
            scrollbar-width: none;  /* Firefox */
        }
        body::-webkit-scrollbar {
            display: none; /* Chrome, Safari, Opera */
        }
    </style>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        'primary-dark': 'var(--color-primary-dark)',
                        'secondary-gold': 'var(--color-secondary-gold)',
                        'accent-teal': 'var(--color-accent-teal)',
                    },
                },
            },
        }
    </script>
</head>
<body class="bg-primary-dark text-gray-100 min-h-screen">

    <!-- Navigation Bar -->
    <header class="sticky top-0 z-50 bg-primary-dark/95 shadow-lg border-b border-gray-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-20">
                <!-- Logo: Image -->
                <a href="#" class="flex items-center">
                    <img src="https://i.imgur.com/uR1S94f.png" alt="Super Entertainment Group Logo" class="header-logo">
                </a>
                
                <!-- Desktop Menu -->
                <nav id="main-navigation" class="hidden md:flex space-x-8 font-semibold">
                    <a href="#hero" class="text-gray-300 hover:text-secondary-gold transition duration-300">Home</a>
                    <a href="#about" class="text-gray-300 hover:text-secondary-gold transition duration-300">About</a>
                    <a href="#services" class="text-gray-300 hover:text-secondary-gold transition duration-300">Services</a>
                    <a href="#creator" class="text-gray-300 hover:text-secondary-gold transition duration-300">Creator✨</a>
                    <a href="#packages" class="text-gray-300 hover:text-secondary-gold transition duration-300">Packages</a>
                    <a href="#contact" class="py-2 px-4 rounded-full bg-accent-teal text-primary-dark hover:bg-secondary-gold hover:text-primary-dark transition duration-300">Book Now</a>
                </nav>

                <!-- Mobile Menu Button -->
                <button id="mobile-menu-button" class="md:hidden p-2 rounded-lg text-secondary-gold hover:bg-gray-800 transition duration-200" aria-label="Toggle navigation">
                    <span data-lucide="menu" class="w-6 h-6"></span>
                </button>
            </div>
        </div>

        <!-- Mobile Menu Content -->
        <div id="mobile-nav-content" class="hidden md:hidden bg-primary-dark border-t border-gray-800">
            <div class="px-2 pt-2 pb-3 space-y-1 sm:px-3 flex flex-col items-center">
                <a href="#hero" class="block py-2 text-center w-full rounded-md text-gray-300 hover:bg-gray-800 hover:text-secondary-gold">Home</a>
                <a href="#about" class="block py-2 text-center w-full rounded-md text-gray-300 hover:bg-gray-800 hover:text-secondary-gold">About</a>
                <a href="#services" class="block py-2 text-center w-full rounded-md text-gray-300 hover:bg-gray-800 hover:text-secondary-gold">Services</a>
                <a href="#creator" class="block py-2 text-center w-full rounded-md text-gray-300 hover:bg-gray-800 hover:text-secondary-gold">Creator✨</a>
                <a href="#packages" class="block py-2 text-center w-full rounded-md text-gray-300 hover:bg-gray-800 hover:text-secondary-gold">Packages</a>
                <a href="#contact" class="block py-2 text-center w-full rounded-md bg-accent-teal text-primary-dark mt-2 hover:bg-secondary-gold">Book Now</a>
            </div>
        </div>
    </header>

    <main>
        <!-- Hero Section -->
        <section id="hero" class="relative overflow-hidden pt-24 pb-32 sm:pt-40 sm:pb-56 bg-cover bg-center" style="background-image: url('https://images.unsplash.com/photo-1514933651103-005eec06c4ee?q=80&w=2970&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D');">
            <div class="absolute inset-0 bg-primary-dark/70"></div>
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10 text-center">
                <h1 class="text-5xl sm:text-7xl font-extrabold text-secondary-gold tracking-tight mb-4">
                    Your Signature Night, Poured.
                </h1>
                <p class="text-xl sm:text-3xl text-gray-200 max-w-3xl mx-auto mb-10">
                    Full-service luxury beverage experiences for weddings, corporate events, and private parties. Crafting moments, one cocktail at a time.
                </p>
                <div class="space-x-4">
                    <a href="#packages" class="inline-block py-3 px-8 text-lg font-bold rounded-full bg-accent-teal text-primary-dark shadow-xl hover:bg-secondary-gold transition duration-300 transform hover:scale-105">
                        Explore Packages
                    </a>
                    <a href="#contact" class="inline-block py-3 px-8 text-lg font-bold rounded-full border-2 border-secondary-gold text-secondary-gold hover:bg-secondary-gold hover:text-primary-dark transition duration-300 transform hover:scale-105">
                        Get a Quote
                    </a>
                </div>
            </div>
        </section>

        <!-- About/Mission Section -->
        <section id="about" class="py-16 sm:py-24 bg-gray-900">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="grid md:grid-cols-2 gap-12 items-center">
                    <div class="text-gray-300 order-2 md:order-1">
                        <h2 class="text-4xl sm:text-5xl font-bold mb-6 text-secondary-gold">About SEG BEVERAGE</h2>
                        <p class="text-xl mb-6 leading-relaxed">
                            Our mission is simple: to transform ordinary gatherings into extraordinary celebrations. As **SEG BEVERAGE** (Super Entertainment Group Beverage), we specialize in providing unparalleled mobile bar services, focusing on customized cocktails, premium ingredients, and highly trained, professional staff.
                        </p>
                        <p class="text-lg leading-relaxed">
                            We believe that every great event deserves a spectacular beverage experience. From intimate weddings to large corporate functions, we handle every detail—from custom menu creation and T.I.P.S. certified bartenders to exquisite glassware and garnish—ensuring your guests are delighted and you can focus on enjoying the moment.
                        </p>
                    </div>
                    <div class="order-1 md:order-2">
                        <!-- High-Quality Image for About Section -->
                        <img src="https://images.unsplash.com/photo-1587373809623-6901f11c7b82?q=80&w=2970&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Elegant Bartender Counter" class="rounded-xl shadow-2xl border-4 border-accent-teal w-full h-auto object-cover">
                    </div>
                </div>
            </div>
        </section>

        <!-- Services Section -->
        <section id="services" class="py-16 sm:py-24 bg-gray-800">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <h2 class="text-4xl sm:text-5xl font-bold text-center mb-12 text-secondary-gold">What We Offer</h2>
                
                <div class="grid md:grid-cols-3 gap-8">
                    <!-- Service 1: Custom Menu -->
                    <div class="text-center p-6 bg-primary-dark rounded-xl shadow-xl border border-gray-700">
                        <div class="text-accent-teal mb-4 mx-auto w-16 h-16 flex items-center justify-center rounded-full bg-gray-900 border-2 border-accent-teal">
                            <span data-lucide="pencil-ruler" class="w-8 h-8"></span>
                        </div>
                        <h3 class="text-2xl font-semibold mb-3 text-gray-100">Custom Cocktail Menu</h3>
                        <p class="text-gray-400">Collaborate with our mixologists to design signature drinks tailored perfectly to your event theme and personal taste.</p>
                    </div>

                    <!-- Service 2: Professional Staff -->
                    <div class="text-center p-6 bg-primary-dark rounded-xl shadow-xl border border-gray-700">
                        <div class="text-accent-teal mb-4 mx-auto w-16 h-16 flex items-center justify-center rounded-full bg-gray-900 border-2 border-accent-teal">
                            <span data-lucide="users" class="w-8 h-8"></span>
                        </div>
                        <h3 class="text-2xl font-semibold mb-3 text-gray-100">Licensed Bar Professionals</h3>
                        <p class="text-gray-400">Enjoy seamless service with T.I.P.S. certified bartenders who handle all logistics, setup, and cleanup with grace.</p>
                    </div>

                    <!-- Service 3: Premium Bar Setup -->
                    <div class="text-center p-6 bg-primary-dark rounded-xl shadow-xl border border-gray-700">
                        <div class="text-accent-teal mb-4 mx-auto w-16 h-16 flex items-center justify-center rounded-full bg-gray-900 border-2 border-accent-teal">
                            <span data-lucide="bar-chart-3" class="w-8 h-8"></span>
                        </div>
                        <h3 class="text-2xl font-semibold mb-3 text-gray-100">Signature Bar Setup</h3>
                        <p class="text-gray-400">Our stunning, elegant bar unit adds a touch of rustic luxury, serving as a beautiful focal point for any venue.</p>
                    </div>
                </div>
            </div>
        </section>
        
        <!-- Signature Drink Creator Section (LLM Powered) -->
        <section id="creator" class="py-16 sm:py-24 bg-gray-700">
            <div class="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8">
                <h2 class="text-4xl sm:text-5xl font-bold text-center mb-4 text-secondary-gold">Signature Drink Creator ✨</h2>
                <p class="text-center text-xl text-gray-300 mb-10 max-w-3xl mx-auto">
                    Instantly brainstorm a unique, event-themed cocktail tailored to your taste, powered by the latest mixology insights.
                </p>

                <div class="bg-primary-dark p-8 md:p-12 rounded-xl shadow-2xl border border-gray-800 space-y-6">
                    <!-- Input Fields -->
                    <div class="grid md:grid-cols-3 gap-4">
                        <input type="text" id="event-theme" placeholder="Event Theme (e.g., Tropical Wedding)" required
                               class="w-full p-4 rounded-lg bg-gray-800 border border-gray-700 text-gray-100 focus:border-accent-teal focus:ring-1 focus:ring-accent-teal transition duration-300">
                        
                        <select id="base-spirit" required
                                class="w-full p-4 rounded-lg bg-gray-800 border border-gray-700 text-gray-400 focus:border-accent-teal focus:ring-1 focus:ring-accent-teal transition duration-300">
                            <option value="" disabled selected>Select Base Spirit</option>
                            <option value="Vodka">Vodka</option>
                            <option value="Gin">Gin</option>
                            <option value="Tequila">Tequila</option>
                            <option value="Rum">Rum</option>
                            <option value="Whiskey/Bourbon">Whiskey/Bourbon</option>
                            <option value="Non-Alcoholic">Non-Alcoholic</option>
                        </select>
                        
                        <select id="flavor-profile" required
                                class="w-full p-4 rounded-lg bg-gray-800 border border-gray-700 text-gray-400 focus:border-accent-teal focus:ring-1 focus:ring-accent-teal transition duration-300">
                            <option value="" disabled selected>Select Flavor Profile</option>
                            <option value="Sweet and Citrusy">Sweet & Citrusy</option>
                            <option value="Spicy and Smoky">Spicy & Smoky</option>
                            <option value="Herbaceous and Floral">Herbaceous & Floral</option>
                            <option value="Rich and Complex">Rich & Complex</option>
                        </select>
                    </div>

                    <button id="generate-cocktail-btn" class="w-full py-4 text-xl font-bold rounded-full bg-secondary-gold text-primary-dark hover:bg-accent-teal transform hover:scale-[1.01] transition duration-500 ease-in-out">
                        Generate Signature Cocktail Recipe ✨
                    </button>
                    
                    <!-- Loading Indicator -->
                    <div id="loading-indicator" class="hidden text-center text-lg font-medium text-accent-teal">
                        <span data-lucide="loader-2" class="w-6 h-6 inline-block animate-spin mr-2"></span> Mixing the perfect drink...
                    </div>

                    <!-- Results Area -->
                    <div id="cocktail-result" class="hidden p-6 mt-6 bg-gray-800 rounded-xl border border-gray-700 text-left space-y-4">
                        <h3 class="text-3xl font-bold text-secondary-gold" id="recipe-name"></h3>
                        <p class="text-sm italic text-gray-400" id="theme-rationale"></p>
                        
                        <div>
                            <p class="text-xl font-semibold text-accent-teal mb-2">Ingredients:</p>
                            <ul id="ingredients-list" class="list-disc list-inside ml-4 text-gray-300 space-y-1"></ul>
                        </div>
                        
                        <div>
                            <p class="text-xl font-semibold text-accent-teal mb-2">Instructions:</p>
                            <p class="text-gray-300" id="instructions"></p>
                        </div>
                        
                        <div>
                            <p class="text-xl font-semibold text-accent-teal mb-2">Garnish Suggestion:</p>
                            <p class="text-gray-300" id="garnish-suggestion"></p>
                        </div>
                    </div>

                    <!-- Error Message -->
                    <div id="error-message" class="hidden p-4 rounded-lg bg-red-800 text-gray-100 font-medium mt-4">
                        Sorry, an error occurred while mixing your cocktail. Please try again!
                    </div>
                </div>
            </div>
        </section>
        <!-- End LLM Section -->

        <!-- Packages Section (Includes Cost Calculator Data) -->
        <section id="packages" class="py-16 sm:py-24 bg-gray-900">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <h2 class="text-4xl sm:text-5xl font-bold text-center mb-4 text-secondary-gold">Our Signature Packages</h2>
                <p class="text-center text-xl text-gray-400 mb-12 max-w-3xl mx-auto">
                    Choose the level of service that best fits your event size and style.
                </p>

                <div class="grid md:grid-cols-3 gap-8">
                    <!-- Package 1: Silver -->
                    <div class="package-card bg-primary-dark p-8 rounded-xl shadow-2xl border-2 border-gray-700" data-package="Silver Tier" data-price="55">
                        <p class="text-accent-teal font-semibold text-lg">The Classic</p>
                        <h3 class="text-3xl font-bold text-gray-100 mt-2 mb-4">Silver Tier</h3>
                        <p class="text-5xl font-extrabold text-secondary-gold mb-6">$55<span class="text-xl font-normal text-gray-400">/per person</span></p>
                        <ul class="space-y-3 text-gray-300 mb-8">
                            <li class="flex items-start"><span data-lucide="check-circle" class="w-5 h-5 text-accent-teal mr-2 flex-shrink-0"></span> Full Bar Rental (4 hours)</li>
                            <li class="flex items-start"><span data-lucide="check-circle" class="w-5 h-5 text-accent-teal mr-2 flex-shrink-0"></span> Licensed Bartender (1)</li>
                            <li class="flex items-start"><span data-lucide="check-circle" class="w-5 h-5 text-accent-teal mr-2 flex-shrink-0"></span> Two Signature Cocktails</li>
                            <li class="flex items-start"><span data-lucide="check-circle" class="w-5 h-5 text-accent-teal mr-2 flex-shrink-0"></span> Mixers, Garnishes, Ice</li>
                        </ul>
                        <a href="#contact" class="select-package block text-center py-3 rounded-full bg-accent-teal text-primary-dark font-bold hover:bg-secondary-gold transition duration-300">Select & Inquire</a>
                    </div>

                    <!-- Package 2: Gold (Recommended) -->
                    <div class="package-card bg-secondary-gold p-8 rounded-xl shadow-2xl transform scale-105 border-4 border-accent-teal" data-package="Gold Tier" data-price="85">
                        <p class="text-primary-dark font-semibold text-lg">Most Popular</p>
                        <h3 class="text-3xl font-bold text-primary-dark mt-2 mb-4">Gold Tier</h3>
                        <p class="text-5xl font-extrabold text-primary-dark mb-6">$85<span class="text-xl font-normal text-gray-700">/per person</span></p>
                        <ul class="space-y-3 text-primary-dark mb-8">
                            <li class="flex items-start"><span data-lucide="check-circle" class="w-5 h-5 text-primary-dark mr-2 flex-shrink-0"></span> Full Bar Rental (5 hours)</li>
                            <li class="flex items-start"><span data-lucide="check-circle" class="w-5 h-5 text-primary-dark mr-2 flex-shrink-0"></span> Licensed Bartenders (2)</li>
                            <li class="flex items-start"><span data-lucide="check-circle" class="w-5 h-5 text-primary-dark mr-2 flex-shrink-0"></span> Three Signature Cocktails</li>
                            <li class="flex items-start"><span data-lucide="check-circle" class="w-5 h-5 text-primary-dark mr-2 flex-shrink-0"></span> Premium Mixers & Juices</li>
                            <li class="flex items-start"><span data-lucide="check-circle" class="w-5 h-5 text-primary-dark mr-2 flex-shrink-0"></span> Custom Bar Signage</li>
                        </ul>
                        <a href="#contact" class="select-package block text-center py-3 rounded-full bg-accent-teal text-primary-dark font-bold hover:bg-primary-dark hover:text-secondary-gold transition duration-300">Select & Book</a>
                    </div>
                    
                    <!-- Package 3: Platinum -->
                    <div class="package-card bg-primary-dark p-8 rounded-xl shadow-2xl border-2 border-gray-700" data-package="Platinum Tier" data-price="120">
                        <p class="text-accent-teal font-semibold text-lg">The Elite</p>
                        <h3 class="text-3xl font-bold text-gray-100 mt-2 mb-4">Platinum Tier</h3>
                        <p class="text-5xl font-extrabold text-secondary-gold mb-6">$120<span class="text-xl font-normal text-gray-400">/per person</span></p>
                        <ul class="space-y-3 text-gray-300 mb-8">
                            <li class="flex items-start"><span data-lucide="check-circle" class="w-5 h-5 text-accent-teal mr-2 flex-shrink-0"></span> Full Bar Rental (6 hours)</li>
                            <li class="flex items-start"><span data-lucide="check-circle" class="w-5 h-5 text-accent-teal mr-2 flex-shrink-0"></span> Dedicated Cocktail Servers</li>
                            <li class="flex items-start"><span data-lucide="check-circle" class="w-5 h-5 text-accent-teal mr-2 flex-shrink-0"></span> Unlimited Custom Cocktails</li>
                            <li class="flex items-start"><span data-lucide="check-circle" class="w-5 h-5 text-accent-teal mr-2 flex-shrink-0"></span> Champagne Toast Service</li>
                            <li class="flex items-start"><span data-lucide="check-circle" class="w-5 h-5 text-accent-teal mr-2 flex-shrink-0"></span> Premium Glassware Included</li>
                        </ul>
                        <a href="#contact" class="select-package block text-center py-3 rounded-full bg-accent-teal text-primary-dark font-bold hover:bg-secondary-gold transition duration-300">Select & Inquire</a>
                    </div>
                </div>
            </div>
        </section>

        <!-- Contact Section (Includes Cost Calculator) -->
        <section id="contact" class="py-16 sm:py-24 bg-gray-900">
            <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
                <h2 class="text-4xl sm:text-5xl font-bold mb-4 text-secondary-gold">Ready to Book?</h2>
                <p class="text-xl text-gray-400 mb-10">
                    Tell us about your event and let's craft the perfect beverage experience.
                </p>

                <!-- Contact Form -->
                <form class="bg-primary-dark p-8 md:p-12 rounded-xl shadow-2xl border border-gray-800 space-y-6">
                    <div>
                        <input type="text" id="name" name="name" placeholder="Your Name or Company" required
                               class="w-full p-4 rounded-lg bg-gray-800 border border-gray-700 text-gray-100 focus:border-accent-teal focus:ring-1 focus:ring-accent-teal transition duration-300">
                    </div>
                    <div>
                        <input type="email" id="email" name="email" placeholder="Email Address" required
                               class="w-full p-4 rounded-lg bg-gray-800 border border-gray-700 text-gray-100 focus:border-accent-teal focus:ring-1 focus:ring-accent-teal transition duration-300">
                    </div>
                    
                    <!-- Package Selector and Guests Input -->
                    <div class="grid md:grid-cols-2 gap-4">
                        <select id="package-tier" name="package-tier" required onchange="calculateCost()"
                                class="w-full p-4 rounded-lg bg-gray-800 border border-gray-700 text-gray-400 focus:border-accent-teal focus:ring-1 focus:ring-accent-teal transition duration-300">
                            <option value="" disabled selected>Select Your Package Tier</option>
                            <option value="55" data-name="Silver Tier">Silver Tier ($55 pp)</option>
                            <option value="85" data-name="Gold Tier">Gold Tier ($85 pp)</option>
                            <option value="120" data-name="Platinum Tier">Platinum Tier ($120 pp)</option>
                        </select>
                        <input type="number" id="guests" name="guests" placeholder="Approx. Guests (Min 50)" required min="50" oninput="calculateCost()"
                               class="w-full p-4 rounded-lg bg-gray-800 border border-gray-700 text-gray-100 focus:border-accent-teal focus:ring-1 focus:ring-accent-teal transition duration-300">
                    </div>

                    <div class="grid md:grid-cols-2 gap-4">
                        <input type="date" id="event-date" name="event-date" required
                               class="w-full p-4 rounded-lg bg-gray-800 border border-gray-700 text-gray-400 focus:border-accent-teal focus:ring-1 focus:ring-accent-teal transition duration-300">
                        
                        <!-- Estimated Cost Display -->
                        <div class="w-full p-4 rounded-lg bg-secondary-gold text-primary-dark font-extrabold text-lg text-left" id="estimated-cost">
                            Estimated Cost: $0.00
                        </div>
                    </div>
                    
                    <div>
                        <textarea id="details" name="details" rows="4" placeholder="Event details (type of event, location, special requests)" required
                                  class="w-full p-4 rounded-lg bg-gray-800 border border-gray-700 text-gray-100 focus:border-accent-teal focus:ring-1 focus:ring-accent-teal transition duration-300"></textarea>
                    </div>
                    <button type="submit" class="w-full py-4 text-xl font-bold rounded-full bg-accent-teal text-primary-dark hover:bg-secondary-gold transform hover:scale-[1.01] transition duration-500 ease-in-out">
                        Send Booking Request
                    </button>
                    <!-- Form Submission Message Box -->
                    <div id="message-box" class="hidden p-4 rounded-lg bg-accent-teal text-primary-dark font-medium mt-4">
                        Thank you! Your request has been sent successfully. We will be in touch within 24 hours.
                    </div>
                </form>
            </div>
        </section>

    </main>

    <!-- Footer: UPDATED NAME -->
    <footer class="bg-gray-800 border-t border-gray-700 py-8">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center text-gray-400">
            <p>&copy; <span id="current-year"></span> Super Entertainment Group Beverage. All rights reserved.</p>
            <p class="text-sm mt-2">Crafting extraordinary experiences in every glass.</p>
        </div>
    </footer>

    <!-- JavaScript for Mobile Menu, Form Submission, Cost Calculator, and LLM Integration -->
    <script>
        // Initialize Lucide icons
        lucide.createIcons();
        
        // API Configuration
        const API_KEY = ""; // Canvas will provide this in runtime
        const API_URL = "https://generativelanguage.googleapis.com/v1beta/models/gemini-2.5-flash-preview-09-2025:generateContent";
        
        // --- Utility Functions ---
        
        // Function for exponential backoff retry logic
        async function exponentialBackoffFetch(url, options, maxRetries = 5) {
            for (let i = 0; i < maxRetries; i++) {
                try {
                    const response = await fetch(url, options);
                    if (response.ok) {
                        return response;
                    }
                    if (response.status === 429 && i < maxRetries - 1) {
                        const delay = Math.pow(2, i) * 1000 + Math.random() * 1000;
                        await new Promise(resolve => setTimeout(resolve, delay));
                        continue;
                    }
                    throw new Error(`API call failed with status: ${response.status}`);
                } catch (error) {
                    if (i === maxRetries - 1) throw error;
                    const delay = Math.pow(2, i) * 1000 + Math.random() * 1000;
                    await new Promise(resolve => setTimeout(resolve, delay));
                }
            }
            throw new Error("Exceeded maximum retries.");
        }

        // --- Core Application Logic ---

        // Function to calculate and display the estimated total cost
        function calculateCost() {
            const packagePrice = parseFloat(document.getElementById('package-tier').value) || 0;
            let guestCount = parseInt(document.getElementById('guests').value) || 0;
            const costDisplay = document.getElementById('estimated-cost');

            const MIN_GUESTS = 50;
            if (guestCount < MIN_GUESTS && guestCount > 0) {
                document.getElementById('guests').value = MIN_GUESTS;
                guestCount = MIN_GUESTS;
            } else if (guestCount < 0) {
                 document.getElementById('guests').value = 0;
                 guestCount = 0;
            }

            if (packagePrice > 0 && guestCount >= MIN_GUESTS) {
                const estimatedTotal = packagePrice * guestCount;
                costDisplay.textContent = `Estimated Cost: $${estimatedTotal.toLocaleString('en-US', { minimumFractionDigits: 2, maximumFractionDigits: 2 })}`;
            } else {
                costDisplay.textContent = 'Estimated Cost: $0.00';
            }
        }
        
        // --- LLM Logic: Cocktail Generation ---
        
        const cocktailResultDiv = document.getElementById('cocktail-result');
        const loadingIndicator = document.getElementById('loading-indicator');
        const errorMessageDiv = document.getElementById('error-message');

        async function generateCocktail() {
            const theme = document.getElementById('event-theme').value.trim();
            const spirit = document.getElementById('base-spirit').value;
            const flavor = document.getElementById('flavor-profile').value;

            // Simple validation
            if (!theme || !spirit || !flavor) {
                errorMessageDiv.textContent = "Please fill out the Event Theme and select both a Base Spirit and Flavor Profile.";
                errorMessageDiv.classList.remove('hidden');
                cocktailResultDiv.classList.add('hidden');
                return;
            }

            // Hide previous results and show loading
            cocktailResultDiv.classList.add('hidden');
            errorMessageDiv.classList.add('hidden');
            loadingIndicator.classList.remove('hidden');

            const systemPrompt = "Act as a world-class, creative mixologist for a high-end mobile bar service. You must generate a single signature cocktail recipe that is sophisticated, easy to execute at an event (using common ingredients or easily sourced syrups/purees), and perfectly matches the theme, spirit, and flavor profile provided. Your response MUST be a JSON object conforming to the provided schema.";
            const userQuery = `Generate a signature cocktail for an event with the theme: '${theme}'. The required base spirit is '${spirit}', and the desired flavor profile is '${flavor}'.`;
            
            // Define the required JSON structure
            const recipeSchema = {
                type: "OBJECT",
                properties: {
                    recipeName: { type: "STRING", description: "A creative and thematic name for the cocktail." },
                    themeMatchRationale: { type: "STRING", description: "A brief, 1-sentence explanation of why this drink matches the theme." },
                    ingredients: {
                        type: "ARRAY",
                        items: { type: "STRING" },
                        description: "A list of 4-6 key ingredients with precise measurements (e.g., 2 oz Gin, 0.75 oz Fresh Lime Juice)."
                    },
                    instructions: { type: "STRING", description: "Step-by-step instructions for mixing, including glass type and technique (shaken, stirred)." },
                    garnishSuggestion: { type: "STRING", description: "A sophisticated garnish suggestion." }
                },
                required: ["recipeName", "themeMatchRationale", "ingredients", "instructions", "garnishSuggestion"]
            };

            const payload = {
                contents: [{ parts: [{ text: userQuery }] }],
                systemInstruction: { parts: [{ text: systemPrompt }] },
                config: {
                    responseMimeType: "application/json",
                    responseSchema: recipeSchema
                }
            };

            const urlWithKey = `${API_URL}?key=${API_KEY}`;

            try {
                const response = await exponentialBackoffFetch(urlWithKey, {
                    method: 'POST',
                    headers: { 'Content-Type': 'application/json' },
                    body: JSON.stringify(payload)
                });

                const result = await response.json();
                const jsonText = result.candidates?.[0]?.content?.parts?.[0]?.text;

                if (jsonText) {
                    const recipe = JSON.parse(jsonText);
                    displayCocktailResult(recipe);
                } else {
                    throw new Error("Received an empty or malformed response from the LLM.");
                }
            } catch (error) {
                console.error("Gemini API Error:", error);
                errorMessageDiv.textContent = "Apologies, our mixology AI encountered an error. Please check your inputs and try again.";
                errorMessageDiv.classList.remove('hidden');
            } finally {
                loadingIndicator.classList.add('hidden');
            }
        }

        function displayCocktailResult(recipe) {
            document.getElementById('recipe-name').textContent = recipe.recipeName || 'Untitled Cocktail';
            document.getElementById('theme-rationale').textContent = recipe.themeMatchRationale || 'No rationale provided.';
            document.getElementById('instructions').textContent = recipe.instructions || 'No instructions provided.';
            document.getElementById('garnish-suggestion').textContent = recipe.garnishSuggestion || 'A simple twist of citrus.';

            const ingredientsList = document.getElementById('ingredients-list');
            ingredientsList.innerHTML = ''; // Clear previous list
            if (Array.isArray(recipe.ingredients)) {
                recipe.ingredients.forEach(item => {
                    const li = document.createElement('li');
                    li.textContent = item;
                    ingredientsList.appendChild(li);
                });
            } else {
                ingredientsList.innerHTML = '<li>Ingredients could not be loaded.</li>';
            }

            cocktailResultDiv.classList.remove('hidden');
            cocktailResultDiv.scrollIntoView({ behavior: 'smooth', block: 'start' });
        }


        document.addEventListener('DOMContentLoaded', () => {
            const mobileMenuButton = document.getElementById('mobile-menu-button');
            const mobileNavContent = document.getElementById('mobile-nav-content');
            const navLinks = document.querySelectorAll('#mobile-nav-content a, #main-navigation a:not([href="#contact"])'); // Include desktop links for closing menu, but exclude 'Book Now'
            const form = document.querySelector('form');
            const messageBox = document.getElementById('message-box');
            const generateButton = document.getElementById('generate-cocktail-btn');
            
            // --- LLM Event Listener ---
            generateButton.addEventListener('click', generateCocktail);
            
            // --- Package Selection Handlers ---
            const selectPackageButtons = document.querySelectorAll('.select-package');
            const packageSelector = document.getElementById('package-tier');

            selectPackageButtons.forEach(button => {
                button.addEventListener('click', (e) => {
                    const packageCard = e.target.closest('.package-card');
                    const price = packageCard.getAttribute('data-price');
                    packageSelector.value = price;
                    calculateCost(); 
                });
            });

            // Set current year in footer
            document.getElementById('current-year').textContent = new Date().getFullYear();

            // Toggle Mobile Menu
            mobileMenuButton.addEventListener('click', () => {
                mobileNavContent.classList.toggle('hidden');
            });
            
            // Close mobile menu when a link is clicked
            navLinks.forEach(link => {
                link.addEventListener('click', () => {
                    // Only hide if the mobile menu is visible
                    if (!mobileNavContent.classList.contains('hidden')) {
                        mobileNavContent.classList.add('hidden'); 
                    }
                });
            });

            // Handle Form Submission (Simulated)
            form.addEventListener('submit', (e) => {
                e.preventDefault();
                
                messageBox.classList.remove('hidden');
                messageBox.scrollIntoView({ behavior: 'smooth' });

                setTimeout(() => {
                    form.reset();
                    document.getElementById('estimated-cost').textContent = 'Estimated Cost: $0.00';
                }, 100);

                setTimeout(() => {
                    messageBox.classList.add('hidden');
                }, 5000);
            });

            // Initial calculation run
            calculateCost();
        });
    </script>
</body>
</html>
