# Game of War 🃏

Game of War is a **simple browser-based card game** built using **Vanilla JavaScript** and the **Deck of Cards API**.  
The player competes against the computer by drawing cards—whoever draws the higher card wins the round.

This project demonstrates **API integration, game logic, DOM manipulation, and state management**.

---

##  How the Game Works

1. Click **New Deck** to shuffle a fresh deck.
2. Click **Draw Cards** to draw two cards:
   - One for the computer
   - One for the player
3. The card with the higher value wins the round.
4. Scores update automatically.
5. When all cards are used, the game ends.

---

##  Features

- Real-time card drawing from an external API
- Computer vs Player gameplay
- Automatic score tracking
- Remaining card count display
- Button state control (disabled when deck is empty)
- Simple and clean UI

---

##  Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- Fetch API
- Deck of Cards API (via Scrimba proxy)

---

##  API Used

- **Deck of Cards API**  
  Provides shuffled decks, card images, and card data.

---

##  Project Structure
game-of-war/
│
├── index.html
├── style.css
├── index.js
└── README.md


---

## Key Concepts Demonstrated

- Fetching data from APIs
- Game logic implementation
- State management using variables
- Event listeners
- Conditional logic
- DOM updates
- Button enable/disable handling

---

## Card Comparison Logic

Card values are compared using a predefined ranking order:
2 < 3 < 4 < 5 < 6 < 7 < 8 < 9 < 10 < JACK < QUEEN < KING < ACE
The higher-ranked card wins the round.

---

##  How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/Damu987/Game-of-war.git


* Open index.html in your browser.
* Click New Deck to start the game.
* Click Draw Cards to play.

## Screenshots

<img width="400" height="400" alt="Image4 1" src="https://github.com/user-attachments/assets/beb8c19a-7b4a-46c9-a32e-ec23a3b6aff9" />
<img width="400" height="400" alt="Image4 2" src="https://github.com/user-attachments/assets/188fd945-7cc5-4d45-b4a2-0920c8d100e2" />

## Future Enhancements

* Declare final winner when the game ends
* Add sound effects and animations
* Mobile responsiveness improvements
* Restart game button
* Player name input

## Author

Damini S
Frontend Developer (Fresher)
Interested in interactive JavaScript projects and game logic

GitHub: https://github.com/Damu987

📄 License

This project is licensed under the MIT License.


 
