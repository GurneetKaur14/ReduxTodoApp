# 📝 Redux ToDo App (React Native)

A React Native ToDo application built with **Redux Toolkit**, demonstrating **state management fundamentals** using slices, actions, and reducers.

---

## 🚀 Project Overview

This lab project teaches how to integrate **Redux Toolkit** in a React Native app to manage application state efficiently.

- Configured a Redux store using `@reduxjs/toolkit`
- Created and used Redux slices with actions and reducers
- Connected React Native components to Redux using `useSelector` and `useDispatch`
- Implemented CRUD operations and filtering in a ToDo list

---

## Folder Structure
ReduxTodoApp/
├── src/
│   ├── store/
│   │   ├── index.js
│   │   └── todosSlice.js
│   ├── screens/
│   │   └── TodoListScreen.js
└── App.js

---

## 🏗️ Setup Instructions

### Create Project
npx react-native init ReduxTodoApp
cd ReduxTodoApp
npm install @reduxjs/toolkit react-redux
npm install react-native-vector-icons

- Create desired components
- Wrap App.js with Redux Provider
- Build and run the app