
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Atika Jonathan Matata Dominic - Christian Servant & Ministry Leader</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome Icons CDN -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@500;600;700&family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link rel="icon" type="image/png" href="image_0.png">
    <!-- Custom Styles & Design Tokens -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        navy: {
                            DEFAULT: '#101d2d',
                            light: '#17283c',
                            dark: '#0a131f',
                        },
                        ivory: {
                            DEFAULT: '#f8f5ee',
                            paper: '#fffdf9',
                        },
                        gold: {
                            DEFAULT: '#b99757',
                            light: '#dfc27f',
                            dark: '#96783d',
                        },
                        charcoal: '#182331',
                        muted: '#66717d',
                        borderSubtle: '#e8e2d7'
                    },
                    fontFamily: {
                        serif: ['Georgia', 'Cinzel', 'serif'],
                        sans: ['Inter', 'Helvetica', 'Arial', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <style>
        body {
            background-color: #f8f5ee;
            color: #182331;
            font-family: 'Inter', sans-serif;
        }
        .font-serif-custom {
            font-family: 'Georgia', serif;
        }
        .hero-pattern {
            background-color: #101d2d;
            background-image: radial-gradient(#17283c 1px, transparent 1px);
            background-size: 24px 24px;
        }
        /* Custom scrollbar */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #f8f5ee;
        }
        ::-webkit-scrollbar-thumb {
            background: #b99757;
            border-radius: 4px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #96783d;
        }
    </style>
</head>
<body class="bg-ivory text-charcoal antialiased selection:bg-gold selection:text-white">

    <!-- Header / Navigation Bar -->
    <header id="main-header" class="sticky top-0 z-50 bg-navy text-ivory-paper shadow-md transition-all duration-300">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-20">
                <!-- Logo / Name -->
                <a href="#" class="flex items-center space-x-3 group">
                    <div class="w-10 h-10 rounded-full border-2 border-gold flex items-center justify-center bg-navy-light text-gold font-serif text-xl font-bold transition duration-300 group-hover:bg-gold group-hover:text-navy">
                        AJ
                    </div>
                    <div class="flex flex-col">
                        <span class="font-serif-custom text-lg font-bold tracking-wider text-ivory group-hover:text-gold transition">ATIKA JONATHAN</span>
                        <span class="text-[10px] tracking-widest uppercase text-gold">Matata Dominic</span>
                    </div>
                </a>

                <!-- Desktop Navigation Links -->
                <nav class="hidden xl:flex items-center space-x-6 text-sm font-medium text-ivory/90">
                    <a href="#story" class="hover:text-gold transition py-1">Story</a>
                    <a href="#ministry" class="hover:text-gold transition py-1">Ministry</a>
                    <a href="#sermons" class="hover:text-gold transition py-1">Sermons</a>
                    <a href="#gallery" class="hover:text-gold transition py-1">Gallery</a>
                    <a href="#training" class="hover:text-gold transition py-1">Training</a>
                    <a href="#vision" class="hover:text-gold transition py-1">Vision</a>
                    <a href="#resources" class="hover:text-gold transition py-1">Resources</a>
                    <a href="#support" class="hover:text-gold transition py-1">Support</a>
                    <a href="#contact" class="px-4 py-2 bg-gold hover:bg-gold-light text-navy font-semibold rounded-md transition shadow-sm">Contact</a>
                </nav>

                <!-- Mobile Hamburger Button -->
                <button id="mobile-menu-btn" type="button" class="xl:hidden text-ivory hover:text-gold focus:outline-none p-2 rounded-md" aria-label="Toggle navigation">
                    <i class="fa-solid fa-bars text-2xl" id="menu-icon"></i>
                </button>
            </div>
        </div>

        <!-- Mobile Navigation Drawer -->
        <div id="mobile-menu" class="hidden xl:hidden bg-navy-light border-t border-navy-dark px-4 pt-3 pb-6 space-y-2">
            <a href="#story" class="mobile-nav-link block px-3 py-2 rounded-md text-base font-medium text-ivory hover:bg-navy hover:text-gold">Story</a>
            <a href="#ministry" class="mobile-nav-link block px-3 py-2 rounded-md text-base font-medium text-ivory hover:bg-navy hover:text-gold">Ministry</a>
            <a href="#sermons" class="mobile-nav-link block px-3 py-2 rounded-md text-base font-medium text-ivory hover:bg-navy hover:text-gold">Sermons</a>
            <a href="#gallery" class="mobile-nav-link block px-3 py-2 rounded-md text-base font-medium text-ivory hover:bg-navy hover:text-gold">Gallery</a>
            <a href="#training" class="mobile-nav-link block px-3 py-2 rounded-md text-base font-medium text-ivory hover:bg-navy hover:text-gold">Training</a>
            <a href="#vision" class="mobile-nav-link block px-3 py-2 rounded-md text-base font-medium text-ivory hover:bg-navy hover:text-gold">Vision</a>
            <a href="#resources" class="mobile-nav-link block px-3 py-2 rounded-md text-base font-medium text-ivory hover:bg-navy hover:text-gold">Resources</a>
            <a href="#support" class="mobile-nav-link block px-3 py-2 rounded-md text-base font-medium text-ivory hover:bg-navy hover:text-gold">Support</a>
            <a href="#contact" class="mobile-nav-link block px-3 py-2 rounded-md text-base font-medium bg-gold text-navy font-semibold hover:bg-gold-light mt-2">Contact & Prayer</a>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero-pattern text-ivory py-16 md:py-24 relative overflow-hidden border-b border-gold/20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
                <!-- Text Content -->
                <div class="lg:col-span-7 space-y-6">
                    <div class="inline-flex items-center space-x-2 px-3 py-1 rounded-full bg-gold/10 border border-gold/30 text-gold text-xs sm:text-sm font-semibold tracking-wider uppercase">
                        <i class="fa-solid fa-cross text-xs"></i>
                        <span>Serving God • Equipping Children • Building Hope</span>
                    </div>
                    <h1 class="text-3xl sm:text-4xl md:text-5xl font-serif-custom font-bold text-ivory leading-tight">
                        Helping the next generation discover their value, know God & find hope.
                    </h1>
                    <p class="text-base sm:text-lg text-ivory/80 leading-relaxed max-w-2xl font-light">
                        "I am <strong class="text-gold font-semibold">Atika Jonathan Matata Dominic</strong>, a Christian servant, children’s ministry teacher, preacher, teacher, and choir leader serving with Foursquare Gospel Church."
                    </p>
                    <div class="pt-4 flex flex-col sm:flex-row gap-4">
                        <a href="#ministry" class="inline-flex items-center justify-center px-6 py-3.5 bg-gold hover:bg-gold-light text-navy font-bold rounded-md transition shadow-lg hover:shadow-gold/20 text-center">
                            <span>Explore My Ministry</span>
                            <i class="fa-solid fa-arrow-right ml-2 text-sm"></i>
                        </a>
                        <a href="#story" class="inline-flex items-center justify-center px-6 py-3.5 border border-ivory/30 hover:border-gold hover:text-gold text-ivory font-medium rounded-md transition text-center">
                            <span>Read My Story</span>
                        </a>
                    </div>
                    
                    <!-- Quick Stats Badges -->
                    <div class="pt-8 grid grid-cols-3 gap-4 border-t border-ivory/10 text-center sm:text-left">
                        <div>
                            <span class="block text-2xl font-bold font-serif-custom text-gold">10+</span>
                            <span class="text-xs text-ivory/70">Years of Service</span>
                        </div>
                        <div>
                            <span class="block text-2xl font-bold font-serif-custom text-gold">500+</span>
                            <span class="text-xs text-ivory/70">Children Mentored</span>
                        </div>
                        <div>
                            <span class="block text-2xl font-bold font-serif-custom text-gold">Foursquare</span>
                            <span class="text-xs text-ivory/70">Gospel Church Servant</span>
                        </div>
                    </div>
                </div>

                <!-- Hero Portrait Card -->
                <div class="lg:col-span-5 flex justify-center">
                    <div class="relative w-full max-w-md">
                        <!-- Decorative Frame Behind Image -->
                        <div class="absolute -inset-2 rounded-2xl bg-gradient-to-r from-gold/30 to-gold/10 transform rotate-2 blur-sm"></div>
                        <div class="relative bg-navy-light p-3 rounded-2xl border border-gold/30 shadow-2xl">
                            <div class="relative overflow-hidden rounded-xl aspect-[4/5] bg-navy">
                                <img src="image_0.png" 
                                     alt="Atika Jonathan Matata Dominic" 
                                     class="w-full h-full object-cover object-center filter contrast-105"
                                     onerror="this.src='https://placehold.co/600x750/17283c/dfc27f?text=Atika+Jonathan'">
                                <div class="absolute inset-0 bg-gradient-to-t from-navy via-transparent to-transparent opacity-90"></div>
                                <div class="absolute bottom-0 inset-x-0 p-6 text-center">
                                    <h3 class="font-serif-custom text-xl font-bold text-ivory">Atika Jonathan</h3>
                                    <p class="text-xs text-gold uppercase tracking-widest mt-1">Ministry Servant & Educator</p>
                                    <p class="text-xs text-ivory/70 mt-2 font-serif-custom italic">"Train up a child in the way he should go..." — Proverbs 22:6</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Main Content Container -->
    <main>
        
        <!-- Section 1: My Story / Journey of Faith -->
        <section id="story" class="py-20 bg-ivory">
            <div class="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="text-center max-w-3xl mx-auto mb-12">
                    <span class="text-gold font-semibold uppercase tracking-wider text-xs">Heart of Service</span>
                    <h2 class="text-3xl sm:text-4xl font-serif-custom font-bold text-navy mt-1">My Story & Journey of Faith</h2>
                    <div class="w-16 h-1 bg-gold mx-auto mt-4 rounded-full"></div>
                </div>

                <div class="bg-ivory-paper border border-borderSubtle rounded-2xl p-6 sm:p-10 shadow-sm space-y-6 text-charcoal/90 leading-relaxed text-base sm:text-lg">
                    <div class="flex flex-col md:flex-row gap-8 items-center mb-6">
                        <div class="w-full md:w-1/3 shrink-0">
                            <div class="p-2 bg-ivory rounded-xl border border-borderSubtle shadow-inner">
                                <img src="https://images.unsplash.com/photo-1509021436471-187320803b18?auto=format&fit=crop&w=600&q=80" 
                                     alt="Church Worship and Teaching" 
                                     class="rounded-lg w-full h-48 object-cover"
                                     onerror="this.src='https://placehold.co/600x400/101d2d/fffdf9?text=Faith+Journey'">
                            </div>
                        </div>
                        <div class="w-full md:w-2/3">
                            <h3 class="font-serif-custom text-2xl font-bold text-navy mb-3">Called to Serve & Restore Hope</h3>
                            <p class="text-muted text-base">
                                My journey in Christian ministry began with a deep, unshakable conviction that true transformation in any community begins in the hearts of children and youth. Through the grace of God, I have dedicated my life to biblical instruction, musical praise, and practical spiritual mentorship.
                            </p>
                        </div>
                    </div>

                    <p>
                        Serving with the <strong>Foursquare Gospel Church</strong>, I have witnessed firsthand how tailored children's ministry and structured choir leadership can spark joy, foster resilience, and lay an unyielding spiritual foundation for young minds. Every lesson taught, song rehearsed, and message preached is driven by a single purpose: to guide individuals to know Christ and realize their God-given potential.
                    </p>

                    <blockquote class="my-6 p-6 border-l-4 border-gold bg-ivory/60 rounded-r-lg italic text-navy font-serif-custom">
                        "Ministry is not merely a title or a duty—it is a daily commitment to listen, nurture, and mirror God’s love to those who need it most."
                    </blockquote>

                    <p class="text-base text-muted">
                        Beyond the pulpit and Sunday school classrooms, my passion lies in equipping teachers, guiding youth through life's complex transitions, and harmonizing voices in praise to elevate corporate worship.
                    </p>
                </div>
            </div>
        </section>

        <!-- Section 2: Core Ministries -->
        <section id="ministry" class="py-20 bg-navy text-ivory border-t border-b border-navy-light">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="text-center max-w-3xl mx-auto mb-16">
                    <span class="text-gold font-semibold uppercase tracking-wider text-xs">Pillars of Calling</span>
                    <h2 class="text-3xl sm:text-4xl font-serif-custom font-bold text-ivory mt-1">Core Ministries</h2>
                    <p class="text-ivory/70 mt-3 text-sm sm:text-base">Discover the key areas where God has entrusted me to lead, teach, and encourage.</p>
                    <div class="w-16 h-1 bg-gold mx-auto mt-4 rounded-full"></div>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                    <!-- Ministry 1 -->
                    <div class="bg-navy-light border border-gold/20 rounded-xl p-6 transition duration-300 hover:border-gold hover:-translate-y-1 shadow-lg flex flex-col justify-between">
                        <div>
                            <div class="w-12 h-12 rounded-lg bg-gold/10 text-gold flex items-center justify-center mb-6 text-2xl">
                                <i class="fa-solid fa-child-reaching"></i>
                            </div>
                            <h3 class="font-serif-custom text-xl font-bold text-ivory mb-3">Children's Ministry</h3>
                            <p class="text-ivory/70 text-sm leading-relaxed mb-4">
                                Interactive Sunday school lessons, age-appropriate Bible teaching, crafts, and spiritual foundation building for young believers.
                            </p>
                        </div>
                        <ul class="text-xs text-gold space-y-1 pt-4 border-t border-navy-dark">
                            <li><i class="fa-solid fa-check mr-1.5"></i> Sunday School Teaching</li>
                            <li><i class="fa-solid fa-check mr-1.5"></i> VBS & Kids Camps</li>
                        </ul>
                    </div>

                    <!-- Ministry 2 -->
                    <div class="bg-navy-light border border-gold/20 rounded-xl p-6 transition duration-300 hover:border-gold hover:-translate-y-1 shadow-lg flex flex-col justify-between">
                        <div>
                            <div class="w-12 h-12 rounded-lg bg-gold/10 text-gold flex items-center justify-center mb-6 text-2xl">
                                <i class="fa-solid fa-music"></i>
                            </div>
                            <h3 class="font-serif-custom text-xl font-bold text-ivory mb-3">Choir Leadership</h3>
                            <p class="text-ivory/70 text-sm leading-relaxed mb-4">
                                Vocal coaching, hymnology, arrangement, and spiritual preparation for church choirs to facilitate heartfelt worship.
                            </p>
                        </div>
                        <ul class="text-xs text-gold space-y-1 pt-4 border-t border-navy-dark">
                            <li><i class="fa-solid fa-check mr-1.5"></i> Worship Direction</li>
                            <li><i class="fa-solid fa-check mr-1.5"></i> Choir Rehearsals</li>
                        </ul>
                    </div>

                    <!-- Ministry 3 -->
                    <div class="bg-navy-light border border-gold/20 rounded-xl p-6 transition duration-300 hover:border-gold hover:-translate-y-1 shadow-lg flex flex-col justify-between">
                        <div>
                            <div class="w-12 h-12 rounded-lg bg-gold/10 text-gold flex items-center justify-center mb-6 text-2xl">
                                <i class="fa-solid fa-book-bible"></i>
                            </div>
                            <h3 class="font-serif-custom text-xl font-bold text-ivory mb-3">Preaching & Teaching</h3>
                            <p class="text-ivory/70 text-sm leading-relaxed mb-4">
                                Expository Bible teaching, pulpit ministry, and devotional sessions focused on practical spiritual growth and faith.
                            </p>
                        </div>
                        <ul class="text-xs text-gold space-y-1 pt-4 border-t border-navy-dark">
                            <li><i class="fa-solid fa-check mr-1.5"></i> Pulpit Ministry</li>
                            <li><i class="fa-solid fa-check mr-1.5"></i> Bible Study Groups</li>
                        </ul>
                    </div>

                    <!-- Ministry 4 -->
                    <div class="bg-navy-light border border-gold/20 rounded-xl p-6 transition duration-300 hover:border-gold hover:-translate-y-1 shadow-lg flex flex-col justify-between">
                        <div>
                            <div class="w-12 h-12 rounded-lg bg-gold/10 text-gold flex items-center justify-center mb-6 text-2xl">
                                <i class="fa-solid fa-hands-holding-child"></i>
                            </div>
                            <h3 class="font-serif-custom text-xl font-bold text-ivory mb-3">Community Outreach</h3>
                            <p class="text-ivory/70 text-sm leading-relaxed mb-4">
                                Visiting families, youth mentorship programs, and local outreach bringing hope and practical aid to children in need.
                            </p>
                        </div>
                        <ul class="text-xs text-gold space-y-1 pt-4 border-t border-navy-dark">
                            <li><i class="fa-solid fa-check mr-1.5"></i> Youth Counseling</li>
                            <li><i class="fa-solid fa-check mr-1.5"></i> Hope Initiatives</li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>

        <!-- Section 3: Sermons & Messages -->
        <section id="sermons" class="py-20 bg-ivory">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="text-center max-w-3xl mx-auto mb-16">
                    <span class="text-gold font-semibold uppercase tracking-wider text-xs">Spiritual Food</span>
                    <h2 class="text-3xl sm:text-4xl font-serif-custom font-bold text-navy mt-1">Sermons & Messages</h2>
                    <p class="text-muted mt-2 text-sm sm:text-base">Listen to recent biblical teachings and spiritual messages.</p>
                    <div class="w-16 h-1 bg-gold mx-auto mt-4 rounded-full"></div>
                </div>

                <!-- Featured Audio Player Simulation -->
                <div class="bg-navy text-ivory rounded-2xl p-6 sm:p-8 mb-12 shadow-xl border border-gold/30">
                    <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                        <div class="lg:col-span-5 space-y-4">
                            <span class="inline-block px-3 py-1 bg-gold/20 text-gold text-xs font-semibold rounded-full uppercase">Featured Teaching</span>
                            <h3 id="current-sermon-title" class="font-serif-custom text-2xl font-bold text-ivory">Building an Unshakable Faith in Youth</h3>
                            <p id="current-sermon-desc" class="text-ivory/70 text-sm leading-relaxed">
                                A comprehensive look at Deuteronomy 6 and how parents and Sunday school teachers can partner to disciple children effectively in today's changing world.
                            </p>
                            <div class="flex items-center space-x-4 text-xs text-gold/80">
                                <span><i class="fa-regular fa-clock mr-1"></i> 34 mins</span>
                                <span><i class="fa-regular fa-calendar mr-1"></i> Recent Sunday Service</span>
                            </div>
                        </div>

                        <!-- Audio Control Interface -->
                        <div class="lg:col-span-7 bg-navy-light p-6 rounded-xl border border-navy-dark space-y-4">
                            <div class="flex items-center justify-between text-xs text-ivory/60 font-mono">
                                <span id="sermon-timer">02:15</span>
                                <span>/</span>
                                <span>34:10</span>
                            </div>

                            <!-- Progress Bar -->
                            <div class="w-full bg-navy rounded-full h-2 overflow-hidden cursor-pointer">
                                <div class="bg-gold h-full w-1/4 rounded-full"></div>
                            </div>

                            <!-- Controls -->
                            <div class="flex items-center justify-center space-x-6 pt-2">
                                <button type="button" class="text-ivory/70 hover:text-gold transition text-lg" title="Rewind 10s">
                                    <i class="fa-solid fa-rotate-left"></i>
                                </button>
                                <button id="play-pause-btn" type="button" onclick="toggleAudioPlay()" class="w-12 h-12 rounded-full bg-gold hover:bg-gold-light text-navy font-bold flex items-center justify-center shadow-md transition">
                                    <i class="fa-solid fa-play text-lg ml-0.5" id="play-icon"></i>
                                </button>
                                <button type="button" class="text-ivory/70 hover:text-gold transition text-lg" title="Forward 10s">
                                    <i class="fa-solid fa-rotate-right"></i>
                                </button>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Sermon Cards List -->
                <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                    <div class="bg-ivory-paper border border-borderSubtle rounded-xl p-6 hover:shadow-md transition cursor-pointer" onclick="selectSermon('Building an Unshakable Faith in Youth', 'A comprehensive look at Deuteronomy 6 and how parents and Sunday school teachers can partner to disciple children.', '34 mins')">
                        <div class="text-gold text-xs font-semibold uppercase mb-2"><i class="fa-solid fa-volume-high mr-1"></i> Audio Sermon</div>
                        <h4 class="font-serif-custom text-lg font-bold text-navy mb-2">Building an Unshakable Faith in Youth</h4>
                        <p class="text-muted text-xs leading-relaxed mb-4">Exploring biblical frameworks for instilling enduring spiritual habits early in life.</p>
                        <span class="text-xs text-gold font-medium hover:underline">Listen Now &rarr;</span>
                    </div>

                    <div class="bg-ivory-paper border border-borderSubtle rounded-xl p-6 hover:shadow-md transition cursor-pointer" onclick="selectSermon('The Harmony of Praise: Worship with One Voice', 'Understanding the spiritual role of choir leadership in corporate church worship.', '28 mins')">
                        <div class="text-gold text-xs font-semibold uppercase mb-2"><i class="fa-solid fa-volume-high mr-1"></i> Choir Devotional</div>
                        <h4 class="font-serif-custom text-lg font-bold text-navy mb-2">The Harmony of Praise: Worship with One Voice</h4>
                        <p class="text-muted text-xs leading-relaxed mb-4">Understanding the spiritual role of choir leadership in corporate church worship.</p>
                        <span class="text-xs text-gold font-medium hover:underline">Listen Now &rarr;</span>
                    </div>

                    <div class="bg-ivory-paper border border-borderSubtle rounded-xl p-6 hover:shadow-md transition cursor-pointer" onclick="selectSermon('Serving with Humility & Joy', 'Reflections on Paul’s letters to Timothy regarding church leadership and service.', '42 mins')">
                        <div class="text-gold text-xs font-semibold uppercase mb-2"><i class="fa-solid fa-volume-high mr-1"></i> Bible Teaching</div>
                        <h4 class="font-serif-custom text-lg font-bold text-navy mb-2">Serving with Humility & Joy</h4>
                        <p class="text-muted text-xs leading-relaxed mb-4">Reflections on Paul’s letters regarding faithful church leadership and endurance.</p>
                        <span class="text-xs text-gold font-medium hover:underline">Listen Now &rarr;</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- Section 4: Photo & Event Gallery -->
        <section id="gallery" class="py-20 bg-ivory-paper border-t border-borderSubtle">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="text-center max-w-3xl mx-auto mb-16">
                    <span class="text-gold font-semibold uppercase tracking-wider text-xs">Ministry Moments</span>
                    <h2 class="text-3xl sm:text-4xl font-serif-custom font-bold text-navy mt-1">Photo & Event Gallery</h2>
                    <p class="text-muted mt-2 text-sm sm:text-base">Glimpses of Sunday school workshops, choir rehearsals, and community gatherings.</p>
                    <div class="w-16 h-1 bg-gold mx-auto mt-4 rounded-full"></div>
                </div>

                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
                    <!-- Gallery Item 1 -->
                    <div class="group relative overflow-hidden rounded-xl border border-borderSubtle shadow-sm bg-navy aspect-video">
                        <img src="https://images.unsplash.com/photo-1488521787991-ed7bbaae773c?auto=format&fit=crop&w=700&q=80" 
                             alt="Children's Sunday School Session" 
                             class="w-full h-full object-cover transition duration-500 group-hover:scale-105 opacity-90 group-hover:opacity-100"
                             onerror="this.src='https://placehold.co/700x450/101d2d/dfc27f?text=Sunday+School'">
                        <div class="absolute inset-0 bg-gradient-to-t from-navy via-navy/20 to-transparent opacity-80 group-hover:opacity-90 transition"></div>
                        <div class="absolute bottom-0 inset-x-0 p-4 text-ivory">
                            <span class="text-gold text-[10px] uppercase tracking-wider font-semibold">Sunday School</span>
                            <h4 class="font-serif-custom text-base font-bold">Interactive Bible Story Time</h4>
                        </div>
                    </div>

                    <!-- Gallery Item 2 -->
                    <div class="group relative overflow-hidden rounded-xl border border-borderSubtle shadow-sm bg-navy aspect-video">
                        <img src="https://images.unsplash.com/photo-1511671782779-c97d3d27a1d4?auto=format&fit=crop&w=700&q=80" 
                             alt="Choir Rehearsal" 
                             class="w-full h-full object-cover transition duration-500 group-hover:scale-105 opacity-90 group-hover:opacity-100"
                             onerror="this.src='https://placehold.co/700x450/101d2d/dfc27f?text=Choir+Rehearsal'">
                        <div class="absolute inset-0 bg-gradient-to-t from-navy via-navy/20 to-transparent opacity-80 group-hover:opacity-90 transition"></div>
                        <div class="absolute bottom-0 inset-x-0 p-4 text-ivory">
                            <span class="text-gold text-[10px] uppercase tracking-wider font-semibold">Music Ministry</span>
                            <h4 class="font-serif-custom text-base font-bold">Foursquare Church Choir Rehearsal</h4>
                        </div>
                    </div>

                    <!-- Gallery Item 3 -->
                    <div class="group relative overflow-hidden rounded-xl border border-borderSubtle shadow-sm bg-navy aspect-video">
                        <img src="https://images.unsplash.com/photo-1529156069898-49953e39b3ac?auto=format&fit=crop&w=700&q=80" 
                             alt="Youth Leadership Workshop" 
                             class="w-full h-full object-cover transition duration-500 group-hover:scale-105 opacity-90 group-hover:opacity-100"
                             onerror="this.src='https://placehold.co/700x450/101d2d/dfc27f?text=Youth+Workshop'">
                        <div class="absolute inset-0 bg-gradient-to-t from-navy via-navy/20 to-transparent opacity-80 group-hover:opacity-90 transition"></div>
                        <div class="absolute bottom-0 inset-x-0 p-4 text-ivory">
                            <span class="text-gold text-[10px] uppercase tracking-wider font-semibold">Leadership Training</span>
                            <h4 class="font-serif-custom text-base font-bold">Equipping Next-Gen Teachers</h4>
                        </div>
                    </div>

                    <!-- Gallery Item 4 -->
                    <div class="group relative overflow-hidden rounded-xl border border-borderSubtle shadow-sm bg-navy aspect-video">
                        <img src="https://images.unsplash.com/photo-1509099836639-18ba1795216d?auto=format&fit=crop&w=700&q=80" 
                             alt="Community Outreach Gathering" 
                             class="w-full h-full object-cover transition duration-500 group-hover:scale-105 opacity-90 group-hover:opacity-100"
                             onerror="this.src='https://placehold.co/700x450/101d2d/dfc27f?text=Community+Outreach'">
                        <div class="absolute inset-0 bg-gradient-to-t from-navy via-navy/20 to-transparent opacity-80 group-hover:opacity-90 transition"></div>
                        <div class="absolute bottom-0 inset-x-0 p-4 text-ivory">
                            <span class="text-gold text-[10px] uppercase tracking-wider font-semibold">Community Outreach</span>
                            <h4 class="font-serif-custom text-base font-bold">Children's Hope Initiative</h4>
                        </div>
                    </div>

                    <!-- Gallery Item 5 -->
                    <div class="group relative overflow-hidden rounded-xl border border-borderSubtle shadow-sm bg-navy aspect-video">
                        <img src="https://images.unsplash.com/photo-1469571486292-0ba58a3f068b?auto=format&fit=crop&w=700&q=80" 
                             alt="Annual Praise Celebration" 
                             class="w-full h-full object-cover transition duration-500 group-hover:scale-105 opacity-90 group-hover:opacity-100"
                             onerror="this.src='https://placehold.co/700x450/101d2d/dfc27f?text=Praise+Event'">
                        <div class="absolute inset-0 bg-gradient-to-t from-navy via-navy/20 to-transparent opacity-80 group-hover:opacity-90 transition"></div>
                        <div class="absolute bottom-0 inset-x-0 p-4 text-ivory">
                            <span class="text-gold text-[10px] uppercase tracking-wider font-semibold">Special Events</span>
                            <h4 class="font-serif-custom text-base font-bold">Annual Praise & Worship Night</h4>
                        </div>
                    </div>

                    <!-- Gallery Item 6 -->
                    <div class="group relative overflow-hidden rounded-xl border border-borderSubtle shadow-sm bg-navy aspect-video">
                        <img src="https://images.unsplash.com/photo-1438283173091-5dbf5c5a3206?auto=format&fit=crop&w=700&q=80" 
                             alt="Scripture Recitation Event" 
                             class="w-full h-full object-cover transition duration-500 group-hover:scale-105 opacity-90 group-hover:opacity-100"
                             onerror="this.src='https://placehold.co/700x450/101d2d/dfc27f?text=Scripture+Recitation'">
                        <div class="absolute inset-0 bg-gradient-to-t from-navy via-navy/20 to-transparent opacity-80 group-hover:opacity-90 transition"></div>
                        <div class="absolute bottom-0 inset-x-0 p-4 text-ivory">
                            <span class="text-gold text-[10px] uppercase tracking-wider font-semibold">Discipline</span>
                            <h4 class="font-serif-custom text-base font-bold">Scripture Memorization Awards</h4>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Section 5: Teacher & Youth Training -->
        <section id="training" class="py-20 bg-ivory">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
                    <div class="lg:col-span-6 space-y-6">
                        <span class="text-gold font-semibold uppercase tracking-wider text-xs">Equipping Leaders</span>
                        <h2 class="text-3xl sm:text-4xl font-serif-custom font-bold text-navy leading-tight">Teacher & Youth Training Programs</h2>
                        <p class="text-muted leading-relaxed text-base">
                            Strong children's ministries require passionate, well-prepared teachers. I facilitate practical workshops and mentorship modules designed to equip Sunday school volunteers and youth leaders with effective teaching methodologies and biblical knowledge.
                        </p>

                        <div class="space-y-4 pt-2">
                            <div class="flex items-start space-x-4">
                                <div class="w-10 h-10 rounded-lg bg-gold/10 text-gold flex items-center justify-center shrink-0 mt-1">
                                    <i class="fa-solid fa-chalkboard-user"></i>
                                </div>
                                <div>
                                    <h4 class="font-serif-custom text-lg font-bold text-navy">Pedagogy for Children's Teachers</h4>
                                    <p class="text-muted text-sm">Age-appropriate storytelling, visual aids creation, and classroom management for spiritual growth.</p>
                                </div>
                            </div>

                            <div class="flex items-start space-x-4">
                                <div class="w-10 h-10 rounded-lg bg-gold/10 text-gold flex items-center justify-center shrink-0 mt-1">
                                    <i class="fa-solid fa-users-gear"></i>
                                </div>
                                <div>
                                    <h4 class="font-serif-custom text-lg font-bold text-navy">Youth Mentorship & Guidance</h4>
                                    <p class="text-muted text-sm">Navigating peer challenges, fostering personal prayer lives, and developing young spiritual leadership.</p>
                                </div>
                            </div>

                            <div class="flex items-start space-x-4">
                                <div class="w-10 h-10 rounded-lg bg-gold/10 text-gold flex items-center justify-center shrink-0 mt-1">
                                    <i class="fa-solid fa-guitar"></i>
                                </div>
                                <div>
                                    <h4 class="font-serif-custom text-lg font-bold text-navy">Choir Discipline & Music Basics</h4>
                                    <p class="text-muted text-sm">Vocal warmup techniques, harmony fundamentals, and spiritual discipline in worship ministry.</p>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="lg:col-span-6 bg-navy text-ivory p-8 rounded-2xl border border-gold/30 shadow-xl">
                        <h3 class="font-serif-custom text-2xl font-bold text-ivory mb-2">Request a Workshop</h3>
                        <p class="text-ivory/70 text-sm mb-6">Interested in hosting a teacher training or choir workshop for your local assembly?</p>

                        <form id="workshop-form" onsubmit="handleWorkshopSubmit(event)" class="space-y-4">
                            <div>
                                <label class="block text-xs font-semibold uppercase tracking-wider text-gold mb-1">Church / Organization</label>
                                <input type="text" required class="w-full px-4 py-2.5 rounded-lg bg-navy-light border border-navy-dark text-ivory placeholder-ivory/40 focus:outline-none focus:border-gold text-sm" placeholder="e.g. Local Foursquare Church">
                            </div>
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                <div>
                                    <label class="block text-xs font-semibold uppercase tracking-wider text-gold mb-1">Contact Person</label>
                                    <input type="text" required class="w-full px-4 py-2.5 rounded-lg bg-navy-light border border-navy-dark text-ivory placeholder-ivory/40 focus:outline-none focus:border-gold text-sm" placeholder="Your Name">
                                </div>
                                <div>
                                    <label class="block text-xs font-semibold uppercase tracking-wider text-gold mb-1">Preferred Date</label>
                                    <input type="date" required class="w-full px-4 py-2.5 rounded-lg bg-navy-light border border-navy-dark text-ivory placeholder-ivory/40 focus:outline-none focus:border-gold text-sm">
                                </div>
                            </div>
                            <div>
                                <label class="block text-xs font-semibold uppercase tracking-wider text-gold mb-1">Module Interest</label>
                                <select class="w-full px-4 py-2.5 rounded-lg bg-navy-light border border-navy-dark text-ivory focus:outline-none focus:border-gold text-sm">
                                    <option>Sunday School Teacher Training</option>
                                    <option>Choir & Music Ministry Development</option>
                                    <option>Youth Mentorship Program</option>
                                    <option>General Biblical Leadership</option>
                                </select>
                            </div>
                            <button type="submit" class="w-full py-3 bg-gold hover:bg-gold-light text-navy font-bold rounded-lg transition shadow-md">
                                Send Workshop Request
                            </button>
                        </form>
                        <div id="workshop-success" class="hidden mt-4 p-3 bg-gold/20 border border-gold/40 text-gold rounded-lg text-sm text-center">
                            Thank you! Your request has been received. I will reach out shortly.
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Section 6: Future Vision & Projects -->
        <section id="vision" class="py-20 bg-navy text-ivory">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="text-center max-w-3xl mx-auto mb-16">
                    <span class="text-gold font-semibold uppercase tracking-wider text-xs">Looking Forward</span>
                    <h2 class="text-3xl sm:text-4xl font-serif-custom font-bold text-ivory mt-1">Future Vision & Projects</h2>
                    <p class="text-ivory/70 mt-2 text-sm sm:text-base">Targeted initiatives to expand reach and provide sustained support for children.</p>
                    <div class="w-16 h-1 bg-gold mx-auto mt-4 rounded-full"></div>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                    <!-- Vision Card 1 -->
                    <div class="bg-navy-light border border-gold/20 rounded-xl p-6 relative flex flex-col justify-between">
                        <div class="absolute -top-4 right-6 w-8 h-8 rounded-full bg-gold text-navy font-serif-custom font-bold flex items-center justify-center text-sm">1</div>
                        <div>
                            <h3 class="font-serif-custom text-xl font-bold text-ivory mb-3">Children’s Bible Curriculum Expansion</h3>
                            <p class="text-ivory/70 text-sm leading-relaxed mb-4">
                                Developing culturally contextualized, printed study guides and visual flashcards for rural Sunday school classes with limited digital access.
                            </p>
                        </div>
                        <div class="w-full bg-navy rounded-full h-1.5 mt-4">
                            <div class="bg-gold h-1.5 rounded-full w-2/3"></div>
                        </div>
                        <span class="text-[11px] text-gold mt-2 block font-mono">Status: Material Preparation (65%)</span>
                    </div>

                    <!-- Vision Card 2 -->
                    <div class="bg-navy-light border border-gold/20 rounded-xl p-6 relative flex flex-col justify-between">
                        <div class="absolute -top-4 right-6 w-8 h-8 rounded-full bg-gold text-navy font-serif-custom font-bold flex items-center justify-center text-sm">2</div>
                        <div>
                            <h3 class="font-serif-custom text-xl font-bold text-ivory mb-3">Youth Choir Hymnal & Music Resource</h3>
                            <p class="text-ivory/70 text-sm leading-relaxed mb-4">
                                Compiling a comprehensive hymnbook complete with sheet music and audio rehearsals to preserve sacred music and empower local choirs.
                            </p>
                        </div>
                        <div class="w-full bg-navy rounded-full h-1.5 mt-4">
                            <div class="bg-gold h-1.5 rounded-full w-2/5"></div>
                        </div>
                        <span class="text-[11px] text-gold mt-2 block font-mono">Status: Arrangement Phase (40%)</span>
                    </div>

                    <!-- Vision Card 3 -->
                    <div class="bg-navy-light border border-gold/20 rounded-xl p-6 relative flex flex-col justify-between">
                        <div class="absolute -top-4 right-6 w-8 h-8 rounded-full bg-gold text-navy font-serif-custom font-bold flex items-center justify-center text-sm">3</div>
                        <div>
                            <h3 class="font-serif-custom text-xl font-bold text-ivory mb-3">Hope Ministry Educational Sponsorship</h3>
                            <p class="text-ivory/70 text-sm leading-relaxed mb-4">
                                Establishing an annual support fund to supply school books, uniforms, and meals for vulnerable children in our Sunday school fellowship.
                            </p>
                        </div>
                        <div class="w-full bg-navy rounded-full h-1.5 mt-4">
                            <div class="bg-gold h-1.5 rounded-full w-1/4"></div>
                        </div>
                        <span class="text-[11px] text-gold mt-2 block font-mono">Status: Partner Gathering (25%)</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- Section 7: Free Resources -->
        <section id="resources" class="py-20 bg-ivory">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="text-center max-w-3xl mx-auto mb-16">
                    <span class="text-gold font-semibold uppercase tracking-wider text-xs">Equipping You</span>
                    <h2 class="text-3xl sm:text-4xl font-serif-custom font-bold text-navy mt-1">Free Spiritual & Educational Resources</h2>
                    <p class="text-muted mt-2 text-sm sm:text-base">Downloadable study guides, lesson outlines, and choir guides for teachers and leaders.</p>
                    <div class="w-16 h-1 bg-gold mx-auto mt-4 rounded-full"></div>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                    <!-- Resource 1 -->
                    <div class="bg-ivory-paper border border-borderSubtle rounded-2xl p-6 shadow-sm hover:shadow-md transition flex flex-col justify-between">
                        <div>
                            <div class="w-10 h-10 rounded-lg bg-navy/5 text-navy flex items-center justify-center mb-4 text-xl">
                                <i class="fa-solid fa-file-pdf text-gold"></i>
                            </div>
                            <h3 class="font-serif-custom text-lg font-bold text-navy mb-2">12-Week Sunday School Lesson Plan</h3>
                            <p class="text-muted text-xs leading-relaxed mb-4">
                                A structured guide covering foundational Old and New Testament stories, complete with discussion prompts and activity ideas.
                            </p>
                        </div>
                        <button type="button" onclick="openResourceModal('12-Week Sunday School Lesson Plan')" class="w-full py-2.5 border border-navy text-navy font-semibold text-xs rounded-lg hover:bg-navy hover:text-ivory transition">
                            <i class="fa-solid fa-download mr-1"></i> Access Guide
                        </button>
                    </div>

                    <!-- Resource 2 -->
                    <div class="bg-ivory-paper border border-borderSubtle rounded-2xl p-6 shadow-sm hover:shadow-md transition flex flex-col justify-between">
                        <div>
                            <div class="w-10 h-10 rounded-lg bg-navy/5 text-navy flex items-center justify-center mb-4 text-xl">
                                <i class="fa-solid fa-file-audio text-gold"></i>
                            </div>
                            <h3 class="font-serif-custom text-lg font-bold text-navy mb-2">Choir Vocal Warmup Handbook</h3>
                            <p class="text-muted text-xs leading-relaxed mb-4">
                                Practical exercises for voice projection, pitch accuracy, and spiritual devotion prior to Sunday worship services.
                            </p>
                        </div>
                        <button type="button" onclick="openResourceModal('Choir Vocal Warmup Handbook')" class="w-full py-2.5 border border-navy text-navy font-semibold text-xs rounded-lg hover:bg-navy hover:text-ivory transition">
                            <i class="fa-solid fa-download mr-1"></i> Access Guide
                        </button>
                    </div>

                    <!-- Resource 3 -->
                    <div class="bg-ivory-paper border border-borderSubtle rounded-2xl p-6 shadow-sm hover:shadow-md transition flex flex-col justify-between">
                        <div>
                            <div class="w-10 h-10 rounded-lg bg-navy/5 text-navy flex items-center justify-center mb-4 text-xl">
                                <i class="fa-solid fa-book-open text-gold"></i>
                            </div>
                            <h3 class="font-serif-custom text-lg font-bold text-navy mb-2">Youth Devotional Memory Verses</h3>
                            <p class="text-muted text-xs leading-relaxed mb-4">
                                A curated list of 52 core Scripture verses with reflection questions to encourage weekly verse memorization.
                            </p>
                        </div>
                        <button type="button" onclick="openResourceModal('Youth Devotional Memory Verses')" class="w-full py-2.5 border border-navy text-navy font-semibold text-xs rounded-lg hover:bg-navy hover:text-ivory transition">
                            <i class="fa-solid fa-download mr-1"></i> Access Guide
                        </button>
                    </div>
                </div>
            </div>
        </section>

        <!-- Section 8: Support the Mission -->
        <section id="support" class="py-20 bg-ivory-paper border-t border-b border-borderSubtle">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="text-center max-w-3xl mx-auto mb-16">
                    <span class="text-gold font-semibold uppercase tracking-wider text-xs">Partner With Us</span>
                    <h2 class="text-3xl sm:text-4xl font-serif-custom font-bold text-navy mt-1">Support the Mission</h2>
                    <p class="text-muted mt-2 text-sm sm:text-base">Your prayers, volunteer time, and financial contributions empower our work.</p>
                    <div class="w-16 h-1 bg-gold mx-auto mt-4 rounded-full"></div>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                    <!-- Prayer Partnership -->
                    <div class="bg-ivory rounded-2xl border border-borderSubtle p-8 shadow-sm flex flex-col justify-between">
                        <div>
                            <div class="w-12 h-12 rounded-xl bg-gold/10 text-gold flex items-center justify-center mb-6 text-2xl">
                                <i class="fa-solid fa-hands-praying"></i>
                            </div>
                            <h3 class="font-serif-custom text-xl font-bold text-navy mb-3">Prayer Partnership</h3>
                            <p class="text-muted text-sm leading-relaxed mb-6">
                                Join our dedicated prayer circle to receive monthly updates and intercede for children, Sunday school teachers, and church choir members.
                            </p>
                        </div>
                        <a href="#contact" class="w-full py-3 bg-navy hover:bg-navy-light text-ivory text-center font-semibold text-sm rounded-lg transition">
                            Join Prayer List
                        </a>
                    </div>

                    <!-- Volunteer & Mentor -->
                    <div class="bg-ivory rounded-2xl border border-borderSubtle p-8 shadow-sm flex flex-col justify-between">
                        <div>
                            <div class="w-12 h-12 rounded-xl bg-gold/10 text-gold flex items-center justify-center mb-6 text-2xl">
                                <i class="fa-solid fa-hand-holding-heart"></i>
                            </div>
                            <h3 class="font-serif-custom text-xl font-bold text-navy mb-3">Volunteer & Mentor</h3>
                            <p class="text-muted text-sm leading-relaxed mb-6">
                                Offer your skills in teaching, music, art, or logistics to support local weekend children’s workshops and choir gatherings.
                            </p>
                        </div>
                        <a href="#contact" class="w-full py-3 bg-navy hover:bg-navy-light text-ivory text-center font-semibold text-sm rounded-lg transition">
                            Sign Up to Volunteer
                        </a>
                    </div>

                    <!-- Financial Support -->
                    <div class="bg-ivory rounded-2xl border border-gold/40 p-8 shadow-md flex flex-col justify-between relative overflow-hidden">
                        <div class="absolute top-0 right-0 bg-gold text-navy text-[10px] font-bold uppercase tracking-wider px-3 py-1 rounded-bl-lg">
                            Direct Impact
                        </div>
                        <div>
                            <div class="w-12 h-12 rounded-xl bg-gold/20 text-gold flex items-center justify-center mb-6 text-2xl">
                                <i class="fa-solid fa-gift"></i>
                            </div>
                            <h3 class="font-serif-custom text-xl font-bold text-navy mb-3">Financial Giving</h3>
                            <p class="text-muted text-sm leading-relaxed mb-6">
                                Help fund Sunday school study materials, children's snacks, musical equipment, and student educational sponsorships.
                            </p>
                        </div>
                        <button type="button" onclick="openGivingModal()" class="w-full py-3 bg-gold hover:bg-gold-light text-navy font-bold text-center text-sm rounded-lg transition shadow">
                            View Support Details
                        </button>
                    </div>
                </div>

                <!-- Transparency Callout -->
                <div class="mt-12 bg-navy text-ivory p-6 rounded-xl border border-gold/20 flex flex-col sm:flex-row items-center justify-between gap-4">
                    <div class="flex items-center space-x-4">
                        <i class="fa-solid fa-shield-halved text-gold text-3xl shrink-0"></i>
                        <div>
                            <h4 class="font-serif-custom text-lg font-bold">Stewardship & Transparency</h4>
                            <p class="text-xs text-ivory/70">All gifts directly support Foursquare Gospel Church children's ministry equipment, educational resources, and youth choir training.</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Section 9: Contact & Prayer Requests -->
        <section id="contact" class="py-20 bg-ivory">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-12">
                    
                    <!-- Contact Details -->
                    <div class="lg:col-span-5 space-y-8">
                        <div>
                            <span class="text-gold font-semibold uppercase tracking-wider text-xs">Reach Out</span>
                            <h2 class="text-3xl sm:text-4xl font-serif-custom font-bold text-navy mt-1">Get in Touch</h2>
                            <p class="text-muted mt-3 text-sm sm:text-base leading-relaxed">
                                Whether you have a prayer request, want to invite me for a seminar, or desire to collaborate in children's ministry, I welcome your message.
                            </p>
                            <div class="w-16 h-1 bg-gold mt-4 rounded-full"></div>
                        </div>

                        <div class="space-y-4">
                            <div class="flex items-start space-x-4">
                                <div class="w-10 h-10 rounded-lg bg-navy/5 text-navy flex items-center justify-center shrink-0">
                                    <i class="fa-solid fa-church text-gold"></i>
                                </div>
                                <div>
                                    <h4 class="font-serif-custom text-sm font-bold text-navy">Church Affiliation</h4>
                                    <p class="text-muted text-xs">Foursquare Gospel Church</p>
                                </div>
                            </div>

                            <div class="flex items-start space-x-4">
                                <div class="w-10 h-10 rounded-lg bg-navy/5 text-navy flex items-center justify-center shrink-0">
                                    <i class="fa-solid fa-envelope text-gold"></i>
                                </div>
                                <div>
                                    <h4 class="font-serif-custom text-sm font-bold text-navy">Email Contact</h4>
                                    <p class="text-muted text-xs">contact@atikajonathan.org</p>
                                </div>
                            </div>

                            <div class="flex items-start space-x-4">
                                <div class="w-10 h-10 rounded-lg bg-navy/5 text-navy flex items-center justify-center shrink-0">
                                    <i class="fa-solid fa-location-dot text-gold"></i>
                                </div>
                                <div>
                                    <h4 class="font-serif-custom text-sm font-bold text-navy">Ministry Location</h4>
                                    <p class="text-muted text-xs">Serving Locally & Regionally</p>
                                </div>
                            </div>
                        </div>

                        <div class="p-6 bg-navy text-ivory rounded-xl border border-gold/30">
                            <h4 class="font-serif-custom text-base font-bold text-gold mb-2"><i class="fa-solid fa-heart mr-2"></i>A Personal Note</h4>
                            <p class="text-xs text-ivory/80 leading-relaxed italic">
                                "Every message is read with prayer and care. Please let me know how I can pray for you and your family today."
                            </p>
                        </div>
                    </div>

                    <!-- Contact Form -->
                    <div class="lg:col-span-7 bg-ivory-paper p-8 rounded-2xl border border-borderSubtle shadow-sm">
                        <form id="contact-form" onsubmit="handleContactSubmit(event)" class="space-y-6">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-6">
                                <div>
                                    <label class="block text-xs font-semibold uppercase tracking-wider text-navy mb-2">Your Full Name *</label>
                                    <input type="text" required class="w-full px-4 py-3 rounded-lg bg-ivory border border-borderSubtle text-charcoal focus:outline-none focus:border-gold text-sm" placeholder="e.g. John Doe">
                                </div>
                                <div>
                                    <label class="block text-xs font-semibold uppercase tracking-wider text-navy mb-2">Your Email Address *</label>
                                    <input type="email" required class="w-full px-4 py-3 rounded-lg bg-ivory border border-borderSubtle text-charcoal focus:outline-none focus:border-gold text-sm" placeholder="john@example.com">
                                </div>
                            </div>

                            <div>
                                <label class="block text-xs font-semibold uppercase tracking-wider text-navy mb-2">Subject</label>
                                <input type="text" class="w-full px-4 py-3 rounded-lg bg-ivory border border-borderSubtle text-charcoal focus:outline-none focus:border-gold text-sm" placeholder="e.g. Prayer Request / Speaker Invitation">
                            </div>

                            <div>
                                <label class="block text-xs font-semibold uppercase tracking-wider text-navy mb-2">Areas of Interest (Select all that apply)</label>
                                <div class="grid grid-cols-1 sm:grid-cols-2 gap-3 text-xs text-charcoal/80">
                                    <label class="flex items-center space-x-2 cursor-pointer">
                                        <input type="checkbox" class="rounded text-gold focus:ring-gold">
                                        <span>Prayer Request</span>
                                    </label>
                                    <label class="flex items-center space-x-2 cursor-pointer">
                                        <input type="checkbox" class="rounded text-gold focus:ring-gold">
                                        <span>Sunday School Workshops</span>
                                    </label>
                                    <label class="flex items-center space-x-2 cursor-pointer">
                                        <input type="checkbox" class="rounded text-gold focus:ring-gold">
                                        <span>Choir Ministry Consultation</span>
                                    </label>
                                    <label class="flex items-center space-x-2 cursor-pointer">
                                        <input type="checkbox" class="rounded text-gold focus:ring-gold">
                                        <span>General Inquiries</span>
                                    </label>
                                </div>
                            </div>

                            <div>
                                <label class="block text-xs font-semibold uppercase tracking-wider text-navy mb-2">Your Message / Prayer Request *</label>
                                <textarea rows="5" required class="w-full px-4 py-3 rounded-lg bg-ivory border border-borderSubtle text-charcoal focus:outline-none focus:border-gold text-sm" placeholder="Write your message or prayer request here..."></textarea>
                            </div>

                            <button type="submit" class="w-full py-3.5 bg-gold hover:bg-gold-light text-navy font-bold rounded-lg transition shadow-md">
                                Send Message
                            </button>
                        </form>

                        <div id="contact-success" class="hidden mt-6 p-4 bg-navy text-gold border border-gold/40 rounded-xl text-center font-medium text-sm">
                            <i class="fa-solid fa-circle-check text-lg mr-2"></i> Thank you! Your message has been sent successfully. I will respond as soon as possible.
                        </div>
                    </div>
                </div>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="bg-navy-dark text-ivory/80 border-t border-navy-light py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-12 gap-8 pb-12 border-b border-navy-light">
                
                <!-- Col 1: Identity -->
                <div class="md:col-span-5 space-y-4">
                    <div class="flex items-center space-x-3">
                        <div class="w-8 h-8 rounded-full border border-gold flex items-center justify-center bg-navy text-gold font-serif text-sm font-bold">
                            AJ
                        </div>
                        <span class="font-serif-custom text-lg font-bold text-ivory">ATIKA JONATHAN MATATA DOMINIC</span>
                    </div>
                    <p class="text-xs text-ivory/60 leading-relaxed max-w-sm">
                        Serving God faithfully through children's teaching, choir direction, and pulpit ministry under Foursquare Gospel Church.
                    </p>
                </div>

                <!-- Col 2: Navigation Links -->
                <div class="md:col-span-3 space-y-2">
                    <h4 class="text-xs font-semibold text-gold uppercase tracking-wider mb-3">Quick Navigation</h4>
                    <div class="grid grid-cols-2 gap-2 text-xs">
                        <a href="#story" class="hover:text-gold transition">Story</a>
                        <a href="#ministry" class="hover:text-gold transition">Ministry</a>
                        <a href="#sermons" class="hover:text-gold transition">Sermons</a>
                        <a href="#gallery" class="hover:text-gold transition">Gallery</a>
                        <a href="#training" class="hover:text-gold transition">Training</a>
                        <a href="#vision" class="hover:text-gold transition">Vision</a>
                        <a href="#resources" class="hover:text-gold transition">Resources</a>
                        <a href="#support" class="hover:text-gold transition">Support</a>
                    </div>
                </div>

                <!-- Col 3: Scripture Quote -->
                <div class="md:col-span-4 space-y-2 text-xs">
                    <h4 class="text-xs font-semibold text-gold uppercase tracking-wider mb-3">Scripture Anchor</h4>
                    <p class="italic text-ivory/70 font-serif-custom">
                        "Let no one despise you for your youth, but set the believers an example in speech, in conduct, in love, in faith, in purity."
                    </p>
                    <span class="block text-gold text-[11px] font-mono">— 1 Timothy 4:12</span>
                </div>
            </div>

            <div class="pt-8 flex flex-col sm:flex-row items-center justify-between text-xs text-ivory/50 gap-4">
                <p>&copy; <span id="year"></span> Atika Jonathan Matata Dominic. All Rights Reserved.</p>
                <div class="flex space-x-4">
                    <a href="#main-header" class="hover:text-gold transition">Back to Top <i class="fa-solid fa-arrow-up ml-1"></i></a>
                </div>
            </div>
        </div>
    </footer>

    <!-- Modals -->
    
    <!-- Resource Modal -->
    <div id="resource-modal" class="fixed inset-0 z-50 hidden bg-navy/80 backdrop-blur-sm flex items-center justify-center p-4">
        <div class="bg-ivory-paper border border-borderSubtle rounded-2xl max-w-md w-full p-6 shadow-2xl relative">
            <button type="button" onclick="closeResourceModal()" class="absolute top-4 right-4 text-muted hover:text-navy text-lg">
                <i class="fa-solid fa-xmark"></i>
            </button>
            <div class="w-12 h-12 rounded-full bg-gold/20 text-gold flex items-center justify-center mb-4 text-xl">
                <i class="fa-solid fa-file-arrow-down"></i>
            </div>
            <h3 id="modal-resource-title" class="font-serif-custom text-xl font-bold text-navy mb-2">Resource Download</h3>
            <p class="text-xs text-muted mb-6">Enter your email address below to receive instant access link to this ministry resource.</p>

            <form onsubmit="handleResourceDownload(event)" class="space-y-4">
                <div>
                    <label class="block text-xs font-semibold uppercase tracking-wider text-navy mb-1">Your Email</label>
                    <input type="email" required class="w-full px-4 py-2.5 rounded-lg bg-ivory border border-borderSubtle text-charcoal focus:outline-none focus:border-gold text-sm" placeholder="you@example.com">
                </div>
                <button type="submit" class="w-full py-3 bg-gold hover:bg-gold-light text-navy font-bold rounded-lg transition text-sm">
                    Send Download Link
                </button>
            </form>
            <div id="modal-download-success" class="hidden mt-4 p-3 bg-navy text-gold rounded-lg text-xs text-center">
                Download link dispatched to your inbox!
            </div>
        </div>
    </div>

    <!-- Giving Modal -->
    <div id="giving-modal" class="fixed inset-0 z-50 hidden bg-navy/80 backdrop-blur-sm flex items-center justify-center p-4">
        <div class="bg-navy-light border border-gold/30 text-ivory rounded-2xl max-w-lg w-full p-6 shadow-2xl relative">
            <button type="button" onclick="closeGivingModal()" class="absolute top-4 right-4 text-ivory/60 hover:text-gold text-lg">
                <i class="fa-solid fa-xmark"></i>
            </button>
            <div class="w-12 h-12 rounded-full bg-gold/20 text-gold flex items-center justify-center mb-4 text-xl">
                <i class="fa-solid fa-hand-holding-dollar"></i>
            </div>
            <h3 class="font-serif-custom text-2xl font-bold text-ivory mb-2">Financial Partnership</h3>
            <p class="text-xs text-ivory/70 mb-6">Thank you for supporting the children's and musical ministry. All contributions directly fund ministry materials and youth activities.</p>

            <div class="space-y-4 text-xs">
                <div class="p-4 bg-navy rounded-xl border border-navy-dark">
                    <span class="block text-gold font-bold uppercase mb-1">Foursquare Church Ministry Fund</span>
                    <p class="text-ivory/80">For direct church contributions, please specify: <strong>"Children & Choir Ministry - Atika Jonathan"</strong></p>
                </div>
                
                <div class="p-4 bg-navy rounded-xl border border-navy-dark">
                    <span class="block text-gold font-bold uppercase mb-1">Personal Inquiries & Direct Aid</span>
                    <p class="text-ivory/80">For sponsorship of specific student materials or choir equipment, please write to us via the contact form.</p>
                </div>
            </div>

            <div class="mt-6 pt-4 border-t border-navy-dark flex justify-end">
                <button type="button" onclick="closeGivingModal()" class="px-5 py-2 bg-gold text-navy font-bold rounded-lg text-xs hover:bg-gold-light transition">
                    Close Window
                </button>
            </div>
        </div>
    </div>

    <!-- JavaScript Interactions -->
    <script>
        // Set dynamic copyright year
        document.getElementById('year').textContent = new Date().getFullYear();

        // Mobile Menu Toggle
        const mobileMenuBtn = document.getElementById('mobile-menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');
        const menuIcon = document.getElementById('menu-icon');

        mobileMenuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
            if (mobileMenu.classList.contains('hidden')) {
                menuIcon.classList.remove('fa-xmark');
                menuIcon.classList.add('fa-bars');
            } else {
                menuIcon.classList.remove('fa-bars');
                menuIcon.classList.add('fa-xmark');
            }
        });

        // Close mobile menu when clicking nav links
        document.querySelectorAll('.mobile-nav-link').forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
                menuIcon.classList.remove('fa-xmark');
                menuIcon.classList.add('fa-bars');
            });
        });

        // Simulated Audio Player State
        let isPlaying = false;
        function toggleAudioPlay() {
            isPlaying = !isPlaying;
            const playIcon = document.getElementById('play-icon');
            if (isPlaying) {
                playIcon.classList.remove('fa-play');
                playIcon.classList.add('fa-pause');
            } else {
                playIcon.classList.remove('fa-pause');
                playIcon.classList.add('fa-play');
            }
        }

        function selectSermon(title, desc, duration) {
            document.getElementById('current-sermon-title').textContent = title;
            document.getElementById('current-sermon-desc').textContent = desc;
            if (isPlaying) toggleAudioPlay();
            window.scrollTo({
                top: document.getElementById('sermons').offsetTop - 80,
                behavior: 'smooth'
            });
        }

        // Workshop Form Submission Handler
        function handleWorkshopSubmit(e) {
            e.preventDefault();
            document.getElementById('workshop-form').reset();
            const successMsg = document.getElementById('workshop-success');
            successMsg.classList.remove('hidden');
            setTimeout(() => {
                successMsg.classList.add('hidden');
            }, 5000);
        }

        // Contact Form Submission Handler
        function handleContactSubmit(e) {
            e.preventDefault();
            document.getElementById('contact-form').reset();
            const successMsg = document.getElementById('contact-success');
            successMsg.classList.remove('hidden');
            setTimeout(() => {
                successMsg.classList.add('hidden');
            }, 6000);
        }

        // Resource Download Modal Functions
        function openResourceModal(title) {
            document.getElementById('modal-resource-title').textContent = title;
            document.getElementById('modal-download-success').classList.add('hidden');
            document.getElementById('resource-modal').classList.remove('hidden');
        }

        function closeResourceModal() {
            document.getElementById('resource-modal').classList.add('hidden');
        }

        function handleResourceDownload(e) {
            e.preventDefault();
            const successMsg = document.getElementById('modal-download-success');
            successMsg.classList.remove('hidden');
            setTimeout(() => {
                closeResourceModal();
            }, 2500);
        }

        // Giving Modal Functions
        function openGivingModal() {
            document.getElementById('giving-modal').classList.remove('hidden');
        }

        function closeGivingModal() {
            document.getElementById('giving-modal').classList.add('hidden');
        }
    </script>
</body>
</html>
