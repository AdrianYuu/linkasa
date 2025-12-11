# Linkasa

## Project Description

Linkasa is a comprehensive airport operations management desktop application built with Electron, React, and TypeScript. It centralizes critical workflows for modern airports including flight operations, passenger services, cargo logistics, staff coordination, security protocols, and financial operations. The platform integrates with Firebase for real-time data synchronization and requires an active internet connection for full functionality.

## Features

- **Flight Operations Management**: Create, edit, and manage flight schedules with real-time status updates and baggage status tracking
- **Passenger Services**: Boarding pass generation, custom declarations processing, passport and visa management, and passenger information tracking
- **Cargo & Logistics**: Cargo shipment management, storage space allocation, and inventory tracking for ground operations
- **Staff Management**: Employee records, role-based access control, training program management, and employee development programs
- **Baggage Handling**: Baggage handling task assignment, security incident reporting, and flight baggage status monitoring
- **Ground Operations**: Transportation route management, transportation schedule coordination, and landside operations oversight
- **Equipment Maintenance**: Equipment tracking, maintenance scheduling, and facility management
- **Lost & Found Management**: Lost and found item logging, status tracking, and photo documentation
- **Budget & Financial Management**: Budget request submissions, financial tracking, and expense management
- **Communications**: Real-time chat system, broadcast messaging with priority levels, and staff notifications
- **Interactive Visualization**: Terminal maps and airport maps for better operational awareness
- **Multi-role Support**: Customized interfaces for 20+ different airport roles
- **Real-time Updates**: Live data synchronization across all connected clients via Firebase

## Technology Stack

### Frontend

- **Language**: TypeScript 5.x
- **Framework**: React 18.2.0
- **Desktop Framework**: Electron
- **Build Tool**: Vite 5.x
- **Styling**: Bootstrap 5.3.2, CSS
- **Real-time Database**: Firebase Firestore
- **Cloud Storage**: Firebase Cloud Storage
- **Routing**: React Router DOM v6.x

### Backend

- **Service**: Firebase (BaaS)
- **Authentication**: Firebase Authentication (JWT-based)
- **Database**: Cloud Firestore (Real-time NoSQL)
- **File Storage**: Firebase Cloud Storage

### Desktop

- **Runtime**: Electron with Node.js
- **Package Manager**: npm
- **Type Checking**: TypeScript
- **Bundling**: Electron Vite
