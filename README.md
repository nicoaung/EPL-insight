# EPL-insight
The site where you can know all about EPL
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EPL Insider - Your Hub for Premier League News</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Font - Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f3f4f6;
        }
        .bg-gradient-hero {
            background-image: linear-gradient(to right, rgba(20, 30, 48, 0.8), rgba(20, 30, 48, 0.5)), url('https://placehold.co/1920x1080/0f172a/FFFFFF?text=EPL+Stadium');
            background-size: cover;
            background-position: center;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <!-- Header & Navigation -->
    <header class="bg-white shadow-md sticky top-0 z-50">
        <nav class="container mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#" class="text-2xl font-bold text-gray-900">EPL Insider</a>
            <div class="hidden md:flex space-x-6 font-medium">
                <a href="#transfers" class="text-gray-600 hover:text-blue-600 transition-colors duration-300">Transfers</a>
                <a href="#analysis" class="text-gray-600 hover:text-blue-600 transition-colors duration-300">Match Analysis</a>
                <a href="#players" class="text-gray-600 hover:text-blue-600 transition-colors duration-300">Player Profiles</a>
                <a href="#creators" class="text-gray-600 hover:text-blue-600 transition-colors duration-300">For Creators</a>
            </div>
            <!-- Mobile Menu Button -->
            <button class="md:hidden text-gray-600 hover:text-blue-600 focus:outline-none">
                <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
                </svg>
            </button>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="bg-gradient-hero text-white text-center py-24 md:py-32">
        <div class="container mx-auto px-6">
            <h1 class="text-4xl md:text-6xl font-extrabold leading-tight tracking-tight mb-4">
                The Ultimate Hub for English Premier League
            </h1>
            <p class="text-lg md:text-xl font-light mb-8 max-w-2xl mx-auto">
                Get the latest transfer updates, in-depth match analysis, and detailed player profiles, all focused on the EPL.
            </p>
            <a href="#transfers" class="bg-blue-600 text-white font-semibold py-3 px-8 rounded-full shadow-lg hover:bg-blue-700 transition-colors duration-300 transform hover:scale-105 inline-block">
                Explore the Latest News
            </a>
        </div>
    </section>

    <main class="container mx-auto px-6 py-12 md:py-16">

        <!-- Transfer News Section -->
        <section id="transfers" class="mb-16">
            <h2 class="text-3xl font-bold text-center text-gray-900 mb-8 md:mb-12">Latest EPL Transfer News</h2>
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">

                <!-- Transfer Card 1 -->
                <div class="bg-white rounded-xl shadow-lg overflow-hidden transform hover:scale-105 transition-transform duration-300">
                    <img src="https://placehold.co/600x400/0f172a/FFFFFF?text=Midfielder+to+Chelsea" alt="Midfielder to Chelsea" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <span class="inline-block bg-green-200 text-green-800 text-xs font-bold uppercase rounded-full px-3 py-1 mb-2">Confirmed</span>
                        <h3 class="text-xl font-bold text-gray-900 mb-2">Midfielder Seals Move to Chelsea</h3>
                        <p class="text-gray-600 text-sm">
                            A highly-rated midfielder has completed a move to Stamford Bridge on a long-term contract, bolstering the Blues' midfield options.
                        </p>
                        <a href="#" class="mt-4 text-blue-600 hover:text-blue-800 font-semibold inline-block">Read More &rarr;</a>
                    </div>
                </div>

                <!-- Transfer Card 2 -->
                <div class="bg-white rounded-xl shadow-lg overflow-hidden transform hover:scale-105 transition-transform duration-300">
                    <img src="https://placehold.co/600x400/0f172a/FFFFFF?text=Striker+to+Man+United" alt="Striker to Man United" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <span class="inline-block bg-yellow-200 text-yellow-800 text-xs font-bold uppercase rounded-full px-3 py-1 mb-2">Rumour</span>
                        <h3 class="text-xl font-bold text-gray-900 mb-2">United in Talks for Star Striker</h3>
                        <p class="text-gray-600 text-sm">
                            Manchester United are reportedly in advanced negotiations to sign a prolific forward from the Bundesliga.
                        </p>
                        <a href="#" class="mt-4 text-blue-600 hover:text-blue-800 font-semibold inline-block">Read More &rarr;</a>
                    </div>
                </div>

                <!-- Transfer Card 3 -->
                <div class="bg-white rounded-xl shadow-lg overflow-hidden transform hover:scale-105 transition-transform duration-300">
                    <img src="https://placehold.co/600x400/0f172a/FFFFFF?text=Player+Signs+New+Deal" alt="Player Signs New Deal" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <span class="inline-block bg-red-200 text-red-800 text-xs font-bold uppercase rounded-full px-3 py-1 mb-2">Contract Extension</span>
                        <h3 class="text-xl font-bold text-gray-900 mb-2">Arsenal Star Extends Contract</h3>
                        <p class="text-gray-600 text-sm">
                            The club captain has committed his future to Arsenal, signing a new long-term deal that will keep him in North London.
                        </p>
                        <a href="#" class="mt-4 text-blue-600 hover:text-blue-800 font-semibold inline-block">Read More &rarr;</a>
                    </div>
                </div>

            </div>
        </section>

        <!-- Match Analysis Section -->
        <section id="analysis" class="mb-16">
            <h2 class="text-3xl font-bold text-center text-gray-900 mb-8 md:mb-12">EPL Match Analysis & Reviews</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">

                <!-- Match Card 1 -->
                <div class="bg-white rounded-xl shadow-lg p-6 flex flex-col justify-between transform hover:scale-105 transition-transform duration-300">
                    <div>
                        <h3 class="text-xl font-bold text-gray-900 mb-2">Final Showdown: City vs Reds</h3>
                        <p class="text-gray-600 text-sm">
                            A tactical deep dive into how Manchester City overcame Liverpool in a thrilling 3-2 victory.
                        </p>
                    </div>
                    <div class="mt-4">
                        <span class="text-2xl font-bold text-blue-600">3 - 2</span>
                        <p class="text-xs text-gray-500">Full Time</p>
                        <a href="#" class="mt-2 text-blue-600 hover:text-blue-800 font-semibold inline-block">Read Full Analysis &rarr;</a>
                    </div>
                </div>

                <!-- Match Card 2 -->
                <div class="bg-white rounded-xl shadow-lg p-6 flex flex-col justify-between transform hover:scale-105 transition-transform duration-300">
                    <div>
                        <h3 class="text-xl font-bold text-gray-900 mb-2">Derby Day Drama: United vs Spurs</h3>
                        <p class="text-gray-600 text-sm">
                            A late goal from Son seals a point for Tottenham in a hard-fought derby against Manchester United.
                        </p>
                    </div>
                    <div class="mt-4">
                        <span class="text-2xl font-bold text-blue-600">1 - 1</span>
                        <p class="text-xs text-gray-500">Full Time</p>
                        <a href="#" class="mt-2 text-blue-600 hover:text-blue-800 font-semibold inline-block">Read Full Analysis &rarr;</a>
                    </div>
                </div>
                
                <!-- Match Card 3 -->
                <div class="bg-white rounded-xl shadow-lg p-6 flex flex-col justify-between transform hover:scale-105 transition-transform duration-300">
                    <div>
                        <h3 class="text-xl font-bold text-gray-900 mb-2">Chelsea's Dominant Performance</h3>
                        <p class="text-gray-600 text-sm">
                            Chelsea progress to the next round with a dominant away performance against a newly promoted side.
                        </p>
                    </div>
                    <div class="mt-4">
                        <span class="text-2xl font-bold text-blue-600">0 - 2</span>
                        <p class="text-xs text-gray-500">Full Time</p>
                        <a href="#" class="mt-2 text-blue-600 hover:text-blue-800 font-semibold inline-block">Read Full Analysis &rarr;</a>
                    </div>
                </div>

                <!-- Match Card 4 -->
                <div class="bg-white rounded-xl shadow-lg p-6 flex flex-col justify-between transform hover:scale-105 transition-transform duration-300">
                    <div>
                        <h3 class="text-xl font-bold text-gray-900 mb-2">Cup Upset: Minnows Triumph</h3>
                        <p class="text-gray-600 text-sm">
                            A stunning upset as the underdog team knocks out the reigning EPL champions in the FA Cup.
                        </p>
                    </div>
                    <div class="mt-4">
                        <span class="text-2xl font-bold text-blue-600">4 - 3</span>
                        <p class="text-xs text-gray-500">Penalty Shootout</p>
                        <a href="#" class="mt-2 text-blue-600 hover:text-blue-800 font-semibold inline-block">Read Full Analysis &rarr;</a>
                    </div>
                </div>

            </div>
        </section>

        <!-- Player Analysis Section -->
        <section id="players" class="mb-16">
            <h2 class="text-3xl font-bold text-center text-gray-900 mb-8 md:mb-12">Featured EPL Player Profiles</h2>
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
                
                <!-- Player Card 1 -->
                <div class="bg-white rounded-xl shadow-lg overflow-hidden transform hover:scale-105 transition-transform duration-300">
                    <img src="https://placehold.co/600x400/1f2937/FFFFFF?text=EPL+Player+A" alt="EPL Player A" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-gray-900 mb-1">Star Midfielder</h3>
                        <p class="text-sm text-gray-500 mb-4">Midfielder | Manchester City</p>
                        <ul class="text-gray-700 space-y-2">
                            <li class="flex items-center">
                                <span class="bg-blue-100 text-blue-600 text-sm font-semibold px-2 py-0.5 rounded mr-2">15</span> Goals
                            </li>
                            <li class="flex items-center">
                                <span class="bg-blue-100 text-blue-600 text-sm font-semibold px-2 py-0.5 rounded mr-2">22</span> Assists
                            </li>
                            <li class="flex items-center">
                                <span class="bg-blue-100 text-blue-600 text-sm font-semibold px-2 py-0.5 rounded mr-2">8.5</span> Rating
                            </li>
                        </ul>
                        <a href="#" class="mt-4 text-blue-600 hover:text-blue-800 font-semibold inline-block">View Full Profile &rarr;</a>
                    </div>
                </div>
                
                <!-- Player Card 2 -->
                <div class="bg-white rounded-xl shadow-lg overflow-hidden transform hover:scale-105 transition-transform duration-300">
                    <img src="https://placehold.co/600x400/1f2937/FFFFFF?text=EPL+Player+B" alt="EPL Player B" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-gray-900 mb-1">Defensive Wall</h3>
                        <p class="text-sm text-gray-500 mb-4">Defender | Liverpool</p>
                        <ul class="text-gray-700 space-y-2">
                            <li class="flex items-center">
                                <span class="bg-blue-100 text-blue-600 text-sm font-semibold px-2 py-0.5 rounded mr-2">12</span> Clean Sheets
                            </li>
                            <li class="flex items-center">
                                <span class="bg-blue-100 text-blue-600 text-sm font-semibold px-2 py-0.5 rounded mr-2">80%</span> Tackles Won
                            </li>
                            <li class="flex items-center">
                                <span class="bg-blue-100 text-blue-600 text-sm font-semibold px-2 py-0.5 rounded mr-2">91%</span> Pass Accuracy
                            </li>
                        </ul>
                        <a href="#" class="mt-4 text-blue-600 hover:text-blue-800 font-semibold inline-block">View Full Profile &rarr;</a>
                    </div>
                </div>

                <!-- Player Card 3 -->
                <div class="bg-white rounded-xl shadow-lg overflow-hidden transform hover:scale-105 transition-transform duration-300">
                    <img src="https://placehold.co/600x400/1f2937/FFFFFF?text=EPL+Player+C" alt="EPL Player C" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-gray-900 mb-1">Young Talent</h3>
                        <p class="text-sm text-gray-500 mb-4">Winger | Arsenal</p>
                        <ul class="text-gray-700 space-y-2">
                            <li class="flex items-center">
                                <span class="bg-blue-100 text-blue-600 text-sm font-semibold px-2 py-0.5 rounded mr-2">10</span> Goals
                            </li>
                            <li class="flex items-center">
                                <span class="bg-blue-100 text-blue-600 text-sm font-semibold px-2 py-0.5 rounded mr-2">15</span> Assists
                            </li>
                            <li class="flex items-center">
                                <span class="bg-blue-100 text-blue-600 text-sm font-semibold px-2 py-0.5 rounded mr-2">72%</span> Dribble Success
                            </li>
                        </ul>
                        <a href="#" class="mt-4 text-blue-600 hover:text-blue-800 font-semibold inline-block">View Full Profile &rarr;</a>
                    </div>
                </div>
            </div>
        </section>

        <!-- Creator Hub Section -->
        <section id="creators" class="text-center py-16 bg-blue-50 rounded-xl shadow-lg">
            <h2 class="text-3xl font-bold text-gray-900 mb-4">Join Our Creator Hub</h2>
            <p class="text-gray-600 max-w-2xl mx-auto mb-6">
                Are you a passionate football writer or analyst? Publish your content on EPL Insider and get a share of the profits.
            </p>
            <a href="#" class="bg-blue-600 text-white font-semibold py-3 px-8 rounded-full shadow-lg hover:bg-blue-700 transition-colors duration-300 transform hover:scale-105 inline-block">
                Learn More & Join
            </a>
        </section>

    </main>

    <!-- Footer -->
    <footer class="bg-gray-900 text-gray-400 py-8">
        <div class="container mx-auto px-6 text-center">
            <p>&copy; 2024 EPL Insider. All rights reserved.</p>
        </div>
    </footer>

</body>
</html>
