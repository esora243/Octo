<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Octo Energy (オクトエナジー) - あなたの太陽光発電収益を最大化</title>
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Google Fonts: Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&family=Noto+Sans+JP:wght@400;500;700&display=swap" rel="stylesheet">
    
    <!-- Custom Styles -->
    <style>
        body {
            font-family: 'Inter', 'Noto Sans JP', sans-serif;
        }
        /* スムーズスクロール */
        html {
            scroll-behavior: smooth;
        }
        /* グラデーションテキスト */
        .gradient-text {
            background: linear-gradient(to right, #1dd1a1, #48dbfb);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
    </style>
</head>
<body class="bg-gray-900 text-white">

    <!-- Header -->
    <header class="bg-gray-900/80 backdrop-blur-sm sticky top-0 z-50">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#" class="text-2xl font-bold gradient-text">
                Octo Energy
            </a>
            <nav class="hidden md:flex space-x-8 items-center">
                <a href="#problem" class="hover:text-cyan-400 transition-colors">課題</a>
                <a href="#solution" class="hover:text-cyan-400 transition-colors">解決策</a>
                <a href="#features" class="hover:text-cyan-400 transition-colors">機能</a>
                <a href="#pricing" class="hover:text-cyan-400 transition-colors">料金</a>
                <a href="#contact" class="bg-cyan-500 hover:bg-cyan-600 text-white font-bold py-2 px-4 rounded-lg transition-transform transform hover:scale-105">
                    お問い合わせ
                </a>
            </nav>
            <button id="mobile-menu-button" class="md:hidden text-white focus:outline-none">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path></svg>
            </button>
        </div>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden">
            <a href="#problem" class="block py-2 px-6 text-sm hover:bg-gray-800">課題</a>
            <a href="#solution" class="block py-2 px-6 text-sm hover:bg-gray-800">解決策</a>
            <a href="#features" class="block py-2 px-6 text-sm hover:bg-gray-800">機能</a>
            <a href="#pricing" class="block py-2 px-6 text-sm hover:bg-gray-800">料金</a>
            <a href="#contact" class="block py-2 px-6 text-sm hover:bg-gray-800">お問い合わせ</a>
        </div>
    </header>

    <!-- Main Content -->
    <main>
        <!-- Hero Section -->
        <section class="relative text-center py-20 md:py-32 px-6 overflow-hidden">
            <!-- Background Glow -->
            <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-[40rem] h-[40rem] bg-cyan-500/10 rounded-full blur-3xl -z-10"></div>
            
            <h1 class="text-4xl md:text-6xl font-bold mb-4 leading-tight">
                眠っている太陽光の価値を<br class="md:hidden">
                <span class="gradient-text">最大限に</span>引き出す。
            </h1>
            <p class="text-lg md:text-xl text-gray-300 max-w-3xl mx-auto mb-8">
                オクトエナジーは、AIがあなたの太陽光発電の売電収益を最大化する「パーソナル・エネルギー・トレーディングプラットフォーム」。面倒な売電先選びから解放され、スマートなエネルギー運用を始めましょう。
            </p>
            <a href="#features" class="bg-gradient-to-r from-cyan-500 to-blue-500 hover:from-cyan-600 hover:to-blue-600 text-white font-bold py-3 px-8 rounded-lg text-lg transition-transform transform hover:scale-105 inline-block">
                今すぐ始める
            </a>
        </section>

        <!-- Problem Section -->
        <section id="problem" class="py-20 bg-gray-800/50">
            <div class="container mx-auto px-6 text-center">
                <h2 class="text-3xl md:text-4xl font-bold mb-4">こんな<span class="text-yellow-400">悩み</span>、ありませんか？</h2>
                <p class="text-gray-400 mb-12 max-w-2xl mx-auto">FIT制度終了（卒FIT）後、太陽光発電の運用はより複雑になっています。</p>
                <div class="grid md:grid-cols-2 gap-8 text-left">
                    <div class="bg-gray-800 p-8 rounded-xl border border-gray-700">
                        <h3 class="text-xl font-bold mb-2 flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-red-400 mr-3"><line x1="12" y1="19" x2="12" y2="5"></line><polyline points="5 12 12 5 19 12"></polyline></svg>
                            売電価格が大幅に下落した
                        </h3>
                        <p class="text-gray-400">FIT期間中のような高値での売電はもう終わり。何もしなければ、収益は大きく減少してしまいます。</p>
                    </div>
                    <div class="bg-gray-800 p-8 rounded-xl border border-gray-700">
                        <h3 class="text-xl font-bold mb-2 flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-blue-400 mr-3"><path d="M10.29 3.86L1.82 18a2 2 0 0 0 1.71 3h16.94a2 2 0 0 0 1.71-3L13.71 3.86a2 2 0 0 0-3.42 0z"></path><line x1="12" y1="9" x2="12" y2="13"></line><line x1="12" y1="17" x2="12.01" y2="17"></line></svg>
                            どの電力会社を選べば良いかわからない
                        </h3>
                        <p class="text-gray-400">無数の新電力が様々なプランを提供しており、最適な選択肢を個人で見つけるのは至難の業です。</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Solution Section -->
        <section id="solution" class="py-20">
            <div class="container mx-auto px-6">
                <div class="text-center mb-12">
                    <h2 class="text-3xl md:text-4xl font-bold mb-4">
                        その悩み、<span class="gradient-text">Octo Energy</span>が解決します
                    </h2>
                    <p class="text-gray-300 max-w-3xl mx-auto">
                        私たちは、複雑なエネルギー市場の情報をシンプルに変換し、あなたの利益を最大化するインテリジェントなシステムを提供します。
                    </p>
                </div>
                <div class="relative max-w-4xl mx-auto">
                    <div class="absolute w-full h-full bg-cyan-500/10 rounded-3xl blur-2xl -z-10 transform -rotate-3"></div>
                    <img src="https://placehold.co/1200x675/1a202c/48dbfb?text=ダッシュボード画面のイメージ" 
                         alt="ダッシュボード画面のイメージ"
                         class="rounded-2xl shadow-2xl shadow-cyan-500/20 w-full"
                         onerror="this.onerror=null;this.src='https://placehold.co/1200x675/1a202c/48dbfb?text=Image+Not+Found';">
                </div>
            </div>
        </section>

        <!-- Features Section -->
        <section id="features" class="py-20 bg-gray-900">
            <div class="container mx-auto px-6">
                <div class="text-center mb-12">
                    <h2 class="text-3xl md:text-4xl font-bold mb-4">主な機能</h2>
                    <p class="text-gray-400 max-w-2xl mx-auto">専門知識は不要。3つのステップで、あなたのエネルギー資産運用を最適化します。</p>
                </div>
                <div class="grid md:grid-cols-3 gap-8">
                    <!-- Feature 1: Visualize -->
                    <div class="bg-gray-800 p-8 rounded-xl border border-gray-700 transform hover:-translate-y-2 transition-transform">
                        <div class="bg-green-500/10 text-green-400 rounded-lg w-12 h-12 flex items-center justify-center mb-4">
                            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21.21 15.89A10 10 0 1 1 8 2.83"></path><path d="M22 12A10 10 0 0 0 12 2v10z"></path></svg>
                        </div>
                        <h3 class="text-xl font-bold mb-2">① 可視化・分析</h3>
                        <p class="text-gray-400">発電量や売電収益をリアルタイムで直感的に把握。漠然とした不安を解消し、資産状況を正確に把握できます。</p>
                    </div>
                    <!-- Feature 2: Maximize -->
                    <div class="bg-gray-800 p-8 rounded-xl border border-gray-700 transform hover:-translate-y-2 transition-transform">
                        <div class="bg-cyan-500/10 text-cyan-400 rounded-lg w-12 h-12 flex items-center justify-center mb-4">
                            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="12" y1="19" x2="12" y2="5"></line><polyline points="5 12 12 5 19 12"></polyline></svg>
                        </div>
                        <h3 class="text-xl font-bold mb-2">② 収益最大化</h3>
                        <p class="text-gray-400">AIが全国の電力会社のプランを比較分析し、あなたに最適な売電先を自動で推奨。機会損失を防ぎます。</p>
                    </div>
                    <!-- Feature 3: Automate -->
                    <div class="bg-gray-800 p-8 rounded-xl border border-gray-700 transform hover:-translate-y-2 transition-transform">
                        <div class="bg-purple-500/10 text-purple-400 rounded-lg w-12 h-12 flex items-center justify-center mb-4">
                            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 6L7 17l-5-5"></path><path d="M22 10L12 20l-5-5"></path></svg>
                        </div>
                        <h3 class="text-xl font-bold mb-2">③ 自動化・効率化</h3>
                        <p class="text-gray-400">面倒な電力会社の切り替え手続きもシステムがサポート。時間と手間を大幅に削減します。</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Pricing Section -->
        <section id="pricing" class="py-20">
            <div class="container mx-auto px-6 text-center">
                <h2 class="text-3xl md:text-4xl font-bold mb-4">料金プラン</h2>
                <p class="text-gray-400 mb-12 max-w-2xl mx-auto">シンプルな料金体系で、どなたでも安心してご利用いただけます。</p>
                <div class="max-w-md mx-auto bg-gray-800 rounded-2xl p-8 border border-cyan-500/50 shadow-lg shadow-cyan-500/10">
                    <h3 class="text-2xl font-bold mb-2">スタンダードプラン</h3>
                    <p class="text-gray-400 mb-6">全ての基本機能をご利用いただけます</p>
                    <p class="text-5xl font-bold mb-2">¥980<span class="text-lg font-normal text-gray-400"> / 月</span></p>
                    <p class="text-gray-500 mb-8">(税抜)</p>
                    <ul class="text-left space-y-3 mb-8">
                        <li class="flex items-center"><svg class="w-5 h-5 text-green-400 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>リアルタイムモニタリング</li>
                        <li class="flex items-center"><svg class="w-5 h-5 text-green-400 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>収益レポート</li>
                        <li class="flex items-center"><svg class="w-5 h-5 text-green-400 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>最適売電先レコメンデーション</li>
                        <li class="flex items-center"><svg class="w-5 h-5 text-green-400 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>切り替えサポート</li>
                    </ul>
                    <a href="#contact" class="w-full bg-gradient-to-r from-cyan-500 to-blue-500 hover:from-cyan-600 hover:to-blue-600 text-white font-bold py-3 px-8 rounded-lg text-lg transition-transform transform hover:scale-105 inline-block">
                        30日間無料トライアル
                    </a>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="py-20 bg-gray-800/50">
            <div class="container mx-auto px-6 text-center">
                <h2 class="text-3xl md:text-4xl font-bold mb-4">お問い合わせ</h2>
                <p class="text-gray-400 mb-8 max-w-2xl mx-auto">ご質問やご相談、サービス導入に関するお問い合わせはこちらから。</p>
                <div class="max-w-lg mx-auto text-left">
                    <form>
                        <div class="mb-4">
                            <label for="name" class="block text-gray-300 mb-2">お名前</label>
                            <input type="text" id="name" class="w-full bg-gray-700 border border-gray-600 rounded-lg py-2 px-4 focus:outline-none focus:ring-2 focus:ring-cyan-500">
                        </div>
                        <div class="mb-4">
                            <label for="email" class="block text-gray-300 mb-2">メールアドレス</label>
                            <input type="email" id="email" class="w-full bg-gray-700 border border-gray-600 rounded-lg py-2 px-4 focus:outline-none focus:ring-2 focus:ring-cyan-500">
                        </div>
                        <div class="mb-6">
                            <label for="message" class="block text-gray-300 mb-2">お問い合わせ内容</label>
                            <textarea id="message" rows="5" class="w-full bg-gray-700 border border-gray-600 rounded-lg py-2 px-4 focus:outline-none focus:ring-2 focus:ring-cyan-500"></textarea>
                        </div>
                        <div class="text-center">
                            <button type="submit" class="bg-cyan-500 hover:bg-cyan-600 text-white font-bold py-3 px-12 rounded-lg transition-colors">
                                送信する
                            </button>
                        </div>
                    </form>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="bg-gray-900">
        <div class="container mx-auto px-6 py-8">
            <div class="flex flex-col md:flex-row justify-between items-center">
                <div class="mb-4 md:mb-0">
                    <a href="#" class="text-xl font-bold gradient-text">Octo Energy LLC</a>
                    <p class="text-sm text-gray-500 mt-1">〒160-0023 東京都新宿区西新宿３丁目３−１３</p>
                </div>
                <div class="text-sm text-gray-400">
                    <a href="#" class="hover:text-white">プライバシーポリシー</a>
                    <span class="mx-2">|</span>
                    <a href="#" class="hover:text-white">利用規約</a>
                </div>
            </div>
            <div class="mt-8 border-t border-gray-800 pt-6 text-center text-gray-500 text-sm">
                &copy; 2024 Octo Energy LLC. All Rights Reserved.
            </div>
        </div>
    </footer>

    <script>
        // Mobile Menu Toggle
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');
        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Close mobile menu when a link is clicked
        const mobileMenuLinks = document.querySelectorAll('#mobile-menu a');
        mobileMenuLinks.forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        });
    </script>

</body>
</html>
