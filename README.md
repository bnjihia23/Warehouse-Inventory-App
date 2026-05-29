# Warehouse Inventory App

## Overview

The Warehouse Inventory App is an Android application I developed to help small warehouse teams keep track of inventory in a simple and efficient way. The goal of the project was to create a reliable stock tracking system that works entirely offline while providing a clean and intuitive user experience.

Users can register an account, log in, add inventory items, edit existing items, and delete items when they are no longer needed. Inventory data is stored locally using SQLite, allowing the application to function without an internet connection while maintaining data persistence across sessions.

## Features

* User registration and login
* Add, edit, and delete inventory items
* Offline data storage using SQLite
* Color-coded inventory status indicators

  * Green = Healthy stock levels
  * Yellow = Low stock
  * Red = Critical stock
* Responsive inventory dashboard
* Optional SMS notifications for low inventory alerts
* Persistent data storage across app restarts

## Technologies Used

* Java
* Android Studio
* Android SDK
* SQLite
* XML Layouts
* Material Design Components

## Project Motivation

I built this application to solve a common problem found in smaller warehouse environments. Many inventory systems are designed for larger organizations and can be overly complex for teams that only need basic stock tracking. I wanted to create something that allowed users to quickly update inventory levels, view stock status at a glance, and continue working even without network access.

The project also gave me the opportunity to gain hands-on experience with Android development, local database management, user authentication, and mobile UI design.

## Design Approach

I approached this project by focusing on the user's workflow first. Before writing code, I outlined the key tasks users would perform most often and designed the application around those actions.

The dashboard serves as the central hub of the application, displaying inventory items in a two-column grid with visual stock indicators. Common actions such as adding, editing, and deleting items are intentionally easy to access so users can complete routine inventory updates with minimal navigation.

Throughout development, I built features in small increments and tested them frequently to ensure each part of the application worked correctly before moving on to the next feature.

## Technical Highlights

One of the most important parts of this project was implementing SQLite persistence. Every inventory action updates the local database, allowing users to close and reopen the application without losing data.

Another challenge was implementing SMS notifications while maintaining an offline-first design. I chose to make SMS alerts completely optional. Users are only prompted for SMS permission if they choose to enable low-stock notifications, ensuring the core functionality of the application does not depend on sensitive permissions.

## Testing

To validate the application, I tested the complete inventory management workflow, including:

* User registration and login
* Adding inventory items
* Editing inventory quantities
* Deleting inventory records
* Data persistence after restarting the application
* Inventory status color thresholds
* SMS permission approval and denial scenarios

This testing helped ensure that both the inventory management features and the user experience worked as intended.

## Future Improvements

There are several enhancements I would like to implement in future versions of the application:

* Password hashing and stronger authentication security
* Search and filtering functionality
* Inventory sorting options
* CSV import and export support
* Cloud synchronization
* Multi-user inventory management
* Reporting and analytics features

## What I Learned

This project strengthened my understanding of Android application development, SQLite database integration, user interface design, and mobile application testing. It also reinforced the importance of designing software around the user's workflow and building features incrementally to improve reliability and maintainability.

Overall, this project demonstrates my ability to design, develop, test, and refine a complete mobile application from concept to implementation.
