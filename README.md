# BatPanel Dashboard

**BatPanel** is a Batman-inspired admin dashboard built entirely with **HTML and CSS** — no frameworks, no JavaScript.  
The goal was to create a visually striking, responsive, and fully functional dark interface that feels like operating the Batcomputer itself.

---

## Features

-  **Dark Mode UI** — Consistent black & gold theme inspired by Gotham’s tone  
-  **Smooth Page Transitions** — Subtle fade-in animations between pages  
-  **Sidebar Navigation** — Persistent, hover-expandable sidebar  
-  **Authentication Pages** — Login and Register screens styled for immersion  
-  **Unified Design System** — CSS variables for quick theming and maintainability  
-  **Modular Pages** — Allies, Equipment, Missions, and About sections designed as separate modules  

---

## Tech Stack

| Tech | Purpose |
|------|----------|
| **HTML5** | Page structure & layout |
| **CSS3** | Styling, animation, and responsive design |
| **GitHub Pages** | Hosting and deployment |

---

## Folder Structure
batpanel-dashboard/
│
├── index.html # Landing page
├── login.html # Login form
├── register.html # Registration form
│
├── dashboard.html # Home page
├── allies.html # Allies list
├── equipment.html # Equipment management
├── missions.html # Mission overview
├── about.html # About the system
│
├── style.css # Global styles and theme variables
└── assets/
├── images/
└── icons/

---

## Design Language

All color and style elements are managed with CSS variables for theme consistency:

```css
:root {
  --bg-main: #121212;
  --bg-soft: #1a1a1a;
  --bg-card: #1e1e1e;
  --accent: #ffcc00;
  --text-primary: #f5f5f5;
  --text-secondary: #ccc;
  --text-muted: #888;
}
```

📸 Preview
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/01416b7a-879d-46f8-b029-b0754584caf0" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/49243122-33c1-49f3-b381-816f444df1e2" />


Lessons Learned

Building BatPanel helped me learn how to:

-Organize a multi-page frontend project without using JavaScript frameworks

-Apply CSS variable theming for consistent design

-Create interactive UI elements using only CSS transitions and pseudo-selectors

-Maintain readability and scalability in large CSS files

 Live Demo

 Live Site: https://tatrong.github.io/batpanel-dashboard

 GitHub Repo: https://github.com/tatrong/batpanel-dashboard

