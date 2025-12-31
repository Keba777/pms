# Raycon Construction PMS - User Manual

Welcome to the Raycon Construction Project Management System (PMS). This manual guides you through the features and correct usage of the application.

## 1. Getting Started

### 1.1 Login
- **URL**: Navigate to the application URL (e.g., `http://localhost:3000/login`).
- **Credentials**: Enter your **Email** and **Password** to log in.
- **Forgot Password**: If enabled, use the "Reset Password" link to recover access.
- **First Time Access**: Your administrator may have created an account for you. If not, contact your administrator.

## 2. Navigation Overview
Once logged in, you will see a **Sidebar** on the left containing the main menu. The available options depend on your **Role** (e.g., Admin, Project Manager, HR, User).

### Common Key Icons:
- **Dashboard**: Your home screen with summary widgets.
- **Settings**: Configuration options (bottom of sidebar).
- **Notifications**: Alerts and updates.
- **Chat**: Team collaboration tools.

---

## 3. Core Modules

### 3.1 Dashboard (`/`)
- **Overview**: Provides a snapshot of project status, tasks, and key metrics.
- **HR Dashboard**: (If you are HR) A specialized dashboard for managing personnel and leave requests.

### 3.2 Projects (`/projects`)
- **Manage Projects**: View a list of all active projects. Click on a project to see its details (budget, timeline, team).
- **Favorite Projects**: Quick access to projects you have starred.
- **Project Phase**: timeline view of project phases.

### 3.3 Master Schedule (`/master-schedule`)
- **Gantt/Timeline View**: comprehensive view of all project schedules.
- **Projects & Tasks**: Drill down into specific projects (`/project/[id]`) and tasks (`/task/[id]`) to see progress, dependencies, and deadlines.

### 3.4 Activities (`/activities`)
- **Activity List**: View granular activities associated with tasks.
- **Details**: Click an activity to update its status, resource usage, or logs.

### 3.5 Tasks (`/tasks`)
- **My Tasks**: View tasks assigned specifically to you.
- **Status Update**: Move tasks between statuses (e.g., To Do -> In Progress -> Done).

---

## 4. Resource & Request Management

### 4.1 Resources
- **Manage Materials** (`/resources/materials`): Inventory of available materials.
- **Manage Equipment** (`/resources/equipments`): Tracking of heavy machinery and tools.
- **Manage Labors** (`/resources/labors`): Overview of workforce availability.

### 4.2 Requests (`/requests`)
- **Incoming Requests**: View requests awaiting your action (`/requests-incoming`).
- **Make a Request**:
    - **Material**: Request supplies for a site.
    - **Equipment**: Request machinery for a task.
    - **Labor**: Request additional workers.
- **Approvals** (`/request-approval`): (Managers) Approve or reject incoming resource requests.
- **Dispatch** (`/dispatches`): Track items sent to sites.
- **Delivery** (`/request-delivery`): Confirm receipt of items at the site.

### 4.3 My Warehouse (`/mywarehouse`)
- **Site Inventory**: Manage materials and equipment currently held at your specific site (`/site-materials`, `/site-equipments`).

### 4.4 Store Requisition (`/store-requisition`)
- **Stock Requests**: Formal requests to the central store for restocking.

---

## 5. Finance Management

### 5.1 Overview (`/finance/*`)
- **Budgets**: View project budget allocations and actual spend.
- **Invoices**: Manage client billing and supplier invoices.
- **Payments**: Track incoming and outgoing payments.
- **Payrolls**: Manage employee salaries and wages (Access restricted).

---

## 6. HR & Administration

### 6.1 HR Management (`/hrm`)
- **Employee Directory**: List of all staff.
- **Leave Requests** (`/leave-requests`): Submit and approve leave/time-off applications.
- **KPIs** (`/kpis`): Key Performance Indicators for staff performance.

### 6.2 Settings (`/settings`)
- **General**: App-wide settings.
- **Users**: Create and manage system users (Admins only).
- **Permissions**: Configure what each role can do.
- **Departments/Sites/Clients**: Manage master data lists.
- **Languages**: Configure application language settings.

---

## 7. Collaboration

- **Chat** (`/chat`): Direct messaging with colleagues.
- **Meetings** (`/meetings`): Schedule and view upcoming team meetings.
- **Announcements**: Company-wide news and updates.
- **Todos**: Personal or shared to-do lists for ad-hoc items.
- **Issues**: Tracker for problems or blockers needing resolution.

---

## Troubleshooting
- **Missing Menu Items?**: You may not have the required permissions. Contact your Admin.
- **Page Not Loading?**: Refresh the page or check your internet connection.
- **Login Failed?**: Ensure your Caps Lock is off and you are using the correct email.

---
*This manual is a living document. Features may be updated.*
