# GatorsLink - Peer Tutoring Platform

A modern, responsive project portfolio website showcasing **GatorsLink**, an innovative peer tutoring and academic forum platform designed to connect students for collaborative learning.

## GatorsLink Project Overview

**GatorsLink** is a comprehensive peer tutoring and academic collaboration platform designed specifically for students. The platform combines the best of peer tutoring with forum-style academic discussions, creating a supportive learning community.

### 🎓 **Core Features**

#### **Peer Tutoring System**
- Student registration and profile creation
- Tutor-student matching algorithm
- Skill-based tutoring categories
- Rating and review system for tutors

#### **Academic Forum**
- Course-based question posting
- Organized by upper/lower division courses
- Subject-specific discussion threads
- Real-time Q&A functionality

#### **Campus Integration**
- In-person meeting scheduling
- Designated campus building locations
- Library meeting room reservations
- Location-based tutor availability

## Team Members

### 👨‍💼 **Sebastian Cervantez** - Team Lead
- **Email:** sebastiane.cervantez@gmail.com
- **Role:** Website/Application Design
- **GatorsLink Focus:** Overall platform architecture, user experience design, and technical leadership for the peer tutoring system.

### 🎨 **Qilan Lao** - Feature Design & Testing
- **Email:** qilao34@gmail.com
- **Role:** Feature Design & Testing
- **GatorsLink Focus:** Designing the tutoring matching algorithm, forum functionality, and comprehensive testing of all platform features.

### 📚 **Mona Menghani** - Documentation & Research
- **Email:** menghanimona@gmail.com
- **Role:** Documentation, Research & Testing
- **GatorsLink Focus:** Researching peer tutoring best practices, documenting platform specifications, and testing user workflows.

### 💻 **Sintia Plasencia** - Frontend/UI Design
- **Email:** sintiadiasz@gmail.com
- **Role:** Frontend/UI Design
- **GatorsLink Focus:** Creating intuitive user interfaces for the tutoring platform, forum design, and mobile-responsive layouts.

## GatorsLink Technical Stack

### **Frontend Technologies**
- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling with Flexbox and Grid
- **JavaScript (ES6+)** - Interactive functionality
- **React.js** - Component-based UI development
- **Responsive Design** - Mobile-first approach

### **Backend Technologies** (Planned)
- **Node.js** - Server-side JavaScript runtime
- **Express.js** - Web application framework
- **MongoDB** - NoSQL database for user and session data
- **Socket.io** - Real-time communication for forums

### **Additional Tools**
- **Font Awesome** - Icon library
- **Google Fonts** - Typography (Inter font family)
- **Git** - Version control
- **Figma** - UI/UX design and prototyping

## File Structure

```
Project Portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
├── README.md           # Project documentation
├── CMakeLists.txt      # CMake configuration
└── main.cpp            # Original C++ file
```

## Customization Guide

### Adding Team Members
```html
<div class="team-member">
    <div class="member-photo">
        <img src="path/to/photo.jpg" alt="Member Name">
        <div class="member-overlay">
            <div class="social-links">
                <a href="#"><i class="fab fa-linkedin"></i></a>
                <a href="#"><i class="fab fa-github"></i></a>
            </div>
        </div>
    </div>
    <h3>Member Name</h3>
    <p class="member-role">Role Title</p>
    <p class="member-bio">Member bio and description</p>
</div>
```

### Adding Gallery Items
```html
<div class="gallery-item" data-category="design">
    <img src="path/to/image.jpg" alt="Project Name">
    <div class="gallery-overlay">
        <h3>Project Name</h3>
        <p>Project description</p>
        <button class="btn btn-small">View Details</button>
    </div>
</div>
```

### Customizing Colors
Update the CSS custom properties in `styles.css`:
```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    --accent-color: #10b981;
}
```