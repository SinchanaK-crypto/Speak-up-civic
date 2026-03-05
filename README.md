# CivicTrack: Public Issue Reporting System

CivicTrack is a localized, transparent platform designed to bridge the gap between citizens and municipal authorities. It allows users to report civic issues like potholes, broken streetlights, and garbage overflows with real-time GPS tagging and status tracking.

---

## Key Features

* **Geo-Tagged Reporting:** Integrated with Leaflet.js to capture the exact coordinates of the issue.
* **Live Tracking:** Every complaint generates a unique ID (e.g., CT-1001) that users can use to monitor progress through a visual timeline.
* **Public Transparency Dashboard:** Real-time statistics showing total reports, pending tasks, and resolved issues.
* **Interactive Map:** A high-level view of all reported problems across the city.
* **Admin Portal:** A secure management console for officials to verify complaints, assign them to departments (BBMP, BESCOM, BWSSB), and update statuses.
* **Responsive Design:** Built with Tailwind CSS, ensuring functionality across mobile, tablet, and desktop devices.

---

## Tech Stack

| Component | Technology Used |
| --- | --- |
| **Frontend** | HTML5, Tailwind CSS |
| **Interactivity** | JavaScript (ES6+) |
| **Maps** | Leaflet.js (OpenStreetMap API) |
| **Icons** | FontAwesome 6 |
| **Data Storage** | Browser LocalStorage (Client-side persistence) |

---

## Getting Started

Since this is a client-side application, no server-side installation is required.

1. **Clone the repository:**
```bash
git clone https://github.com/your-username/CivicTrack.git

```


2. **Open the project:**
Locate the index.html file in the project folder and open it in any modern web browser.
3. **Admin Access:**
* Navigate to the Admin Login section.
* **Password:** admin123
* Use this to enter the Official Management Console to update and resolve issues.



---

## Project Logic Flow

1. **Reporting:** The user fills out the form. If GPS permissions are granted, the application captures the specific Latitude and Longitude.
2. **Storage:** Data is stored in the browser's LocalStorage as a JSON string. This ensures data persists even if the page is refreshed.
3. **Administrative Action:** An administrator logs in, reviews the table of reports, and updates the status to "In Progress" or "Resolved" and assigns a department.
4. **Feedback Loop:** The citizen enters their unique ID on the "Track" page to see the updated status and the assigned municipal department.

---

## Contributing

1. Fork the Project.
2. Create your Feature Branch (git checkout -b feature/NewFeature).
3. Commit your Changes (git commit -m 'Add some NewFeature').
4. Push to the Branch (git push origin feature/NewFeature).
5. Open a Pull Request.

---
