# Mobile Appz – Crowdsourced Road Repair

# 🛠 CrowdRepair Frontend

CrowdRepair is a crowdsourced road repair reporting platform.  
This **frontend** is built with [React](https://react.dev/) + [Vite](https://vitejs.dev/) and integrates interactive maps using [Mapbox GL](https://docs.mapbox.com/mapbox-gl-js/).  
It provides separate interfaces for **citizens** and **administrators** to submit, view, and manage road repair reports.

---

## 📸 Features

### 🚗 User Features
- **Report Issues** – Submit location-based reports with images and descriptions.
- **View Nearby Reports** – Map view sorted by proximity using Haversine distance.
- **Upvote & Comment** – Support existing reports and provide additional details.
- **My Reports Page** – Track the status of your submitted issues.
- **Real-Time Location** – Auto-center maps on the user’s current location.

### 🛡 Admin Features
- **Dashboard Overview** – Stats on total reports, pending fixes, fixed reports, and average resolution time.
- **Report Management** – Approve, reject (with reason), or update the status of reports.
- **Type Distribution Charts** – Visualize issue categories using charts.
- **Heatmap View** – Identify hotspots of reported issues.

---

## 🏗 Tech Stack

- **Framework:** [React 18](https://react.dev/)
- **Bundler:** [Vite](https://vitejs.dev/)
- **UI:** [React Bootstrap](https://react-bootstrap.github.io/), [React Icons](https://react-icons.github.io/react-icons/)
- **Maps:** [Mapbox GL JS](https://docs.mapbox.com/mapbox-gl-js/), [React Map GL](https://visgl.github.io/react-map-gl/)
- **HTTP Client:** [Axios](https://axios-http.com/)
- **State & Context:** React Hooks + Context API
- **Utilities:** Haversine formula for distance calculation, timeAgo formatting

---

## 📂 Project Structure

src/
├── components/ # Reusable UI components (ProtectedRoute, MapPicker, Modals)
├── context/ # AuthContext for managing user authentication state
├── pages/ # Page-level components (Dashboard, Admin Panel, Heatmap, etc.)
├── services/ # API service layer (auth, reports, admin)
├── utils/ # Utility functions (distance, time formatting)
├── App.jsx # Main app routes
├── main.jsx # Entry point
└── index.css # Global styles


---

## ⚙️ Setup & Installation

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/CrowdRepair-frontend.git
cd MobileAppzFrontend