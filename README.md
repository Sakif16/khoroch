# Khoroch
## Intro
A family expense tracking web app where members can join a shared group, log their spending, and view each other's expenses transparently — month by month.

---

## Description
Khoroch (খরচ) is a full-stack web application built for families who want to track their collective monthly expenses. After signing up, a user can create a family group or join one using a shared code. Once inside, every member can log their own expenses, and the entire family can see the breakdown — by member and by category.

## Website: https://khoroch.onrender.com/

### What you can do:
- Sign up and sign in with email and password
- Create a family group with a unique auto-generated code
- Join an existing family using the shared code
- Log expenses with a title, amount, category, and date
- View your personal spending stats for the current month
- See the full family total and your percentage share
- Browse recent expenses logged by all family members
- View member-wise and category-wise spending breakdowns

---

## Tech Stack
- **Next.js** (App Router)
- **TypeScript**
- **Tailwind CSS**
- **BetterAuth** (authentication & user management)
- **MongoDB** (database)
- **Mongoose** (schemas)
- **Render** (deployment)

---


## Contributions
Contributions are welcome!

### You can contribute by:
- Reporting bugs or issues
- Suggesting new features or improvements
- Refactoring code for better performance or readability
- Improving the UI or adding responsive design
- Enhancing documentation

### How to contribute:

### 1) Fork the repository

### 2) Clone your fork
```bash
git clone https://github.com/YOUR_USERNAME/kharoch.git
```

### 3) Create a new branch
```bash
git checkout -b feature-name
```

### 4) Make your changes and commit
```bash
git commit -m "Add: your feature description"
```

### 5) Push to your fork
```bash
git push origin feature-name
```

### 6) Open a Pull Request on GitHub

---

## ⚠️ Known Issues
- Month navigation not implemented yet
- No loading states
- Expense deletion is not yet supported
- No pagination on the recent expenses list — limited to the last 10 entries

---

## Future Development
- Month navigation to browse expenses from past months
- Expense deletion and editing
- Push or email notifications when a family member logs an expense
- Pagination or infinite scroll on the expense list
- Export expenses as CSV or PDF
- Charts and visual spending trends over multiple months
- Dark mode support

### Fun Fact
This app was originally founded because my girlfriend thought I was spending too much money on Domino's
