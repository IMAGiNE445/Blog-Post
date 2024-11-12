
# InternSync: Internship Activity Monitoring Portal

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Architecture](#architecture)
- [Modules](#modules)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Project Overview
InternSync is a web and mobile platform designed to streamline the management and tracking of internship activities for interns, college mentors, and company mentors during the eighth semester. It replaces traditional Excel-based systems by centralizing the submission and review of daily reports, allowing interns to submit their internship details and daily progress directly through the platform.

## Features
- **Centralized Reporting**: Interns can submit daily reports directly on the platform.
- **Automated Summaries**: College mentors receive weekly performance summaries via analytics dashboards.
- **Hierarchical Access**: Different access levels for administrative functions and department-level management.
- **Mobile Application**: A mobile app for students and college mentors that mirrors the functionalities of the web platform.
- **Key Modules**: Attendance Management, Daily Report Submission, Internship Management, College Mentor Assignment, and Company Mentor Assignment.

## Technologies Used
- **Frontend**: 
  - Next.js (React framework)
  - TypeScript (Typed JavaScript)
  - Tailwind CSS (Utility-first CSS framework)
- **Backend**: 
  - Supabase (Backend as a Service with PostgreSQL)
  - Node.js
- **Mobile Development**: 
  - Android Studio
  - Kotlin (Programming language)
  - Jetpack Compose (UI toolkit)
- **Deployment**: 
  - Vercel (Deployment platform)

## Installation
To set up the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/internsync.git
   cd internsync
   ```

2. **Install dependencies**:
   For the web application:
   ```bash
   cd web
   npm install
   ```

   For the mobile application:
   ```bash
   cd mobile
   ./gradlew build
   ```

3. **Set up environment variables**:
   Create a `.env.local` file in the web directory and add your Supabase credentials:
   ```
   NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
   NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
   ```

4. **Run the application**:
   For the web application:
   ```bash
   npm run dev
   ```

   For the mobile application, open it in Android Studio and run it on an emulator or physical device.

## Usage
- **Interns**: Log in to submit daily reports, view progress, and manage internship details.
- **College Mentors**: Monitor intern progress, provide feedback, and manage assignments.
- **Company Mentors**: Supervise interns and evaluate their work.

## Architecture
The architecture of InternSync is designed to facilitate seamless communication and data flow between different user roles. It consists of three main layers:

1. **Application Layer (Backend)**: Contains server-side logic, including authentication and database connectivity.
2. **Presentation Layer (Frontend)**: The user interface built using Next.js.
3. **Data Layer (Database)**: Managed by Supabase, storing all relevant data.

![Proposed System Architecture](path/to/architecture-diagram.png)

## Modules
- **Login Modules**: For different user roles (Institute, Department, College Mentor, Company Mentor, Intern).
- **Mentor Assignment Module**: Assigns mentors to students and tracks their progress.
- **Internship Management Module**: Provides details about the internship program.
- **Attendance Management Module**: Monitors intern attendance and compliance.
- **Daily Report Submission Module**: Allows interns to submit daily reports.

## Contributing
Contributions are welcome! Please follow these steps to contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
We would like to express our gratitude to our project supervisor, Prof. Akshay A Jadhav, for his guidance and support throughout this project. We also thank the Head of the Department, Dr. Monika Bhagwat, and the Principal, Dr. Sandeep Joshi, for their encouragement and resources.

---

For more information, please refer to the [documentation](path/to/documentation).
```

### Notes:
- Replace `https://github.com/yourusername/internsync.git` with the actual repository URL.
- Update the path to the architecture diagram and documentation as necessary.
- Ensure that the installation instructions are accurate and reflect the actual setup process for your project.
