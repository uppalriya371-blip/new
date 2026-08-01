Virtual Pet Simulation (Python)


📌 Overview
This project is a simple console-based Virtual Pet Simulator written in Python. The player adopts a pet and interacts with it by feeding, bathing, sleeping, and playing. Each action affects the pet’s stats—hunger, happiness, energy, cleanliness, and health. The pet’s mood also changes based on its condition. If any critical stat reaches zero, the pet dies and the game ends.

This project is perfect for beginners learning about:

Functions

Dictionaries

Loops & condition handling

Simple game logic

⭐ Features
✔ Create and name your virtual pet

✔ Track your pet’s status (energy, hunger, happiness, cleanliness, health, mood)

✔ Interact using multiple actions:

Feed

Bathe

Sleep

Play

Bark

✔ Dynamic mood updates

✔ Game-over logic when vital stats reach zero

🛠 Technologies / Tools Used
Python 3.x

Standard Python input/output (no external libraries)

🚀 Installation & Running the Project
Install Python
Download Python from: https://www.python.org/downloads/

Save the Script
Save the provided code in a file named:

virtual_pet.py

Run the Program
Open a terminal or command prompt and run:

python virtual_pet.py

🧪 Instructions for Testing
Run the game You will be prompted to enter the pet’s name.

Observe initial status The program displays all current stats.

Choose actions from the menu Test different actions (feed, bath, sleep, play, bark, check status).

Verify stat changes

Feeding increases hunger but reduces cleanliness

Bathing increases cleanliness and happiness

Sleeping restores energy

Playing increases happiness but lowers energy and hunger

Test mood changes

Low hunger → "hungry"

Low energy → "sleepy"

Low health → "sick"

Low happiness → "sad"

Low cleanliness → "irritated"

Trigger a game over Reduce any stat to 0 by repeated actions and confirm "Your pet is Dead" appears.
