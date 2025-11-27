# CSE220 Lab Marks Dashboard

A modern, glassmorphic web application for viewing CSE220 lab course marks and performance metrics. Built with React and featuring Google OAuth authentication.

![CSE220 Lab Marks Dashboard](https://img.shields.io/badge/React-19.2.0-blue) ![Vite](https://img.shields.io/badge/Vite-7.2.4-purple) ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-4.1.17-cyan) ![Framer Motion](https://img.shields.io/badge/Framer%20Motion-12.23.24-ff69b4) ![Lucide React](https://img.shields.io/badge/Lucide%20React-0.554.0-orange)

## ✨ Features

### 🔐 Secure Authentication
- **Google OAuth Integration**: Sign in securely with your G Suite email
- **Protected Routes**: Dashboard access restricted to authenticated users only
- **Session Management**: Seamless logout functionality with state cleanup

### 📊 Comprehensive Performance Tracking
- **Real-time Data Visualization**: Interactive charts and graphs for all course components
- **Performance Metrics**: Track your progress across:
  - Lab Performance (with average calculation)
  - Lab Exams (best N-1 scores counted)
  - Assignments (best N scores counted)
  - Attendance Log
- **Summary Statistics**: Quick overview cards showing key metrics and eligibility status

### 🎨 Modern Glass UI Design
- **Glassmorphism Effects**: Beautiful frosted glass aesthetic throughout the app
- **Responsive Layout**: Optimized for desktop, tablet, and mobile devices
- **Smooth Animations**: Framer Motion powered transitions and interactions
- **Dark Theme**: Eye-friendly dark mode with vibrant accent colors

### 📈 Interactive Data Visualization
- **Inline Charts**: Embedded bar charts for each performance category
- **Expandable Chart Modals**: Click on stat cards to view detailed breakdowns
- **Radar Charts**: Visual comparison of overall performance metrics
- **Color-Coded Data**: Easy-to-read color schemes for different categories
- **Plagiarism Indicators**: Clear visual markers for flagged submissions

### 👤 Student Profile Section
- **Personal Information**: Display of student ID, email, semester, and section
- **Status Indicators**: 
  - Final exam eligibility status
  - Absent count tracking
  - Plagiarism count monitoring
  - Lab policy signature status
  - Survey form completion status
- **Visual Chips**: Color-coded status chips for quick information scanning

### 🔍 Detailed Data Grids
- **Attendance Tracking**: Complete log of attendance with dates and status
- **Assignment Breakdown**: Individual scores with plagiarism flags
- **Lab Performance**: Detailed scores for each lab session
- **Lab Exam Results**: Individual exam scores and rankings

### 🛡️ Robust Error Handling
- **Lab Policy Enforcement**: Blocks dashboard access until lab policy is signed
- **Student Verification**: Validates student email against database
- **Network Error Detection**: Graceful handling of connection issues
- **User-Friendly Messages**: Clear error messages with guidance to contact faculty
- **Logout on Error**: Easy recovery option for authentication issues

### 🎯 Smart Features
- **Scroll-to-Section**: Click stat cards to navigate to detailed sections
- **Criteria Display**: Shows which scores are counted (e.g., "Best 3 of 4")
- **Progress Bars**: Visual representation of marks obtained vs total
- **Persistent Header/Footer**: Consistent navigation throughout the app

## 🚀 Technology Stack

- **Frontend Framework**: React 19.2.0
- **Build Tool**: Vite 7.2.4
- **Styling**: TailwindCSS 4.1.17 with custom glass design tokens
- **Authentication**: @react-oauth/google
- **Charts**: Recharts 3.5.0

- ## 🎨 Design Philosophy

The application follows a **glassmorphism** design language, featuring:
- Semi-transparent panels with backdrop blur effects
- Subtle borders and shadows for depth
- Smooth transitions and micro-interactions
- Consistent spacing and typography using the Poppins font family
- Color-coded information for quick scanning

## 📱 Responsive Design

The dashboard is fully responsive with breakpoints optimized for:
- Mobile devices (320px+)
- Tablets (768px+)
- Desktops (1024px+)

## 📄 License

This project is licensed under the MIT License.

## 👥 Support

For any issues or questions, please contact your lab faculty members.

---

Built for CSE220 students
