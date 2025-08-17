# Splitter - Full Stack Expense Splitting App  

**Splitter** is a full-stack expense splitting application that allows users to track and manage shared expenses with friends and groups. Built with Next.js, Convex (real-time database), Clerk (authentication), and Shadcn UI, this app simplifies splitting bills, settling debts, and tracking payments efficiently.  

## Key Features  

- **Expense Management**:  
  - Add individual or group expenses with multiple split options (equal, percentage, or exact amounts).  
  - Categorize expenses (e.g., transportation, food) for better tracking.  

- **Smart Debt Simplification**:  
  - Automatically calculates the most efficient way to settle debts, reducing unnecessary transactions.  

- **Group & Contact Management**:  
  - Create and manage groups with multiple members.  
  - Track settlement history and record payments between users.  

- **Real-Time Updates**:  
  - Powered by Convex for instant synchronization across all users.  

- **Interactive Dashboard**:  
  - Visualize monthly spending patterns with charts.  
  - AI-powered insights for personalized spending analysis.  

- **Payment Reminders**:  
  - Automated email reminders for pending payments.  

- **Modern UI**:  
  - Responsive and sleek design built with Next.js and Shadcn UI.  

## Tech Stack  

Frontend: Next.js

Backend: Convex (Real-time database and serverless functions)

Authentication: Clerk

AI: Gemini API

Email: Resend

Styling: Tailwind CSS

🚀 Getting Started
Clone the repository:

Bash

git clone https://github.com/your-username/splitr.git
cd splitr
Install dependencies:

Bash

npm install
Set up environment variables:

Create a .env file in the root directory and add the following variables. You can find these keys by setting up the services mentioned in the tech stack.

# Deployment used by `npx convex dev`
CONVEX_DEPLOYMENT=

NEXT_PUBLIC_CONVEX_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

CLERK_JWT_ISSUER_DOMAIN=

RESEND_API_KEY=

GEMINI_API_KEY=
Run the development server:

Bash

npm run dev
Open http://localhost:3000 in your browser to see the app.

🤝 Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

Fork the Project

Create your Feature Branch (git checkout -b feature/AmazingFeature)

Commit your Changes (git commit -m 'Add some AmazingFeature')

Push to the Branch (git push origin feature/AmazingFeature)

Open a Pull Request

Contact
Naman Tripathi - namantripathi937@gmail.com
