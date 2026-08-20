html
<!DOCTYPE html>
<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PRIMACELL - Jasa Servis HP Panggilan Ke Rumah Batulicin & Simpang Empat</title>
    
    <!-- SEO Meta Tags -->
    <meta name="description" content="Jasa servis HP panggilan ke rumah profesional di Simpang Empat, Batulicin, Plajau, & Sungai Kecil. Hubungi 085161686967 untuk perbaikan LCD, charging, IC, iPhone & Android. Cepat, transparan, terpercaya.">
    <meta name="keywords" content="servis hp panggilan batulicin, servis hp simpang empat, ganti lcd batulicin, servis iphone batulicin, primacell, teknisi hp panggilan, ganti konektor cas">
    <meta name="author" content="PRIMACELL Smartphone Repair Specialists">
    <meta name="robots" content="index, follow">

    <!-- Open Graph / Social Media -->
    <meta property="og:type" content="website">
    <meta property="og:site_name" content="PRIMACELL">
    <meta property="og:title" content="PRIMACELL - Jasa Servis HP Panggilan Ke Rumah | Batulicin & Simpang Empat">
    <meta property="og:description" content="Teknisi berpengalaman datang langsung ke lokasi Anda. Cepat, transparan, dan bergaransi. Hubungi 085161686967.">

    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            50: '#f0f7ff',
                            100: '#e0effe',
                            200: '#bae0fd',
                            300: '#7cc5fb',
                            400: '#36a9f7',
                            500: '#0c8de9',
                            600: '#006ec7',
                            700: '#0058a3',
                            800: '#054b87',
                            900: '#0a3f70',
                            950: '#07284a',
                        },
                        dark: {
                            800: '#0e1726',
                            900: '#090d16',
                            950: '#04070d',
                        }
                    },
                    fontFamily: {
                        sans: ['Plus Jakarta Sans', 'Inter', 'sans-serif'],
                    },
                    boxShadow: {
                        'glow': '0 0 35px -5px rgba(12, 141, 233, 0.4)',
                        'glow-lg': '0 0 50px -10px rgba(12, 141, 233, 0.6)',
                        'glow-emerald': '0 0 35px -5px rgba(16, 185, 129, 0.4)',
                    }
                }
            }
        }
    </script>

    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800;900&display=swap" rel="stylesheet">
    
    <!-- Alpine.js & Lucide Icons -->
    <script src="https://cdn.jsdelivr.net/npm/alpinejs@3.x.x/dist/cdn.min.js"></script>
    <script src="https://unpkg.com/lucide@latest"></script>

    <!-- AOS Animation Library -->
    <link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />

    <!-- Custom Modern Styling -->
    <style>
        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
            background-color: #090d16;
            color: #e2e8f0;
        }
        .glass-nav {
            background: rgba(9, 13, 22, 0.85);
            backdrop-filter: blur(16px);
            -webkit-backdrop-filter: blur(16px);
            border-bottom: 1px solid rgba(255, 255, 255, 0.08);
        }
        .glass-card {
            background: rgba(14, 23, 38, 0.7);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(255, 255, 255, 0.08);
        }
        .glass-card-hover {
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }
        .glass-card-hover:hover {
            background: rgba(20, 32, 54, 0.85);
            border-color: rgba(12, 141, 233, 0.4);
            transform: translateY(-4px);
            box-shadow: 0 12px 30px -10px rgba(12, 141, 233, 0.25);
        }
        .hero-gradient {
            background: radial-gradient(circle at 50% 0%, rgba(12, 141, 233, 0.18) 0%, rgba(9, 13, 22, 0) 70%);
        }
        .cta-gradient {
            background: linear-gradient(135deg, #0058a3 0%, #0c8de9 50%, #054b87 100%);
        }
        .text-gradient {
            background: linear-gradient(135deg, #ffffff 0%, #93c5fd 50%, #38bdf8 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .text-gradient-gold {
            background: linear-gradient(135deg, #fde047 0%, #eab308 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        @keyframes float {
            0%, 10
