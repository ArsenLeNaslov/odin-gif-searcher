# Odin's GIF searcher

A small client-side web application built to practice working with external APIs using the Fetch API. It allows users to dynamically retrieve and display GIFs without reloading the page, reinforcing core concepts such as asynchronous JavaScript, promise handling, and basic error management.

Referencing Odin's Assignment: [To Do List App](https://www.theodinproject.com/lessons/node-path-javascript-todo-list)

Live preview https://arsenlenaslov.github.io/odin-gif-searcher/

<img width="1429" height="1187" alt="image" src="https://github.com/user-attachments/assets/43009453-1f47-4f16-9e6b-32de0b936d19" />

#Features
- **Fetches GIFs** from a public GIF API using the Fetch API. Reference: [MDN Web Docs, Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)
- **Displays a GIF** on page load and updates the image dynamically when requested, demonstrating DOM manipulation combined with asynchronous data fetching.
- **Includes a search input** that lets users query GIFs by keyword
- **User input is passed** as a query parameter to the API request
- **Provides a button to fetch** a new GIF without refreshing the page. This reinforces event handling and state updates in JavaScript
- **Handles API-related** errors gracefully_
  - **Non-2xx HTTP responses** are checked manually using the Response object
  - **JavaScript runtime errors** are caught using .catch() for safer execution. Reference: [MDN Web Docs, Response interface](https://developer.mozilla.org/en-US/docs/Web/API/Response)

## Credits
- Created by [ArsenLeNaslov](https://github.com/ArsenLeNaslov) for [The Odin Project](https://www.theodinproject.com/) 🎴
