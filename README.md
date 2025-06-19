
# StayEase: Airbnb Clone Project

## Overview
StayEase is a full-stack web application inspired by Airbnb. The goal is to create a seamless, user-friendly accommodation booking platform where users can search for properties, view details, and book stays securely. This project is part of a learning journey to understand full-stack web development, responsive UI/UX, and modern deployment practices.

## Tech Stack
- **Frontend**: HTML, CSS, JavaScript, React
- **Backend**: Node.js, Express (Planned)
- **Database**: MongoDB or PostgreSQL (TBD)
- **Version Control**: Git + GitHub
- **Design**: Figma (for UI/UX design and wireframes)

## Project Goals
- Build a responsive and intuitive accommodation booking platform.
- Implement secure user authentication.
- Allow users to browse, filter, and book properties.
- Follow industry best practices in frontend and backend development.
- Practice agile teamwork and collaboration.

##  Project Structure (Planned)

## 🎨 UI/UX Design Planning

### Design Goals

- Build an intuitive and seamless booking experience
- Maintain visual consistency across all components
- Ensure mobile-first, responsive design for all screen sizes
- Prioritize fast loading times for better user retention
- Follow accessibility standards (WCAG) for inclusive use

---

### Key Features to Implement

- **Property Search & Filtering**: Users can browse listings based on location, price, availability, etc.
- **Detailed Property View**: Full information on a property with images, pricing, amenities, and reviews.
- **Secure Checkout Flow**: Simple, clean payment and booking confirmation process.
- **User Authentication**: Login/Signup with secure user sessions.
- **Responsive UI**: Optimized for mobile, tablet, and desktop.
- **Favorites**: Allow users to save properties to revisit later.

---

### Primary Pages Description

| Page                   | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| **Property Listing View** | A grid-based view displaying available properties with filters for price, type, and location. |
| **Listing Detailed View** | Displays complete property details including photo carousel, host info, amenities, reviews, and a booking form. |
| **Simple Checkout View**  | Allows users to review their booking, enter payment details, and confirm the reservation in a clean UI. |

---

### Importance of User-Friendly Design

A well-crafted user experience is crucial in the accommodation booking industry. Here's why:

- Reduces **friction** in the user journey, allowing faster bookings
- Improves **trust** and credibility of the platform
- Encourages **repeat usage** through convenience and satisfaction
- Increases **conversion rates** with intuitive interfaces
- Ensures **accessibility** for all users, including those with disabilities
---

### 🎨 Color Styles (Figma)

- **Primary Background:** `#FFFFFF` (white)
- **Primary Accent:** `#FFA800` (yellow/orange) — used in search icons
- **Dark Background:** `#161117` — used for buttons and main sections
- **Highlight Green:** `#34967C` — used in main call-to-action buttons
- **Secondary Background:** `#F0FFFB` — used in highlighted content areas
- **Footer Background:** `#222222`
- **Card Shadows:** `#00000040`
- **Star Rating Color:** `#FAC02B`
- **Text Grays:** `#CACACA`, `#ECECEC`

---

### ✒️ Typography

#### Font Families Used:
- **Quicksand**
- **SF Pro Display**
- **Source Sans Pro**

#### Examples:

| Use Case           | Font Family        | Font Weight | Font Size | Notes                               |
|--------------------|--------------------|-------------|-----------|-------------------------------------|
| Button Text        | SF Pro Display     | 400         | 17px      | Rounded buttons                     |
| Card Titles        | Quicksand          | 600         | 22px      | Bold property headings              |
| Tags/Badges        | Quicksand          | 500         | 12.16px   | Category labels like "Top Villa"    |
| Main Header        | Source Sans Pro    | 600         | 94px      | Big central title (home banner)     |
| Footer Headline    | Quicksand          | 600         | 22px      | Section titles in the footer        |
| General Paragraphs | Quicksand          | 500         | 16px      | Normal content text                 |

---

### 💡 Importance of Identifying Design Properties

Identifying specific design properties (like font, color, padding, spacing) in Figma is **crucial for frontend consistency** and developer collaboration. It ensures that:

- Developers can **match the design exactly**
- There’s **visual consistency** across pages and components
- UI is more **scalable and maintainable**
- Speeds up the dev process by **removing guesswork**
- UX remains clean and professional on all screen sizes

A clear understanding of design specs ensures that what’s **designed is what gets built**.

---

## 👥 Project Roles and Responsibilities

| Role              | Responsibilities                                                                 |
|-------------------|-----------------------------------------------------------------------------------|
| **Project Manager** | Oversees the full project, tracks deadlines, manages team communication and goals |
| **Frontend Developers** | Build and style all UI components, ensure mobile responsiveness, and integrate APIs |
| **Backend Developers** | Set up databases, build and secure APIs, manage business logic and user auth    |
| **Designers**         | Create the Figma mockups, maintain consistency, and deliver assets and guidelines |
| **QA/Testers**        | Test UI, business logic, and responsiveness. Write bug reports and test cases   |
| **DevOps Engineers**  | Handle deployments, CI/CD pipelines, and infrastructure for staging and production |
| **Product Owner**     | Defines features, maintains backlog, and ensures stakeholder alignment           |
| **Scrum Master**      | Facilitates agile workflow, runs stand-ups, and removes blockers                 |

Each of these roles ensures **cross-functional success**, and together they simulate real-world teamwork in software development.

---

## 🧩 UI Component Patterns

To maintain consistency and speed up development, the following UI components will be designed as reusable building blocks:

---

### 🧭 Navbar

**Purpose**: Appears at the top of every page for navigation and access to key features.

**Elements**:
- Logo (linked to homepage)
- Search bar
- User profile icon / login/logout
- Responsive hamburger menu (mobile)
- Navigation links (Home, Browse, Favorites, Bookings)

---

### 🏘️ Property Card

**Purpose**: Display property previews in the listings grid.

**Elements**:
- Property image thumbnail
- Title and location
- Price per night
- Star rating and number of reviews
- “Favorite” (heart) icon
- Clickable to view more details

---

### 📥 Footer

**Purpose**: Standard footer that provides information and links at the bottom of every page.

**Elements**:
- Company/about links
- Social media icons
- Contact information
- Copyright

---

### 💡 Reusability Focus

Each component will:
- Be styled using a shared design system (colors, spacing, typography)
- Use responsive design patterns
- Be reusable across multiple pages
- Be built as independent React components (or similar, depending on framework)
