# Full-stack
tack Choice: I used a single-file web app built with HTML, CSS (via CDN) for styling, and Chart.js for simple data-visualization. The AI chatbot is implemented with rule-based logic and contextual memory stored in localStorage.
Run Steps: Open index.html in any modern browser (Chrome, Edge, or Firefox). No build step or backend setup required. Activities and chatbot memory persist using localStorage.
Trade-offs: To ensure zero setup and fast loading, I avoided a backend or package bundler. For a production build, I would modularize the codebase, add tests, and replace the rule-based chatbot with an API-backed LLM.
