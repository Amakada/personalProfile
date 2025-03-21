# Professional Portfolio Website

This is a professional portfolio website built with HTML and vanilla CSS. It features a colorful theme, smooth animations, and interactivity.

## Features

- **Responsive Design**: Works on all devices and screen sizes
- **Modern UI**: Clean and professional design with a colorful theme
- **Smooth Animations**: CSS animations for a professional look
- **Interactive Elements**: Including form validation and project filtering
- **Mobile-Friendly Navigation**: Hamburger menu for smaller screens
- **Social Media Integration**: Icons with links to social platforms
- **Professional Photo Space**: Placeholder for your professional photo

## Pages

1. **Home** - Introduction, skills, and featured projects
2. **About** - Personal information, education, experience, and interests
3. **Projects** - Showcase of your projects with filtering capability
4. **Contact** - Contact form and contact information

## How to Customize

### Personal Information

- Edit your name and title in the HTML files
- Replace placeholder text with your own information
- Update skills, projects, education, and experience details

### Profile Photo

1. Add your professional photo to the `assets` directory
2. Update the image path in `about.html`:
   ```html
   <img src="assets/your-photo.jpg" alt="Your Name" class="photo-placeholder">
   ```

### Projects

1. For each project, modify the project information in `projects.html`
2. Add your project images to the `assets` directory
3. Update the background image paths for project cards

### Contact Information

- Update your email, phone, and location in `contact.html`
- Add your actual map embed code if desired

### Social Links

- Update the social media links in the footer of each page:
  ```html
  <a href="https://github.com/yourusername" class="social-icon"><i class="fab fa-github"></i></a>
  ```

### Color Theme

- To change the color scheme, edit the CSS variables in `styles.css`:
  ```css
  :root {
      --primary-color: #4e54c8;
      --secondary-color: #8a2be2;
      --accent-color: #e9486e;
      /* other colors... */
  }
  ```

## Credits

- Font Awesome for icons
- Google Fonts for typography
- Unsplash for placeholder images (if used)

## License

This project is available for personal use. Feel free to modify and adapt it for your needs.

---

Created with 💜 for your professional portfolio needs. 