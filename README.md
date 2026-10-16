<!DOCTYPE html>
<html lang="uz" class="dark scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EDU-Pro | Zamonaviy Online Ta'lim va Valyuta Kurslari Platformasi</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    colors: {
                        brand: {
                            50: '#eep2ff',
                            500: '#6366f1',
                            600: '#4f46e5',
                            700: '#4338ca',
                            accent: '#ec4899',
                            emerald: '#10b981',
                            dark: '#0b0f19',
                            card: '#111827'
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <!-- Lucide Icons -->
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        body { font-family: 'Inter', sans-serif; }
        .glass {
            background: rgba(17, 24, 39, 0.7);
            backdrop-filter: blur(16px);
            -webkit-backdrop-filter: blur(16px);
            border: 1px solid rgba(255, 255, 255, 0.08);
        }
        .glass-card {
            background: rgba(31, 41, 55, 0.4);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(255, 255, 255, 0.05);
        }
        .gradient-text {
            background: linear-gradient(135deg, #6366f1 0%, #ec4899 50%, #10b981 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .glow-effect {
            box-shadow: 0 0 25px -5px rgba(99, 102, 241, 0.4);
        }
        /* Custom Scrollbar */
        ::-webkit-scrollbar { width: 8px; }
        ::-webkit-scrollbar-track { background: #0b0f19; }
        ::-webkit-scrollbar-thumb { background: #1f2937; border-radius: 4px; }
        ::-webkit-scrollbar-thumb:hover { background: #374151; }
    </style>
</head>
<body class="bg-brand-dark text-slate-100 min-h-screen selection:bg-brand-500 selection:text-white">

    <!-- Toast Notification -->
    <div id="toast" class="fixed bottom-5 right-5 z-50 transform translate-y-20 opacity-0 transition-all duration-300 pointer-events-none">
        <div class="glass px-5 py-4 rounded-xl flex items-center gap-3 border-l-4 border-brand-emerald shadow-2xl">
            <i data-lucide="check-circle" class="w-6 h-6 text-brand-emerald"></i>
            <div>
                <p id="toast-title" class="font-semibold text-sm text-white">Muvaffaqiyatli!</p>
                <p id="toast-desc" class="text-xs text-slate-400">Amaliyot bajarildi.</p>
            </div>
        </div>
    </div>

    <!-- Header Navigation -->
    <header class="sticky top-0 z-40 glass border-b border-slate-800/60">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
            <!-- Logo -->
            <a href="#" class="flex items-center gap-3 group">
                <div class="w-10 h-10 rounded-xl bg-gradient-to-tr from-brand-500 to-brand-accent flex items-center justify-center font-bold text-xl text-white shadow-lg group-hover:scale-105 transition-transform">
                    E
                </div>
                <span class="text-2xl font-extrabold tracking-tight">EDU<span class="text-brand-500">.Pro</span></span>
            </a>

            <!-- Desktop Navigation -->
            <nav class="hidden md:flex items-center gap-8 text-sm font-medium text-slate-300">
                <a href="#courses" class="hover:text-brand-500 transition-colors">Kurslar</a>
                <a href="#currency" class="hover:text-brand-500 transition-colors flex items-center gap-1.5">
                    <span class="relative flex h-2 w-2">
                      <span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-brand-emerald opacity-75"></span>
                      <span class="relative inline-flex rounded-full h-2 w-2 bg-brand-


                      
