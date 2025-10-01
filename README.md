# Tarot Pull Web App

**WORK IN PROGRESS**

This is a personal project—a fun and accessible Tarot card shuffler and draw web app!  
It’s a work in progress and will be updated periodically as I experiment and learn.

![ezgif-4238c483bac038](https://github.com/user-attachments/assets/c576bcbe-4d03-451b-b000-cfa35ad0b196)

## Features

- Shuffle a full tarot deck and draw cards
- Accessible, WCAG-compliant design -- IN PROGRESS 
- Keyboard and screen reader friendly -- IN PROGRESS (so far so good! Testing with VoiceOver on Mac)
- Whimsical, magical gothic theme -- Styling will happen eventually! 

## How to Use

1. Clone or download this repository.
2. Open `index.html` in your browser (or use [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) in VS Code for live preview).
3. Shuffle the deck and draw cards!

## How it Works
This little web app works like a virtual deck of cards. You can shuffle the deck and then draw cards one by one. Here’s what’s happening behind the scenes in simple steps:
1. The Deck
- The app starts with a full list of cards (stored in another file called tarot-deck.js).
- When you shuffle, it creates a fresh copy of this deck so every shuffle starts with all the cards.
2. Shuffling
- The shuffle mixes the deck randomly, just like physically shuffling a deck of cards.
- It does this by going through the cards and swapping their positions around in a random order.
3. Drawing a Card
- Every time you press the "Draw" button, the app pulls the next card from the shuffled deck.
- The app shows the card’s name, its meaning, and an image (if one exists).
- Once a card is drawn, it’s marked as "used," so you can’t draw the same card twice until you shuffle again.
4. Deck Runs Out
- If you keep drawing until the deck is empty, the app tells you there are no more cards left and prompts you to shuffle again to reset.
5. Button Feedback
- When you click "Shuffle" or "Draw," the button highlights briefly so you know which action you just used.

## Accessibility

- Skip link for keyboard users
- Proper ARIA roles and live regions - IN PROGRESS 
- High-contrast, readable color scheme - Testing with Color Contrast Checker Chrome Extansion 

## Status

This project is just for fun and for refreshing my HTML skills!  
I’ll be updating it as I go—feel free to watch or fork if you’re interested.

---

*Made with curiosity and a little magic.*
