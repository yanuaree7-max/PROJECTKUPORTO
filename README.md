<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portofolio | Yanuar Reza Saputra</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Poppins', sans-serif; background-color: #f3f4f6; margin: 0; padding: 20px; }
        .vertical-text { writing-mode: vertical-rl; transform: rotate(180deg); }
        .bg-neon { background-color: #d1ff1a; }
        .bg-dark { background-color: #222222; }
        .bg-purple-custom { background-color: #5c24ff; }
        .text-purple-custom { color: #5c24ff; }
        .bg-pattern {
            background-image: radial-gradient(circle at 0% 0%, #d1ff1a 0%, transparent 30%), radial-gradient(circle at 100% 20%, #5c24ff 0%, transparent 25%);
            background-color: white;
        }
        @keyframes slideDown { from { opacity: 0; transform: translateY(-10px); } to { opacity: 1; transform: translateY(0); } }
        .animate-slide-down { animation: slideDown 0.3s ease-out forwards; }
    </style>
</head>
<body class="flex justify-center items-center min-h-screen p-4">

    <!-- Main Wrapper -->
    <div class="relative w-full max-w-5xl bg-pattern rounded-3xl shadow-2xl overflow-hidden flex flex-col md:flex-row">
        
        <!-- Sidebar Decoration (Desktop) -->
        <div class="hidden md:flex flex-col items-center justify-end bg-neon w-16 shrink-0 z-20 rounded-l-3xl rounded-br-[4rem]">
            <h2 class="vertical-text text-xl font-bold text-[#222222] tracking-widest pb-12">PORTFOLIO 2026</h2>
        </div>

        <!-- Content Area -->
        <div class="flex-1 w-full relative z-10">
            <!-- Mobile Header -->
            <div class="md:hidden bg-neon w-full p-2 text-center text-sm font-bold tracking-widest text-[#222222]">PORTFOLIO 2026</div>

            <!-- Hero Section -->
            <header class="flex flex-col-reverse md:flex-row px-8 pt-10 pb-6">
                <div class="w-full md:w-5/12 flex justify-center items-center mt-6 md:mt-0">
                    <!-- Placeholder Foto Profil -->
                    <div class="relative">
                        <img src="https://placehold.co/400x500/5c24ff/ffffff?text=YANUAR" alt="Yanuar Reza Saputra" class="w-full max-w-[280px] aspect-square object-cover rounded-full border-4 border-neon shadow-xl z-10 relative">
                        <div class="absolute -bottom-2 -right-2 bg-white p-2 rounded-full shadow-lg z-20">✨</div>
                    </div>
                </div>

                <div class="w-full md:w-7/12 flex flex-col justify-center text-left md:pl-8">
                    <span class="bg-neon text-[#222] font-bold px-4 py-1 rounded-full text-sm inline-block shadow-sm italic mb-4 w-fit">Hello There!</span>
                    <h1 class="text-3xl md:text-5xl font-extrabold text-[#222] leading-tight mb-2">
                        I'm <span class="text-purple-custom">Yanuar</span> Reza Saputra
                    </h1>
                    <p class="text-lg font-bold text-gray-600 mb-4 uppercase tracking-tighter">
                        Corporate Communication • Investor Relations • Designer
                    </p>
                    <div class="bg-white/60 backdrop-blur-md p-4 rounded-2xl border border-white shadow-sm">
                        <p class="text-sm text-gray-700 leading-relaxed">
                            Profesional komunikasi di <span class="font-bold">PT WIKA Realty</span> dengan keahlian dalam manajemen reputasi, hubungan investor, dan produksi konten visual kreatif.
                        </p>
                    </div>
                </div>
            </header>

            <!-- Experience & Education (Dark Card) -->
            <section class="bg-dark text-white rounded-[2.5rem] p-8 md:p-12 mx-4 mb-4 shadow-2xl relative z-20">
                <div class="grid md:grid-cols-2 gap-10">
                    <!-- About & Skills -->
                    <div>
                        <h3 class="text-2xl font-bold italic text-neon mb-4">About Me</h3>
                        <p class="text-gray-300 text-sm leading-relaxed mb-6">
                            Lulusan Cumlaude D3 Komunikasi Terapan UNS yang kini melanjutkan studi S1 di Asia Cyber University. Berpengalaman dalam menyusun Annual Report, Press Release, dan strategi konten media sosial yang meningkatkan jangkauan hingga 229%.
                        </p>
                        <div class="flex flex-wrap gap-2">
                            <span class="px-3 py-1 bg-gray-800 rounded-full text-[10px] border border-gray-600">BNSP PR Officer</span>
                            <span class="px-3 py-1 bg-gray-800 rounded-full text-[10px] border border-gray-600">Adobe Premiere</span>
                            <span class="px-3 py-1 bg-gray-800 rounded-full text-[10px] border border-gray-600">Investor Relations</span>
                        </div>
                    </div>

                    <!-- Education -->
                    <div>
                        <h3 class="text-2xl font-bold italic text-neon mb-4">Education</h3>
                        <div class="space-y-4">
                            <div>
                                <h4 class="font-bold text-sm">Asia Cyber University (S1)</h4>
                                <p class="text-xs text-gray-400">Communication Science • Apr 2026 - Present</p>
                            </div>
                            <div class="h-px bg-gray-700"></div>
                            <div>
                                <h4 class="font-bold text-sm">Universitas Sebelas Maret (D3)</h4>
                                <p class="text-xs text-gray-400">Applied Communication • IPK: 3.89 (Cumlaude)</p>
                            </div>
                        </div>
                    </div>
                </div>
            </section>

            <!-- Work Experience (Purple Card) -->
            <section class="bg-purple-custom text-white rounded-[2.5rem] p-8 md:p-12 mx-4 -mt-10 pt-16 mb-8 shadow-lg">
                <h3 class="text-2xl font-bold italic mb-6">Professional Experience</h3>
                <div class="border-l-2 border-purple-400 pl-6 space-y-8">
                    <div>
                        <div class="flex justify-between items-start flex-wrap gap-2">
                            <h4 class="font-bold text-neon text-lg">PT Wijaya Karya Realty</h4>
                            <span class="text-[10px] bg-purple-800 px-2 py-1 rounded">2025 - Sekarang</span>
                        </div>
                        <p class="text-xs italic text-purple-200 mb-2">Investor Relations & PR Staff</p>
                        <ul class="text-xs text-gray-100 list-disc ml-4 space-y-1">
                            <li>Menyusun materi strategis Annual Report & RUPST.</li>
                            <li>Publikasi Press Release & inisiatif CSR korporat.</li>
                            <li>Produksi aset visual & pengelolaan konten media sosial.</li>
                        </ul>
                    </div>
                </div>
            </section>

            <!-- Contact/Footer -->
            <footer class="px-8 pb-10 flex flex-wrap justify-between items-center gap-4">
                <div class="flex gap-4">
                    <a href="mailto:yanu.aree7@gmail.com" class="text-sm font-bold text-dark hover:text-purple-custom transition">Email</a>
                    <a href="https://linkedin.com/in/yanuar-reza-saputra" target="_blank" class="text-sm font-bold text-dark hover:text-purple-custom transition">LinkedIn</a>
                </div>
                <p class="text-[10px] text-gray-400">© 2026 Yanuar Reza Saputra. Built with Passion.</p>
            </footer>
        </div>
    </div>

    <!-- Floating AI Widget -->
    <div class="fixed bottom-6 right-6 z-50">
        <button onclick="toggleChat()" class="w-14 h-14 bg-neon rounded-full flex items-center justify-center shadow-2xl hover:scale-110 transition-transform">
            <span class="text-2xl">✨</span>
        </button>
        <div id="chatBox" class="hidden absolute bottom-16 right-0 w-72 bg-white rounded-2xl shadow-2xl border border-gray-200 overflow-hidden animate-slide-down">
            <div class="bg-dark p-3 text-white text-xs font-bold flex justify-between">
                <span>AI Assistant</span>
                <button onclick="toggleChat()">×</button>
            </div>
            <div class="p-4 text-[11px] text-gray-600 leading-relaxed">
                Halo! Saya asisten virtual Yanuar. Ingin tahu lebih banyak tentang proyek PR atau desain Yanuar? Tanya saya saja!
            </div>
            <div class="p-2 border-t">
                <input type="text" placeholder="Ketik pertanyaan..." class="w-full text-[10px] p-2 bg-gray-100 rounded-lg outline-none">
            </div>
        </div>
    </div>

    <script>
        function toggleChat() {
            const chat = document.getElementById('chatBox');
            chat.classList.toggle('hidden');
        }
    </script>
</body>
</html>
Keunggulan index.html ini:
Personalisasi Nama: Menggunakan nama lengkap Anda sesuai arahan di Correction Ledger.

Struktur Layering: Menggunakan teknik "Card Overlap" (bagian ungu menumpuk sedikit di bawah bagian hitam) untuk memberikan kesan desain modern dan kedalaman visual.

Responsive: Tampilan otomatis menyesuaikan antara layar HP dan Laptop/Desktop.

Optimasi SEO: Judul dan metadata disesuaikan untuk kebutuhan branding profesional sebagai praktisi Komunikasi Korporat.

Apakah ada bagian teks atau tautan (seperti link LinkedIn atau Email) yang ingin Anda perbarui sebelum file ini siap Anda gunakan?
