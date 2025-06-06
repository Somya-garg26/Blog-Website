# Blog-Website

##Coding Blog Website
 Description
This is a responsive Coding Blog Website created using HTML, CSS, JavaScript, and Bootstrap 5. The website features a modern design and layout that highlights blog posts related to coding, programming, and web development. It was developed as a part of an internship/web development task to demonstrate my skills in front-end technologies.
The website consists of a navigation bar, carousel section, multiple blog cards, and a footer — all designed to provide a clean and informative user interface.

## How I Built It (Code Breakdown)
 1. Bootstrap Integration
To ensure a responsive and mobile-first design, I used Bootstrap 5. I linked the Bootstrap CDN in the <head> section for both CSS and JavaScript:
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/css/bootstrap.min.css" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/js/bootstrap.bundle.min.js"></script>

2. Navbar (Navigation Menu)
I created a responsive dark-themed navbar using Bootstrap's navbar component. It includes:
-Brand name: "Coding Blog"
-Navigation links like Home and Contact
-A dropdown menu for blog topics (HTML, CSS, JavaScript)
-A search bar with button
<nav class="navbar navbar-expand-lg navbar-dark bg-dark"> ... </nav>

 3. Carousel Section
The website includes a Bootstrap carousel with three sliding images. Each slide contains:
-An image (img tag)
-A caption (carousel-caption) with heading, subtext, and buttons
<div class="carousel-item active">
  <img src="image1.jpg" class="d-block w-100">
  <div class="carousel-caption d-none d-md-block">
    <h2>Welcome To Coding Blog</h2>
    <p>Programming Blogs, News, Updates</p>
  </div>
</div>

 4. Blog Cards Section
I used Bootstrap’s card component in a grid layout to display blog topics. Each card includes:
-An image (with width="100%" height="225" for consistent size)
-A short description
-Action buttons: View / Edit
-Timestamp (e.g., "5 mins", "32 mins")
<div class="card shadow-sm">
  <img src="Blog1.jfif" class="card-img-top">
  <div class="card-body">
    <p class="card-text">Best free Python resources for beginners to learn for free.</p>
  </div>
</div>

5. Footer Section
At the end of the page, I added a simple footer with copyright:
<footer class="blog-footer">
  <p>Copyright 2025 @Coding Blog</p>
</footer>

##Technologies Used
1.HTML5
2.CSS3
3.JavaScript 
4.Bootstrap 5

Screenshots of the output:-

![Image](https://github.com/user-attachments/assets/cf9e367b-0928-4939-91ec-d98614761d38)

![Image](https://github.com/user-attachments/assets/37eebc76-d138-434e-be32-6340f7416129)









