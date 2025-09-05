# TravelGenie: A Smart Tourism Assistance Portal

**TravelGenie** is a full-stack web application designed to provide a seamless and comprehensive tourism experience in Bangladesh. It serves as a dynamic marketplace connecting local tour operators with travelers, all managed under a powerful administrative dashboard.

---

## Table of Contents
- Project Overview
- Key Features
- Technology Stack

---

## Project Overview

TravelGenie is built on a modern architecture featuring a **Laravel API backend** and a **static HTML/CSS/JS frontend** powered by **Alpine.js**. This separation of concerns allows for a scalable and maintainable codebase. The platform is designed around three core user roles, each with a dedicated and secure experience: the **Traveler**, the **Business Owner**, and the **Administrator**.

## Key Features

### For Travelers:
- **Dynamic Tour Discovery:** Browse, search, and filter a wide variety of tour packages.
- **Detailed Tour Information:** View comprehensive tour details, including highlights, reviews, and interactive map locations.
- **Secure Booking:** A seamless, multi-step booking and payment process.
- **Personalized Dashboard:** Manage bookings, submit reviews for completed tours, and curate a personal wishlist.
- **Role-Based Restrictions:** Booking and reviewing functionalities are correctly restricted to logged-in travelers.

### For Business Owners:
- **Self-Service Dashboard:** A dedicated portal to manage their business presence.
- **Tour Management:** Create, manage, and delete tour package listings.
- **Real-time Analytics:** View a live count of how many times each tour has been booked.
- **Content Creation:** Upload a primary tour image and set precise map coordinates.

### For Administrators:
- **Full Platform Oversight:** A comprehensive admin panel to manage all aspects of the application.
- **User Management:** View all users, change user roles, and securely delete non-admin accounts.
- **Content Moderation:** Manage all tours and bookings from all business owners.
- **Dynamic Blog Management:** Create and publish blog posts with multiple images, assigning them to specific travel divisions to enrich the main site's content.

---

## Technology Stack

- **Backend:** Laravel 12 (PHP)
- **Frontend:** HTML5, Alpine.js, Tailwind CSS
- **Database:** MySQL
- **Maps:** Leaflet.js & OpenStreetMap
- **Server:** Apache (via XAMPP/WAMP), `php artisan serve`
