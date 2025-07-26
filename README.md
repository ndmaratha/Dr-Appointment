# Full Stack Doctors Appointment Platform 🏥

A modern telemedicine platform built with cutting-edge technologies to facilitate doctor-patient interactions, appointment scheduling, and video consultations.

## 🚀 Tech Stack

- **Frontend**: Next.js 15.3.2, React 19
- **Styling**: Tailwind CSS 4.1.7, Shadcn UI
- **Backend**: Next.js API Routes
- **Database**: PostgreSQL (via Neon)
- **ORM**: Prisma 6.7.0
- **Authentication**: Clerk
- **Video SDK**: Vonage Video API
- **Form Handling**: React Hook Form, Zod
- **UI Components**: Radix UI

## ✨ Key Features

### 👥 User Management

- Multi-role support (Patients, Doctors, Administrators)
- Secure authentication with Clerk
- Profile management and customization

### 📅 Appointment System

- Real-time availability scheduling
- Automated reminders
- Calendar integration
- Booking management

### 💳 Payment & Credits

- Credit-based payment system
- Secure transaction processing
- Doctor payout management
- Platform fee handling

### 🎥 Video Consultations

- High-quality video streaming
- Screen sharing capabilities
- Chat functionality
- Session recording options

### ⚙️ Admin Dashboard

- User verification system
- Analytics and reporting
- Payment processing
- Platform monitoring

## 🛠️ Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/doctors-appointment-platform.git

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env.local

# Generate Prisma client
npx prisma generate

# Run development server
npm run dev
```

## 🔧 Environment Variables

```env
DATABASE_URL="your-neon-database-url"
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY="your-clerk-publishable-key"
CLERK_SECRET_KEY="your-clerk-secret-key"
VONAGE_API_KEY="your-vonage-api-key"
VONAGE_API_SECRET="your-vonage-api-secret"
```

## 📁 Project Structure

```
├── app/
│   ├── api/         # API routes
│   ├── (auth)/      # Authentication pages
│   ├── (routes)/    # Main application routes
│   └── layout.tsx   # Root layout
├── components/      # Reusable components
├── lib/            # Utility functions
├── prisma/         # Database schema
└── public/         # Static assets
```

## 💻 Development

```bash
# Run development server
npm run dev

# Build for production
npm run build

# Start production server
npm start

# Run linting
npm run lint
```

## 🎯 API Endpoints

- `/api/appointments` - Appointment management
- `/api/users` - User operations
- `/api/payments` - Payment processing
- `/api/video` - Video session management

## 🔐 Security Features

- JWT authentication
- Role-based access control
- Data encryption
- Secure video sessions
- CSRF protection

## 🎨 UI Components

- Custom themed components
- Responsive design
- Dark/Light mode
- Loading states
- Toast notifications
- Form validation

## 📱 Mobile Responsiveness

- Fully responsive design
- Mobile-first approach
- Touch-friendly interfaces
- Progressive Web App capabilities

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## 📺 Tutorial

Watch the full tutorial on YouTube: [Build a Doctor's Appointment Platform](https://www.youtube.com/watch?v=ID1PRFF1dlw)

## 🔗 Links

- [Documentation](#)
- [Live Demo](#)
- [Bug Report](#)
- [Feature Request](#)

## 📧 Support

For support, email support@example.com or join our Slack channel.
