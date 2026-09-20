<!DOCTYPE html>
<html lang="bn" class="h-full bg-slate-50">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RTG MCQ Test Web - Online Exam Platform</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Hind+Siliguri:wght@300;400;500;600;700&family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <!-- FontAwesome Icons CDN -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            50: '#f0fdf4',
                            100: '#dcfce7',
                            500: '#22c55e',
                            600: '#16a34a',
                            700: '#15803d',
                            800: '#166534',
                            900: '#14532d',
                        },
                        navy: {
                            800: '#1e293b',
                            900: '#0f172a',
                        }
                    },
                    fontFamily: {
                        sans: ['Hind Siliguri', 'Inter', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <style>
        body { font-family: 'Hind Siliguri', 'Inter', sans-serif; }
        .glass-card {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
        }
        ::-webkit-scrollbar {
            width: 6px;
            height: 6px;
        }
        ::-webkit-scrollbar-track {
            background: #f1f5f9;
        }
        ::-webkit-scrollbar-thumb {
            background: #cbd5e1;
            border-radius: 4px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #94a3b8;
        }
    </style>
</head>
<body class="h-full flex flex-col text-slate-800 bg-slate-50 selection:bg-brand-500 selection:text-white">

    <!-- Header Navigation -->
    <header id="mainHeader" class="bg-slate-900 text-white shadow-md sticky top-0 z-40 transition-all duration-300 hidden">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-16 flex items-center justify-between">
            <div class="flex items-center space-x-3 space-x-reverse cursor-pointer" onclick="navigateTo('category')">
                <div class="w-10 h-10 rounded-xl bg-gradient-to-tr from-brand-600 to-emerald-400 flex items-center justify-center text-white font-bold text-xl shadow-lg shadow-brand-500/30">
                    RTG
                </div>
                <div>
                    <span class="text-xl font-bold tracking-tight text-white block leading-none">RTG MCQ Test</span>
                    <span class="text-xs text-brand-400 font-medium tracking-wide">Online Knowledge Hub</span>
                </div>
            </div>

            <div class="flex items-center space-x-3 sm:space-x-4">
                <button id="langToggleBtn" onclick="toggleLanguage()" class="px-3 py-1.5 rounded-lg border border-slate-700 bg-slate-800 hover:bg-slate-700 text-xs font-semibold text-slate-200 transition">
                    <i class="fa-solid font-bold text-brand-400 fa-globe mr-1"></i> <span id="langText">English</span>
                </button>

                <div id="userProfileBadge" class="hidden flex items-center space-x-2 border-l border-slate-700 pl-3">
                    <div class="w-8 h-8 rounded-full bg-brand-600 text-white font-bold flex items-center justify-center text-sm" id="userAvatar">
                        U
                    </div>
                    <div class="hidden md:block text-left">
                        <div class="text-xs font-semibold text-white" id="userNameDisplay">User Name</div>
                        <div class="text-[10px] text-slate-400" id="userPhoneDisplay">01700000000</div>
                    </div>
                    <button onclick="logout()" class="p-2 text-slate-400 hover:text-red-400 transition" title="Logout">
                        <i class="fa-solid fa-right-from-bracket"></i>
                    </button>
                </div>
            </div>
        </div>
    </header>

    <!-- Main Container -->
    <main class="flex-grow flex items-center justify-center p-3 sm:p-6 md:p-8">

        <!-- AUTH PAGE -->
        <section id="authPage" class="w-full max-w-md my-auto">
            <div class="bg-white rounded-2xl shadow-xl border border-slate-100 overflow-hidden transition-all duration-300">
                <div class="bg-gradient-to-r from-slate-900 via-slate-800 to-slate-900 p-6 text-center text-white relative">
                    <div class="inline-flex items-center justify-center w-14 h-14 rounded-2xl bg-brand-600 text-white font-bold text-2xl shadow-lg mb-3">
                        RTG
                    </div>
                    <h2 id="authHeading" class="text-2xl font-bold">লগইন করুন</h2>
                    <p id="authSubheading" class="text-xs text-slate-300 mt-1">RTG অনলাইন মডেল টেস্ট প্ল্যাটফর্মে আপনাকে স্বাগতম</p>
                    
                    <div class="grid grid-cols-2 mt-6 bg-slate-800/80 p-1 rounded-xl text-sm font-semibold border border-slate-700">
                        <button id="loginTabBtn" onclick="switchAuthTab('login')" class="py-2 rounded-lg bg-brand-600 text-white transition shadow">
                            <span data-key="login">লগইন</span>
                        </button>
                        <button id="signupTabBtn" onclick="switchAuthTab('signup')" class="py-2 rounded-lg text-slate-300 hover:text-white transition">
                            <span data-key="signup">রেজিস্টার</span>
                        </button>
                    </div>
                </div>

                <div class="p-6">
                    <form id="authForm" onsubmit="handleAuthSubmit(event)">
                        <div id="nameGroup" class="mb-4 hidden">
                            <label class="block text-xs font-bold text-slate-700 uppercase tracking-wider mb-1" data-key="fullName">পূর্ণ নাম</label>
                            <div class="relative">
                                <span class="absolute inset-y-0 left-0 pl-3 flex items-center text-slate-400"><i class="fa-regular fa-user"></i></span>
                                <input type="text" id="authName" class="w-full pl-10 pr-4 py-2.5 rounded-xl border border-slate-200 focus:border-brand-500 focus:ring-2 focus:ring-brand-500/20 text-sm outline-none transition" placeholder="আব্দুর রহমান">
                            </div>
                        </div>

                        <div class="mb-4">
                            <label class="block text-xs font-bold text-slate-700 uppercase tracking-wider mb-1" data-key="phone">মোবাইল নম্বর</label>
                            <div class="relative">
                                <span class="absolute inset-y-0 left-0 pl-3 flex items-center text-slate-400"><i class="fa-solid fa-phone"></i></span>
                                <input type="tel" id="authPhone" required class="w-full pl-10 pr-4 py-2.5 rounded-xl border border-slate-200 focus:border-brand-500 focus:ring-2 focus:ring-brand-500/20 text-sm outline-none transition" placeholder="017XXXXXXXX">
                            </div>
                        </div>

                        <div id="emailGroup" class="mb-4 hidden">
                            <label class="block text-xs font-bold text-slate-700 uppercase tracking-wider mb-1" data-key="email">ইমেইল ঠিকানা (ঐচ্ছিক)</label>
                            <div class="relative">
                                <span class="absolute inset-y-0 left-0 pl-3 flex items-center text-slate-400"><i class="fa-regular fa-envelope"></i></span>
                                <input type="email" id="authEmail" class="w-full pl-10 pr-4 py-2.5 rounded-xl border border-slate-200 focus:border-brand-500 focus:ring-2 focus:ring-brand-500/20 text-sm outline-none transition" placeholder="example@mail.com">
                            </div>
                        </div>

                        <div class="mb-4">
                            <label class="block text-xs font-bold text-slate-700 uppercase tracking-wider mb-1" data-key="password">পাসওয়ার্ড</label>
                            <div class="relative">
                                <span class="absolute inset-y-0 left-0 pl-3 flex items-center text-slate-400"><i class="fa-solid fa-lock"></i></span>
                                <input type="password" id="authPassword" required class="w-full pl-10 pr-4 py-2.5 rounded-xl border border-slate-200 focus:border-brand-500 focus:ring-2 focus:ring-brand-500/20 text-sm outline-none transition" placeholder="••••••••">
                            </div>
                        </div>

                        <div id="confirmPasswordGroup" class="mb-4 hidden">
                            <label class="block text-xs font-bold text-slate-700 uppercase tracking-wider mb-1" data-key="confirmPassword">পাসওয়ার্ড নিশ্চিত করুন</label>
                            <div class="relative">
                                <span class="absolute inset-y-0 left-0 pl-3 flex items-center text-slate-400"><i class="fa-solid fa-shield-halved"></i></span>
                                <input type="password" id="authConfirmPassword" class="w-full pl-10 pr-4 py-2.5 rounded-xl border border-slate-200 focus:border-brand-500 focus:ring-2 focus:ring-brand-500/20 text-sm outline-none transition" placeholder="••••••••">
                            </div>
                        </div>

                        <div id="rememberRow" class="flex items-center justify-between mb-6 text-xs">
                            <label class="flex items-center space-x-2 space-x-reverse cursor-pointer">
                                <input type="checkbox" id="rememberMe" class="rounded border-slate-300 text-brand-600 focus:ring-brand-500 w-4 h-4">
                                <span class="text-slate-600 font-medium" data-key="rememberMe">মনে রাখুন</span>
                            </label>
                            <a href="#" onclick="showNotice('পাসওয়ার্ড রিসেট করতে অ্যাডমিনের সাথে যোগাযোগ করুন।'); return false;" class="text-brand-600 hover:underline font-semibold" data-key="forgotPassword">পাসওয়ার্ড ভুলে গেছেন?</a>
                        </div>

                        <button type="submit" id="authSubmitBtn" class="w-full py-3 bg-brand-600 hover:bg-brand-700 text-white font-bold rounded-xl shadow-lg shadow-brand-600/30 transition transform active:scale-95 flex items-center justify-center space-x-2">
                            <span id="authBtnText" data-key="loginBtn">লগইন করুন</span>
                            <i class="fa-solid fa-arrow-right text-sm"></i>
                        </button>
                    </form>
                </div>
            </div>
        </section>

        <!-- CATEGORY PAGE -->
        <section id="categoryPage" class="w-full max-w-6xl hidden">
            <div class="mb-8 text-center sm:text-left flex flex-col sm:flex-row justify-between items-center gap-4">
                <div>
                    <h1 class="text-2xl sm:text-3xl font-extrabold text-slate-900 tracking-tight" data-key="selectCategory">শ্রেণী / ক্যাটাগরি নির্বাচন করুন</h1>
                    <p class="text-sm text-slate-500 mt-1" data-key="selectCategorySub">আপনার পরীক্ষার কোর্স বা শ্রেণী অনুযায়ী সঠিক বিভাগ পছন্দ করুন</p>
                </div>
                <div class="inline-flex items-center gap-2 bg-brand-50 border border-brand-200 px-4 py-2 rounded-xl text-brand-700 font-semibold text-xs">
                    <i class="fa-solid fa-lightbulb text-amber-500 text-sm"></i>
                    <span data-key="aiPoweredNotice">Gemini AI দ্বারা স্বয়ংক্রিয় প্রশ্ন জেনারেটর যুক্ত</span>
                </div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-4 sm:gap-5" id="categoryGrid"></div>
        </section>

        <!-- PARAMS PAGE -->
        <section id="paramsPage" class="w-full max-w-2xl hidden">
            <div class="bg-white rounded-2xl shadow-xl border border-slate-100 overflow-hidden">
                <div class="p-6 bg-gradient-to-r from-slate-900 to-slate-800 text-white flex items-center justify-between">
                    <div>
                        <span class="text-xs uppercase font-bold text-brand-400 tracking-wider" id="selectedCategoryBadge">ক্যাটাগরি</span>
                        <h2 class="text-xl font-bold mt-0.5" id="selectedCategoryTitle">শ্রেণী নাম</h2>
                    </div>
                    <button onclick="navigateTo('category')" class="px-3 py-1.5 rounded-lg bg-slate-700 hover:bg-slate-600 text-xs font-semibold text-slate-200 transition">
                        <i class="fa-solid fa-arrow-left mr-1"></i> <span data-key="changeCategory">পরিবর্তন</span>
                    </button>
                </div>

                <div class="p-6 sm:p-8 space-y-6">
                    <div>
                        <label class="block text-xs font-bold text-slate-700 uppercase tracking-wider mb-2" data-key="selectSubject">বিষয় বা টপিক (ঐচ্ছিক)</label>
                        <select id="subjectSelect" class="w-full p-3 rounded-xl border border-slate-200 focus:border-brand-500 focus:ring-2 focus:ring-brand-500/20 text-sm outline-none font-medium text-slate-700 bg-white">
                            <option value="General">সকল বিষয় সমন্বিত (General Knowledge & Core Subjects)</option>
                            <option value="Science">বিজ্ঞান ও তথ্যপ্রযুক্তি (Science & ICT)</option>
                            <option value="Mathematics">গণিত ও সাধারণ বুদ্ধিমত্তা (Mathematics)</option>
                            <option value="Bangla">বাংলা ভাষা ও সাহিত্য (Bangla)</option>
                            <option value="English">ইংরেজি ব্যাকরণ (English Grammar)</option>
                        </select>
                    </div>

                    <!-- Gemini API Key Input Field -->
                    <div>
                        <label class="block text-xs font-bold text-slate-700 uppercase tracking-wider mb-2">
                            Gemini API Key (ঐচ্ছিক)
                        </label>
                        <input type="password" id="geminiApiKey" class="w-full p-3 rounded-xl border border-slate-200 focus:border-brand-500 focus:ring-2 focus:ring-brand-500/20 text-sm outline-none font-medium text-slate-700 bg-white" placeholder="আপনার Gemini API Key লিখুন (ফাঁকা রাখলে বিল্ট-ইন কি ব্যবহার হবে)">
                        <p class="text-[11px] text-slate-400 mt-1">সরাসরি গুগল থেকে রিয়েল-টাইম ইউনিক প্রশ্ন তৈরি করতে API key দিতে পারেন।</p>
                    </div>

                    <div>
                        <label class="block text-xs font-bold text-slate-700 uppercase tracking-wider mb-2" data-key="questionCount">প্রশ্নের সংখ্যা নির্ধারণ করুন</label>
                        <div class="grid grid-cols-4 sm:grid-cols-4 gap-2.5" id="countGrid"></div>
                    </div>

                    <div class="bg-slate-50 border border-slate-200/80 rounded-xl p-4 flex items-center justify-between">
                        <div class="flex items-center space-x-3 space-x-reverse">
                            <div class="w-10 h-10 rounded-lg bg-amber-100 text-amber-600 flex items-center justify-center font-bold text-lg">
                                <i class="fa-solid fa-stopwatch"></i>
                            </div>
                            <div>
                                <span class="text-xs text-slate-500 font-semibold block" data-key="allocatedTime">বরাদ্দকৃত মোট সময়</span>
                                <span class="text-lg font-extrabold text-slate-800" id="calculatedTimeDisplay">১০ মিনিট</span>
                            </div>
                        </div>
                        <div class="text-right text-xs text-slate-500">
                            <span data-key="perQuestionSpeed">প্রতি প্রশ্নে বরাদ্দ</span><br>
                            <span class="font-bold text-slate-700" id="perQuestionTimeDisplay">৪৫ সেকেন্ড</span>
                        </div>
                    </div>

                    <div class="flex items-center justify-between border-t border-slate-100 pt-4">
                        <div>
                            <span class="text-sm font-bold text-slate-800 block" data-key="autoAdvance">স্বয়ংক্রিয় পরবর্তী প্রশ্ন (Auto-advance)</span>
                            <span class="text-xs text-slate-500" data-key="autoAdvanceSub">উত্তর নির্বাচন করলেই দ্রুত পরবর্তী প্রশ্নে চলে যাবে</span>
                        </div>
                        <label class="relative inline-flex items-center cursor-pointer">
                            <input type="checkbox" id="autoAdvanceToggle" checked class="sr-only peer">
                            <div class="w-11 h-6 bg-slate-200 peer-focus:outline-none rounded-full peer peer-checked:after:translate-x-full peer-checked:after:border-white after:content-[''] after:absolute after:top-[2px] after:left-[2px] after:bg-white after:border-slate-300 after:border after:rounded-full after:h-5 after:w-5 after:transition-all peer-checked:bg-brand-600"></div>
                        </label>
                    </div>

                    <button onclick="startExam()" class="w-full py-3.5 bg-brand-600 hover:bg-brand-700 text-white font-extrabold rounded-xl shadow-lg shadow-brand-600/30 transition transform active:scale-95 flex items-center justify-center space-x-2 text-base">
                        <i class="fa-solid fa-play"></i>
                        <span data-key="startExamBtn">পরীক্ষা শুরু করুন</span>
                    </button>
                </div>
            </div>
        </section>

        <!-- EXAM PAGE -->
        <section id="examPage" class="w-full max-w-4xl hidden">
            <div class="bg-white rounded-2xl shadow-md border border-slate-200/80 p-4 mb-6 sticky top-20 z-30 flex flex-wrap items-center justify-between gap-4">
                <div class="flex items-center space-x-3 space-x-reverse">
                    <span class="bg-slate-100 text-slate-700 text-xs font-bold px-3 py-1.5 rounded-lg border border-slate-200" id="examCategoryTag">
                        Class 10
                    </span>
                    <span class="text-xs font-semibold text-slate-500">
                        <span data-key="questionLabel">প্রশ্ন</span>: <strong id="currentQNum" class="text-slate-900 font-extrabold text-sm">1</strong>/<span id="totalQNum">10</span>
                    </span>
                </div>

                <div id="timerContainer" class="flex items-center space-x-2 px-4 py-1.5 rounded-xl bg-slate-900 text-white shadow font-mono font-bold text-base transition-colors">
                    <i class="fa-solid fa-clock text-amber-400 text-sm"></i>
                    <span id="timerDisplay">10:00</span>
                </div>

                <button onclick="confirmFinishExam()" class="px-4 py-1.5 bg-red-500 hover:bg-red-600 text-white font-bold text-xs rounded-xl shadow transition">
                    <i class="fa-solid fa-flag-checkered mr-1"></i> <span data-key="finishExam">পরীক্ষা শেষ করুন</span>
                </button>
            </div>

            <div class="w-full bg-slate-200 rounded-full h-2 mb-6 overflow-hidden">
                <div id="examProgressBar" class="bg-brand-600 h-2 rounded-full transition-all duration-300" style="width: 0%"></div>
            </div>

            <div class="bg-white rounded-2xl shadow-xl border border-slate-100 p-6 sm:p-8 transition-all">
                <div class="flex items-start space-x-3 mb-6">
                    <span class="inline-flex items-center justify-center w-8 h-8 rounded-lg bg-brand-100 text-brand-700 font-bold text-sm shrink-0 mt-0.5" id="questionIndexBadge">
                        ১
                    </span>
                    <h3 id="questionText" class="text-lg sm:text-xl font-bold text-slate-800 leading-relaxed">
                        প্রশ্ন লোড হচ্ছে...
                    </h3>
                </div>

                <div class="grid grid-cols-1 gap-3.5" id="optionsContainer"></div>

                <div class="flex items-center justify-between border-t border-slate-100 mt-8 pt-5">
                    <button id="prevQBtn" onclick="navigateQuestion(-1)" class="px-4 py-2 rounded-xl bg-slate-100 hover:bg-slate-200 text-slate-700 font-semibold text-xs sm:text-sm transition disabled:opacity-40 disabled:cursor-not-allowed">
                        <i class="fa-solid fa-arrow-left mr-1"></i> <span data-key="prevQ">পূর্ববর্তী</span>
                    </button>

                    <div class="text-xs text-slate-400 font-medium hidden sm:block" id="answeredCountBadge">
                        উত্তর দেওয়া হয়েছে: 0 / 10
                    </div>

                    <button id="nextQBtn" onclick="navigateQuestion(1)" class="px-5 py-2 rounded-xl bg-slate-900 hover:bg-slate-800 text-white font-semibold text-xs sm:text-sm transition">
                        <span data-key="nextQ">পরবর্তী</span> <i class="fa-solid fa-arrow-right ml-1"></i>
                    </button>
                </div>
            </div>
        </section>

        <!-- RESULT PAGE -->
        <section id="resultPage" class="w-full max-w-4xl hidden">
            <div class="bg-white rounded-2xl shadow-xl border border-slate-100 overflow-hidden mb-8">
                <div class="bg-gradient-to-r from-slate-900 via-slate-800 to-slate-900 p-6 sm:p-8 text-white text-center relative">
                    <div class="inline-flex items-center justify-center w-16 h-16 rounded-full bg-slate-800 border-2 border-brand-500 mb-3 shadow-lg">
                        <i class="fa-solid fa-trophy text-amber-400 text-2xl"></i>
                    </div>
                    <h2 class="text-2xl sm:text-3xl font-extrabold" data-key="resultTitle">পরীক্ষার ফলাফল রিপোর্ট</h2>
                    <p class="text-xs sm:text-sm text-slate-300 mt-1" id="resultSubtitle">শ্রেণী ১০ - সাধারণ জ্ঞান ও বিষয় ভিত্তিক টেস্ট</p>

                    <div class="mt-6 inline-block bg-slate-800/90 border border-slate-700 px-6 py-2.5 rounded-2xl">
                        <span class="text-xs uppercase tracking-wider text-slate-400 block font-bold" data-key="gradeAchieved">অর্জিত গ্রেড</span>
                        <span class="text-2xl sm:text-3xl font-black text-brand-400" id="resultGrade">A+</span>
                    </div>
                </div>

                <div class="grid grid-cols-2 md:grid-cols-4 divide-y md:divide-y-0 md:divide-x divide-slate-100 border-b border-slate-100">
                    <div class="p-4 sm:p-6 text-center">
                        <span class="text-xs text-slate-500 font-bold uppercase block" data-key="totalScore">মোট স্কোর</span>
                        <span class="text-2xl sm:text-3xl font-black text-slate-800" id="scoreObtained">0</span>
                        <span class="text-xs text-slate-400 font-semibold" id="scoreTotal">/ 100</span>
                    </div>

                    <div class="p-4 sm:p-6 text-center">
                        <span class="text-xs text-slate-500 font-bold uppercase block" data-key="accuracy">সঠিকতার হার</span>
                        <span class="text-2xl sm:text-3xl font-black text-brand-600" id="accuracyPercentage">0%</span>
                    </div>

                    <div class="p-4 sm:p-6 text-center">
                        <span class="text-xs text-slate-500 font-bold uppercase block" data-key="correctAnswers">সঠিক উত্তর</span>
                        <span class="text-2xl sm:text-3xl font-black text-emerald-600" id="correctCount">0</span>
                    </div>

                    <div class="p-4 sm:p-6 text-center">
                        <span class="text-xs text-slate-500 font-bold uppercase block" data-key="incorrectAnswers">ভুল উত্তর / উত্তরহীন</span>
                        <span class="text-2xl sm:text-3xl font-black text-rose-500" id="incorrectCount">0</span>
                    </div>
                </div>

                <div class="p-4 bg-slate-50 flex flex-wrap justify-center gap-3">
                    <button onclick="navigateTo('category')" class="px-5 py-2.5 rounded-xl bg-slate-900 hover:bg-slate-800 text-white font-bold text-xs sm:text-sm shadow transition">
                        <i class="fa-solid fa-house mr-1"></i> <span data-key="backHome">প্রধান পাতা</span>
                    </button>
                    <button onclick="restartExam()" class="px-5 py-2.5 rounded-xl bg-brand-600 hover:bg-brand-700 text-white font-bold text-xs sm:text-sm shadow transition">
                        <i class="fa-solid fa-rotate-right mr-1"></i> <span data-key="reTakeExam">পুনরায় পরীক্ষা দিন</span>
                    </button>
                </div>
            </div>

            <div class="space-y-4">
                <h3 class="text-xl font-extrabold text-slate-800 flex items-center justify-between" data-key="detailedReview">
                    <span>প্রশ্ন ও উত্তর বিস্তারিত পর্যালোচনা</span>
                    <span class="text-xs font-normal text-slate-500" id="reviewCountBadge">১০ টি প্রশ্ন</span>
                </h3>

                <div id="reviewContainer" class="space-y-4"></div>
            </div>
        </section>

    </main>

    <!-- Custom Modal -->
    <div id="customModal" class="fixed inset-0 bg-slate-900/60 backdrop-blur-sm z-50 flex items-center justify-center p-4 hidden">
        <div class="bg-white rounded-2xl max-w-sm w-full p-6 shadow-2xl border border-slate-100 text-center animate-in fade-in zoom-in duration-200">
            <div class="w-12 h-12 rounded-full bg-brand-100 text-brand-600 inline-flex items-center justify-center text-xl mb-4" id="modalIcon">
                <i class="fa-solid fa-circle-info"></i>
            </div>
            <h3 class="text-lg font-bold text-slate-900 mb-2" id="modalTitle">বিজ্ঞপ্তি</h3>
            <p class="text-xs text-slate-600 mb-6" id="modalMessage">বার্তার বিবরণ...</p>
            <div class="flex items-center justify-center space-x-3 space-x-reverse" id="modalButtons">
                <button onclick="closeModal()" class="w-full py-2.5 bg-brand-600 hover:bg-brand-700 text-white text-xs font-bold rounded-xl transition">
                    ঠিক আছে
                </button>
            </div>
        </div>
    </div>

    <!-- Loading Overlay -->
    <div id="loadingOverlay" class="fixed inset-0 bg-slate-900/70 backdrop-blur-sm z-50 flex flex-col items-center justify-center text-white hidden">
        <div class="w-12 h-12 border-4 border-brand-500 border-t-transparent rounded-full animate-spin mb-4"></div>
        <div class="text-base font-bold" id="loadingText">প্রশ্নমালা প্রস্তুত করা হচ্ছে...</div>
        <div class="text-xs text-slate-300 mt-1">Gemini AI Engine Processing</div>
    </div>

    <script>
        const state = {
            lang: 'bn',
            user: null,
            currentCategory: null,
            subject: 'General',
            questionCount: 10,
            allocatedTimeMinutes: 10,
            autoAdvance: true,
            questions: [],
            userAnswers: {},
            currentQuestionIndex: 0,
            timerInterval: null,
            timeRemainingSeconds: 0,
            examStartTime: null,
            examActive: false
        };

        const categories = [
            { id: 'class_1', nameBn: '১ম শ্রেণী', nameEn: 'Class 1', icon: 'fa-child-reaching', levelPrompt: 'Very basic primary school Level 1 questions for age 6.' },
            { id: 'class_2', nameBn: '২য় শ্রেণী', nameEn: 'Class 2', icon: 'fa-child', levelPrompt: 'Primary school Level 2 questions for age 7.' },
            { id: 'class_3', nameBn: '৩য় শ্রেণী', nameEn: 'Class 3', icon: 'fa-children', levelPrompt: 'Primary school Level 3 questions for age 8.' },
            { id: 'class_4', nameBn: '৪র্থ শ্রেণী', nameEn: 'Class 4', icon: 'fa-book-open', levelPrompt: 'Primary school Level 4 curriculum questions.' },
            { id: 'class_5', nameBn: '৫ম শ্রেণী', nameEn: 'Class 5', icon: 'fa-shapes', levelPrompt: 'Primary school Level 5 (PECE Standard) questions.' },
            { id: 'class_6', nameBn: 'ষষ্ঠ শ্রেণী', nameEn: 'Class 6', icon: 'fa-book-bookmark', levelPrompt: 'Junior high Class 6 NCTB standard questions.' },
            { id: 'class_7', nameBn: 'সপ্তম শ্রেণী', nameEn: 'Class 7', icon: 'fa-book-open-reader', levelPrompt: 'Junior high Class 7 NCTB standard questions.' },
            { id: 'class_8', nameBn: 'অষ্টম শ্রেণী', nameEn: 'Class 8', icon: 'fa-school', levelPrompt: 'Junior high Class 8 (JSC Standard) questions.' },
            { id: 'class_9', nameBn: 'নবম শ্রেণী', nameEn: 'Class 9', icon: 'fa-user-graduate', levelPrompt: 'Secondary High School Class 9 curriculum standard questions.' },
            { id: 'class_10', nameBn: '১০ম শ্রেণী (SSC)', nameEn: 'Class 10 (SSC)', icon: 'fa-graduation-cap', levelPrompt: 'Secondary School Certificate (SSC) examination board standard.' },
            { id: 'hsc', nameBn: '১১দশ - ১২দশ (HSC)', nameEn: 'HSC / Intermediate', icon: 'fa-university', levelPrompt: 'Higher Secondary Certificate (HSC) level questions.' },
            { id: 'college_adm', nameBn: 'কলেজ ভর্তি (SSC পরবর্তী)', nameEn: 'College Admission', icon: 'fa-building-columns', levelPrompt: 'Top College Entrance Test standard questions.' },
            { id: 'bteb_poly', nameBn: 'কারিগরি ও পলিটেকনিক (BTEB)', nameEn: 'Polytechnic Admission', icon: 'fa-microchip', levelPrompt: 'Diploma in Engineering BTEB entrance standard.' }
        ];

        const builtInQuestionPool = {
            'class_10': [
                {
                    questionBn: 'বাংলাদেশ টেক্সটাইল বিশ্ববিদ্যালয় (BUTEX) কোথায় অবস্থিত?',
                    questionEn: 'Where is Bangladesh University of Textiles (BUTEX) located?',
                    optionsBn: ['তেজগাঁও, ঢাকা', 'মিরপুর, ঢাকা', 'উত্তরা, ঢাকা', 'গাজীপুর'],
                    optionsEn: ['Tejgaon, Dhaka', 'Mirpur, Dhaka', 'Uttara, Dhaka', 'Gazipur'],
                    answer: 0
                },
                {
                    questionBn: 'পদার্থের চতুর্থ অবস্থাকে কী বলা হয়?',
                    questionEn: 'What is the fourth state of matter called?',
                    optionsBn: ['কঠিন', 'তরল', 'প্লাজমা', 'গ্যাসিয়'],
                    optionsEn: ['Solid', 'Liquid', 'Plasma', 'Gaseous'],
                    answer: 2
                }
            ],
            'general': [
                {
                    questionBn: 'কম্পিউটারের মস্তিষ্কের মতো কাজ করে কোনটি?',
                    questionEn: 'Which acts as the brain of a computer?',
                    optionsBn: ['RAM', 'CPU', 'Hard Disk', 'Monitor'],
                    optionsEn: ['RAM', 'CPU', 'Hard Disk', 'Monitor'],
                    answer: 1
                }
            ]
        };

        const i18n = {
            bn: {
                login: "লগইন", signup: "রেজিস্টার", fullName: "পূর্ণ নাম", phone: "মোবাইল নম্বর",
                email: "ইমেইল ঠিকানা (ঐচ্ছিক)", password: "পাসওয়ার্ড", confirmPassword: "পাসওয়ার্ড নিশ্চিত করুন",
                rememberMe: "মনে রাখুন", forgotPassword: "পাসওয়ার্ড ভুলে গেছেন?", loginBtn: "লগইন করুন",
                signupBtn: "অ্যাকাউন্ট তৈরি করুন", selectCategory: "শ্রেণী / ক্যাটাগরি নির্বাচন করুন",
                selectCategorySub: "আপনার পরীক্ষার কোর্স বা শ্রেণী অনুযায়ী সঠিক বিভাগ পছন্দ করুন",
                aiPoweredNotice: "Gemini AI দ্বারা স্বয়ংক্রিয় প্রশ্ন জেনারেটর যুক্ত", selectSubject: "বিষয় বা টপিক (ঐচ্ছিক)",
                questionCount: "প্রশ্নের সংখ্যা নির্ধারণ করুন", allocatedTime: "বরাদ্দকৃত মোট সময়",
                perQuestionSpeed: "প্রতি প্রশ্নে বরাদ্দ", autoAdvance: "স্বয়ংক্রিয় পরবর্তী প্রশ্ন (Auto-advance)",
                autoAdvanceSub: "উত্তর নির্বাচন করলেই দ্রুত পরবর্তী প্রশ্নে চলে যাবে", startExamBtn: "পরীক্ষা শুরু করুন",
                changeCategory: "পরিবর্তন", questionLabel: "প্রশ্ন", finishExam: "পরীক্ষা শেষ করুন", prevQ: "পূর্ববর্তী",
                nextQ: "পরবর্তী", resultTitle: "পরীক্ষার ফলাফল রিপোর্ট", gradeAchieved: "অর্জিত গ্রেড",
                totalScore: "মোট স্কোর", accuracy: "সঠিকতার হার", correctAnswers: "সঠিক উত্তর",
                incorrectAnswers: "ভুল উত্তর / উত্তরহীন", backHome: "প্রধান পাতা", reTakeExam: "পুনরায় পরীক্ষা দিন",
                detailedReview: "প্রশ্ন ও উত্তর বিস্তারিত পর্যালোচনা"
            },
            en: {
                login: "Login", signup: "Sign Up", fullName: "Full Name", phone: "Phone Number",
                email: "Email Address (Optional)", password: "Password", confirmPassword: "Confirm Password",
                rememberMe: "Remember Me", forgotPassword: "Forgot Password?", loginBtn: "Login Now",
                signupBtn: "Create Account", selectCategory: "Select Class / Category",
                selectCategorySub: "Choose the appropriate level according to your curriculum",
                aiPoweredNotice: "Gemini AI Dynamic Question Generator Powered", selectSubject: "Subject / Topic (Optional)",
                questionCount: "Select Number of Questions", allocatedTime: "Total Time Allocated",
                perQuestionSpeed: "Time Per Question", autoAdvance: "Auto-advance to Next Question",
                autoAdvanceSub: "Automatically proceeds to next question upon selection", startExamBtn: "Start Examination",
                changeCategory: "Change", questionLabel: "Question", finishExam: "Finish Exam", prevQ: "Previous",
                nextQ: "Next", resultTitle: "Examination Result Report", gradeAchieved: "Grade Achieved",
                totalScore: "Total Score", accuracy: "Accuracy Rate", correctAnswers: "Correct Answers",
                incorrectAnswers: "Incorrect / Skipped", backHome: "Home Screen", reTakeExam: "Retake Examination",
                detailedReview: "Detailed Question & Answer Review"
            }
        };

        window.onload = function() {
            checkSavedUser();
            renderCategories();
            renderQuestionCountOptions();
        };

        function checkSavedUser() {
            const savedUser = localStorage.getItem('rtg_mcq_user');
            if (savedUser && savedUser !== 'undefined' && savedUser !== 'null') {
                try {
                    state.user = JSON.parse(savedUser);
                    updateUserDisplay();
                    navigateTo('category');
                } catch(e) {
                    localStorage.removeItem('rtg_mcq_user');
                    navigateTo('auth');
                }
            } else {
                navigateTo('auth');
            }
        }

        function navigateTo(pageId) {
            const pages = ['authPage', 'categoryPage', 'paramsPage', 'examPage', 'resultPage'];
            pages.forEach(p => {
                const el = document.getElementById(p);
                if (el) el.classList.add('hidden');
            });

            const targetPage = document.getElementById(pageId + 'Page');
            if (targetPage) targetPage.classList.remove('hidden');

            const header = document.getElementById('mainHeader');
            if (pageId === 'auth') {
                header.classList.add('hidden');
            } else {
                header.classList.remove('hidden');
            }
            window.scrollTo({ top: 0, behavior: 'smooth' });
        }

        function toggleLanguage() {
            state.lang = state.lang === 'bn' ? 'en' : 'bn';
            document.getElementById('langText').innerText = state.lang === 'bn' ? 'English' : 'বাংলা';
            
            document.querySelectorAll('[data-key]').forEach(el => {
                const key = el.getAttribute('data-key');
                if (i18n[state.lang] && i18n[state.lang][key]) {
                    el.innerText = i18n[state.lang][key];
                }
            });

            renderCategories();
            updateTimeCalculations();
            if (state.questions.length > 0) {
                renderCurrentQuestion();
            }
        }

        let authMode = 'login';

        function switchAuthTab(mode) {
            authMode = mode;
            const loginBtn = document.getElementById('loginTabBtn');
            const signupBtn = document.getElementById('signupTabBtn');
            const nameGroup = document.getElementById('nameGroup');
            const emailGroup = document.getElementById('emailGroup');
            const confirmGroup = document.getElementById('confirmPasswordGroup');
            const heading = document.getElementById('authHeading');
            const btnText = document.getElementById('authBtnText');

            if (mode === 'signup') {
                loginBtn.className = "py-2 rounded-lg text-slate-300 hover:text-white transition";
                signupBtn.className = "py-2 rounded-lg bg-brand-600 text-white transition shadow";
                nameGroup.classList.remove('hidden');
                emailGroup.classList.remove('hidden');
                confirmGroup.classList.remove('hidden');
                heading.innerText = state.lang === 'bn' ? "নতুন অ্যাকাউন্ট তৈরি করুন" : "Create New Account";
                btnText.innerText = i18n[state.lang].signupBtn;
            } else {
                signupBtn.className = "py-2 rounded-lg text-slate-300 hover:text-white transition";
                loginBtn.className = "py-2 rounded-lg bg-brand-600 text-white transition shadow";
                nameGroup.classList.add('hidden');
                emailGroup.classList.add('hidden');
                confirmGroup.classList.add('hidden');
                heading.innerText = state.lang === 'bn' ? "লগইন করুন" : "Account Login";
                btnText.innerText = i18n[state.lang].loginBtn;
            }
        }

        function handleAuthSubmit(e) {
            e.preventDefault();
            const phone = document.getElementById('authPhone').value.trim();
            const password = document.getElementById('authPassword').value;

            if (!phone || !password) {
                showNotice("অনুগ্রহ করে মোবাইল নম্বর এবং পাসওয়ার্ড প্রদান করুন।");
                return;
            }

            if (authMode === 'signup') {
                const name = document.getElementById('authName').value.trim();
                const confirmPw = document.getElementById('authConfirmPassword').value;

                if (!name) {
                    showNotice("অনুগ্রহ করে আপনার নাম লিখুন।");
                    return;
                }
                if (password !== confirmPw) {
                    showNotice("পাসওয়ার্ড দুটি মিলছে না।");
                    return;
                }

                state.user = { name, phone, email: document.getElementById('authEmail').value };
            } else {
                state.user = { name: phone.slice(-4) + " স্টুডেন্ট", phone };
            }

            if (document.getElementById('rememberMe').checked) {
                localStorage.setItem('rtg_mcq_user', JSON.stringify(state.user));
            }

            updateUserDisplay();
            navigateTo('category');
        }

        function updateUserDisplay() {
            if (!state.user) return;
            document.getElementById('userProfileBadge').classList.remove('hidden');
            document.getElementById('userNameDisplay').innerText = state.user.name || "শিক্ষার্থী";
            document.getElementById('userPhoneDisplay').innerText = state.user.phone || "";
            document.getElementById('userAvatar').innerText = (state.user.name || "U")[0].toUpperCase();
        }

        function logout() {
            localStorage.removeItem('rtg_mcq_user');
            state.user = null;
            document.getElementById('userProfileBadge').classList.add('hidden');
            navigateTo('auth');
        }

        function renderCategories() {
            const grid = document.getElementById('categoryGrid');
            grid.innerHTML = '';

            categories.forEach(cat => {
                const name = state.lang === 'bn' ? cat.nameBn : cat.nameEn;

                const card = document.createElement('div');
                card.className = "bg-white rounded-2xl p-5 border border-slate-200/80 hover:border-brand-500/50 shadow-sm hover:shadow-xl transition-all duration-300 cursor-pointer group flex flex-col justify-between";
                card.onclick = () => selectCategory(cat);

                card.innerHTML = `
                    <div>
                        <div class="w-10 h-10 rounded-xl bg-slate-100 group-hover:bg-brand-600 text-slate-700 group-hover:text-white flex items-center justify-center text-lg mb-3 transition-colors">
                            <i class="fa-solid ${cat.icon}"></i>
                        </div>
                        <h3 class="text-base font-bold text-slate-900 group-hover:text-brand-600 transition-colors">${name}</h3>
                        <p class="text-xs text-slate-500 mt-1.5 leading-relaxed">${cat.levelPrompt}</p>
                    </div>
                    <div class="mt-5 pt-3 border-t border-slate-100 flex items-center justify-between text-xs font-bold text-brand-600">
                        <span>${state.lang === 'bn' ? 'পরীক্ষা নির্বাচন করুন' : 'Select Class'}</span>
                        <i class="fa-solid fa-chevron-right transform group-hover:translate-x-1 transition"></i>
                    </div>
                `;
                grid.appendChild(card);
            });
        }

        function selectCategory(cat) {
            state.currentCategory = cat;
            document.getElementById('selectedCategoryTitle').innerText = state.lang === 'bn' ? cat.nameBn : cat.nameEn;
            document.getElementById('selectedCategoryBadge').innerText = cat.id.toUpperCase();
            navigateTo('params');
        }

        const questionPresets = [10, 20, 30, 50, 70, 100, 200, 500];

        function renderQuestionCountOptions() {
            const container = document.getElementById('countGrid');
            container.innerHTML = '';

            questionPresets.forEach(count => {
                const btn = document.createElement('button');
                btn.type = 'button';
                btn.className = `py-2.5 rounded-xl text-xs sm:text-sm font-bold border transition ${
                    count === state.questionCount 
                    ? 'bg-slate-900 text-white border-slate-900 shadow-md scale-105' 
                    : 'bg-white text-slate-700 border-slate-200 hover:border-slate-300'
                }`;
                btn.innerText = count + (state.lang === 'bn' ? ' টি' : '');
                btn.onclick = () => {
                    state.questionCount = count;
                    renderQuestionCountOptions();
                    updateTimeCalculations();
                };
                container.appendChild(btn);
            });
            updateTimeCalculations();
        }

        function updateTimeCalculations() {
            const totalSeconds = state.questionCount * 45;
            state.allocatedTimeMinutes = Math.ceil(totalSeconds / 60);

            const displayMin = state.allocatedTimeMinutes;
            document.getElementById('calculatedTimeDisplay').innerText = state.lang === 'bn' 
                ? displayMin + " মিনিট" 
                : displayMin + " Mins";

            document.getElementById('perQuestionTimeDisplay').innerText = state.lang === 'bn' 
                ? "৪৫ সেকেন্ড" 
                : "45 Seconds";
        }

        // GEMINI AI INTEGRATION FUNCTION
        async function fetchQuestionsFromGemini(category, count, subject) {
            const apiKeyInput = document.getElementById('geminiApiKey').value.trim();
            const apiKey = apiKeyInput || ""; // Put default key if needed

            // Dynamic unique seed to prevent repeated questions across generations
            const randomSeed = Math.floor(Math.random() * 1000000);
            const timestamp = new Date().getTime();

            const systemPrompt = `You are an expert exam paper setter for Bangladesh National Curriculum (NCTB) and competitive exams. 
Generate exactly ${count} multiple-choice questions (MCQs).
Target Class Level: ${category.nameEn} (${category.nameBn}).
Curriculum Guidelines: ${category.levelPrompt}.
Subject: ${subject}.
IMPORTANT RULES:
1. Questions MUST strictly match the complexity and difficulty level appropriate for ${category.nameEn}. (e.g., Class 1-3 must be very simple, Class 9-10/HSC must be appropriate board exam level).
2. Ensure high uniqueness. Random Seed: ${randomSeed}_${timestamp}.
3. Balance question difficulty (40% Easy, 40% Medium, 20% Hard).
4. Return ONLY valid JSON array without any markdown formatted blocks. Each item must contain:
   - "questionBn": string
   - "questionEn": string
   - "optionsBn": array of 4 strings
   - "optionsEn": array of 4 strings
   - "answer": integer index (0, 1, 2, or 3)`;

            const userPrompt = `Generate ${count} dynamic MCQs for ${category.nameBn} in ${subject}. Seed: ${randomSeed}`;

            const payload = {
                contents: [{ parts: [{ text: userPrompt }] }],
                systemInstruction: { parts: [{ text: systemPrompt }] },
                generationConfig: {
                    responseMimeType: "application/json",
                    responseSchema: {
                        type: "ARRAY",
                        items: {
                            type: "OBJECT",
                            properties: {
                                "questionBn": { type: "STRING" },
                                "questionEn": { type: "STRING" },
                                "optionsBn": { type: "ARRAY", items: { type: "STRING" } },
                                "optionsEn": { type: "ARRAY", items: { type: "STRING" } },
                                "answer": { type: "INTEGER" }
                            },
                            required: ["questionBn", "questionEn", "optionsBn", "optionsEn", "answer"]
                        }
                    }
                }
            };

            if (!apiKey) {
                throw new Error("API Key is missing");
            }

            const apiUrl = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.5-flash:generateContent?key=${apiKey}`;

            const response = await fetch(apiUrl, {
                method: 'POST',
                headers: { 'Content-Type': 'application/json' },
                body: JSON.stringify(payload)
            });

            if (!response.ok) throw new Error("API call failed: " + response.statusText);

            const result = await response.json();
            const rawJson = result.candidates?.[0]?.content?.parts?.[0]?.text;
            if (!rawJson) throw new Error("Empty response");

            let cleanJson = rawJson.trim();
            if (cleanJson.startsWith('```json')) {
                cleanJson = cleanJson.replace(/^```json\s*/, '').replace(/\s*```$/, '');
            } else if (cleanJson.startsWith('```')) {
                cleanJson = cleanJson.replace(/^```\s*/, '').replace(/\s*```$/, '');
            }

            return JSON.parse(cleanJson);
        }

        function generateFallbackQuestions(count) {
            const source = builtInQuestionPool[state.currentCategory?.id] || builtInQuestionPool['class_10'] || builtInQuestionPool['general'];
            const generated = [];

            for (let i = 0; i < count; i++) {
                const baseItem = source[i % source.length];
                generated.push({
                    questionBn: `[${state.currentCategory?.nameBn || 'সাধারণ'} - প্রশ্ন ${i + 1}] ${baseItem.questionBn}`,
                    questionEn: `[${state.currentCategory?.nameEn || 'General'} - Q${i + 1}] ${baseItem.questionEn}`,
                    optionsBn: [...baseItem.optionsBn],
                    optionsEn: [...baseItem.optionsEn],
                    answer: baseItem.answer
                });
            }
            return generated;
        }

        async function startExam() {
            state.subject = document.getElementById('subjectSelect').value;
            state.autoAdvance = document.getElementById('autoAdvanceToggle').checked;
            state.userAnswers = {};
            state.currentQuestionIndex = 0;

            const loadingOverlay = document.getElementById('loadingOverlay');
            loadingOverlay.classList.remove('hidden');

            try {
                const questions = await fetchQuestionsFromGemini(state.currentCategory, state.questionCount, state.subject);
                if (questions && Array.isArray(questions) && questions.length > 0) {
                    state.questions = questions;
                } else {
                    throw new Error("Invalid output format");
                }
            } catch (error) {
                console.warn("Gemini API call skipped or failed. Using dynamic fallback engine:", error);
                state.questions = generateFallbackQuestions(state.questionCount);
            } finally {
                loadingOverlay.classList.add('hidden');
            }

            document.getElementById('examCategoryTag').innerText = state.lang === 'bn' ? state.currentCategory.nameBn : state.currentCategory.nameEn;
            document.getElementById('totalQNum').innerText = state.questions.length;
            
            state.timeRemainingSeconds = state.allocatedTimeMinutes * 60;
            state.examActive = true;
            startTimer();

            navigateTo('exam');
            renderCurrentQuestion();
        }

        function startTimer() {
            clearInterval(state.timerInterval);
            updateTimerDisplay();

            state.timerInterval = setInterval(() => {
                if (!state.examActive) return;
                state.timeRemainingSeconds--;

                updateTimerDisplay();

                if (state.timeRemainingSeconds <= 0) {
                    clearInterval(state.timerInterval);
                    showNotice("সময় শেষ হয়ে গেছে! আপনার পরীক্ষা স্বয়ংক্রিয়ভাবে জমা নেওয়া হচ্ছে।", () => {
                        finishExam();
                    });
                }
            }, 1000);
        }

        function updateTimerDisplay() {
            const minutes = Math.floor(state.timeRemainingSeconds / 60);
            const seconds = state.timeRemainingSeconds % 60;
            const formatted = `${String(minutes).padStart(2, '0')}:${String(seconds).padStart(2, '0')}`;
            
            const timerDisplay = document.getElementById('timerDisplay');
            timerDisplay.innerText = formatted;

            const timerContainer = document.getElementById('timerContainer');
            if (state.timeRemainingSeconds < 60) {
                timerContainer.className = "flex items-center space-x-2 px-4 py-1.5 rounded-xl bg-red-600 text-white shadow font-mono font-bold text-base animate-pulse";
            } else {
                timerContainer.className = "flex items-center space-x-2 px-4 py-1.5 rounded-xl bg-slate-900 text-white shadow font-mono font-bold text-base";
            }
        }

        function renderCurrentQuestion() {
            const idx = state.currentQuestionIndex;
            const q = state.questions[idx];

            if (!q) return;

            document.getElementById('currentQNum').innerText = idx + 1;
            document.getElementById('questionIndexBadge').innerText = state.lang === 'bn' ? (idx + 1).toLocaleString('bn-BD') : (idx + 1);
            
            const pct = ((idx + 1) / state.questions.length) * 100;
            document.getElementById('examProgressBar').style.width = `${pct}%`;

            document.getElementById('questionText').innerText = state.lang === 'bn' ? q.questionBn : q.questionEn;

            const options = state.lang === 'bn' ? q.optionsBn : q.optionsEn;
            const container = document.getElementById('optionsContainer');
            container.innerHTML = '';

            const selectedOption = state.userAnswers[idx];

            options.forEach((optText, oIdx) => {
                const optBtn = document.createElement('button');
                const isSelected = selectedOption === oIdx;

                optBtn.className = `w-full p-4 rounded-xl border text-left transition-all flex items-center justify-between group ${
                    isSelected 
                    ? 'bg-brand-50 border-brand-500 text-brand-900 ring-2 ring-brand-500/30 shadow-md font-bold' 
                    : 'bg-white border-slate-200 hover:border-slate-300 text-slate-800'
                }`;

                const prefix = String.fromCharCode(65 + oIdx);

                optBtn.innerHTML = `
                    <div class="flex items-center space-x-3 space-x-reverse">
                        <span class="w-8 h-8 rounded-lg flex items-center justify-center font-bold text-xs shrink-0 ${
                            isSelected ? 'bg-brand-600 text-white' : 'bg-slate-100 text-slate-600 group-hover:bg-slate-200'
                        }">
                            ${prefix}
                        </span>
                        <span class="text-sm sm:text-base">${optText}</span>
                    </div>
                    <div class="w-5 h-5 rounded-full border flex items-center justify-center ${
                        isSelected ? 'border-brand-600 bg-brand-600 text-white' : 'border-slate-300'
                    }">
                        ${isSelected ? '<i class="fa-solid fa-check text-[10px]"></i>' : ''}
                    </div>
                `;

                optBtn.onclick = () => selectAnswer(idx, oIdx);
                container.appendChild(optBtn);
            });

            document.getElementById('prevQBtn').disabled = idx === 0;
            const nextBtn = document.getElementById('nextQBtn');
            if (idx === state.questions.length - 1) {
                nextBtn.innerHTML = `<span>${state.lang === 'bn' ? 'সমাপ্ত করুন' : 'Finish'}</span> <i class="fa-solid fa-flag-checkered ml-1"></i>`;
                nextBtn.onclick = confirmFinishExam;
            } else {
                nextBtn.innerHTML = `<span>${i18n[state.lang].nextQ}</span> <i class="fa-solid fa-arrow-right ml-1"></i>`;
                nextBtn.onclick = () => navigateQuestion(1);
            }

            const answeredCount = Object.keys(state.userAnswers).length;
            document.getElementById('answeredCountBadge').innerText = state.lang === 'bn' 
                ? `উত্তর দেওয়া হয়েছে: ${answeredCount} / ${state.questions.length}` 
                : `Answered: ${answeredCount} / ${state.questions.length}`;
        }

        function selectAnswer(qIdx, optionIdx) {
            state.userAnswers[qIdx] = optionIdx;
            renderCurrentQuestion();

            if (state.autoAdvance && qIdx < state.questions.length - 1) {
                setTimeout(() => {
                    if (state.currentQuestionIndex === qIdx) {
                        navigateQuestion(1);
                    }
                }, 350);
            }
        }

        function navigateQuestion(direction) {
            const nextIdx = state.currentQuestionIndex + direction;
            if (nextIdx >= 0 && nextIdx < state.questions.length) {
                state.currentQuestionIndex = nextIdx;
                renderCurrentQuestion();
            }
        }

        function confirmFinishExam() {
            const answered = Object.keys(state.userAnswers).length;
            const total = state.questions.length;
            const unattempted = total - answered;

            let msg = `আপনি কি পরীক্ষা শেষ করতে চান?\nউত্তর দিয়েছেন: ${answered}/${total}`;
            if (unattempted > 0) {
                msg += `\n${unattempted} টি উত্তর না দেওয়া প্রশ্ন রয়েছে।`;
            }

            showConfirm("পরীক্ষা সম্পন্ন করুন", msg, () => {
                finishExam();
            });
        }

        function finishExam() {
            state.examActive = false;
            clearInterval(state.timerInterval);

            let correct = 0;
            let incorrect = 0;
            let unattempted = 0;

            state.questions.forEach((q, idx) => {
                const userAns = state.userAnswers[idx];
                if (userAns === undefined) {
                    unattempted++;
                } else if (userAns === q.answer) {
                    correct++;
                } else {
                    incorrect++;
                }
            });

            const total = state.questions.length;
            const pct = Math.round((correct / total) * 100);

            let grade = 'F';
            if (pct >= 80) grade = 'A+';
            else if (pct >= 70) grade = 'A';
            else if (pct >= 60) grade = 'A-';
            else if (pct >= 50) grade = 'B';
            else if (pct >= 40) grade = 'Pass';

            document.getElementById('resultSubtitle').innerText = `${state.lang === 'bn' ? state.currentCategory.nameBn : state.currentCategory.nameEn} • ${state.subject}`;
            document.getElementById('resultGrade').innerText = grade;
            document.getElementById('scoreObtained').innerText = correct;
            document.getElementById('scoreTotal').innerText = `/ ${total}`;
            document.getElementById('accuracyPercentage').innerText = `${pct}%`;
            document.getElementById('correctCount').innerText = correct;
            document.getElementById('incorrectCount').innerText = incorrect + unattempted;

            renderReviewList();
            navigateTo('result');
        }

        function renderReviewList() {
            const container = document.getElementById('reviewContainer');
            container.innerHTML = '';

            document.getElementById('reviewCountBadge').innerText = `${state.questions.length} ${state.lang === 'bn' ? 'টি প্রশ্ন' : 'Questions'}`;

            state.questions.forEach((q, idx) => {
                const userAns = state.userAnswers[idx];
                const isCorrect = userAns === q.answer;
                const isSkipped = userAns === undefined;

                const qText = state.lang === 'bn' ? q.questionBn : q.questionEn;
                const options = state.lang === 'bn' ? q.optionsBn : q.optionsEn;

                const reviewCard = document.createElement('div');
                reviewCard.className = `p-5 rounded-2xl border bg-white shadow-sm ${
                    isCorrect ? 'border-emerald-200' : isSkipped ? 'border-amber-200' : 'border-rose-200'
                }`;

                let badgeHtml = '';
                if (isCorrect) {
                    badgeHtml = `<span class="px-2.5 py-1 rounded-lg bg-emerald-100 text-emerald-700 font-bold text-xs flex items-center gap-1"><i class="fa-solid fa-circle-check"></i> সঠিক</span>`;
                } else if (isSkipped) {
                    badgeHtml = `<span class="px-2.5 py-1 rounded-lg bg-amber-100 text-amber-700 font-bold text-xs flex items-center gap-1"><i class="fa-solid fa-circle-minus"></i> উত্তর দেওয়া হয়নি</span>`;
                } else {
                    badgeHtml = `<span class="px-2.5 py-1 rounded-lg bg-rose-100 text-rose-700 font-bold text-xs flex items-center gap-1"><i class="fa-solid fa-circle-xmark"></i> ভুল উত্তর</span>`;
                }

                let optionsListHtml = `<div class="grid grid-cols-1 sm:grid-cols-2 gap-2 mt-3">`;
                options.forEach((opt, oIdx) => {
                    let optStyle = "bg-slate-50 text-slate-700 border-slate-200";
                    if (oIdx === q.answer) {
                        optStyle = "bg-emerald-50 text-emerald-800 border-emerald-400 font-bold";
                    } else if (oIdx === userAns && !isCorrect) {
                        optStyle = "bg-rose-50 text-rose-800 border-rose-300 line-through";
                    }

                    optionsListHtml += `
                        <div class="p-2.5 rounded-xl border text-xs flex items-center space-x-2 ${optStyle}">
                            <span class="font-bold uppercase">${String.fromCharCode(65 + oIdx)}.</span>
                            <span>${opt}</span>
                        </div>
                    `;
                });
                optionsListHtml += `</div>`;

                reviewCard.innerHTML = `
                    <div class="flex items-start justify-between gap-3">
                        <div class="font-bold text-slate-800 text-sm">
                            <span class="text-brand-600 mr-1">#${idx + 1}</span> ${qText}
                        </div>
                        <div>${badgeHtml}</div>
                    </div>
                    ${optionsListHtml}
                `;

                container.appendChild(reviewCard);
            });
        }

        function restartExam() {
            startExam();
        }

        function showNotice(msg, callback = null) {
            const modal = document.getElementById('customModal');
            document.getElementById('modalTitle').innerText = "বিজ্ঞপ্তি";
            document.getElementById('modalMessage').innerText = msg;
            
            const btnContainer = document.getElementById('modalButtons');
            btnContainer.innerHTML = `
                <button onclick="closeModal(true)" class="w-full py-2.5 bg-brand-600 hover:bg-brand-700 text-white text-xs font-bold rounded-xl transition">
                    ঠিক আছে
                </button>
            `;
            
            window._modalCallback = callback;
            modal.classList.remove('hidden');
        }

        function showConfirm(title, msg, onConfirm) {
            const modal = document.getElementById('customModal');
            document.getElementById('modalTitle').innerText = title;
            document.getElementById('modalMessage').innerText = msg;

            const btnContainer = document.getElementById('modalButtons');
            btnContainer.innerHTML = `
                <button onclick="closeModal(false)" class="w-1/2 py-2.5 bg-slate-200 hover:bg-slate-300 text-slate-700 text-xs font-bold rounded-xl transition">
                    বাতিল
                </button>
                <button onclick="closeModal(true)" class="w-1/2 py-2.5 bg-red-600 hover:bg-red-700 text-white text-xs font-bold rounded-xl transition">
                    হ্যাঁ, নিশ্চিত
                </button>
            `;

            window._modalCallback = (confirmed) => {
                if (confirmed) onConfirm();
            };
            modal.classList.remove('hidden');
        }

        function closeModal(param = false) {
            document.getElementById('customModal').classList.add('hidden');
            if (typeof window._modalCallback === 'function') {
                const cb = window._modalCallback;
                window._modalCallback = null;
                cb(param);
            }
        }
    </script>
</body>
</html>
