# Mentcare Frontend System

## Overview
A role-based mental healthcare management system providing specialized dashboards for different healthcare professionals. This frontend application delivers tailored interfaces for doctors, nurses, health visitors, receptionists, and administrators to efficiently manage patient care, records, appointments, and consultations.

## Features
- **Role-Based Dashboards**: Customized interfaces for each user role with appropriate permissions
- **Patient Records Management**: Secure access to patient medical records and history
- **Appointment Scheduling**: Streamlined booking and management of patient consultations
- **Multi-Role Support**: Doctor, Nurse, Health Visitor, Receptionist, and Admin dashboards
- **Responsive Design**: Clean, accessible interface built with HTML and CSS
- **Medical Records Access**: Role-appropriate viewing and editing of patient information

## Quick Start

### Running Locally
1. Clone this repository
2. Open `index.html` in your web browser
3. Alternatively, serve using a local web server:
   ```bash
   python -m http.server 8000
   ```
   Then visit `http://localhost:8000`

### Accessing the System
Navigate to `index.html` to access the main login/selection page, then choose your role to view the corresponding dashboard.

## Pages and Roles

### Available Dashboards:
- **`index.html`** - Main entry point and role selection
- **`doctor.html` / `doctor_page.html`** - Doctor dashboard with patient consultation tools
- **`nurse.html` / `nurse_page.html`** - Nursing staff interface for patient care management
- **`health-visitor.html` / `health-visitor_page.html`** - Health visitor dashboard for community care
- **`receptionist.html` / `receptionist_page.html`** - Receptionist interface for appointments and admin
- **`admin.html` / `admin_page.html`** - Administrator dashboard for system management
- **`medical-records.html` / `medical_records_page.html`** - Medical records viewing and management
- **`Mental_Healthcare.html`** - Mental healthcare specific information and resources

### Styling
- **`styles.css`** - Main stylesheet for consistent design across all pages

## Roadmap

- [ ] Backend integration for data persistence
- [ ] User authentication and session management
- [ ] Real-time appointment notifications
- [ ] Advanced reporting and analytics dashboard
- [ ] Mobile app version
- [ ] Integration with electronic health record (EHR) systems
- [ ] Multi-language support
- [ ] Accessibility improvements (WCAG 2.1 AA compliance)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Screenshots
*(Screenshots to be added)*

![Dashboard Overview]()
![Role Selection]()
![Patient Records]()
