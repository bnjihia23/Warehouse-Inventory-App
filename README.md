# Warehouse Inventory App

A mobile inventory management application built for Android that enables small warehouse teams to track stock levels quickly and efficiently without requiring an internet connection.

## Overview

Warehouse Inventory App was designed as an offline-first inventory solution for small operations that need reliable stock tracking without the complexity of enterprise warehouse management systems. The application allows users to manage inventory items, monitor stock levels through visual indicators, and maintain persistent data storage directly on the device.

The primary goal was to create a fast and intuitive workflow that minimizes the number of steps required to perform common inventory tasks while ensuring data remains available even when network connectivity is unavailable.

## Key Features

* Secure user registration and login system
* Inventory dashboard with responsive two-column grid layout
* Add, edit, and delete inventory items
* Color-coded stock status indicators for quick inventory assessment

  * Green: Healthy stock levels
  * Yellow: Low inventory warning
  * Red: Critical inventory levels
* Local SQLite database for persistent offline storage
* Optional SMS notifications for critical low-stock alerts
* Material Design user interface optimized for mobile devices
* Data persistence across application restarts

## Technical Stack

### Frontend

* Android SDK
* Java
* XML Layouts
* Material Design Components

### Data Storage

* SQLite Database
* Local persistent storage architecture

### Device Integration

* Android SMS Permission API
* Runtime permission handling

## Architecture

The application follows a local-first design philosophy where all inventory data is stored directly on the device using SQLite. This approach provides:

* Fast data access with no network latency
* Full offline functionality
* Reduced infrastructure costs
* Improved reliability in environments with limited connectivity

Inventory records are automatically synchronized with the local database whenever users create, update, or delete items, ensuring data consistency across sessions.

## Development Process

This project was developed using an iterative, user-focused approach. The workflow began with identifying core warehouse inventory challenges and designing a streamlined user experience before implementation.

Development was completed in small, functional increments, allowing each feature to be tested end-to-end before moving to the next stage. This approach improved reliability, simplified debugging, and ensured that the application remained aligned with user needs throughout development.

## Testing

The application was tested across the complete inventory management workflow:

* User registration and authentication
* Inventory item creation
* Inventory item updates
* Inventory item deletion
* Data persistence after application restart
* Stock indicator accuracy
* User interface responsiveness
* SMS permission acceptance and denial scenarios

Special attention was given to validating offline functionality and ensuring the application remained fully operational when SMS permissions were not granted.

## Challenges & Solutions

### Offline-First Design

One of the primary challenges was balancing a fully offline inventory system with optional SMS-based notifications. To address this, SMS functionality was implemented as a completely independent feature that users can enable if desired.

This design ensures that inventory management remains functional regardless of permission status while still providing enhanced notification capabilities for users who need them.

### User Experience Optimization

The dashboard layout was refined to prioritize speed and clarity. Inventory status indicators, floating action buttons, and consistent navigation patterns were incorporated to reduce friction during daily inventory management tasks.

## Future Enhancements

Planned improvements include:

* Password hashing and enhanced authentication security
* Inventory search and filtering
* Sorting capabilities
* CSV import and export functionality
* Multi-user support
* Cloud synchronization
* Analytics and reporting dashboard
* Role-based access control

## What This Project Demonstrates

This project showcases my ability to:

* Design and develop Android applications from concept to deployment
* Implement local database solutions using SQLite
* Build intuitive mobile user interfaces
* Handle Android runtime permissions securely
* Create offline-first applications
* Test and validate complete user workflows
* Balance technical requirements with user experience considerations

The combination of persistent local storage, responsive UI design, and optional device integration demonstrates practical mobile development skills applicable to real-world business applications.
