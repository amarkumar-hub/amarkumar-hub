import React from "react";
import { Linkedin, Instagram } from "lucide-react";

export default function App() {
  return (
    <div className="min-h-screen bg-gray-50 flex items-center justify-center p-6">
      <div className="bg-white shadow-xl rounded-3xl p-8 max-w-lg w-full text-center">

        {/* Profile Image */}
        <img
          src="https://github.com/amarkumar-hub/amarkumar-hub/blob/main/IMG_0426.jpeg?raw=true"
          alt="Amar Kumar"
          className="w-40 h-40 rounded-full mx-auto object-cover shadow-md"
        />

        {/* Name */}
        <h1 className="text-3xl font-bold mt-4">Amar Kumar</h1>
        <p className="text-gray-600 mt-2">
          Web Developer • Frontend Designer • React Learner
        </p>

        {/* Connect With Me */}
        <h2 className="text-xl font-semibold mt-6">Connect With Me</h2>

        <div className="flex justify-center gap-6 mt-4">
          {/* LinkedIn */}
          <a
            href="https://www.linkedin.com/in/amarkumar-hub"
            target="_blank"
            className="hover:scale-110 transition"
          >
            <Linkedin size={34} />
          </a>

          {/* Instagram */}
          <a
            href="https://www.instagram.com/amarsingh_24"
            target="_blank"
            className="hover:scale-110 transition"
          >
            <Instagram size={34} />
          </a>
        </div>

        {/* About */}
        <p className="text-gray-700 mt-6 leading-relaxed">
          I build simple, fast, and responsive websites using HTML, CSS, 
          JavaScript, and React. Passionate about UI/UX and modern web 
          designs. Always learning & improving.
        </p>

        {/* Footer */}
        <p className="text-gray-400 text-sm mt-6">© 2025 Amar Kumar</p>
      </div>
    </div>
  );
}
