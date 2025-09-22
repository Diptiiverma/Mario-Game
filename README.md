# Mario-Game
"Mario Game 🎮 | A 2D platformer where I applied DSA concepts (Dynamic Programming &amp; Greedy) to calculate the optimal path for collecting maximum coins while avoiding enemies."

🌟 Description
Help Mario collect the maximum number of coins while avoiding enemies and navigating tricky platforms!
This game combines classic platform mechanics with algorithmic problem-solving to optimize your coin collection strategy.

🚀 Features
🎲 Dynamic Platforms – Coins and enemies are randomized on each platform, making every run unique.
🕹️ Player Mechanics – Walk, jump, and fly across platforms with smooth physics.
👾 Enemy Interactions – Jump on enemies to defeat them or avoid collisions.
💡 Core Optimization – Algorithm calculates the optimal path to collect maximum coins.
🔁 Replayability – Each playthrough generates a different experience with coins and enemies positioned differently.
🧠 Logic & Implementation

🧠 Logic & Implementation

The game uses Dynamic Programming + Greedy Approach for maximum coin collection:
★ Input Representation: Each platform is a 2D array, storing rewards for higher and lower platforms.

★ Decision Making:
1 → Jump to the higher platform
0 → Stay on the lower platform

★ Dynamic Programming:
ans1 → Maximum coins if Mario jumps higher
ans2 → Maximum coins if Mario stays lower
Update ans1 and ans2 for each platform to maintain maximum reward

★ Greedy Adjustment: After choosing 1, the next move is always 0 to follow game constraints.

★ Gameplay Execution: Algorithm generates a sequence of moves (0 or 1) that Mario follows automatically to maximize coin collection.

🛠️ Tech Stack
★ Frontend / Game Engine: HTML, CSS, JavaScript, Phaser.js (2D canvas rendering & physics)
★ Game Canvas: HTML5 Canvas for sprite and tile rendering
★ Animation & Physics: Phaser physics engine handles gravity, collisions, and animations
★ Algorithm: Dynamic Programming + Greedy strategy for optimal coin collection

🎓 Skills Developed
★ Graph-based Decision Making: Optimal moves for rewards
★ Dynamic Programming: Real-time application in gameplay
★ Greedy Algorithm Application: Efficient selection of moves
★ Phaser.js Game Development: Build interactive 2D games with animations
★ Physics & Collision Handling: Smooth gameplay with sprite interactions
