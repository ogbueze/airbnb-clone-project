# airbnb-clone-project

This is a recreation of the airbnb website for project and learning purposes

# Airbnb Clone Project

## 🏠 Overview

The **Airbnb Clone Project** is a full-stack web application inspired by Airbnb.  
It aims to replicate core features such as property listings, booking management, user authentication, and search filters.

## 🎯 Project Goals

- Build a realistic clone of Airbnb using modern technologies.
- Strengthen full-stack development skills.
- Practice UI design and responsive layouts.
- Implement authentication and database integration.

## 🧰 Tech Stack

**Frontend:** HTML, CSS, Javascript, React, Tailwind CSS, Vite

## 🎨 UI/UX Design Planning

### 🎯 Design Goals

The UI/UX design focuses on creating a **clean, intuitive, and responsive interface** that mirrors the simplicity and aesthetic appeal of Airbnb.  
The goal is to ensure users can:

- Easily browse available properties.
- Quickly access detailed information about each listing.
- Seamlessly complete a booking with minimal friction.

### 🌟 Key Features

- **Responsive Design:** Optimized for both mobile and desktop users.
- **Visual Hierarchy:** Clear presentation of listings, prices, and booking buttons.
- **Smooth Navigation:** Quick access between listings, details, and checkout pages.
- **Consistent Branding:** Use of uniform color schemes, fonts, and spacing.
- **Accessibility:** Clear contrasts, readable fonts, and accessible controls.

---

### 🏠 Primary Pages Overview

| Page                      | Description                                                              | Key UI Elements                                                                 |
| ------------------------- | ------------------------------------------------------------------------ | ------------------------------------------------------------------------------- |
| **Property Listing View** | Displays all available properties with images, price, and short details. | Search bar, filters (price, location, amenities), grid/list layout, pagination. |
| **Listing Detailed View** | Shows comprehensive details for a selected property.                     | Property images carousel, description, amenities list, reviews, booking button. |
| **Simple Checkout View**  | Handles booking confirmation and payment steps.                          | Guest details form, booking summary, payment options, confirmation message.     |

---

### 💡 Importance of a User-Friendly Design

A user-friendly design is **critical** in a booking system because it directly impacts user trust and conversion rates.  
When users find it easy to search, view details, and complete bookings:

- They spend less time figuring out navigation.
- They make fewer mistakes during checkout.
- They are more likely to complete a booking and return in the future.  
  A smooth, intuitive design ultimately translates to **higher engagement and customer satisfaction**.

---

### 🎨 Figma Design Specifications

You can view the full design prototype on Figma:  
🔗 [Project Airbnb – Figma Design](https://www.figma.com/design/E2BRqdPcKkrnX6hLGPto8Z/Project-Airbnb?node-id=3-87&t=WzIdnoYxh04UcbKU-0)

---

#### 🧩 Color Styles

| Color Name         | Hex Code  | Usage                                              |
| ------------------ | --------- | -------------------------------------------------- |
| **Primary**        | `#FF5A5F` | Main accent color used for buttons and highlights. |
| **Secondary**      | `#008489` | Used for links, icons, and supportive accents.     |
| **Background**     | `#FFFFFF` | Primary background color for all pages.            |
| **Text**           | `#222222` | Main text color for body and titles.               |
| **Secondary Text** | `#717171` | Used for subtitles, hints, and descriptions.       |

---

#### 🖋️ Typography

| Text Role          | Font Family | Font Weight  | Font Size | Usage                                |
| ------------------ | ----------- | ------------ | --------- | ------------------------------------ |
| **Primary Font**   | Circular    | Medium (500) | 16px      | Default body text and buttons.       |
| **Headings**       | Circular    | Bold (700)   | 24px–32px | Page titles and section headers.     |
| **Secondary Text** | Circular    | Book (400)   | 14px      | Labels, captions, and minor content. |

---

### 🧠 Importance of Identifying Design Properties

Identifying design properties ensures **consistency and accuracy** when converting mockups into functional UI elements.  
It allows developers and designers to:

- Maintain a **unified visual identity** across all pages.
- Ensure **readability and accessibility** by following defined font and color standards.
- **Reduce development time** through reusable style tokens and CSS variables.
- Support **collaboration** between design and engineering teams.
- Produce a product that **faithfully matches the Figma prototype** and delivers a better user experience.

---

---

## 👥 Project Roles and Responsibilities

Clearly defining roles ensures smooth collaboration, accountability, and a structured workflow throughout the project lifecycle.

| **Role**                | **Responsibilities**                                                                                                                     |
| ----------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| **Project Manager**     | Oversees the project timeline, coordinates the team, and manages deliverables to ensure milestones are met efficiently.                  |
| **Frontend Developers** | Implement user interface (UI) components, ensure responsive design, and maintain visual consistency with the design system.              |
| **Backend Developers**  | Build and maintain APIs, manage the database, and implement business logic to handle data flow and server-side operations.               |
| **Designers**           | Create Figma mockups, define design properties, maintain the design system, and ensure a high-quality user experience (UX).              |
| **QA/Testers**          | Develop test cases, perform functional and regression testing, identify and report bugs, and ensure the system meets quality standards.  |
| **DevOps Engineers**    | Manage deployment pipelines, maintain CI/CD processes, and ensure scalability and uptime through efficient server infrastructure.        |
| **Product Owner**       | Define product requirements, prioritize features, and represent stakeholder interests to align business goals with development progress. |
| **Scrum Master**        | Facilitate Agile ceremonies, remove blockers, and help the team stay organized, focused, and aligned with sprint goals.                  |

---

Each role plays a vital part in the project’s success:

- **Project Managers** keep everything on schedule.
- **Developers and Designers** turn ideas into reality.
- **QA/Testers** ensure reliability.
- **DevOps Engineers** make deployment seamless.
- **Product Owners** ensure the product meets user needs.
- **Scrum Masters** maintain team efficiency and communication.

---

---

## 🧩 UI Component Patterns

A well-structured UI relies on consistent and reusable components. The following components will be designed and implemented to ensure uniformity, responsiveness, and maintainability across the application.

### Planned Components

#### 🧭 Navbar

- **Logo** – Represents brand identity and links back to the homepage.
- **Search Bar** – Allows users to search for properties or destinations.
- **User Navigation** – Contains links for login, sign-up, and profile access.
- **Responsive Menu** – Adjusts layout and options for mobile and desktop views.

#### 🏡 Property Card

- **Property Image** – Displays the main photo of the property.
- **Basic Details** – Shows key information such as price, location, and rating.
- **Favorite Button** – Lets users mark properties as favorites.
- **Responsive Layout** – Automatically adapts to different screen sizes for a seamless experience.

#### ⚙️ Footer

- **Site Links** – Provides navigation to important pages such as About, Contact, and Help.
- **Company Information** – Displays brief company details and contact information.
- **Social Media Links** – Links to social profiles for user engagement.
- **Copyright Information** – Displays ownership and legal information.

---

Each component will be designed for **reusability, consistency, and responsiveness**, ensuring a smooth and intuitive user experience across all devices.

---
