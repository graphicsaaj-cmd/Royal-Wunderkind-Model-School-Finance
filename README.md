# Royal Wunderkind Model School – Financial Tools

A lightweight, offline-first web application for managing:

- School fees receipts
- Staff paychecks
- Invoices
- Expense tracking

Built with vanilla HTML, CSS, and JavaScript. All data is stored locally in the browser using `localStorage`. No server required.

## Features

- Login system with user roles (admin/user)
- Auto-save temporary work
- Idle timeout (5 minutes) with auto-save
- Print-optimized layout
- Export to Excel (using SheetJS)
- Editable school header, logo, signatures, stamp
- Admin dashboard with user activity and password reset requests

## Default Logins

| Username | Password   | Role  |
|---------|------------|-------|
| admin   | admin123   | Admin |
| john    | john2025   | User  |
| mary    | mary2025   | User  |

## Usage

1. Open `index.html` in any modern browser.
2. Log in using one of the default accounts.
3. Use the buttons to switch between tools.
4. Click "Print" for clean A4 output.

## Deployment

Host on GitHub Pages, Netlify, Vercel, or any static file server.

## Assets

Place logos, signatures, or stamps in the `/assets` folder if you want to reference them directly (optional).

---

**Note**: All sensitive operations use SHA-256 hashed passwords stored locally only.