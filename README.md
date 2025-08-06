# Snake Game - Python

एक क्लासिक Snake गेम Python और Pygame में बनाया गया है।

## Features

- क्लासिक Snake gameplay
- स्कोर ट्रैकिंग
- Smooth movement और controls
- Collision detection
- Beautiful grass-pattern background

## Installation

1. पहले Python 3.x install करें
2. Required dependencies install करें:
```bash
pip install -r requirements.txt
```

## How to Play

गेम को चलाने के लिए:
```bash
python snake_game.py
```

### Controls

- **Arrow Keys** - Snake को move करने के लिए
  - ↑ (Up Arrow) - ऊपर
  - ↓ (Down Arrow) - नीचे  
  - ← (Left Arrow) - बाएं
  - → (Right Arrow) - दाएं

### Game Rules

1. Snake को red food तक ले जाएं
2. Food खाने पर Snake बड़ा होता जाता है और score बढ़ता है
3. दीवारों या अपने body से टकराने पर game over
4. जितना ज्यादा food खाएं, उतना ज्यादा score मिलेगा

## Game Features

- **Window Size**: 800x600 pixels
- **Snake**: Green colored blocks
- **Food**: Red colored blocks  
- **Background**: Beautiful grass pattern
- **Score Display**: Top-left corner में

## Technical Details

- Built with Pygame library
- Object-oriented design
- Clean code structure with separate classes for Snake, Food, and Game logic
- 60 FPS smooth gameplay

Enjoy the game! 🐍
