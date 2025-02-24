# popCorn-app
# PopCorn App

## Overview

Welcome to the PopCorn App! 🍿

This project was built as part of my learning journey with React. The goal was to create a simple movie search and management app while learning important React concepts like **props**, **prop drilling**, **component composition**, **state management**, **hooks**, and **custom hooks**.

In this project, I implemented a movie search feature where users can search for movies, view their details, and manage a "watched" list. The app stores watched movies using **localStorage**, and provides a rating feature for movies. The project was structured using functional components and React hooks.

## Features

- **Movie Search**: Search for movies using an API and display the results.
- **Movie Details**: View detailed information about a movie (rating, director, plot, etc.).
- **Watched List**: Add movies to a watched list and track the rating and runtime.
- **Custom Hooks**: Implemented a custom hook to manage local storage (`useLocalStorage`) and handle key events (`useKey`).
- **State Management**: Used React's `useState` for local component state and `useEffect` for side effects.
- **Component Composition**: Used component composition to pass children components and reuse UI components.

## Key Concepts Learned

### 1. **Props & Prop Drilling**
Props are used to pass data between components. I also learned how prop drilling works when passing props from parent to nested components. In the future, I plan to improve this by using **Context API** or **Redux** for state management to avoid deep prop drilling.

### 2. **Component Composition**
Instead of passing all props directly, I explored component composition. This allows me to structure my components in a more modular way, where child components are passed as elements or children, making the app more flexible and reusable.

### 3. **State Management**
I used React's `useState` hook to manage the state across components, including managing the search query, selected movie, and watched movies list. This allowed me to keep track of the app's dynamic state in response to user interactions.

### 4. **Hooks**
I learned how to use React hooks, including:
   - `useState`: To manage component state.
   - `useEffect`: To perform side effects like fetching data from an API or setting the document title.
   - `useRef`: To access DOM elements directly and manage focus.
   - **Custom Hooks**: I created custom hooks like `useLocalStorage` for persistent data storage and `useKey` for handling key press events (like the Escape key).

### 5. **Event Handling**
The app listens for user interactions like typing in the search input, clicking on movies, and pressing the Escape key to close movie details. Custom event handling functions were used to manage these interactions effectively.

## Getting Started

To run the PopCorn App locally, follow these steps:

### Prerequisites
- Node.js and npm installed on your machine.
  You can download Node.js from [here](https://nodejs.org/).

### 1. Clone the Repository

```bash
git clone https://github.com/salman9011/popCorn-app.git
