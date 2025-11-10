<!DOCTYPE html>
<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <!-- Meta SEO dari Skema -->
    <title>Co.PPI: Kopi Susu Segar, Kuasai Kebahagiaanmu</title>
    <meta name="description" content="Nikmati kopi susu segar premium dari Co.PPI. Tersedia varian Americano, Brown Sugar, dan Almond. Pesan sekarang, kuasai kebahagiaanmu!">

    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Load Font (Inter) -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;800&display=swap" rel="stylesheet">

    <script>
        // Konfigurasi Tailwind untuk menyertakan palet warna kustom
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        'soft-pink': '#EBC9C9',
                        'dark-brown': '#3B2B26',
                        'cream': '#FDF9F3',
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    }
                }
            }
        }
    </script>

    <style>
        /* Base styles */
        body {
            font-family: 'Inter', sans-serif;
            background-color: #FDF9F3; /* Warna Latar Belakang: Cream */
            color: #3B2B26; /* Warna Teks: Dark Brown */
        }

        /* Style Tombol CTA (Call to Action) Utama */
        .cta-button {
            background-color: #EBC9C9; /* Soft Pink */
            color: #3B2B26; /* Dark Brown */
            font-weight: 600;
            border-radius: 8px;
            padding: 0.75rem 1.5rem;
            transition: all 0.3s ease;
            box-shadow: 0 4px 10px -2px rgba(0, 0, 0, 0.1);
        }
        .cta-button:hover {
            opacity: 0.85;
            transform: translateY(-2px);
            box-shadow: 0 6px 12px -2px rgba(0, 0, 0, 0.15);
        }

        /* Style Tombol CTA Sekunder */
        .cta-secondary {
            background-color: transparent;
            border: 2px solid #EBC9C9; /* Soft Pink */
            color: #3B2B26; /* Dark Brown */
            font-weight: 600;
            border-radius: 8px;
            padding: 0.625rem 1.25rem;
            transition: all 0.3s ease;
        }
        .cta-secondary:hover {
            background-color: #EBC9C9;
        }
    </style>
