<!DOCTYPE html>
<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dedy Maulana Hamzah | Professional Portfolio</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <!-- FontAwesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        primary: '#1e3a8a', // Deep Blue
                        secondary: '#3b82f6', // Bright Blue
                        gold: '#D4AF37', // Elegant Gold
                        darkbase: '#050505', // Almost Black
                        cardbase: '#111111', // Dark Gray for cards
                        cardborder: '#222222'
                    }
                }
            }
        }
    </script>
    <style>
        /* Custom Styles for timeline and minor details */
        body {
            background-color: #050505;
        }
        .timeline-dot {
            width: 16px;
            height: 16px;
            background-color: #D4AF37; /* Gold */
            border-radius: 50%;
            position: absolute;
            left: -8px;
            top: 6px;
            border: 3px solid #050505;
            box-shadow: 0 0 10px rgba(212, 175, 55, 0.5);
        }
        .glass-nav {
            background: rgba(5, 5, 5, 0.85);
            backdrop-filter: blur(12px);
        }
        /* Gold text gradient */
        .text-gradient-gold {
            background: linear-gradient(to right, #D4AF37, #F3E5AB, #D4AF37);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
    </style>
</head>
<body class="text-slate-300 font-sans antialiased selection:bg-gold selection:text-black">

    <!-- Navigation -->
    <nav class="fixed w-full z-50 glass-nav border-b border-white/10 transition-all duration-300" id="navbar">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-20">
                <div class="flex-shrink-0 flex items-center">
                    <a href="#home" class="text-2xl font-bold text-white tracking-tight">E-Portofolio<span class="text-gold">.</span></a>
                </div>
                <div class="hidden md:flex space-x-8">
                    <a href="#about" class="text-slate-400 hover:text-gold font-medium transition-colors">Tentang Saya</a>
                    <a href="#skills" class="text-slate-400 hover:text-gold font-medium transition-colors">Keahlian</a>
                    <a href="#experience" class="text-slate-400 hover:text-gold font-medium transition-colors">Pengalaman</a>
                    <a href="#education" class="text-slate-400 hover:text-gold font-medium transition-colors">Pendidikan</a>
                    <a href="#portfolio" class="text-slate-400 hover:text-gold font-medium transition-colors">Portofolio</a>
                    <a href="#contact" class="text-slate-400 hover:text-gold font-medium transition-colors">Kontak</a>
                </div>
                <div class="md:hidden flex items-center">
                    <button id="mobile-menu-btn" class="text-slate-400 hover:text-gold focus:outline-none">
                        <i class="fas fa-bars text-2xl"></i>
                    </button>
                </div>
            </div>
        </div>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-cardbase border-t border-white/10 absolute w-full shadow-2xl">
            <div class="px-4 pt-2 pb-6 space-y-2">
                <a href="#about" class="block px-3 py-2 rounded-md text-base font-medium text-slate-300 hover:text-gold hover:bg-white/5">Tentang Saya</a>
                <a href="#skills" class="block px-3 py-2 rounded-md text-base font-medium text-slate-300 hover:text-gold hover:bg-white/5">Keahlian</a>
                <a href="#experience" class="block px-3 py-2 rounded-md text-base font-medium text-slate-300 hover:text-gold hover:bg-white/5">Pengalaman</a>
                <a href="#education" class="block px-3 py-2 rounded-md text-base font-medium text-slate-300 hover:text-gold hover:bg-white/5">Pendidikan</a>
                <a href="#portfolio" class="block px-3 py-2 rounded-md text-base font-medium text-slate-300 hover:text-gold hover:bg-white/5">Portofolio</a>
                <a href="#contact" class="block px-3 py-2 rounded-md text-base font-medium text-slate-300 hover:text-gold hover:bg-white/5">Kontak</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="pt-32 pb-20 md:pt-40 md:pb-28 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col-reverse md:flex-row items-center gap-12 relative overflow-hidden">
        <!-- Glow effect background -->
        <div class="absolute top-1/4 left-1/4 w-96 h-96 bg-primary/20 rounded-full blur-3xl -z-10"></div>
        <div class="absolute bottom-1/4 right-1/4 w-96 h-96 bg-gold/10 rounded-full blur-3xl -z-10"></div>

        <div class="w-full md:w-3/5 text-center md:text-left z-10">
            <div class="inline-block px-4 py-1.5 rounded-full bg-white/5 text-gold font-semibold text-sm mb-6 border border-gold/30 backdrop-blur-sm">
                B2B Sales Professional & Digital Marketing Enthusiast
            </div>
            <h1 class="text-4xl md:text-6xl font-bold text-white leading-tight mb-6">
                Halo, Saya <br><span class="text-gradient-gold">Dedy Maulana Hamzah</span>
            </h1>
            <p class="text-lg md:text-xl text-slate-400 mb-8 leading-relaxed max-w-2xl">
                Profesional berpengalaman dalam penjualan B2B, Manajemen E-Commerce dan Content Creations. Berorientasi pada target, analisis data, Editor dan Script Writer. Siap mengembangkan strategi pemasaran digital yang inovatif.
            </p>
            <div class="flex flex-col sm:flex-row items-center justify-center md:justify-start gap-4 flex-wrap">
                <a href="#contact" class="w-full sm:w-auto px-8 py-3.5 bg-gold text-black font-bold rounded-lg shadow-[0_0_15px_rgba(212,175,55,0.4)] hover:shadow-[0_0_25px_rgba(212,175,55,0.6)] hover:bg-[#ebd077] transition-all duration-300 text-center flex items-center justify-center gap-2">
                    <i class="fas fa-envelope"></i> Hubungi Saya
                </a>
                <a href="#about" class="w-full sm:w-auto px-8 py-3.5 bg-transparent text-gold font-medium rounded-lg border border-gold hover:bg-gold/10 transition-all duration-300 text-center flex items-center justify-center gap-2">
                    <i class="fas fa-file-alt"></i> Lihat Profil
                </a>
                <!-- Download CV Button -->
                <a href="/Users/mac/Desktop/CV - Dedy Maulana H 2.pdf" download="/Users/mac/Desktop/CV - Dedy Maulana H 2.pdf" class="w-full sm:w-auto px-8 py-3.5 bg-primary/20 text-blue-400 font-medium rounded-lg border border-blue-500 hover:bg-blue-600 hover:text-white transition-all duration-300 text-center flex items-center justify-center gap-2 shadow-[0_0_15px_rgba(59,130,246,0.2)]">
                    <i class="fas fa-download"></i> Unduh CV
                </a>
            </div>
        </div>
        <div class="w-full md:w-2/5 flex justify-center z-10">
            <div class="relative group">
                <!-- Decorative background elements -->
                <div class="absolute -inset-4 bg-gradient-to-tr from-gold to-primary rounded-[2rem] transform rotate-3 opacity-50 group-hover:rotate-6 transition-transform duration-500 -z-10 blur-sm"></div>
                <!-- Profile Image: Updated to DSC09508.jpg -->
                <img src="DSC09508.jpg" alt="Dedy Maulana Hamzah" class="w-72 md:w-[22rem] rounded-[1.5rem] shadow-2xl object-cover border-2 border-gold/50 aspect-[4/5] z-10 relative">
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-cardbase border-y border-white/5 relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row gap-12 items-center">
                <div class="w-full md:w-1/2">
                    <h2 class="text-sm font-bold tracking-widest text-gold uppercase mb-2">Tentang Saya</h2>
                    <h3 class="text-3xl md:text-4xl font-bold text-white mb-6">Mendorong Pertumbuhan Melalui <span class="text-primary text-blue-400">Penjualan Strategis</span></h3>
                    <div class="space-y-4 text-slate-400 leading-relaxed text-lg">
                        <p>
                            Saya memiliki rekam jejak yang terbukti dalam penjualan online maupun offline, dengan keahlian khusus di sektor B2B dan konten kreasi . Saya terbiasa menangani proses penjualan dari awal hingga akhir (*end-to-end*), melakukan analisis data pasar, serta memimpin koordinasi lintas tim.
                        </p>
                        <p>
                            Pengalaman sebagai admin sales telah mempertajam ketelitian saya dalam menyusun laporan yang komprehensif dan mengurai data penjualan yang kompleks. Saya adalah individu yang komunikatif, sangat adaptif terhadap dinamika pasar, dan selalu berorientasi pada pencapaian target.
                        </p>
                        <p class="font-medium text-gold">
                            Saat ini, saya antusias untuk terus mengembangkan karier di bidang Digital Marketing, dengan fokus utama pada perancangan strategi penjualan dan pengembangan bisnis perusahaan yang berbasis digital.
                        </p>
                    </div>
                </div>
                <div class="w-full md:w-1/2 grid grid-cols-2 gap-4">
                    <div class="bg-darkbase p-6 rounded-xl border border-white/10 hover:border-gold/50 transition-colors shadow-sm group">
                        <i class="fas fa-chart-line text-3xl text-gold mb-4 group-hover:scale-110 transition-transform"></i>
                        <h4 class="font-bold text-white mb-2">Goal-Oriented</h4>
                        <p class="text-sm text-slate-500">Fokus pada pencapaian target dan pertumbuhan metrik penjualan.</p>
                    </div>
                    <div class="bg-darkbase p-6 rounded-xl border border-white/10 hover:border-gold/50 transition-colors shadow-sm group">
                        <i class="fas fa-users text-3xl text-blue-500 mb-4 group-hover:scale-110 transition-transform"></i>
                        <h4 class="font-bold text-white mb-2">Team Coordination</h4>
                        <p class="text-sm text-slate-500">Kemampuan kolaborasi dan manajemen lintas divisi yang efektif.</p>
                    </div>
                    <div class="bg-darkbase p-6 rounded-xl border border-white/10 hover:border-gold/50 transition-colors shadow-sm group">
                        <i class="fas fa-magnifying-glass-chart text-3xl text-blue-500 mb-4 group-hover:scale-110 transition-transform"></i>
                        <h4 class="font-bold text-white mb-2">Data Analysis</h4>
                        <p class="text-sm text-slate-500">Menganalisis data pasar untuk merumuskan strategi yang akurat.</p>
                    </div>
                    <div class="bg-darkbase p-6 rounded-xl border border-white/10 hover:border-gold/50 transition-colors shadow-sm group">
                        <i class="fas fa-bolt text-3xl text-gold mb-4 group-hover:scale-110 transition-transform"></i>
                        <h4 class="font-bold text-white mb-2">Adaptable</h4>
                        <p class="text-sm text-slate-500">Cepat beradaptasi dengan dinamika dan tren pasar modern.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="py-20 bg-darkbase relative overflow-hidden">
        <div class="absolute right-0 top-0 w-64 h-64 bg-primary/10 rounded-full blur-3xl -z-10"></div>
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="text-center mb-16">
                <h2 class="text-sm font-bold tracking-widest text-gold uppercase mb-2">Kompetensi Inti</h2>
                <h3 class="text-3xl md:text-4xl font-bold text-white">Keahlian & Perangkat</h3>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Skill Card 1 -->
                <div class="bg-cardbase p-8 rounded-2xl border border-cardborder hover:border-gold/50 hover:shadow-[0_0_20px_rgba(212,175,55,0.1)] transition-all group">
                    <div class="w-14 h-14 bg-white/5 border border-white/10 text-gold rounded-xl flex items-center justify-center text-2xl mb-6 group-hover:bg-gold/10 transition-colors">
                        <i class="fas fa-handshake"></i>
                    </div>
                    <h4 class="text-xl font-bold text-white mb-4">B2B Sales Strategy</h4>
                    <ul class="space-y-3 text-slate-400">
                        <li class="flex items-start gap-3"><i class="fas fa-check text-blue-500 mt-1 text-sm"></i> Business Development</li>
                        <li class="flex items-start gap-3"><i class="fas fa-check text-blue-500 mt-1 text-sm"></i> Strategic Negotiation</li>
                        <li class="flex items-start gap-3"><i class="fas fa-check text-blue-500 mt-1 text-sm"></i> Market Penetration</li>
                    </ul>
                </div>

                <!-- Skill Card 2 -->
                <div class="bg-cardbase p-8 rounded-2xl border border-cardborder hover:border-gold/50 hover:shadow-[0_0_20px_rgba(212,175,55,0.1)] transition-all group">
                    <div class="w-14 h-14 bg-white/5 border border-white/10 text-blue-400 rounded-xl flex items-center justify-center text-2xl mb-6 group-hover:bg-blue-500/10 transition-colors">
                        <i class="fas fa-store"></i>
                    </div>
                    <h4 class="text-xl font-bold text-white mb-4">E-Commerce Management</h4>
                    <ul class="space-y-3 text-slate-400">
                        <li class="flex items-start gap-3"><i class="fas fa-check text-gold mt-1 text-sm"></i> Operational Leadership</li>
                        <li class="flex items-start gap-3"><i class="fas fa-check text-gold mt-1 text-sm"></i> Client Relationship</li>
                        <li class="flex items-start gap-3"><i class="fas fa-check text-gold mt-1 text-sm"></i> Digital Content Creation</li>
                        <li class="flex items-start gap-3"><i class="fas fa-check text-gold mt-1 text-sm"></i> Target Oriented</li>
                    </ul>
                </div>

                <!-- Skill Card 3 -->
                <div class="bg-cardbase p-8 rounded-2xl border border-cardborder hover:border-gold/50 hover:shadow-[0_0_20px_rgba(212,175,55,0.1)] transition-all group">
                    <div class="w-14 h-14 bg-white/5 border border-white/10 text-gold rounded-xl flex items-center justify-center text-2xl mb-6 group-hover:bg-gold/10 transition-colors">
                        <i class="fas fa-laptop-code"></i>
                    </div>
                    <h4 class="text-xl font-bold text-white mb-4">Software & Tools</h4>
                    <ul class="space-y-3 text-slate-400 text-sm">
                        <li class="flex items-start gap-3"><i class="fas fa-check text-blue-500 mt-1 text-xs"></i> Microsoft Office (Excel, Word, PPT)</li>
                        <li class="flex items-start gap-3"><i class="fas fa-check text-blue-500 mt-1 text-xs"></i> Google Workspace</li>
                        <li class="flex items-start gap-3"><i class="fas fa-check text-blue-500 mt-1 text-xs"></i> Marketplace Seller Center</li>
                        <li class="flex items-start gap-3"><i class="fas fa-check text-blue-500 mt-1 text-xs"></i> AI Prompter (ChatGPT, Gemini)</li>
                        <li class="flex items-start gap-3"><i class="fas fa-check text-blue-500 mt-1 text-xs"></i> Multimedia (Capcut, Canva, Music)</li>
                        <li class="flex items-start gap-3"><i class="fas fa-check text-blue-500 mt-1 text-xs"></i> PC & Network Troubleshooting</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Experience Section -->
    <section id="experience" class="py-20 bg-cardbase border-y border-white/5">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-sm font-bold tracking-widest text-gold uppercase mb-2">Riwayat Pekerjaan</h2>
                <h3 class="text-3xl md:text-4xl font-bold text-white">Pengalaman Profesional</h3>
            </div>

            <div class="relative border-l-2 border-white/10 ml-4 md:ml-0">
                
                <!-- Experience 1 -->
                <div class="mb-12 relative pl-8 md:pl-10">
                    <div class="timeline-dot"></div>
                    <div class="flex flex-col md:flex-row md:items-center justify-between mb-2">
                        <h4 class="text-xl font-bold text-white">Sales B2B</h4>
                        <span class="text-sm font-semibold text-gold bg-gold/10 border border-gold/20 px-4 py-1.5 rounded-full w-max mt-2 md:mt-0 shadow-[0_0_10px_rgba(212,175,55,0.1)]">2022 - NOW</span>
                    </div>
                    <h5 class="text-lg font-medium text-blue-400 mb-4">Dist. Vitoza Malang</h5>
                    <p class="text-slate-400 mb-2 leading-relaxed">
                        • Mengembangkan dan membangun kerja sama dengan mitra lama maupun baru, mencapai peningkatan <strong class="text-white">10-15% per tahun</strong>.
                    </p>
                    <p class="text-slate-400 leading-relaxed">
                        • Menangani negosiasi kontrak kerja sama, penagihan, serta memberikan edukasi produk kepada apoteker dan agen guna meningkatkan volume *repeat order*.
                    </p>
                </div>

                <!-- Experience 2 -->
                <div class="mb-12 relative pl-8 md:pl-10">
                    <div class="timeline-dot !bg-slate-600 !border-darkbase !shadow-none"></div>
                    <div class="flex flex-col md:flex-row md:items-center justify-between mb-2">
                        <h4 class="text-xl font-bold text-white">E-Commerce Entrepreneurship</h4>
                        <span class="text-sm font-semibold text-gold bg-gold/10 border border-gold/20 px-4 py-1.5 rounded-full w-max mt-2 md:mt-0 shadow-[0_0_10px_rgba(212,175,55,0.1)]">2019 - NOW</span>
                    </div>
                    <h5 class="text-lg font-medium text-blue-400 mb-4">Skinbae.id - Herbae - Scentbybae</h5>
                    <p class="text-slate-400 mb-2 leading-relaxed">
                        • Managing various online business lines (Herbal Products, Gaming Gear, Fashion &Skincare) with a focus on profitability.
                    </p>
                    <p class="text-slate-400 leading-relaxed">
                        • <strong class="text-white">Upselling & Recommendations:</strong> Secara aktif merekomendasikan dan melakukan Upselling dan Crosselling kepada customer.
                </div>

                <!-- Experience 3 -->
                <div class="mb-12 relative pl-8 md:pl-10">
                    <div class="timeline-dot"></div>
                    <div class="flex flex-col md:flex-row md:items-center justify-between mb-2">
                        <h4 class="text-xl font-bold text-white">Content Creations</h4>
                        <span class="text-sm font-semibold text-gold bg-gold/10 border border-gold/20 px-4 py-1.5 rounded-full w-max mt-2 md:mt-0 shadow-[0_0_10px_rgba(212,175,55,0.1)]">2022 - NOW</span>
                    </div>
                    <h5 class="text-lg font-medium text-blue-400 mb-4">Bocchiw - Bocchiw Official</h5>
                    <p class="text-slate-400 mb-2 leading-relaxed">
                        •  Collaborate as a Video Editor for content creators and affiliate marketers, creating engaging
visual content to increase audience engagement.<strong class="text-white">AOERA - KSECRET dst.</strong>.
                    </p>
                </div>

            </div>
        </div>
    </section>

    <!-- Education Section -->
    <section id="education" class="py-20 bg-darkbase">
        <div class="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-sm font-bold tracking-widest text-gold uppercase mb-2">Latar Belakang Akademis</h2>
                <h3 class="text-3xl md:text-4xl font-bold text-white">Pendidikan</h3>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <!-- Degree 1 -->
                <div class="bg-cardbase p-8 rounded-2xl border border-cardborder border-l-4 border-l-gold hover:border-l-gold/80 hover:bg-white/5 transition-all relative overflow-hidden">
                    <div class="absolute -right-6 -top-6 text-7xl text-white/[0.03] rotate-12"><i class="fas fa-graduation-cap"></i></div>
                    <div class="flex justify-between items-start mb-6 relative z-10">
                        <div class="w-12 h-12 rounded-full bg-gold/10 flex items-center justify-center border border-gold/30 text-gold text-xl">
                            <i class="fas fa-award"></i>
                        </div>
                        <span class="text-sm font-semibold text-gold bg-gold/10 border border-gold/20 px-3 py-1 rounded-full">2025 - Sekarang</span>
                    </div>
                    <h4 class="text-2xl font-bold text-white mb-2 relative z-10">Master's Degree</h4>
                    <h5 class="text-lg font-medium text-blue-400 mb-4 relative z-10">Marketing Management</h5>
                    <p class="text-slate-400 font-medium relative z-10"><i class="fas fa-university mr-2 text-slate-500"></i>Universitas Brawijaya</p>
                </div>

                <!-- Degree 2 -->
                <div class="bg-cardbase p-8 rounded-2xl border border-cardborder border-l-4 border-l-slate-600 hover:bg-white/5 transition-all relative overflow-hidden">
                    <div class="absolute -right-6 -top-6 text-7xl text-white/[0.03] rotate-12"><i class="fas fa-graduation-cap"></i></div>
                    <div class="flex justify-between items-start mb-6 relative z-10">
                        <div class="w-12 h-12 rounded-full bg-white/5 flex items-center justify-center border border-white/10 text-slate-400 text-xl">
                            <i class="fas fa-book"></i>
                        </div>
                        <span class="text-sm font-semibold text-slate-300 bg-white/10 border border-white/10 px-3 py-1 rounded-full">2018 - 2024</span>
                    </div>
                    <h4 class="text-2xl font-bold text-white mb-2 relative z-10">Bachelor's Degree</h4>
                    <h5 class="text-lg font-medium text-slate-300 mb-4 relative z-10">Marketing Management</h5>
                    <p class="text-slate-400 font-medium relative z-10"><i class="fas fa-university mr-2 text-slate-500"></i>Universitas Gajayana</p>
                </div>
            </div>
        </div>
    </section>

<!-- Projects / Entrepreneurship Section -->
<section id="portfolio" class="py-20 bg-cardbase border-y border-white/5 relative">
    <div class="absolute left-0 top-1/2 w-72 h-72 bg-gold/5 rounded-full blur-3xl -z-10"></div>
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
        <div class="text-center mb-16">
            <h2 class="text-sm font-bold tracking-widest text-gold uppercase mb-2">Portofolio & Proyek</h2>
            <h3 class="text-3xl md:text-4xl font-bold text-white">Kewirausahaan & Inisiatif Lepas</h3>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
            
            <!-- Project 1 -->
            <div class="bg-darkbase rounded-2xl border border-cardborder overflow-hidden hover:border-gold/40 transition-all group flex flex-col h-full">
                <div class="h-2 bg-gradient-to-r from-gold to-yellow-600"></div>
                <div class="p-8 flex-1">
                    <div class="text-xs font-bold text-gold/70 mb-3 uppercase tracking-widest">2022 - 2023</div>
                    <h4 class="text-xl font-bold text-white mb-1 group-hover:text-gold transition-colors">Owner & Founder</h4>
                    <h5 class="text-sm font-semibold text-blue-400 mb-4">Dimsum Kudasai (F&B Retail)</h5>
                    <p class="text-slate-400 text-sm leading-relaxed mb-4">
                        Berhasil mengekspansi bisnis kuliner dengan mendirikan dan mengelola 3 cabang aktif dalam 1 tahun. Bertanggung jawab penuh pada operasional dari hulu ke hilir (*supply chain*, negosiasi *supplier*, kontrol kualitas) hingga kepemimpinan SDM.
                    </p>
                </div>
            </div>

            <!-- Project 2 -->
            <div class="bg-darkbase rounded-2xl border border-cardborder overflow-hidden hover:border-blue-500/40 transition-all group flex flex-col h-full">
                <div class="h-2 bg-gradient-to-r from-blue-500 to-primary"></div>
                <div class="p-8 flex-1">
                    <div class="text-xs font-bold text-blue-400/70 mb-3 uppercase tracking-widest">2018 - 2024</div>
                    <h4 class="text-xl font-bold text-white mb-1 group-hover:text-blue-400 transition-colors">Cat House Mainecoon</h4>
                    <h5 class="text-sm font-semibold text-blue-400 mb-4">NEKOMA CAT HOUSE</h5>
                    <p class="text-slate-400 text-sm leading-relaxed mb-4">
                        Membangun dan mengelola usaha cathouse Maine Coon yang mencakup program breeding, perawatan kesehatan, serta pengelolaan kualitas indukan dan kitten untuk menjaga standar ras dan kesejahteraan hewan.
                    </p>
                </div>
            </div>

            <!-- Project 3 (Video Showcase - 5 Videos) -->
            <div class="bg-darkbase rounded-2xl border border-gold/30 overflow-hidden shadow-[0_0_20px_rgba(212,175,55,0.05)] hover:border-gold/50 hover:shadow-[0_0_30px_rgba(212,175,55,0.15)] transition-all duration-500 group md:col-span-2 lg:col-span-3 flex flex-col">
                <div class="h-2 bg-gradient-to-r from-gold via-yellow-400 to-gold"></div>
                <div class="p-8 flex flex-col lg:flex-row gap-8 items-start flex-1">
                    <!-- Deskripsi Konten Kiri (Sticky) -->
                    <div class="w-full lg:w-1/3 lg:sticky lg:top-28">
                        <div class="text-xs font-bold text-gold mb-4 uppercase tracking-widest flex items-center gap-2">
                            <span class="w-2 h-2 rounded-full bg-gold animate-pulse"></span> 2024 - Sekarang
                        </div>
                        <h4 class="text-3xl font-bold text-white mb-2 group-hover:text-gold transition-colors duration-300">Content Production</h4>
                        <h5 class="text-md font-semibold text-blue-400 mb-5 flex items-center gap-2">
                            <i class="fas fa-clapperboard"></i> Video Editor Showcase
                        </h5>
                        <p class="text-slate-400 text-sm leading-relaxed mb-6">
                            Berkolaborasi sebagai Video Editor untuk *content creator* dan *affiliate marketer*. Menciptakan konten visual yang menarik dengan tujuan meningkatkan keterlibatan audiens.
                        </p>
                        <div class="flex flex-wrap gap-2 mb-6">
                            <span class="bg-white/5 text-gold text-xs px-3 py-1.5 rounded-full border border-gold/20 backdrop-blur-sm"><i class="fas fa-cut mr-1"></i> CapCut</span>
                            <span class="bg-white/5 text-gold text-xs px-3 py-1.5 rounded-full border border-gold/20 backdrop-blur-sm"><i class="fas fa-pen-nib mr-1"></i> Canva</span>
                            <span class="bg-white/5 text-gold text-xs px-3 py-1.5 rounded-full border border-gold/20 backdrop-blur-sm"><i class="fas fa-robot mr-1"></i> AI Prompter</span>
                        </div>
                    </div>
                    <!-- Grid 5 Video Kanan -->
                    <div class="w-full lg:w-2/3">
                        <div class="bg-blue-900/10 border border-blue-500/20 text-blue-300 text-xs p-4 rounded-xl mb-6 flex items-start gap-3 backdrop-blur-sm">
                            <i class="fas fa-info-circle mt-0.5 text-blue-400 text-base"></i>
                            <p class="leading-relaxed"><strong>Petunjuk:</strong> Anda dapat mengganti nilai <code>src="..."</code> di setiap elemen video dengan link file video asli milik Anda.</p>
                        </div>
                        <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
                            <!-- Video Utama -->
                            <div class="col-span-2 row-span-2 relative rounded-xl overflow-hidden border-2 border-white/10 hover:border-gold/60 bg-black shadow-lg hover:shadow-[0_0_20px_rgba(212,175,55,0.3)] transition-all duration-300 group/video h-full min-h-[300px] md:min-h-[400px]">
                                <div class="absolute top-4 left-4 bg-black/70 backdrop-blur-md text-gold text-xs font-bold px-3 py-1.5 rounded-lg border border-gold/30 z-10 flex items-center gap-2 shadow-lg">
                                    <i class="fas fa-star text-gold"></i> Featured Work
                                </div>
                                <video class="w-full h-full object-cover bg-black" controls preload="metadata">
                                    <source src="/Users/mac/Desktop/Justin Paul - Bocchiw.mov" type="video/mp4">
                                </video>
                            </div>
                            <!-- Video Kecil 1-4 -->
                            <div class="relative rounded-xl overflow-hidden border border-white/10 hover:border-gold/50 bg-black shadow-inner aspect-[9/16] transition-all duration-300">
                                <video class="w-full h-full object-cover bg-black" controls preload="metadata">
                                    <source src="/Users/mac/Desktop/TI'AM - Bocchiw.mov" type="video/mp4">
                                </video>
                            </div>
                            <div class="relative rounded-xl overflow-hidden border border-white/10 hover:border-gold/50 bg-black shadow-inner aspect-[9/16] transition-all duration-300">
                                <video class="w-full h-full object-cover bg-black" controls preload="metadata">
                                    <source src="/Users/mac/Desktop/Rintik - Bocchiw.mov" type="video/mp4">
                                </video>
                            </div>
                            <div class="relative rounded-xl overflow-hidden border border-white/10 hover:border-gold/50 bg-black shadow-inner aspect-[9/16] transition-all duration-300">
                                <video class="w-full h-full object-cover bg-black" controls preload="metadata">
                                    <source src="/Users/mac/Desktop/Buttered 2 - Bocchiw.mov" type="video/mp4">
                                </video>
                            </div>
                            <div class="relative rounded-xl overflow-hidden border border-white/10 hover:border-gold/50 bg-black shadow-inner aspect-[9/16] transition-all duration-300">
                                <video class="w-full h-full object-cover bg-black" controls preload="metadata">
                                    <source src="/Users/mac/Desktop/Justin Paul - Bocchiw.mov" type="video/mp4">
                                </video>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Project 4 (Telah Disempurnakan) -->
            <div class="bg-darkbase rounded-2xl border border-cardborder overflow-hidden hover:border-gold/40 hover:shadow-[0_0_20px_rgba(212,175,55,0.1)] transition-all duration-300 group flex flex-col h-full">
                <div class="h-2 bg-gradient-to-r from-gold to-yellow-600"></div>
                <div class="p-8 flex-1 flex flex-col">
                    <div class="flex items-center justify-between mb-5">
                        <div class="w-12 h-12 rounded-full bg-gold/10 flex items-center justify-center text-gold border border-gold/20 group-hover:scale-110 transition-transform">
                            <i class="fas fa-gamepad text-xl"></i>
                        </div>
                        <div class="text-xs font-bold text-gold/70 uppercase tracking-widest bg-white/5 px-3 py-1.5 rounded-full border border-white/10 backdrop-blur-sm">2024</div>
                    </div>
                    <h4 class="text-xl font-bold text-white mb-1 group-hover:text-gold transition-colors">Service & Rental</h4>
                    <h5 class="text-sm font-semibold text-blue-400 mb-4">PlayStation Delivery</h5>
                    <p class="text-slate-400 text-sm leading-relaxed mb-4 flex-1">
                        Menginisiasi layanan rental PlayStation inovatif yang dilengkapi sistem pesan-antar (*delivery*). Berfokus pada kemudahan pelanggan dan efisiensi manajemen logistik operasional.
                    </p>
                </div>
            </div>

            <!-- Project 5 (Telah Disempurnakan) -->
            <div class="bg-darkbase rounded-2xl border border-cardborder overflow-hidden hover:border-gold/40 hover:shadow-[0_0_20px_rgba(212,175,55,0.1)] transition-all duration-300 group flex flex-col h-full">
                <div class="h-2 bg-gradient-to-r from-yellow-500 to-gold"></div>
                <div class="p-8 flex-1 flex flex-col">
                    <div class="flex items-center justify-between mb-5">
                        <div class="w-12 h-12 rounded-full bg-gold/10 flex items-center justify-center text-gold border border-gold/20 group-hover:scale-110 transition-transform">
                            <i class="fas fa-graduation-cap text-xl"></i>
                        </div>
                        <div class="text-xs font-bold text-gold/70 uppercase tracking-widest bg-white/5 px-3 py-1.5 rounded-full border border-white/10 backdrop-blur-sm">2023 - 2024</div>
                    </div>
                    <h4 class="text-xl font-bold text-white mb-1 group-hover:text-gold transition-colors">Academic Consultant</h4>
                    <h5 class="text-sm font-semibold text-blue-400 mb-4">Freelance</h5>
                    <p class="text-slate-400 text-sm leading-relaxed mb-4 flex-1">
                        Menyediakan layanan bantuan riset dan penulisan akademis (makalah & tesis) dengan standar akurasi yang tinggi serta manajemen *deadline* yang ketat.
                    </p>
                </div>
            </div>

            <!-- Project 6 (Telah Disempurnakan) -->
            <div class="bg-darkbase rounded-2xl border border-cardborder overflow-hidden hover:border-gold/40 hover:shadow-[0_0_20px_rgba(212,175,55,0.1)] transition-all duration-300 group flex flex-col h-full">
                <div class="h-2 bg-gradient-to-r from-yellow-600 to-yellow-500"></div>
                <div class="p-8 flex-1 flex flex-col">
                    <div class="flex items-center justify-between mb-5">
                        <div class="w-12 h-12 rounded-full bg-gold/10 flex items-center justify-center text-gold border border-gold/20 group-hover:scale-110 transition-transform">
                            <i class="fas fa-handshake text-xl"></i>
                        </div>
                        <div class="text-xs font-bold text-gold/70 uppercase tracking-widest bg-white/5 px-3 py-1.5 rounded-full border border-white/10 backdrop-blur-sm">2016 - Now</div>
                    </div>
                    <h4 class="text-xl font-bold text-white mb-1 group-hover:text-gold transition-colors">Marketplace Trade</h4>
                    <h5 class="text-sm font-semibold text-blue-400 mb-4">Asset Trading</h5>
                    <p class="text-slate-400 text-sm leading-relaxed mb-4 flex-1">
                        Berpengalaman dalam transaksi jual beli aset bernilai (Kendaraan Bermotor & Pengembangbiakan Kucing Maine Coon), yang mengasah kemampuan negosiasi harga dan penilaian aset.
                    </p>
                </div>
            </div>

        </div>
    </div>
</section>

    <!-- Certifications Section -->
    <section class="py-16 bg-darkbase border-b border-white/5">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <h3 class="text-2xl font-bold text-white mb-10 text-center"><i class="fas fa-award text-gold mr-3"></i> Sertifikasi & Pencapaian</h3>
            <div class="flex flex-wrap justify-center gap-4 md:gap-6">
                <div class="bg-cardbase px-6 py-4 rounded-xl border border-cardborder flex items-center gap-4 hover:border-gold/30 transition-colors">
                    <div class="bg-gold/10 text-gold p-3 rounded-full text-xl"><i class="fas fa-language"></i></div>
                    <div>
                        <div class="font-bold text-white text-lg">TOEFL Score 463</div>
                        <div class="text-xs text-slate-500 font-medium tracking-wide">Tahun 2025</div>
                    </div>
                </div>
                <div class="bg-cardbase px-6 py-4 rounded-xl border border-cardborder flex items-center gap-4 hover:border-gold/30 transition-colors">
                    <div class="bg-blue-500/10 text-blue-400 p-3 rounded-full text-xl"><i class="fas fa-brain"></i></div>
                    <div>
                        <div class="font-bold text-white text-lg">TPA Score 546,80</div>
                        <div class="text-xs text-slate-500 font-medium tracking-wide">Tahun 2025</div>
                    </div>
                </div>
                <div class="bg-cardbase px-6 py-4 rounded-xl border border-cardborder flex items-center gap-4 hover:border-gold/30 transition-colors">
                    <div class="bg-gold/10 text-gold p-3 rounded-full text-xl"><i class="fas fa-certificate"></i></div>
                    <div>
                        <div class="font-bold text-white text-lg">Amoeba Marketing</div>
                        <div class="text-xs text-slate-500 font-medium tracking-wide">Tahun 2016</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-24 bg-cardbase relative overflow-hidden">
        <!-- Decoration -->
        <div class="absolute bottom-0 left-1/2 -translate-x-1/2 w-full max-w-2xl h-64 bg-primary/20 rounded-[100%] blur-[80px] -z-10"></div>
        
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 text-center relative z-10">
            <h2 class="text-3xl md:text-5xl font-bold mb-6 text-white">Siap <span class="text-gradient-gold">Berkolaborasi?</span></h2>
            <p class="text-slate-400 mb-10 text-lg max-w-2xl mx-auto leading-relaxed">
                Saya terbuka untuk mendiskusikan peluang karier, proyek kerja sama, atau bagaimana saya dapat memberikan nilai tambah bagi bisnis Anda.
            </p>
            
            <div class="flex flex-col md:flex-row justify-center items-center gap-6 mb-16">
                <a href="mailto:hamzahdedy0000@gmail.com" class="flex items-center gap-4 bg-darkbase border border-white/10 hover:border-gold/50 hover:shadow-[0_0_15px_rgba(212,175,55,0.2)] px-8 py-4 rounded-xl transition-all w-full md:w-auto justify-center group">
                    <div class="w-10 h-10 rounded-full bg-white/5 flex items-center justify-center group-hover:bg-gold/10 transition-colors">
                        <i class="fas fa-envelope text-xl text-gold"></i>
                    </div>
                    <span class="font-medium text-lg text-slate-200 group-hover:text-white">hamzahdedy0000@gmail.com</span>
                </a>
                <a href="https://wa.me/628123253349" target="_blank" class="flex items-center gap-4 bg-darkbase border border-white/10 hover:border-green-500/50 hover:shadow-[0_0_15px_rgba(34,197,94,0.2)] px-8 py-4 rounded-xl transition-all w-full md:w-auto justify-center group">
                    <div class="w-10 h-10 rounded-full bg-white/5 flex items-center justify-center group-hover:bg-green-500/10 transition-colors">
                        <i class="fab fa-whatsapp text-xl text-green-400"></i>
                    </div>
                    <span class="font-medium text-lg text-slate-200 group-hover:text-white">+62 812-3253-3349</span>
                </a>
            </div>

            <div class="inline-flex items-center justify-center gap-3 text-slate-400 bg-white/5 px-6 py-2.5 rounded-full border border-white/10">
                <i class="fas fa-map-marker-alt text-gold"></i>
                <span class="font-medium tracking-wide text-sm">Dau, Kab. Malang, Indonesia</span>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-black py-8 border-t border-white/10 text-center">
        <p class="text-slate-500 text-sm">
            &copy; 2026 Dedy Maulana Hamzah. All Rights Reserved. <br>
            <span class="text-xs mt-2 text-slate-600 inline-block font-medium tracking-widest uppercase">Professional Portfolio</span>
        </p>
    </footer>

    <!-- Script for Mobile Menu & Video Features -->
    <script>
        // --- Mobile Menu Toggle ---
        const btn = document.getElementById('mobile-menu-btn');
        const menu = document.getElementById('mobile-menu');

        btn.addEventListener('click', () => {
            menu.classList.toggle('hidden');
        });

        // Close mobile menu on click
        const links = menu.querySelectorAll('a');
        links.forEach(link => {
            link.addEventListener('click', () => {
                menu.classList.add('hidden');
            });
        });

        // --- Fitur Upload Video Preview ---
        const videoUploader = document.getElementById('video-uploader');
        const videoPlayer = document.getElementById('video-preview-player');
        const videoFileName = document.getElementById('video-file-name');

        if (videoUploader && videoPlayer) {
            videoUploader.addEventListener('change', function(event) {
                const file = event.target.files[0];
                if (file) {
                    // Membuat URL lokal sementara untuk file yang diupload
                    const fileURL = URL.createObjectURL(file);
                    
                    // Memasukkan URL ke dalam tag video dan memutarnya
                    videoPlayer.src = fileURL;
                    videoPlayer.play();
                    
                    // Menampilkan nama file dengan styling Emas (Gold)
                    videoFileName.innerHTML = `<i class="fas fa-check-circle mr-1"></i> Memutar file: <strong>${file.name}</strong>`;
                    videoFileName.classList.remove('hidden');
                }
            });
        }
    </script>
</body>
</html># profile
