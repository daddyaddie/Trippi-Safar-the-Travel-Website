Trippi safar:

<img width="1807" height="935" alt="Screenshot 2025-08-25 071353" src="https://github.com/user-attachments/assets/d67623ad-109d-4181-9a8a-92e4417b867b" />



<img width="1849" height="939" alt="Screenshot 2025-08-25 071315" src="https://github.com/user-attachments/assets/b001f693-5a2a-427c-b0e1-5cb838e63136" />









Trippi-Planner 🧳
A smart travel planner that generates personalized itineraries using the Gemini API. Built with React, Tailwind CSS, and modern ES Modules—no build tools requir

https://github.com/user-attachments/assets/5bfe43ed-331d-4864-aee8-8cc128a8b716

ed.


🚀 Prerequisites
Modern browser (Chrome, Firefox, Edge, Safari)

Visual Studio Code (recommended)

Node.js & npm (for local server only)

 Setup Instructions
1. Clone & Organize
Place all project files in a folder like /trippi-planner. Key files include:

/trippi-planner
|-- /components
|   |-- /icons
|   |-- ... (other component files)
|-- /services
|   |-- geminiService.ts
|-- App.tsx
|-- constants.ts
|-- index.html
|-- index.tsx
|-- metadata.json
|-- types.ts
|-- (and all other files)

2. Add API Keys
Create env.js in the root:
Google Gemini API (@google/genai)
OpenAI DALL-E 3 API

// env.js
window.process = {
  env: {
    // Replace with your actual Google Gemini API key
    API_KEY: 'YOUR_GEMINI_API_KEY_HERE',

    // Replace with your actual OpenAI API key (used for image fallback)
    OPENAI_API_KEY: 'YOUR_OPENAI_API_KEY_HERE'
  }
};

Update index.html:


<!-- index.html -->

<!-- ... inside the <body> tag ... -->
    <div id="root"></div>

    <!-- ADD THIS LINE -->
    <script src="/env.js"></script>

    <script type="module" src="/index.tsx"></script>
  </body>
</html>

3. Start Local Server
bash
cd path/to/trippi-planner
npm install
npx http-server .
4. Launch App
Visit http://localhost:8080 in your browser to start planning your dream trip.



<img width="1257" height="1022" alt="Screenshot 2025-08-25 074159" src="https://github.com/user-attachments/assets/5cbce980-a1ec-4fe4-a090-523d0412dde7" />
<img width="1219" height="1034" alt="Screenshot 2025-08-25 074143" src="https://github.com/user-attachments/assets/1df0dbcf-1f47-4027-9a3e-5b09c49e10c9" />
<img width="1053" height="954" alt="Screenshot 2025-08-25 074118" src="https://github.com/user-attachments/assets/71e17f5d-2e4d-4dc5-aead-510ba63fb4c8" />
<img width="1365" height="1000" alt="Screenshot 2025-08-25 074054" src="https://github.com/user-attachments/assets/025494ab-1e02-44fa-8a7c-bde3965ad172" />
 



