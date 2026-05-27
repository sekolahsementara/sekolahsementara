<!DOCTYPE html>
<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sekolah Sementara — Belajar Hal yang Tidak Diajarkan di Sekolah</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script defer src="https://cdn.jsdelivr.net/npm/alpinejs@3.x.x/dist/cdn.min.js"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700&display=swap" rel="stylesheet">
    <script src="https://unpkg.com/lucide@latest"></script>
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Plus Jakarta Sans', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            cream: '#FDFBF7',     /* Cream / off-white */
                            card: '#FFFFFF',      /* Murni Putih */
                            dark: '#0F172A',      /* Navy Gelap */
                            muted: '#475569',     /* Slate Muted */
                            softGray: '#F1F5F9',  /* Soft Gray */
                            copper: '#D97706',    /* Warm Orange/Copper */
                            copperHover: '#B45309'
                        }
                    }
                }
            }
        }
    </script>
    <style>
        body {
            background-color: #FDFBF7;
            color: #0F172A;
        }
        .glass-nav {
            background: rgba(253, 251, 247, 0.8);
            backdrop-filter: blur(12px);
        }
    </style>
</head>
<body class="antialiased selection:bg-brand-softGray selection:text-brand-copper overflow-x-hidden">

    <nav class="fixed top-0 left-0 right-0 z-50 glass-nav border-b border-brand-dark/5 transition-all duration-300">
        <div class="max-w-6xl mx-auto px-6 h-20 flex items-center justify-between">
            <a href="#" class="flex items-center space-x-2">
                <span class="font-bold text-lg tracking-tight text-brand-dark">Sekolah Sementara.</span>
            </a>
            
            <div class="hidden md:flex items-center space-x-8 text-sm font-medium text-brand-muted">
                <a href="#about" class="hover:text-brand-dark transition-colors">Tentang Kami</a>
                <a href="#curriculum" class="hover:text-brand-dark transition-colors">Curriculum</a>
                <a href="#journey" class="hover:text-brand-dark transition-colors">Journey</a>
                <a href="#project" class="hover:text-brand-dark transition-colors">Mini Project</a>
            </div>

            <div>
                <a href="https://forms.gle/YQ83ppq3yELtR9v29" target="_blank" class="inline-flex items-center justify-center px-5 py-2.5 text-xs font-semibold tracking-wide text-brand-cream bg-brand-dark rounded-full hover:bg-brand-copper transition-all duration-300 shadow-sm">
                    Gabung Fellowship
                </a>
            </div>
        </div>
    </nav>

    <section class="relative pt-48 pb-24 min-h-[75vh] flex items-center">
        <div class="absolute top-1/4 left-1/10 w-96 h-96 bg-brand-copper/5 rounded-full filter blur-3xl opacity-70 -z-10 animate-pulse" style="animation-duration: 8s;"></div>
        <div class="absolute bottom-1/4 right-1/10 w-80 h-80 bg-brand-dark/5 rounded-full filter blur-3xl opacity-60 -z-10 animate-pulse" style="animation-duration: 12s;"></div>

        <div class="max-w-4xl mx-auto px-6 text-center" data-aos="fade-up" data-aos-duration="1000">
            <h1 class="text-4xl sm:text-5xl md:text-6xl font-bold text-brand-dark tracking-tight leading-[1.15] mb-8">
                Saatnya kamu menjadi bagian <br class="hidden sm:inline"> dari perjalanan ini
            </h1>
            
            <p class="text-base sm:text-lg md:text-xl text-brand-muted max-w-2xl mx-auto leading-relaxed mb-12 font-light">
                Ruang inkubasi yang menjembatani fase transisi kamu dengan mentorship eksklusif, desain kurikulum yang berorientasi masa depan, dan eksekusi proyek nyata yang berdampak langsung pada masyarakat.
            </p>
            
            <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
                <a href="https://forms.gle/YQ83ppq3yELtR9v29" target="_blank" class="w-full sm:w-auto inline-flex items-center justify-center px-8 py-4 font-semibold text-brand-cream bg-brand-dark rounded-full hover:bg-brand-copper shadow-md shadow-brand-dark/10 transition-all duration-300 group gap-2">
                    <i data-lucide="instagram" class="w-5 h-5 text-brand-dark group-hover:text-brand-cream transition-colors"></i>
                    Daftar Setara Fellowship
                    <i data-lucide="arrow-right" class="w-4 h-4 ml-1 group-hover:translate-x-1 transition-transform text-brand-copper group-hover:text-brand-cream"></i>
                </a>
                <a href="#about" class="w-full sm:w-auto inline-flex items-center justify-center px-8 py-4 font-semibold text-brand-dark bg-transparent border border-brand-dark/10 rounded-full hover:bg-brand-softGray transition-colors">
                    Pelajari Program
                </a>
            </div>
        </div>
    </section>

    <section id="about" class="py-24 border-t border-brand-dark/5 bg-white">
        <div class="max-w-6xl mx-auto px-6">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-start">
                
                <div class="lg:col-span-5 lg:sticky lg:top-32" data-aos="fade-up" data-aos-duration="800">
                    <span class="text-brand-copper font-semibold text-sm tracking-wider uppercase block mb-3">Tentang Kami</span>
                    <h2 class="text-3xl md:text-4xl font-bold text-brand-dark tracking-tight mb-6">Apa itu Sekolah Sementara?</h2>
                    <p class="text-brand-muted leading-relaxed text-base md:text-lg font-light">
                        Sekolah Sementara adalah organisasi non-profit yang membantu anak muda di masa transisi membangun self leadership, resilience, dan kesiapan masa depan melalui mentoring, experiential learning, dan project-based learning.
                    </p>
                </div>
                
                <div class="lg:col-span-7 grid grid-cols-1 sm:grid-cols-2 gap-4" data-aos="fade-up" data-aos-duration="1000">
                    
                    <div class="p-8 rounded-3xl bg-brand-cream border border-brand-dark/5 shadow-sm hover:shadow-md hover:-translate-y-1 transition-all duration-300">
                        <div class="w-10 h-10 rounded-xl bg-brand-copper/10 text-brand-copper flex items-center justify-center mb-6 shadow-sm">
                            <i data-lucide="compass" class="w-5 h-5"></i>
                        </div>
                        <h3 class="font-bold text-lg text-brand-dark mb-2">Self Leadership</h3>
                        <p class="text-sm text-brand-muted leading-relaxed font-light">Menavigasi arah hidup secara mandiri dan mengambil keputusan dengan penuh kesadaran.</p>
                    </div>

                    <div class="p-8 rounded-3xl bg-brand-cream border border-brand-dark/5 shadow-sm hover:shadow-md hover:-translate-y-1 transition-all duration-300">
                        <div class="w-10 h-10 rounded-xl bg-brand-copper/10 text-brand-copper flex items-center justify-center mb-6 shadow-sm">
                            <i data-lucide="smile" class="w-5 h-5"></i>
                        </div>
                        <h3 class="font-bold text-lg text-brand-dark mb-2">Mindset Development</h3>
                        <p class="text-sm text-brand-muted leading-relaxed font-light">Membentuk ketangguhan berpikir (resilience) dalam menghadapi ketidakpastian masa depan.</p>
                    </div>

                    <div class="p-8 rounded-3xl bg-brand-cream border border-brand-dark/5 shadow-sm hover:shadow-md hover:-translate-y-1 transition-all duration-300">
                        <div class="w-10 h-10 rounded-xl bg-brand-copper/10 text-brand-copper flex items-center justify-center mb-6 shadow-sm">
                            <i data-lucide="layers" class="w-5 h-5"></i>
                        </div>
                        <h3 class="font-bold text-lg text-brand-dark mb-2">Productivity System</h3>
                        <p class="text-sm text-brand-muted leading-relaxed font-light">Merancang kerangka kerja harian yang efektif tanpa terjebak toxic productivity.</p>
                    </div>

                    <div class="p-8 rounded-3xl bg-brand-cream border border-brand-dark/5 shadow-sm hover:shadow-md hover:-translate-y-1 transition-all duration-300">
                        <div class="w-10 h-10 rounded-xl bg-brand-copper/10 text-brand-copper flex items-center justify-center mb-6 shadow-sm">
                            <i data-lucide="user-check" class="w-5 h-5"></i>
                        </div>
                        <h3 class="font-bold text-lg text-brand-dark mb-2">Personal Branding</h3>
                        <p class="text-sm text-brand-muted leading-relaxed font-light">Mengartikulasikan nilai diri dan potensi secara otentik kepada dunia luar.</p>
                    </div>

                    <div class="p-8 rounded-3xl bg-brand-cream border border-brand-dark/5 shadow-sm hover:shadow-md hover:-translate-y-1 transition-all duration-300 sm:col-span-2">
                        <div class="w-10 h-10 rounded-xl bg-brand-copper/10 text-brand-copper flex items-center justify-center mb-6 shadow-sm">
                            <i data-lucide="trending-up" class="w-5 h-5"></i>
                        </div>
                        <h3 class="font-bold text-lg text-brand-dark mb-2">Future Readiness</h3>
                        <p class="text-sm text-brand-muted leading-relaxed font-light">Mempersiapkan bekal keterampilan interdisipliner yang relevan untuk kebutuhan industri, akademik, maupun sosial di masa mendatang.</p>
                    </div>

                </div>
            </div>
        </div>
    </section>

    <section id="curriculum" class="py-24 bg-brand-cream">
        <div class="max-w-6xl mx-auto px-6">
            <div class="text-center max-w-2xl mx-auto mb-16" data-aos="fade-up" data-aos-duration="800">
                <span class="text-brand-copper font-semibold text-sm tracking-wider uppercase block mb-3">Kurikulum Kami</span>
                <h2 class="text-3xl md:text-4xl font-bold text-brand-dark tracking-tight">Curriculum Framework</h2>
                <div class="w-12 h-1 bg-brand-copper/30 mx-auto mt-4 rounded-full"></div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-6" data-aos="fade-up" data-aos-duration="1000">
                <div class="bg-brand-card p-8 rounded-3xl border border-brand-dark/5 shadow-sm hover:shadow-md transition-all duration-300 group flex gap-6 items-start">
                    <div class="w-12 h-12 rounded-2xl bg-brand-copper/10 text-brand-copper flex-shrink-0 flex items-center justify-center group-hover:scale-110 transition-transform shadow-sm">
                        <i data-lucide="compass" class="w-6 h-6"></i>
                    </div>
                    <div>
                        <h3 class="font-bold text-xl text-brand-dark mb-2 group-hover:text-brand-copper transition-colors">Embracing the Gap & Mindset Reset</h3>
                        <p class="text-brand-muted text-sm leading-relaxed font-light">Mengubah cara pandang terhadap gap year, berdamai dengan ketidakpastian, dan menyusun ulang peta kompas internal diri.</p>
                    </div>
                </div>

                <div class="bg-brand-card p-8 rounded-3xl border border-brand-dark/5 shadow-sm hover:shadow-md transition-all duration-300 group flex gap-6 items-start">
                    <div class="w-12 h-12 rounded-2xl bg-brand-copper/10 text-brand-copper flex-shrink-0 flex items-center justify-center group-hover:scale-110 transition-transform shadow-sm">
                        <i data-lucide="user-check" class="w-6 h-6"></i>
                    </div>
                    <div>
                        <h3 class="font-bold text-xl text-brand-dark mb-2 group-hover:text-brand-copper transition-colors">Self-Leadership</h3>
                        <p class="text-brand-muted text-sm leading-relaxed font-light">Menguasai regulasi emosi, kedisiplinan otonom, dan seni memimpin diri sendiri sebelum menggerakkan orang lain.</p>
                    </div>
                </div>

                <div class="bg-brand-card p-8 rounded-3xl border border-brand-dark/5 shadow-sm hover:shadow-md transition-all duration-300 group flex gap-6 items-start">
                    <div class="w-12 h-12 rounded-2xl bg-brand-copper/10 text-brand-copper flex-shrink-0 flex items-center justify-center group-hover:scale-110 transition-transform shadow-sm">
                        <i data-lucide="map" class="w-6 h-6"></i>
                    </div>
                    <div>
                        <h3 class="font-bold text-xl text-brand-dark mb-2 group-hover:text-brand-copper transition-colors">Productivity & Strategic Life Mapping</h3>
                        <p class="text-brand-muted text-sm leading-relaxed font-light">Membangun kerangka sistem kerja personal yang taktis, manajemen waktu, serta visualisasi rencana hidup jangka menengah.</p>
                    </div>
                </div>

                <div class="bg-brand-card p-8 rounded-3xl border border-brand-dark/5 shadow-sm hover:shadow-md transition-all duration-300 group flex gap-6 items-start">
                    <div class="w-12 h-12 rounded-2xl bg-brand-copper/10 text-brand-copper flex-shrink-0 flex items-center justify-center group-hover:scale-110 transition-transform shadow-sm">
                        <i data-lucide="message-square-code" class="w-6 h-6"></i>
                    </div>
                    <div>
                        <h3 class="font-bold text-xl text-brand-dark mb-2 group-hover:text-brand-copper transition-colors">Strategic Narrative Engineering</h3>
                        <p class="text-brand-muted text-sm leading-relaxed font-light">Keterampilan mengemas cerita, menyusun argumen terstruktur, presentasi ide, dan melatih komunikasi publik secara berdampak.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="journey" class="py-24 bg-white overflow-hidden">
        <div class="max-w-5xl mx-auto px-6">
            <div class="text-center max-w-2xl mx-auto mb-20" data-aos="fade-up" data-aos-duration="800">
                <span class="text-brand-copper font-semibold text-sm tracking-wider uppercase block mb-3">Perjalanan Program</span>
                <h2 class="text-3xl md:text-4xl font-bold text-brand-dark tracking-tight">Program Journey</h2>
                <div class="w-12 h-1 bg-brand-copper/30 mx-auto mt-4 rounded-full"></div>
            </div>

            <div class="relative max-w-3xl mx-auto" data-aos="fade-up" data-aos-duration="1000">
                <div class="absolute left-4 md:left-1/2 top-0 bottom-0 w-[2px] bg-brand-softGray -translate-x-1/2"></div>

                <div class="relative z-10 mb-16 md:mb-20 flex flex-col md:flex-row items-start md:justify-between">
                    <div class="absolute left-4 md:left-1/2 w-4 h-4 rounded-full bg-brand-copper border-4 border-white -translate-x-1/2 top-1.5 shadow-sm"></div>
                    
                    <div class="w-full md:w-[45%] pl-10 md:pl-0 md:text-right">
                        <span class="inline-block px-3 py-1 rounded-full bg-brand-cream border border-brand-dark/5 text-xs font-semibold text-brand-copper mb-3">Bulan Pertama</span>
                        <h3 class="font-bold text-xl text-brand-dark mb-3">Foundation & Self Leadership</h3>
                        <p class="text-sm text-brand-muted leading-relaxed font-light text-left md:text-right">
                            Kami akan mengajak kamu mengenal diri sendiri lebih dalam, membangun kembali kepercayaan diri, dan belajar mengelola diri dengan lebih baik selama menjalani gap year.
                        </p>
                    </div>
                    <div class="hidden md:block w-[45%]"></div>
                </div>

                <div class="relative z-10 mb-16 md:mb-20 flex flex-col md:flex-row items-start md:justify-between">
                    <div class="absolute left-4 md:left-1/2 w-4 h-4 rounded-full bg-brand-dark border-4 border-white -translate-x-1/2 top-1.5 shadow-sm"></div>
                    
                    <div class="hidden md:block w-[45%]"></div>
                    <div class="w-full md:w-[45%] pl-10 md:pl-0">
                        <span class="inline-block px-3 py-1 rounded-full bg-brand-cream border border-brand-dark/5 text-xs font-semibold text-brand-copper mb-3">Bulan Kedua</span>
                        <h3 class="font-bold text-xl text-brand-dark mb-3">Future Readiness & Personal Branding</h3>
                        <p class="text-sm text-brand-muted leading-relaxed font-light text-left">
                            Kamu akan belajar menyusun arah masa depan, membangun sistem produktivitas, mengembangkan portfolio, dan personal branding secara lebih profesional.
                        </p>
                    </div>
                </div>

                <div class="relative z-10 flex flex-col md:flex-row items-start md:justify-between">
                    <div class="absolute left-4 md:left-1/2 w-4 h-4 rounded-full bg-brand-copper border-4 border-white -translate-x-1/2 top-1.5 shadow-sm"></div>
                    
                    <div class="w-full md:w-[45%] pl-10 md:pl-0 md:text-right">
                        <span class="inline-block px-3 py-1 rounded-full bg-brand-cream border border-brand-dark/5 text-xs font-semibold text-brand-copper mb-3">Bulan Ketiga</span>
                        <h3 class="font-bold text-xl text-brand-dark mb-3">Capstone Mini Project</h3>
                        <p class="text-sm text-brand-muted leading-relaxed font-light text-left md:text-right">
                            Di fase terakhir, kamu akan mengembangkan mini project berdasarkan minat atau isu yang kamu pedulikan sebagai bentuk implementasi dari seluruh proses pembelajaran selama program berlangsung.
                        </p>
                    </div>
                    <div class="hidden md:block w-[45%]"></div>
                </div>
            </div>
        </div>
    </section>

    <section id="project" class="py-24 bg-brand-cream">
        <div class="max-w-6xl mx-auto px-6">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center mb-16" data-aos="fade-up" data-aos-duration="800">
                <div class="lg:col-span-6">
                    <span class="text-brand-copper font-semibold text-sm tracking-wider uppercase block mb-3">Implementasi Nyata</span>
                    <h2 class="text-3xl md:text-4xl font-bold text-brand-dark tracking-tight mb-4">Build Something Real.</h2>
                    <p class="text-brand-muted leading-relaxed font-light">Peserta akan mengembangkan mini project berdasarkan minat dan isu yang mereka pedulikan sebagai bentuk implementasi pembelajaran selama program berlangsung.</p>
                </div>
                <div class="lg:col-span-6 grid grid-cols-2 gap-4 text-xs font-medium text-brand-dark">
                    <div class="flex items-center gap-2 px-4 py-3 bg-white rounded-xl border border-brand-dark/5"><i data-lucide="folder-git" class="w-4 h-4 text-brand-copper"></i> Portfolio Development</div>
                    <div class="flex items-center gap-2 px-4 py-3 bg-white rounded-xl border border-brand-dark/5"><i data-lucide="shield-check" class="w-4 h-4 text-brand-copper"></i> Self Leadership Practice</div>
                    <div class="flex items-center gap-2 px-4 py-3 bg-white rounded-xl border border-brand-dark/5"><i data-lucide="sparkles" class="w-4 h-4 text-brand-copper"></i> Bukti Perkembangan Diri</div>
                    <div class="flex items-center gap-2 px-4 py-3 bg-white rounded-xl border border-brand-dark/5"><i data-lucide="briefcase" class="w-4 h-4 text-brand-copper"></i> Persiapan Karir & Akademik</div>
                </div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6" data-aos="fade-up" data-aos-duration="1000">
                
                <div class="bg-brand-card p-6 rounded-2xl border border-brand-dark/5 shadow-sm hover:shadow-md transition-all group">
                    <div class="w-8 h-8 rounded-lg bg-brand-dark text-brand-cream flex items-center justify-center mb-4 group-hover:bg-brand-copper transition-colors"><i data-lucide="megaphone" class="w-4 h-4"></i></div>
                    <h4 class="font-bold text-base text-brand-dark mb-1">Educational Campaign</h4>
                    <p class="text-xs text-brand-muted leading-relaxed font-light">Gerakan penyadaran isu sosial atau literasi tertentu secara digital maupun terestrial.</p>
                </div>

                <div class="bg-brand-card p-6 rounded-2xl border border-brand-dark/5 shadow-sm hover:shadow-md transition-all group">
                    <div class="w-8 h-8 rounded-lg bg-brand-dark text-brand-cream flex items-center justify-center mb-4 group-hover:bg-brand-copper transition-colors"><i data-lucide="heart" class="w-4 h-4"></i></div>
                    <h4 class="font-bold text-base text-brand-dark mb-1">Social Initiative</h4>
                    <p class="text-xs text-brand-muted leading-relaxed font-light">Inisiasi program berbasis kerelawanan untuk memecahkan masalah lokal spesifik.</p>
                </div>

                <div class="bg-brand-card p-6 rounded-2xl border border-brand-dark/5 shadow-sm hover:shadow-md transition-all group">
                    <div class="w-8 h-8 rounded-lg bg-brand-dark text-brand-cream flex items-center justify-center mb-4 group-hover:bg-brand-copper transition-colors"><i data-lucide="users" class="w-4 h-4"></i></div>
                    <h4 class="font-bold text-base text-brand-dark mb-1">Community Project</h4>
                    <p class="text-xs text-brand-muted leading-relaxed font-light">Kolaborasi langsung dengan komunitas adat, marginal, atau kelompok pemuda di wilayah khusus.</p>
                </div>

            </div>
        </div>
    </section>

    <section class="py-24 bg-white">
        <div class="max-w-4xl mx-auto px-6">
            <div class="text-center max-w-2xl mx-auto mb-16" data-aos="fade-up" data-aos-duration="800">
                <span class="text-brand-copper font-semibold text-sm tracking-wider uppercase block mb-3">Output Peserta</span>
                <h2 class="text-3xl md:text-4xl font-bold text-brand-dark tracking-tight">Setelah Program, Peserta Akan Memiliki:</h2>
                <div class="w-12 h-1 bg-brand-copper/30 mx-auto mt-4 rounded-full"></div>
            </div>

            <div class="bg-brand-cream border border-brand-dark/5 rounded-3xl p-8 md:p-12 shadow-sm grid grid-cols-1 sm:grid-cols-2 gap-6" data-aos="fade-up" data-aos-duration="1000">
                
                <div class="flex items-start space-x-4">
                    <div class="w-6 h-6 rounded-full bg-brand-dark flex items-center justify-center text-brand-cream flex-shrink-0 mt-0.5 shadow-sm">
                        <i data-lucide="check" class="w-3.5 h-3.5"></i>
                    </div>
                    <div>
                        <h4 class="font-bold text-base text-brand-dark mb-1">Personal Portfolio</h4>
                        <p class="text-xs text-brand-muted leading-relaxed font-light">Dokumentasi hasil karya otentik sebagai modal rekam jejak mendaftar beasiswa atau kerja.</p>
                    </div>
                </div>

                <div class="flex items-start space-x-4">
                    <div class="w-6 h-6 rounded-full bg-brand-dark flex items-center justify-center text-brand-cream flex-shrink-0 mt-0.5 shadow-sm">
                        <i data-lucide="check" class="w-3.5 h-3.5"></i>
                    </div>
                    <div>
                        <h4 class="font-bold text-base text-brand-dark mb-1">Mini Project Experience</h4>
                        <p class="text-xs text-brand-muted leading-relaxed font-light">Pengalaman praktis mengelola proyek sosial dari nol hingga eksekusi lapangan.</p>
                    </div>
                </div>

                <div class="flex items-start space-x-4">
                    <div class="w-6 h-6 rounded-full bg-brand-dark flex items-center justify-center text-brand-cream flex-shrink-0 mt-0.5 shadow-sm">
                        <i data-lucide="check" class="w-3.5 h-3.5"></i>
                    </div>
                    <div>
                        <h4 class="font-bold text-base text-brand-dark mb-1">Personal Roadmap</h4>
                        <p class="text-xs text-brand-muted leading-relaxed font-light">Rencana strategis tertulis mengenai arah hidup akademis maupun karir pasca-transisi.</p>
                    </div>
                </div>

                <div class="flex items-start space-x-4">
                    <div class="w-6 h-6 rounded-full bg-brand-dark flex items-center justify-center text-brand-cream flex-shrink-0 mt-0.5 shadow-sm">
                        <i data-lucide="check" class="w-3.5 h-3.5"></i>
                    </div>
                    <div>
                        <h4 class="font-bold text-base text-brand-dark mb-1">Self Leadership Skills</h4>
                        <p class="text-xs text-brand-muted leading-relaxed font-light">Peningkatan kapasitas internal dalam manajemen emosi, resiliensi, dan disiplin diri.</p>
                    </div>
                </div>

                <div class="flex items-start space-x-4 sm:col-span-2 pt-4 border-t border-brand-dark/5">
                    <div class="w-6 h-6 rounded-full bg-brand-dark flex items-center justify-center text-brand-cream flex-shrink-0 mt-0.5 shadow-sm">
                        <i data-lucide="check" class="w-3.5 h-3.5"></i>
                    </div>
                    <div>
                        <h4 class="font-bold text-base text-brand-dark mb-1">Mentor & Community Network</h4>
                        <p class="text-xs text-brand-muted leading-relaxed font-light">Akses seumur hidup ke ekosistem alumni, praktisi profesional, serta jejaring pemuda berdampak di tingkat nasional.</p>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <section class="py-24 bg-white relative overflow-hidden">
        <div class="max-w-4xl mx-auto px-6">
            <div class="bg-brand-dark text-brand-cream rounded-[2.5rem] p-8 md:p-16 text-center relative overflow-hidden shadow-xl" data-aos="zoom-in" data-aos-duration="1000">
                <div class="absolute -top-12 -right-12 w-40 h-40 bg-brand-copper/20 rounded-full filter blur-2xl"></div>
                <div class="absolute -bottom-12 -left-12 w-40 h-40 bg-brand-softGray/10 rounded-full filter blur-2xl"></div>

                <span class="inline-block text-brand-copper bg-brand-cream px-4 py-1.5 rounded-full text-xs font-semibold uppercase tracking-wider mb-6">Program Utama</span>
                
                <h2 class="text-3xl md:text-5xl font-bold tracking-tight mb-4 max-w-2xl mx-auto leading-tight">
                    Siap Bertumbuh Bersama Sekolah Sementara?
                </h2>
                
                <p class="text-sm md:text-base text-gray-300 max-w-xl mx-auto leading-relaxed mb-10 font-light">
                    Setara Fellowship adalah program mentoring dan pengembangan diri intensif bagi anak muda di masa transisi. Persiapkan dirimu untuk melangkah lebih jauh.
                </p>
                
                <div>
                    <a href="https://forms.gle/YQ83ppq3yELtR9v29" target="_blank" class="inline-flex items-center justify-center px-8 py-4 font-semibold text-brand-dark bg-brand-cream rounded-full hover:bg-brand-copper hover:text-brand-cream transition-all duration-300 group shadow-lg gap-2">
                        <i data-lucide="instagram" class="w-5 h-5 text-brand-dark group-hover:text-brand-cream transition-colors"></i>
                        Daftar Setara Fellowship
                        <i data-lucide="arrow-right" class="w-4 h-4 ml-1 group-hover:translate-x-1 transition-transform text-brand-copper group-hover:text-brand-cream"></i>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <footer class="bg-brand-cream border-t border-brand-dark/5 py-16">
        <div class="max-w-4xl mx-auto px-6 flex flex-col items-center text-center">
            
            <div class="mb-6">
                <a href="#" class="font-bold text-xl tracking-tight text-brand-dark block">
                    Sekolah Sementara.
                </a>
            </div>

            <div class="flex flex-col items-center gap-2">
                <span class="text-xs font-semibold text-brand-dark uppercase tracking-widest block opacity-40">Hubungi kami</span>
                <div class="flex items-center gap-4 text-sm font-medium">
                    <a href="https://instagram.com/sekolahsementara" target="_blank" class="text-brand-muted hover:text-brand-copper transition-colors duration-300">
                        Instagram
                    </a>
                    <span class="text-brand-dark/20">&#8226;</span>
                    <a href="mailto:infosekolahsementara@gmail.com" class="text-brand-muted hover:text-brand-copper transition-colors duration-300">
                        E-mail
                    </a>
                </div>
            </div>

        </div>
        <div class="max-w-6xl mx-auto px-6 mt-12 pt-6 border-t border-brand-dark/5 text-center">
            <p class="text-[10px] text-gray-400">&copy; 2026 Sekolah Sementara. All rights reserved.</p>
        </div>
    </footer>

    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script>
        // Initialize Animate On Scroll
        AOS.init({
            once: true, 
            offset: 120,
        });
        
        // Initialize Lucide Icons
        lucide.createIcons();
    </script>
</body>
</html>
