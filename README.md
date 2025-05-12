<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>🐍 Retro Snake Game – C++ & raylib</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      margin: 20px;
      background-color: #f9f9f9;
      color: #333;
    }
    h1, h2, h3 {
      color: #2c3e50;
    }
    code {
      background-color: #eaeaea;
      padding: 2px 4px;
      border-radius: 4px;
      font-family: monospace;
    }
    pre {
      background-color: #eaeaea;
      padding: 10px;
      border-radius: 4px;
      overflow-x: auto;
    }
    a {
      color: #3498db;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    ul {
      list-style-type: disc;
      margin-left: 20px;
    }
    .screenshot {
      max-width: 100%;
      height: auto;
      border: 1px solid #ccc;
      margin: 10px 0;
    }
  </style>
</head>
<body>

  <h1>🐍 Retro Snake Game – C++ & raylib</h1>

  <p>A modern take on the classic Snake game, developed in C++ using the <a href="https://www.raylib.com/">raylib</a> library. This project showcases fundamental game development concepts, including object-oriented programming, real-time input handling, collision detection, and audio integration.</p>

  <h2>🎮 Features</h2>
  <ul>
    <li><strong>Smooth Gameplay</strong>: Responsive controls with arrow keys for seamless snake movement.</li>
    <li><strong>Dynamic Food Generation</strong>: Food appears at random positions, ensuring it doesn't overlap with the snake's body.</li>
    <li><strong>Collision Detection</strong>: Game ends upon collision with walls or the snake's own body.</li>
    <li><strong>Audio Feedback</strong>: Sound effects for eating food and game over events enhance the gaming experience.</li>
    <li><strong>Score Tracking</strong>: Real-time score display keeps players informed of their progress.</li>
    <li><strong>Game Over Screen</strong>: A dedicated screen informs players of the game's end and prompts for a restart.</li>
  </ul>

  <h2>🛠️ Installation & Setup</h2>

  <h3>Prerequisites</h3>
  <ul>
    <li>C++ compiler (e.g., <code>g++</code>)</li>
    <li><a href="https://www.raylib.com/">raylib</a> library installed</li>
    <li>Audio files:
      <ul>
        <li><code>Sounds/eat.mp3</code></li>
        <li><code>Sounds/wall.mp3</code></li>
      </ul>
    </li>
    <li>Image file:
      <ul>
        <li><code>Graphics/food.png</code></li>
      </ul>
    </li>
  </ul>

  <h3>Building the Project</h3>
  <ol>
    <li>Clone the repository:
      <pre><code>git clone https://github.com/yourusername/retro-snake-game.git
cd retro-snake-game</code></pre>
    </li>
    <li>Compile the project:
      <pre><code>g++ main.cpp -o SnakeGame -lraylib -lGL -lm -lpthread -ldl -lrt -lX11</code></pre>
    </li>
    <li>Run the game:
      <pre><code>./SnakeGame</code></pre>
    </li>
  </ol>
  <p><em>Note: Ensure that the <code>Sounds</code> and <code>Graphics</code> directories are in the same directory as the executable, and they contain the required files.</em></p>

  <h2>📷 Screenshots</h2>
  <p><em>Include screenshots of the game here to showcase the gameplay, start screen, and game over screen.</em></p>
  <!-- Example:
  <img src="screenshots/gameplay.png" alt="Gameplay Screenshot" class="screenshot">
  -->

  <h2>🚀 Future Enhancements</h2>
  <ul>
    <li>Implement pause and resume functionality.</li>
    <li>Introduce multiple difficulty levels.</li>
    <li>Add a high-score leaderboard.</li>
    <li>Develop a mobile version of the game.</li>
    <li>Incorporate multiplayer support.</li>
  </ul>

  <h2>🤝 Contributing</h2>
  <p>Contributions are welcome! If you have suggestions for improvements or new features, feel free to fork the repository and submit a pull request.</p>

  <h2>📄 License</h2>
  <p>This project is licensed under the <a href="LICENSE">MIT License</a>.</p>

  <h2>📬 Contact</h2>
  <p>For any inquiries or feedback, please contact <a href="mailto:yourname@example.com">yourname@example.com</a>.</p>

</body>
</html>