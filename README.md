Exploring State Management in React
I recently worked on a small project to understand and demonstrate state management in React. This project involves two main components: a LikeButton and a Counter. Here’s a brief overview of the implementation:

LikeButton Component
The LikeButton component allows users to toggle a "like" state. It uses React's useState hook to manage two states:

isLiked to track whether the button is liked or not.
clicks to count the number of times the button has been clicked.
When the button is clicked, the toggleLike function toggles the isLiked state and increments the clicks count. Depending on the isLiked state, the button displays either a filled heart icon or an outlined heart icon.

Counter Component
The Counter component is a simple counter that increments the count each time the button is clicked. It also uses the useState hook to manage the count state. The incCount function updates the count state by adding 1 every time the button is clicked.

