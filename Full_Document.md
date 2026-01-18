<div align="center">

# <img src="assets/images/logoL3iii.webp" alt="LEYECO III Logo" height="50" style="vertical-align: middle; margin-bottom: 5px;"> **LEYECO III FORMS MANAGEMENT SYSTEM**

[![License: Proprietary](https://img.shields.io/badge/License-Proprietary-red.svg)](LICENSE)
[![PHP Version](https://img.shields.io/badge/PHP-8.2%2B-blue.svg)](https://php.net/)
[![Docker](https://img.shields.io/badge/Docker-✓-blue.svg)](https://www.docker.com/)
[![MySQL](https://img.shields.io/badge/MySQL-8.0+-blue.svg)](https://www.mysql.com/)

A comprehensive web-based forms and operations management system developed by Computer Science Seniors at Holy Cross College of Carigara Incorporated for LEYECO III (Leyte III Electric Cooperative), enabling efficient online submission, tracking, and management of complaints, meter replacements, and requisition forms.

</div>

## Project Overview

<table>
  <tr>
    <td><img src="docs\web-screenshot-18-01-2026.png" alt="Public Homepage - Main Interface" width="400"/></td>
    <td><img src="docs\web-screenshot-18-01-2026 (1).png" alt="Homepage - Form Selection Cards" width="400"/></td>
  </tr>
  <tr>
    <td align="center"><b>Public Homepage - Main Interface</b></td>
    <td align="center"><b>Form Selection Cards</b></td>
  </tr>
</table>

The LEYECO III Forms Management System transforms the service request and operational workflow process by providing a fully digital platform. Staff and customers can submit, track, and manage various forms without the need for paper-based systems or office visits. The system ensures transparency, real-time status updates, and complete audit trails for all transactions.

## Core Modules

### 🎫 Complaints Management

A full-featured complaint tracking system with status workflow management:

- **Public Interface**: Submit complaints with location mapping, photo uploads, and automatic reference code generation (CLN-YYYYMMDD-XXXX)
- **Staff Dashboard**: View and manage all complaints with filtering, search, and Excel export capabilities
- **Workflow Statuses**: NEW → INVESTIGATING → RESOLVED → CLOSED
- **Dispatch System**: Assign complaints to linemen with multiple dispatch modes (Handcarried, Radio/SMS/Chat/Email, Others)
- **Analytics**: Comprehensive complaint analytics with charts and statistics
- **History Archive**: View and manage resolved/closed complaints
- **Email Notifications**: Automated status update emails to reporters and assignment notifications to linemen
- **My Stats**: Individual staff performance tracking

<table>
  <tr>
    <td><img src="docs\web-screenshot-18-01-2026 (4).png" alt="Complaints Dashboard" width="400"/></td>
    <td><img src="docs\web-screenshot-18-01-2026 (5).png" alt="Complaints Analytics" width="400"/></td>
  </tr>
  <tr>
    <td align="center"><b>Complaints Dashboard</b></td>
    <td align="center"><b>Complaints Analytics</b></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="docs\web-screenshot-18-01-2026 (14).png" alt="Complaint Details #1" width="400"/></td>
    <td><img src="docs\web-screenshot-18-01-2026 (15).png" alt="Complaint Details #2" width="400"/></td>
  </tr>
  <tr>
    <td align="center"><b>Complaint Details #1</b></td>
    <td align="center"><b>Complaint Details #2</b></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="docs\web-screenshot-18-01-2026 (16).png" alt="Complaint Details #3" width="400"/></td>
    <td><img src="docs\web-screenshot-18-01-2026 (17).png" alt="Complaint Details #4" width="400"/></td>
  </tr>
  <tr>
    <td align="center"><b>Complaint Details #3</b></td>
    <td align="center"><b>Complaint Details #4</b></td>
  </tr>
</table>

### ⚡ Meter Replacements Management

Complete meter replacement request and fulfillment system:

- **Public Interface**: Submit meter replacement requests with detailed customer information
- **Staff Dashboard**: Manage replacement requests with status tracking and workflow management
- **Workflow Statuses**: NEW → APPROVED → IN_PROGRESS → RESOLVED → CLOSED
- **Dispatch Details**: Track dispatch information, action taken, acknowledgment, and settlement dates
- **Analytics**: Dedicated meter replacement analytics with visual charts
- **History Archive**: Manage completed meter replacement records
- **Email Notifications**: Automated status updates at each workflow stage
- **My Stats**: Personal performance metrics for staff

<table>
  <tr>
    <td><img src="docs\web-screenshot-18-01-2026 (6).png" alt="Meter Replacements Dashboard" width="400"/></td>
  </tr>
  <tr>
    <td align="center"><b>Meter Replacements Dashboard</b></td>
  </tr>
</table>

### 📋 Requisition Forms System (_For Staff's Only_)

Multi-level approval workflow for internal requisitions:

- **Public Interface**: Submit requisition requests (currently in development)
- **Staff Dashboard**: Create and track requisition forms with material/supplies listing
- **Approval Workflow**: 5-level hierarchical approval system:
  1. Department Head (Noted by)
  2. Warehouse Section Head (Inventory Check)
  3. Budget Officer (Budget Approval)
  4. Internal Auditor (Checked by)
  5. General Manager (Final Approval)
- **Approver Portal**: Dedicated interface for approvers with role-based access
- **Admin Dashboard**: Comprehensive view of all requisitions and approvals
- **History & Reports**: Track requisition history and generate reports

<table>
  <tr>
    <td><img src="docs\web-screenshot-18-01-2026 (8).png" alt="Requisition Dashboard" width="400"/></td>
  </tr>
  <tr>
    <td align="center"><b>Requisition Dashboard</b></td>
  </tr>
</table>

## Staff Portal Features

### 📈 Main Dashboard

Unified dashboard showing:

- **Quick Stats**:
  - Total complaints (by status)
  - Total meter replacements (by status)
  - Pending requisitions (for approvers)
  - Online staff count
- **Quick Access Cards**: Direct links to Complaints, Meter Replacements, and Requisition forms
- **Recent Activity**: Latest updates across all modules
- **Page Visit Analytics**: Track daily form visits

<table>
  <tr>
    <td><img src="docs\web-screenshot-18-01-2026 (3).png" alt="Staff Main Dashboard" width="400"/></td>
    <td><img src="docs\web-screenshot-18-01-2026 (7).png" alt="Your Stats" width="400"/></td>
  </tr>
  <tr>
    <td align="center"><b>Staff Main Dashboard</b></td>
    <td align="center"><b>Your Stats</b></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="docs\web-screenshot-18-01-2026 (9).png" alt="System Analytics" width="400"/></td>
    <td><img src="docs\web-screenshot-18-01-2026 (10).png" alt="System Analytics" width="400"/></td>
  </tr>
  <tr>
    <td align="center"><b>System Analytics</b></td>
    <td align="center"><b>System Analytics</b></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="docs\web-screenshot-18-01-2026 (11).png" alt="System Analytics" width="400"/></td>
  </tr>
  <tr>
    <td align="center"><b>System Analytics</b></td>
  </tr>
</table>

### 👥 User Management

- **User Roles**: Admin, Staff, Lineman, Approver (supports multiple roles)
- **User Creation**: Add new staff with role assignment and permissions
- **Profile Management**: Update user information, passwords, and avatars
- **Activity Tracking**: Monitor user login activity and online status
- **Statistics**: Real-time user statistics (online staff, role distribution)

<table>
  <tr>
    <td><img src="docs\web-screenshot-18-01-2026 (12).png" alt="User Management" width="400"/></td>
  </tr>
  <tr>
    <td align="center"><b>User Management</b></td>
  </tr>
</table>

### ⚙️ System Settings

- **Profile Settings**: Personal information and avatar management
- **System Settings**: Application-wide configuration (admin only)
- **Password Management**: Secure password updates
- **Session Management**: Control active sessions

<table>
  <tr>
    <td><img src="docs\web-screenshot-18-01-2026 (13).png" alt="System Settings" width="400"/></td>
  </tr>
  <tr>
    <td align="center"><b>System Settings</b></td>
  </tr>
</table>

## Public Features

### 🌐 Multi-Language Support

- **Bilingual Interface**: English and Waray-Waray language support
- **Supported Pages**:
  - Homepage (index)
  - Complaints homepage and submission form
  - Meter replacements homepage and submission form
  - About page
  - Contact page
- **Easy Language Toggle**: Switch between languages with a single click

### 📍 Location Features

- **Interactive Maps**: Leaflet.js integration for precise location selection
- **Municipality/Barangay Selection**: Cascading dropdowns for accurate location data
- **GPS Coordinates**: Automatic latitude/longitude capture

### 🔍 Tracking System

- **Reference Code Tracking**: Public tracking pages for complaints and meter replacements
- **Real-time Status**: View current status and timeline
- **Email Links**: Direct tracking links in notification emails

## Technical Features

### 📧 Email Notification System

Powered by PHPMailer with comprehensive email templates:

- **Lineman Assignment Emails**: Notify assigned staff of new tasks
- **Status Update Emails**: Automatic notifications on status changes
- **Complaint Workflow**: Emails on INVESTIGATING and RESOLVED statuses
- **Meter Replacement Workflow**: Emails on APPROVED, IN_PROGRESS, and RESOLVED statuses
- **HTML Templates**: Professional, branded email templates with tracking links
- **Fallback Text**: Plain text alternatives for all emails

<table>
  <tr>
    <td><img src="docs\web-screenshot-18-01-2026 (18).png" alt="Sending Email" width="400"/></td>
  </tr>
  <tr>
    <td align="center"><b>Sending Email</b></td>
  </tr>
</table>

### 📊 Reporting & Analytics

- **Excel Export**: Download complaints and meter replacements data
- **PDF Generation**: Print-friendly forms and reports
- **Custom Filters**: Filter by date range, status, type, location
- **Search Functionality**: Quick search across all fields
- **Visual Analytics**: Charts and graphs for data visualization
- **Activity Reports**: Staff performance and system usage reports

## Quick Start

### <img src="https://skillicons.dev/icons?i=docker" height="30" style="vertical-align: middle;"> With Docker (Recommended) \*Private Repo need permission

```bash
git clone https://github.com/frostjade71/leyeco_form_sys.git
cd leyeco_form_sys
docker-compose up -d
```

Access the application:

- **Public Homepage**: http://localhost:8080
- **Staff Portal**: http://localhost:8080/staff/login.php
- **phpMyAdmin**: http://localhost:8081

## Technology Stack

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=html,css,js,php,mysql,docker,vscode" />
  </a>
</p>

## Development Roadmap

### 🚧 Future Plans or i dunno

- Service request form (New connections)
- Reconnection request form

## License

This project is licensed under a **Proprietary License** exclusively for **LEYECO III (Leyte III Electric Cooperative)**.

**Key Terms:**

- This system is developed specifically for LEYECO III's internal operations
- The system may NOT be sold, distributed, or used outside of LEYECO III without explicit written permission
- All rights reserved by the developer

See the [LICENSE](LICENSE) file for complete details.

---

## **Credits** <img src="assets/images/HCCCI.webp" alt="HCCCI Logo" height="24" style="vertical-align: middle;"> HCCCI Computer Science Seniors

> #### Documentation & QA/Testers:

- Sophia Caridad
- Loren Mae Pascual
- Fauna Dea Opetina
- Agnes Osip
- Zxyrah Mae Indemne

> #### **Developer**

- **Jaderby Peñaranda**

  [![Website](https://img.shields.io/badge/🌏-jaderbypenaranda.link-1e88e5)](https://gravatar.com/jaderbypenaranda) [![Email](https://img.shields.io/badge/📩-Contact-4caf50)](mailto:jaderbypenaranda@gmail.com)

---

<div align="left">
<span><b>Built for</b></span>
  <img src="assets/images/logo_leyeco3.webp" alt="LEYECO III Logo" height="40" style="vertical-align: middle; margin-right: 12px;">
  <span><i>Lighting Houses, Lighting Homes, Lighting Hopes</i></span>
</div>

---

**Version**: 2.0.0  
**Last Updated**: January 18, 2026
