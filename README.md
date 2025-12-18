# evil-eye-game
👁️ Evil Eye Game - Escape From Monster A thrilling 2D browser-based endless runner game where you play as a motorcyclist escaping from a terrifying monster with a giant eye!

![2d_sidescrolling_video_202512180711_7y8ld-ezgif com-video-to-gif-converter-2-6](https://github.com/user-attachments/assets/7ff8277d-1683-4431-9e44-da67f793a450)
![Thirdperson_sidescrolling_video_20251218065-ezgif com-video-to-gif-converter-8](https://github.com/user-attachments/assets/da7232e9-f8f7-4500-aa75-1a1e98a8ce9c)


🎮 Game Description Run as far as you can while jumping over obstacles and escaping from the evil eye monster that's chasing you! The monster gradually speeds up, making the game increasingly challenging. ✨ Features

Simple Controls: Just press SPACE to jump Atmospheric Graphics: Dark tunnel environment with eerie lighting Progressive Difficulty: Monster speeds up as you progress Real-time Score: Track your distance in meters Smooth Physics: Realistic jump mechanics and collision detection Custom Artwork: Unique monster and motorcycle sprites

🎯 How to Play

Press SPACE to start the game Press SPACE to jump over obstacles Avoid hitting obstacles Run as far as you can before the monster catches you! Press SPACE after game over to restart

🚀 Quick Start Play Online Simply open the game in your browser - no installation required! Run Locally

Clone this repository:

bash git clone https://github.com/nikitalisin/evil-eye-game.git

Open index.html in your browser Start playing!

🛠️ Technical Details

Framework: React Styling: Tailwind CSS Game Loop: 60 FPS using setInterval Physics: Custom gravity and jump mechanics Collision Detection: Bounding box collision system

Game Parameters

Jump Force: -18 Gravity: 0.8 Game Speed: 6 pixels/frame Obstacle Spawn Rate: Every 90 frames Monster Speed: 0.3 + (score/10000) pixels/frame

🎨 Assets

Monster Sprite: Custom evil eye creature with tentacles Motorcycle Sprite: Orange motorcycle with rider Environment: Procedurally generated tunnel with atmospheric lighting

📊 Game Mechanics Physics System

Smooth jump arc with realistic gravity Ground detection and collision Jump only when on ground (no double jumps)

Difficulty Progression

Monster gradually increases speed Distance-based scoring system Consistent obstacle placement for fair gameplay

Collision Detection

Precise hitbox calculations 20-pixel margin for player sprite Bottom collision detection for obstacles

🏆 Tips & Tricks

Time your jumps carefully - the physics are realistic! Watch the monster's distance - if it gets too close, focus on survival Obstacles appear at regular intervals - find your rhythm The longer you survive, the faster the monster gets

🤝 Contributing Contributions are welcome! Feel free to:

Report bugs Suggest new features Submit pull requests Improve graphics or animations

📝 Future Features (Roadmap)

Sound effects and background music Multiple obstacle types Power-ups and collectibles Leaderboard system Different game modes Mobile touch controls More atmospheric effects Achievement system

📜 License This project is open source and available under the MIT License. 👤 Author Created by @nikitalisin 🙏 Acknowledgments

Inspired by classic endless runner games Horror aesthetic inspired by atmospheric indie games Built with React and Tailwind CSS

📞 Contact

GitHub: @nikitalisin Issues: Report a bug

Enjoy the game and try to beat your high score! 🏍️💨👁️ Game Controls Summary SPACE - Start Game / Jump / Restart System Requirements

Modern web browser (Chrome, Firefox, Safari, Edge) JavaScript enabled No additional plugins required
