<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
    </style>
</head>
<body class="bg-pink-50 text-gray-800">
    <!-- Header Section -->
    <header class="bg-white shadow-md">
        <div class="container mx-auto px-4 py-6 flex justify-between items-center">
            <h1 class="text-2xl font-bold">My Portfolio</h1>
            <nav>
                <ul class="flex space-x-6">
                    <li><a href="#about" class="text-gray-600 hover:text-gray-900">About</a></li>
                    <li><a href="#projects" class="text-gray-600 hover:text-gray-900">Projects</a></li>
                    <li><a href="#contact" class="text-gray-600 hover:text-gray-900">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="bg-purple-100 text-gray-800">
        <div class="container mx-auto px-4 py-20 text-center">
            <h2 class="text-4xl font-bold mb-4">Welcome to My Portfolio</h2>
            <p class="text-lg mb-8">Hi, I'm [Your Name], a passionate [Your Profession or Skillset].</p>
            <a href="#projects" class="bg-teal-400 text-white px-6 py-3 rounded-lg text-lg font-semibold hover:bg-teal-500">View My Work</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="bg-white py-20">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-3xl font-bold mb-6">About Me</h2>
            <p class="text-lg text-gray-600">I am a [Your Profession], specializing in [Your Skills/Technologies]. I enjoy creating solutions that make an impact. With a passion for learning and problem-solving, I strive to deliver high-quality work and build great user experiences.</p>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="bg-blue-50 py-20">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold mb-6 text-center">Projects</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Project 1 -->
                <div class="bg-white shadow-md rounded-lg overflow-hidden">
                    <img src="https://via.placeholder.com/400x200" alt="Project 1" class="w-full h-48 object-cover">
                    <div class="p-4">
                        <h3 class="text-xl font-semibold mb-2">Project 1</h3>
                        <p class="text-gray-600">Brief description of the project and what it does.</p>
                    </div>
                </div>
                <!-- Project 2 -->
                <div class="bg-white shadow-md rounded-lg overflow-hidden">
                    <img src="https://via.placeholder.com/400x200" alt="Project 2" class="w-full h-48 object-cover">
                    <div class="p-4">
                        <h3 class="text-xl font-semibold mb-2">Project 2</h3>
                        <p class="text-gray-600">Brief description of the project and what it does.</p>
                    </div>
                </div>
                <!-- Project 3 -->
                <div class="bg-white shadow-md rounded-lg overflow-hidden">
                    <img src="https://via.placeholder.com/400x200" alt="Project 3" class="w-full h-48 object-cover">
                    <div class="p-4">
                        <h3 class="text-xl font-semibold mb-2">Project 3</h3>
                        <p class="text-gray-600">Brief description of the project and what it does.</p>
                    </div>
                </div>
                <!-- Project 4 -->
                <div class="bg-white shadow-md rounded-lg overflow-hidden">
                    <img src="https://via.placeholder.com/400x200" alt="Project 4" class="w-full h-48 object-cover">
                    <div class="p-4">
                        <h3 class="text-xl font-semibold mb-2">Project 4</h3>
                        <p class="text-gray-600">Brief description of the project and what it does.</p>
                    </div>
                </div>
                <!-- Project 5 -->
                <div class="bg-white shadow-md rounded-lg overflow-hidden">
                    <img src="https://via.placeholder.com/400x200" alt="Project 5" class="w-full h-48 object-cover">
                    <div class="p-4">
                        <h3 class="text-xl font-semibold mb-2">Project 5</h3>
                        <p class="text-gray-600">Brief description of the project and what it does.</p>
                    </div>
                </div>
                <!-- Project 6 -->
                <div class="bg-white shadow-md rounded-lg overflow-hidden">
                    <img src="https://via.placeholder.com/400x200" alt="Project 6" class="w-full h-48 object-cover">
                    <div class="p-4">
                        <h3 class="text-xl font-semibold mb-2">Project 6</h3>
                        <p class="text-gray-600">Brief description of the project and what it does.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="bg-white py-20">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-3xl font-bold mb-6">Contact Me</h2>
            <p class="text-lg text-gray-600 mb-6">Feel free to reach out to me via the form below or connect with me on social media.</p>
            <form action="https://formspree.io/f/{your_form_id}" method="POST" class="max-w-xl mx-auto">
                <div class="mb-4">
                    <input type="text" name="name" placeholder="Your Name" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-teal-400">
                </div>
                <div class="mb-4">
                    <input type="email" name="email" placeholder="Your Email" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-teal-400">
                </div>
                <div class="mb-4">
                    <textarea name="message" rows="5" placeholder="Your Message" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-teal-400"></textarea>
                </div>
                <button type="submit" class="bg-teal-400 text-white px-6 py-3 rounded-lg font-semibold hover:bg-teal-500">Send Message</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-purple-100 text-gray-800 py-6">
        <div class="container mx-auto px-4 text-center">
            <p>&copy; 2025 [Your Name]. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
