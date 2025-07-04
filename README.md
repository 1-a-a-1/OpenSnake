# 🐍 OpenSnake

A Snake game. In OpenComputers.  
Why?  
Because everything else was too easy.

## 📟 What is this?

It's Snake. That game from every Nokia phone, ever.  
Except now it's running inside a pretend computer.  
Inside Minecraft.  
Running a pretend operating system.  
On a pretend screen.  
That *you* had to build.

This is OpenSnake.

## 🎮 How do I play?

1. Slap the code into your OpenComputers system.  
   Doesn’t matter how. Floppy. HDD. Quantum pigeon. You do you.

2. Run it like this:
   ```lua
   dofile("opensnake.lua")
3. Controls:

   - Arrow keys → Move
   - Q → Quit
   - R → Restart (you'll need this)

4. Objectives:

   - Consume the red dot.
   - Avoid becoming a noodle ball.
   - Repeat.

## 💾 Requirements

- OpenComputers mod (you knew that)
- A screen (any, but Tier 2+ is smarter)
- A GPU (required unless you enjoy voids)
- A keyboard (for pressing buttons, presumably)

## 🍏 Features

- Snake.
- Food.
- Collision-based failure.
- Restart loop for infinite shame.
- No menus. No settings. It just starts.

## 🧠 Internals

- Written in Lua. Not fast. Not efficient. But it works.
- Uses `term` API and `event.pull()` to simulate pain.
- Snake body = table of coordinates. Food = RNG.
- Every tick redraws the entire screen. No optimizations. Raw.

## 🧪 Bugs (or features?)

- No pause button. Consider blinking instead.
- No score saving. Your memory is the only leaderboard.
- No sound. Add your own hiss.

## 📸 Screenshots

> Black screen. Green lines. Red dot.  
> You can imagine it. Or build it and see it.

## 🪦 License

MIT. Do what you want.  
Just don't try to sell this to actual snakes.

## ✍️ Author

1-a-a-1
The one who dared to put Snake inside a computer inside a game inside a game.

---

*This is OpenSnake.  
You made the screen. Now suffer the serpent.*
