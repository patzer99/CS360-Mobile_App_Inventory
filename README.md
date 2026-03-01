# CS360-Mobile_App_Inventory
Project Three – Final Portfolio Artifact

Project Overview

This project is a fully functional Android inventory management application developed as part of CS 360. The purpose of the app is to allow users to log in, manage inventory items, track stock levels, and receive SMS notifications when items fall below a defined threshold.

The primary goal of the application was to design and implement a user-centered mobile solution that supports efficient inventory tracking while applying best practices in Android development.

Requirements and User Needs

The app was designed to address the need for a simple, efficient way to manage inventory from a mobile device. Users needed the ability to:

Log in securely

Add, edit, and delete inventory items

View inventory in an organized dashboard

Define low-stock thresholds

Receive SMS notifications when inventory falls below set limits

Rather than simply storing data, the application focuses on usability and clarity so users can quickly understand stock levels and take action when needed.

Screens and Features

To support user needs and create a user-centered UI, the app includes:

Login Screen – Secure user authentication

Permissions Screen – SMS permission handling

Dashboard Screen – Displays inventory using a RecyclerView layout

Add/Edit Dialogs – Allows users to modify inventory items

Low-Inventory SMS Alerts – Automated notification system

The UI design prioritizes simplicity and consistency. Toolbars, structured layouts, and intuitive navigation ensure that users can move between screens easily. Clear labeling and structured input fields reduce confusion and improve efficiency.

Development Approach

My approach to development evolved throughout this project. Instead of building everything at once, I implemented features incrementally:

Database setup

CRUD operations

UI integration

SMS permission handling

Low-inventory alert logic

Breaking the application into smaller, manageable components made debugging more effective and improved overall maintainability. Logic related to inventory checks and SMS alerts was centralized to improve readability and organization.

This structured approach is one I will continue using in future projects.

Testing and Debugging

Testing was performed continuously throughout development. Each feature was tested individually before integration. This included:

Verifying database functionality

Testing activity transitions

Validating permission handling

Ensuring SMS alerts triggered correctly

Systematic debugging helped identify issues such as unresolved references, navigation errors, and permission-related failures. Testing at each stage ensured stability and prevented larger issues later in development.

This process reinforced the importance of incremental development and verification.

Challenges and Innovation

One of the primary challenges involved integrating SMS permissions and ensuring notifications triggered correctly without disrupting user flow. Resolving this required careful handling of Android permission requests and logic placement.

Additionally, maintaining clean architecture while connecting database logic with UI components required thoughtful structuring. This pushed me to think beyond simply writing code and toward designing maintainable systems.

Areas of Success

The strongest component of this project was the integration between backend logic (database operations and threshold checks) and frontend UI design. The application demonstrates:

Functional CRUD operations

Structured activity navigation

Proper permission management

User-centered interface design

This project reflects my growth from focusing solely on feature functionality to developing structured, user-focused mobile applications.

Future Application

Moving forward, I plan to continue building mobile applications using a user-first, structured development approach. This project provided a complete development cycle experience—from planning and UI design to implementation and testing.

This application may serve as a foundation for future refinement and potential publication on the Google Play Store as part of my professional portfolio.
