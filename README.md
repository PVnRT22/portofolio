# portofolio
<!DOCTYPE html>
<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pandu Dian | Digital Portfolio</title>
    
    <!-- Fonts: Inter for clean, academic readability -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    
    <!-- Icons: FontAwesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        primary: '#0ea5e9',   // Sky blue (Tech/Engineering)
                        secondary: '#14b8a6', // Teal (Chemistry/Sustainability)
                        dark: '#0f172a',      // Slate 900
                        surface: '#f8fafc',   // Slate 50
                    }
                }
            }
        }
    </script>
    <style>
        /* Custom Styles for Polish */
        body { font-family: 'Inter', sans-serif; color: #334155; }
        .glass-nav { background: rgba(255, 255, 255, 0.9); backdrop-filter: blur(10px); }
        .gradient-text { background: linear-gradient(135deg, #0ea5e9, #14b8a6); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
        .card-hover { transition: transform 0.3s ease, box-shadow 0.3s ease; }
        .card-hover:hover { transform: translateY(-5px); box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.1), 0 8px 10px -6px rgba(0, 0, 0, 0.1); }
        .section-padding { padding-top: 5rem; padding-bottom: 5rem; }
    </style>
</head>
<body class="bg-slate-50 antialiased selection:bg-primary selection:text-white">

    <nav class="fixed w-full z-50 glass-nav shadow-sm border-b border-slate-200 transition-all duration-300">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-16">
                <div class="flex-shrink-0 flex items-center">
                    <a href="#home" class="font-bold text-xl tracking-tight text-dark">Pandu<span class="text-primary">Dian.</span></a>
                </div>
                <!-- Desktop Menu -->
                <div class="hidden md:flex space-x-8 items-center">
                    <a href="#about" class="text-sm font-medium text-slate-600 hover:text-primary transition-colors">Tentang</a>
                    <a href="#research" class="text-sm font-medium text-slate-600 hover:text-primary transition-colors">Riset</a>
                    <a href="#projects" class="text-sm font-medium text-slate-600 hover:text-primary transition-colors">Pengalaman Lab</a>
                    <a href="#competencies" class="text-sm font-medium text-slate-600 hover:text-primary transition-colors">Kompetensi</a>
                    <a href="#contact" class="px-4 py-2 rounded-full bg-primary text-white text-sm font-semibold hover:bg-sky-600 transition-colors shadow-md">Hubungi Saya</a>
                </div>
                <!-- Mobile Menu Button -->
                <div class="md:hidden flex items-center">
                    <button id="mobile-menu-btn" class="text-slate-600 hover:text-primary focus:outline-none">
                        <i class="fa-solid fa-bars text-2xl"></i>
                    </button>
                </div>
            </div>
        </div>
        <!-- Mobile Menu Panel -->
        <div id="mobile-menu" class="hidden md:hidden bg-white border-t border-slate-100 absolute w-full shadow-lg">
            <div class="px-2 pt-2 pb-3 space-y-1 sm:px-3">
                <a href="#about" class="block px-3 py-2 text-base font-medium text-slate-700 hover:text-primary hover:bg-slate-50 rounded-md">Tentang</a>
                <a href="#research" class="block px-3 py-2 text-base font-medium text-slate-700 hover:text-primary hover:bg-slate-50 rounded-md">Riset</a>
                <a href="#projects" class="block px-3 py-2 text-base font-medium text-slate-700 hover:text-primary hover:bg-slate-50 rounded-md">Pengalaman Lab</a>
                <a href="#competencies" class="block px-3 py-2 text-base font-medium text-slate-700 hover:text-primary hover:bg-slate-50 rounded-md">Kompetensi</a>
                <a href="#contact" class="block px-3 py-2 text-base font-medium text-primary hover:bg-slate-50 rounded-md">Hubungi Saya</a>
            </div>
        </div>
    </nav>

    <section id="home" class="relative pt-32 pb-20 lg:pt-48 lg:pb-32 overflow-hidden">
        <div class="absolute inset-0 z-0 opacity-20">
            <!-- Background pattern/blobs -->
            <div class="absolute top-0 right-0 w-96 h-96 bg-primary rounded-full mix-blend-multiply filter blur-3xl opacity-30 transform translate-x-1/2 -translate-y-1/4"></div>
            <div class="absolute bottom-0 left-0 w-96 h-96 bg-secondary rounded-full mix-blend-multiply filter blur-3xl opacity-30 transform -translate-x-1/2 translate-y-1/4"></div>
        </div>

        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="flex flex-col-reverse lg:flex-row items-center gap-12 lg:gap-8">
                <!-- Text Content -->
                <div class="w-full lg:w-3/5 text-center lg:text-left">
                    <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-sky-100 text-sky-700 text-sm font-semibold mb-6">
                        <i class="fa-solid fa-flask"></i> Chemical Engineering Student
                    </div>
                    <h1 class="text-4xl sm:text-5xl lg:text-6xl font-extrabold text-dark tracking-tight mb-4 leading-tight">
                        Halo, saya <span class="gradient-text">Pandu Dian</span>
                    </h1>
                    <h2 class="text-xl sm:text-2xl text-slate-600 font-medium mb-6">
                        Research Enthusiast | Aspiring Process Engineer | Future Academic Researcher
                    </h2>
                    <p class="text-base sm:text-lg text-slate-500 mb-8 max-w-2xl mx-auto lg:mx-0 leading-relaxed">
                        Mahasiswa Teknologi Kimia Industri Terapan di Politeknik Negeri Ujung Pandang. Saya percaya sains bukan hanya teori di ruang kelas, melainkan alat untuk memahami dunia dan menciptakan solusi yang berdampak nyata bagi masyarakat.
                    </p>
                    <div class="flex flex-col sm:flex-row gap-4 justify-center lg:justify-start">
                        <a href="#research" class="px-8 py-3 rounded-lg bg-dark text-white font-semibold hover:bg-slate-800 transition-colors shadow-lg hover:shadow-xl text-center">
                            Lihat Fokus Riset
                        </a>
                        <a href="#contact" class="px-8 py-3 rounded-lg bg-white text-dark border border-slate-300 font-semibold hover:border-primary hover:text-primary transition-colors text-center shadow-sm">
                            Mari Berdiskusi
                        </a>
                    </div>
                </div>

                <!-- Profile Image -->
                <div class="w-full lg:w-2/5 flex justify-center lg:justify-end">
                    <div class="relative">
                        <div class="absolute inset-0 bg-gradient-to-tr from-primary to-secondary rounded-2xl transform rotate-3 scale-105 opacity-20"></div>
                        <!-- IMPORTANT: Referencing the user's specific image verbatim -->
                        <img src="Foto profil Pandu.jpeg" alt="Pandu Dian Profile" class="relative rounded-2xl shadow-2xl object-cover w-72 h-96 sm:w-80 sm:h-[420px] lg:w-96 lg:h-[500px] border-4 border-white z-10" onerror="this.src='https://placehold.co/400x500/0f172a/ffffff?text=Pandu+Dian'">
                        
                        <!-- Floating Badges -->
                        <div class="absolute -bottom-6 -left-6 bg-white p-4 rounded-xl shadow-xl z-20 flex items-center gap-3 animate-bounce" style="animation-duration: 3s;">
                            <div class="w-10 h-10 rounded-full bg-green-100 flex items-center justify-center text-green-600">
                                <i class="fa-solid fa-certificate"></i>
                            </div>
                            <div>
                                <p class="text-xs text-slate-500 font-medium">Sertifikasi Standar</p>
                                <p class="text-sm font-bold text-dark">ISO/IEC 17025</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="about" class="section-padding bg-white border-y border-slate-100">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-dark mb-4">Tentang Saya</h2>
                <div class="w-20 h-1 bg-primary mx-auto rounded-full"></div>
            </div>

            <div class="grid md:grid-cols-2 gap-12 items-center">
                <div class="space-y-6 text-slate-600 leading-relaxed text-lg text-justify">
                    <p>
                        Ketertarikan saya terhadap sains telah tumbuh sejak sekolah menengah, ketika saya menyadari bahwa setiap fenomena memiliki penjelasan ilmiah yang dapat ditelusuri melalui ilmu kimia. Perjalanan tersebut membawa saya ke dunia <strong>Teknik Kimia</strong>, bidang yang mempertemukan ilmu dasar, teknologi, rekayasa proses, dan pemecahan masalah dalam skala industri.
                    </p>
                    <p>
                        Sebagai mahasiswa di Politeknik Negeri Ujung Pandang, saya terbiasa berinteraksi dengan perancangan percobaan, pengambilan data, hingga penyusunan laporan ilmiah yang sistematis. Bagi saya, teknik kimia bukan hanya tentang mempelajari proses industri, tetapi juga sarana untuk menciptakan inovasi yang menjawab tantangan lingkungan.
                    </p>
                    <p>
                        Saya menikmati setiap fase penelitian—mulai dari menyusun hipotesis, mengeksekusi eksperimen, hingga menginterpretasikan hasil statistik berdasarkan literatur. <em>Bagi saya, penelitian adalah proses belajar yang tidak pernah berhenti.</em>
                    </p>
                </div>

                <div class="grid grid-cols-1 sm:grid-cols-2 gap-6">
                    <!-- Filosofi Cards -->
                    <div class="bg-slate-50 p-6 rounded-xl border border-slate-100 card-hover">
                        <div class="w-12 h-12 bg-sky-100 text-sky-600 rounded-lg flex items-center justify-center text-xl mb-4">
                            <i class="fa-solid fa-lightbulb"></i>
                        </div>
                        <h3 class="font-bold text-dark mb-2">Rasa Ingin Tahu</h3>
                        <p class="text-sm text-slate-500">Setiap penelitian dimulai dari keberanian untuk bertanya dan observasi.</p>
                    </div>
                    <div class="bg-slate-50 p-6 rounded-xl border border-slate-100 card-hover">
                        <div class="w-12 h-12 bg-teal-100 text-teal-600 rounded-lg flex items-center justify-center text-xl mb-4">
                            <i class="fa-solid fa-scale-balanced"></i>
                        </div>
                        <h3 class="font-bold text-dark mb-2">Integritas Ilmiah</h3>
                        <p class="text-sm text-slate-500">Data harus dapat dipertanggungjawabkan, ditelusuri, dan objektif.</p>
                    </div>
                    <div class="bg-slate-50 p-6 rounded-xl border border-slate-100 card-hover">
                        <div class="w-12 h-12 bg-indigo-100 text-indigo-600 rounded-lg flex items-center justify-center text-xl mb-4">
                            <i class="fa-solid fa-book-open"></i>
                        </div>
                        <h3 class="font-bold text-dark mb-2">Pembelajaran Berkelanjutan</h3>
                        <p class="text-sm text-slate-500">Ilmu selalu berkembang; kemampuan belajar adalah aset terpenting.</p>
                    </div>
                    <div class="bg-slate-50 p-6 rounded-xl border border-slate-100 card-hover">
                        <div class="w-12 h-12 bg-emerald-100 text-emerald-600 rounded-lg flex items-center justify-center text-xl mb-4">
                            <i class="fa-solid fa-leaf"></i>
                        </div>
                        <h3 class="font-bold text-dark mb-2">Dampak Nyata</h3>
                        <p class="text-sm text-slate-500">Riset terbaik memberi manfaat bagi masyarakat dan lingkungan.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="research" class="section-padding bg-slate-900 text-white relative overflow-hidden">
        <!-- Abstract background element -->
        <div class="absolute top-0 right-0 w-1/2 h-full bg-secondary/10 skew-x-12 transform origin-top-right z-0"></div>
        
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <p class="text-secondary font-semibold tracking-wider uppercase text-sm mb-2">Fokus Penelitian Saat Ini</p>
                <h2 class="text-3xl md:text-4xl font-bold mb-4">Material Berkelanjutan & Ekonomi Sirkular</h2>
                <div class="w-20 h-1 bg-secondary mx-auto rounded-full"></div>
            </div>

            <div class="bg-slate-800/80 backdrop-blur-md rounded-2xl border border-slate-700 p-8 md:p-12 shadow-2xl">
                <div class="flex flex-col lg:flex-row gap-10">
                    <div class="lg:w-2/3 space-y-6">
                        <h3 class="text-2xl font-bold text-white leading-tight">
                            Pemurnian Serat Selulosa Asetat Daur Ulang (rCDA) dari Limbah Puntung Rokok dan Aplikasinya pada Campuran Aspal SMA
                        </h3>
                        <p class="text-slate-300 text-lg leading-relaxed text-justify">
                            Penelitian ini lahir dari ketertarikan saya terhadap konsep keberlanjutan. Limbah puntung rokok sering terabaikan, padahal mengandung selulosa asetat yang memiliki nilai material tinggi. Proyek ini memurnikan limbah tersebut menjadi rCDA untuk digunakan sebagai bahan tambahan dalam campuran <em>Stone Matrix Asphalt</em> (SMA), mengubah limbah menjadi material bernilai tambah teknis dan ekonomis.
                        </p>
                        
                        <div class="pt-4">
                            <h4 class="text-lg font-semibold text-secondary mb-4">Kontribusi & Fokus Kajian:</h4>
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 text-slate-300">
                                <div class="flex items-start gap-3">
                                    <i class="fa-solid fa-check-circle text-secondary mt-1"></i>
                                    <span>Preparasi dan pencucian bahan baku</span>
                                </div>
                                <div class="flex items-start gap-3">
                                    <i class="fa-solid fa-check-circle text-secondary mt-1"></i>
                                    <span>Perlakuan kimia menggunakan larutan NaOH</span>
                                </div>
                                <div class="flex items-start gap-3">
                                    <i class="fa-solid fa-check-circle text-secondary mt-1"></i>
                                    <span>Penyusunan logbook berbasis ISO/IEC 17025</span>
                                </div>
                                <div class="flex items-start gap-3">
                                    <i class="fa-solid fa-check-circle text-secondary mt-1"></i>
                                    <span>Dokumentasi dan ketertelusuran data (Traceability)</span>
                                </div>
                                <div class="flex items-start gap-3">
                                    <i class="fa-solid fa-check-circle text-secondary mt-1"></i>
                                    <span>Analisis dan interpretasi hasil pengujian</span>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="lg:w-1/3 flex flex-col justify-center gap-4">
                        <div class="bg-slate-900 rounded-xl p-6 border border-slate-700 text-center">
                            <i class="fa-solid fa-recycle text-4xl text-emerald-400 mb-3"></i>
                            <h4 class="font-bold text-lg mb-2">Waste Valorization</h4>
                            <p class="text-sm text-slate-400">Pemanfaatan limbah menjadi produk bernilai tinggi.</p>
                        </div>
                        <div class="bg-slate-900 rounded-xl p-6 border border-slate-700 text-center">
                            <i class="fa-solid fa-road text-4xl text-amber-400 mb-3"></i>
                            <h4 class="font-bold text-lg mb-2">Material Engineering</h4>
                            <p class="text-sm text-slate-400">Pengembangan campuran aspal SMA yang lebih kuat dan awet.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="projects" class="section-padding bg-surface">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-dark mb-4">Pengalaman Akademik & Laboratorium</h2>
                <p class="text-lg text-slate-600">Selama menempuh pendidikan di Teknik Kimia, saya telah terlibat aktif dalam berbagai kegiatan analisis dan praktikum.</p>
                <div class="w-20 h-1 bg-primary mx-auto rounded-full mt-4"></div>
            </div>

            <!-- Grid Layout for Lab Experience -->
            <div class="grid grid-cols-1 md:grid-cols-2 xl:grid-cols-3 gap-6">
                
                <!-- Card 1 -->
                <div class="bg-white rounded-xl shadow-sm border border-slate-100 p-6 card-hover">
                    <div class="flex items-center gap-4 mb-4">
                        <div class="w-10 h-10 rounded-full bg-blue-100 text-blue-600 flex items-center justify-center">
                            <i class="fa-solid fa-stopwatch"></i>
                        </div>
                        <h3 class="font-bold text-xl text-dark">Kinetika Reaksi</h3>
                    </div>
                    <ul class="space-y-2 text-slate-600 text-sm">
                        <li><i class="fa-solid fa-angle-right text-primary mr-2"></i>Analisis pengaruh katalis terhadap laju reaksi</li>
                        <li><i class="fa-solid fa-angle-right text-primary mr-2"></i>Penentuan konstanta laju reaksi</li>
                        <li><i class="fa-solid fa-angle-right text-primary mr-2"></i>Hubungan energi aktivasi dan kinetika</li>
                    </ul>
                </div>

                <!-- Card 2 -->
                <div class="bg-white rounded-xl shadow-sm border border-slate-100 p-6 card-hover">
                    <div class="flex items-center gap-4 mb-4">
                        <div class="w-10 h-10 rounded-full bg-teal-100 text-teal-600 flex items-center justify-center">
                            <i class="fa-solid fa-layer-group"></i>
                        </div>
                        <h3 class="font-bold text-xl text-dark">Adsorpsi</h3>
                    </div>
                    <ul class="space-y-2 text-slate-600 text-sm">
                        <li><i class="fa-solid fa-angle-right text-primary mr-2"></i>Analisis isoterm Langmuir</li>
                        <li><i class="fa-solid fa-angle-right text-primary mr-2"></i>Analisis isoterm Freundlich</li>
                        <li><i class="fa-solid fa-angle-right text-primary mr-2"></i>Pengolahan data adsorpsi via regresi linear</li>
                    </ul>
                </div>

                <!-- Card 3 -->
                <div class="bg-white rounded-xl shadow-sm border border-slate-100 p-6 card-hover">
                    <div class="flex items-center gap-4 mb-4">
                        <div class="w-10 h-10 rounded-full bg-indigo-100 text-indigo-600 flex items-center justify-center">
                            <i class="fa-solid fa-water"></i>
                        </div>
                        <h3 class="font-bold text-xl text-dark">Sifat Fisik Fluida</h3>
                    </div>
                    <ul class="space-y-2 text-slate-600 text-sm">
                        <li><i class="fa-solid fa-angle-right text-primary mr-2"></i>Pengukuran viskositas dinamis & kinematis</li>
                        <li><i class="fa-solid fa-angle-right text-primary mr-2"></i>Evaluasi hubungan suhu terhadap viskositas</li>
                        <li><i class="fa-solid fa-angle-right text-primary mr-2"></i>Tegangan permukaan</li>
                    </ul>
                </div>

                <!-- Card 4 -->
                <div class="bg-white rounded-xl shadow-sm border border-slate-100 p-6 card-hover">
                    <div class="flex items-center gap-4 mb-4">
                        <div class="w-10 h-10 rounded-full bg-purple-100 text-purple-600 flex items-center justify-center">
                            <i class="fa-solid fa-vial-virus"></i>
                        </div>
                        <h3 class="font-bold text-xl text-dark">Kimia Organik</h3>
                    </div>
                    <ul class="space-y-2 text-slate-600 text-sm">
                        <li><i class="fa-solid fa-angle-right text-primary mr-2"></i>Ekstraksi cair-cair & Isolasi polifenol</li>
                        <li><i class="fa-solid fa-angle-right text-primary mr-2"></i>Analisis kadar protein</li>
                        <li><i class="fa-solid fa-angle-right text-primary mr-2"></i>Hidrolisis metil & Sintesis asam salisilat</li>
                        <li><i class="fa-solid fa-angle-right text-primary mr-2"></i>Pembuatan resin urea</li>
                    </ul>
                </div>

                <!-- Card 5 -->
                <div class="bg-white rounded-xl shadow-sm border border-slate-100 p-6 card-hover">
                    <div class="flex items-center gap-4 mb-4">
                        <div class="w-10 h-10 rounded-full bg-orange-100 text-orange-600 flex items-center justify-center">
                            <i class="fa-solid fa-temperature-half"></i>
                        </div>
                        <h3 class="font-bold text-xl text-dark">Kimia Fisika</h3>
                    </div>
                    <ul class="space-y-2 text-slate-600 text-sm">
                        <li><i class="fa-solid fa-angle-right text-primary mr-2"></i>Hukum Hess & Diagram Terner</li>
                        <li><i class="fa-solid fa-angle-right text-primary mr-2"></i>Destilasi sederhana</li>
                        <li><i class="fa-solid fa-angle-right text-primary mr-2"></i>Kinetika reaksi H2O2 dengan KI</li>
                    </ul>
                </div>

                <!-- Card 6 -->
                <div class="bg-white rounded-xl shadow-sm border border-slate-100 p-6 card-hover">
                    <div class="flex items-center gap-4 mb-4">
                        <div class="w-10 h-10 rounded-full bg-green-100 text-green-600 flex items-center justify-center">
                            <i class="fa-solid fa-chart-line"></i>
                        </div>
                        <h3 class="font-bold text-xl text-dark">Analisis & Pengolahan Data</h3>
                    </div>
                    <ul class="space-y-2 text-slate-600 text-sm">
                        <li><i class="fa-solid fa-angle-right text-primary mr-2"></i>Perhitungan regresi linear & Evaluasi galat</li>
                        <li><i class="fa-solid fa-angle-right text-primary mr-2"></i>Interpretasi grafik eksperimen</li>
                        <li><i class="fa-solid fa-angle-right text-primary mr-2"></i>Pengolahan kompleks via Microsoft Excel</li>
                        <li><i class="fa-solid fa-angle-right text-primary mr-2"></i>Pembuatan larutan standar & pengenceran</li>
                    </ul>
                </div>

            </div>
        </div>
    </section>

    <section id="competencies" class="section-padding bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col lg:flex-row gap-16">
                
                <!-- Left: Competencies -->
                <div class="lg:w-1/2">
                    <h2 class="text-3xl font-bold text-dark mb-2">Matriks Kompetensi</h2>
                    <div class="w-16 h-1 bg-primary mb-8 rounded-full"></div>
                    
                    <div class="space-y-8">
                        <!-- Competency Block -->
                        <div>
                            <h4 class="text-lg font-bold text-slate-800 flex items-center gap-2 mb-3">
                                <i class="fa-solid fa-flask-vial text-primary"></i> Laboratorium & Mutu
                            </h4>
                            <div class="flex flex-wrap gap-2">
                                <span class="px-3 py-1 bg-slate-100 text-slate-700 text-sm rounded-full">GLP</span>
                                <span class="px-3 py-1 bg-slate-100 text-slate-700 text-sm rounded-full">ISO/IEC 17025</span>
                                <span class="px-3 py-1 bg-slate-100 text-slate-700 text-sm rounded-full">Validasi Metode</span>
                                <span class="px-3 py-1 bg-slate-100 text-slate-700 text-sm rounded-full">Preparasi Sampel</span>
                            </div>
                        </div>
                        
                        <div>
                            <h4 class="text-lg font-bold text-slate-800 flex items-center gap-2 mb-3">
                                <i class="fa-solid fa-magnifying-glass-chart text-secondary"></i> Penelitian & Sains
                            </h4>
                            <div class="flex flex-wrap gap-2">
                                <span class="px-3 py-1 bg-slate-100 text-slate-700 text-sm rounded-full">Desain Eksperimental</span>
                                <span class="px-3 py-1 bg-slate-100 text-slate-700 text-sm rounded-full">Kajian Literatur</span>
                                <span class="px-3 py-1 bg-slate-100 text-slate-700 text-sm rounded-full">Penulisan Ilmiah</span>
                                <span class="px-3 py-1 bg-slate-100 text-slate-700 text-sm rounded-full">Logbook Penilitian</span>
                            </div>
                        </div>

                        <div>
                            <h4 class="text-lg font-bold text-slate-800 flex items-center gap-2 mb-3">
                                <i class="fa-solid fa-chart-pie text-sky-500"></i> Analisis Data
                            </h4>
                            <div class="flex flex-wrap gap-2">
                                <span class="px-3 py-1 bg-slate-100 text-slate-700 text-sm rounded-full">Microsoft Excel</span>
                                <span class="px-3 py-1 bg-slate-100 text-slate-700 text-sm rounded-full">Regresi Linear</span>
                                <span class="px-3 py-1 bg-slate-100 text-slate-700 text-sm rounded-full">Statistik Dasar</span>
                                <span class="px-3 py-1 bg-slate-100 text-slate-700 text-sm rounded-full">Interpretasi Hasil</span>
                            </div>
                        </div>

                        <div>
                            <h4 class="text-lg font-bold text-slate-800 flex items-center gap-2 mb-3">
                                <i class="fa-solid fa-industry text-indigo-500"></i> Teknik Kimia
                            </h4>
                            <div class="flex flex-wrap gap-2">
                                <span class="px-3 py-1 bg-slate-100 text-slate-700 text-sm rounded-full">Neraca Massa & Energi</span>
                                <span class="px-3 py-1 bg-slate-100 text-slate-700 text-sm rounded-full">Teknologi Material</span>
                                <span class="px-3 py-1 bg-slate-100 text-slate-700 text-sm rounded-full">Pengolahan Limbah</span>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Right: Achievements & Vision -->
                <div class="lg:w-1/2">
                    <h2 class="text-3xl font-bold text-dark mb-2">Prestasi Akademik</h2>
                    <div class="w-16 h-1 bg-primary mb-8 rounded-full"></div>

                    <div class="relative border-l-2 border-slate-200 ml-3 space-y-8 pb-8">
                        <div class="relative pl-6">
                            <div class="absolute -left-[9px] top-1 w-4 h-4 rounded-full bg-primary border-4 border-white"></div>
                            <h4 class="font-bold text-lg text-dark">Finalis</h4>
                            <p class="text-slate-600 text-sm mt-1">Olimpiade Nasional Tingkat Provinsi Bidang Geografi</p>
                        </div>
                        <div class="relative pl-6">
                            <div class="absolute -left-[9px] top-1 w-4 h-4 rounded-full bg-primary border-4 border-white"></div>
                            <h4 class="font-bold text-lg text-dark">Juara 2</h4>
                            <p class="text-slate-600 text-sm mt-1">Kompetisi Kuis Sains Regional</p>
                        </div>
                        <div class="relative pl-6">
                            <div class="absolute -left-[9px] top-1 w-4 h-4 rounded-full bg-primary border-4 border-white"></div>
                            <h4 class="font-bold text-lg text-dark">Top 200 Nasional</h4>
                            <p class="text-slate-600 text-sm mt-1">Kompetisi Sains Ruangguru</p>
                        </div>
                    </div>

                    <div class="mt-8 bg-sky-50 border border-sky-100 p-6 rounded-xl relative">
                        <i class="fa-solid fa-quote-left absolute top-4 left-4 text-3xl text-sky-200 opacity-50"></i>
                        <h3 class="text-xl font-bold text-sky-900 mb-2 relative z-10">Visi Jangka Panjang</h3>
                        <p class="text-slate-700 text-sm italic relative z-10 leading-relaxed">
                            "Menjadi peneliti dan akademisi di bidang teknik kimia yang berkontribusi pada pengembangan material inovatif, teknologi lingkungan, dan pemanfaatan limbah berbasis prinsip keberlanjutan melalui riset yang berdampak bagi industri, masyarakat, dan perkembangan ilmu pengetahuan."
                        </p>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <section id="contact" class="bg-dark pt-20 pb-10 text-center text-white border-t-4 border-primary">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl md:text-4xl font-bold mb-6">Mari Berkolaborasi!</h2>
            <p class="text-slate-400 text-lg mb-10 max-w-2xl mx-auto">
                Tertarik berdiskusi mengenai penelitian teknik kimia, inovasi material berkelanjutan, atau peluang akademis? Silakan hubungi saya melalui platform di bawah ini.
            </p>
            
            <div class="flex flex-col sm:flex-row justify-center gap-6 mb-16">
                <!-- Mailto link fixed the 'ii' typo from prompt to ensure it works correctly -->
                <a href="mailto:pandudian022@gmail.com" class="flex items-center justify-center gap-3 bg-white/10 hover:bg-white/20 border border-white/20 px-8 py-4 rounded-xl transition-all duration-300">
                    <i class="fa-solid fa-envelope text-2xl text-sky-400"></i>
                    <span class="font-medium text-lg">pandudian022@gmail.com</span>
                </a>
                <a href="https://www.linkedin.com/in/pandu-dian-938645384" target="_blank" class="flex items-center justify-center gap-3 bg-blue-600 hover:bg-blue-700 px-8 py-4 rounded-xl transition-all duration-300">
                    <i class="fa-brands fa-linkedin text-2xl"></i>
                    <span class="font-medium text-lg">LinkedIn Profil</span>
                </a>
            </div>

            <div class="border-t border-slate-800 pt-8 flex flex-col md:flex-row justify-between items-center gap-4 text-sm text-slate-500">
                <p>&copy; 2024 Pandu Dian. All Rights Reserved.</p>
                <div class="flex gap-4">
                    <span>Chemical Engineering</span>
                    <span>•</span>
                    <span>Research</span>
                    <span>•</span>
                    <span>Process Engineering</span>
                </div>
            </div>
        </div>
    </section>

    <script>
        // Mobile menu toggle functionality
        const btn = document.getElementById('mobile-menu-btn');
        const menu = document.getElementById('mobile-menu');

        btn.addEventListener('click', () => {
            menu.classList.toggle('hidden');
        });

        // Close mobile menu when clicking a link
        const mobileLinks = menu.querySelectorAll('a');
        mobileLinks.forEach(link => {
            link.addEventListener('click', () => {
                menu.classList.add('hidden');
            });
        });

        // Add shadow to navbar on scroll
        window.addEventListener('scroll', () => {
            const nav = document.querySelector('nav');
            if (window.scrollY > 10) {
                nav.classList.add('shadow-md');
                nav.classList.remove('shadow-sm', 'bg-white/90');
                nav.classList.add('bg-white');
            } else {
                nav.classList.remove('shadow-md', 'bg-white');
                nav.classList.add('shadow-sm', 'bg-white/90');
            }
        });
    </script>
</body>
</html>
