<div align="center">

# 🌻 Plants vs. Zombies

### Four worlds. Many ways to play. One Java adventure.

A desktop game inspired by **Plants vs. Zombies**, created for the Advanced Programming course at **Sharif University of Technology**.

![Java 21](https://img.shields.io/badge/Java-21-ED8B00?logo=openjdk\&logoColor=white)
![LibGDX](https://img.shields.io/badge/LibGDX-Desktop-E74C3C)
![Gradle](https://img.shields.io/badge/Build-Gradle-02303A?logo=gradle\&logoColor=white)
![Team project](https://img.shields.io/badge/Team-3%20developers-3A8D5D)

[Explore the game](#-explore-the-game) · [Features](#-features) · [Run locally](#-run-locally) · [Team](#-team)

</div>

---

## 🎮 Explore the game

Place plants, collect sun, and defend against waves of zombies across four themed chapters. The project combines graphical gameplay with account, collection, quest, and progression systems.

## 🎮 Gameplay

<p align="center">
  <img src="docs/game_play/GamePlay_Gif.gif" alt="Gameplay preview">
  <br><br>
  <a href="docs/game_play/Gameplay_Project.mp4">▶ Watch the full gameplay</a>
</p>


### Adventure worlds

|                       Ancient Egypt                       |                       Frostbite Caves                       |
| :-------------------------------------------------------: | :---------------------------------------------------------: |
|  ![Ancient Egypt](docs/screenshots/05-ancient-egypt.png)  | ![Frostbite Caves](docs/screenshots/06-frostbite-caves.png) |
|                       Big Wave Beach                      |                          Dark Ages                          |
|                           :---:                           |                            :---:                            |
| ![Big Wave Beach](docs/screenshots/07-big-wave-beach.png) |       ![Dark Ages](docs/screenshots/09-dark-ages.png)       |

### Beyond adventure

|                      Beghouled                      |                          I, Zombie                          |
| :-------------------------------------------------: | :---------------------------------------------------------: |
|   ![Beghouled](docs/screenshots/11-beghouled.png)   |     ![I, Zombie](docs/screenshots/12-izombie-board.png)     |
|                     Vasebreaker                     |                       Wallnut Bowling                       |
|                        :---:                        |                            :---:                            |
| ![Vasebreaker](docs/screenshots/13-vasebreaker.png) | ![Wallnut Bowling](docs/screenshots/14-wallnut-bowling.png) |

<details>
<summary><strong>View all other</strong> — menus, battles, collections, greenhouse, quests, and leaderboard</summary>

|                    Main Menu                    |                       Mode Selection                      |
| :---------------------------------------------: | :-------------------------------------------------------: |
| ![main-menu](docs/screenshots/01-main-menu.png) | ![mode-selection](docs/screenshots/02-mode-selection.png) |

|                    World Map                    |                       Plant Selection                       |
| :---------------------------------------------: | :---------------------------------------------------------: |
| ![world-map](docs/screenshots/03-world-map.png) | ![plant-selection](docs/screenshots/04-plant-selection.png) |

|                      Beach Battle                     |                        Dark Ages Battle                       |
| :---------------------------------------------------: | :-----------------------------------------------------------: |
| ![beach-battle](docs/screenshots/08-beach-battle.png) | ![dark-ages-battle](docs/screenshots/10-dark-ages-battle.png) |

|                        Plant Collection                       |                        Zombie Collection                        |
| :-----------------------------------------------------------: | :-------------------------------------------------------------: |
| ![plant-collection](docs/screenshots/15-plant-collection.png) | ![zombie-collection](docs/screenshots/16-zombie-collection.png) |

|                     Greenhouse                    |                   Quests                  |
| :-----------------------------------------------: | :---------------------------------------: |
| ![greenhouse](docs/screenshots/17-greenhouse.png) | ![quests](docs/screenshots/18-quests.png) |

|                     Leaderboard                     |                  News                 |
| :-------------------------------------------------: | :-----------------------------------: |
| ![leaderboard](docs/screenshots/19-leaderboard.png) | ![news](docs/screenshots/20-news.png) |

</details>

## ✨ Features

* **Four themed chapters:** Ancient Egypt, Frostbite Caves, Big Wave Beach, and Dark Ages.
* **Plant and zombie systems:** Different families, abilities, chapter enemies, and combat interactions.
* **Game simulation:** Waves, sun generation, plant food, lawn mowers, rewards, and progression.
* **Additional modes:** Vasebreaker, Wallnut Bowling, I, Zombie, and Beghouled.
* **Player systems:** Accounts, collection, greenhouse, quests, shop, leaderboard, and locally saved progress.
* **Hybrid interface:** LibGDX gameplay with command-line menu workflows.

## 🚀 Run locally

### Requirements

* **JDK 21**
* Internet access on the first run to download Gradle dependencies

The Gradle wrapper is included; a separate Gradle installation is unnecessary. Run from the repository root:

**Windows**

```powershell
.\gradlew.bat lwjgl3:run
```

**Linux / macOS**

```bash
./gradlew lwjgl3:run
```

## 🧱 Under the hood

| Path      | What it contains                                          |
| --------- | --------------------------------------------------------- |
| `core/`   | Game logic, models, controllers, persistence, and screens |
| `lwjgl3/` | Desktop launcher and runtime configuration                |
| `assets/` | Game art, audio, and other assets                         |
| `config/` | Checkstyle and PMD configuration                          |

**Stack:** Java 21 · LibGDX · Gradle · Jackson

## 👥 Team

Developed as a three-person Advanced Programming project.
*Team members are listed in alphabetical order.*

* **Ali Ariakia** — [@Hichcas](https://github.com/Hichcas)
* **Fatemeh Mostafavi** — [@AMFMICSI](https://github.com/AMFMICSI)
* **Mahdi HajEbrahimi** — [@MahdiHEbrahimi](https://github.com/MahdiHEbrahimi)
