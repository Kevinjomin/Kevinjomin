![image](..\src\Polucity\Polucity_gif.gif)
## 🎮 About the game

PoluCity is a city-building game where you are tasked to construct and manage a sustainable city. As you develop and expand your city, you must carefully monitor and control air pollution levels. The game aims to raise awareness about air pollution in a fun and interactive way.

## ⬇️ Download game
Itch.io : https://juli93.itch.io/polucity

## 👤 Developer & contributions
- Julian Putra Utama - Project Manager & Game Artist
- Kevin Jonathan Mintaryo - Game Programmer
- Ario Pratono - Game Programmer

## 💼 What I worked on
In this project, I developed a game system that dynamically manages and increments resources based on in-game time and the types of player-placed structures. The system tracks resources (coins, population, and polution level), which can increase or decrease over time, and automatically updates the game state when win or lose conditions are met.


## 🕹️ Game controls

| Key Binding       | Function          |
| ----------------- | ----------------- |
| W,A,S,D           | Camera movement   |
| Mouse click       | Place structures  |
| Esc               | Pause menu        |

## 📜 Scripts

| Script       | Function                                                  |
| ------------------- | ------------------------------------------------------------ |
| `StatsManager.cs` | Manages the amount of ingame resources and changes them based on a determined time interval. This script also checks if the game objective is fulfilled and determines win/lose condition. |
| `StatsUI.cs`  | Object to hold information from StatsManager.cs in UI format |
| `StructureManager.cs`  | Places a structure prefab on the selected position whenever the condition is fulfilled. |
| `etc`  | |