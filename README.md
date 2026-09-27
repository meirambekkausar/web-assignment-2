# Assignment 2 - Advanced CSS (Flexbox & Grid)

**Student:** Kaussar Meirambekkyzy  
**Group:** IT-2513

---

## Part 1. Flexbox

### Task 0 & Task 1: Navbar and Character Cards
In the first part, I worked with Flexbox for both the header and the cards.
- The navigation bar uses display flex with space-between to keep the brand on the left and links on the right, centered vertically.
- For the cards, I chose 3 of my favorite Game of Thrones characters (Robb Stark, Margaery Tyrell, and Jaime Lannister). They are aligned horizontally in a row with a 20px gap. All cards stay equal in height, and there is a smooth lift hover effect when pointing at them.

![Task 0 and Task 1](screenshots/task1.png)



## Part 2. Grid System

### Task 2: Page Layout with Grid Areas
In this task, I practiced building a complete page structure using CSS Grid template areas.
- Set up a layout with header across the top, sidebar on the left, main content on the right, and footer at the bottom.
- Assigned each section to its area using grid-area names so everything stays organized.

![Task 2](screenshots/task2.png)

### Task 3: Image Gallery
Here I built a 3x3 photo gallery showcasing Margaery Tyrell's dresses and outfits.
- The gallery is a CSS Grid with 3 equal columns and uniform gaps.
- The photos use object-fit contain so the dresses are fully visible without being cropped.
- Each image has a hover overlay that displays the name of the outfit when you hover over it.

![Task 3](screenshots/task3.png)



## Part 3. Combining Flexbox & Grid

### Task 4: Portfolio Page
For the final task, I combined both layout models to create a portfolio page for Margaery Tyrell.
- Flexbox is used in the header for the logo and navigation links.
- CSS Grid splits the main area into two columns: royal initiatives on the left and the bio/skills sidebar on the right.
- Inside each initiative card, Flexbox arranges the title, description, and button, pushing the button to the bottom so cards look consistent.
- The footer spans across the whole bottom of the page.

![Task 4](screenshots/task4.png)



## Work Process Summary
1. Set up basic resets and box-sizing border-box.
2. Used Flexbox for simple 1D layouts like the navbar and the row of character cards.
3. Used CSS Grid for 2D layouts like the page structure and the 3x3 photo gallery.
4. Combined both techniques in Task 4 to build a complete portfolio layout.
