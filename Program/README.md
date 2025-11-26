# LinKasa

## Description
An Electron desktop application built with React and TypeScript that provides a comprehensive, modular suite of tools for airport operations management. Linkasa centralizes operational workflows — staff and role management, employee training and development, baggage handling and security incident tracking, cargo and logistics, boarding pass and customs/declaration processing, budget requests and financial tracking, and equipment and maintenance tracking — into a single, offline-capable desktop client.

The app integrates Firebase for authentication, real-time database updates, cloud storage, and notifications, enabling synchronized data across devices and teams. It also includes interactive visual aids (terminal and airport maps), chat and broadcast communication channels for staff coordination, and role-based interfaces to ensure users see only the tools relevant to their responsibilities. The architecture is modular to make it easy to add new operational modules and scale the system to different airport sizes.

## Features
- Cross-platform support (Windows, macOS, Linux)
- User-friendly interface for managing airport operations
- Real-time updates and notifications
- Modular architecture for scalability
- Interactive airport maps for better visualization
- Employee management and training modules
- Baggage handling and security incident tracking
- Cargo shipment and logistics management
- Budget request and financial tracking
- Chat and broadcast communication tools
- Custom declaration and boarding pass management

## Technology Stacks
- **Frontend**: React, TypeScript
- **Backend**: Firebase
- **Build Tools**: Vite, Electron Builder
- **Styling**: Bootstrap

## Prerequisites
- Node.js (v16 or higher)
- npm (v7 or higher)

## Installation

### Clone the Repository
```bash
git clone <repository-url>
cd linkasa/Program
```

### Install Dependencies
```bash
npm install
```

### Setup Environment Variables
1. Copy the `.env.example` file and rename it to `.env`.
2. Fill in the required environment variables in the `.env` file.

### Run the Development Server
```bash
npm run dev
```
