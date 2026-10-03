# 🐍 Snake Game (Python & Tkinter)

A classic Snake game with a graphical window, built with Python and the Tkinter library. Control the snake, eat the food, and try to get the highest score without hitting the walls or yourself!

## ✨ Features

- Graphical game window (Tkinter)
- Control the snake with the keyboard arrow keys
- Random food placement
- Live score counter
- Snake grows each time it eats
- Game over when hitting a wall or the snake's own body
- Game window automatically centered on the screen

## 🛠️ Requirements

- Python 3.6 or higher
- Tkinter (included with Python on Windows and macOS)

On some Linux systems, you may need to install Tkinter first:
```bash
sudo apt install python3-tk
```

## 🚀 How to Run

1. Clone this repository or download the files:
```bash
   git clone https://github.com/YOUR-USERNAME/snake-game.git
```
2. Go to the project folder:
```bash
   cd snake-game
```
3. Run the game:
```bash
   python snake_game.py
```

## 🕹️ Controls

| Key | Action |
|-----|--------|
| ⬆️ Up Arrow | Move up |
| ⬇️ Down Arrow | Move down |
| ⬅️ Left Arrow | Move left |
| ➡️ Right Arrow | Move right |

## 🎯 How to Play

1. The snake starts moving automatically.
2. Use the arrow keys to guide it toward the red food.
3. Each food you eat gives you +1 point and makes the snake longer.
4. The game ends if the snake hits the edge of the window or its own body.

## 🔧 Customization

You can easily change the game at the top of the code:

```python
GAME_WIDTH = 1400
GAME_HEIGHT = 600
SPEED = 50            # lower = faster
SNAKE_COLOR = "Blue"
FOOD_COLOR = "Red"
```

## 📚 What I Learned

- Building a graphical interface with Tkinter
- Using classes (`Snake` and `Food`)
- Handling keyboard events with `bind`
- Updating the game with `window.after`
- Detecting collisions
- Using global variables carefully

## 🔮 Future Improvements

- Add a restart button after Game Over
- Save the high score
- Add difficulty levels
- Add sound effects

## 👤 Author

**Mehdi**
GitHub: [@ghezzaz-mehdi-dev](https://github.com/ghezzaz-mehdi-dev)
