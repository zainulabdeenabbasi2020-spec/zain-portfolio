<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zain ul Abideen | Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Inter', sans-serif; scroll-behavior: smooth; }
        .glass-card { background: rgba(255, 255, 255, 0.8); backdrop-filter: blur(10px); border: 1px solid rgba(0,0,0,0.05); }
        .skill-tag { transition: all 0.3s ease; }
        .skill-tag:hover { transform: translateY(-3px); background-color: #f3f4f6; }
    </style>
</head>
<body class="bg-white text-gray-900">

    <nav class="fixed w-full z-50 bg-white/80 backdrop-blur-md border-b border-gray-100">
        <div class="max-w-6xl mx-auto px-6 py-4 flex justify-between items-center">
            <span class="font-bold text-xl tracking-tighter">ZA.</span>
            <div class="hidden md:flex space-x-8 text-sm font-medium">
                <a href="#about" class="hover:text-blue-600 transition">About</a>
                <a href="#skills" class="hover:text-blue-600 transition">Skills</a>
                <a href="#experience" class="hover:text-blue-600 transition">Experience</a>
                <a href="#projects" class="hover:text-blue-600 transition">Projects</a>
                <a href="#contact" class="hover:text-blue-600 transition">Contact</a>
            </div>
        </div>
    </nav>

    <section class="pt-32 pb-20 px-6">
        <div class="max-w-6xl mx-auto flex flex-col md:flex-row items-center gap-12">
            <div class="flex-1 space-y-6">
                <h1 class="text-5xl md:text-7xl font-bold leading-tight">Zain ul <br><span class="text-blue-600">Abideen</span></h1>
                <p class="text-xl text-gray-600 max-w-lg">
                    Computer Science student at FAST–NUCES with hands-on experience in mobile app development and teaching assistance. 
                </p>
                <div class="flex gap-4">
                    <a href="#contact" class="bg-black text-white px-8 py-3 rounded-full font-medium hover:bg-gray-800 transition">Contact Me</a>
                    <a href="#" class="border border-gray-200 px-8 py-3 rounded-full font-medium hover:bg-gray-50 transition">Download CV</a>
                </div>
            </div>
            <div class="flex-1 flex justify-center">
                <div class="relative w-72 h-72 md:w-96 md:h-96">
                    <img src="https://i.ibb.co/3ykfL60/image1.jpg" alt="Zain ul Abideen" class="rounded-2xl object-cover w-full h-full shadow-2xl">
                    <div class="absolute -bottom-4 -right-4 bg-blue-600 text-white p-4 rounded-xl shadow-lg">
                        <p class="text-sm font-bold">FAST-NUCES '26</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="about" class="py-20 bg-gray-50">
        <div class="max-w-6xl mx-auto px-6">
            <div class="flex flex-col md:flex-row-reverse items-center gap-16">
                <div class="flex-1 space-y-6">
                    <h2 class="text-3xl font-bold">About Me</h2>
                    <p class="text-gray-600 leading-relaxed">
                        I am currently pursuing my BS in Computer Science at **FAST–NUCES Karachi**. My journey in tech is driven by a strong foundation in core CS principles, including Data Structures, OS, and Software Engineering. 
                    </p>
                    <p class="text-gray-600 leading-relaxed">
                        With professional experience as a **Mobile App Development Intern** at TIERS Limited and academic leadership as a **Teaching Assistant**, I bridge the gap between complex theoretical concepts and real-world application. I am dedicated to growing as a software engineer who builds efficient, scalable solutions.
                    </p>
                </div>
                <div class="flex-1">
                    <img src="https://i.ibb.co/L5N7pWb/image2.jpg" alt="Zain working" class="rounded-2xl shadow-xl grayscale hover:grayscale-0 transition duration-500">
                </div>
            </div>
        </div>
    </section>

    <section id="skills" class="py-20 px-6">
        <div class="max-w-6xl mx-auto">
            <h2 class="text-3xl font-bold mb-12 text-center">Technical Toolbox</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                <div class="p-6 border border-gray-100 rounded-2xl hover:border-blue-200 transition">
                    <h3 class="font-bold mb-4 text-blue-600">Languages</h3>
                    <ul class="space-y-2 text-gray-600">
                        <li>C / C++</li>
                        <li>Python</li>
                        <li>JavaScript</li>
                        <li>Assembly / SQL</li>
                    </ul>
                </div>
                <div class="p-6 border border-gray-100 rounded-2xl hover:border-blue-200 transition">
                    <h3 class="font-bold mb-4 text-blue-600">Web & Mobile</h3>
                    <ul class="space-y-2 text-gray-600">
                        <li>React / Node.js</li>
                        <li>Express.js</li>
                        <li>HTML / CSS</li>
                        <li>App UI Design</li>
                    </ul>
                </div>
                <div class="p-6 border border-gray-100 rounded-2xl hover:border-blue-200 transition">
                    <h3 class="font-bold mb-4 text-blue-600">Databases</h3>
                    <ul class="space-y-2 text-gray-600">
                        <li>Oracle DB</li>
                        <li>MySQL</li>
                        <li>PostgreSQL</li>
                    </ul>
                </div>
                <div class="p-6 border border-gray-100 rounded-2xl hover:border-blue-200 transition">
                    <h3 class="font-bold mb-4 text-blue-600">Core CS</h3>
                    <ul class="space-y-2 text-gray-600">
                        <li>Algorithms (DSA)</li>
                        <li>Operating Systems</li>
                        <li>Multithreading</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <section id="experience" class="py-20 bg-black text-white px-6">
        <div class="max-w-4xl mx-auto">
            <h2 class="text-3xl font-bold mb-12">Professional Experience</h2>
            <div class="space-y-12">
                <div class="border-l-2 border-blue-600 pl-8 relative">
                    <div class="absolute w-4 h-4 bg-blue-600 rounded-full -left-[9px] top-0"></div>
                    <span class="text-blue-400 text-sm font-bold uppercase tracking-widest">2025</span>
                    <h3 class="text-xl font-bold mt-1">Mobile App Development Intern — TIERS Limited</h3>
                    <p class="text-gray-400 mt-2">Designed UI components and implemented core application logic. Optimized performance and conducted rigorous debugging in a professional sprint-based environment.</p>
                </div>
                <div class="border-l-2 border-gray-700 pl-8 relative">
                    <div class="absolute w-4 h-4 bg-gray-700 rounded-full -left-[9px] top-0"></div>
                    <span class="text-gray-500 text-sm font-bold uppercase tracking-widest">Present</span>
                    <h3 class="text-xl font-bold mt-1">Teaching Assistant (Calculus) — FAST–NUCES</h3>
                    <p class="text-gray-400 mt-2">Mentoring undergraduate students, conducting tutorials, and managing grading. Focus on simplifying complex mathematical concepts.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="projects" class="py-20 px-6">
        <div class="max-w-6xl mx-auto">
            <h2 class="text-3xl font-bold mb-12">Selected Projects</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <div class="group bg-gray-50 p-8 rounded-3xl hover:bg-blue-50 transition duration-500">
                    <h3 class="text-2xl font-bold mb-2">Harmic eCommerce</h3>
                    <p class="text-gray-600 mb-4 text-sm uppercase tracking-wider font-semibold">Oracle DB • React • Node.js</p>
                    <p class="text-gray-600">A full-stack fruit and vegetable commerce system with robust database management.</p>
                </div>
                <div class="group bg-gray-50 p-8 rounded-3xl hover:bg-blue-50 transition duration-500">
                    <h3 class="text-2xl font-bold mb-2">City Sprint Metro</h3>
                    <p class="text-gray-600 mb-4 text-sm uppercase tracking-wider font-semibold">Algorithms • C++</p>
                    <p class="text-gray-600">Desktop application utilizing Dijkstra’s Algorithm to calculate the most efficient routes across city metro lines.</p>
                </div>
                <div class="group bg-gray-50 p-8 rounded-3xl hover:bg-blue-50 transition duration-500">
                    <h3 class="text-2xl font-bold mb-2">Bus Management System</h3>
                    <p class="text-gray-600 mb-4 text-sm uppercase tracking-wider font-semibold">C++ • Multithreading</p>
                    <p class="text-gray-600">A complex system demonstrating synchronization and thread management for real-time operations.</p>
                </div>
                <div class="group bg-gray-50 p-8 rounded-3xl hover:bg-blue-50 transition duration-500">
                    <h3 class="text-2xl font-bold mb-2">ATM & Hospital Systems</h3>
                    <p class="text-gray-600 mb-4 text-sm uppercase tracking-wider font-semibold">C • C++ • OOP</p>
                    <p class="text-gray-600">Core logic simulations for financial transactions and healthcare management workflows.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="py-20 bg-gray-50 px-6 text-center">
        <div class="max-w-3xl mx-auto space-y-8">
            <h2 class="text-4xl font-bold">Let's Connect</h2>
            <p class="text-gray-600">Currently looking for new opportunities and collaborations in Karachi or remote.</p>
            <div class="flex flex-col items-center gap-4">
                <a href="mailto:zainulabdeenabbasi2020@gmail.com" class="text-xl font-semibold hover:text-blue-600 transition">zainulabdeenabbasi2020@gmail.com</a>
                <div class="flex gap-6 mt-4">
                    <a href="https://www.linkedin.com/in/zain-ul-abideen-61a7592b5" class="bg-white p-4 rounded-full shadow-sm hover:shadow-md transition">LinkedIn</a>
                    <a href="#" class="bg-white p-4 rounded-full shadow-sm hover:shadow-md transition">GitHub</a>
                </div>
            </div>
        </div>
    </section>

    <footer class="py-10 border-t border-gray-100 text-center text-gray-400 text-sm">
        <p>© 2026 Zain ul Abideen. Built with passion in Karachi.</p>
    </footer>

</body>
</html>
