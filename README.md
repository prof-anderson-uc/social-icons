# Animated Social Media Buttons (Pure CSS)

This project demonstrates animated social media buttons using **Font Awesome icons** and **CSS transitions**. Each icon smoothly reveals a colored background and changes appearance on hover — no JavaScript needed!

## ✨ Features

- Clean, animated buttons for popular social platforms
- Fully responsive with Flexbox
- Hover effects using only CSS
- Icons provided by [Font Awesome v4.7](https://fontawesome.com/v4.7/)

---

## Live Preview
[Animated Icons Demo](https://prof-anderson-uc.github.io/social-icons/)


---

## 🔧 Getting Started

1. Clone or download this repo.
2. Open `index.html` in a browser.
3. Replace `#` in each `<a>` tag with your actual social media URLs.
4. You can remove or reorder buttons based on your needs.

---

## 📁 File Structure

```
animated-social-buttons/
├── index.html       # HTML structure with icon links
├── social.css       # CSS styles and animations
└── README.md        # This Documentation
```

---

## 🎨 About Font Awesome

This project uses **[Font Awesome v4.7](https://fontawesome.com/v4.7/)** via a free CDN — no account or signup required.

Add this to your HTML `<head>` to use it:

```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
```

Font Awesome is a popular icon library that provides scalable vector icons you can style with CSS. It uses a combination of classes on an `<i>` (icon) element to determine which icon is displayed.

---

## 🔠 Font Awesome Syntax Explained

Each icon is created using an `<i>` element like this:

```html
<i class="fa fa-twitter"></i>
```

- `fa` — the base class required for all Font Awesome icons
- `fa-twitter` — the specific icon name (in this case, the Twitter logo)

Icons must be inside an HTML element (like a `<div>` or `<a>`) to appear on the page.

---

## 🔎 Browse Available Icons

Font Awesome v4.7 includes hundreds of icons. Browse them here:

- [Full icon list – Font Awesome 4.7](https://fontawesome.com/v4.7/icons/)
- [Cheat Sheet](https://fontawesome.com/v4.7/cheatsheet/)

You can change the icon by swapping out the `fa-*` class with another icon name from the list.

Example: Change a Facebook icon to GitHub:

```html
<i class="fa fa-github"></i>
```

---

## 🧠 How the Animation Works (CSS Summary)

- Buttons are created with `<a class="btn">`
- Each button uses a `::before` pseudo-element to animate the background color
- On hover, the icon color changes to white, and the background slides into view
- Transitions and transforms give the smooth animation effect
