# ProConnect

ProConnect is a professional networking platform that enables users to connect, share posts, discover job opportunities, build communities, and communicate with other professionals. The application provides an interactive environment for students, professionals, and organizations to network and collaborate.

## Features

- User Authentication
- User Profile Management
- Create, Edit, and Delete Posts
- Like, Unlike, and Save Posts
- Comment on Posts
- Follow and Unfollow Users
- Professional News Feed
- Job Portal
- Community Management
- Community Events
- Real-Time Messaging
- Education Management
- User Search
- Responsive User Interface

## Technology Stack

### Frontend

- Next.js
- React.js
- TypeScript
- Tailwind CSS
- Shadcn UI

### Backend

- Next.js API Routes
- Clerk Authentication

### Database

- PostgreSQL (Neon)

### Additional Tools

- Git
- GitHub
- Vercel
- Resend Email API

## Project Structure

```
ProConnect
│
├── actions
├── app
├── components
├── database
├── lib
├── public
├── types
├── middleware.ts
├── package.json
└── README.md
```

## Installation

Clone the repository

```bash
git clone https://github.com/santoshkonakalla/ProConnect.git
```

Navigate to the project folder

```bash
cd ProConnect
```

Install dependencies

```bash
npm install
```

Run the development server

```bash
npm run dev
```

Open the application in your browser

```
http://localhost:3000
```

## Environment Variables

Create a `.env.local` file in the project root and add the following variables.

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=

CLERK_SECRET_KEY=

DATABASE_URL=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in

NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/

NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

RESEND_API_KEY=
```

## Future Enhancements

- Video Calling
- Notifications
- Dark Mode
- AI Job Recommendations
- AI Content Suggestions
- Resume Builder
- Mobile Application

## Contributing

1. Fork the repository.
2. Create a new feature branch.

```bash
git checkout -b feature-name
```

3. Commit your changes.

```bash
git commit -m "Added new feature"
```

4. Push your changes.

```bash
git push origin feature-name
```

5. Create a Pull Request.

## License

This project is developed for educational and learning purposes.

## Author

Santosh Konakalla

GitHub: https://github.com/santoshkonakalla