</head>
<body class="bg-cream text-dark-brown">

    <!-- 1. Header / Navigasi -->
    <header class="sticky top-0 z-50 w-full bg-cream/90 backdrop-blur-sm shadow-sm">
        <nav class="container mx-auto max-w-6xl px-4 py-4 flex justify-between items-center">
            <!-- Logo -->
            <a href="#" class="text-2xl font-bold text-dark-brown">Co.PPI</a>
            
            <!-- Menu (Desktop) -->
            <div class="hidden md:flex space-x-8">
                <a href="#produk" class="hover:text-soft-pink transition-colors">Varian Rasa</a>
                <a href="#cerita" class="hover:text-soft-pink transition-colors">Cerita Kami</a>
                <a href="#testimoni" class="hover:text-soft-pink transition-colors">Testimoni</a>
            </div>
            
            <!-- Tombol CTA Header -->
            <a href="#pesan" class="cta-button">
                Pesan Sekarang
            </a>
        </nav>
    </header>

    <main>

        <!-- 2. Hero Section -->
        <section class="container mx-auto max-w-6xl px-4 pt-20 pb-16 md:pt-32 md:pb-24 flex flex-col md:flex-row items-center">
            <!-- Teks Hero -->
            <div class="w-full md:w-1/2 text-center md:text-left mb-10 md:mb-0">
                <h1 class="text-4xl md:text-5xl font-extrabold mb-4 leading-tight">
                    Co.PPI: Kopi Susu Segar, Kuasai Kebahagiaanmu.
                </h1>
                <p class="text-lg mb-8 max-w-lg mx-auto md:mx-0">
                    Dibuat dari biji kopi pilihan dan bahan premium. Nikmati ketenangan dalam setiap tegukan. Pesan sekarang, kami antar ke tempatmu!
                </p>
                <div class="flex gap-4 justify-center md:justify-start">
                    <a href="#pesan" class="cta-button">Pesan Sekarang</a>
                    <a href="#produk" class="cta-secondary">Lihat Varian</a>
                </div>
            </div>
            
            <!-- Gambar Hero -->
            <div class="w-full md:w-1/2">
                <!-- Ganti URL placeholder ini dengan URL gambar produk Anda -->
                <img src="https://placehold.co/600x600/EBC9C9/3B2B26?text=Foto+Produk+Co.PPI" 
                     alt="Tiga varian kopi Co.PPI: Almond, Brown Sugar, dan Americano" 
                     class="rounded-lg shadow-xl w-full max-w-md mx-auto">
            </div>
        </section>

        <!-- 4. Product Section (Varian Rasa) -->
        <section id="produk" class="py-16 bg-white">
            <div class="container mx-auto max-w-6xl px-4">
                <h2 class="text-3xl font-bold text-center mb-12">
                    Temukan Rasa Favoritmu
                </h2>
                
                <!-- Grid Produk -->
                <div class="grid md:grid-cols-3 gap-8">
                    
                    <!-- Kartu Produk 1: Americano -->
                    <div class="bg-cream rounded-lg shadow-lg overflow-hidden flex flex-col">
                        <img src="https://placehold.co/400x400/3B2B26/FDF9F3?text=Americano" 
                             alt="Botol Kopi Co.PPI Varian Americano" 
                             class="w-full h-64 object-cover">
                        <div class="p-6 flex flex-col flex-grow">
                            <h3 class="text-2xl font-bold mb-2">Americano</h3>
                            <p class="mb-4 flex-grow">
                                Kopi hitam klasik yang kuat dan kaya rasa, tanpa gula, untuk semangat sepanjang hari.
                            </p>
                            <div class="text-xl font-semibold text-dark-brown mt-4">Rp 18.000</div>
                        </div>
                    </div>
                    
                    <!-- Kartu Produk 2: Brown Sugar -->
                    <div class="bg-cream rounded-lg shadow-lg overflow-hidden flex flex-col">
                        <img src="https://placehold.co/400x400/C19A6B/FDF9F3?text=Brown+Sugar" 
                             alt="Botol Kopi Susu Co.PPI Varian Brown Sugar" 
                             class="w-full h-64 object-cover">
                        <div class="p-6 flex flex-col flex-grow">
                            <h3 class="text-2xl font-bold mb-2">Brown Sugar</h3>
                            <p class="mb-4 flex-grow">
                                Perpaduan kopi susu creamy dengan manisnya gula aren alami. Pas untuk jadi mood booster-mu.
                            </p>
                            <div class="text-xl font-semibold text-dark-brown mt-4">Rp 20.000</div>
                        </div>
                    </div>

                    <!-- Kartu Produk 3: Almond -->
                    <div class="bg-cream rounded-lg shadow-lg overflow-hidden flex flex-col">
                        <img src="https://placehold.co/400x400/DABFA7/3B2B26?text=Almond" 
                             alt="Botol Kopi Susu Co.PPI Varian Almond" 
                             class="w-full h-64 object-cover">
                        <div class="p-6 flex flex-col flex-grow">
                            <h3 class="text-2xl font-bold mb-2">Almond</h3>
                            <p class="mb-4 flex-grow">
                                Rasa kopi susu unik dengan sentuhan gurih dan wangi dari sirup almond berkualitas.
                            </p>
                            <div class="text-xl font-semibold text-dark-brown mt-4">Rp 22.000</div>
                        </div>
                    </div>
                    
                </div>
            </div>
        </section>

        <!-- 5. "About Us" Section (Cerita Kami) -->
        <section id="cerita" class="py-20">
            <div class="container mx-auto max-w-3xl px-4 text-center">
                <h2 class="text-3xl font-bold mb-6">
                    Sedikit Tenang, Kuasai Kebahagiaan.
                </h2>
                <div class="space-y-4 text-lg">
                    <p>
                        Co.PPI (Kopi Susu Penuh Kebahagiaan) lahir dari filosofi bahwa ketenangan bisa ditemukan dalam jeda sederhana. Di tengah kesibukan, kami percaya secangkir kopi berkualitas bisa jadi teman terbaikmu untuk #KuasaiKebahagiaan.
                    </p>
                    <p>
                        Kami hanya menggunakan biji kopi [Asal Biji Kopi, misal: Robusta Temanggung] terbaik dan bahan-bahan segar tanpa pengawet untuk menjamin rasa yang konsisten dan berkualitas di setiap botolnya.
                    </p>
                    <p>
                        Kami bangga jadi bagian dari komunitas [Sebutkan Komunitas/Kota, misal: Sampit]. Ikuti perjalanan kami di Instagram <a href="https://www.instagram.com/bkpsdmkotim" target="_blank" class="font-semibold hover:text-soft-pink">@bkpsdmkotim</a>.
                    </p>
                </div>
            </div>
        </section>

        <!-- 6. Testimonials (Apa Kata Mereka) -->
        <section id="testimoni" class="py-16 bg-white">
            <div class="container mx-auto max-w-6xl px-4">
                <h2 class="text-3xl font-bold text-center mb-12">
                    Kata Mereka yang Sudah Bahagia
                </h2>
                <div class="grid md:grid-cols-3 gap-8">
                    <!-- Testimoni 1 -->
                    <div class="bg-cream p-6 rounded-lg shadow-lg">
                        <p class="italic text-lg mb-4">"Brown sugar-nya pas banget, creamy tapi kopinya tetap terasa. Nagih! Bakal repeat order pasti."</p>
                        <p class="font-bold text-right text-dark-brown">- Andini, Karyawan</p>
                    </div>
                    <!-- Testimoni 2 -->
                    <div class="bg-cream p-6 rounded-lg shadow-lg">
                        <p class="italic text-lg mb-4">"Americano-nya mantap. Nggak asam, pas buat kerja. Packaging-nya juga aman dan bagus."</p>
                        <p class="font-bold text-right text-dark-brown">- Bima, Mahasiswa</p>
                    </div>
                    <!-- Testimoni 3 -->
                    <div class="bg-cream p-6 rounded-lg shadow-lg">
                        <p class="italic text-lg mb-4">"Suka yang Almond, unik rasanya. Nggak terlalu manis dan wangi. Cepat juga pengirimannya."</p>
                        <p class="font-bold text-right text-dark-brown">- Sarah, Freelancer</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- 7. How to Order (Cara Pesan) -->
        <section id="cara-pesan" class="py-20">
            <div class="container mx-auto max-w-4xl px-4">
                <h2 class="text-3xl font-bold text-center mb-12">
                    3 Langkah Mudah Menuju Bahagia
                </h2>
                <div class="flex flex-col md:flex-row justify-between gap-10">
                    <!-- Langkah 1 -->
                    <div class="flex-1 text-center">
                        <div class="w-16 h-16 bg-soft-pink rounded-full flex items-center justify-center text-dark-brown font-bold text-2xl mx-auto mb-4">
                            1
                        </div>
                        <h3 class="text-xl font-bold mb-2">Pilih Rasa</h3>
                        <p>Tentukan varian Co.PPI favoritmu dari daftar produk kami.</p>
                    </div>
                    <!-- Langkah 2 -->
                    <div class="flex-1 text-center">
                        <div class="w-16 h-16 bg-soft-pink rounded-full flex items-center justify-center text-dark-brown font-bold text-2xl mx-auto mb-4">
                            2
                        </div>
                        <h3 class="text-xl font-bold mb-2">Kirim Pesanan</h3>
                        <p>Klik tombol WhatsApp dan kirim format pesananmu.</p>
                    </div>
                    <!-- Langkah 3 -->
                    <div class="flex-1 text-center">
                        <div class="w-16 h-16 bg-soft-pink rounded-full flex items-center justify-center text-dark-brown font-bold text-2xl mx-auto mb-4">
                            3
                        </div>
                        <h3 class="text-xl font-bold mb-2">Duduk Tenang</h3>
                        <p>Kopimu akan segera kami siapkan dan antar ke lokasimu (Area [Area Pengantaran]).</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- 8. Final Call-to-Action (CTA) -->
        <section id="pesan" class="py-20 bg-soft-pink">
            <div class="container mx-auto max-w-3xl px-4 text-center">
                <h2 class="text-3xl md:text-4xl font-extrabold text-dark-brown mb-4">
                    Siap Kuasai Kebahagiaanmu Hari Ini?
                </h2>
                <p class="text-lg text-dark-brown mb-8">
                    Jangan biarkan harimu berlalu tanpa secangkir ketenangan. Pesan Co.PPI sekarang!
                </p>
                <!-- Ganti NOMOR_ANDA dengan nomor WhatsApp (misal: 628123456789) -->
                <a href="https://api.whatsapp.com/send?phone=NOMOR_ANDA&text=Halo Co.PPI, saya mau pesan kopi"
                   target="_blank"
                   class="cta-button bg-dark-brown text-cream hover:bg-black py-4 px-8 text-lg font-bold">
                    PESAN VIA WHATSAPP
                </a>
            </div>
        </section>

        <!-- 9. FAQ (Frequently Asked Questions) -->
        <section id="faq" class="py-16">
            <div class="container mx-auto max-w-3xl px-4">
                <h2 class="text-3xl font-bold text-center mb-12">
                    Yang Sering Ditanyakan
                </h2>
                <div class="space-y-4">
                    <!-- FAQ 1 -->
                    <details class="bg-white p-4 rounded-lg shadow-sm group">
                        <summary class="font-semibold text-lg cursor-pointer list-none flex justify-between items-center">
                            Q: Apakah bisa kirim ke luar kota?
                            <span class="group-open:hidden">+</span>
                            <span class="hidden group-open:inline">-</span>
                        </summary>
                        <div class="pt-4 text-gray-700">
                            A: Saat ini kami hanya melayani pengantaran di dalam area [Area Pengantaran] untuk menjaga kesegaran produk.
                        </div>
                    </details>
                    <!-- FAQ 2 -->
                    <details class="bg-white p-4 rounded-lg shadow-sm group">
                        <summary class="font-semibold text-lg cursor-pointer list-none flex justify-between items-center">
                            Q: Kopinya tahan berapa lama?
                            <span class="group-open:hidden">+</span>
                            <span class="hidden group-open:inline">-</span>
                        </summary>
                        <div class="pt-4 text-gray-700">
                            A: Kopi kami dibuat segar setiap hari tanpa pengawet. Sebaiknya dikonsumsi habis dalam 3-4 hari. Harap selalu simpan di dalam kulkas (suhu di bawah 5°C).
                        </div>
                    </details>
                    <!-- FAQ 3 -->
                    <details class="bg-white p-4 rounded-lg shadow-sm group">
                        <summary class="font-semibold text-lg cursor-pointer list-none flex justify-between items-center">
                            Q: Apa saja metode pembayarannya?
                            <span class="group-open:hidden">+</span>
                            <span class="hidden group-open:inline">-</span>
                        </summary>
                        <div class="pt-4 text-gray-700">
                            A: Kami menerima transfer Bank [Nama Bank] dan e-wallet (DANA, OVO, GoPay).
                        </div>
                    </details>
                </div>
            </div>
        </section>

    </main>

    <!-- 10. Footer -->
    <footer class="bg-dark-brown text-cream py-12">
        <div class="container mx-auto max-w-6xl px-4">
            <div class="flex flex-col md:flex-row justify-between items-center text-center md:text-left">
                <div class="mb-4 md:mb-0">
                    <a href="#" class="text-2xl font-bold">Co.PPI</a>
                    <p class="text-sm text-cream/70">Kuasai Kebahagiaanmu.</p>
                </div>
                
                <div class="flex space-x-4 mb-4 md:mb-0">
                    <!-- Ikon Instagram -->
                    <a href="https://www.instagram.com/bkpsdmkotim" target="_blank" class="hover:opacity-70">
                        <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                            <path fill-rule="evenodd" d="M12.315 2.315a.75.75 0 01.75.75v.001c0 .414.336.75.75.75H15a.75.75 0 01.75.75v.001c0 .414.336.75.75.75h.001a.75.75 0 01.75.75v.001c0 .414.336.75.75.75h.001a.75.75 0 01.75.75v.001c0 .414.336.75.75.75h.001a.75.75 0 01.75.75v.001c0 .414.336.75.75.75h.001a.75.75 0 01.75.75v1.028a.75.75 0 01-.75.75h-.001a.75.75 0 01-.75-.75v-.001c0-.414-.336-.75-.75-.75h-.001a.75.75 0 01-.75-.75v-.001c0-.414-.336-.75-.75-.75h-.001a.75.75 0 01-.75-.75v-.001c0-.414-.336-.75-.75-.75h-.001a.75.75 0 01-.75-.75V7.5a.75.75 0 01.75-.75h.001a.75.75 0 01.75.75v.001c0 .414.336.75.75.75h.001a.75.75 0 01.75.75v.001c0 .414.336.75.75.75h.001a.75.75 0 01.75.75v.001c0 .414.336.75.75.75h.001a.75.75 0 01.75.75v.001c0 .414.336.75.75.75h.001a.75.75 0 01.75.75V15a.75.75 0 01-.75.75h-.001a.75.75 0 01-.75-.75v-.001c0-.414-.336-.75-.75-.75h-.001a.75.75 0 01-.75-.75v-.001c0-.414-.336-.75-.75-.75h-.001a.75.75 0 01-.75-.75v-.001c0-.414-.336-.75-.75-.75h-.001a.75.75 0 01-.75-.75v-.001c0-.414-.336-.75-.75-.75h-.001a.75.75 0 01-.75-.75V9a.75.75 0 01.75-.75h.001a.75.75 0 01.75.75v.001c0 .414.336.75.75.75h.001a.75.75 0 01.75.75v.001c0 .414.336.75.75.75h.001a.75.75 0 01.75.75v.001c0 .414.336.75.75.75h.001a.75.75 0 01.75.75V12a.75.75 0 01-.75.75h-.001a.75.75 0 01-.75-.75v-.001c0-.414-.336-.75-.75-.75H15a.75.75 0 01-.75-.75v-.001c0-.414-.336-.75-.75-.75h-.001a.75.75 0 01-.75-.75V4.5a.75.75 0 01.75-.75h.001a.75.75 0 01.75.75v.001c0 .414.336.75.75.75H12a.75.75 0 01-.75-.75V2.315z" clip-rule="evenodd" />
                            <path d="M12 2.25a9.75 9.75 0 100 19.5 9.75 9.75 0 000-19.5zM.75 12a11.25 11.25 0 1122.5 0 11.25 11.25 0 01-22.5 0z" />
                        </svg>
                    </a>
                    <!-- Anda bisa tambahkan ikon lain di sini -->
                </div>

                <div class="text-sm text-cream/70">
                    © 2025 Co.PPI. All Rights Reserved.
                </div>
            </div>
        </div>
    </footer>

</body>
</html>
