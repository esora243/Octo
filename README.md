<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Octo Energy (オクトエナジー) - あなたの太陽光発電収益を最大化</title>
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Google Fonts: Noto Sans JP for better Japanese readability -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@400;500;700&display=swap" rel="stylesheet">
    
    <!-- Custom Styles for Readability -->
    <style>
        body {
            font-family: 'Noto Sans JP', sans-serif;
            background-color: #f8fafc; /* 明るい背景色に変更 */
            color: #1e293b; /* ダークグレーのテキスト色で見やすく */
        }
        /* スムーズスクロール */
        html {
            scroll-behavior: smooth;
        }
        /* グラデーションテキスト */
        .gradient-text {
            background: linear-gradient(to right, #0d9488, #0ea5e9); /* 少し落ち着いた色合いに */
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        /* 全体の行間と文字サイズを調整 */
        section {
            padding-top: 5rem;
            padding-bottom: 5rem;
        }
        h1 {
            font-size: 2.5rem; /* 40px */
            line-height: 1.3;
        }
        h2 {
            font-size: 2rem; /* 32px */
            line-height: 1.4;
        }
        p, li {
            font-size: 1.125rem; /* 18px */
            line-height: 1.8;
            color: #475569;
        }
        @media (min-width: 768px) {
            h1 {
                font-size: 3.75rem; /* 60px */
            }
            h2 {
                font-size: 2.5rem; /* 40px */
            }
        }
    </style>
</head>
<body class="antialiased">

    <!-- Header -->
    <header class="bg-white/80 backdrop-blur-sm sticky top-0 z-50 border-b border-gray-200">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#" class="text-2xl font-bold gradient-text flex items-center">
                <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="mr-2 text-teal-600"><path d="M12 2.69l5.66 5.66a8 8 0 1 1-11.31 0z"></path></svg>
                Octo Energy
            </a>
            <nav class="hidden md:flex space-x-6 items-center text-gray-600 font-medium">
                <a href="#problem" class="hover:text-sky-600 transition-colors">卒FITの悩み</a>
                <a href="#solution" class="hover:text-sky-600 transition-colors">私たちの解決策</a>
                <a href="#features" class="hover:text-sky-600 transition-colors">主な機能</a>
                <a href="#pricing" class="hover:text-sky-600 transition-colors">料金プラン</a>
                <a href="#contact" class="bg-sky-500 hover:bg-sky-600 text-white font-bold py-2 px-5 rounded-lg transition-all transform hover:scale-105">
                    無料相談はこちら
                </a>
            </nav>
            <button id="mobile-menu-button" class="md:hidden text-gray-700 focus:outline-none">
                <svg class="w-7 h-7" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path></svg>
            </button>
        </div>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-white border-t border-gray-200">
            <a href="#problem" class="block py-3 px-6 text-gray-700 hover:bg-gray-50">卒FITの悩み</a>
            <a href="#solution" class="block py-3 px-6 text-gray-700 hover:bg-gray-50">私たちの解決策</a>
            <a href="#features" class="block py-3 px-6 text-gray-700 hover:bg-gray-50">主な機能</a>
            <a href="#pricing" class="block py-3 px-6 text-gray-700 hover:bg-gray-50">料金プラン</a>
            <a href="#contact" class="block py-3 px-6 text-gray-700 hover:bg-gray-50">無料相談はこちら</a>
        </div>
    </header>

    <!-- Main Content -->
    <main>
        <!-- Hero Section -->
        <section class="text-center px-6">
            <div class="container mx-auto">
                <div class="bg-teal-50 border border-teal-200 text-teal-800 rounded-full px-4 py-1.5 inline-block mb-6 font-medium">
                    <span class="font-bold">九州・山口県</span>にお住まいの太陽光オーナー様へ
                </div>
                <h1 class="font-bold text-gray-800 mb-6">
                    太陽光の売電収入、<br class="md:hidden">
                    <span class="gradient-text">もっと増やせる</span>って<br>知ってましたか？
                </h1>
                <p class="max-w-3xl mx-auto mb-10">
                    「卒FIT」で売電価格が下がってしまった…、どの電力会社がお得かわからない…。<br>
                    そんなあなたの悩みを、オクトエナジーのAIが解決。面倒なことは全部お任せで、売電収益を最大化します。
                </p>
                <a href="#pricing" class="bg-gradient-to-r from-teal-500 to-sky-500 hover:from-teal-600 hover:to-sky-600 text-white font-bold py-4 px-10 rounded-lg text-xl transition-all transform hover:scale-105 inline-block shadow-lg hover:shadow-xl">
                    料金プランと無料トライアルを見る
                </a>
            </div>
        </section>

        <!-- Problem Section -->
        <section id="problem" class="bg-white">
            <div class="container mx-auto px-6">
                <div class="text-center mb-16">
                    <h2 class="font-bold text-gray-800 mb-4">「卒FIT」後の、こんな<span class="text-amber-500">悩み</span>ありませんか？</h2>
                    <p class="max-w-2xl mx-auto">多くの方が、情報不足や手続きの複雑さに直面しています。</p>
                </div>
                <div class="grid md:grid-cols-2 gap-10 text-left">
                    <div class="bg-white p-8 rounded-2xl border-2 border-red-100 shadow-sm">
                        <h3 class="text-2xl font-bold mb-4 flex items-start">
                            <span class="text-red-500 mr-4 mt-1">📉</span>
                            <div>
                                売電価格が<br>ガクッと下がった…
                            </div>
                        </h3>
                        <p>FIT期間中の買取価格は10年間だけの保証。その後は何もしないと、買電価格の半分以下になってしまうことも。せっかくの太陽光発電がもったいない状態です。</p>
                    </div>
                    <div class="bg-white p-8 rounded-2xl border-2 border-blue-100 shadow-sm">
                        <h3 class="text-2xl font-bold mb-4 flex items-start">
                            <span class="text-blue-500 mr-4 mt-1">🤯</span>
                            <div>
                                どの新電力が一番お得か<br>調べきれない…
                            </div>
                        </h3>
                        <p>たくさんの新電力が参入し、プランも複雑。自分の発電量に合った一番有利な会社を、無数の中から自力で探し出すのは、時間も手間もかかりすぎます。</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Solution Section -->
        <section id="solution" class="bg-teal-50">
            <div class="container mx-auto px-6">
                <div class="text-center mb-12">
                    <h2 class="font-bold text-gray-800 mb-4">
                        その悩み、<span class="gradient-text">オクトエナジー</span>が<br class="md:hidden">すべて解決します！
                    </h2>
                    <p class="max-w-3xl mx-auto">
                        私たちが開発したAI搭載の「オクトソーラーシステム（特許申請中）」が、<br>
                        あなたに代わって、24時間365日、一番高く売れる電力会社を探し続けます。
                    </p>
                </div>
                <div class="relative max-w-4xl mx-auto">
                    <!-- 
                        ■■■ 画像の差し替えについて ■■■
                        以下の `src` の部分を、お客様がお持ちの画像のURL、またはファイル名に書き換えてください。
                        例： src="https://example.com/your-image.png"
                    -->
                    <img src="https://placehold.co/1200x750/e0f2f1/0d9488?text=AI搭載ダッシュボードの画面イメージ" 
                         alt="AIが最適な売電先を提案するダッシュボード画面"
                         class="rounded-2xl shadow-2xl w-full border-4 border-white">
                </div>
            </div>
        </section>

        <!-- Features Section -->
        <section id="features" class="bg-white">
            <div class="container mx-auto px-6">
                <div class="text-center mb-16">
                    <h2 class="font-bold text-gray-800 mb-4">主な機能</h2>
                    <p class="max-w-2xl mx-auto">面倒なことはAIにお任せ。あなたはスマホで結果を確認するだけ。</p>
                </div>
                <div class="grid md:grid-cols-3 gap-8">
                    <div class="text-center">
                        <div class="bg-green-100 text-green-600 rounded-full w-20 h-20 flex items-center justify-center mx-auto mb-6 shadow-md">
                            <svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M3 3v18h18"></path><path d="M18.7 8a6 6 0 0 0-8.3-5.3"></path><path d="M13 12.5a4.5 4.5 0 0 1 5-5.5"></path></svg>
                        </div>
                        <h3 class="text-xl font-bold mb-2">① 発電状況の見える化</h3>
                        <p class="text-left">今日の発電量や売電額がスマホで一目瞭然。どれだけ家計に貢献しているか、毎日チェックするのが楽しくなります。</p>
                    </div>
                    <div class="text-center">
                        <div class="bg-sky-100 text-sky-600 rounded-full w-20 h-20 flex items-center justify-center mx-auto mb-6 shadow-md">
                            <svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 2v20M17 5H9.5a3.5 3.5 0 0 0 0 7h5a3.5 3.5 0 0 1 0 7H6"></path></svg>
                        </div>
                        <h3 class="text-xl font-bold mb-2">② AIによる収益最大化</h3>
                        <p class="text-left">AIがあなたの発電パターンを学習し、九州・山口エリアの電力会社の中から、常に一番高く買ってくれる会社を自動で推奨します。</p>
                    </div>
                    <div class="text-center">
                        <div class="bg-indigo-100 text-indigo-600 rounded-full w-20 h-20 flex items-center justify-center mx-auto mb-6 shadow-md">
                            <svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M20 7h-9"></path><path d="M14 17H5"></path><circle cx="17" cy="17" r="3"></circle><circle cx="7" cy="7" r="3"></circle></svg>
                        </div>
                        <h3 class="text-xl font-bold mb-2">③ 面倒な手続きの簡素化</h3>
                        <p class="text-left">推奨された電力会社への切り替えも、アプリ上から簡単操作。書類のやり取りなど、面倒な手続きの手間を大幅に削減します。</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Pricing Section -->
        <section id="pricing" class="bg-gray-50">
            <div class="container mx-auto px-6 text-center">
                <h2 class="font-bold text-gray-800 mb-4">料金プラン</h2>
                <p class="mb-12 max-w-2xl mx-auto">あなたのニーズに合わせた3つのプランをご用意しました。</p>
                <div class="grid lg:grid-cols-3 gap-8 max-w-5xl mx-auto items-stretch">
                    <!-- Basic Plan -->
                    <div class="bg-white rounded-2xl p-8 border border-gray-200 flex flex-col shadow-lg">
                        <h3 class="text-2xl font-bold mb-2">ベーシック</h3>
                        <p class="text-gray-500 mb-6 flex-grow">まずは気軽に始めたい方へ</p>
                        <p class="text-5xl font-bold my-4">¥0<span class="text-lg font-normal text-gray-500"> / 月</span></p>
                        <ul class="text-left space-y-4 my-8">
                            <li class="flex items-center"><svg class="w-6 h-6 text-green-500 mr-3 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>リアルタイムモニタリング</li>
                            <li class="flex items-center text-gray-400"><svg class="w-6 h-6 text-gray-300 mr-3 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path></svg>収益レポート</li>
                            <li class="flex items-center text-gray-400"><svg class="w-6 h-6 text-gray-300 mr-3 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path></svg>最適売電先レコメンデーション</li>
                        </ul>
                        <a href="#contact" class="w-full mt-auto bg-gray-200 hover:bg-gray-300 text-gray-700 font-bold py-3 px-8 rounded-lg transition-colors">
                            無料で始める
                        </a>
                    </div>
                    <!-- Standard Plan (Most Popular) -->
                    <div class="bg-white rounded-2xl p-8 border-2 border-teal-500 shadow-2xl relative flex flex-col transform scale-105">
                        <div class="absolute top-0 left-1/2 -translate-x-1/2 -translate-y-1/2 bg-teal-500 text-white text-sm font-bold px-4 py-1.5 rounded-full">一番人気</div>
                        <h3 class="text-2xl font-bold mb-2 text-teal-600">スタンダード</h3>
                        <p class="text-gray-500 mb-6 flex-grow">収益を最大化したい方へ</p>
                        <p class="text-5xl font-bold my-4">¥980<span class="text-lg font-normal text-gray-500"> / 月</span></p>
                        <ul class="text-left space-y-4 my-8">
                            <li class="flex items-center"><svg class="w-6 h-6 text-green-500 mr-3 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>リアルタイムモニタリング</li>
                            <li class="flex items-center"><svg class="w-6 h-6 text-green-500 mr-3 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>収益レポート</li>
                            <li class="flex items-center"><svg class="w-6 h-6 text-green-500 mr-3 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>最適売電先レコメンデーション</li>
                            <li class="flex items-center"><svg class="w-6 h-6 text-green-500 mr-3 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>切り替えサポート</li>
                        </ul>
                        <a href="#contact" class="w-full mt-auto bg-gradient-to-r from-teal-500 to-sky-500 hover:from-teal-600 hover:to-sky-600 text-white font-bold py-3 px-8 rounded-lg transition-transform transform hover:scale-105">
                            30日間無料トライアル
                        </a>
                    </div>
                    <!-- Pro Plan -->
                    <div class="bg-white rounded-2xl p-8 border border-gray-200 flex flex-col shadow-lg">
                        <h3 class="text-2xl font-bold mb-2">プロ</h3>
                        <p class="text-gray-500 mb-6 flex-grow">蓄電池やEVをお持ちの方へ</p>
                        <p class="text-5xl font-bold my-4">¥2,980<span class="text-lg font-normal text-gray-500"> / 月</span></p>
                        <ul class="text-left space-y-4 my-8">
                            <li class="flex items-center"><svg class="w-6 h-6 text-green-500 mr-3 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>スタンダードプランの全機能</li>
                            <li class="flex items-center"><svg class="w-6 h-6 text-green-500 mr-3 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>蓄電池・EV連携最適化</li>
                            <li class="flex items-center text-gray-400"><svg class="w-6 h-6 text-gray-300 mr-3 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>VPP/DR対応（近日公開）</li>
                        </ul>
                        <a href="#contact" class="w-full mt-auto bg-gray-200 hover:bg-gray-300 text-gray-700 font-bold py-3 px-8 rounded-lg transition-colors">
                            お問い合わせ
                        </a>
                    </div>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="bg-white">
            <div class="container mx-auto px-6 text-center">
                <h2 class="font-bold text-gray-800 mb-4">まずはお気軽にご相談ください</h2>
                <p class="mb-8 max-w-2xl mx-auto">あなたの家の太陽光で、あとどれくらい収益を増やせるか無料でシミュレーションいたします。<br>無理な勧誘は一切ありませんので、安心してお問い合わせください。</p>
                <div class="max-w-xl mx-auto bg-gray-50 border border-gray-200 rounded-2xl p-8">
                    <p class="mb-2 text-gray-600">お電話でのお問い合わせ</p>
                    <p class="text-3xl font-bold text-gray-800 mb-8">
                        <a href="tel:08052866815" class="hover:text-sky-600">080-5286-6815</a>
                    </p>
                    <p class="mb-4 text-gray-600">または、以下のフォームからご連絡ください</p>
                    <form>
                        <div class="mb-4">
                            <label for="name" class="sr-only">お名前</label>
                            <input type="text" id="name" placeholder="お名前" class="w-full bg-white border border-gray-300 rounded-lg py-3 px-4 focus:outline-none focus:ring-2 focus:ring-sky-500">
                        </div>
                        <div class="mb-4">
                            <label for="email" class="sr-only">メールアドレス</label>
                            <input type="email" id="email" placeholder="メールアドレス" class="w-full bg-white border border-gray-300 rounded-lg py-3 px-4 focus:outline-none focus:ring-2 focus:ring-sky-500">
                        </div>
                        <div class="mb-6">
                            <label for="message" class="sr-only">お問い合わせ内容</label>
                            <textarea id="message" rows="5" placeholder="ご相談内容（例：無料シミュレーション希望、など）" class="w-full bg-white border border-gray-300 rounded-lg py-3 px-4 focus:outline-none focus:ring-2 focus:ring-sky-500"></textarea>
                        </div>
                        <div class="text-center">
                            <button type="submit" class="bg-sky-500 hover:bg-sky-600 text-white font-bold py-3 px-12 rounded-lg transition-colors text-lg">
                                無料相談を申し込む
                            </button>
                        </div>
                    </form>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white">
        <div class="container mx-auto px-6 py-10">
            <div class="flex flex-col md:flex-row justify-between items-center text-center md:text-left">
                <div class="mb-6 md:mb-0">
                    <p class="text-xl font-bold">Octo Energy LLC</p>
                    <p class="text-sm text-gray-400 mt-2">代表社員 本田 奏人</p>
                    <p class="text-sm text-gray-400 mt-1">〒160-0023 東京都新宿区西新宿３丁目３−１３</p>
                    <p class="text-sm text-gray-400 mt-1">Tel: <a href="tel:08052866815" class="hover:text-white">080-5286-6815</a></p>
                </div>
                <div class="text-sm text-gray-300">
                    <a href="#" class="hover:text-white">プライバシーポリシー</a>
                    <span class="mx-2">|</span>
                    <a href="#" class="hover:text-white">利用規約</a>
                </div>
            </div>
            <div class="mt-8 border-t border-gray-700 pt-6 text-center text-gray-500 text-sm">
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
