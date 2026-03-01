# 🚀 React + TypeScript: Migration Exercise

This project is a practical exercise focused on migrating an existing **React (JavaScript)** application to **TypeScript**. The primary goal was to implement static typing to ensure better code reliability, safety, and a superior developer experience.
From Scrimba.

---

## 🎯 Exercise Objectives
* Configure the development environment for TypeScript support.
* Convert `.js` and `.jsx` files to `.ts` and `.tsx`.
* Define **Interfaces** and **Types** for Props and State.
* Resolve compilation errors and eliminate the `any` type where possible.
* Properly type form events and DOM references.

## 🛠️ Key Steps Taken

Here is a summary of the migration process:

1. **Configuration:** Installed necessary dependencies (`typescript`, `@types/react`, `@types/react-dom`) and initialized the `tsconfig.json` file.
2. **File Conversion:** Systematically renamed files from `.js`/`.jsx` to `.ts`/`.tsx`.
3. **Component Refactoring:** Replaced `PropTypes` with TypeScript **Interfaces** for better IDE autocompletion.
4. **Typed Hooks:** Applied specific types to Hooks

---

## 💻 Technologies Used
* **React** (Core Library)
* **TypeScript** (Static Typing)
* **Vite** (Build Tool)

---

## 🚀 How to Run the Project

1. **Clone the repository:**
   ```bash
   git clone git@github.com:DrummerTriga/typescript_practice.git
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```
3. **Start the development server:**
   ```bash
   npm run dev
   ```
