# Zone - Simple Tailwind Landing Page

A simple and responsive landing page project built using **HTML** and **Tailwind CSS**.

This project is designed for beginners who want to practice Tailwind CSS fundamentals such as Flexbox, Grid, responsive design, cards, buttons, navigation, dark mode, and hover/focus states.

## 📌 Project Overview

Nova is a simple modern website with three pages:

* Home
* About
* Contact

The project uses Tailwind CSS through the CDN, so no installation or build setup is required.

## 📁 Project Structure

```text
nova-tailwind/
│
├── index.html
├── about.html
├── contact.html
├── README.md
│
└── images/
```

## 🌐 Pages

### 1. Home Page

The home page contains six main sections:

1. Navigation Bar
2. Hero Section
3. Features Section
4. Services Section
5. Statistics Section
6. Testimonials Section
7. CTA Section
8. Footer

> The CTA and footer are included as part of the overall homepage layout.

### 2. About Page

The About page contains:

* About Hero
* Our Story
* Mission
* Our Values
* Footer

### 3. Contact Page

The Contact page contains:

* Contact Hero
* Contact Information
* Contact Form
* Footer

## 🛠️ Technologies Used

* HTML5
* Tailwind CSS
* JavaScript

Tailwind CSS is loaded using the CDN:

```html
<script src="https://cdn.tailwindcss.com"></script>
```

## ✨ Features

### Responsive Design

The website works on:

* Mobile
* Tablet
* Desktop

Tailwind responsive breakpoints such as:

```text
sm:
md:
lg:
```

are used throughout the project.

### Flexbox

Flexbox is used for:

* Navigation
* Buttons
* Footer
* User information
* Layout alignment

Example:

```html
<div class="flex items-center justify-between">
```

### CSS Grid

Grid is used for:

* Feature cards
* Service cards
* Statistics
* Testimonials
* Contact layout

Example:

```html
<div class="grid md:grid-cols-2 gap-12">
```

### Dark Mode

The project includes a simple dark mode.

Click the moon button:

```text
🌙
```

to switch between light and dark themes.

### Hover Effects

Cards and buttons include hover effects.

Example:

```html
hover:bg-indigo-700
```

and:

```html
hover:shadow-xl
```

### Focus States

Form inputs and buttons include focus styles for better accessibility.

Example:

```html
focus:ring-2 focus:ring-indigo-500
```

## 🚀 How to Run

No installation is required.

### Step 1

Download or clone the project.

### Step 2

Open the project folder.

### Step 3

Open:

```text
index.html
```

in your browser.

That's it!

## 💻 Recommended Development Setup

For a better development experience, you can use:

* Visual Studio Code
* Live Server extension
* Google Chrome
* Tailwind CSS IntelliSense extension

With Live Server:

1. Open the project in VS Code.
2. Install **Live Server**.
3. Right-click `index.html`.
4. Select **Open with Live Server**.

## 📚 Tailwind CSS Concepts Practiced

This project helps practice:

* Utility classes
* Colors
* Spacing
* Typography
* Flexbox
* CSS Grid
* Responsive breakpoints
* Borders
* Shadows
* Rounded corners
* Hover states
* Focus states
* Dark mode
* Responsive navigation
* Forms

## 🎯 Learning Goals

After completing this project, you should have a better understanding of how to:

* Build responsive layouts with Tailwind CSS
* Create reusable card designs
* Create responsive navigation
* Use Flexbox and Grid
* Add hover and focus effects
* Create a dark mode interface
* Build multiple HTML pages
* Connect multiple pages using navigation links

## 🔮 Future Improvements

You can improve this project by adding:

* Mobile hamburger menu animation
* Persistent dark mode using `localStorage`
* Real images
* Form validation
* Working contact form
* Mobile menu
* Testimonials carousel
* Pricing section
* Blog page
* FAQ section
* Real backend/API integration
* Tailwind CLI or Vite setup


