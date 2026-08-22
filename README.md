### Netflix Clone (Frontend)

Hey there! This is a pixel-perfect clone of the Netflix landing page built from scratch using pure HTML and CSS. I built this to practice my layout skills, especially working with Flexbox, CSS Grid, and building custom components without relying on external UI libraries. 

### ✨ Features

* **Immersive Hero Section:** Full-screen background layout with a dark overlay, customized input fields, and the classic red Netflix call-to-action buttons.
* **Trending Carousel:** A horizontal movie slider featuring large background rank numbers (1-10) with a clean text-stroke effect. It includes smooth horizontal scroll snapping.
* **Feature Cards:** Built using CSS linear gradients and Flexbox to replicate Netflix's information cards.
* **FAQ Accordion Setup:** Styled question boxes that mimic the interactive layout of the actual site.
* **Footer Layout:** A clean 4-column responsive grid layout complete with a custom language selector dropdown.

### 🛠️ Built With

* **HTML5:** Semantic structuring for accessibility and SEO.
* **CSS3:** Flexbox, CSS Grid, linear-gradients, absolute positioning, custom scrollbar overrides, and scroll-snap.

### 💡 What I Learned / Challenges Fixed

* **Handling Layout Gaps:** Figured out how default browser margins and block-level dimensions can throw off a footer structure, fixing it using width: fit-content and proper margin control.
* **Text Stroke Effects:** Learned how to style hollow numbers using -webkit-text-stroke to get that exact look for top trending movies.
* **Custom Scrollbars:** Implemented ::-webkit-scrollbar { display: none; } to keep the layout incredibly clean while still allowing horizontal swipe mechanics.