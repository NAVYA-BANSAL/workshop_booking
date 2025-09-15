# **Workshop Booking**

> This website is for coordinators to book a workshop(s), they can book a workshop based on instructors posts or can propose a workshop date based on their convenience.

### Features

- Statistics

  1. Instructors Only
     - Monthly Workshop Count
     - Instructor/Coordinator Profile stats
     - Upcoming Workshops
     - View/Post comments on Coordinator's Profile
  2. Open to All
     - Workshops taken over Map of India
     - Pie chart based on Total Workshops taken to Type of Workshops.

- Workshop Related Features
  > Instructors can Accept, Reject or Delete workshops based on their preference, also they can postpone a workshop based on coordinators request.

# Workshop App

This project manages workshops and user profiles.  
Branch: `feature/initial-setup`

# Workshop Booking – UI/UX Enhancements

## 🚀 Overview

This branch (`feature/initial-setup`) focuses on improving the UI/UX of the FOSSEE Workshop Booking platform.  
The original site was minimal and functional, but lacked responsiveness and clear visual hierarchy.  
My goal was to enhance usability, especially for students accessing on mobile devices.

## Enhancements Made

1. **Added Bootstrap (via CDN)** for responsive layouts and consistent styling.
2. **Navbar Improvements** – Added Bootstrap navbar with collapsible menu for mobile.
3. **Footer Enhancements** – Updated footer with better readability and modern styling.
4. **Banner for Identification** – Clear visual indicator to differentiate feature branch updates.
5. **Message Notifications** – Integrated Toastr for better feedback on user actions.

## Design Principles Used

- **Mobile-first design** – ensured navigation and text remain readable on small screens.
- **Consistency** – Bootstrap styling keeps components uniform.
- **Accessibility** – improved color contrast, larger clickable areas.
- **Visual Hierarchy** – navbar at top, footer at bottom, content in clear sections.

## Responsiveness

- Bootstrap grid system automatically adapts layout.
- Navbar collapses into a toggle menu on smaller devices.
- Flexible container widths for different screen sizes.

## Trade-offs

- Used Bootstrap (external dependency) → slight increase in load time, but gained responsive, modern UI without reinventing CSS.
- Kept changes **incremental**, avoiding heavy redesigns, so performance stayed lightweight.

## Challenges

- Ensuring templates extended the updated `base.html` (took debugging to confirm changes).
- Balancing **new UI** while keeping the **existing Django structure intact**.
- Managed Git commits carefully to keep history clean for recruiters to review.

**NOTE**: Check docs/Getting_Started.md for more info.
