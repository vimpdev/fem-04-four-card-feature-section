# 🚀 Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK).  
A responsive four card feature section built with semantic HTML and modern CSS.  
This solution focuses on clean layout architecture, native CSS nesting, and accessibility best practices.

---

## 🎬 Demo

<p align="center"> <img src="./docs/demo.gif" alt="Animated demo of the responsive four card feature section layout" /> </p>

---

## 📸 Screenshots

### 📱 Mobile

<p align="center"> <img src="./docs/mobile-default.avif" alt="Mobile layout showing stacked feature cards" /> </p>

### 💻 Desktop

<p align="center"> <img src="./docs/desktop-default.avif" alt="Desktop layout showing asymmetric grid arrangement of feature cards" /> </p>

### 💻 Interaction - Hover & Focus-Visible

<p align="center"> <img src="./docs/desktop-interaction.avif" alt="Hover and focus-visible interaction states on attribution links" /> </p>

---

## 🔗 Links

- 🌎 [Live site](https://vimpdev.github.io/fem-04-four-card-feature-section/)

<!-- - 👩‍💻 [Frontend Mentor solution](https://your-solution-url.com) -->

---

## 🛠️ Built with

- Semantic HTML5
- CSS custom properties
- Native CSS Nesting
- CSS Grid (with `grid-template-areas`)
- Logical properties (`inline-size`, `block-size`)
- Mobile-first workflow
- Modern accessibility practices

---

## 🧠 Technical Highlights

### 1️⃣ Grid Architecture with Template Areas

The layout uses grid-template-areas to create an asymmetric card distribution across breakpoints:

- Single column on mobile
- Two-column structured layout on tablet
- Three-column asymmetric grid on desktop

This approach keeps layout logic explicit and readable.

### 2️⃣ Native CSS Nesting

Styles are organized using native CSS nesting, including:

- Nested element selectors
- Media queries inside components
- Pseudo-classes like :hover, :focus-visible
- Pseudo-elements like ::after

Example pattern used:
```js
.features__header {
  h1 {
    span {
      font-weight: 200;
    }
  }

  @media (width >= 1366px) {
    padding-top: 6.5rem;
  }
}
```
This improves readability and keeps related styles grouped.

### 3️⃣ Accessibility Considerations

- Proper heading hierarchy
- `visually-hidden` utility for screen readers
- `aria-hidden="true"` on decorative images
- `:focus-visible` for keyboard accessibility
- Meaningful `og:image:alt` and `twitter:image:alt` meta tags

### 4️⃣ Component Responsibility

The .card component uses a controlled max-inline-size to prevent excessive growth when spanning multiple grid areas, ensuring visual balance across breakpoints.

---

## 📈 What I learned

- How `grid-template-areas` interacts with column sizing across breakpoints
- When to control width at layout level vs component level
- How native CSS nesting improves maintainability
- The importance of logical properties for more flexible layouts
- The difference between visual structure and semantic structure

---

## 🤖 AI Collaboration

AI tools were used to:

- Refine layout decisions and architectural trade-offs
- Improve commit message clarity
- Optimize meta tag structure
- Review accessibility and semantic decisions

The goal was not code generation, but architectural discussion and refinement.

---

## 👤 Author

- Frontend Mentor - [@vimpdev](https://www.frontendmentor.io/profile/vimpdev)