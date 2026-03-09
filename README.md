# 🏡 HomeLodge‑Mockup

A **mockup homestay booking management platform** built for demonstration, prototyping, and UI/UX testing.  
It simulates the core functionality of a real‑world homestay reservation system, giving you an end‑to‑end experience of guest and administration workflows.

---

URL: https://aisyahumairah.github.io/HomeLodge-Mockup/

---

## 🚀 Project Overview

**HomeLodge** allows two primary personas to interact:

- **Guests**
  - Sign up or log in (Email / Google SSO)
  - Browse available homestays and check availability
  - Create, view and cancel bookings
  - Make payments and see history
  - Receive notifications and chat with administrators
  - View profile and personal bookings

- **Administrators**
  - Manage users, roles, and permissions
  - Oversee all bookings and payments
  - Configure system settings and security
  - Monitor activity with audit logs
  - Issue QR codes for door access
  - Communicate with guests via real‑time chat

This mockup is primarily HTML/CSS/JS and is ideal for front‑end development or as a UX prototype.

---

## ✅ Key Features

| Feature                                  | Guests | Admins |
|------------------------------------------|:------:|:------:|
| Authentication (Email / Google SSO)      | ✅     | ✅     |
| Booking management                       | ✅     | ✅     |
| Payment processing (gateway + webhook)   | ✅     | ✅     |
| QR‑code door access                      | —      | ✅     |
| Real‑time chat (WebSocket)               | ✅     | ✅     |
| Notifications (in‑app & email)           | ✅     | ✅     |
| Google Calendar integration              | ✅     | ✅     |
| Role & permission management             | —      | ✅     |
| User management                          | —      | ✅     |
| System settings & security               | —      | ✅     |
| Audit logging                            | —      | ✅     |

---

## 📁 Project Structure

```
/ (root)
├─ admin/            # Admin pages
├─ auth/             # Authentication pages
├─ guest/            # Guest-facing pages
└─ modernize-bootstrap-free-v2/  # UI library and samples
```

Each folder contains standalone HTML templates for the various application screens.  
Assets like CSS, JS and images are located under `modernize-bootstrap-free-v2/src/assets/...`.

---

## 🛠 Getting Started

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-org/HomeLodge-Mockup.git
   cd HomeLodge-Mockup
   ```

2. **Open in browser**

   Simply open index.html or any of the pages under admin, auth or guest with your preferred browser.

3. **Customize**

   - Modify HTML templates to fit your UI/UX requirements.
   - Update styles in `modernize-bootstrap-free-v2/src/scss/` or use the pre‑compiled `.css` files.
   - Add JavaScript logic in js.

> ⚠️ This is a *static mockup*. There is no backend or database; navigation links mimic the flow.

---

## 🧩 Use Cases

- UI / UX prototyping for homestay or hospitality platforms  
- Demoing authentication, booking, and admin workflows  
- Front‑end testing and component development  
- Teaching HTML/CSS/JS structure with a real‑world theme

---

## 📝 Notes

- The mockup is based on the **Modernize Bootstrap Free** template.
- All assets are included; no external dependencies are required.
- Feel free to extend or integrate with your own API/backend for a working prototype.

---

## 📬 Contact & Contributions

Contributions are welcome—simply fork the repo, make your changes, and open a pull request.  
For questions or feedback, contact the maintainer at `support@homelodge.example.com`.

---

Thank you for checking out **HomeLodge‑Mockup**!  
Enjoy building or demonstrating your homestay management ideas.
