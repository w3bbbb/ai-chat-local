# Chatbot Application with Modern Web Technologies

This project is a browser-based chatbot application. It integrates a Machine Learning Cloud Engine (MLC) model for dynamic AI interactions.

## Table of Contents

1. [Features](#features)
   - [HTML Features](#html-features)
   - [CSS Features](#css-features)
   - [JavaScript Features](#javascript-features)

---

## Features

### HTML Features
- **`<template>` Tag**  
  Defines reusable fragments of markup that are not rendered until explicitly instantiated. Used for dynamically creating chat messages and ensuring consistent styling and structure.

### CSS Features
- **`dvh` (Dynamic Viewport Height)**  
  Ensures correct sizing of content even when mobile browser UI elements like the address bar change the viewport height.

- **`scroll-behavior: smooth;`**  
  Provides smooth scrolling, enhancing user experience when navigating through the chat interface.

- **Nested Selectors**  
  Improves CSS structure and readability. Example:
  ```css
  .message {
    span {
      width: 36px;
      height: 36px;
    }
  }

### JavaScript Features
- **`<script type="module">` Tag**
   With this approach you can use the import and export keywords.
