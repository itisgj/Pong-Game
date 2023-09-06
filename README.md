# Pong Game

Welcome to the Pong Game, a classic arcade-style gaming experience implemented using the Turtle library. This README will guide you through the setup, gameplay, and customization options available in this game.

**Table of Contents**

1. Installation
2. Gameplay
3. Adding Your Own Audio Files


**Installation**

To play the Pong Game on your local machine, follow these steps:

1. **Clone the Repository:** Start by cloning this repository to your local machine using the following command:
`git clone https://github.com/itisgj/Pong-Game.git`

2. **Install Turtle:** Ensure you have Turtle installed on your machine. Also, import WinSound to play the audio files. If you don't have Turtle already, you can install it using pip:
`pip install turtle`

3. **Run the Game:** Navigate to the cloned repository's directory and run the game:
`cd Pong-Game`
`python main.py`

4. **Enjoy the Game:** Play the game by following the on-screen instructions and using the keyboard controls.


**Gameplay**

The Pong Game features two paddles and a ball, allowing two players to compete against each other. Here's a quick overview of the gameplay:

• Player 1 controls the left paddle using the W and S keys.

• Player 2 controls the right paddle using the Up Arrow and Down Arrow keys.

• The objective is to bounce the ball off your paddle and prevent it from passing you.


**Adding Your Own Audio Files**

The Pong Game includes audio files for ball bounces, wall bounces, and paddle misses. If you want to use your own audio files, follow these steps:

1. Prepare your audio files in the WAV format.
2. Replace the existing audio files in the sounds directory with your own files. Make sure to name them appropriately:

    •  `bounce.wav` for ball bounce sounds.
   
    •  `wallBounce.wav` for wall bounce sounds.
   
    •  `uff.wav` for paddle miss sounds
3. Ensure that the audio files you add have similar characteristics to the original ones in terms of duration and sound effects for a seamless gaming experience.
