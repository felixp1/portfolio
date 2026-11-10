
<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Adeyemi Adedamola Felix | Portfolio</title>
    <meta name="description" content="Portfolio of Adeyemi Adedamola Felix, Information Technology graduate with experience in computer networking, IT support, network troubleshooting and data analytics.">
    <meta name="author" content="Adeyemi Adedamola Felix">
    <meta property="og:title" content="Adeyemi Adedamola Felix | Portfolio">
    <meta property="og:description" content="Information Technology Graduate | Network & Systems Enthusiast">
    <meta property="og:type" content="website">

    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
</head>
<body class="bg-gray-50 text-gray-900 font-sans antialiased">

    <!-- Navigation -->
    <nav class="bg-white shadow-sm fixed w-full z-10 top-0">
        <div class="max-w-6xl mx-auto px-4">
            <div class="flex justify-between items-center py-4">
                <a href="#top" class="text-xl font-bold text-blue-700">Damola's Portfolio</a>

                <div class="hidden md:flex space-x-6">
                    <a href="#about" class="text-gray-600 hover:text-blue-700 font-medium transition-colors">About Me</a>
                    <a href="#what-i-do" class="text-gray-600 hover:text-blue-700 font-medium transition-colors">What I Do</a>
                    <a href="#portfolio" class="text-gray-600 hover:text-blue-700 font-medium transition-colors">My Portfolio</a>
                    <a href="#projects" class="text-gray-600 hover:text-blue-700 font-medium transition-colors">Project</a>
                    <a href="#contact" class="text-gray-600 hover:text-blue-700 font-medium transition-colors">Contact Details</a>
                </div>

                <button id="menu-btn" class="md:hidden text-gray-700 hover:text-blue-700" aria-label="Toggle menu" aria-expanded="false">
                    <i class="fas fa-bars fa-lg"></i>
                </button>
            </div>

            <div id="mobile-menu" class="hidden md:hidden pb-4 space-y-2">
                <a href="#about" class="block text-gray-600 hover:text-blue-700 font-medium">About Me</a>
                <a href="#what-i-do" class="block text-gray-600 hover:text-blue-700 font-medium">What I Do</a>
                <a href="#portfolio" class="block text-gray-600 hover:text-blue-700 font-medium">My Portfolio</a>
                <a href="#projects" class="block text-gray-600 hover:text-blue-700 font-medium">Project</a>
                <a href="#contact" class="block text-gray-600 hover:text-blue-700 font-medium">Contact Details</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header id="top" class="pt-32 pb-16 bg-blue-700 text-white text-center">
        <div class="max-w-4xl mx-auto px-4">
            <img src="assets/damola.jpg" alt="Portrait of Adeyemi Adedamola Felix"
                 class="w-40 h-40 md:w-48 md:h-48 rounded-full object-cover object-top border-4 border-white shadow-lg mx-auto mb-6">
            <h1 class="text-4xl md:text-5xl font-bold mb-4">Adeyemi Adedamola Felix</h1>
            <p class="text-xl md:text-2xl mb-8 font-light text-blue-100">Information Technology Graduate | Network &amp; Systems Enthusiast</p>
            <div class="flex justify-center space-x-6">
                <a href="mailto:adedamola636@gmail.com" class="text-white hover:text-blue-200 transition-colors" aria-label="Email">
                    <i class="fas fa-envelope fa-xl"></i>
                </a>
                <a href="https://www.linkedin.com/in/adeflex" target="_blank" rel="noopener noreferrer" class="text-white hover:text-blue-200 transition-colors" aria-label="LinkedIn">
                    <i class="fab fa-linkedin fa-xl"></i>
                </a>
                <a href="https://github.com/felixp1" target="_blank" rel="noopener noreferrer" class="text-white hover:text-blue-200 transition-colors" aria-label="GitHub">
                    <i class="fab fa-github fa-xl"></i>
                </a>
            </div>
        </div>
    </header>

    <main class="max-w-6xl mx-auto px-4 py-12 space-y-20">

        <!-- 1. ABOUT ME -->
        <section id="about" class="scroll-mt-24">
            <h2 class="text-3xl font-bold border-b-2 border-blue-700 pb-2 mb-6">ABOUT ME</h2>
            <p class="text-lg leading-relaxed text-gray-700">
                Information Technology graduate with hands-on experience in computer networking, IT support, network troubleshooting and data analytics. Practical exposure to routing and switching environments, technical assistance and network security testing. Strong interest in cloud computing, cybersecurity, artificial intelligence and emerging technologies.
            </p>
        </section>

        <!-- 2. WHAT I DO -->
        <section id="what-i-do" class="scroll-mt-24">
            <h2 class="text-3xl font-bold border-b-2 border-blue-700 pb-2 mb-6">WHAT I DO</h2>
            <div class="flex flex-wrap gap-3">
                <span class="bg-blue-50 text-blue-800 px-4 py-2 rounded-lg font-medium border border-blue-100">Computer Networking</span>
                <span class="bg-blue-50 text-blue-800 px-4 py-2 rounded-lg font-medium border border-blue-100">IT Support</span>
                <span class="bg-blue-50 text-blue-800 px-4 py-2 rounded-lg font-medium border border-blue-100">Network Troubleshooting</span>
                <span class="bg-blue-50 text-blue-800 px-4 py-2 rounded-lg font-medium border border-blue-100">SQL &amp; Data Analytics</span>
                <span class="bg-blue-50 text-blue-800 px-4 py-2 rounded-lg font-medium border border-blue-100">React.js &amp; Tailwind CSS</span>
                <span class="bg-blue-50 text-blue-800 px-4 py-2 rounded-lg font-medium border border-blue-100">Python (FastAPI)</span>
                <span class="bg-blue-50 text-blue-800 px-4 py-2 rounded-lg font-medium border border-blue-100">Prompt Engineering</span>
                <span class="bg-blue-50 text-blue-800 px-4 py-2 rounded-lg font-medium border border-blue-100">Technical Documentation</span>
            </div>
        </section>

        <!-- 3. MY PORTFOLIO (experience, education, certifications) -->
        <section id="portfolio" class="scroll-mt-24">
            <h2 class="text-3xl font-bold border-b-2 border-blue-700 pb-2 mb-8">MY PORTFOLIO</h2>

            <h3 class="text-2xl font-semibold text-blue-700 mb-4">Experience</h3>
            <div class="bg-white p-6 rounded-lg shadow-sm border border-gray-100 mb-6">
                <div class="flex flex-col md:flex-row justify-between mb-4">
                    <h4 class="text-xl font-bold text-gray-900">IT Intern</h4>
                    <span class="text-blue-700 font-semibold bg-blue-50 px-3 py-1 rounded-full text-sm self-start mt-2 md:mt-0">May 2025 - Oct 2025</span>
                </div>
                <p class="text-gray-600 font-medium mb-4">National Institute of Information Technology (NIIT)</p>
                <ul class="list-disc list-inside text-gray-700 space-y-2">
                    <li>Simulated enterprise networking environments to validate configurations.</li>
                    <li>Assisted students during networking labs and troubleshooting.</li>
                    <li>Participated in testing network security configurations.</li>
                    <li>Supported routing and switching practical sessions.</li>
                </ul>
            </div>

            <div class="bg-white p-6 rounded-lg shadow-sm border border-gray-100 mb-12">
                <div class="flex flex-col md:flex-row justify-between mb-4">
                    <h4 class="text-xl font-bold text-gray-900">Course Beta Tester (Volunteer)</h4>
                    <span class="text-blue-700 font-semibold bg-blue-50 px-3 py-1 rounded-full text-sm self-start mt-2 md:mt-0">June 2025 - Present</span>
                </div>
                <p class="text-gray-600 font-medium mb-2">Coursera</p>
                <p class="text-gray-700">Reviewing pre-release online course materials in computer science, data science, and information technology to improve the learning experience.</p>
            </div>

            <div class="grid md:grid-cols-2 gap-10">
                <div>
                    <h3 class="text-2xl font-semibold text-blue-700 mb-4">Education</h3>
                    <div class="space-y-6">
                        <div class="bg-white p-5 rounded-lg shadow-sm border border-gray-100">
                            <h4 class="text-lg font-bold text-gray-900">B.Sc. Information Technology</h4>
                            <p class="text-blue-700 font-medium">Redeemer's University</p>
                            <p class="text-gray-500 text-sm mt-1">Oct 2022 - July 2026</p>
                        </div>
                        <div class="bg-white p-5 rounded-lg shadow-sm border border-gray-100">
                            <h4 class="text-lg font-bold text-gray-900">OND, Science Laboratory Technology</h4>
                            <p class="text-blue-700 font-medium">Yaba College of Technology</p>
                            <p class="text-gray-500 text-sm mt-1">2019 - 2022</p>
                        </div>
                    </div>
                </div>

                <div>
                    <h3 class="text-2xl font-semibold text-blue-700 mb-4">Certifications</h3>
                    <ul class="space-y-3">
                        <li class="bg-white p-4 rounded-lg shadow-sm border border-gray-100 flex items-center">
                            <i class="fas fa-shield-alt text-blue-700 mr-3"></i>
                            <span class="text-gray-800 font-medium">Certified in Cybersecurity (ISC2)</span>
                        </li>
                        <li class="bg-white p-4 rounded-lg shadow-sm border border-gray-100 flex items-center">
                            <i class="fas fa-brain text-blue-700 mr-3"></i>
                            <span class="text-gray-800 font-medium">Google AI Essentials</span>
                        </li>
                        <li class="bg-white p-4 rounded-lg shadow-sm border border-gray-100 flex items-center">
                            <i class="fas fa-link text-blue-700 mr-3"></i>
                            <span class="text-gray-800 font-medium">Blockchain Fundamentals (Chainlink)</span>
                        </li>
                        <li class="bg-white p-4 rounded-lg shadow-sm border border-gray-100 flex items-center">
                            <i class="fas fa-certificate text-blue-700 mr-3"></i>
                            <span class="text-gray-800 font-medium">Ethics in AI (University of Helsinki - 2 credits)</span>
                        </li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- 4. PROJECT -->
        <section id="projects" class="scroll-mt-24">
            <h2 class="text-3xl font-bold border-b-2 border-blue-700 pb-2 mb-6">PROJECT</h2>
            <div class="grid md:grid-cols-2 gap-6">
                <div class="bg-white p-6 rounded-lg shadow-sm border-t-4 border-blue-700">
                    <h3 class="text-xl font-bold mb-3 text-gray-900">Mood Detection System</h3>
                    <p class="text-gray-700">Developed a deep learning-based emotion detection application. The project leverages a Convolutional Neural Network trained on large datasets, structured with a React.js/Tailwind CSS frontend and a robust backend database.</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-sm border-t-4 border-blue-700">
                    <h3 class="text-xl font-bold mb-3 text-gray-900">Stable Diffusion 2.0 AI Hackathon</h3>
                    <p class="text-gray-700">Built an AI-powered solution using generative AI methodologies to solve practical visual challenges.</p>
                </div>
            </div>
        </section>

        <!-- 5. CONTACT DETAILS -->
        <section id="contact" class="scroll-mt-24 pb-12">
            <h2 class="text-3xl font-bold border-b-2 border-blue-700 pb-2 mb-6">CONTACT DETAILS</h2>
            <div class="grid sm:grid-cols-2 gap-4">
                <a href="mailto:adedamola636@gmail.com" class="bg-white p-4 rounded-lg shadow-sm border border-gray-100 flex items-center hover:border-blue-700 transition-colors">
                    <i class="fas fa-envelope text-blue-700 mr-3"></i>
                    <span class="text-gray-800 font-medium">adedamola636@gmail.com</span>
                </a>
                <a href="tel:+2348120532169" class="bg-white p-4 rounded-lg shadow-sm border border-gray-100 flex items-center hover:border-blue-700 transition-colors">
                    <i class="fas fa-phone-alt text-blue-700 mr-3"></i>
                    <span class="text-gray-800 font-medium">+234 8120532169</span>
                </a>
                <a href="https://www.linkedin.com/in/adeflex" target="_blank" rel="noopener noreferrer" class="bg-white p-4 rounded-lg shadow-sm border border-gray-100 flex items-center hover:border-blue-700 transition-colors">
                    <i class="fab fa-linkedin text-blue-700 mr-3"></i>
                    <span class="text-gray-800 font-medium">linkedin.com/in/adeflex</span>
                </a>
                <a href="https://github.com/felixp1" target="_blank" rel="noopener noreferrer" class="bg-white p-4 rounded-lg shadow-sm border border-gray-100 flex items-center hover:border-blue-700 transition-colors">
                    <i class="fab fa-github text-blue-700 mr-3"></i>
                    <span class="text-gray-800 font-medium">github.com/felixp1</span>
                </a>
                <div class="bg-white p-4 rounded-lg shadow-sm border border-gray-100 flex items-center sm:col-span-2">
                    <i class="fas fa-map-marker-alt text-blue-700 mr-3"></i>
                    <span class="text-gray-800 font-medium">Lagos, Nigeria</span>
                </div>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="bg-gray-900 text-gray-500 py-6 text-center text-sm">
        &copy; <span id="currentYear"></span> Adeyemi Adedamola Felix. All rights reserved.
    </footer>

    <script src="main.js"></script>
</body>
</html>
