---
description: >-
  The Admin Page Builder streamlines the development process by allowing
  developers to create admin interfaces without manually coding the backend and
  frontend. It automates integration and manages perm
---

# Architecture Overview

#### Workflow:

1. **Template Selection**:
   * Developers start by selecting a template from the Template Library that matches their needs for admin tasks such as dashboards, user management, or reporting.
2. **Page Customization**:
   * Using the Page Builder Interface, developers drag and drop components onto the canvas, adjusting properties and styles as needed.
   * The API Integration Panel allows developers to bind components to backend data models by configuring endpoints and data sources.
3. **Backend Automation**:
   * As developers configure the frontend, the API Blueprint Engine in the backend layer automatically generates the necessary API endpoints and server-side logic.
   * The Data Model Manager ensures that these configurations are mapped correctly to the underlying database structure.
4. **Permission Management**:
   * Developers can define and manage user roles and permissions through the integrated Permission System, ensuring secure access control for different parts of the admin pages.
   * The Permission System is flexible and can be adjusted to fit any access control requirement specified by the developers.

Note: <mark style="color:yellow;">**Details on how to create a page will be under the User Interface section.**</mark>

#### Benefits

* **Efficiency**: Quick and easy admin page creation.
* **Usability**: Accessible to all skill levels.
* **Security**: Robust permission management.
* **Flexibility**: Supports MySQL and MongoDB.
