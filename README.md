✨ Eternal AI ✨
Hello! This is my project, Eternal AI—a beautifully designed, immersive web interface I built to connect with a divine, persona-driven AI. 
The goal was to create a digital sanctuary where users can seek wisdom from different spiritual perspectives in a serene and beautiful environment.



What It Does
I've designed this application to be more than just a chatbot. It's an experience. You can select a persona—like Lord Krishna, Jesus, or a universal "Eternal AI"—and receive answers that are not only insightful but are also in character, often quoting from sacred texts like the Bhagavad Gita or the Bible.

Immersive UI: The interface features a dynamic, celestial particle background and an elegant, responsive layout that feels truly special.
Persona Selection: Choose from multiple divine personas to frame the AI's wisdom.
Authentic Responses: The AI is instructed to answer from the perspective of the chosen persona and quote relevant verses from their associated holy books.
Text-to-Speech Audio: Responses are automatically "preached" aloud, with a simple toggle to turn the audio on or off.
Secure & Modern: The app is built with security in mind. The Google Gemini API key is kept safe on a backend serverless function, never exposed to the public.

Tech Stack

Frontend: HTML, Tailwind CSS, and plain JavaScript for the dynamic visuals and audio.
Backend: Vercel Serverless Functions (Node.js) to securely handle API calls.
API: Google Gemini API.
Deployment: Vercel via GitHub.

How to Deploy

I've set this up for a super simple deployment using Vercel and GitHub.

Push to GitHub: Make sure all the project files (index.html, the /api folder, etc.) are in your GitHub repository.
Import to Vercel: Connect your GitHub account to Vercel and import this repository.
Set Environment Variable: In your Vercel project settings, go to Environment Variables and add your GEMINI_API_KEY. This is the crucial step for security.

Deploy! Vercel will handle the rest. Any time you push a new change to GitHub, Vercel will automatically update the live site.
