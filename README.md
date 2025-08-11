Inter-Block Outpass System
A full-stack React + Vite application for managing inter-block outpass requests at KL University, Hyderabad.
The system supports multiple user roles — Students, Faculty, Admins (HODs), and VO Officers — with OTP-based ticket approval and verification.

Features
Student Dashboard
Raise outpass tickets

View ticket status

Manage personal profile

Faculty Dashboard
Raise tickets for personal use

View raised ticket requests

Admin Dashboard (HODs)
View tickets assigned to their branch

Approve or reject ticket requests

VO Portal
Verify tickets using OTP at the gate

View ticket details instantly

Common System Features
OTP Verification for secure ticket approval

Role-based Authentication for different user types

Supabase Integration for database storage and management

Tech Stack
Layer	Technology
Frontend	React 19, Vite, React Router, React Toastify, Lucide Icons, React Datepicker
Backend	Express.js, Supabase (PostgreSQL), CORS, dotenv
Styling	CSS (Inter font, responsive design)
Linting	ESLint with recommended React rules

Project Structure
src/
  ├── AdminDashboard.jsx
  ├── FacultyDashboard.jsx
  ├── StudentDashboard.jsx
  ├── VOPortal.jsx
  ├── Login.jsx
  ├── context/
  │     └── AuthContext.js
  ├── services/
  │     └── ticketService.js
  ├── supabaseClient.js
  ├── index.css
  └── main.jsx
server.js
vite.config.js
eslint.config.js
package.json
.env (not committed)

Setup Instructions
Clone the repository

git clone [https://github.com/yourusername/inter-block-outpass-system.git](https://github.com/chpurnabhargav/Inter-Block-OutPass-System/)
cd inter-block-outpass-system

Install dependencies
npm install
Configure Supabase

Create a .env file and add:

SUPABASE_URL=your_supabase_url
SUPABASE_SERVICE_KEY=your_service_key
Update src/supabaseClient.js if required.

Start the backend server

npm run dev
Default port: 3001

Start the frontend


npm run dev
Default port: 5173

Usage Guide
Login with your university credentials (role-based access)

Raise Ticket for outpass requests (students/faculty)

Approve/Reject requests (admin/HOD)

Verify with OTP at the VO gate portal

Development Commands
Lint Code

npm run lint
Build for Production

npm run build
Preview Build

npm run preview
Contributing
Contributions are welcome.
For major changes, please open an issue first to discuss the proposed updates.

License
This project is licensed under the MIT License.

Developed for KL (Deemed to be University), Hyderabad
By CH PURNA BHARGAV,
   PAWAN ACHYUTANAND
   K SANHITH REDDY
   SAI KRISHNA A
