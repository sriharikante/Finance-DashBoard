# Personal Finance Dashboard 💰

A front-end UI project I built while learning Bootstrap 5.
It's not connected to any backend — just HTML, CSS and Bootstrap for now.

---

## What is this?

This is a simple dashboard where you can see your income, expenses, savings
and recent transactions — all in one place. I made this as a practice project
to get better at Bootstrap layout and responsive design.

No frameworks, no npm, no complicated setup. Just open the HTML file and it works.

---

## Features

- Navbar with username and avatar
- Sidebar with navigation links (collapses on mobile)
- 4 summary cards — Balance, Income, Expenses, Savings
- Recent transactions table with Income/Expense badges
- Add Transaction form with category dropdown
- Responsive on mobile, tablet and desktop
- Small custom CSS on top of Bootstrap

---

## Folder Structure

```
finance-dashboard/
│
├── index.html
├── css/
│   └── style.css
└── README.md
```

---

## How to run it

No setup needed honestly.

1. Download or clone the project
2. Open `index.html` in your browser
3. That's it

---

## What I found difficult

- Getting the sidebar and main content to sit side by side properly took me a while
- The sidebar collapse on mobile was confusing at first — had to read Bootstrap docs twice
- Making the table scroll on small screens without breaking the layout
- Keeping the cards same height using `h-100` — didn't know about that before

---

## What I learned

- How Bootstrap grid system actually works (`col-12 col-sm-6 col-xl-3`)
- Using `d-flex` for layouts instead of floats
- `table-responsive` wrapper for mobile tables
- Bootstrap's `collapse` component for the mobile menu
- How small CSS changes like `border-radius` and `box-shadow` make things look cleaner
- Writing cleaner, more readable HTML with proper spacing

---

## Tech used

- HTML5
- CSS3
- Bootstrap 5 (CDN)
- No JavaScript frameworks

---

## Screenshots

> Will add screenshots soon — still cleaning up a few things

---

## What I want to add later

- [ ] Connect form to localStorage so data actually saves
- [ ] Add a simple chart for monthly spending
- [ ] Dark mode toggle
- [ ] Filter transactions by category

---

## Notes

This project is not perfect and I know there are things to improve.
Built this step by step while learning — so the code might not be the cleanest
but it works and I understood everything I wrote.

Feel free to use it or suggest improvements.

---

*Made by Alex — still learning, always building* 🚀
