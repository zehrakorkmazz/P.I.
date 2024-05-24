# User Management Screen - UI Specification Document

## Overview
The User Management Screen allows administrators to view, add, edit, and delete users. This document outlines the requirements, UI components, and behaviors.

## Requirements
1. **New User**: Provide a form to add a new user.
2. **Hide Disabled User**: Hide the information of users registered as Disabled users.
3. **Save User**: Save the information of new users.

## UI Components
1. **Header**
    - **New User Button**: Opens 'New User' form.
    - **Hide Disabled User**: Hide the information of disabled users.
    - **Save User**: Save the information of new users.
    
2. **User List**
    - **Filter Dropdown**: Filter by role.
    - **Table**:
        - **Columns**: ID, User Name, Email, Enabled
        - **Rows**: User data.

3. **New User Form**
    - **Fields**: Username, Display Name, Phone, Email, User Roles(Select one from three options: Guest, Admin, SuperAdmin), Enabled (Toggle for enabled status).


## Detailed UI Components

### Header
