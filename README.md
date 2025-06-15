# CarePlus Hospital Appointment System

A simple web-based hospital appointment system with an admin panel.  
Users can book appointments, and admins can manage them (mark as completed, canceled, postponed, or delete) via a protected admin panel.

## Features

- **Book Appointments:** Patients can fill out a form to book appointments.
- **Admin Panel:** View, update status, or delete appointments.
- **Admin Login:** Simple frontend-only login for admin access.
- **Auto-Refresh:** Admin panel auto-refreshes every 5 seconds to show the latest data.
- **Export CSV:** Download all appointments as a CSV file.
- **No Backend Required:** All data is stored in the browser's localStorage.

## Getting Started

1. **Clone or Download this Repository**

2. **Open `index.html` in your browser**  
   - Book appointments using the form.

3. **Admin Access**
   - Open `admin-login.html` in your browser.
   - Default credentials:
     - **Username:** `admin`
     - **Password:** `admin123`
   - On successful login, you will be redirected to `admin.html`.

4. **Admin Panel Features**
   - View all appointments.
   - Change status (Completed, Canceled, Postponed).
   - Delete appointments.
   - Download all appointments as a CSV file.
   - Logout button to exit admin mode.

## File Structure

```
index.html           # Main site and appointment form
admin-login.html     # Admin login page
admin.html           # Admin panel
```

## Notes

- **Data is stored in your browser's localStorage.**  
  Clearing browser data will remove all appointments and admin login state.
- **For demonstration and local/offline use only.**  
  Do not use for production or sensitive data.

## License
