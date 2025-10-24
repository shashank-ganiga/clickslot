🕒 ClickSlot – Advanced Scheduling App

ClickSlot is a full-stack web-based scheduling platform designed to simplify meeting organization for freelancers, educators, and businesses. It lets users create events, share personalized booking links, manage real-time availability, and integrate seamlessly with Google Calendar — all through a secure and responsive interface.

🚀 Features

Secure authentication with Google OAuth via Clerk Create, edit, and delete events with custom settings Configure working hours, buffers, and slot durations Share a personalized booking page — guests book without creating an account Google Calendar API integration: auto-sync events and generate Google Meet links Email confirmations for bookings and cancellations Responsive design across desktops, tablets, and mobiles Built for scalability and high performance

🧰 Tech Stack

Frontend : Next.js, React, Tailwind CSS, ShadCN UI 
Backend : Next.js API Routes 
Authentication : Clerk with Google OAuth 
Database : NeonDB (PostgreSQL) 
ORM : Prisma 
Form Handling : React Hook Form & Zod Validation 
Integration : Google Calendar API V
ersion Control : Git & GitHub

⚙️ Installation & Setup

1️⃣ Clone the Repository 
git clone https://github.com/shashank-ganiga/clickslot.git 
cd clickslot

2️⃣ Install Dependencies 
npm install

3️⃣ Setup Environment Variables (.env.local) DATABASE_URL=your_neondb_connection_url
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
GOOGLE_API_KEY=your_google_api_key
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
NEXT_PUBLIC_BASE_URL=http://localhost:3000

4️⃣ Run Database Migrations 
npx prisma migrate dev

5️⃣ Start the Application 
npm run dev

Open http://localhost:3000 to access the app.

👨‍💻 By

Shashank Ganiga 
🌐 GitHub: shashank-ganiga 
🔗 LinkedIn: linkedin.com/in/shashank-ganiga/
