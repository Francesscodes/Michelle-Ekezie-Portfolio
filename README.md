# Michelle Ekezie Portfolio

A professional, responsive portfolio website showcasing Michelle Ekezie's work as CEO of **Chelle's Dessert** - a premium dessert brand specializing in custom cakes, pastries, and catering services.


 About

This portfolio website highlights Michelle Ekezie's expertise in:
- **Custom Cake Design** - Wedding cakes, birthday cakes, and special occasion desserts
- **Premium Desserts** - Tiramisu, pastries, and gourmet treats
- **Catering Services** - Full-service event catering and dessert tables
- **Pastries & Confectioneries** - Small chops, finger foods, and artisanal baked goods

 Features

-  Fully Responsive Design - Optimized for desktop, tablet, and mobile devices
-  Modern UI/UX - Clean, elegant design with smooth animations
-  Interactive Gallery- Lightbox feature to showcase dessert creations
-  Dynamic Service Tabs - Easy navigation through different service offerings
-  Contact Form- Integrated form for client inquiries
-  Smooth Animations - Swiper carousel and scroll effects
-  Active Navigation - Highlights current section while scrolling
-  Social Media Integration - Direct links to Facebook and Instagram

Technologies Used

- HTML5 - Semantic markup
- CSS3 - Custom styling with CSS Grid and Flexbox
- JavaScript (ES6) - Interactive functionality
- [Swiper.js](https://swiperjs.com/)- Touch-enabled image carousel
- [Boxicons](https://boxicons.com/) - Beautiful icon library
- [Formspree](https://formspree.io/) - Contact form backend

 Project Structure

```
michelle-ekezie-portfolio/
│
├── index.html          # Main HTML file
├── style.css           # Stylesheet
├── script.js           # JavaScript functionality
├── README.md           # Project documentation
│
└── image/              # Image assets folder
    ├── michelle.png
    ├── image 1.png
    ├── image 2.png
    ├── tiramisu-dessert.webp
    ├── RED-VELVET.jpg
    ├── kid cakes.jpg
    ├── wedding cake.jpg
    ├── small chops.png
    ├── caterring.jpg
    └── ... (other images)
```

 Getting Started

 Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic understanding of HTML/CSS/JavaScript (for customization)

 Installation

1. Clone the repository
   ```bash
   git clone https://github.com/francesscodes/michelle-ekezie-portfolio.git
   ```

2. Navigate to the project directory
   ```bash
   cd michelle-ekezie-portfolio
   ```

3. Add your images
   - Place all image files in the `image/` folder
   - Ensure filenames match those referenced in `index.html`

4. Configure the contact form
   - Sign up for a free account at [Formspree](https://formspree.io/)
   - Replace `YOUR_FORM_ID` in `index.html` (line 243) with your actual Formspree form ID:
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST" class="contact-form">
   ```

5. Open in browser
   - Simply open `index.html` in your web browser
   - Or use a local server (recommended):
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (with http-server)
   npx http-server
   ```

Customization

Changing Colors

Edit the CSS variables in `style.css`:

```css
:root {
  --first-hue: 258;        /* Primary color hue */
  --second-hue: 225;       /* Secondary color hue */
  --first-color: hsl(var(--first-hue), 54%, 48%);
  --title-color: hsl(var(--second-hue), 64%, 18%);
  /* ... other color variables */
}
```

Adding New Gallery Images

1. Add image to the `image/` folder
2. Insert new gallery item in `index.html`:
```html
<div class="work-content">
    <img src="image/your-new-image.jpg" alt="Description">
    <div class="work-overlay"></div>
    <i class="bx bx-camera work-overlay-icon"></i>
</div>
```

 Modifying Services

Edit the service sections in `index.html` (lines 140-207) to update service descriptions, images, or add new services.

 Responsive Breakpoints

- Desktop: 1024px and above
- Tablet: 768px - 1023px
- Mobile: 576px - 767px
- Small Mobile: Below 576px


 Contact Information

- Email: michelleekezie@gmail.com
- Phone: 08163122919
- Location: Ago Palaceway Okota, Lagos, Nigeria
- Facebook: [Michelle Ekezie](https://web.facebook.com/michelleijeoma.ekezie.9/)
- Instagram: [@chelles_desserts](https://www.instagram.com/chelles_desserts/)

Developer

Developed by: [Francess Ekezie](mailto:ekezieezinne@gmail.com)  

 License

This project is open source and available under the [MIT License](LICENSE).

 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/yourusername/michelle-ekezie-portfolio/issues).

 Show Your Support ; Give a ⭐️ if you like this project!


© 2024 Michelle Ekezie | Chelle's Dessert. All Rights Reserved.**
