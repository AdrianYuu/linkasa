# LinKasa

## Description

LinKasa is a desktop Electron app built with React and TypeScript that brings airport operations together in one place — staff and role management, baggage and cargo handling, training, boarding/declaration processing, budgeting, and internal communications.

The app relies on Firebase for authentication, real-time data, cloud storage, and notifications. An active internet connection is required for normal operation because the app connects to Firebase services.

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
git clone https://github.com/AdrianYuu/linkasa
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

## Additional Resources
The repository root contains design and requirements artifacts to help understand system workflows and architecture:

- Diagram.vpp — Visual Paradigm project containing system diagrams (use case, sequence, and others). Open with Visual Paradigm.
- UseCaseDescription.xlsx — Excel workbook with detailed use case descriptions, acceptance criteria, and user stories.