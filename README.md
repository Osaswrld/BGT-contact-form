# BGT-contact-form
BG Technical Services - Contact Form A modern, responsive contact form built with HTML5, CSS3, and Bootstrap 5, featuring advanced animations, glassmorphism effects, and comprehensive form validation.
🚀 Features
HTML5 Features

Semantic HTML Structure: Uses semantic elements for better accessibility and SEO
Form Validation Attributes: Native HTML5 validation with required, type="email", type="tel"
ARIA Labels: Full accessibility support with aria-required attributes
Modern Input Types: Email, telephone, and textarea with maxlength attribute
No-Validate Form: Custom JavaScript validation with novalidate attribute

CSS3 Features

Advanced Animations: Multiple keyframe animations (sectionFade, textPulse, socialSpin)
CSS Grid & Flexbox: Modern layout techniques for responsive design
CSS Variables: Dynamic color schemes and consistent theming
Transform & Transitions: Smooth hover effects and micro-interactions
Gradient Backgrounds: Linear gradients for modern visual appeal
Box Shadows: Layered shadows for depth and visual hierarchy
Media Queries: Responsive breakpoints for mobile-first design

Bootstrap 5 Integration

Responsive Grid System: Bootstrap's 12-column grid with col-lg, col-md classes
Form Components: Bootstrap form controls, labels, and validation feedback
Utility Classes: Spacing (mb-3, me-2), text alignment, and display utilities
Component Classes: Buttons, containers, and form validation styling
Icon Integration: Font Awesome icons with Bootstrap spacing utilities

🎨 Design Features
Visual Effects

Glassmorphism: Semi-transparent overlays with backdrop blur effects
Animated Backgrounds: Gradient backgrounds with subtle animation loops
Interactive Elements: Hover transformations and focus animations
Dynamic Icons: Character counter with changing icons based on input length
Social Media Animations: Rotating social media icons

Responsive Design

Mobile-First Approach: Optimized for mobile devices with progressive enhancement
Flexible Layouts: Adapts seamlessly from mobile (320px) to desktop (1920px+)
Touch-Friendly: Adequate button sizes and spacing for touch interfaces
Readable Typography: Scalable fonts with proper line heights


<!-- Modern Form Elements -->
<input type="email" required>
<input type="tel" required>
<textarea maxlength="300">
<select aria-required="false">

<!-- Accessibility Features -->
<label for="fieldId">
<div class="invalid-feedback">
CSS3 Features Implemented
Animations & Keyframes
css@keyframes sectionFade {
    0% { opacity: 0.9; }
    100% { opacity: 1; }
}

@keyframes textPulse {
    0% { transform: scale(1); }
    100% { transform: scale(1.02); }
}
Modern Layout
css/* Flexbox & Grid */
display: flex;
flex-direction: column;

/* CSS Transforms */
transform: translateY(-2px);
transition: all 0.4s ease;

/* Advanced Selectors */
.contact-form::before
.contact-info h4::after
Bootstrap 5 Classes Used
Grid System
html<div class="container">
<div class="row">
<div class="col-lg-8">
<div class="col-md-6 mb-3">
Form Components
html<div class="form-label">
<input class="form-control">
<select class="form-select">
<div class="invalid-feedback">
<button class="btn btn-primary">
Utility Classes
html<!-- Spacing -->
<div class="mb-3 me-2 text-center">

<!-- Display -->
<div class="d-flex justify-content-center">
🔧 Setup Instructions
Prerequisites

Modern web browser supporting HTML5 and CSS3
Internet connection for CDN resources

Installation

Download Files: Clone or download the project files
Folder Structure: Ensure the CSS file is in the css/ directory
Images: Add background images to the img/ directory:

glowing-contact-us-image.png (Header background)
call-center-representative.png (Form background)


Open Browser: Launch contact-osas.html in a web browser

CDN Dependencies
html<!-- Bootstrap 5.3.0 CSS -->
<link href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.0/css/bootstrap.min.css">

<!-- Font Awesome 6.4.0 -->
<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

<!-- Bootstrap 5.3.0 JS -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.0/js/bootstrap.bundle.min.js">


📄 License
This project demonstrates modern web development techniques using HTML5, CSS3, and Bootstrap 5. Customize as needed for your organization's requirements.
    
images of my design

<img width="1328" height="686" alt="Screenshot 2025-08-21 141305" src="https://github.com/user-attachments/assets/b2dddf3d-7cd3-49ae-af1f-cea8e87ef8b3" />
<img width="863" height="686" alt="Screenshot 2025-08-21 141700" src="https://github.com/user-attachments/assets/83aa592f-ca21-475a-87e1-4cda858c57aa" />
<img width="1329" height="679" alt="Screenshot 2025-08-21 141247" src="https://github.com/user-attachments/assets/0b7a2e18-5dd5-4f55-9ce2-29189223242b" />

