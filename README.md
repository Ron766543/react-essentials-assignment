# React Essentials Assignment (Parent Repository)

This repository organizes multiple ReactJS applications using **Git submodules**.
It contains the following projects:

## 📂 Projects Included

1. **Portfolio Card Application**
    - Path: `PortfolioCard`
    - GitHub Repo: [Ron766543/-react-essentials-assignment1](https://github.com/Ron766543/-react-essentials-assignment1)

2. **ZMovies Database Mini Application**
    - Path: `zmovies-database`
    - GitHub Repo: [Ron766543/react-essentials-assignment2](https://github.com/Ron766543/react-essentials-assignment2)

---

## 🚀 How to View the Projects

### Step 1: Clone the parent repository

```bash
git clone https://github.com/username/react-essentials-assignment.git
cd react-essentials-assignment
```

### Step 2: Initialize submodules

```bash
git submodule update --init --recursive
```

### Step 3: Navigate into a project and run

For Portfolio Card:

```bash
cd PortfolioCard
npm install
npm start
```

For ZMovies Database:

```bash
cd ../zmovies-database
npm install
npm start
```

---

## 📝 Notes

- Each project has its own dependencies and can be run independently.
- The parent repo simply groups them together for easy access.
- Recruiters or collaborators only need to clone this parent repo once, then initialize submodules to explore both apps.
