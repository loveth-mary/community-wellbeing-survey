📌 Community Well-Being Survey


A multi-page survey designed to collect insights on community well-being, built using HTML and CSS.
The project focuses on creating a structured and user-friendly survey experience with proper validation and clean layout.


🚀 Features

Multi-page survey structure (10 pages)
Form validation using HTML (required)
Controlled navigation using <form> and submit
Clean and responsive layout
Improved input alignment and user experience


⚠️ Challenges & Solutions

1. Form Validation Across Multiple Pages
Problem
Navigation was initially handled using <a> links
Users could skip pages without filling required inputs
Solution
Replaced <a> navigation with <form> and submit buttons
Added required attributes to key fields
Result
Users must complete required fields before proceeding
Improved structure and data integrity
2. Input Alignment Issues
Problem
Global width: 100% affected radio buttons
Caused misalignment and poor UI
Solution
CSS
Copy code
input[type="radio"] {
  width: auto;
}
Result
Proper alignment restored
Cleaner and more professional layout
3. Data Persistence Limitation
Problem
Inputs reset when navigating back between pages
Explanation
Each page is a separate HTML file (no shared state)
Future Solution
Implement JavaScript (e.g., localStorage) to persist user input


📈 What I Learned

Structuring multi-page forms using HTML
Implementing form validation without JavaScript
Debugging CSS conflicts effectively
The importance of finishing projects
Building consistency through practice


🔮 Future Improvements

Add JavaScript for data persistence
Improve user experience across navigation
Connect to backend for real data collection


🌐 Live Demo
👉 https://loveth-mary.github.io/community-wellbeing-survey/

