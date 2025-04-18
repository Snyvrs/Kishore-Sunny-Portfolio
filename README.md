# Kishore-Sunny-Portfolio
import React from 'react';
import { FaGithub, FaLinkedin } from 'react-icons/fa';

export default function Portfolio() {
  return (
    <div className="font-sans bg-gradient-to-br from-indigo-100 via-purple-100 to-pink-100 text-gray-900">
      {/* Hero Section */}
      <section className="min-h-screen flex flex-col justify-center items-center text-center bg-gradient-to-r from-pink-500 to-yellow-500 text-white">
        <h1 className="text-4xl md:text-6xl font-bold mb-4 drop-shadow-lg">Hi, I'm Kishore Sunny</h1>
        <p className="text-xl md:text-2xl mb-6 drop-shadow">Frontend Developer | JavaScript Enthusiast | UI Engineer</p>
        <div className="space-x-4">
          <a href="#projects" className="px-6 py-3 bg-white text-pink-600 font-semibold rounded-full shadow hover:bg-pink-50 transition">View Projects</a>
          <a href="#contact" className="px-6 py-3 border border-white text-white rounded-full hover:bg-white hover:text-pink-600 transition">Contact Me</a>
        </div>
      </section>

      {/* About Section */}
      <section className="py-20 px-6 bg-white text-center">
        <h2 className="text-4xl font-bold text-pink-600 mb-6">About Me</h2>
        <p className="max-w-3xl mx-auto text-lg text-gray-700">
          I'm a frontend developer based in Patna, India, with a strong passion for building performant, accessible, and pixel-perfect web applications. I love working with modern JavaScript frameworks like React and constantly explore new tools and libraries to improve my workflow and user experiences. I also bring a unique edge with my background in client relations and tech sales, bridging communication between users and products.
        </p>
      </section>

      {/* Skills Section */}
      <section className="py-20 px-6 bg-gradient-to-r from-purple-200 to-blue-100 text-center">
        <h2 className="text-4xl font-bold text-purple-700 mb-10">Tech Stack</h2>
        <div className="grid grid-cols-2 md:grid-cols-4 gap-6 max-w-4xl mx-auto text-lg text-gray-800">
          <div className="bg-white p-4 rounded-xl shadow">HTML5</div>
          <div className="bg-white p-4 rounded-xl shadow">CSS3 / Tailwind CSS</div>
          <div className="bg-white p-4 rounded-xl shadow">JavaScript (ES6+)</div>
          <div className="bg-white p-4 rounded-xl shadow">React.js</div>
          <div className="bg-white p-4 rounded-xl shadow">AJAX / REST APIs</div>
          <div className="bg-white p-4 rounded-xl shadow">Git / GitHub</div>
          <div className="bg-white p-4 rounded-xl shadow">Salesforce CRM</div>
          <div className="bg-white p-4 rounded-xl shadow">Python, C, C++</div>
        </div>
      </section>

      {/* Projects Section */}
      <section id="projects" className="py-20 px-6 bg-white text-center">
        <h2 className="text-4xl font-bold text-pink-600 mb-10">Projects</h2>
        <div className="grid gap-10 md:grid-cols-2 max-w-5xl mx-auto">
          <div className="bg-pink-50 rounded-2xl shadow-xl p-6 border border-pink-200">
            <h3 className="text-2xl font-semibold mb-2 text-pink-700">Attendance Management WebApp</h3>
            <p className="mb-4 text-gray-700">A responsive full-stack web application for managing student attendance efficiently using modern web technologies.</p>
            <a href="https://attendance-management-webapp.netlify.app/" className="text-pink-600 underline font-medium">Live Demo</a>
          </div>
          <div className="bg-pink-50 rounded-2xl shadow-xl p-6 border border-pink-200">
            <h3 className="text-2xl font-semibold mb-2 text-pink-700">Ecommerce WebApp UI</h3>
            <p className="mb-4 text-gray-700">A high-fidelity ecommerce UI built with clean code structure and responsive design principles. Ideal for prototyping real-world shopping experiences.</p>
            <a href="https://tech-cart.netlify.app/" className="text-pink-600 underline font-medium">Live Demo</a>
          </div>
        </div>
      </section>

      {/* Contact Section */}
      <section id="contact" className="py-20 px-6 bg-gradient-to-br from-yellow-200 via-pink-100 to-purple-200 text-center">
        <h2 className="text-4xl font-bold text-purple-700 mb-6">Let's Connect</h2>
        <p className="mb-6 text-lg text-gray-800">Have a project in mind or want to collaborate on a tech idea? Drop a message!</p>
        <div className="flex justify-center space-x-6 mb-6 text-pink-700">
          <a href="mailto:kishore768sunny@gmail.com" className="hover:underline">kishore768sunny@gmail.com</a>
          <span>|</span>
          <a href="tel:+919608662411" className="hover:underline">+91 9608662411</a>
        </div>
        <div className="flex justify-center space-x-6 text-purple-700">
          <a href="https://github.com/Snyvrs" target="_blank" rel="noopener noreferrer"><FaGithub size={30} /></a>
          <a href="https://linkedin.com/in/kishore-sunny" target="_blank" rel="noopener noreferrer"><FaLinkedin size={30} /></a>
        </div>
      </section>

      {/* Footer */}
      <footer className="py-6 bg-white text-center text-sm text-gray-600">
        © {new Date().getFullYear()} Kishore Sunny. Built with 💖 using React & Tailwind CSS.
      </footer>
    </div>
  );
}
