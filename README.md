Capstone Frontend Development Plan (1 Week)
Project Title: SkinCare Companion – A Personalized Skin Routine Tracker
 Type: Frontend Only (React + Vite + Tailwind CSS)
 Duration: 7 Days
 Focus: UI/UX, State Management, Routing, Responsive Design, Local Storage

Day 1 – Project Setup & Planning
Objectives:
Finalize the project idea and feature scope.


Create low-fidelity wireframes using Figma to visualize:


Landing Page


Skin Type Quiz Page


Result/Recommendation Page


Daily Routine Tracker Page


Education Hub Page


Set up project environment:


Initialize React app using Vite


Install required dependencies: TailwindCSS, React Router, React Icons


Configure Tailwind with PostCSS


Organize project folder structure:


/src/components/ – reusable components


/src/pages/ – distinct app pages


/src/styles/ – styling files if needed


Push initial setup to a GitHub repository.
Day 2 – Landing Page + Navigation
Objectives:
Build a visually clean and modern Landing Page:


Welcome message, benefits of skincare tracking


CTA button: “Start Assessment”


Set up React Router:


Route: / → Landing Page


Route: /quiz → Skin Assessment Quiz


Other routes: /results, /tracker, /education


Build a Navbar component for navigating between pages.


Make the Landing Page fully responsive using Tailwind.


Day 3 – Skin Assessment Quiz Functionality
Objectives:
Develop a multi-step Skin Assessment Quiz:


Questions based on common skincare needs (e.g., dryness, oiliness, sensitivity)


Use useState to capture and update quiz responses.


Add a progress indicator for user clarity.


Implement logic to determine skin type based on answers.


Navigate to /results upon completion and pass results via props, context, or local state.


Ensure quiz layout is fully responsive.


Day 4 – Display Recommendations Page
Objectives:
Build a dynamic Results Page:


Display identified skin type
Recommend a skincare routine (morning/evening)


Organize recommendations in a card/grid layout.


Add basic animations or transitions for visual appeal.


Store the quiz result in localStorage to retain across sessions.


Include a CTA to proceed to the Routine Tracker page.


Day 5 – Routine Tracker Functionality
Objectives:
Create a routine tracking interface:


List skincare steps with checkboxes/toggles


Separate sections for Morning and Night routines


Use useState and localStorage to maintain tracking state even after refresh.


Display completion status or percentage (optional).


Provide a “Reset Routine” option.


Ensure responsiveness and accessibility across devices.


Day 6 – Education Hub + UI Polish
Objectives:
Build an Education Hub Page:


Grid of tip cards or article links on skincare topics


Optional filters based on skin types or categories


Refine all components and pages:


Consistent spacing, fonts, and color themes


Interactive hover effects and smooth transitions


Conduct accessibility review (semantic tags, alt text, keyboard support).


Handle any layout bugs or edge cases.


Day 7 – Final Testing + Showcase Prep
Objectives:
Conduct full testing cycle:


Verify routing, state persistence, quiz logic, and tracker updates


Test across different screen sizes and browsers


Prepare a short demo video (2–3 minutes):


Walkthrough of features and user flow


Take screenshots of final UI (mobile and desktop views)


Write final README.md:


Project summary, setup instructions, tech stack


Submit code and assets for review/presentation
