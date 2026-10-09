# SahaYatra Web (Admin Dashboard)

SahaYatra (सहयात्रा - "Journey Together") Web is the central command center for school transport administrators. Built with Next.js, it provides a powerful, interactive interface to manage the entire lifecycle of school transportation—from visually building routes on a map to monitoring the fleet in real-time.

The dashboard eliminates the need for complex spreadsheets by providing a visual, click-to-build route creator, precise geofence configuration, and a live operational map that updates in real-time via Server-Sent Events (SSE).

## Key Features
- **Interactive Route Builder:** Click-to-add waypoints on MapLibre GL JS to draw exact bus paths, with drag-and-drop editing for fine-tuning.
- **Advanced Geofence Management:** Add stops along routes and configure precise arrival/approach radii, including per-student geofence overrides for maximum notification accuracy.
- **Live Fleet Monitoring:** A real-time map displaying all active buses, color-coded by operational status (moving, stopped, alert), powered by low-latency SSE streams from the backend.
- **Student & Parent Mapping:** Easily assign students to specific stops and manage parent contact details to ensure targeted, privacy-compliant notifications.
- **Trip & Manifest Oversight:** View active trips in real-time, monitor live student boarding status, and review historical trip data for auditing and reporting.
- **Centralized Alert Center:** Real-time feed for system-generated alerts (e.g., speeding, route deviation, offline buses) with quick acknowledgment workflows.

## Tech Stack
- **Framework:** Next.js 14+ (App Router)
- **UI/UX:** Tailwind CSS, Shadcn UI
- **Maps:** MapLibre GL JS
- **State & Data Fetching:** TanStack Query (React Query)
- **Real-time:** Server-Sent Events (SSE) for live fleet updates
- **Forms & Validation:** React Hook Form, Zod

### Part of the SahaYatra Ecosystem
- 📱 [Mobile App (Flutter)](https://github.com/Abhishek-Adhikari-1/SahaYatra_Flutter.git)
- ⚙️ [Backend API (Bun)](https://github.com/Abhishek-Adhikari-1/SahaYatra_Backend.git)