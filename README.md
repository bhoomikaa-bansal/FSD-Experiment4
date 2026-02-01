# Experiment 4 – React State Management 

## Project Title
**Implementation of Local and Global State Management Handling in React Applications**

---

## Purpose
This project demonstrates two essential state management approaches in React:
1. **Component-Level Counter** – Built using React Hooks for isolated state
2. **Application-Wide Counter** – Built using Redux for centralized state sharing

---

## Experiment Number
**Experiment – 4**

---

## Description of the Experiment

This React application showcases the distinction between managing state at the component level versus managing it globally across the entire application.

- **Component-Level Counter** uses the `useState` hook to keep state within a single component, demonstrating how to handle state locally.
- **Application-Wide Counter** leverages **Redux** for centralized state storage, allowing multiple components to access and modify the same state through a unified Redux store and Provider pattern.

Through this experiment, developers gain insight into state management patterns at different levels in a React application, and learn when to apply each approach in different scenarios.

---

## Core Technologies

- React JS
- Redux
- React-Redux
- Vite
- JavaScript (ES6+)
- HTML & CSS

---

## Features Implemented

- Counter operations such as increment, decrement, and reset 
- Component-scoped state using `useState` hook
- Centralized state management via Redux Store
- Modular and maintainable component structure

---

## 📁 Experiment Structure

<pre>
src/
│── assets/
│
│── components/
│   └── context/
│     ├── CounterGlobalContextAPI.jsx
│   ├── CounterGlobalContextParent.jsx
│   ├── CounterLocalState.jsx
│   └── CounterReduxParent.jsx
│
│── store/
│   ├── CounterReducer.jsx
│   └── Store.jsx
│
│── App.css
│── App.jsx
│── index.css
│── main.jsx
</pre>

---

## KLearning Outcomes

Upon finishing this project, you will have developed the ability to:

1. Grasp the fundamentals of **React state**
2. Compare **component-level state with application-level state**
3. Use the `useState` hook for managing component state
4. Set up and configure a **Redux store**
5. Design scalable and maintainable React architectures

---

## Deployed on Platforms

- The full project source code is available on **GitHub** for version control and collaboration.
- The application is live on **Netlify**, providing public access to the working demo.

---

## Summary

This experiment effectively illustrates state management principles in React using both localized and global strategies. It equips learners with practical experience in Redux implementation and prepares them to handle state management in complex, production-grade applications.

---

**Submitted as part of React JS Laboratory – Experiment 4**


