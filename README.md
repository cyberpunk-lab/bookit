# 🏢 Bookit App

A sophisticated meeting room booking application built with modern web technologies. This full-stack application demonstrates proficiency in React, Next.js 13+, and cloud infrastructure integration through Appwrite.

<img src="public/images/screen.png" alt="Bookit App Screenshot" />

## 🚀 Tech Stack

- **Frontend Framework**: Next.js 13+ with App Router
- **UI Framework**: React 18 with Server and Client Components
- **Authentication**: Custom auth implementation using Appwrite
- **Database**: Appwrite Cloud Database
- **Styling**: Tailwind CSS with custom configuration
- **State Management**: React Context API for auth state
- **API Layer**: Next.js Server Actions for secure API endpoints
- **Type Safety**: JavaScript with JSConfig setup
- **Deployment Ready**: Vercel compatible

## ✨ Key Features

- **User Authentication**
  - Secure login and registration system
  - Session management with Appwrite
  - Protected routes and API endpoints
  - Role-based access control

- **Room Management**
  - Create and delete meeting rooms
  - Detailed room information and availability
  - Room image upload and management
  - Owner-only room management capabilities

- **Booking System**
  - Real-time availability checking
  - Conflict-free booking management
  - Booking cancellation with validation
  - User-specific booking history

- **Modern UI/UX**
  - Responsive design for all devices
  - Clean and intuitive interface
  - Toast notifications for user feedback
  - Loading states and error handling

## 🛠 Architecture

### Frontend Architecture
- Implements the new Next.js 13+ App Router
- Utilizes both Server and Client Components strategically
- Centralized state management using Context API
- Component-based architecture with reusable UI elements

### Backend Architecture
- Leverages Next.js Server Actions for API endpoints
- Secure integration with Appwrite Backend as a Service
- Robust error handling and input validation
- Efficient data fetching with proper caching

## 📦 Project Structure

```
├── app/                  # Next.js 13 app directory
│   ├── actions/         # Server actions for API endpoints
│   ├── bookings/       # Booking management pages
│   ├── rooms/          # Room management pages
│   └── layout.jsx      # Root layout with providers
├── components/          # Reusable React components
├── config/             # Configuration files
├── context/            # React Context providers
└── public/             # Static assets
```

## 🚀 Getting Started

### Prerequisites
- Node.js 16.8 or later
- NPM or Yarn
- Appwrite Cloud Account

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/bookit-app.git
   cd bookit-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Configure environment variables:
   - Rename `.env.example` to `.env.local`
   - Add your Appwrite credentials:
     ```env
     NEXT_PUBLIC_APPWRITE_PROJECT_ID=your_project_id
     NEXT_PUBLIC_APPWRITE_ENDPOINT=your_endpoint
     NEXT_PUBLIC_APPWRITE_DATABASE_ID=your_database_id
     ```

4. Run the development server:
   ```bash
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) with your browser.

## 🔧 Appwrite Setup

1. Create a new project in [Appwrite Console](https://cloud.appwrite.io/console)
2. Set up a new database with the following collections:
   - Users
   - Rooms
   - Bookings
3. Configure authentication methods
4. Set up storage for room images
5. Configure security rules and API permissions

## 🔐 Security Features

- Protected API routes with session validation
- Secure password handling
- XSS protection
- CSRF protection
- Input sanitization
- Role-based access control

## 🌟 Upcoming Features

- [ ] Real-time notifications
- [ ] Calendar integration
- [ ] Room analytics dashboard
- [ ] Advanced booking rules
- [ ] Teams and departments

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
