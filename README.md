# 🚀 AI Vendor Management System

## Overview

The **AI Vendor Management System** is a modern, full-stack platform designed to streamline and optimize the entire vendor lifecycle for organizations. Leveraging advanced AI capabilities, robust backend integrations, and a beautiful, responsive UI, this system empowers procurement, compliance, and finance teams to manage vendors, contracts, NDAs, RFPs, invoicing, and performance analytics efficiently and securely.

## Project Vision & Importance

Vendor management is critical for organizations aiming to reduce risk, ensure compliance, and maximize value from supplier relationships. This project addresses common pain points in vendor onboarding, evaluation, contract management, and ongoing performance tracking. By integrating AI-powered document analysis, automated compliance checks, and real-time analytics, the platform delivers:

- **Efficiency:** Automates manual processes, reducing administrative overhead.
- **Accuracy:** AI-driven document parsing and validation minimize human error.
- **Transparency:** Centralized dashboard for all vendor activities and metrics.
- **Compliance:** Built-in checks for contracts, NDAs, and regulatory requirements.
- **Scalability:** Modular architecture supports growth and integration with other systems.

## Key Features

### 🧩 UI Components
- **Dashboard:** Unified view of vendor status, contracts, NDAs, RFPs, invoices, and performance.
- **Tables & Charts:** Interactive data tables (TanStack Table) and visualizations (Recharts).
- **Forms:** Type-safe forms with React Hook Form and Zod validation.
- **Feedback:** Alerts, toasts, progress bars, skeleton loaders.
- **Navigation:** Responsive sidebar, breadcrumbs, pagination, and more.
- **Overlay:** Dialogs, sheets, popovers, tooltips, hover cards.

### 📊 Data & Analytics
- **Vendor Screening:** Automated AML, sanctions, and risk checks.
- **Performance Analytics:** KPI tracking, trend analysis, and benchmarking.
- **RFP & Proposal Checker:** AI-powered document parsing for completeness and compliance.
- **Invoice Processing:** Upload, extract, and validate invoices against POs.

### 🔐 Backend Integration
- **Authentication:** Secure auth flows with NextAuth.js.
- **Database:** Type-safe operations with Prisma ORM.
- **API Client:** HTTP requests via Axios and TanStack Query.
- **State Management:** Scalable state with Zustand.

### 🎨 Advanced UI/UX
- **Animations:** Framer Motion for smooth micro-interactions.
- **Drag & Drop:** DND Kit for modern drag-and-drop features.
- **Theme Switching:** Built-in dark/light mode.
- **Internationalization:** Multi-language support with Next Intl.

### 🗄️ Document & File Handling
- **PDF & Image Processing:** Extract text/data from PDFs and images using PyPDF2, pdfplumber, Pillow, pytesseract.
- **File Uploads:** Secure upload and temporary storage for contract and invoice files.

## Technology Stack

- **Frontend:** Next.js 15, TypeScript 5, Tailwind CSS 4, shadcn/ui, Lucide React, Framer Motion, Zustand, TanStack Query/Table, Axios, Zod, React Hook Form, Next Intl, Date-fns, ReactUse.
- **Backend:** FastAPI, Python, Prisma ORM, PyPDF2, pdfplumber, Pillow, pytesseract.
- **DevOps:** Docker, ESLint, PostCSS, integrated testing.
- **Other:** Automated documentation, code generation, and optimization tools.

## Project Structure

```
src/
├── app/                 # Next.js App Router pages
├── components/          # Reusable React components
│   └── ui/             # shadcn/ui components
├── hooks/              # Custom React hooks
└── lib/                # Utility functions and configurations
```

## Available Features & Components

This system includes a comprehensive set of modern web development tools:

### UI Components (shadcn/ui)
- **Layout**: Card, Separator, Aspect Ratio, Resizable Panels
- **Forms**: Input, Textarea, Select, Checkbox, Radio Group, Switch
- **Feedback**: Alert, Toast (Sonner), Progress, Skeleton
- **Navigation**: Breadcrumb, Menubar, Navigation Menu, Pagination
- **Overlay**: Dialog, Sheet, Popover, Tooltip, Hover Card
- **Data Display**: Badge, Avatar, Calendar

### Advanced Data Features
- **Tables**: Powerful data tables with sorting, filtering, pagination (TanStack Table)
- **Charts**: Beautiful visualizations with Recharts
- **Forms**: Type-safe forms with React Hook Form + Zod validation

### Interactive Features
- **Animations**: Smooth micro-interactions with Framer Motion
- **Drag & Drop**: Modern drag-and-drop functionality with DND Kit
- **Theme Switching**: Built-in dark/light mode support

### Backend Integration
- **Authentication**: Ready-to-use auth flows with NextAuth.js
- **Database**: Type-safe database operations with Prisma
- **API Client**: HTTP requests with Axios + TanStack Query
- **State Management**: Simple and scalable with Zustand

### Production Features
- **Internationalization**: Multi-language support with Next Intl
- **Image Optimization**: Automatic image processing with Sharp
- **Type Safety**: End-to-end TypeScript with Zod validation
- **Essential Hooks**: 100+ useful React hooks with ReactUse for common patterns

### Document & File Handling
- **PDF & Image Processing**: Extract text/data from PDFs and images using PyPDF2, pdfplumber, Pillow, pytesseract.
- **File Uploads**: Secure upload and temporary storage for contract and invoice files.

## Quick Start

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Start production server
npm start
```


