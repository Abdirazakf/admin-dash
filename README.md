# Admin Dashboard

A custom admin dashboard interface built with HTML and CSS as part of The Odin Project’s Intermediate HTML and CSS curriculum. This dashboard features a collapsible sidebar, a header with search and profile controls, dynamic project cards, announcement widgets, and a “Trending” panel.

## Features

- **Header Bar**  
  - Search input with icon  
  - Account greeting (“Hi, there, Abdirazak Farah (@butterdabread)”)  
  - Notification bell and secondary profile controls  

- **Action Buttons**  
  - “New Upload” and “Share” buttons styled with rounded corners and hover effects  

- **Sidebar Navigation**  
  - Vertical menu with icons and labels for Dashboard, Home, Profile, Messages, History, Tasks, Communities, Settings, Support, and Privacy  
  - Styled in a consistent brand color (`#1991d2`)  

- **Main Content Grid**  
  - **Your Projects** section displaying card widgets for multiple user projects  
  - **Announcements** panel with multi-row cards and action icons (Favorite, Watchlist, Share)  
  - **Trending** sidebar listing top user profiles with avatars and short descriptions  

- **Responsive Layout**  
  - CSS Grid for the overall page structure  
  - Flexbox for header, card layouts, and sidebar items  
  - Media queries can be added to adapt to tablet/mobile widths  

---

## Built With

- **HTML5** for semantic markup  
- **CSS3**  
  - CSS Grid (`grid-template-columns` & `grid-template-rows`)  
  - Flexbox (`display: flex; align-items; justify-content; gap`)  

---

## Getting Started

1. **Clone the repository**  
   ```bash
   git clone https://github.com/Abdirazakf/admin-dash.git
   ```

2. **Navigate to the project folder**  
   ```bash
   cd admin-dash
   ```

3. **Open `index.html`** in your browser to view the dashboard.

---

## File Structure

```
admin-dash/
├── assets/
│   ├── icons/        # All sidebar & header icons
│   └── img/          # Profile Pics
├── index.html        # Main HTML markup
├── styles.css        # Layout & styling
└── README.md
```

---

## Customization

- **Update Profile**  
  Change the greeting name and handle in `index.html` under the `.account-greeting` section.

- **Add/Remove Projects**  
  Duplicate or remove `<div class="card card-X">…</div>` blocks in the Projects grid.

- **Modify Announcements**  
  Edit the content in the `<section class="announcement-card">` markup to reflect your own announcements.

- **Change Colors & Fonts**  
  Edit `styles.css`—replace the `#1991d2` sidebar color or adjust font-family in the global selector.

---

## Contributing

1. Fork this repository  
2. Create a new branch:  
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes and commit:  
   ```bash
   git commit -m "Add new dashboard widget"
   ```
4. Push to your fork and open a pull request

