<!DOCTYPE html>
<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portofolio Saya | Ramadhita Dyah Sulistyorini</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        body { font-family: 'Inter', sans-serif; }
        .nav-link { position: relative; }
        .nav-link::after {
            content: '';
            position: absolute;
            width: 0; height: 2px;
            bottom: -2px; left: 0;
            background-color: #3b82f6;
            transition: width 0.3s;
        }
        .nav-link:hover::after { width: 100%; }
    </style>
</head>
<body class="bg-slate-50 text-slate-900">

    <nav class="fixed top-0 w-full bg-white/80 backdrop-blur-md z-50 border-b border-slate-200">
        <div class="max-w-5xl mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#" class="text-xl font-bold tracking-tighter">Rin<span class="text-blue-600">.</span></a>
            <div class="hidden md:flex space-x-8 font-medium text-sm uppercase tracking-widest">
                <a href="#about" class="nav-link">About</a>
                <a href="#projects" class="nav-link">Projects</a>
                <a href="#contact" class="nav-link">Contact</a>
            </div>
        </div>
    </nav>

    <section class="h-screen flex flex-col justify-center items-center text-center px-6">
        <h2 class="text-slate-500 font-medium tracking-[0.2em] mb-4 uppercase">Web Developer & Designer</h2>
        <h1 class="text-5xl md:text-7xl font-bold mb-6 tracking-tight">Halo, Saya <span class="text-blue-600">Ramadhita.</span></h1>
        <p class="max-w-xl text-slate-600 leading-relaxed mb-8">
            Saya senang membangun produk digital yang fungsional, estetis, dan memberikan pengalaman pengguna yang luar biasa.
        </p>
        <a href="#projects" class="bg-slate-900 text-white px-8 py-3 rounded-full hover:bg-blue-600 transition duration-300">Lihat Karya Saya</a>
    </section>

    <section id="about" class="py-24 bg-white px-6">
        <div class="max-w-4xl mx-auto">
            <h3 class="text-3xl font-bold mb-12 border-b-4 border-blue-600 w-fit">Tentang Saya</h3>
            <div class="grid md:grid-cols-2 gap-12 items-center">
                <div class="bg-slate-200 aspect-square rounded-2xl overflow-hidden shadow-xl">
                    <img src="c:\Users\Administrator\Pictures\SEC\ranom thing\༺♡༻.jpeg" alt="Profile" class="w-full h-full object-cover">
                </div>
                <div>
                    <p class="text-slate-600 leading-relaxed mb-6">
                        Halo! Saya adalah seorang pengembang yang berfokus pada teknologi web modern. Saya memiliki minat besar dalam desain UI/UX dan pemrograman front-end.
                    </p>
                    <div class="space-y-4">
                        <h4 class="font-bold uppercase tracking-wider text-sm">Tech Stack:</h4>
                        <div class="flex flex-wrap gap-2">
                            <span class="bg-slate-100 px-4 py-1 rounded-full text-sm font-medium">HTML/CSS</span>
                            <span class="bg-slate-100 px-4 py-1 rounded-full text-sm font-medium">JavaScript</span>
                            <span class="bg-slate-100 px-4 py-1 rounded-full text-sm font-medium">React.js</span>
                            <span class="bg-slate-100 px-4 py-1 rounded-full text-sm font-medium">Tailwind CSS</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="projects" class="py-24 px-6 bg-slate-50">
        <div class="max-w-5xl mx-auto">
            <h3 class="text-3xl font-bold mb-12 text-center">Project Pilihan</h3>
            <div class="grid md:grid-cols-2 gap-8">
                <div class="group bg-white rounded-2xl overflow-hidden shadow-sm border border-slate-100 hover:shadow-xl transition">
                    <div class="h-64 bg-slate-300 overflow-hidden">
                        <img src="https://images.unsplash.com/photo-1460925895917-afdab827c52f?auto=format&fit=crop&w=800&q=80" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-6">
                        <h4 class="font-bold text-xl mb-2">E-Commerce App</h4>
                        <p class="text-slate-600 text-sm mb-4">Website toko online dengan fitur keranjang belanja dan payment gateway.</p>
                        <a href="#" class="text-blue-600 font-bold hover:underline">Lihat Detail →</a>
                    </div>
                </div>
                <div class="group bg-white rounded-2xl overflow-hidden shadow-sm border border-slate-100 hover:shadow-xl transition">
                    <div class="h-64 bg-slate-300 overflow-hidden">
                        <img src="https://images.unsplash.com/photo-1498050108023-c5249f4df085?auto=format&fit=crop&w=800&q=80" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-6">
                        <h4 class="font-bold text-xl mb-2">Class Website</h4>
                        <p class="text-slate-600 text-sm mb-4">Portal informasi untuk kelas dengan fitur galeri dan jadwal pelajaran.</p>
                        <a href="#" class="text-blue-600 font-bold hover:underline">Lihat Detail →</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="py-24 px-6 bg-slate-900 text-white">
        <div class="max-w-3xl mx-auto text-center">
            <h3 class="text-3xl font-bold mb-6">Ayo Berdiskusi!</h3>
            <p class="text-slate-400 mb-10">Jika kamu memiliki ide proyek atau sekadar ingin menyapa, silakan hubungi saya melalui email atau sosial media.</p>
            <div class="flex justify-center space-x-6 text-3xl">
                <a href="#" class="hover:text-blue-500 transition"><i class="fab fa-github"></i></a>
                <a href="#" class="hover:text-blue-400 transition"><i class="fab fa-linkedin"></i></a>
                <a href="#" class="hover:text-red-500 transition"><i class="fas fa-envelope"></i></a>
                <a href="#" class="hover:text-pink-500 transition"><i class="fab fa-instagram"></i></a>
            </div>
        </div>
    </section>

    <footer class="py-8 text-center text-slate-500 text-sm border-t border-slate-200 bg-white">
        <p>&copy; 2024 Nama Kamu. Built with Tailwind CSS & ❤️</p>
    </footer>

</body>
</html>
