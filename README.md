                                                    
# CodeMentor Hub

A platform for developers to share code snippets, access expert guides, and collaborate in teams. Built with Tailwind CSS, Firebase, and Gemini API for AI-driven code reviews.

## Features

- *Explore Snippets*: Browse tagged code in Python, JS, C++, etc.
- *Upload Code*: Share snippets with AI-powered reviews.
- *Guides*: Tutorials with progress tracking.
- *Teams*: Real-time collaboration with Firestore storage.
- *Dashboard*: Manage snippets and settings.
- *Auth*: Firebase login/signup or anonymous access.
- *UI*: Responsive, modern design with Inter font.

## Tech Stack

- HTML, Tailwind CSS, JavaScript
- Firebase (Auth, Firestore)
- Gemini API
- Inter font

## Setup

1. *Clone*:
   bash
   git clone https://github.com/your-username/codementor-hub.git
   cd codementor-hub
   

2. *Firebase Config*:
   - Create a Firebase project, enable Auth (Email/Anonymous) and Firestore.
   - Add config to index.html:
     javascript
     const firebaseConfig = { apiKey: "your-key", ... };
     

3. *Gemini API*:
   - Add API key in index.html:
     javascript
     const apiKey = "your-gemini-key";
     

4. *Run*:
   - Use live-server or open index.html in a browser.

5. *Deploy*:
   - Host on Netlify/Vercel or Firebase Hosting.

## Structure


codementor-hub/
├── index.html
└── README.md


## Contributing

Fork, branch (feature/your-feature), commit, push, and submit a Pull Request.

## License

MIT License

## Team

- Avtar Jassal (Lead), Shreya Mutkule (Dev), Vaishnavi Gade (Design), Karan Bankar (Backend), Om Bhosale (Frontend)
-End
