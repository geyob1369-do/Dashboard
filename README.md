# Admin Dashboard 📊

A modern, responsive administrative dashboard web interface built with semantic **HTML5** and advanced **CSS3 (Grid & Flexbox)**. This project is inspired by [The Odin Project's](https://www.theodinproject.com/) Intermediate HTML and CSS curriculum.

---

## 🚀 Live Demo & Preview

Open `index.htm` in any modern web browser to view the dashboard locally.

---

## ✨ Features

- **Sidebar Navigation**:
  - Dashboard logo and branded header.
  - Primary navigation links: *Home*, *Profile*, *Messages*, *History*, *Tasks*, and *Communities*.
  - Secondary utility links: *Settings*, *Support*, and *Privacy*.
  - Styled with custom SVG icons and hover-ready items.

- **Header Section**:
  - **Top Bar**: Search bar with integrated search icon, notification alert, and mini user profile avatar.
  - **Bottom Bar**: Personalized welcome greeting (*"Hi there, Morgan Oakley (@morgan)"*) alongside quick-action buttons (*New*, *Upload*, *Share*).

- **Projects Showcase**:
  - Clean two-column responsive CSS Grid.
  - White card containers featuring yellow accent left-borders (`border-left`) and card drop shadows.
  - Detailed project titles and descriptions.

- **Sidebar Feeds (Right Column)**:
  - **Announcements**: Highlighted cards for site maintenance, community updates, and privacy policies with clean horizontal dividers.
  - **Trending**: Community feed displaying user avatars, handles, and popular project tags.

---

## 🛠️ Built With

- **HTML5**: Semantic document structuring (`<header>`, `<nav>`, `<main>`, `<section>`).
- **CSS3**:
  - **CSS Grid**: Primary page architecture (`2-column`, `2-row` layout) and the projects grid.
  - **CSS Flexbox**: Aligning navigation items, header components, and trending user cards.
  - **CSS Custom Properties (Variables)**: Centralized color palette and font declarations.
  - **CSS Filters**: Dynamic SVG icon color inversion (`filter: brightness(0) invert(1)`).
- **Google Fonts**: [Roboto](https://fonts.google.com/specimen/Roboto) typography.
- **Icons**: Custom SVG icons.

---

## 📂 Project Structure

```text
morgan_oklay/
│
├── index.htm          # Main HTML markup
├── style.css          # Core stylesheets and grid definitions
├── README.md          # Project documentation
│
└── icons_and_pics/    # SVG icons, user avatars, and media assets
    ├── view-dashboard.svg
    ├── home-account.svg
    ├── account-box.svg
    ├── bell-ring.svg
    ├── magnify.svg
    ├── Cat Cute.jpg
    └── ...
```

---

## 💻 Getting Started

1. Clone or download this repository:
   ```bash
   git clone https://github.com/<your-username>/admin-dashboard.git
   ```
2. Navigate into the project folder:
   ```bash
   cd morgan_oklay
   ```
3. Open `index.htm` directly in your browser, or run a local development server (such as VS Code's **Live Server** extension).

---

## 🎯 Key Learning Takeaways

- Structuring multi-panel layouts using CSS Grid templates (`grid-template-columns`, `grid-template-rows`).
- Combining CSS Grid for macro-layout with Flexbox for micro-components and alignment.
- Managing overflow, card sizing, and responsive fractional units (`fr` vs fixed `px`).
- Working with SVG assets and image styling (aspect ratios, circular avatars).

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
