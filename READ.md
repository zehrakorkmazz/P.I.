# User Management Screen - UI Specification Document

## Overview
The User Management Screen allows administrators to view, add, edit, and delete users. This document outlines the requirements, UI components, and behaviors.

## Requirements
1. **View Users**: Display a list of users with search and filter options.
2. **Add User**: Provide a form to add a new user.
3. **Edit User**: Allow editing of existing users.
4. **Delete User**: Enable deletion of users with confirmation.

## UI Components
1. **Header**
    - **Title**: "User Management"
    - **Add User Button**: Opens 'Add User' form.
    
2. **User List**
    - **Search Bar**: Input to search users.
    - **Filter Dropdown**: Filter by role.
    - **Table**:
        - **Columns**: Name, Email, Role, Actions.
        - **Rows**: User data.
        - **Actions**: Edit and Delete buttons.

3. **Add/Edit User Form**
    - **Fields**: Name, Email, Role.
    - **Buttons**: Save, Cancel.
    
4. **Delete Confirmation Dialog**
    - **Message**: "Are you sure you want to delete [User Name]?"
    - **Buttons**: Confirm, Cancel.

## Initial State
- Header with title and "Add User" button.
- Search bar and filter dropdown.
- Empty or populated user list table.

## Behavior
1. **Add User Button**: Opens 'Add User' form.
2. **Search Bar**: Filters user list dynamically.
3. **Filter Dropdown**: Filters user list by role.
4. **User List Table**:
    - **Edit Button**: Opens 'Edit User' form with details.
    - **Delete Button**: Opens delete confirmation dialog.
5. **Add/Edit User Form**:
    - **Save Button**: Validates and saves details, updates list.
    - **Cancel Button**: Closes form without saving.
6. **Delete Confirmation Dialog**:
    - **Confirm Button**: Deletes user from list.
    - **Cancel Button**: Closes dialog.

## Detailed UI Components

### Header
