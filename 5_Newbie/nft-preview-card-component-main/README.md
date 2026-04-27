# </> Frontend Mentor - NFT Preview Card Component

<div align="center">
  <img src="images/screenshot.jpg" alt="Design preview for the NFT preview card component" width="600" />
</div>

<br>

<div align="center">
  <h3>
    <a href="#">Live Demo</a>
    <span> | </span>
    <a href="#">Github</a>
  </h3>
</div>

<div align="center">
  <p>An NFT preview card component challenge from <a href="https://www.frontendmentor.io/" target="_blank">Frontend Mentor</a>.</p>
  <p>
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
    <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
    <img src="https://img.shields.io/badge/FLEXBOX-8A2BE2?style=for-the-badge&logo=css3&logoColor=white" alt="Flexbox" />
    <img src="https://img.shields.io/badge/GRID-4CAF50?style=for-the-badge&logo=css3&logoColor=white" alt="Grid" />
  </p>
</div>

---

## 📝 Project Overview

This project is my solution to the [NFT Preview Card Component Challenge](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdBECGAm) from Frontend Mentor.  
The goal was to build a visually attractive, accessible card component that highlights an NFT, its meta-data, price, countdown, and creator info—with a focus on crisp CSS effects and clean HTML structure.

---

## 🚀 Features

- **Fully Responsive Layout:** Uses modern CSS Grid and Flexbox to center and adapt the card on any screen size.
- **Interactive Hover Effects:**  
  - Subtle color and image overlay transitions when hovering over the card image, NFT title, and creator name.
  - Minor UI enhancements for better engagement with key information.
- **Custom Image Overlay:**  
  - Achieved using absolute positioning and CSS gradients with an icon, for an elegant, interactive user experience.
- **Accessible & Semantic HTML:**  
  - Uses meaningful tags for better accessibility and SEO.
- **CSS Variables for Theming:**  
  - All colors and typography are handled via custom properties for easy project-wide changes.

---

## 💡 Key Learnings

- **CSS Variables:**  
  Using `:root` for global color and typography management made the code much more maintainable and ready for theming or style changes in the future.
- **Overlay Techniques:**  
  I leveraged absolute positioning and `background-blend-mode` with both gradient and icon layered seamlessly, ensuring the overlay effect could be achieved with minimal markup.
- **Component-Based Layout:**  
  Building the card with a clear separation of content sections helped in scaling and future-proofing similar UI projects.
- **Hover & Transition States:**  
  Focused on making each hover action feel smooth and accessible, without unnecessary JS or extra elements.
```
.card-image-overlay { 
border-radius: 5px; 
position: absolute; 
inset: 0; 
background: linear-gradient(rgba(0,255,247,0.5), rgba(0,255,247,0.5)), url('images/icon-view.svg') center no-repeat;
 background-blend-mode: multiply; 
 opacity: 0; 
 transition: opacity 0.3s; 
 pointer-events: none; 
 }
.card-image:hover .card-image-overlay { 
opacity: 1; 
}

```

---

## 📦 Built With

- HTML5 (semantic, accessible markup)
- CSS3 (Flexbox, Grid, custom properties, transitions)
- Responsive, mobile-friendly design
- Minimal JavaScript (if any, for extra interactivity)

---

## 🎯 What I Would Improve Next

- Add keyboard navigability and ARIA roles for even better accessibility.
- Explore more advanced BEM naming for even greater scalability.
- Create a "dark/light" theme switcher using the custom properties.

---

## 👤 Author

* LinkedIn – [@HavishyaVally](YOUR_LINKEDIN_URL)
* Frontend Mentor – [@HavishyaVally](https://www.frontendmentor.io/profile/HavishyaVally)
* GitHub – [@HavishyaVally](YOUR_GITHUB_URL)

---

**Thanks for checking out my solution! Feedback and suggestions are always welcome.**