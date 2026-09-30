<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PT Bangun Manunggal Trisno - Contractor & Supplier</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            blue: '#0F387A',
                            dark: '#082046',
                            light: '#1D5BBF',
                            accent: '#F3F7FC'
                        }
                    },
                    fontFamily: {
                        sans: ['Plus Jakarta Sans', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <style>
        html { scroll-behavior: smooth; }
        .hero-bg {
            background: linear-gradient(rgba(8, 32, 70, 0.82), rgba(15, 56, 122, 0.88)), url('https://images.unsplash.com/photo-1541888946425-d0fbb186a5b7?auto=format&fit=crop&q=80&w=1920');
            background-size: cover;
            background-position: center;
        }
    </style>
</head>
<body class="font-sans text-slate-800 bg-slate-50 antialiased selection:bg-brand-blue selection:text-white">

    <!-- NAVBAR -->
    <nav class="sticky top-0 z-50 bg-white/95 backdrop-blur-md border-b border-slate-100 shadow-sm">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-20">
                <!-- Logo & Brand Name -->
                <a href="#" class="flex items-center gap-3">
                    <div class="w-11 h-11 bg-white rounded-lg p-1 border border-slate-200 shadow-sm flex items-center justify-center shrink-0">
                        <svg viewBox="0 0 100 100" class="w-full h-full">
                            <path d="M 22,12 L 64,12 C 78,12 88,20 88,34 C 88,44 82,50 72,53 C 84,57 90,66 90,78 C 90,92 78,100 62,100 L 22,100 Z M 52,56 L 22,86 L 22,56 Z M 44,32 L 64,32 C 68,32 72,30 72,26 C 72,22 68,20 64,20 L 44,20 Z M 44,78 L 66,78 C 71,78 75,75 75,70 C 75,65 71,62 66,62 L 44,62 Z" fill="#0F387A"/>
                        </svg>
                    </div>
                    <div>
                        <span class="text-base sm:text-lg font-extrabold tracking-tight text-brand-dark block leading-none">PT BANGUN MANUNGGAL TRISNO</span>
                        <span class="text-[10px] sm:text-xs font-semibold text-slate-500 tracking-wider uppercase block mt-1">Contractor & Supplier</span>
                    </div>
                </a>

                <!-- Desktop Navigation Links -->
                <div class="hidden md:flex items-center gap-8 font-medium text-sm text-slate-600">
                    <a href="#tentang" class="hover:text-brand-blue transition">Tentang Kami</a>
                    <a href="#layanan" class="hover:text-brand-blue transition">Layanan</a>
                    <a href="#keunggulan" class="hover:text-brand-blue transition">Keunggulan</a>
                    <a href="#portofolio" class="hover:text-brand-blue transition">Portofolio</a>
                    <a href="#kontak" class="hover:text-brand-blue transition">Kontak</a>
                </div>

                <!-- CTA Button -->
                <div class="hidden md:flex items-center">
                    <a href="https://wa.me/6281284186229?text=Halo%20PT%20Bangun%20Manunggal%20Trisno,%20saya%20ingin%20konsultasi%20proyek" target="_blank" class="bg-brand-blue hover:bg-brand-dark text-white px-5 py-2.5 rounded-lg font-semibold text-sm transition shadow-md shadow-brand-blue/20 flex items-center gap-2">
                        <i class="fa-brands fa-whatsapp text-lg"></i>
                        <span>Hubungi Kami</span>
                    </a>
                </div>

                <!-- Mobile Menu Button -->
                <button id="menu-btn" class="md:hidden text-slate-700 hover:text-brand-blue focus:outline-none p-2">
                    <i class="fa-solid fa-bars text-2xl"></i>
                </button>
            </div>
        </div>

        <!-- Mobile Menu Dropdown -->
        <div id="mobile-menu" class="hidden md:hidden bg-white border-b border-slate-200 px-4 pt-2 pb-6 space-y-3 font-medium text-slate-700">
            <a href="#tentang" class="block py-2 hover:text-brand-blue border-b border-slate-100">Tentang Kami</a>
            <a href="#layanan" class="block py-2 hover:text-brand-blue border-b border-slate-100">Layanan</a>
            <a href="#keunggulan" class="block py-2 hover:text-brand-blue border-b border-slate-100">Keunggulan</a>
            <a href="#portofolio" class="block py-2 hover:text-brand-blue border-b border-slate-100">Portofolio</a>
            <a href="#kontak" class="block py-2 hover:text-brand-blue">Kontak</a>
            <a href="https://wa.me/6281284186229?text=Halo%20PT%20Bangun%20Manunggal%20Trisno,%20saya%20ingin%20konsultasi%20proyek" target="_blank" class="w-full bg-brand-blue text-white py-3 rounded-lg font-semibold text-center flex items-center justify-center gap-2 mt-4">
                <i class="fa-brands fa-whatsapp text-lg"></i> Konsultasi via WhatsApp
            </a>
        </div>
    </nav>

    <!-- 1. HERO SECTION -->
    <section class="hero-bg min-h-[85vh] flex items-center relative text-white py-20 px-4">
        <div class="max-w-7xl mx-auto w-full">
            <div class="max-w-3xl">
                <div class="inline-flex items-center gap-2 px-3 py-1.5 rounded-full bg-white/10 backdrop-blur-md border border-white/20 text-xs sm:text-sm font-medium mb-6">
                    <span class="w-2 h-2 rounded-full bg-emerald-400 animate-pulse"></span>
                    Kontraktor & Perdagangan Umum Terpercaya
                </div>
                <h1 class="text-4xl sm:text-5xl lg:text-6xl font-extrabold tracking-tight leading-tight mb-6">
                    PT Bangun Manunggal Trisno
                </h1>
                <p class="text-lg sm:text-xl text-slate-200 mb-8 font-normal leading-relaxed">
                    Mitra Terpercaya Solusi Konstruksi dan Perdagangan Umum dengan Komitmen Mutu Terbaik, Ketepatan Waktu, dan Legalitas Lengkap.
                </p>
                <div class="flex flex-col sm:flex-row gap-4">
                    <a href="https://wa.me/6281284186229?text=Halo%20PT%20Bangun%20Manunggal%20Trisno,%20saya%20ingin%20konsultasi%20proyek%20konstruksi" target="_blank" class="bg-emerald-600 hover:bg-emerald-700 text-white px-8 py-4 rounded-xl font-bold text-base transition shadow-lg shadow-emerald-900/30 flex items-center justify-center gap-3">
                        <i class="fa-brands fa-whatsapp text-2xl"></i>
                        <span>Konsultasi Proyek (WhatsApp)</span>
                    </a>
                    <a href="#layanan" class="bg-white/10 hover:bg-white/20 border border-white/30 text-white px-8 py-4 rounded-xl font-semibold text-base transition backdrop-blur-sm flex items-center justify-center">
                        Lihat Layanan Kami
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- 2. TENTANG KAMI -->
    <section id="tentang" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
                <div>
                    <span class="text-brand-blue font-bold text-sm tracking-wider uppercase mb-2 block">Tentang Perusahaan</span>
                    <h2 class="text-3xl sm:text-4xl font-extrabold text-slate-900 mb-6 leading-tight">
                        Komitmen Utama Kami Adalah Kualitas & Kepercayaan
                    </h2>
                    <p class="text-slate-600 leading-relaxed mb-6 text-base sm:text-lg">
                        <strong>PT Bangun Manunggal Trisno</strong> adalah perusahaan yang bergerak di bidang jasa konstruksi terintegrasi dan perdagangan umum. Kami berkomitmen memberikan hasil pembangunan yang kokoh, aman, tepat waktu, dan berstandar mutu tinggi.
                    </p>
                    <p class="text-slate-600 leading-relaxed mb-8 text-base sm:text-lg">
                        Dengan didukung oleh tenaga ahli profesional dan berpengalaman di bidangnya, kami siap melayani berbagai kebutuhan proyek konstruksi skala kecil, menengah, hingga besar secara efisien dan transparan.
                    </p>
                    <div class="grid grid-cols-2 gap-4 pt-4 border-t border-slate-100">
                        <div class="flex items-center gap-3">
                            <div class="w-12 h-12 rounded-lg bg-brand-accent flex items-center justify-center text-brand-blue">
                                <i class="fa-solid fa-shield-halved text-xl"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-slate-900">Legalitas Resmi</h4>
                                <p class="text-xs text-slate-500">Berbadan Hukum (PT)</p>
                            </div>
                        </div>
                        <div class="flex items-center gap-3">
                            <div class="w-12 h-12 rounded-lg bg-brand-accent flex items-center justify-center text-brand-blue">
                                <i class="fa-solid fa-user-gear text-xl"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-slate-900">Tim Profesional</h4>
                                <p class="text-xs text-slate-500">Ahli & Berpengalaman</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="relative">
                    <img src="https://images.unsplash.com/photo-1504307651254-35680f356dfd?auto=format&fit=crop&q=80&w=1000" alt="Konstruksi PT Bangun Manunggal Trisno" class="rounded-2xl shadow-2xl w-full h-[450px] object-cover">
                    <div class="absolute -bottom-6 -left-6 bg-brand-blue text-white p-6 rounded-2xl shadow-xl hidden sm:block max-w-xs">
                        <p class="text-3xl font-extrabold mb-1">100%</p>
                        <p class="text-sm font-medium text-slate-200">Komitmen pada Mutu, Keselamatan Kerja, dan Ketepatan Waktu Proyek</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 3. LAYANAN KAMI -->
    <section id="layanan" class="py-20 bg-slate-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <span class="text-brand-blue font-bold text-sm tracking-wider uppercase mb-2 block">Layanan Utama</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-slate-900">Solusi Konstruksi & Perdagangan Terlengkap</h2>
                <p class="text-slate-600 mt-4 text-lg">Kami menyediakan berbagai layanan bidang jasa konstruksi dan pengerjaan teknik dengan standar profesionalisme tinggi.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Service 1 -->
                <div class="bg-white p-8 rounded-2xl border border-slate-200/80 shadow-sm hover:shadow-xl transition-all duration-300 group">
                    <div class="w-14 h-14 bg-brand-blue/10 text-brand-blue rounded-xl flex items-center justify-center text-2xl mb-6 group-hover:bg-brand-blue group-hover:text-white transition-colors">
                        <i class="fa-solid fa-building"></i>
                    </div>
                    <h3 class="text-xl font-bold text-slate-900 mb-3">Konstruksi Bangunan & Gedung</h3>
                    <p class="text-slate-600 text-sm leading-relaxed">
                        Pembangunan rumah tinggal, ruko, gedung perkantoran, dan fasilitas umum dari perencanaan teknis hingga serah terima pekerjaan secara sempurna.
                    </p>
                </div>

                <!-- Service 2 -->
                <div class="bg-white p-8 rounded-2xl border border-slate-200/80 shadow-sm hover:shadow-xl transition-all duration-300 group">
                    <div class="w-14 h-14 bg-brand-blue/10 text-brand-blue rounded-xl flex items-center justify-center text-2xl mb-6 group-hover:bg-brand-blue group-hover:text-white transition-colors">
                        <i class="fa-solid fa-hammer"></i>
                    </div>
                    <h3 class="text-xl font-bold text-slate-900 mb-3">Renovasi & Restorasi</h3>
                    <p class="text-slate-600 text-sm leading-relaxed">
                        Layanan perbaikan, perluasan struktur, pembaruan fasad, serta penataan interior/eksterior bangunan untuk tampilan dan daya tahan maksimal.
                    </p>
                </div>

                <!-- Service 3 -->
                <div class="bg-white p-8 rounded-2xl border border-slate-200/80 shadow-sm hover:shadow-xl transition-all duration-300 group">
                    <div class="w-14 h-14 bg-brand-blue/10 text-brand-blue rounded-xl flex items-center justify-center text-2xl mb-6 group-hover:bg-brand-blue group-hover:text-white transition-colors">
                        <i class="fa-solid fa-road"></i>
                    </div>
                    <h3 class="text-xl font-bold text-slate-900 mb-3">Pekerjaan Infrastruktur & Sipil</h3>
                    <p class="text-slate-600 text-sm leading-relaxed">
                        Pengerjaan jalan, saluran air/drainase, pembuatan pondasi berat, serta proyek pekerjaan tanah sipil (*earthwork*) secara menyeluruh.
                    </p>
                </div>

                <!-- Service 4 -->
                <div class="bg-white p-8 rounded-2xl border border-slate-200/80 shadow-sm hover:shadow-xl transition-all duration-300 group">
                    <div class="w-14 h-14 bg-brand-blue/10 text-brand-blue rounded-xl flex items-center justify-center text-2xl mb-6 group-hover:bg-brand-blue group-hover:text-white transition-colors">
                        <i class="fa-solid fa-list-check"></i>
                    </div>
                    <h3 class="text-xl font-bold text-slate-900 mb-3">Manajemen & Konsultasi Proyek</h3>
                    <p class="text-slate-600 text-sm leading-relaxed">
                        Pengawasan konstruksi, penyusunan Rencana Anggaran Biaya (RAB), estimasi ekonomis, serta tata kelola proyek secara efektif dan hemat biaya.
                    </p>
                </div>

                <!-- Service 5 -->
                <div class="bg-white p-8 rounded-2xl border border-slate-200/80 shadow-sm hover:shadow-xl transition-all duration-300 group md:col-span-2 lg:col-span-1">
                    <div class="w-14 h-14 bg-brand-blue/10 text-brand-blue rounded-xl flex items-center justify-center text-2xl mb-6 group-hover:bg-brand-blue group-hover:text-white transition-colors">
                        <i class="fa-solid fa-dumpster"></i>
                    </div>
                    <h3 class="text-xl font-bold text-slate-900 mb-3">Pematangan Lahan</h3>
                    <p class="text-slate-600 text-sm leading-relaxed">
                        Jasa persiapan lahan terlengkap mencakup <em>land clearing</em>, pemotongan dan pengurugan (*cut and fill*), pemadatan (*compaction*), dan pembuatan drainase.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- 4. KEUNGGULAN KAMI -->
    <section id="keunggulan" class="py-20 bg-brand-dark text-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <span class="text-blue-400 font-bold text-sm tracking-wider uppercase mb-2 block">Mengapa Memilih Kami</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-white">Keunggulan PT Bangun Manunggal Trisno</h2>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
                <div class="bg-white/5 border border-white/10 p-6 rounded-xl">
                    <i class="fa-solid fa-users-gear text-3xl text-blue-400 mb-4"></i>
                    <h3 class="text-lg font-bold mb-2">Tenaga Ahli Berpengalaman</h3>
                    <p class="text-slate-300 text-sm">Dikerjakan langsung oleh tim profesional dan teknisi handal yang berpengalaman di bidangnya.</p>
                </div>
                <div class="bg-white/5 border border-white/10 p-6 rounded-xl">
                    <i class="fa-solid fa-award text-3xl text-blue-400 mb-4"></i>
                    <h3 class="text-lg font-bold mb-2">Mutu & Kualitas Terjamin</h3>
                    <p class="text-slate-300 text-sm">Penggunaan material standar mutu tinggi serta penerapan metode pengawasan konstruksi teruji.</p>
                </div>
                <div class="bg-white/5 border border-white/10 p-6 rounded-xl">
                    <i class="fa-solid fa-clock text-3xl text-blue-400 mb-4"></i>
                    <h3 class="text-lg font-bold mb-2">Tepat Waktu & Transparan</h3>
                    <p class="text-slate-300 text-sm">Perencanaan pengerjaan terstruktur dengan jadwal tepat serta estimasi anggaran biaya yang jelas.</p>
                </div>
                <div class="bg-white/5 border border-white/10 p-6 rounded-xl">
                    <i class="fa-solid fa-file-contract text-3xl text-blue-400 mb-4"></i>
                    <h3 class="text-lg font-bold mb-2">Legalitas Lengkap</h3>
                    <p class="text-slate-300 text-sm">Perusahaan resmi berbadan hukum berbentuk Perseroan Terbatas (PT) dengan izin usaha resmi.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- PORTOFOLIO PROYEK -->
    <section id="portofolio" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-12">
                <span class="text-brand-blue font-bold text-sm tracking-wider uppercase mb-2 block">Galeri Karya</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-slate-900">Dokumentasi Proyek</h2>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <div class="rounded-2xl overflow-hidden shadow-md group relative">
                    <img src="https://images.unsplash.com/photo-1590486803833-1c5dc8ddd4c8?auto=format&fit=crop&q=80&w=800" alt="Pematangan Lahan" class="w-full h-64 object-cover group-hover:scale-105 transition duration-500">
                    <div class="absolute inset-0 bg-gradient-to-t from-slate-900/90 via-slate-900/30 to-transparent p-6 flex flex-col justify-end">
                        <span class="text-xs text-blue-400 font-semibold uppercase">Pematangan Lahan</span>
                        <h3 class="text-lg font-bold text-white">Cut and Fill & Land Clearing</h3>
                    </div>
                </div>
                <div class="rounded-2xl overflow-hidden shadow-md group relative">
                    <img src="https://images.unsplash.com/photo-1486406146926-c627a92ad1ab?auto=format&fit=crop&q=80&w=800" alt="Konstruksi Gedung" class="w-full h-64 object-cover group-hover:scale-105 transition duration-500">
                    <div class="absolute inset-0 bg-gradient-to-t from-slate-900/90 via-slate-900/30 to-transparent p-6 flex flex-col justify-end">
                        <span class="text-xs text-blue-400 font-semibold uppercase">Konstruksi Gedung</span>
                        <h3 class="text-lg font-bold text-white">Pembangunan Fasilitas & Ruko</h3>
                    </div>
                </div>
                <div class="rounded-2xl overflow-hidden shadow-md group relative">
                    <img src="https://images.unsplash.com/photo-1621905251189-08b45d6a269e?auto=format&fit=crop&q=80&w=800" alt="Pekerjaan Infrastruktur" class="w-full h-64 object-cover group-hover:scale-105 transition duration-500">
                    <div class="absolute inset-0 bg-gradient-to-t from-slate-900/90 via-slate-900/30 to-transparent p-6 flex flex-col justify-end">
                        <span class="text-xs text-blue-400 font-semibold uppercase">Infrastruktur</span>
                        <h3 class="text-lg font-bold text-white">Drainase & Pengerjaan Jalan</h3>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 5. KONTAK & LOKASI -->
    <section id="kontak" class="py-20 bg-slate-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12">

                <!-- Contact Detail Box -->
                <div class="lg:col-span-5 bg-white p-8 sm:p-10 rounded-2xl border border-slate-200/80 shadow-md">
                    <span class="text-brand-blue font-bold text-sm tracking-wider uppercase mb-2 block">Hubungi Kami</span>
                    <h2 class="text-2xl sm:text-3xl font-extrabold text-slate-900 mb-8">Informasi Kantor & Kontak</h2>

                    <div class="space-y-6">
                        <!-- Alamat -->
                        <div class="flex items-start gap-4">
                            <div class="w-12 h-12 bg-brand-accent text-brand-blue rounded-xl flex items-center justify-center shrink-0 font-bold text-xl">
                                <i class="fa-solid fa-location-dot"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-slate-900 mb-1">Alamat Kantor</h4>
                                <p class="text-slate-600 text-sm leading-relaxed">
                                    Jl. Green Lake City Boulevard, Jl. West Europe VIII No.69, RT.001/RW.001, Ketapang, Kec. Cipondoh, Kota Tangerang, Banten 15147
                                </p>
                            </div>
                        </div>

                        <!-- Telepon -->
                        <div class="flex items-start gap-4">
                            <div class="w-12 h-12 bg-brand-accent text-brand-blue rounded-xl flex items-center justify-center shrink-0 font-bold text-xl">
                                <i class="fa-solid fa-phone"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-slate-900 mb-1">Telepon Kantor</h4>
                                <a href="tel:02123096007" class="text-slate-600 hover:text-brand-blue text-sm transition block font-medium">
                                    021-23096007
                                </a>
                            </div>
                        </div>

                        <!-- WhatsApp -->
                        <div class="flex items-start gap-4">
                            <div class="w-12 h-12 bg-emerald-50 text-emerald-600 rounded-xl flex items-center justify-center shrink-0 font-bold text-xl">
                                <i class="fa-brands fa-whatsapp"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-slate-900 mb-1">WhatsApp Responsive</h4>
                                <a href="https://wa.me/6281284186229" target="_blank" class="text-slate-600 hover:text-emerald-600 text-sm transition block font-medium">
                                    0812-8418-6229
                                </a>
                            </div>
                        </div>

                        <!-- Email -->
                        <div class="flex items-start gap-4">
                            <div class="w-12 h-12 bg-brand-accent text-brand-blue rounded-xl flex items-center justify-center shrink-0 font-bold text-xl">
                                <i class="fa-solid fa-envelope"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-slate-900 mb-1">Email Resmi</h4>
                                <a href="mailto:sutrisno.bmt@gmail.com" class="text-slate-600 hover:text-brand-blue text-sm transition block font-medium">
                                    sutrisno.bmt@gmail.com
                                </a>
                            </div>
                        </div>

                        <!-- Jam Operasional -->
                        <div class="flex items-start gap-4">
                            <div class="w-12 h-12 bg-brand-accent text-brand-blue rounded-xl flex items-center justify-center shrink-0 font-bold text-xl">
                                <i class="fa-solid fa-clock"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-slate-900 mb-1">Jam Operasional</h4>
                                <p class="text-slate-600 text-sm">
                                    Senin – Sabtu (08.00 – 17.00 WIB)
                                </p>
                            </div>
                        </div>
                    </div>

                    <div class="mt-8 pt-6 border-t border-slate-100">
                        <a href="https://wa.me/6281284186229?text=Halo%20PT%20Bangun%20Manunggal%20Trisno,%20saya%20ingin%20berkonsultasi" target="_blank" class="w-full bg-emerald-600 hover:bg-emerald-700 text-white font-bold py-3.5 px-4 rounded-xl transition flex items-center justify-center gap-2">
                            <i class="fa-brands fa-whatsapp text-xl"></i> Chat WhatsApp Sekarang
                        </a>
                    </div>
                </div>

                <!-- Google Maps Interactive Widget -->
                <div class="lg:col-span-7 flex flex-col h-full">
                    <div class="bg-white p-4 rounded-2xl border border-slate-200/80 shadow-md flex-1 flex flex-col">
                        <div class="flex items-center justify-between mb-4 px-2">
                            <h3 class="font-bold text-slate-900 text-lg flex items-center gap-2">
                                <i class="fa-solid fa-map-location-dot text-brand-blue"></i>
                                Lokasi Google Maps
                            </h3>
                            <a href="https://maps.google.com/?q=Jl.+Green+Lake+City+Boulevard+West+Europe+VIII+No.69+Cipondoh+Tangerang" target="_blank" class="text-xs bg-brand-accent text-brand-blue hover:bg-brand-blue hover:text-white px-3 py-1.5 rounded-lg font-semibold transition flex items-center gap-1">
                                <span>Buka Aplikasi Maps</span>
                                <i class="fa-solid fa-arrow-up-right-from-square text-[10px]"></i>
                            </a>
                        </div>
                        
                        <div class="w-full h-[380px] lg:h-full rounded-xl overflow-hidden border border-slate-200 relative">
                            <iframe 
                                title="Peta Lokasi PT Bangun Manunggal Trisno"
                                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3966.521260322283!2d106.7025!3d-6.1947!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e69f826359e19d7%3A0x7d2876f2f0123456!2sGreen%20Lake%20City!5e0!3m2!1sid!2sid!4v1700000000000!5m2!1sid!2sid" 
                                class="w-full h-full border-0" 
                                allowfullscreen="" 
                                loading="lazy" 
                                referrerpolicy="no-referrer-when-downgrade">
                            </iframe>
                        </div>

                        <div class="mt-4 p-3 bg-amber-50 border border-amber-200/60 rounded-xl flex items-center justify-between gap-4">
                            <div class="flex items-center gap-3">
                                <i class="fa-solid fa-star text-amber-500 text-xl"></i>
                                <span class="text-xs sm:text-sm font-medium text-slate-700">Berikan ulasan atau lihat rujukan petunjuk arah kantor di Google.</span>
                            </div>
                            <a href="https://maps.google.com/?q=Jl.+Green+Lake+City+Boulevard+West+Europe+VIII+No.69+Cipondoh+Tangerang" target="_blank" class="shrink-0 bg-white border border-slate-200 text-slate-800 hover:bg-slate-50 text-xs font-bold px-3 py-2 rounded-lg shadow-sm transition">
                                Review & Arah
                            </a>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- FOOTER -->
    <footer class="bg-brand-dark text-slate-400 py-12 border-t border-white/10">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row justify-between items-center gap-6">
                <div class="flex items-center gap-3">
                    <div class="w-10 h-10 bg-white rounded-lg p-1 flex items-center justify-center shrink-0">
                        <svg viewBox="0 0 100 100" class="w-full h-full">
                            <path d="M 22,12 L 64,12 C 78,12 88,20 88,34 C 88,44 82,50 72,53 C 84,57 90,66 90,78 C 90,92 78,100 62,100 L 22,100 Z M 52,56 L 22,86 L 22,56 Z M 44,32 L 64,32 C 68,32 72,30 72,26 C 72,22 68,20 64,20 L 44,20 Z M 44,78 L 66,78 C 71,78 75,75 75,70 C 75,65 71,62 66,62 L 44,62 Z" fill="#0F387A"/>
                        </svg>
                    </div>
                    <div>
                        <span class="text-white font-bold text-base block">PT BANGUN MANUNGGAL TRISNO</span>
                        <span class="text-xs text-slate-400">Jasa Konstruksi & Perdagangan Umum</span>
                    </div>
                </div>
                <div class="text-xs text-center md:text-right">
                    <p>&copy; 2026 PT Bangun Manunggal Trisno. Hak Cipta Dilindungi Undang-Undang.</p>
                </div>
            </div>
        </div>
    </footer>

    <!-- FLOATING WHATSAPP BUTTON -->
    <a href="https://wa.me/6281284186229?text=Halo%20PT%20Bangun%20Manunggal%20Trisno,%20saya%20ingin%20konsultasi%20proyek" target="_blank" aria-label="Konsultasi WhatsApp" class="fixed bottom-6 right-6 z-50 bg-emerald-500 hover:bg-emerald-600 text-white w-14 h-14 rounded-full shadow-2xl flex items-center justify-center text-3xl transition-transform hover:scale-110 active:scale-95 group">
        <i class="fa-brands fa-whatsapp"></i>
        <span class="absolute right-16 bg-slate-900 text-white text-xs font-semibold px-3 py-1.5 rounded-lg whitespace-nowrap opacity-0 group-hover:opacity-100 transition-opacity duration-200 pointer-events-none shadow-md">
            Konsultasi WhatsApp
        </span>
    </a>

    <!-- SCRIPT MOBILE MENU -->
    <script>
        const menuBtn = document.getElementById('menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');

        menuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Close menu on navigation click
        document.querySelectorAll('#mobile-menu a').forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        });
    </script>
</body>
</html>
