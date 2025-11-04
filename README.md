# Frontend Mentor - Stats preview card component

This is a solution to the [Results summary component on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62).  
Frontend Mentor challenges help you improve your coding skills by building realistic projects.

---

## 📸 Screenshot

![Screenshot of my solution](./preview.png)

---

## 🔗 Links

- **Solution URL:** [https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62?tab=report](#)
- **Live Site URL:** [https://fransantos103.github.io/frontendMentorEasy-Stats-preview-card-component/](#)

---

## 💻 My process

### Built with
- Semantic **HTML5** markup  
- **CSS3** (Flexbox, custom fonts)  
- Responsive design principles  

---

## 🧠 What I learned

While working on this project, I reinforced my understanding of:
- Using **semantic HTML** (`<main>`)
- Creating **centered layouts** with Flexbox  
- Designing **consistent color palettes and hover effects**

Here’s a little code snippet I’m proud of:

.cardImage {
  flex: 1.08;            
  position: relative;     
  border-top-right-radius: 10px;
  border-bottom-right-radius: 10px;
  overflow: hidden;     
}

img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;  
  filter: brightness(0.9);
}

.cardImage::after {
  content: "";
  position: absolute;
  inset: 0;
  background: hsl(277, 64%, 61%);
  mix-blend-mode: multiply;
  pointer-events: none;
}
