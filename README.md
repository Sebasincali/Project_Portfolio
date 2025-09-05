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

### 🏠 **Portfolio Website Features**
- Hero section showcasing GatorsLink concept
- Team member profiles with roles and contact information
- Visual gallery of platform development stages
- Responsive design for all devices

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

## Key Features Breakdown

### Navigation
- Fixed navigation bar with blur effect
- Smooth scrolling to sections
- Mobile-responsive hamburger menu
- Active link highlighting

### Hero Section
- Animated floating cards with CSS animations
- Gradient background with overlay patterns
- Call-to-action buttons with hover effects
- Scroll indicator animation

### Team Section
- Professional member cards with hover overlays
- Social media integration
- Responsive grid layout
- Image optimization with object-fit

### Proposal Upload
- Drag-and-drop file upload area
- File type validation
- Progress feedback
- Form validation and submission

### Gallery
- Filterable project showcase
- Modal popups for detailed views
- Hover effects and animations
- Responsive grid with masonry-like layout

### Interactive Elements
- Smooth scroll behavior
- Intersection Observer for animations
- Debounced scroll events for performance
- Keyboard navigation support
- Loading states and notifications

## Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Performance Optimizations

- Debounced scroll events
- Intersection Observer for animations
- Optimized images with proper sizing
- Minimal external dependencies
- Efficient CSS animations

## Getting Started

1. **Clone or download** the project files
2. **Add your logo** by replacing the current logo file with your own
3. **Open `index.html`** in a web browser
4. **Customize** the content in the HTML file:
   - Update team member information
   - Modify project details
   - Add your own images and content
5. **Deploy** to any web hosting service

## Adding Your Logo

### **Logo Requirements:**
- **Format:** SVG (recommended), PNG, or JPG
- **Size:** 200x200px or larger (will be automatically resized)
- **Background:** Transparent or white background works best
- **File Name:** Currently using `San_Francisco_State_Gators_logo.svg.png`

### **Logo Placement:**
The logo appears in three locations:
1. **Navigation Bar** - Small logo next to "GatorsLink" text
2. **Hero Section** - Large logo above the main title
3. **Footer** - Small logo in the footer section

### **Current Logo:**
The website now uses the official San Francisco State Gators logo:
- **File:** `San_Francisco_State_Gators_logo.svg.png`
- **Branding:** Official SF State Gators mascot
- **Connection:** Perfect fit for GatorsLink platform
- **Professional:** University-approved branding

## Adding Team Profile Pictures

### **Profile Picture Requirements:**
- **Format:** JPG, PNG, or WebP
- **Size:** 300x300px or larger (will be automatically resized to 200x200px)
- **Quality:** High resolution, clear and professional
- **Background:** Neutral or professional background
- **File Names:** Use the following naming convention:
  - `sebastian.jpg` - Sebastian Cervantez
  - `qilan.jpg` - Qilan Lao
  - `mona.jpg` - Mona Menghani
  - `sintia.jpg` - Sintia Plasencia

### **How to Add Profile Pictures:**

#### **Step 1: Prepare Your Images**
1. Take or select professional headshots of each team member
2. Crop to square format (1:1 aspect ratio)
3. Ensure good lighting and clear visibility
4. Save with the correct filenames listed above

#### **Step 2: Add to Project**
1. Place the image files in the same folder as `index.html`
2. The website will automatically use your images
3. If an image is missing, it will fallback to a placeholder image

#### **Step 3: Test the Results**
1. Open `index.html` in a web browser
2. Navigate to the "Meet Our Team" section
3. Verify all profile pictures display correctly
4. Check that hover effects work properly

### **Profile Picture Features:**
- **Hover Effects:** Social media links appear on hover
- **Responsive Design:** Images scale properly on all devices
- **Fallback System:** Shows placeholder if image is missing
- **Professional Styling:** Rounded corners and subtle shadows

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

## Features in Detail

### File Upload System
- Supports multiple file types
- Drag-and-drop interface
- File validation
- Upload progress feedback
- Error handling

### Animation System
- CSS keyframe animations
- Intersection Observer triggers
- Smooth transitions
- Performance-optimized effects

### Responsive Design
- Mobile-first CSS approach
- Flexible grid layouts
- Touch-friendly interactions
- Optimized typography scaling

## Future Enhancements

- [ ] Backend integration for file storage
- [ ] User authentication system
- [ ] Project management dashboard
- [ ] Real-time collaboration features
- [ ] Advanced filtering options
- [ ] Dark mode toggle
- [ ] Multi-language support

## License

This project is open source and available under the [MIT License](LICENSE).

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Contact

For questions or support, please contact the development team.

---

**Built with ❤️ for showcasing innovative projects and creative excellence.**
