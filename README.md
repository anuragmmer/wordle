# 🎮 Unlimited Wordle

**Play the classic word-guessing game with unlimited rounds!**

🎯 **[Play Now →](https://anuragmmer.github.io/wordle/)**

## How to Play

### The Goal
Guess the hidden 5-letter word in 6 attempts or fewer!

### Game Rules
1. **Enter a word** - Type any valid 5-letter word using your keyboard or the on-screen keyboard
2. **Check your guess** - Press ENTER to submit your word
3. **Read the clues** - Each letter will change color to give you hints:
   - 🟩 **Green** - Correct letter in the correct position
   - 🟨 **Yellow** - Correct letter but in the wrong position  
   - ⬜ **Gray** - Letter is not in the word at all
4. **Use the clues** - Make your next guess based on the feedback
5. **Win or lose** - You have 6 attempts to find the word!

### Features
- 🎲 **Unlimited games** - Play as many rounds as you want
- 📊 **Statistics tracking** - See your win rate, current streak, and total games
- 📱 **Mobile-friendly** - Works perfectly on phones, tablets, and desktop
- 🌙 **Clean dark theme** - Easy on the eyes
- ⚡ **Fast and responsive** - No ads, no sign-ups, just pure gameplay

### Tips for Success
- Start with words that have common vowels (A, E, I, O, U)
- Use words with frequent consonants (R, S, T, L, N)
- Pay attention to letter positioning from yellow clues
- Don't repeat gray letters in future guesses

---

## For Developers

### Tech Stack
- **Pure HTML/CSS/JavaScript** - No frameworks or dependencies
- **Local Storage** - Statistics persist across sessions
- **Responsive Design** - Mobile-first approach with CSS Grid/Flexbox
- **Word List** - 5,700+ words from Stanford's SGB word list

### File Structure
```
├── index.html          # Main game file
├── wordle-words.txt    # Word list (Stanford SGB)
├── meta/
│   ├── icon.png        # Favicon
│   └── cover.png       # Social media preview
└── README.md          # This file
```

### Key Features
- **Dynamic word loading** - Fetches words from external file
- **Shake animation** - Visual feedback for invalid words
- **Auto-clear invalid words** - Automatically removes invalid entries
- **Touch optimization** - Prevents zoom on mobile devices
- **Proper viewport handling** - Uses dynamic viewport height for mobile

### Browser Support
- ✅ Chrome/Edge (Latest)
- ✅ Firefox (Latest) 
- ✅ Safari (Latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

### Local Development
1. Clone the repository
2. Serve files through a local server (due to CORS restrictions on file loading)
3. Open in browser

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Using PHP
php -S localhost:8000
```

### Customization
- **Word list** - Replace `wordle-words.txt` with your own word list
- **Colors** - Modify CSS variables for theming
- **Grid size** - Adjust `maxGuesses` and `wordLength` in JavaScript
- **Statistics** - Data stored in `localStorage` as JSON

### Performance
- **Lightweight** - ~50KB total size including word list
- **Fast loading** - Optimized CSS and minimal JavaScript
- **Efficient** - Uses modern web APIs and optimized algorithms

### Contributing
Feel free to open issues or submit pull requests for improvements!

### License
Open source - feel free to use and modify as needed.

---

*Built with ❤️ for word game enthusiasts*
