
<p align="center">
<img src=""/>   meter imagem do logo do jogo
</p>

<h1 align="center">
  LDTS_L01G07 - RunCollector
</h1>


**RunCollector** is a game where the player collects coins while navigating through levels filled with sharp spikes. The main objective is to collect as many coins as possible while avoiding obstacles that could lead to a Game Over. With increasing difficulty across levels, the game challenges the player to achieve the highest possible score.

> Developed by **Matilde Silva** (up202305722@edu.fe.up.pt), **Sérgio Almeida** (up202305946@edu.fe.up.pt), and **Tiago Almeida** (up202303450@edu.fe.up.pt) for **LDTS 2024** at **FEUP**.
---

## **IMPLEMENTED FEATURES**

* **Character Movement**:
  * `W`: Jump
  * `A`: Move left
  * `D`: Move right

* **Main Menu**:
  * Navigate with arrow keys (up and down).
  * Options:
    * **Play**: Start the game
    * **Exit**: Exit the game
    * **Levels**: Access different levels

* **User Interaction**:
  * Use `W`, `A`, `D` for in-game actions.
  * Use arrow keys for menu navigation.
  * Press `Escape` to exit the game.

* **Collision Detection**:
  * Detects when the player touches spikes, restarting the level.

* **Levels**:
  * Progressive difficulty with increasingly challenging obstacles.

---

## **PLANNED FEATURES**

* All planned features have been successfully implemented, as spikes were the only obstacles included.

---

## **GRAPHICAL INTERFACE**

* Introduced graphical elements for an enhanced user experience.

---

## **DESIGN**

### **General Structure**

* **Problem Context**:
  * Designing an interactive and dynamic environment was challenging, especially ensuring smooth movement and responsive collision mechanics.

* **Mockups in Pixel Art**:
  * Used pixel art mockups for characters, coins, obstacles, and various scenarios.
  * Character images: **16x16 pixels**.
  * Game levels: **64x64 pixels**.
    
    Characters and level design created with pixel art:
    -Menu
    -Running in Front (D)
    ![IMG-20241122-WA0041](https://github.com/user-attachments/assets/0b8ce8d4-558f-44f1-af59-c7de05402c76)
    -Running backwards (A)
    ![IMG-20241122-WA0042](https://github.com/user-attachments/assets/3948330a-c2c4-4b2c-ab3b-4f9f21d9810d)
    -Jump (W)
    ![IMG-20241122-WA0039](https://github.com/user-attachments/assets/06c21202-536e-4f2a-9ad9-141dc0c18e96)
    -Collecting coins 
    ![IMG-20241122-WA0043](https://github.com/user-attachments/assets/f2463dae-0122-4e67-853d-b8d77d8df71f)
    -Game Over
    ![IMG-20241122-WA0040](https://github.com/user-attachments/assets/39ddf583-f01e-45bb-a39c-d26bc911a4d0)


### **Design Patterns**

* **Model-View-Controller (MVC)**:
  * **Model**: Handles game logic and data management.
  * **View**: Manages graphical representation.
  * **Controller**: Handles event management and coordination.

* **Singleton**:
  * Centralized management of game state, including score, level, and progress.

* **Observer**:
  * Efficient event handling between player input and game state.

* **Command**:
  * Manages interactions between the player and the game.

* **Facade**:
  * Simplifies interaction with the **Lanterna** library for better code organization.

---

## **IMPLEMENTATION**

* The code follows object-oriented principles and leverages design patterns to ensure modularity and clarity.
  
---

## **KNOWN ISSUES**

* No significant bugs were identified during testing.

---

## **TESTING**

* Mutation testing was conducted to ensure code robustness.

---

## **RESOURCES**

* **Tools**:
  * **Lanterna**: Used for graphical interface and gameplay rendering.
    
---

## **TEAM CONTRIBUTIONS**

* **Sérgio Almeida **: ??%
* **Matilde Silva**: ??%
* **Sérgio Almeida**: ??%
