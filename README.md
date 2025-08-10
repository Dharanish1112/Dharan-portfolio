# Dharan-portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dharanish S - Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');
        
        * {
            font-family: 'Poppins', sans-serif;
        }
        
        .gradient-bg {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        }
        
        .card-hover {
            transition: all 0.3s ease;
        }
        
        .card-hover:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
        }
        
        .float-animation {
            animation: float 6s ease-in-out infinite;
        }
        
        @keyframes float {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-20px); }
            100% { transform: translateY(0px); }
        }
        
        .fade-in {
            animation: fadeIn 1s ease-in;
        }
        
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        .skill-bar {
            animation: fillBar 2s ease-in-out;
        }
        
        @keyframes fillBar {
            from { width: 0%; }
        }
        
        .profile-image {
            background: linear-gradient(45deg, #667eea, #764ba2);
            padding: 4px;
            border-radius: 50%;
            animation: pulse 2s infinite;
        }
        
        @keyframes pulse {
            0% { box-shadow: 0 0 0 0 rgba(102, 126, 234, 0.7); }
            70% { box-shadow: 0 0 0 10px rgba(102, 126, 234, 0); }
            100% { box-shadow: 0 0 0 0 rgba(102, 126, 234, 0); }
        }
        
        .typing-animation {
            overflow: hidden;
            border-right: 3px solid #667eea;
            white-space: nowrap;
            animation: typing 3s steps(40, end), blink-caret 0.75s step-end infinite;
        }
        
        @keyframes typing {
            from { width: 0; }
            to { width: 100%; }
        }
        
        @keyframes blink-caret {
            from, to { border-color: transparent; }
            50% { border-color: #667eea; }
        }
        
        .social-icon {
            transition: all 0.3s ease;
        }
        
        .social-icon:hover {
            transform: scale(1.2) rotate(5deg);
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Navigation -->
    <nav class="fixed top-0 w-full bg-white/90 backdrop-blur-md z-50 shadow-sm">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center py-4">
                <div class="text-2xl font-bold gradient-bg bg-clip-text text-transparent">
                    Dharanish S
                </div>
                <div class="hidden md:flex space-x-8">
                    <a href="#home" class="text-gray-700 hover:text-purple-600 transition-colors">Home</a>
                    <a href="#about" class="text-gray-700 hover:text-purple-600 transition-colors">About</a>
                    <a href="#skills" class="text-gray-700 hover:text-purple-600 transition-colors">Skills</a>
                    <a href="#experience" class="text-gray-700 hover:text-purple-600 transition-colors">Experience</a>
                    <a href="#projects" class="text-gray-700 hover:text-purple-600 transition-colors">Projects</a>
                    <a href="#contact" class="text-gray-700 hover:text-purple-600 transition-colors">Contact</a>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="min-h-screen gradient-bg flex items-center justify-center pt-20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <div class="fade-in">
                <div class="profile-image w-48 h-48 mx-auto mb-8 float-animation">
                    <div class="w-full h-full bg-white rounded-full flex items-center justify-center">
                        <div class="w-40 h-40 bg-gradient-to-br from-purple-400 to-blue-500 rounded-full flex items-center justify-center text-white text-6xl font-bold">
                            DS
                        </div>
                    </div>
                </div>
                <h1 class="text-5xl md:text-7xl font-bold text-white mb-4">
                    Hi, I'm <span class="typing-animation">Dharanish S</span>
                </h1>
                <p class="text-xl md:text-2xl text-white/90 mb-8">
                    BE CSE (AI/ML) Student | UI/UX Designer | Frontend Developer
                </p>
                <div class="flex justify-center space-x-6 mb-8">
                    <a href="https://www.linkedin.com/in/dharanish-s-b3b7262a4 " target="_blank" class="social-icon bg-white/20 p-4 rounded-full text-white hover:bg-white hover:text-purple-600">
                        <i class="fab fa-linkedin-in text-2xl"></i>
                    </a>
                    <a href="https://wa.me/919843742866" target="_blank" class="social-icon bg-white/20 p-4 rounded-full text-white hover:bg-green-500">
                        <i class="fab fa-whatsapp text-2xl"></i>
                    </a>
                    <a href="mailto:dharanish1112@gmail.com" class="social-icon bg-white/20 p-4 rounded-full text-white hover:bg-red-500">
                        <i class="fas fa-envelope text-2xl"></i>
                    </a>
                </div>
                <a href="#about" class="inline-block bg-white text-purple-600 px-8 py-3 rounded-full font-semibold hover:bg-purple-100 transition-colors">
                    Learn More About Me
                </a>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold text-gray-900 mb-4">About Me</h2>
                <div class="w-24 h-1 gradient-bg mx-auto rounded-full"></div>
            </div>
            <div class="grid md:grid-cols-2 gap-12 items-center">
                <div class="fade-in">
                    <h3 class="text-2xl font-semibold text-gray-900 mb-6">
                        Passionate Designer & Developer
                    </h3>
                    <p class="text-gray-600 mb-6 leading-relaxed">
                        I'm Dharanish S, currently pursuing BE in Computer Science Engineering with specialization in AI/ML at KRCE. 
                        I'm passionate about creating beautiful, functional digital experiences that solve real-world problems.
                    </p>
                    <p class="text-gray-600 mb-6 leading-relaxed">
                        With expertise in frontend web development, UI/UX design, video editing, 3D animation, and machine learning, 
                        I bring a unique blend of technical skills and creative vision to every project.
                    </p>
                    <p class="text-gray-600 mb-8 leading-relaxed">
                        I'm certified in Machine Learning with 96% score from Internshala and have completed multiple internships 
                        that have shaped my professional journey.
                    </p>
                    <div class="flex flex-wrap gap-4">
                        <span class="bg-purple-100 text-purple-800 px-4 py-2 rounded-full text-sm font-medium">AI/ML Enthusiast</span>
                        <span class="bg-blue-100 text-blue-800 px-4 py-2 rounded-full text-sm font-medium">UI/UX Designer</span>
                        <span class="bg-green-100 text-green-800 px-4 py-2 rounded-full text-sm font-medium">Frontend Developer</span>
                    </div>
                </div>
                <div class="text-center">
                    <div class="bg-gradient-to-br from-purple-400 to-blue-500 p-8 rounded-2xl text-white">
                        <div class="grid grid-cols-2 gap-6">
                            <div>
                                <div class="text-3xl font-bold">3+</div>
                                <div class="text-sm opacity-90">Internships</div>
                            </div>
                            <div>
                                <div class="text-3xl font-bold">96%</div>
                                <div class="text-sm opacity-90">ML Certification</div>
                            </div>
                            <div>
                                <div class="text-3xl font-bold">10+</div>
                                <div class="text-sm opacity-90">Tools Mastered</div>
                            </div>
                            <div>
                                <div class="text-3xl font-bold">∞</div>
                                <div class="text-sm opacity-90">Creativity</div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold text-gray-900 mb-4">Skills & Tools</h2>
                <div class="w-24 h-1 gradient-bg mx-auto rounded-full"></div>
            </div>
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Design Skills -->
                <div class="bg-white p-8 rounded-2xl shadow-lg card-hover">
                    <div class="text-center mb-6">
                        <div class="w-16 h-16 gradient-bg rounded-full flex items-center justify-center mx-auto mb-4">
                            <i class="fas fa-palette text-white text-2xl"></i>
                        </div>
                        <h3 class="text-xl font-semibold text-gray-900">Design</h3>
                    </div>
                    <div class="space-y-4">
                        <div>
                            <div class="flex justify-between mb-2">
                                <span class="text-sm font-medium text-gray-700">UI/UX Design</span>
                                <span class="text-sm text-gray-500">90%</span>
                            </div>
                            <div class="w-full bg-gray-200 rounded-full h-2">
                                <div class="skill-bar bg-gradient-to-r from-purple-500 to-blue-500 h-2 rounded-full" style="width: 90%"></div>
                            </div>
                        </div>
                        <div>
                            <div class="flex justify-between mb-2">
                                <span class="text-sm font-medium text-gray-700">Logo Design</span>
                                <span class="text-sm text-gray-500">85%</span>
                            </div>
                            <div class="w-full bg-gray-200 rounded-full h-2">
                                <div class="skill-bar bg-gradient-to-r from-purple-500 to-blue-500 h-2 rounded-full" style="width: 85%"></div>
                            </div>
                        </div>
                        <div>
                            <div class="flex justify-between mb-2">
                                <span class="text-sm font-medium text-gray-700">Poster Making</span>
                                <span class="text-sm text-gray-500">88%</span>
                            </div>
                            <div class="w-full bg-gray-200 rounded-full h-2">
                                <div class="skill-bar bg-gradient-to-r from-purple-500 to-blue-500 h-2 rounded-full" style="width: 88%"></div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Development Skills -->
                <div class="bg-white p-8 rounded-2xl shadow-lg card-hover">
                    <div class="text-center mb-6">
                        <div class="w-16 h-16 gradient-bg rounded-full flex items-center justify-center mx-auto mb-4">
                            <i class="fas fa-code text-white text-2xl"></i>
                        </div>
                        <h3 class="text-xl font-semibold text-gray-900">Development</h3>
                    </div>
                    <div class="space-y-4">
                        <div>
                            <div class="flex justify-between mb-2">
                                <span class="text-sm font-medium text-gray-700">Frontend Web Design</span>
                                <span class="text-sm text-gray-500">92%</span>
                            </div>
                            <div class="w-full bg-gray-200 rounded-full h-2">
                                <div class="skill-bar bg-gradient-to-r from-green-500 to-blue-500 h-2 rounded-full" style="width: 92%"></div>
                            </div>
                        </div>
                        <div>
                            <div class="flex justify-between mb-2">
                                <span class="text-sm font-medium text-gray-700">Machine Learning</span>
                                <span class="text-sm text-gray-500">96%</span>
                            </div>
                            <div class="w-full bg-gray-200 rounded-full h-2">
                                <div class="skill-bar bg-gradient-to-r from-green-500 to-blue-500 h-2 rounded-full" style="width: 96%"></div>
                            </div>
                        </div>
                        <div>
                            <div class="flex justify-between mb-2">
                                <span class="text-sm font-medium text-gray-700">Data Analysis</span>
                                <span class="text-sm text-gray-500">80%</span>
                            </div>
                            <div class="w-full bg-gray-200 rounded-full h-2">
                                <div class="skill-bar bg-gradient-to-r from-green-500 to-blue-500 h-2 rounded-full" style="width: 80%"></div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Media Skills -->
                <div class="bg-white p-8 rounded-2xl shadow-lg card-hover">
                    <div class="text-center mb-6">
                        <div class="w-16 h-16 gradient-bg rounded-full flex items-center justify-center mx-auto mb-4">
                            <i class="fas fa-video text-white text-2xl"></i>
                        </div>
                        <h3 class="text-xl font-semibold text-gray-900">Media</h3>
                    </div>
                    <div class="space-y-4">
                        <div>
                            <div class="flex justify-between mb-2">
                                <span class="text-sm font-medium text-gray-700">Video Editing</span>
                                <span class="text-sm text-gray-500">87%</span>
                            </div>
                            <div class="w-full bg-gray-200 rounded-full h-2">
                                <div class="skill-bar bg-gradient-to-r from-red-500 to-pink-500 h-2 rounded-full" style="width: 87%"></div>
                            </div>
                        </div>
                        <div>
                            <div class="flex justify-between mb-2">
                                <span class="text-sm font-medium text-gray-700">3D Animation</span>
                                <span class="text-sm text-gray-500">75%</span>
                            </div>
                            <div class="w-full bg-gray-200 rounded-full h-2">
                                <div class="skill-bar bg-gradient-to-r from-red-500 to-pink-500 h-2 rounded-full" style="width: 75%"></div>
                            </div>
                        </div>
                        <div>
                            <div class="flex justify-between mb-2">
                                <span class="text-sm font-medium text-gray-700">Motion Graphics</span>
                                <span class="text-sm text-gray-500">82%</span>
                            </div>
                            <div class="w-full bg-gray-200 rounded-full h-2">
                                <div class="skill-bar bg-gradient-to-r from-red-500 to-pink-500 h-2 rounded-full" style="width: 82%"></div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Tools Section -->
            <div class="mt-16">
                <h3 class="text-2xl font-semibold text-center text-gray-900 mb-8">Tools I Use</h3>
                <div class="flex flex-wrap justify-center gap-6">
                    <div class="bg-white p-4 rounded-xl shadow-md card-hover">
                        <i class="fab fa-figma text-3xl text-purple-600 mb-2"></i>
                        <div class="text-sm font-medium text-gray-700">Figma</div>
                    </div>
                    <div class="bg-white p-4 rounded-xl shadow-md card-hover">
                        <i class="fas fa-cube text-3xl text-blue-600 mb-2"></i>
                        <div class="text-sm font-medium text-gray-700">Framer</div>
                    </div>
                    <div class="bg-white p-4 rounded-xl shadow-md card-hover">
                        <i class="fas fa-palette text-3xl text-green-600 mb-2"></i>
                        <div class="text-sm font-medium text-gray-700">Canva</div>
                    </div>
                    <div class="bg-white p-4 rounded-xl shadow-md card-hover">
                        <i class="fas fa-cut text-3xl text-red-600 mb-2"></i>
                        <div class="text-sm font-medium text-gray-700">CapCut</div>
                    </div>
                    <div class="bg-white p-4 rounded-xl shadow-md card-hover">
                        <i class="fas fa-chart-bar text-3xl text-yellow-600 mb-2"></i>
                        <div class="text-sm font-medium text-gray-700">Power BI</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Experience Section -->
    <section id="experience" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold text-gray-900 mb-4">Experience</h2>
                <div class="w-24 h-1 gradient-bg mx-auto rounded-full"></div>
            </div>
            <div class="space-y-8">
                <!-- Experience 1 -->
                <div class="bg-gradient-to-r from-purple-50 to-blue-50 p-8 rounded-2xl card-hover">
                    <div class="flex flex-col md:flex-row md:items-center md:justify-between">
                        <div class="flex-1">
                            <h3 class="text-xl font-semibold text-gray-900 mb-2">UI/UX Design Intern</h3>
                            <p class="text-purple-600 font-medium mb-2">Skill Craft Technology</p>
                            <p class="text-gray-600 mb-4">1 Month • Remote</p>
                            <p class="text-gray-700">
                                Designed user interfaces and experiences for web applications, created wireframes and prototypes, 
                                and collaborated with development teams to implement design solutions.
                            </p>
                        </div>
                        <div class="mt-4 md:mt-0 md:ml-8">
                            <div class="bg-white p-4 rounded-xl shadow-md">
                                <i class="fas fa-mobile-alt text-3xl text-purple-600"></i>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Experience 2 -->
                <div class="bg-gradient-to-r from-blue-50 to-green-50 p-8 rounded-2xl card-hover">
                    <div class="flex flex-col md:flex-row md:items-center md:justify-between">
                        <div class="flex-1">
                            <h3 class="text-xl font-semibold text-gray-900 mb-2">UI/UX Design Intern</h3>
                            <p class="text-blue-600 font-medium mb-2">CodSoft</p>
                            <p class="text-gray-600 mb-4">1 Month • Remote</p>
                            <p class="text-gray-700">
                                Focused on user research, created design systems, and developed responsive web designs. 
                                Gained experience in user testing and iterative design processes.
                            </p>
                        </div>
                        <div class="mt-4 md:mt-0 md:ml-8">
                            <div class="bg-white p-4 rounded-xl shadow-md">
                                <i class="fas fa-paint-brush text-3xl text-blue-600"></i>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Experience 3 -->
                <div class="bg-gradient-to-r from-green-50 to-yellow-50 p-8 rounded-2xl card-hover">
                    <div class="flex flex-col md:flex-row md:items-center md:justify-between">
                        <div class="flex-1">
                            <h3 class="text-xl font-semibold text-gray-900 mb-2">Web Development Intern</h3>
                            <p class="text-green-600 font-medium mb-2">EduExpose</p>
                            <p class="text-gray-600 mb-4">2 Months • Remote</p>
                            <p class="text-gray-700">
                                Developed responsive websites using modern frontend technologies, implemented interactive features, 
                                and optimized web performance. Worked on multiple client projects.
                            </p>
                        </div>
                        <div class="mt-4 md:mt-0 md:ml-8">
                            <div class="bg-white p-4 rounded-xl shadow-md">
                                <i class="fas fa-code text-3xl text-green-600"></i>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Certification -->
                <div class="bg-gradient-to-r from-yellow-50 to-red-50 p-8 rounded-2xl card-hover">
                    <div class="flex flex-col md:flex-row md:items-center md:justify-between">
                        <div class="flex-1">
                            <h3 class="text-xl font-semibold text-gray-900 mb-2">Machine Learning Certification</h3>
                            <p class="text-yellow-600 font-medium mb-2">Internshala</p>
                            <p class="text-gray-600 mb-4">Score: 96% • Online Course</p>
                            <p class="text-gray-700">
                                Completed comprehensive machine learning course covering algorithms, data preprocessing, 
                                model evaluation, and practical implementation using Python and popular ML libraries.
                            </p>
                        </div>
                        <div class="mt-4 md:mt-0 md:ml-8">
                            <div class="bg-white p-4 rounded-xl shadow-md">
                                <i class="fas fa-brain text-3xl text-yellow-600"></i>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold text-gray-900 mb-4">My Projects</h2>
                <div class="w-24 h-1 gradient-bg mx-auto rounded-full"></div>
                <p class="text-gray-600 mt-4">Check out my Figma projects and design work</p>
            </div>
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Project placeholders - you can add your actual Figma project links -->
                <div class="bg-white rounded-2xl shadow-lg overflow-hidden card-hover">
                    <div class="h-48 bg-gradient-to-br from-purple-400 to-blue-500 flex items-center justify-center">
                        <i class="fab fa-figma text-white text-6xl"></i>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-semibold text-gray-900 mb-2">UI/UX Project 1</h3>
                        <p class="text-gray-600 mb-4">Mobile app design with modern interface and smooth user experience.</p>
                        <a href="#" class="inline-flex items-center text-purple-600 hover:text-purple-800 font-medium">
                            View on Figma <i class="fas fa-external-link-alt ml-2"></i>
                        </a>
                    </div>
                </div>

                <div class="bg-white rounded-2xl shadow-lg overflow-hidden card-hover">
                    <div class="h-48 bg-gradient-to-br from-green-400 to-blue-500 flex items-center justify-center">
                        <i class="fas fa-desktop text-white text-6xl"></i>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-semibold text-gray-900 mb-2">Web Design Project</h3>
                        <p class="text-gray-600 mb-4">Responsive website design with clean aesthetics and intuitive navigation.</p>
                        <a href="#" class="inline-flex items-center text-purple-600 hover:text-purple-800 font-medium">
                            View on Figma <i class="fas fa-external-link-alt ml-2"></i>
                        </a>
                    </div>
                </div>

                <div class="bg-white rounded-2xl shadow-lg overflow-hidden card-hover">
                    <div class="h-48 bg-gradient-to-br from-red-400 to-pink-500 flex items-center justify-center">
                        <i class="fas fa-palette text-white text-6xl"></i>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-semibold text-gray-900 mb-2">Brand Identity</h3>
                        <p class="text-gray-600 mb-4">Complete brand identity design including logo, colors, and typography.</p>
                        <a href="#" class="inline-flex items-center text-purple-600 hover:text-purple-800 font-medium">
                            View on Figma <i class="fas fa-external-link-alt ml-2"></i>
                        </a>
                    </div>
                </div>
            </div>
            <div class="text-center mt-12">
                <p class="text-gray-600 mb-4">Want to see more of my work?</p>
                <a href="https://figma.com/@dharanish" target="_blank" class="inline-block bg-purple-600 text-white px-8 py-3 rounded-full font-semibold hover:bg-purple-700 transition-colors">
                    Visit My Figma Profile
                </a>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 gradient-bg">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold text-white mb-4">Let's Connect</h2>
                <div class="w-24 h-1 bg-white mx-auto rounded-full"></div>
                <p class="text-white/90 mt-4">Ready to work together? Let's create something amazing!</p>
            </div>
            <div class="grid md:grid-cols-2 gap-12 items-center">
                <div class="text-white">
                    <h3 class="text-2xl font-semibold mb-6">Get In Touch</h3>
                    <div class="space-y-6">
                        <div class="flex items-center space-x-4">
                            <div class="w-12 h-12 bg-white/20 rounded-full flex items-center justify-center">
                                <i class="fas fa-phone text-white"></i>
                            </div>
                            <div>
                                <p class="font-medium">Phone</p>
                                <a href="tel:+919843742866" class="text-white/90 hover:text-white">+91 98437 42866</a>
                            </div>
                        </div>
                        <div class="flex items-center space-x-4">
                            <div class="w-12 h-12 bg-white/20 rounded-full flex items-center justify-center">
                                <i class="fas fa-envelope text-white"></i>
                            </div>
                            <div>
                                <p class="font-medium">Email</p>
                                <a href="mailto:dharanish.s@example.com" class="text-white/90 hover:text-white">dharanish.s@example.com</a>
                            </div>
                        </div>
                        <div class="flex items-center space-x-4">
                            <div class="w-12 h-12 bg-white/20 rounded-full flex items-center justify-center">
                                <i class="fas fa-map-marker-alt text-white"></i>
                            </div>
                            <div>
                                <p class="font-medium">Location</p>
                                <p class="text-white/90">Tamil Nadu, India</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="bg-white/10 backdrop-blur-md p-8 rounded-2xl">
                    <h3 class="text-2xl font-semibold text-white mb-6">Quick Contact</h3>
                    <div class="grid grid-cols-2 gap-4 mb-6">
                        <a href="https://wa.me/919843742866?text=Hi%20Dharanish,%20I%20saw%20your%20portfolio%20and%20would%20like%20to%20connect!" 
                           target="_blank" 
                           class="bg-green-500 hover:bg-green-600 text-white p-4 rounded-xl text-center transition-colors card-hover">
                            <i class="fab fa-whatsapp text-2xl mb-2"></i>
                            <div class="text-sm font-medium">WhatsApp</div>
                        </a>
                        <a href="https://www.linkedin.com/in/dharanish-s-b3b7262a4 " 
                           target="_blank" 
                           class="bg-blue-600 hover:bg-blue-700 text-white p-4 rounded-xl text-center transition-colors card-hover">
                            <i class="fab fa-linkedin-in text-2xl mb-2"></i>
                            <div class="text-sm font-medium">LinkedIn</div>
                        </a>
                    </div>
                    <a href="mailto:dharanish1112@gmail.com" 
                       class="w-full bg-white/20 hover:bg-white/30 text-white p-4 rounded-xl text-center transition-colors block card-hover">
                        <i class="fas fa-envelope text-xl mr-2"></i>
                        Send Email
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-8">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <p class="text-gray-400">
                © 2024 Dharanish S. Designed with ❤️ for professional excellence.
            </p>
        </div>
    </footer>

    <script>
        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });

        // Add scroll effect to navigation
        window.addEventListener('scroll', function() {
            const nav = document.querySelector('nav');
            if (window.scrollY > 100) {
                nav.classList.add('bg-white/95');
            } else {
                nav.classList.remove('bg-white/95');
            }
        });

        // Animate elements on scroll
        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -50px 0px'
        };

        const observer = new IntersectionObserver(function(entries) {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('fade-in');
                }
            });
        }, observerOptions);

        // Observe all sections
        document.querySelectorAll('section').forEach(section => {
            observer.observe(section);
        });
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'96cfecd055222f6d',t:'MTc1NDgzMzQzNi4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
