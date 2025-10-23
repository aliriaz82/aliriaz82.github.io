<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ali Riaz - DevOps & Software CV</title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Load Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        /* Custom font import for a professional look */
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap');
        body {
            font-family: 'Inter', sans-serif;
            background-color: #0F172A; /* Slate 900 */
        }
        /* Custom scrollbar styling */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-thumb {
            background-color: #3B82F6; /* Blue 500 */
            border-radius: 4px;
        }
        ::-webkit-scrollbar-track {
            background-color: #1E293B; /* Slate 800 */
        }
        .section-header {
            border-left: 5px solid #3B82F6; /* Blue 500 for accent */
        }
    </style>
</head>
<body class="text-gray-200 min-h-screen p-4 sm:p-8">

    <div class="max-w-4xl mx-auto space-y-8">
        
        <!-- Header & Contact Information -->
        <header class="bg-slate-800 p-8 rounded-2xl shadow-xl border-t-4 border-blue-500">
            <h1 class="text-5xl font-extrabold text-blue-400 mb-2 tracking-tight">Ali Riaz</h1>
            <p class="text-2xl font-light text-blue-200 mb-6">Computer Science Graduate | DevOps & Software Enthusiast</p>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-4 text-sm font-medium">
                <div class="flex items-center space-x-2 text-gray-300">
                    <i class="fas fa-map-marker-alt text-blue-500"></i>
                    <span>United Kingdom</span>
                </div>
                <div class="flex items-center space-x-2 text-gray-300">
                    <i class="fas fa-phone text-blue-500"></i>
                    <span>07879 199888</span>
                </div>
                <div class="flex items-center space-x-2 text-gray-300">
                    <i class="fas fa-envelope text-blue-500"></i>
                    <a href="mailto:aliriaz.skp@gmail.com" class="hover:text-blue-400 transition">aliriaz.skp@gmail.com</a>
                </div>
            </div>
        </header>

        <!-- Professional Summary -->
        <section class="bg-slate-800 p-6 rounded-xl shadow-lg">
            <h2 class="section-header text-2xl font-semibold pl-4 mb-4 text-blue-400">
                <i class="fas fa-user mr-3"></i>Professional Summary
            </h2>
            <p class="text-gray-300 leading-relaxed">
                Enthusiastic and dedicated Computer Science graduate currently pursuing an MSc in Computer Science in Birmingham. 
                Experienced in **DevOps**, **cloud fundamentals**, and **software development**, with strong skills in <span class="text-blue-300 font-medium">Python, Linux, Docker, and networking</span>. Excellent communicator, quick learner, and a team player, eager to contribute to dynamic IT teams and deliver high-quality technical solutions.
            </p>
        </section>

        <!-- Work Experience -->
        <section class="bg-slate-800 p-6 rounded-xl shadow-lg">
            <h2 class="section-header text-2xl font-semibold pl-4 mb-6 text-blue-400">
                <i class="fas fa-briefcase mr-3"></i>Work Experience
            </h2>
            
            <!-- Eurus Technology -->
            <div class="relative pb-8 md:pl-8 after:content-[''] after:absolute after:top-0 after:left-0 md:after:left-8 after:h-full after:w-0.5 after:bg-slate-700">
                <div class="relative pl-6">
                    <div class="absolute w-3 h-3 bg-blue-500 rounded-full mt-1.5 -left-1.5 md:-left-0.5 border-4 border-slate-800"></div>
                    <div class="flex flex-col md:flex-row justify-between items-start md:items-center mb-1">
                        <h3 class="text-xl font-bold text-gray-100">DevOps Trainee</h3>
                        <span class="text-sm font-medium text-blue-400">01/2024 – 06/2024</span>
                    </div>
                    <p class="text-md text-gray-300 italic mb-3">Eurus Technology, Islamabad, Pakistan</p>
                    <ul class="list-disc list-outside space-y-2 text-gray-300 ml-5">
                        <li>Gained hands-on experience in **Python scripting**, **Linux administration**, and virtual machine deployment.</li>
                        <li>Worked with **Docker** for containerization and managed basic **CI/CD pipelines**.</li>
                        <li>Assisted in deploying applications on **AWS** using serverless services.</li>
                        <li>Supported testing and troubleshooting to ensure smooth software releases.</li>
                        <li>Collaborated closely with developers and IT teams to improve deployment processes.</li>
                    </ul>
                </div>
            </div>

            <!-- Freelance & Academic Projects -->
            <div class="relative pb-0 md:pl-8">
                <div class="relative pl-6">
                    <div class="absolute w-3 h-3 bg-blue-500 rounded-full mt-1.5 -left-1.5 md:-left-0.5 border-4 border-slate-800"></div>
                    <div class="flex flex-col md:flex-row justify-between items-start md:items-center mb-1">
                        <h3 class="text-xl font-bold text-gray-100">Junior IT Support / Developer</h3>
                        <span class="text-sm font-medium text-blue-400">01/2023 – 12/2023</span>
                    </div>
                    <p class="text-md text-gray-300 italic mb-3">Freelance & Academic Projects, Remote / Pakistan</p>
                    <ul class="list-disc list-outside space-y-2 text-gray-300 ml-5">
                        <li>Developed and maintained a Home Service App using **React Native** and **Node.js**.</li>
                        <li>Designed and implemented a School Management System to track student records and attendance.</li>
                        <li>Built small applications like Tic Tac Toe to practice and showcase programming skills.</li>
                        <li>Provided technical support to peers, troubleshooting basic hardware/software issues.</li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- Education -->
        <section class="bg-slate-800 p-6 rounded-xl shadow-lg">
            <h2 class="section-header text-2xl font-semibold pl-4 mb-6 text-blue-400">
                <i class="fas fa-graduation-cap mr-3"></i>Education
            </h2>
            
            <div class="space-y-4">
                <!-- MSc -->
                <div class="flex justify-between flex-wrap p-3 bg-slate-700/50 rounded-lg">
                    <div>
                        <p class="text-lg font-bold">MSc Computer Science</p>
                        <p class="text-sm text-gray-300">University of Law, United Kingdom</p>
                    </div>
                    <span class="text-sm font-medium text-blue-300">02/2025 – Present</span>
                </div>
                <!-- BSCS -->
                <div class="flex justify-between flex-wrap p-3 bg-slate-700/50 rounded-lg">
                    <div>
                        <p class="text-lg font-bold">Bachelor of Science in Computer Science</p>
                        <p class="text-sm text-gray-300">Shaheed Zulfiqar Ali Bhutto Institute of Science and Technology, Islamabad, Pakistan</p>
                    </div>
                    <span class="text-sm font-medium text-blue-300">09/2020 – 07/2024</span>
                </div>
                <!-- Intermediate -->
                <div class="flex justify-between flex-wrap p-3 bg-slate-700/50 rounded-lg">
                    <div>
                        <p class="text-lg font-bold">Intermediate</p>
                        <p class="text-sm text-gray-300">Ideal Group of Colleges, Sheikhupura, Pakistan</p>
                    </div>
                    <span class="text-sm font-medium text-blue-300">05/2018 – 06/2020</span>
                </div>
            </div>
        </section>
        
        <!-- Skills (Two Columns on Desktop) -->
        <div class="grid grid-cols-1 lg:grid-cols-2 gap-8">
            
            <!-- Technical Skills -->
            <section class="bg-slate-800 p-6 rounded-xl shadow-lg h-full">
                <h2 class="section-header text-2xl font-semibold pl-4 mb-4 text-blue-400">
                    <i class="fas fa-code mr-3"></i>Technical Skills
                </h2>
                <ul class="space-y-3">
                    <li class="p-2 bg-slate-700/50 rounded-md"><span class="font-semibold text-blue-300">Programming:</span> Python, Java, C#, Bash, HTML, CSS, JavaScript</li>
                    <li class="p-2 bg-slate-700/50 rounded-md"><span class="font-semibold text-blue-300">DevOps & Cloud:</span> Linux, Docker, AWS fundamentals, CI/CD basics</li>
                    <li class="p-2 bg-slate-700/50 rounded-md"><span class="font-semibold text-blue-300">Web & App Dev:</span> React Native, Node.js, Express</li>
                    <li class="p-2 bg-slate-700/50 rounded-md"><span class="font-semibold text-blue-300">Networking:</span> Troubleshooting</li>
                    <li class="p-2 bg-slate-700/50 rounded-md"><span class="font-semibold text-blue-300">Database & Scripting:</span> Basic SQL, shell scripting</li>
                </ul>
            </section>
            
            <!-- Professional Skills -->
            <section class="bg-slate-800 p-6 rounded-xl shadow-lg h-full">
                <h2 class="section-header text-2xl font-semibold pl-4 mb-4 text-blue-400">
                    <i class="fas fa-lightbulb mr-3"></i>Professional Skills
                </h2>
                <div class="flex flex-wrap gap-2">
                    <span class="bg-blue-600 text-white text-sm font-medium px-4 py-2 rounded-full shadow-md">Effective Communication & Teamwork</span>
                    <span class="bg-blue-600 text-white text-sm font-medium px-4 py-2 rounded-full shadow-md">Problem Solving & Troubleshooting</span>
                    <span class="bg-blue-600 text-white text-sm font-medium px-4 py-2 rounded-full shadow-md">Positive Attitude & Adaptability</span>
                    <span class="bg-blue-600 text-white text-sm font-medium px-4 py-2 rounded-full shadow-md">Customer Relationship & Sales Handling</span>
                    <span class="bg-blue-600 text-white text-sm font-medium px-4 py-2 rounded-full shadow-md">Conflict Resolution & Team Management</span>
                </div>
            </section>
        </div>

        <!-- Personal Projects -->
        <section class="bg-slate-800 p-6 rounded-xl shadow-lg">
            <h2 class="section-header text-2xl font-semibold pl-4 mb-4 text-blue-400">
                <i class="fas fa-rocket mr-3"></i>Personal Projects
            </h2>
            <div class="grid grid-cols-1 sm:grid-cols-3 gap-4">
                <div class="p-4 bg-slate-700/50 rounded-lg border border-slate-700 hover:border-blue-500 transition">
                    <h3 class="font-bold text-gray-100">Home Service App</h3>
                    <p class="text-sm text-gray-400">React Native frontend & Node.js backend.</p>
                </div>
                <div class="p-4 bg-slate-700/50 rounded-lg border border-slate-700 hover:border-blue-500 transition">
                    <h3 class="font-bold text-gray-100">School Management System</h3>
                    <p class="text-sm text-gray-400">Attendance & record-keeping system.</p>
                </div>
                <div class="p-4 bg-slate-700/50 rounded-lg border border-slate-700 hover:border-blue-500 transition">
                    <h3 class="font-bold text-gray-100">Tic Tac Toe Game</h3>
                    <p class="text-sm text-gray-400">Simple entertainment project to showcase skills.</p>
                </div>
            </div>
        </section>

        <!-- Certificates and Languages -->
        <div class="grid grid-cols-1 sm:grid-cols-2 gap-8">
            <!-- Certificates -->
            <section class="bg-slate-800 p-6 rounded-xl shadow-lg">
                <h2 class="section-header text-2xl font-semibold pl-4 mb-4 text-blue-400">
                    <i class="fas fa-award mr-3"></i>Certificates & Recognition
                </h2>
                <div class="p-2 bg-slate-700/50 rounded-md">
                    <p class="font-semibold text-gray-100">Organizer – ZADTechFusion’23</p>
                    <p class="text-sm text-blue-300">12/2023</p>
                </div>
            </section>
            
            <!-- Languages -->
            <section class="bg-slate-800 p-6 rounded-xl shadow-lg">
                <h2 class="section-header text-2xl font-semibold pl-4 mb-4 text-blue-400">
                    <i class="fas fa-language mr-3"></i>Languages
                </h2>
                <ul class="space-y-2 text-gray-300">
                    <li class="flex justify-between"><span class="font-semibold text-blue-300">English:</span> Full Professional Proficiency</li>
                    <li class="flex justify-between"><span class="font-semibold text-blue-300">Urdu:</span> Native</li>
                    <li class="flex justify-between"><span class="font-semibold text-blue-300">Punjabi:</span> Native</li>
                </ul>
            </section>
        </div>

        <!-- Footer (Optional but good practice) -->
        <footer class="text-center text-sm text-gray-500 pt-4 pb-8">
            <p>&copy; 2025 Ali Riaz. Built with Tailwind CSS.</p>
        </footer>
        
    </div>

</body>
</html>
