<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Uzay 101 - Evreni Keşfet</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            background-color: #0B0D17;
            color: #FFFFFF;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        .stars {
            background-image: radial-gradient(2px 2px at 20px 30px, #eee, rgba(0,0,0,0)),
                              radial-gradient(2px 2px at 40px 70px, #fff, rgba(0,0,0,0)),
                              radial-gradient(1px 1px at 90px 40px, #fff, rgba(0,0,0,0));
            background-repeat: repeat;
            background-size: 200px 200px;
        }
    </style>
</head>
<body class="stars min-h-screen flex flex-col justify-between">

    <!-- Header / Nav -->
    <header class="border-b border-gray-800 bg-black/50 backdrop-blur-md sticky top-0 z-50">
        <div class="max-w-6xl mx-auto px-4 py-4 flex justify-between items-center">
            <a href="#" class="text-2xl font-bold tracking-wider text-purple-400 flex items-center gap-2">
                🚀 UZAY 101
            </a>
            <nav class="hidden md:flex space-x-6 text-gray-300">
                <a href="#kesfet" class="hover:text-purple-400 transition">Keşfet</a>
                <a href="#gezegenler" class="hover:text-purple-400 transition">Gezegenler</a>
                <a href="#bilgi" class="hover:text-purple-400 transition">Temel Bilgiler</a>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="py-20 text-center px-4">
        <div class="max-w-3xl mx-auto">
            <h1 class="text-5xl font-extrabold mb-6 bg-gradient-to-r from-purple-400 to-blue-500 bg-clip-text text-transparent">
                Evrenin Derinliklerine Hoş Geldiniz
            </h1>
            <p class="text-lg text-gray-400 mb-8">
                Uzay 101 ile astronomi, gezegenler, kara delikler ve evrenin gizemleri hakkında temel bilgilere göz atın.
            </p>
            <a href="#gezegenler" class="bg-purple-600 hover:bg-purple-700 text-white px-6 py-3 rounded-full font-semibold transition">
                Keşfe Başla
            </a>
        </div>
    </section>

    <!-- Gezegenler Grid -->
    <section id="gezegenler" class="max-w-6xl mx-auto px-4 py-12">
        <h2 class="text-3xl font-bold text-center mb-10 text-purple-300">Güneş Sistemi & Ötesi</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
            <div class="bg-gray-900/80 border border-gray-800 p-6 rounded-2xl">
                <div class="text-4xl mb-4">🪐</div>
                <h3 class="text-xl font-bold mb-2 text-purple-400">Satürn</h3>
                <p class="text-gray-400 text-sm">Görkemli halkalarıyla bilinen, Güneş sistemimizin en ikonik gaz devlerinden biri.</p>
            </div>
            <div class="bg-gray-900/80 border border-gray-800 p-6 rounded-2xl">
                <div class="text-4xl mb-4">🔴</div>
                <h3 class="text-xl font-bold mb-2 text-purple-400">Mars</h3>
                <p class="text-gray-400 text-sm">Kızıl Gezegen, insanlığın uzay araştırmalarındaki en birincil hedef noktası.</p>
            </div>
            <div class="bg-gray-900/80 border border-gray-800 p-6 rounded-2xl">
                <div class="text-4xl mb-4">🕳️</div>
                <h3 class="text-xl font-bold mb-2 text-purple-400">Kara Delikler</h3>
                <p class="text-gray-400 text-sm">Işığın bile kaçamadığı, kütleçekiminin zirve yaptığı gizemli gök cisimleri.</p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="border-t border-gray-800 py-6 text-center text-gray-500 text-sm">
        &copy; 2026 Uzay 101 - Tüm hakları saklıdır.
    </footer>

</body>
</html>