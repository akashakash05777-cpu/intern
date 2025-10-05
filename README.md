# InternConnect - Internship Management Platform

A modern, comprehensive internship management platform built with Next.js 15, TypeScript, and Tailwind CSS. This NEP-compliant platform connects Students, Faculty/Colleges, and Industry partners to streamline the internship process.

## 🚀 Features

### 👥 Multi-Role Support
- **Students** - Apply for internships, track progress, maintain digital logbooks
- **Staff/Faculty** - Review applications, monitor students, provide feedback
- **Industry Partners** - Create postings, manage interns, conduct evaluations
- **Administrators** - Manage users, MoUs, view comprehensive analytics

### 🎯 Key Functionalities

#### Student Portal
- 📋 **Dashboard** - Overview of applications and progress tracking
- 🔍 **Internship Browser** - Search and filter opportunities by domain, location, credits
- 📝 **Application Management** - Track application status and history
- 📖 **NEP Logbook** - Digital internship logbook as per NEP guidelines
- 📄 **Document Upload** - Resume, video, and document management

#### Staff Portal
- ✅ **Application Review** - Approve/reject student applications
- 👀 **Student Monitoring** - Track progress and logbook entries
- 💬 **Feedback System** - Provide feedback and mark completion
- 📊 **Reports** - Generate evaluation reports and analytics

#### Industry Portal
- 📢 **Posting Management** - Create and manage internship postings
- 🔍 **Application Review** - Review and shortlist candidates
- 👥 **Student Assignment** - Assign mentors and track progress
- ⭐ **Evaluation** - Provide feedback and completion assessments

#### Admin Portal
- 👤 **User Management** - Manage all platform users
- 📋 **MoU Management** - Create, track, and manage agreements
- 📈 **Analytics** - Comprehensive platform analytics and reporting
- ⚙️ **System Settings** - Configure platform settings and permissions

### 📋 MoU Management Module
- **Registry** - List all MoUs with status filters (Active, Pending, Expired, Draft)
- **Creation Wizard** - Step-by-step MoU creation process
- **Digital Signatures** - Mock e-signature workflow
- **Lifecycle Management** - Track status from Draft to Terminated
- **Version History** - Maintain audit trail and version control

## 🛠️ Technology Stack

- **Framework**: Next.js 15.5.4 (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS 4
- **UI Components**: shadcn/ui with Radix UI primitives
- **Charts**: Recharts for data visualization
- **Mock API**: MSW (Mock Service Worker)
- **Icons**: Lucide React
- **Date Handling**: date-fns
- **Forms**: React Hook Form with Zod validation

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ 
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone <your-repository-url>
   cd internconnect
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

### 🔑 Demo Login Credentials

The platform includes demo accounts for all user roles:

| Role | Email | Password | Features |
|------|-------|----------|----------|
| **Student** | `john.doe@student.edu` | `student123` | Apply to internships, track progress, maintain logbook |
| **Staff** | `sarah.johnson@staff.edu` | `staff123` | Review applications, monitor students, provide feedback |
| **Industry** | `hr@techcorp.com` | `industry123` | Create postings, review applications, manage interns |
| **Admin** | `admin@university.edu` | `admin123` | Manage users, MoUs, view analytics |

### 🏗️ Build for Production

```bash
npm run build
npm start
```

## 📁 Project Structure

```
src/
├── app/                    # Next.js App Router pages
│   ├── student/           # Student portal pages
│   ├── staff/             # Staff portal pages
│   ├── industry/          # Industry portal pages
│   ├── admin/             # Admin portal pages
│   └── layout.tsx         # Root layout
├── components/            # Reusable components
│   ├── layout/           # Layout components (Navbar, Sidebar)
│   ├── ui/               # UI components (shadcn/ui)
│   └── providers/        # Context providers
├── lib/                  # Utility functions and mock data
├── mocks/                # MSW mock API handlers
└── types/                # TypeScript type definitions
```

## ✨ Key Features

### 🎨 Modern UI/UX
- Responsive design for all devices
- Dark mode support
- Accessible components (WCAG guidelines)
- Smooth animations and transitions

### 🔐 Role-Based Access Control
- Four distinct user roles with appropriate permissions
- Secure routing and data access
- Protected routes and components

### 📊 Analytics & Reporting
- Interactive charts and graphs
- Real-time statistics and metrics
- Export functionality for reports
- Comprehensive dashboard views

### 📱 Mobile-First Design
- Responsive layout adapting to all screen sizes
- Touch-friendly interface
- Optimized for mobile devices

### 🌙 Dark Mode Support
- System preference detection
- Manual theme toggle
- Consistent theming across components

## 🔧 Configuration

### Environment Variables
Create a `.env.local` file in the root directory:

```env
# Add your environment variables here
NEXT_PUBLIC_APP_URL=http://localhost:3000
```

### Mock Data
The application uses MSW (Mock Service Worker) for realistic mock data including:
- User profiles and authentication
- Internship postings and applications
- MoU management and signatures
- Logbook entries and progress tracking
- Notifications and system alerts

## 🚀 Deployment

### Vercel (Recommended)
1. Push your code to GitHub
2. Connect your repository to Vercel
3. Deploy with default settings

### Other Platforms
The application can be deployed on any platform that supports Next.js:
- Netlify
- Railway
- Heroku
- AWS
- Google Cloud Platform

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **shadcn/ui** for the beautiful UI components
- **Radix UI** for accessible primitives
- **Tailwind CSS** for utility-first styling
- **Next.js** team for the amazing framework
- **Vercel** for hosting and deployment

## 📞 Support

For support and questions:
- Create an issue in this repository
- Contact the development team

---

**Built with ❤️ using Next.js, TypeScript, and Tailwind CSS**