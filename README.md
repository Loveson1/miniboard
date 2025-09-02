📝 Mini Board

Mini Board is a simple React-based dashboard app where you can add, edit, view, and delete users. It includes a sidebar for navigation, a responsive navbar with dark mode toggle, and modal-based forms for user management.

🚀 Overview of Implementation

Frontend Framework: React (with Vite for fast development).

Styling: TailwindCSS with support for dark mode.

Routing: React Router for navigating between Home and Dashboard.

Components:

Navbar: Contains logo, profile picture, dark mode toggle, and a menu button.

Sidebar: Responsive navigation drawer with links to Home and Dashboard.

Users: Displays user cards with options to View, Edit, and Delete.

AddUser / EditUser Modals: Forms to add or edit user details.

Delete Confirmation Modal: Ensures safe deletion of users.

State Management: React hooks (useState, useEffect) used to handle UI state and user data.

Dark Mode: Toggle persists across the UI using Tailwind’s dark class strategy.

⚙️ Setup Instructions
1. Clone the repository
git clone https://github.com/Loveson1/miniboard.git
cd miniboard

2. Install dependencies
npm install

3. Run development server
npm run dev


Your app will be available at http://localhost:5173/
 (or as shown in the terminal).

4. Build for production
npm run build

🛠️ Features

Add new users with Name, Email, Age, Phone, Company, and City.

View user details inside a modal popup.

Edit existing user details.

Delete users with confirmation modal.

Dark mode toggle for better accessibility.

Responsive Sidebar + Navbar (works on desktop and mobile).

Home page with a welcome message and Dashboard entry point.

🔮 Potential Improvements

Persist Data: Currently, users reset on refresh. Connect to a backend (e.g., Node.js + MongoDB, Firebase, or Supabase) to store data.

Authentication: Add login/logout so users can have personalized boards.

Search & Filter: Improve search functionality (filter by multiple fields like name, company, or city).

Better UI/UX: Add animations, transitions, and refine modals for smoother experience.

Testing: Add unit and integration tests using Jest/React Testing Library.

Deploy: Already works with Vercel — continuous deployment can be improved with GitHub Actions.

✨ Built with love, patience, and a little help from an amigo 🤝
